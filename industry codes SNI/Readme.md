This is a folder with documentation and crosswalks between different SNI versions  
There is also some stata code (do-files) that can be uesful when harmonizing between years where different versions of SNI are used

# Swedish Standard Industrial Classification (SNI)

## Overview

**SNI** (*Svensk Näringsgrensindelning*) is the Swedish Standard Industrial Classification system.  
It is used to classify companies and workplaces by the type of activity they carry out, enabling comparison across time, industries, and countries.

- Maintained by **Statistics Sweden (SCB)**  
- Aligned with the **EU’s NACE classification system**  
- Used in statistics, administration, and business registration  
- Companies may have **multiple SNI codes** if they operate in several areas  

---

## Structure

SNI is hierarchical, with multiple levels of detail:

- **Sections** (1-letter codes, e.g. A = Agriculture)  
- **Divisions** (2 digits, e.g. 01 = Crop and animal production)  
- **Groups**  
- **Classes**  
- **Sub-classes / detailed groups**  

---

## Versions

| Version      | Period               | Based On / EU Correspondence | Main Features |
|--------------|----------------------|------------------------------|---------------|
| **SNI 1969** | 1969–1992            | Older Swedish/ISIC systems   | 6 levels, high detail, precursor for EU alignment |
| **SNI 1992** | ~1993–2002           | NACE Rev. 1                  | Reduced to 5 levels, mergers/splits, new details |
| **SNI 2002** | 2002–2007            | NACE Rev. 1.1                | Expanded classes/groups, updates since 1992 |
| **SNI 2007** | 2008–2025 (current)  | NACE Rev. 2                  | Better EU alignment, more service-sector detail, updates for tech/environment sectors |
| **SNI 2025** | From end of 2025     | Updated NACE (post-Rev. 2)   | Adapts to modern industries, digital economy, societal changes. Some codes split/moved |

---
## Crosswalk between versions
 
| SNI92/02G | Text | Skapas utifrån följande SNI92 el. SNI2002-koder | Ingående koder SNI2007, 2-siffer | SNI2007G-Kod | Bokstavs-nivå |
|----|------|-----------------------------------------------|----------------------------------|--------------|---------------|
| 00 | Ej specificerad verksamhet | 00 | 00 | G99 | |
| 01 | Jordbruk, skogsbruk och fiske | 01–05 | 01–03 | G01 | A |
| 02 | Tillverkning och utvinning | 10–37 | 05–33 | G02 | B+C |
| 03 | Energiproduktion, vattenförsörjning och avfallshantering | 40–41, 90 | 35–39 | G03 | D+E |
| 04 | Byggverksamhet | 45 | 41–43 | G04 | F |
| 05 | Handel och kommunikation | 50–52, 60–64 | 45–47, 49–53, 58–63 | G05, G06, G08 | G+H+J |
| 06 | Finansiell verksamhet och företagstjänster | 65–72, 74 | 64–66, 68–82 | G09, G10, G11 | K+L+M+N |
| 07 | Utbildning och forskning | 73, 80 | 85 | G13 | P |
| 08 | Vård och omsorg | 85 | 86–88 | G14 | Q |
| 09 | Personliga och kulturella tjänster | 55, 91–95 | 55–56, 90–99 | G07, G15 | I+R+S+T+U |
| 10 | Offentlig förvaltning m.m. | 75, 99 | 84 | G12 | O |


## Resources

- [SCB – Swedish Standard Industrial Classification](https://www.scb.se/en/documentation/classifications-and-standards/swedish-standard-industrial-classification-sni/)  
- [Verksamt.se – Information on SNI 2025](https://verksamt.se/en/sni2025)  
- [Classification Codes – SNI](https://classification.codes/classifications/industry/sni-sweden)  

