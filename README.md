## Hi there 👋

### 👨‍💻 Senior ERP Technical Architect | Dynamics 365 F&O & AX Expert
Sono uno sviluppatore specializzato nella modernizzazione di processi in **Microsoft Dynamics 365 Finance & Operations** e versioni precedenti come **AX 2012** e **AX 2009**. Ho lavorato su praticamente tutti i moduli della piattaforma, con una particolare specializzazione nell'area **Finance**. Esperto in progettazione di architetture cloud-native per l'ecosistema Microsoft Dynamics

---

### 🚀 Cosa faccio

- 💼 Sviluppo su **Dynamics 365 F&O**, AX 2012 e AX 2009 (con focus sul modulo Finance)
- ⚙️ Utilizzo estensivo di **C#** e **Azure Functions**, inclusi orchestratori (Durable Functions)
- 🔗 Progettazione e sviluppo di **integrazioni** tra Dynamics e sistemi esterni come **ServiceNow** e applicativi custom di terze parti
- 🔄 **Migrazioni dati** da SAP a Dynamics
- ☕ Conoscenza di **Java EE** maturata in esperienze lavorative precedenti
- 🌐 Gestione di un sito di notizie in **PHP**: [parisnews.it](http://www.parisnews.it/)

---

## 🏗️ Architettura di Integrazione Enterprise
Progetto flussi di dati resilienti tra ERP e sistemi esterni (ServiceNow, SAP, Custom Apps) utilizzando il paradigma **Serverless**:

graph LR
    subgraph ERP [D365 F&O / AX]
        A[Business Logic] -->|OData / Service Bus| B(Integration Layer)
    end

    subgraph Azure [Azure Middleware]
        B --> C{Durable Functions}
        C --> D[C# Mapping]
        C --> E[C# Connector]
    end

    subgraph External [External Target]
        E --> F[ServiceNow]
        E --> G[SAP / Custom API]
    end

    style C fill:#0078d4,stroke:#333,stroke-width:2px,color:#fff
    style A fill:#002050,stroke:#333,stroke-width:2px,color:#fff
    style F fill:#293e40,stroke:#333,stroke-width:2px,color:#fff

---

### 📝 Blog tecnico

Ho creato un blog tecnico dove condivido le mie scoperte nel mondo Dynamics e C#:

🔗 [dyn365.it](https://www.dyn365.it/)

---

### 🛠️ Tecnologie & Strumenti

![Dynamics 365](https://img.shields.io/badge/Dynamics%20365-0078D4?style=flat&logo=microsoft&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=csharp&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![Java](https://img.shields.io/badge/Java%20EE-ED8B00?style=flat&logo=openjdk&logoColor=white)
![SAP](https://img.shields.io/badge/SAP-0FAAFF?style=flat&logo=sap&logoColor=white)
