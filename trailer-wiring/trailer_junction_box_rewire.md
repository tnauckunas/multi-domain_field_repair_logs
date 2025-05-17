# Trailer Ground Wire Rebuild + Full Junction Box Repair  
**Project Type:** Trailer Electrical System Ground & Junction Box Restoration  
**Date:** June 25, 2024  
**Technician:** Tomas Nauckunas  
**Trailer:** Rocksolid 24ft Enclosed Cargo Trailer  
**Tow Vehicle:** Ford F-250 Super Duty  

---

## Issue Summary

After a full trailer lighting failure was diagnosed (see [`trailer_light_fault.md`](https://github.com/tnauckunas/multi-domain_field_repair_logs/blob/7b1b5d0a2dd73f125dd35b2d2bf0351a40519ec0/trailer-wiring/trailer_light_fault.md), the root cause was confirmed as:
- **Burned internal wiring**
- **Melted or compromised ground wire**
- **Faulty junction box with unshielded entry points**

All rear and side marker lights were dead. System grounding had been disrupted across the lighting loop. Power from the tow vehicle was arriving but had no closed loop to complete the circuits.

---

## Repair Steps

### Step 1 – Damaged Harness Cut & Measured
- Harness was cut from the connector side to isolate melted segments.
- Measured for new wiring length before pulling replacements.

---

### Step 2 – Fuse Replacement
- Removed and inspected all inline and panel fuses.  
- Replaced two blown 15 A blade fuses in the tow‐vehicle connector.  
- Verified continuity and correct amperage ratings before reinstalling.

---

### Step 3 – Junction Box Rebuild
- Removed melted junction box and all burned terminals.  
- Installed new weather-resistant box with rubber grommets.  
- Re-terminated all 7 wires using heat-shrink ring terminals, color-coded to standard:
  - **Yellow →** Left Turn  
  - **Green →** Right Turn  
  - **Brown →** Tail  
  - **Red →** Brake  
  - **Blue →** Electric Brakes  
  - **White →** Ground  
  - **Black →** Auxiliary 12 V  

- Wrapped wire entries in split-loom tubing and secured with zip-ties + screw-mounted clamps.

---

## Final Testing

- Lights tested individually:
  - Left/Right blinkers 
  - Brake lights 
  - Night tail lights 
  - Marker + side lights 
- Used multimeter to confirm clean voltage loop between tow vehicle → junction → trailer rear assembly.
- No heat buildup, no flickering, no exposed copper.

---

## Visuals Documentation

### Before – Ground Damage + Open Harness  
![Burned junction box with exposed leads](https://github.com/tnauckunas/multi-domain_field_repair_logs/blob/main/assets/trailer-wiring/damaged_harness_exposed.jpg?raw=true)

---

### During – Junction Box Rebuilt with Fresh Terminations  
![New junction box with loom and terminals](https://github.com/tnauckunas/multi-domain_field_repair_logs/blob/main/assets/trailer-wiring/trailer_ground_fix.jpg?raw=true)

> Full re-termination of all 7 wires into new waterproof junction. Strain reliefs added. Heat-shrink and loom used for long-term durability.

---

### After – Fully Repaired Junction & Secured Loom  
![Fully restored junction with proper protection](https://github.com/tnauckunas/multi-domain_field_repair_logs/blob/main/assets/trailer-wiring/Fully%20Repaired.jpg?raw=true)

---

### Final Light System Verification
**Video:** [Full Lighting System Test – All Functions Pass](https://github.com/tnauckunas/multi-domain_field_repair_logs/blob/bfba1c388dce2dba971dbffe13eafb74a8c525ae/assets/trailer-wiring/rear_lights_working.mp4?raw=true)

---

## Final Outcome

Trailer electrical system was restored to safe working condition. Ground fault eliminated. New junction box fully sealed and future-proofed. Trailer passed live road test and inspection.

---

## Notes & Lessons Learned

- Never trust old heat-shrunk boxes without grommets they cook internally over time.
- Grounding must always bolt directly to frame **with clean metal-to-metal contact** painted chassis will cause system failure.
- Always reinforce new junctions with wire loom + physical strain relief.

---

## Related Logs

- [`trailer_light_fault.md`](https://github.com/tnauckunas/multi-domain_field_repair_logs/blob/6cd1208712d06fa08eacfed157040fef7d37ec42/trailer-wiring/trailer_light_fault.md)  – Incident & Diagnosis 
- [`trailer_wiring_gallery.md`](https://github.com/tnauckunas/multi-domain_field_repair_logs/blob/fad056f448a11c1a518a7b821cbe1745301125fd/trailer-wiring/trailer_wiring_gallery.md) – Reference Diagrams & Pinouts  

---

_Last Updated: **May 2025**_
