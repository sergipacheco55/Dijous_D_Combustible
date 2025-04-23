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
| Regulador de tensió        | LM1117            | SOT-223 | [Enllaç](https://www.ti.com/lit/ds/symlink/lm1117.pdf) | Mouser | 1 |
| Regulador de commutació    | LM2596            | TO-220 / TO-263 | [Enllaç](https://www.ti.com/lit/ds/symlink/lm2596.pdf) |Mouser | 1 |
| Transceptor CAN            | MCP2557           | SOIC-8  | [Enllaç](https://www.digikey.es/es/products/detail/microchip-technology/MCP2557FD-H-SN/6009299?gclsrc=aw.ds&&utm_adgroup=&utm_source=google&utm_medium=cpc&utm_campaign=PMax_Product_All%20Products&utm_term=&productid=6009299&utm_content=&utm_id=go_cmp-20199915072_adg-_ad-__dev-c_ext-_prd-6009299_sig-Cj0KCQjw_JzABhC2ARIsAPe3ynpUKI6YB1CwYhuxLEUHioMMJoSxuswcCzv73NbuUfjEhpO7h3KmzM0aAg-ZEALw_wcB&gad_source=1&gbraid=0AAAAADrbLli4DwHuL2SABBDwoZRf1ZzGQ&gclid=Cj0KCQjw_JzABhC2ARIsAPe3ynpUKI6YB1CwYhuxLEUHioMMJoSxuswcCzv73NbuUfjEhpO7h3KmzM0aAg-ZEALw_wcB&gclsrc=aw.ds) | DigiKey | 1 |
| Microcontrolador           | PIC18F258         | SOIC 28 | [Enllaç](https://ww1.microchip.com/downloads/en/devicedoc/39564c.pdf) | DigiKey / Mouser | 1 |
| Cristall de quars          | abls-4.000mhz-b2-t | HC-49-SD | [Enllaç](https://www.mouser.es/ProductDetail/ABRACON/ABLS-4000MHZ-B2-T?qs=D0XpjEo%2FJ5C3RozMqbjMZQ%3D%3D&mgh=1&vip=1&utm_id=19103542967&utm_source=google&utm_medium=cpc&utm_marketing_tactic=emeacorp&gad_source=1&gbraid=0AAAAADn_wf3OXCEtXcIA5_5RcBvoSepTR&gclid=Cj0KCQjw_JzABhC2ARIsAPe3ynqsKUWHLoPzyu7DV4PfzRyfIg9Ooyksv1cDZuEIGajdSMNtnR05LqEaAmMCEALw_wcB) | Mouser | 1 |
| Convertidor DAC            | MCP4725           | SOT-23-6 | [Enllaç](https://ww1.microchip.com/downloads/en/devicedoc/22039d.pdf) | DigiKey / Mouser | 1 |
| Transistor de control | 2SC4213 | SMD:SOT-323 | [Enllaç](https://toshiba.semicon-storage.com/info/docget.jsp?did=19305&prodName=2SC4213) | Mouser | 2 |
| Relé | Fujitsu_FTR-LYAA005x | SPST-Vertical | [Enllaç](https://www.fujitsu.com/sg/imagesgig5/ftr-ly.pdf) | Mouse | 2 |
| Díode protector | PMEG6030EP | Diode_SMD:D_SOD-128 | [Enllaç](https://www.vishay.com/docs/88516/1n5400.pdf) | Mouser | 4 |
| Díode Zener | 1N5822 | DO-201AD | [Enllaç](http://www.vishay.com/docs/88526/1n5820.pdf) | Farnell España | 1 |
| LED Blau | 150080BS75000 | 0805_2012 | [Enllaç](https://www.we-online.com/components/products/datasheet/150080BS75000.pdf)| Digikey | 2 |
| LED Verd | 150080GS75000 | 0805_2012 | [Enllaç](https://www.we-online.com/components/products/datasheet/150080GS75000.pdf)| Digikey | 1 |
| LED Blau | 150080SS75000 | 0805_2012 | [Enllaç](https://www.we-online.com/components/products/datasheet/150080SS75000.pdf)| Digikey | 1 |
| Connector Bateria | 691137710002 | TERM BLK 2POS SIDE ENTRY 5MM PCB | [Enllaç](https://www.we-online.com/components/products/datasheet/691137710002.pdf) | Digikey | 1 |
| Connector 01x02 | 61300211121 | PinHeader_1x02_P2.54mm_Vertical | [Enllaç](https://www.we-online.com/components/products/datasheet/61300211121.pdf) |Digikey | 4 |
| Connector ISCP | 61200621621 | PinHeader_2x03_P2.54mm_Vertical | [Enllaç](https://www.we-online.com/components/products/datasheet/61200621621.pdf) | Digikey | 1 |
| Connector Usart | 61300611121 | PinHeader_1x06_P2.54mm_Vertical | [Enllaç](https://www.we-online.com/components/products/datasheet/61300611121.pdf) | Digikey | 1 |
| Connector 01x03 | G800LR305018EU | FanPinHeader_1x03_P2.54mm_Vertical | [Enllaç]() |Mouser | 1 |
| Jumper | 60900213421 | JUMPER W/TEST PNT 1X2PINS 2.54MM | [Enllaç](https://www.we-online.com/components/products/datasheet/60900213421.pdf) | Digikey | 1 |
| Pulsador reset | SKRKAEE020 | SW_Push_SPST_NO_Alps_SKRK | [Enllaç](https://www.mouser.es/datasheet/2/15/SKRK-1370789.pdf) | Mouser | 1 |
| Connector DB9 | DE09-PT-1 | DSUB-9_Male_Vertical_P2.77x2.84mm | [Enllaç](https://app.adam-tech.com/products/download/data_sheet/198661/dxxx-pt-1-data-sheet.pdf) | Digikey | 1 |
| Díode de protecció de connexió | PMEG040V050EPD | CFP15_SOT-1289 | [Enllaç](https://assets.nexperia.com/documents/data-sheet/PMEG040V050EPD.pdf) | Digikey | 1 |



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
| 2025-04-19 | Raúl Carod | `main`| Layout final |
| 2025-04-19 | Raúl Carod | `main`| Correccionament de layout final |
