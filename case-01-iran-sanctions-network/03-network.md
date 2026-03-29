# Network Diagram

```mermaid
graph LR

Zanjani[Sanctioned Individual<br>Babak Zanjani]
Zarrab[Financial Intermediary<br>Reza Zarrab]
Shams[Intermediary<br>Mahdi Shams]
Onur[Onur Air<br>Turkey]
Qeshm[Qeshm Air<br>Iran-linked]

Zanjani --> Qeshm
Zanjani --> Zarrab
Zarrab --> Shams
Shams --> Onur
Onur --> Qeshm
