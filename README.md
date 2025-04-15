View this project on [CADLAB.io](https://cadlab.io/project/29049). 

# EL COMBUSTIBLE

## Autors
- Raúl Carod (RaulCarod)
- Sergi Pacheco (sergipacheco55)

## Versió - v1.0 ## Curs - Assignatura de Disseny de PCBs amb KiCad - [Curs 2024-2025]

## Objectiu Descripció breu de l'objectiu del projecte.
L'objectiu del projecte és crear una pcb capaç de controlar el mecanisme de tancament de dipòsit del combustible d'un cotxe, controli el sensor de pressió de pneumàtics i el sensor digital de nivell de combustible i el funcionament de la bomba de combustible.
## Requisits i especificacions
- 
- 

## Diagrama de blocs
![Diagrama de bloques](Diagrama%20de%20bloques%20final.png)

## Taula de components
| Descripció                 | Manufacturer Number | Package  | Datasheet | Proveïdor | Unitats |
|----------------------------|--------------------|---------|----------|----------|---------|
| Regulador de tensió        | LM1117            | SOT-223 | [Enllaç](https://www.ti.com/lit/ds/symlink/lm1117.pdf) | DigiKey / Mouser | 1 |
| Regulador de commutació    | LM2596            | TO-220 / TO-263 | [Enllaç](https://www.ti.com/lit/ds/symlink/lm2596.pdf) | DigiKey / Mouser | 1 |
| Transceptor CAN            | MCP2551           | SOIC-8  | [Enllaç](https://eu.mouser.com/ProductDetail/Microchip-Technology/MCP2551-I-SN?qs=9y3LFqDLL8L5zFfqqxdOHg%3D%3D&srsltid=AfmBOoqzXfBuFZmBrmWaRyRollz1dC4TdYavzvEUIGq-QFGKWOZttsKP) | DigiKey / Mouser | 1 |
| Microcontrolador           | PIC18FXX8         | SOIC 28 | [Enllaç](https://ww1.microchip.com/downloads/en/devicedoc/39564c.pdf) | DigiKey / Mouser | 1 |
| Cristall de quars          | HC-49-US          | HC-49-SD | [Enllaç](https://www.txccrystal.com/images/pdf/HC-49US.pdf(https://www.vishay.com/doc?35012)(http://www.farnell.com/datasheets/2865821.pdf?_gl=1*v4ff3h*_gcl_aw*R0NMLjE3NDI0ODU5NjIuQ2owS0NRanctZTYtQmhEbUFSSXNBT3h4bHhWZlNMcTM3SjJ2RGlHTXF6emE0NWNTazRvZHItTmtBTVF5VWFaNVR2Z1Y0eHBud2hpeTZiVWFBbk54RUFMd193Y0I.*_gcl_au*MTQ0MDQ3ODg5NS4xNzQyNDA2NDAy)) | DigiKey / Mouser | 1 |
| Convertidor DAC            | MCP4725           | SOT-23-6 | [Enllaç](https://ww1.microchip.com/downloads/en/devicedoc/22039d.pdf) | DigiKey / Mouser | 1 |
| Transistor de control | 2SC4213 | SMD:SOT-323 | [Enllaç](https://toshiba.semicon-storage.com/info/docget.jsp?did=19305&prodName=2SC4213) | Mouser | 2 |
| Relé | Fujitsu_FTR-LYAA005x | SPST-Vertical | [Enllaç](https://www.fujitsu.com/sg/imagesgig5/ftr-ly.pdf) | Mouse | 2 |
| Díode protector | 1N5408 | DO-201AD | [Enllaç](https://www.vishay.com/docs/88516/1n5400.pdf) | Mouser | 4 |
| Díode Zener | 1N5822 | DO-201AD | [Enllaç](http://www.vishay.com/docs/88526/1n5820.pdf) | Farnell España | 1 |
| Díode de protecció en inversa | MBR340 | DO-201AD_P15.24mm | [Enllaç](http://www.onsemi.com/pub_link/Collateral/MBR340-D.PDF) | Mouser | 1 |



## Funcionalitats
- [ ] Funció 1
- [ ] Funció 2
- [ ] Funció 3

## Historial de canvis
| Data | Autor | Branch | Descripció |
|------|------|--------|------------| 
| 2025-03-20 | Sergi Pacheco | `main` | Creació del projecte |
| 2025-03-24 | Raúl Carod| `main` | Diagrama de blocs |
| 2025-03-24 | Sergi Pacheco| `main`| Llista de materials|
| 2025-03-24 | Raúl Carod | `main`| Esquemàtic entrades |
| 2025-03-25 | Raúl Carod | `main`| Esquemàtic microcontrolador|
| 2025-03-26 | Sergi Pacheco| `main`| Últims Outputs|
| 2025-03-27 | Raúl Carod | `main`| Digrama de blocs+ Sortides esquematic actulaitzades |
| 2025-03-27 | Raúl Carod | `main`| Digrama de blocs correcció |
| 2025-03-31 | Sergi Pacheco | `main`| Correccions del esquemàtic |
| 2025-03-31 | Raúl Carod | `main`| Més correción al esquemàtic + actulització llista materials|
| 2025-04-01 | Raúl Carod | `main`| Correccions al esquemàtic + emprentas components |
| 2025-04-01 | Raúl Carod | `main` | Layout |
| 2025-04-01 | Sergi Pacheco | `main`| Seguiment amb el Layout |
| 2025-04-01 | Raúl Carod | `main`|Layout acabat |
| 2025-04-03 | Sergi Pacheco| `main`|  Canvis al esquemàtic, clock i iscp aprop micro|
| 2025-04-03 | Raúl Carod | `main`| Algunes correccions del layout |
| 2025-04-08 | Sergi Pacheco| `main`|  Augment tamany vies, amplada pistes i treure pads de ground a resistències|
| 2025-04-09 | Raúl Carod | `main`| Correcció d'errors en el layout |
| 2025-04-09 | Raúl Carod | `main`| Correccions del Layout i cambis en l'esquemàtic |
