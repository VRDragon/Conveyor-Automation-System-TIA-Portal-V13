# 🏭 S7-1200 Conveyor Control

**Riadenie dopravníka programovateľným automatom Siemens S7-1200, projekt z kurzu PLC v mechatronike.**

![Rok](https://img.shields.io/badge/rok-2018-blue) ![PLC](https://img.shields.io/badge/Siemens-S7--1200-009999) ![IDE](https://img.shields.io/badge/TIA%20Portal-V13-orange) ![Typ](https://img.shields.io/badge/typ-školský%20projekt-lightgrey)

> **Rok realizácie:** 2018 · **Tagy:** `plc` `siemens` `s7-1200` `tia-portal` `industrial-automation` `conveyor` `mechatronics` `ladder-logic` `fei-stu`

## O projekte

Školský projekt z predmetu **PLC systémy v mechatronike** na FEI STU v Bratislave. Ukazuje, ako sa riadi dopravníkový systém pomocou PLC Siemens SIMATIC S7-1200: od hardvérovej konfigurácie až po logiku programu v prostredí **TIA Portal V13**.

| Parameter | Hodnota |
|---|---|
| Riadiaci systém | Siemens SIMATIC S7-1200 |
| Vývojové prostredie | TIA Portal V13 |
| Aplikácia | automatizované riadenie dopravníka |
| Inštitúcia | FEI STU Bratislava |
| Rok | 2018 |

## Obsah repozitára

```
Dopravnik/
├── Dopravnik.ap13      ← hlavný projektový súbor TIA Portalu
├── AdditionalFiles/    ← archív PLCM
└── System/             ← systémové dáta projektu
```

## Ako projekt otvoriť

1. Nainštalujte **Siemens TIA Portal V13** (alebo novší, ktorý vie projekt migrovať).
2. Otvorte `Dopravnik/Dopravnik.ap13`.
3. Program si môžete prezrieť, simulovať (PLCSIM) alebo nahrať do S7-1200.

## Poznámka

Pri otváraní v novšej verzii TIA Portalu treba počítať s migráciou projektu. Staršie anglické README je v [docs/README.en.md](docs/README.en.md).

## Autor

**Vratislav Režo** ([@VRDragon](https://github.com/VRDragon))
