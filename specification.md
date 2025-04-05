# Insurance Cross-Selling (ENG)

AssurePredict is a leading insurance company specializing in offering innovative solutions for risk management. This project aims to create a predictive model capable of identifying potential cross-selling opportunities for existing customers, determining those who might be interested in purchasing an additional policy for their vehicle.

**PROJECT OBJECTIVE**

The objective is to develop a machine learning model that predicts whether customers, who currently have health insurance, might be interested in subscribing to a vehicle insurance policy. The model will help AssurePredict improve the effectiveness of its cross-selling strategies and increase market penetration.

**ADDED VALUE FOR AssurePredict**
- Increase in the conversion rate for vehicle insurance sales.
- Optimization of marketing campaigns by targeting offers to customers more likely to purchase.
- Reduction in costs associated with ineffective marketing campaigns, thanks to precise targeting.

**DATASET**
The dataset contains detailed information about customers and their insurance behavior. The main features of the dataset are:

- **id**: unique identifier of the customer.
- **Gender**: gender of the customer.
- **Age**: age of the customer.
- **Driving_License**: 1 if the customer has a driving license, 0 otherwise.
- **Region_Code**: unique code of the customer's region.
- **Previously_Insured**: 1 if the customer already has vehicle insurance, 0 otherwise.
- **Vehicle_Age**: age of the vehicle.
- **Vehicle_Damage**: 1 if the customer has previously damaged the vehicle, 0 otherwise.
- **Annual_Premium**: the amount the customer must pay as an annual premium.
- **Policy_Sales_Channel**: anonymized code of the channel used for the proposal (e.g., email, phone, in-person, etc.).
- **Vintage**: days since the customer has been insured with AssurePredict.
- **Response**: 1 if the customer responded positively to the cross-selling proposal, 0 otherwise.

The goal of the model is to predict the value of **Response**.

**REQUIRED ACTIVITIES**
1. **DATASET EXPLORATION**:
Preliminary exploration of the dataset will allow for a better understanding of the distribution of features and the target variable. Specifically, the following will be analyzed:

    - The distribution of the "Response" variable to identify any imbalances between customers who accept or reject the cross-sell offer.
    - Relationships between key variables such as Annual Premium, Vehicle Age, Previously Insured, and customer response.

Added value: Accurate data exploration allows for the identification of hidden patterns and critical points that will influence the success of the predictive model.

2. **HANDLING CLASS IMBALANCE**:
The target variable "Response" might be imbalanced, with far more customers rejecting the offer than accepting it. To address this issue, the following techniques will be used:

    - Class Weights: penalizing the more frequent class in the model.
    - Oversampling or Undersampling: creating a more balanced dataset to improve the model's ability to generalize.

Added value: Properly handling class imbalance is crucial to avoid models with a high false-negative rate, thereby improving the precision of cross-selling.

3. **BUILDING THE PREDICTIVE MODEL**:
Using machine learning algorithms, a model will be built to predict the probability that a customer will respond positively to the cross-sell offer.

Added value: The predictive model will allow AssurePredict to accurately identify customers most likely to subscribe to an additional policy, thereby improving the return on investment of marketing campaigns.

**CONCLUSIONS**
This project will enable AssurePredict to leverage the potential of machine learning to effectively and precisely identify cross-selling opportunities. Adopting a data-driven approach to predicting customer responses will not only increase sales but also enhance customer satisfaction through more relevant and personalized offers.


# Cross-Selling Assicurativo (ITA)

AssurePredict è una compagnia di assicurazioni leader nel settore, specializzata nell'offrire soluzioni innovative per la gestione del rischio. Questo progetto mira a creare un modello predittivo in grado di individuare potenziali opportunità di cross-selling per clienti esistenti, identificando quelli che potrebbero essere interessati ad acquistare una polizza aggiuntiva per il loro veicolo.

**OBIETTIVO DEL PROGETTO**

