# ✈️ Flying Probe Test (FPT) in PCBA

**Flying Probe Test (FPT)** is a type of **electrical test** used to verify the integrity of PCB assemblies **without requiring a custom fixture**. It uses movable probes that “fly” across the board to test points, making it ideal for **low-to-medium volume production**, prototypes, and complex boards.

---

## 🛠️ What It Tests

| Test Area               | Description                                |
|-------------------------|--------------------------------------------|
| 🔌 **Open circuits**    | Detects missing or broken connections       |
| 🔧 **Short circuits**   | Identifies unintended connections           |
| 📏 **Component values** | Resistors, capacitors, inductors           |
| ⚡ **Voltage levels**   | Power and signal voltages                  |
| 🧪 **Diode/transistor** | Forward/reverse bias testing                |
| 🔄 **Polarity**         | Confirms correct component orientation      |

---

## 🔍 How It Works

- Uses **two or more robotic probes** mounted on arms that move over the board
- Controlled via **CAD or Gerber files**
- Probes contact test pads, vias, or exposed pins
- Test points are probed in sequence based on the netlist

🌀 No **bed-of-nails fixture** is required — this makes setup **faster and cheaper** for small runs.

---

## ✅ Advantages

| Benefit                        | Details                                      |
|--------------------------------|----------------------------------------------|
| 🧪 **No fixture needed**       | Saves cost and time in prototyping           |
| 🔁 **Reprogrammable**         | Easy to change test sequence for new revs    |
| 🎯 **High test coverage**     | Can test hard-to-access points               |
| 📉 **Cost-effective**         | Ideal for low-volume production              |
| 🧠 **Intelligent debugging**  | Helps with design validation & DFM feedback  |

---

## ❌ Limitations

| Limitation                     | Description                                  |
|--------------------------------|----------------------------------------------|
| 🐢 **Slower than ICT**         | Sequential probing is time-consuming         |
| 🚫 **Not ideal for high-volume** | ICT is preferred for mass production        |
| ⚡ **Limited power tests**     | Cannot test full operational functionality   |
| 📏 **Access required**         | Needs exposed test points or vias            |

---

## 📊 Flying Probe vs ICT

| Feature                  | Flying Probe Test             | In-Circuit Test (ICT)           |
|--------------------------|-------------------------------|----------------------------------|
| Fixture Required         | ❌ No                          | ✅ Yes (bed-of-nails)           |
| Test Speed               | 🐢 Slower                     | ⚡ Faster                        |
| Setup Time               | ⏱️ Short                     | 🛠️ Long                          |
| Best For                 | Prototypes, low-volume        | High-volume, mature designs     |
| Test Coverage            | ✅ High (fine pitch)          | ✅ High (if access is good)      |
| Test Type                | Structural & basic electrical | Structural & functional          |

---

## 🧾 Test Output

- PASS/FAIL for each net
- Resistance, capacitance, diode values
- Shorts/open report
- Probe coordinates & component ID
- Log files for traceability

---

## 🏁 Summary

The **Flying Probe Test** is a **flexible, fixtureless** electrical test method widely used in:

- Prototype validation
- NPI (New Product Introduction)
- Low-volume/high-mix PCB assembly

It complements other tests like ICT, AOI, and functional testing, especially when fixture cost or board access is a concern.
