# ETHkipu-Project1
# 🛡️ Demonstração de Carteira Multisig na Safe

Este repositório demonstra a criação e utilização de uma **carteira multisig (multiassinatura)** na [Safe (antiga Gnosis Safe)](https://safe.global/).  
A configuração utilizada foi **3 carteiras no total, exigindo 2 assinaturas para execução de transações**.  

Cada etapa está documentada com capturas de tela para facilitar o entendimento.  

---

## 🔑 Criação da Multisig
Durante esta etapa, configuramos a carteira multisig com 3 owners e exigência de 2 assinaturas.  

- Início da criação  
- Definição do nome e rede  
- Adição dos owners  
- Definição das assinaturas necessárias  
- Revisão e criação da carteira  

![Create-1](images/CreateMultiSig_1.png)  
![Create-2](images/CreateMultiSig_2.png)  
![Create-3](images/CreateMultiSig_3.png)  
![Create-4](images/CreateMultiSig_4.png)
![Contract](images/ContractMultiSig.png)

---

## 📤 Execução de Transações
Nesta etapa, realizamos uma transação demonstrando como as assinaturas são necessárias para execução.  

- Início de uma transação  
- Definição do destinatário e valor  
- Revisão da transação  
- Primeira assinatura  
- Status aguardando outra assinatura  
- Segunda assinatura  
- Execução automática da transação  

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
![Confirmation-9](images/Confirmation_10.png)
![Execute-1](images/Execute_1.png)
![Execute-2](images/Execute_2.png)
![Execute-3](images/Execute_3.png)
![Execute-4](images/Execute_4.png)


---

## 📜 Histórico de Transações
Todas as operações ficam registradas, permitindo transparência e auditoria.  

- Lista de transações  
- Detalhes de assinaturas e status  

![HistoryTransaction-1](images/HistoryTransaction_1.png)  
![HistoryTransaction-2](images/HistoryTransaction_2.png)  
![HistoryTransaction-3](images/HistoryTransaction_3.png)  


---

## 🧩 Gestão e Configurações
A multisig permite ajustes de segurança e gerenciamento de participantes.  

- Gestão de owners (adicionar/remover carteiras)  
- Configurações de segurança  
- Painel geral da Safe  

![Config 1](images/Configuration_1.png)  
![Config 2](images/Configuration_2.png)  
![Config 3](images/Configuration_3.png)  

---

# 📚 Conclusão
Este repositório mostra como configurar e operar uma **carteira multisig** na Safe, garantindo maior segurança em transações e gestão compartilhada de ativos.  
A configuração de **2 de 3 assinaturas** garante flexibilidade e proteção contra falhas ou acessos indevidos.  
