# Fraud-Detection-Classification-Model
This notebook presents models generated from sklearn and imbalance learn libraries, and compares them in order to rank the best models according to their ability to identify whether a bank transaction is fraudulent.

The database that will be used to develop this challenge contains approximately 6.3 million transactions. The data contained in this database is simulated and comprises 30 days. These transactions can be of different types and were executed via mobile devices. The features contained in this database are:

step - Step: represents the total hours elapsed since the beginning of the simulation. This feature will vary between 1 and 744 (30 days);

type - Type: transaction type (deposit, withdrawal, debit, payment, and transfer);

amount - Amount: total that was transacted;

nameOrig - CustomerOrigin: the customer who initiated the transaction

oldbalanceOrg - OriginalBalanceOrigin: balance of the original account before the transaction;

newbalanceOrig - BalanceOrigin: balance of the original account after the transaction;

nameDest - ClienteDestino: target client of the transaction;

oldbalanceDest -DestinationInitialBalance: balance of the destination account before the transaction;

newbalanceDest - SaldoFinalDestino: balance of the destination account after the transaction;

isFraud - ÉFraud: flag that defines whether the transaction is fraudulent or not. In this simulation, the purpose of the fraud is to take over the user's account, empty it by transferring it to another account, and then withdraw the money.

isFlaggedFraud - FlaggedAsFraud: automatically flagged by the bank as fraud for trying to transfer more than 200,000 in a single transaction.
