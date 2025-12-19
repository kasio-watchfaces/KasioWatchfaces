# KASIO – Digital Watchfaces for Samsung Tizen

## About the project

**KASIO** is a collection of digital watchfaces inspired by classic Casio-style watches,
developed for **Samsung Tizen smartwatches**.

All watchfaces are packaged as **.wgt** files and installed manually using
**Samsung Debug Bridge (sdb)**.

---

## File naming and compatibility

Each watchface filename ends with a suffix that defines **which devices it supports**:

| Suffix | Compatible devices |
|------|-------------------|
| **W**  | Gear Fit2 / Gear Fit2 Pro |
| **WE** | Gear S only |
| **WR** | Gear S2, Gear S3, Gear Sport, Galaxy Watch (2018) |

**IMPORTANT**  
Installing a watchface on the wrong device may cause crashes, scaling issues, or failure to install.

---

## Supported devices

Only **Gear Fit2 Pro** has been physically tested.
Other devices are listed as compatible but remain untested.

- Gear Fit2
- Gear Fit2 Pro – tested
- Gear S
- Gear S2
- Gear S3 (Classic / Frontier)
- Gear Sport
- Galaxy Watch (2018)

## Not supported

- Galaxy Watch Active
- Galaxy Watch Active2
- Galaxy Watch3

---

## Installation method

All watchfaces are installed using **sdb**:

```bash
sdb connect <watch_ip>
sdb install <watchface>.wgt

See the README inside your device folder for exact instructions.

Disclaimer
This project is not affiliated with Casio or any other brand or developer.
KASIO is an original project inspired by classic digital watches.
