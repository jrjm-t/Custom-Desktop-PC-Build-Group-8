# Custom Desktop PC Build – Group 8

**Course**: CSARCH2  
**Section**: S19  
**Group Members**:  
- Name 1  
- Name 2  
- Name 3  
- Name 4  
- Tan, Jeremy James T.

---

## 1. Introduction
Briefly describe your project build (1–2 paragraphs).  
Mention: target use case (e.g., general-purpose desktop, gaming, programming, data science, etc.) and budget constraint.

---

## 2. Draft Build (PCPartPicker)
This build uses **PCPartPicker System Builder** for compatibility check. 
PCPartPicker Permalink: _________

### Summary Table 
| Component       | Model | Price (USD/Php) | Notes |
|-----------------|-------|-----------------|-------|
| CPU             | ...   | ...             | ...   |
| CPU Cooler      | ...   | ...             | ...   |
| Motherboard     | ...   | ...             | ...   |
| RAM             | ...   | ...             | ...   |
| Storage 1       | ...   | ...             | ...   |
| Storage 2       | ...   | ...             | ...   |
| Graphics Card   | ...   | ...             | ...   |
| Power Supply    | ...   | ...             | ...   |
| Case            | ...   | ...             | ...   |
| Case Fans       | ...   | ...             | ...   |
| **Total**       |       | **XXX USD/Php**     |       |

---

## 3. Local Manila Build
This build uses **locally available parts** from Manila vendors.
Google spreadsheet link: _________  

### Local Build Table
| Component       | Model | Vendor & Link      | Price (Php) | Compatibility Notes                  |
|-----------------|-------|--------------------|-------------|--------------------------------------|
| CPU             | AMD Ryzen 7 7800X3D   | [DynaQuest](https://dynaquestpc.com/products/amd-ryzen-7-7800x3d-4-2-5-0ghz-8-core-16threads-processor-tray) | 20840         | Socket LGA1700 compatible with B760M |
| CPU Cooler      | Thermalright Phantom Spirit 120 SE ARGB CPU Cooler   | [DataBlitz](https://ecommerce.datablitz.com.ph/products/thermalright-phantom-spirit-120-se-argb-cpu-cooler) | 2095         | Fits case clearance                  |
| Motherboard     | Gigabyte B650M AORUS ELITE AX (mATX)   | [DataBlitz](https://ecommerce.datablitz.com.ph/products/gigabyte-b650m-aorus-elite-ax-gaming-motherboard) | 10750         | Supports DDR5 RAM                    |
| RAM             | G.Skill Trident Z5 Neo DDR5   | [DynaQuest](https://dynaquestpc.com/products/g-skill-trident-z5-neo-rgb-32gb-2x16gb-ddr5-6000mt-s-cl30-36-36-96-1-35v-ram-desktop-memory-white-kit-of-2-f5-6000j3036f16gx2-tz5nrw) | 9540         | DDR5-5200 CL40, 2x8GB                |
| Storage 1 (NVME SSD) | Crucial P310 M.2 1TB Gen4 NVMe (2)   | [DynaQuest](https://dynaquestpc.com/products/crucial-p310-m-2-1tb-gen4-nvme-pcie-2280-ssd-ct1000p310ssd8) | 7790         | NVMe M.2 slot supported              |
| Storage 2 (SATA SSD) | Crucial MX500 2TB SATA SSD   | [DynaQuest](https://dynaquestpc.com/products/crucial-mx500-2tb-3d-nand-sata-2-5-inch-internal-ssd-ct2000mx500ssd1)   | 8540         | SATA port supported                  |
| GPU             | AMD Radeon™ RX 9060 XT 16GB GDDR6 Graphics Card   | [PC_Express](https://pcx.com.ph/products/sapphire-nitro-amd-radeon-rx-9060-xt-16gb-gddr6-graphics-card?_pos=2&_sid=6f2baaf09&_ss=r)    | 28600         | Requires 2×8-pin PCIe, PSU supports  |
| PSU             | Seasonic Focus GM-650   | [DynaQuest](https://dynaquestpc.com/products/seasonic-focus-gold-650fm-650watts-80-gold-semi-modular)   | 5190         | 650W, 80+ Bronze                     |
| Case            | Lian Li PC-O11 Dynamic White ATX TG Mid Tower Case   | [DynaQuest](https://dynaquestpc.com/products/lian-li-pc-o11-dynamic-white-secc-atx-tg-mid-tower-case)    | 8850         | ATX Mid-Tower                        |
| Case Fans       | Thermalright TL-S12-S Silent 120mm PWM Hybrid ARGB Effect Case Fan (Black, White) (3-Pack)   | [DataBlitz](https://ecommerce.datablitz.com.ph/products/thermalright-tl-s12-s-silent-120mm-pwm-hybrid-argb-effect-case-fan-black-white-3-pack)    | 1050         | 120mm, 3-pin                         |
| **Total**       |       |                    | **103245 Php** | Within budget                        |

---

## 4. Compatibility Justification
For each part, explain compatibility and choices.  
Example:  
- **CPU + Motherboard**: Baseline Computer Component; Compatible with Motherboard AM5 socket; thermal design power within capacity of CPU cooler; Supports memory controller with DDR5-5000 Motherboard capability and Memeory requirement; PCIe Gen5 lanes for Graphics Card (ready for future upgrades) with back-ward compatiblity to Gen4 devices such as with the selected GPU and memory modules.
- **CPU Cooler**: 154 mm fits within alloted Case CPU cooler clearance of 155mm; Dual-tower heatsink does not obstruct memory modules (DDR5 height complaint), thermal dissipation capacity sufficient for suggested CPU Thermal Design Power
- **RAM**: Form factor compatible with motherboard's two out of four 288-pin DIMM slots; speed compatible with motherboard's memory speed (DDR5-6000); size of each module compatible w/ DIMM capacity of each socket (32 GiB per socket); Fits 32/192 GB of the Motherboard Memory Capacity.  
- **GPU**: Compatible with the Motherboard's PCIe 4.0x16 slot; 300mm graphics card length fits within 420 mm case clearance; 2.5-slot card thickness supported by sufficient expansion slot layout; power consumption within suggested PSU capacity through PSU provided 8-pin power connectors.
- **Storage 1 (NVME SSD)**: Compatible with the Motherboard's two out of two M.2 2280 slots (5th Gen: 2580/25110 M-key and 4th Gen:2280/22110 M-key);
- **Storage 2 (SATA SSD)**: Compatible with motherboard’s one out of four SATA (Gb/s) ports; 2.5" drive form factor supported by case internal 2.5" drive bays
- **Power Supply**: Fits in case (PSU mount supports size ATX)
- **Case**: Supports micro ATX motherboard form factor; drive bays compatible with Storage 2 (2.5"), video card length (300 mm) fits in case (420 mm max), CPU cooler height (154 mm) fits in case (155 mm max), supports size of PSU (ATX)
- **Case Fans**: Fan size compatible with case fan mounts (3x120 mm fans)

---

## 5. Budget Analysis
- **Budget Limit**: ₱105,000
- **Final Total**: ₱103,245
- ✅ Within budget
- Micro ATX motherboard reduces cost but gives less space for expansion cards

---

## 6. Conclusion & Learnings
Reflections on:  
- Price differences (international vs. Manila vendors)  
- Challenges in finding stock or cheaper equivalents  
- What the group learned about PC components and system design  

---
## 7. Video pitch
- Your video link here  

## 8. References
- PCPartPicker build link
- other reference links used
- any documentation consulted

