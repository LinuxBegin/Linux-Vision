
### Vendors:-

#### 1. CPU:-  
**Best:**
- AMD Ryzen 5000/7000 series
- AMD Ryzen Threadripper

**Good:**
- Intel Core 12th/13th gen (needs kernel 6.2+)

**Avoid:**
- Intel 14th gen (immature support)

#### 2. GPU:-
**Best (Open-Source Drivers):**
- AMD Radeon RX 6000/7000 series
- AMD Radeon Pro

**Good (Open-Source, Newer):**
- Intel Arc A-series
- Intel Arc B-series (needs kernel 6.12+)

**Works (Proprietary):**
- NVIDIA GeForce RTX (requires nvidia-driver)

**Avoid:**
- NVIDIA on Wayland (issues)
- Brand new GPUs without kernel support

#### 3. Motherboard:-
**Chipsets:**
- AMD: B650, X670 (AM5)
- Intel: B760, Z790 (LGA 1700)

**Brands (All Equal):**
- ASUS
- MSI
- Gigabyte
- ASRock (slower BIOS updates)

**Key:** Look for Intel WiFi/Ethernet, not Realtek

#### 4. RAM:-
**All work identically:**
- Kingston
- Crucial
- Corsair
- G.Skill
- Teamgroup

**Specs that matter:**
- DDR5-5600+ (AM5/LGA 1700)
- DDR4-3200+ (older platforms)
- 32GB for your use case

#### 5. Storage:-
**All work perfectly:**
- Samsung (980 Pro, 990 Pro)
- Western Digital (Black SN850X)
- Crucial (P5 Plus, P3 Plus)
- SK hynix (Platinum P41)
- Sabrent Rocket

**Note:** All NVMe SSDs work on Linux, brand irrelevant.

#### 6. PSU:-
**Tier S:**
- Seasonic (Focus, Prime)
- Super Flower

**Tier A:**
- Corsair (RM, RMx)
- EVGA (SuperNOVA)
- MSI (MAG)
- be quiet! (Pure Power, Straight Power)

**Minimum:** 650W, 80+ Gold, 5-year warranty
**Note:** Linux doesn't care about PSU brand

#### 7. WiFi / Network:-
**Best:**
- Intel WiFi 6/6E (AX200, AX210)
- Intel Ethernet (I225-V, I219-V)

**Avoid:**
- Realtek WiFi (inconsistent)
- Broadcom WiFi (proprietary)
- Killer WiFi (problematic)

#### 8. Case:-
**Linux doesn't care:**
- Any ATX/mATX case
- Prioritize airflow over RGB

#### 9. Peripherals:-
**Mouse/Keyboard:**
- All USB HID devices work
- Avoid devices requiring Windows-only software
- Logitech: works without software
- Razer: partial support (OpenRazer project)

**Monitors:**
- All work via HDMI/DisplayPort
- No vendor restrictions

