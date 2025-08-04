# 🖨️ Stencil in PCB Assembly (PCBA)

A **stencil** is a critical tool used in the **Surface Mount Technology (SMT)** process of PCB assembly. It enables precise application of **solder paste** onto the PCB pads before component placement.

---

## 🧾 Purpose of a Stencil

- To **deposit solder paste** onto the correct pads on a PCB
- Ensure consistent **paste volume**, height, and shape
- Improve **reliability** and **repeatability** of the soldering process

---

## 🏗️ Types of Stencils

| Type               | Description                                                  |
|--------------------|--------------------------------------------------------------|
| **Frameless**      | Flexible, cost-effective; used in prototype or low-volume    |
| **Framed**         | Rigid aluminum frame; used in high-volume production         |
| **Prototype**      | Low-cost, laser-cut; often for manual printing               |

---

## ✂️ Manufacturing Methods

| Method         | Detail                                                |
|----------------|-------------------------------------------------------|
| **Laser-cut**  | Most accurate; used for fine-pitch components         |
| **Electroform**| High precision; used in BGA and QFN applications      |
| **Chemical Etch** | Cost-effective; less precise than laser             |

---

## 📐 Key Design Parameters

- **Aperture size**: Must match pad dimensions
- **Stencil thickness**: Affects solder volume (typically 0.1 mm to 0.2 mm)
- **Aspect ratio**: Aperture width / stencil thickness (should be >1.5)
- **Area ratio**: Aperture area / sidewall area (should be >0.66)

---

## 🔧 Stencil Printing Process

1. **Align** stencil with PCB pads
2. **Apply solder paste** using a squeegee
3. **Lift stencil** to leave solder paste on pads
4. **Place components** using pick-and-place machine
5. **Reflow soldering**

---

## 🧼 Maintenance and Cleaning

- Clean stencil after every few prints to avoid bridging or defects
- Use **ultrasonic cleaners** or **manual wipes** with IPA

---

## ⚠️ Common Issues

| Issue               | Cause                               | Solution                          |
|---------------------|--------------------------------------|-----------------------------------|
| Insufficient paste  | Clogged aperture, wrong thickness    | Proper cleaning, correct design   |
| Solder bridging     | Excess paste or stencil misalignment | Adjust design or alignment        |
| Paste smearing      | Worn-out squeegee, low tension       | Replace squeegee, clean stencil   |

---

## ✅ Summary

- Stencils are **essential** for accurate solder paste deposition.
- Choosing the **right type and design** directly affects PCBA yield and quality.
- **Proper maintenance** ensures consistent performance.

