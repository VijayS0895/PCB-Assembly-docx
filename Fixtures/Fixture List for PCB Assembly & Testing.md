# 🔩 Fixture List for PCB Assembly & Testing

A complete list of custom and standard fixtures used in SMT, THT, testing, and final assembly processes.

---

## 📦 Fixture Categories

| 🔢 No. | 🛠️ Fixture Type         | ⚙️ Purpose                        | ✅ Usage Area          |
|-------|---------------------------|----------------------------------|------------------------|
| 1     | SMT Support Fixture       | Stabilizes thin PCBs during reflow | SMT Line               |
| 2     | Wave Solder Pallet        | Masks selective areas during wave | THT Line               |
| 3     | ICT Fixture               | In-circuit testing via probes    | Testing/QA             |
| 4     | Functional Test Fixture   | Validates full board operation   | Testing/QA             |
| 5     | Depaneling Fixture        | Supports boards during cutting   | Assembly/Depaneling    |
| 6     | Conformal Coating Fixture | Prevents coating in keep-out zones | Conformal Coating Line |
| 7     | Labeling Jig              | Ensures consistent label placement | Final Packing          |
| 8     | Programming Fixture       | Firmware loading & flashing     | Testing/Programming    |

---

## 📝 Fixture Details Example

### 🔧 Fixture Name: SMT Support Fixture – Type A

- **Type**: Aluminum base with rubber pins  
- **For PCB**: Thickness < 1.2 mm  
- **Used On**: Reflow Oven Line #2  
- **Design Ref**: `SMT_FIX_001_A`  
- **Notes**: Reworkable, height adjustable  

---

### 🔧 Fixture Name: ICT Bed-of-Nails

- **Type**: Pneumatic actuated  
- **For PCB**: All 4-layer boards > 80mm  
- **Test Coverage**: >85% nets  
- **Design Ref**: `ICT_2024_MAIN_REV3`  
- **Notes**: Replace probe set every 10k uses  

---

## 🧰 Maintenance Schedule

| 🛠️ Fixture Name         | 🗓️ Frequency   | 🔄 Action Required              |
|--------------------------|----------------|---------------------------------|
| SMT Support Fixture       | Weekly         | Clean pads, check alignment     |
| ICT Fixture               | Monthly        | Probe alignment, spring test    |
| Wave Solder Pallet        | After 5 runs   | Clean flux residues             |
| Depaneling Fixture        | Bi-weekly      | Blade tension check             |

---

## 🧩 Fixture Storage Info

- 🔒 All fixtures are stored in **Fixture Cabinet #3** near Line-2
- 🧷 Each is tagged with QR codes for traceability
- 📦 Return after cleaning & inspection log entry

---

## 📸 Fixture Image Log (Optional)

| Fixture | Image |
|--------|-------|
| SMT Support Fixture | ![SMT](images/smt_fixture.jpg) |
| ICT Fixture | ![ICT](images/ict_fixture.jpg) |

---

## ✅ Notes & Version History

| 🔄 Version | ✍️ Updated By | 📅 Date | 📝 Notes |
|-----------|---------------|---------|---------|
| v1.0      | QA Team        | 2025-08-04 | Initial fixture list created |
| v1.1      | Prod. Eng.     | 2025-08-10 | Added ICT fixture details |

---

🔐 *Ensure all fixtures meet ESD-safe requirements and are tracked via internal fixture management system.*
