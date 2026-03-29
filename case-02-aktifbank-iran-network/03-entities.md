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