L'obiettivo è sviluppare un modello di machine learning che preveda se i clienti, che attualmente hanno un'assicurazione sanitaria, potrebbero essere interessati a sottoscrivere una polizza assicurativa per il loro veicolo. Il modello aiuterà AssurePredict a migliorare l'efficacia delle proprie strategie di cross-selling e ad aumentare la penetrazione nel mercato

**VALORE AGGIUNTO PER AssurePredict**
- Aumento del tasso di conversione nelle vendite di polizze auto.
- Ottimizzazione delle campagne di marketing, indirizzando le offerte a clienti più propensi ad acquistare.
- Riduzione dei costi legati a campagne di marketing inefficaci, grazie alla targettizzazione precisa.

**DATASET**
Il dataset contiene informazioni dettagliate sui clienti e sul loro comportamento assicurativo. Le caratteristiche principali del dataset sono:

- **id**: id univoco dell'acquirente.
- **Gender**: sesso dell'acquirente.
- **Age**: età dell'acquirente.
- **Driving_License**: 1 se l'utente ha la patente di guida, 0 altrimenti.
- **Region_Code**: codice univoco della regione dell'acquirente.
- **Previously_Insured**: 1 se l'utente ha già un veicolo assicurato, 0 altrimenti.
- **Vehicle_Age**: età del veicolo
- **Vehicle_Damage**: 1 se l'utente ha danneggiato il veicolo in passato, 0 altrimenti.
- **Annual_Premium**: la cifra che l'utente deve pagare come premio durante l'anno.
- **Policy_Sales_Channel**: codice anonimizzato del canale utilizzato per la proposta (es. per email, per telefono, di persona, ecc...)
- **Vintage**: giorni da cui il cliente è assicurato con AssurePredict.
- **Response**: 1 se l'acquirente ha risposto positivametne alla proposta di cross-selling, 0 altrimenti.

L'obiettivo del modello è prevedere il valore di **Response**.

**ATTIVITA' RICHIESTE**
1. **ESPLORAZIONE DEL DATASET**:
L'esplorazione preliminare del dataset permetterà di comprendere meglio la distribuzione delle caratteristiche e delle variabili target. In particolare, si analizzeranno:

    - La distribuzione della variabile "Response", per identificare eventuali sbilanciamenti tra clienti che accettano o rifiutano l'offerta di cross-sell.
    - Le relazioni tra variabili chiave come Annual Premium, Vehicle Age, Previously Insured, e la risposta del cliente.

Valore aggiunto: Un'accurata esplorazione dei dati permette di identificare pattern nascosti e punti critici che influenzeranno il successo del modello predittivo.

2. **GESTIONE DELLO SBILANCIAMENTO DELLE CLASSI**:
La variabile target "Response" potrebbe essere sbilanciata, con molti più clienti che rifiutano l'offerta rispetto a quelli che la accettano. Per affrontare questo problema, verranno utilizzate tecniche di:

    - Class Weights: penalizzazione della classe più frequente nel modello.
    - Oversampling o Undersampling: creazione di un dataset più bilanciato per migliorare la capacità del modello di generalizzare.

Valore aggiunto: Gestire correttamente lo sbilanciamento delle classi è cruciale per evitare modelli che abbiano un alto tasso di falsi negativi, migliorando così la precisione del cross-sell.

3. **COSTRUZIONE DEL MODELLO PREDITTIVO**:
Utilizzando algoritmi di machine learning, verrà costruito un modello che predice la probabilità che un cliente risponda positivamente all'offerta di cross-sell.

Valore aggiunto: Il modello predittivo permetterà a AssurePredict di identificare con precisione i clienti più propensi a sottoscrivere una polizza aggiuntiva, migliorando così il ritorno sull'investimento delle campagne di marketing.

**CONCLUSIONI**
Questo progetto permetterà a AssurePredict di sfruttare le potenzialità del machine learning per identificare opportunità di cross-selling in modo efficace e mirato. L'adozione di un approccio data-driven per la predizione delle risposte dei clienti garantirà non solo un aumento delle vendite, ma anche una maggiore soddisfazione del cliente grazie a offerte più pertinenti e personalizzate.
