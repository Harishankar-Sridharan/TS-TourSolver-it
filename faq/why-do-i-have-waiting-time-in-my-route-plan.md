# 13. Perché ho tempi di attesa nel mio piano di giri?

L'algoritmo di ottimizzazione può introdurre tempi di attesa per questi motivi:

1. La risorsa arriva presso la sede del cliente **prima dell'orario di apertura**.
2. La risorsa raggiunge il deposito **prima che diventi operativo**.

Gli orari di apertura di clienti e depositi sono vincoli rigidi con alta priorità, quindi l'algoritmo deve rispettarli.

**Suggerimento:** Per ridurre i tempi di attesa inutili, usa il **Vincolo di Ora di Partenza Automatica** Questo strumento regola l'orario di partenza in modo che la risorsa inizi più tardi e arrivi dal cliente o al deposito al momento giusto, minimizzando i periodi di inattività in luoghi sconosciuti.
