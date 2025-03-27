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
| 2025-03-26 | Raul Carod | `main`| Digrama de blocs+ Sortides esquematic actulaitzades |

