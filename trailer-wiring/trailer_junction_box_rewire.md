# Trailer Ground Wire Rebuild + Full Junction Box Repair  
**Project Type:** Trailer Electrical System Ground & Junction Box Restoration  
**Location:** 5940 Fairmount Avenue, San Diego County, California  
**Date:** June 25, 2024  
**Technician:** Tomas Nauckunas  
**Trailer:** Rocksolid 24ft Enclosed Cargo Trailer  
**Tow Vehicle:** Ford F-250 Super Duty  

---

## ⚠️ Issue Summary

After a full trailer lighting failure was diagnosed (see [`trailer_light_fault.md`](trailer-wiring/trailer_light_fault.md)), the root cause was confirmed as:
- **Burned internal wiring**
- **Melted or compromised ground wire**
- **Faulty junction box with unshielded entry points**

All rear and side marker lights were dead. System grounding had been disrupted across the lighting loop. Power from the tow vehicle was arriving but had no closed loop to complete the circuits.

---

## 🛠️ Repair Steps

### 🔧 1. Ground Wire Rebuild
- Old, burned ground wire was fully **cut, removed, and measured**.
- Pulled fresh **white 12 AWG ground wire** through junction path.
- Grounded directly to trailer frame with stainless bolt and crimped eyelet.

### 📦 2. Junction Box Replacement
- Removed melted plastic box and all burned terminals.
- Installed new **weather-resistant junction box** with rubber-sealed grommets.
- Re-terminated all 7 wires using heat shrink ring terminals, color-coded to standard:
  - Yellow → Left Turn  
  - Green → Right Turn  
  - Brown → Tail  
  - Red → Brake  
  - Blue → Electric Brakes  
  - White → Ground  
  - Black → Auxiliary 12V

- Wrapped wire entry bundles with **split loom tubing** and secured with zip ties + screw-mounted clamps.

---

## 🧪 Final Testing

- Lights tested individually:
  - Left/Right blinkers ✅  
  - Brake lights ✅  
  - Night tail lights ✅  
  - Marker + side lights ✅  
- Used multimeter to confirm clean voltage loop between tow vehicle → junction → trailer rear assembly.
- No heat buildup, no flickering, no exposed copper.

---

## 📸 Visuals

### 🔥 Before – Ground Damage + Open Harness  
![Burned junction box with exposed leads](https://github.com/tnauckunas/multi-domain_field_repair_logs/blob/main/assets/trailer-wiring/Wire%20Cut%20Measured.jpg?raw=true)

---

### ✅ After – Fully Repaired Junction & Secured Loom  
![Fully restored junction with proper protection](https://github.com/tnauckunas/multi-domain_field_repair_logs/blob/main/assets/trailer-wiring/Fully%20Repaired.jpg?raw=true)

---

### 🎥 Final Light System Verification  
**Video:** [Full Lighting System Test – All Functions Pass](https://github.com/tnauckunas/multi-domain_field_repair_logs/assets/trailer-wiring/final_lights_working_demo.mp4) *(upload video here and link it when ready)*

---

## ✅ Final Outcome

Trailer electrical system was restored to safe working condition. Ground fault eliminated. New junction box fully sealed and future-proofed. Trailer passed live road test and inspection.

---

## 🧠 Notes & Lessons Learned

- Never trust old heat-shrunk boxes without grommets — they cook internally over time.
- Grounding must always bolt directly to frame **with clean metal-to-metal contact** — painted chassis will cause system failure.
- Always reinforce new junctions with wire loom + physical strain relief.

---

## 🔗 Related Logs

- [`trailer_light_fault.md`](./trailer_light_fault.md) – Incident & Diagnosis  
- [`trailer_wiring_gallery.md`](./trailer_wiring_gallery.md) – Reference Diagrams & Pinouts  
