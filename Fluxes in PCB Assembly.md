# 🔬 Fluxes in PCB Assembly (PCBA)

Flux is a **chemical cleaning agent** used in the soldering process to remove oxides from metal surfaces, promote wetting, and prevent re-oxidation during soldering.

---

## 🔖 Functions of Flux

1. 🧼 **Cleans** oxidation and contaminants from surfaces
2. 🧲 **Improves wetting** of solder to PCB pads and component leads
3. 🛡️ **Prevents re-oxidation** during soldering
4. ⚗️ **Aids solder flow** into joints

---

## 🧪 Types of Flux

| Type            | Base         | Activity Level | Cleaning Required | Typical Use Case                  |
|------------------|--------------|----------------|--------------------|----------------------------------|
| **Rosin (R)**     | Natural resin | Low            | Optional           | Hand soldering, general use      |
| **RMA**           | Rosin mildly activated | Medium         | Optional           | Balanced performance             |
| **RA**            | Rosin activated | High            | ✅ Yes            | Strong cleaning, harder to remove |
| **No-Clean**      | Synthetic organics | Low to medium | ❌ No             | SMT, wave soldering, mass prod. |
| **Water-Soluble** | Organic acid | High            | ✅ Yes            | Clean room, high-reliability     |

---

## 🔧 Flux Forms

| Form           | Description                                   | Use Case                    |
|----------------|-----------------------------------------------|-----------------------------|
| **Liquid Flux**| Applied manually or via spray/dip             | Rework, wave soldering      |
| **Flux Pen**   | Precise application during rework             | Manual touch-ups            |
| **Paste Flux** | Thick, stays in place                         | BGA rework, hand soldering  |
| **Flux Core Wire**| Solder wire with flux in center            | Hand soldering              |
| **Preform Flux**| Pre-shaped solid form for precise placement  | Specialized assembly        |

---

## ⚠️ Flux Residue Considerations

| Residue Type | Impact                                   | Action            |
|--------------|-------------------------------------------|-------------------|
| **No-Clean** | Low activity, minimal residue             | Usually left uncleaned |
| **Rosin**    | Sticky, may attract dust/moisture         | May require cleaning    |
| **RA/Water Soluble** | Corrosive, conductive if left | ✅ Must be cleaned    |

---

## 🧼 Cleaning Methods

- 💧 **Water wash** (for water-soluble flux)
- 💨 **Solvent cleaning** (for rosin-based flux)
- ♨️ **Vapor degreasing**
- 🧽 **Ultrasonic cleaning** (for sensitive boards)

---

## 📋 IPC Flux Classification (J-STD-004)

| Symbol | Meaning                        |
|--------|--------------------------------|
| **R**  | Rosin                          |
| **OR** | Organic                        |
| **RE** | Resin                          |
| **L**  | Low activity                   |
| **M**  | Moderate activity              |
| **H**  | High activity                  |
| **0**  | No halides (<0.05%)            |
| **1**  | Halides present (≥0.05%)       |

**Example**: ROL0 → Rosin, Low activity, No halides

---

## 🔐 Best Practices

- ✅ Select flux based on soldering method and reliability needs
- ✅ Avoid excess flux – may cause dendrite formation or corrosion
- ⚠️ Clean high-activity or water-soluble flux residues
- 🚫 Do not mix incompatible flux types

---

> 💡 **Tip**: Flux residue, if not managed properly, can lead to **electrical leakage**, **corrosion**, and **conformal coating issues**.

