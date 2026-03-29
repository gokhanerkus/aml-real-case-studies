# Entities & Network Structure

## Key Actors

### Financial Institution
- Turkish-based bank  
- Provides credit and financial instruments  

---

### Corporate Group
- Receives significant portion of financial exposure  
- Connected to multiple sectors and jurisdictions  

---

### Individuals
- Associated with international financial investigations  
- Linked to cross-border fund movements  

---

### Jurisdictions
- Turkey  
- Iran  
- UAE  
- Malaysia  
- Tajikistan  

---
```mermaid
flowchart LR

    IRAN[Iran-linked funds]
    ZANJANI[Zanjani Network]
    ZARRAB[Zarrab Network]

    BANK[Turkish Bank]
    CALIK[Corporate Group]

    UAE[UAE Entities]
    MALAYSIA[Malaysia Entities]
    TAJIK[Tajikistan Entities]

    GLOBAL[International Financial System]

    IRAN --> ZANJANI
    ZANJANI --> ZARRAB
    ZARRAB --> BANK

    BANK --> CALIK

    BANK --> UAE
    BANK --> MALAYSIA
    BANK --> TAJIK

    UAE --> GLOBAL
    MALAYSIA --> GLOBAL
    TAJIK --> GLOBAL


    ## Interpretation

This diagram illustrates the flow of funds from Iran-linked sources through intermediary networks into the Turkish banking system, followed by distribution across multiple jurisdictions.

Key observations:

- Central role of the financial institution in enabling fund movement  
- Use of intermediary actors to obscure origin  
- Distribution of funds across multiple jurisdictions (UAE, Malaysia, Tajikistan)  
- Integration into the international financial system  

➡️ This structure is consistent with **layering and sanctions evasion typologies**


➡️ The structure reflects a multi-jurisdictional layering strategy designed to obscure fund origin and reduce detection risk.
