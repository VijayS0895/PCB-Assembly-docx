# 🔧 BGA Reballing Process Guide

**Ball Grid Array (BGA) Reballing** involves removing old solder balls from a BGA chip and replacing them with new ones to restore proper electrical contact when re-soldering to a PCB.

---

## 🛠️ When is BGA Reballing Needed?

- ♻️ Reusing salvaged BGA components
- 🔥 Overheating or damaged solder joints
- ❌ Cold solder joints or intermittent connections
- 🔁 Changing alloy type (e.g., leaded ↔️ RoHS)

---

## 📦 Required Tools & Materials

| Item                       | Purpose                            |
|----------------------------|-------------------------------------|
| **Hot air rework station** | Controlled heating/removal         |
| **Soldering flux**         | Improves solder wetting            |
| **BGA reballing stencil**  | Aligns solder balls                |
| **Solder balls**           | (Leaded or lead-free, 0.3–0.76mm)  |
| **Vacuum pickup pen**      | Handles BGA chips safely           |
| **Pre-heater (optional)**  | Prevents warping of BGA or PCB     |
| **Microscope**             | For inspection                     |
| **Solder wick + iron**     | Removes old solder residues        |
| **Cleaning solution**      | IPA or flux remover                |

---

## 🔄 Reballing Procedure

### Step 1️⃣ – **Remove BGA from PCB**
- Use **hot air** (around 220–260°C) and vacuum pickup
- Gently lift when solder melts

### Step 2️⃣ – **Clean BGA Pads**
- Use **solder wick** and flux to remove old solder
- Clean with **IPA** and inspect under microscope

### Step 3️⃣ – **Apply Reballing Stencil**
- Place stencil on BGA chip (align precisely)
- Apply a small amount of **tacky flux**

### Step 4️⃣ – **Place Solder Balls**
- Pour solder balls over stencil
- Shake gently to let them sit in holes
- Remove excess balls

### Step 5️⃣ – **Reflow Solder Balls**
- Place BGA + stencil on hot plate or reflow station
- Heat to ~220°C (leaded) or ~245°C (RoHS) until balls melt
- Cool down gradually

### Step 6️⃣ – **Remove Stencil & Inspect**
- Peel off stencil carefully
- Inspect for ball bridging or missing balls

### Step 7️⃣ – **Clean & Reuse**
- Clean residual flux
- Store reballed BGA in ESD-safe container

---

## 📋 Tips for Success

- ✅ Use **high-quality flux** to prevent voids
- ✅ Handle BGA with **anti-static tweezers**
- ✅ Use **correct solder ball size**
- ✅ Allow gradual **cool-down** to prevent cracks
- ✅ Always **inspect under microscope** before re-use

---

## ⚠️ Common Issues

| Issue                     | Cause                                  |
|---------------------------|-----------------------------------------|
| Ball bridging             | Excess flux, poor stencil alignment     |
| Ball missing              | Insufficient ball volume or misaligned |
| Uneven balls              | Uneven heating or poor reflow profile  |
| Solder not wetting pads   | Oxidized pads or poor flux             |

---

## 📸 Visual Reballing Workflow (optional poster)

1. 🔥 Remove BGA →  
2. 🧼 Clean chip pads →  
3. 📏 Align stencil →  
4. ⚪ Apply balls →  
5. 🔥 Reflow →  
6. 👁️ Inspect →  
7. ✅ Store for reuse

---

> 💡 **Note**: Leaded solder balls (Sn63Pb37) melt at ~183°C; RoHS (e.g., SAC305) melt at ~217°C. Use a compatible reflow profile.

