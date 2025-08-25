# ETHkipu-Project1
# 🛡️ Demonstration of a Multisig Wallet on Safe

This repository demonstrates the creation and usage of a **multisignature (multisig) wallet** on [Safe (formerly Gnosis Safe)](https://safe.global/).  
The configuration used was **3 wallets in total, requiring 2 signatures to execute transactions**.  

Each step is documented with screenshots to make the process easy to follow.  

---
## 🔑 Safe Multisig Address
https://sepolia.etherscan.io/address/0x72f4cfeb3622EE37210685BEA61a76C325E6B27e

---

## 🔑 Creating the Multisig
In this step, we configured the multisig wallet with 3 owners and the requirement of 2 signatures.  

- Start of creation  
- Setting the name and network  
- Adding the owners  
- Defining the required number of signatures  
- Reviewing and creating the wallet  

![Create-1](images/CreateMultiSig_1.png)  
![Create-2](images/CreateMultiSig_2.png)  
![Create-3](images/CreateMultiSig_3.png)  
![Create-4](images/CreateMultiSig_4.png)  
![Contract](images/ContractMultiSig.png)

---

## 📤 Executing Transactions
In this step, we executed a transaction showing how multiple signatures are required.  

- Initiating a transaction  
- Setting the recipient and amount  
- Reviewing the transaction  
- First signature  
- Status waiting for another signature  
- Second signature  
- Automatic transaction execution  

![Transaction-1](images/Transaction_1.png)  
![Transaction-2](images/Transaction_2.png)  
![Transaction-3](images/Transaction_3.png)  
![Transaction-4](images/Transaction_4.png)  
![Transaction-5](images/Transaction_5.png)  
![Transaction-6](images/Transaction_6.png)  
![Confirmation-1](images/Confirmation_1.png)  
![Confirmation-2](images/Confirmation_2.png)  
![Confirmation-3](images/Confirmation_3.png)  
![Confirmation-4](images/Confirmation_4.png)  
![Confirmation-5](images/Confirmation_5.png)  
![Confirmation-6](images/Confirmation_6.png)  
![Confirmation-7](images/Confirmation_7.png)  
![Confirmation-8](images/Confirmation_8.png)  
![Confirmation-9](images/Confirmation_9.png)  
![Confirmation-10](images/Confirmation_10.png)  
![Execute-1](images/Execute_1.png)  
![Execute-2](images/Execute_2.png)  
![Execute-3](images/Execute_3.png)  
![Execute-4](images/Execute_4.png)  

---

## 📜 Transaction History
All operations are recorded, ensuring transparency and auditability.  

- Transaction list  
- Details of signatures and status  

![HistoryTransaction-1](images/HistoryTransaction_1.png)  
![HistoryTransaction-2](images/HistoryTransaction_2.png)  
![HistoryTransaction-3](images/HistoryTransaction_3.png)  

---

## 🧩 Management and Settings
The multisig allows for security adjustments and participant management.  

- Owner management (add/remove wallets)  
- Security configurations  
- General Safe dashboard  

![Config 1](images/Configuration_1.png)  
![Config 2](images/Configuration_2.png)  
![Config 3](images/Configuration_3.png)  

---

# 📚 Conclusion
This repository shows how to configure and operate a **multisig wallet** on Safe, providing greater security for transactions and shared asset management.  
The **2-of-3 signature setup** ensures flexibility while protecting against failures or unauthorized access.  
