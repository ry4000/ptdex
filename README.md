# randy's Public Transport Index (*PTDex*)
A public GitHub repository containing information about public transport cards.
- [**Calypso Cards**](#calypso-cards)
- [**Felicity Cards (FeliCa)**](#felicity-cards-felica)
- [**MIFARE-Based Cards**](#mifare-based-cards)
- [**MIFARE-Based Tickets**](#mifare-based-tickets)
  
> [!IMPORTANT]
>
> <img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg" style="max-width: 0.1em;max-height:0.1em;margin-left: .1em;"><img src="https://mirrors.creativecommons.org/presskit/icons/by.svg" style="max-width: 0.1em;max-height:0.1em;margin-left: .1em;"><img src="https://mirrors.creativecommons.org/presskit/icons/nc.svg" style="max-width: 0.1em;max-height:0.1em;margin-left: .1em;"><img src="https://mirrors.creativecommons.org/presskit/icons/sa.svg" style="max-width: 0.1em;max-height:0.1em;margin-left: .1em;">
> 
> [**PTDex**](https://github.com/ry4000/ptdex) is © 2026 by [**randy**](https://github.com/ry4000), and is licensed under [**CC BY-NC-SA 4.0**](https://creativecommons.org/licenses/by-nc-sa/4.0/).

> [!NOTE]
> 
> *GH/`@micolous` may use this repository to guide any potential [**Metrodroid**](https://github.com/metrodroid/metrodroid) updates.*<br>
> *GH/`@luu176` may use this repository to guide any potential [**Metroflip**](https://github.com/luu176/Metroflip) updates.*<br>
> *GH/`@iceman1001` may use this repository to guide any potential [**Proxmark3**](https://github.com/RfidResearchGroup/proxmark3) updates.*
> 
> *<sup>®</sup>s, <sup>TM</sup>s, and <sup>SM</sup>s are used for descriptive purposes only, and belong to their respective companies.*<br>
> *PTDex is not affiliated with — nor employed/sponsored by — any transit agency/manufacturer/vendor.*
>
> *PTDex information is correct at the time of publication, and may have since been upgraded by the transit agency.*

> [!TIP]
>
> Please join any of the below Discord Communities if you wish to mail randy a public transport card for PTDex:
> - [**Flipper Devices**](https://discord.gg/flipper)
> - [**Metroflip**](https://discord.gg/NR5hhbAXqS)
> - [**RFID Love by Iceman**](https://discord.gg/iceman)

---
## Calypso Cards
| IATA<br>ISO 3166-2<br>City | Name<br>Variant |
| --- | --- |
| **CDG**<br>FR-75C<br>Paris | **Navigo Easy** |
| **CDG**<br>FR-75C<br>Paris | **Navigo Easy**<br>*Paris 2024* |
| **NCE**<br>FR-06<br>Nice | **The Card**<br>*Solo Rescue* |
| **YUL**<br>CA-QC<br>Montréal | **OPUS** |

> [!NOTE]
> 1. **NCE The Card** *Solo Rescue* in French is `La Carte - Solo Secours`.
> 2. **NCE The Card** *Solo Rescue*'s QR Code is a shortened URL to download their [**Android App**](https://play.google.com/store/apps/details?id=eu.mobeepass.walletapplication).

- [**Back to PTDex**](#randys-public-transport-index-ptdex)

---
## Felicity Cards (*FeliCa*)
| IATA<br>ISO 3166-2<br>City | Name<br>Native Name<br>Variant | Prefix<br>Colour<br>Notches | Manufacturer<br>ROM<br>IC | System | Service |
| --- | --- | --- | --- | --- | --- |
| **CTS**<br>JP-01<br>Hokkaido | **Kitaca**<br>-<br>- | JH<br>Silver<br>1 | 0101<br>05<br>31 (RC-S114) | 0003 | 008B<br>090F<br>108F<br>10CB<br>184B<br>208B<br>20CB<br>210B<br>214B<br>218B |
| **FUK**<br>JP-40<br>Fukuoka | **Hayakaken**<br>はやかけん<br>- | FC<br>Silver<br>1 | 0101<br>05<br>31 (RC-S114) | 0003<br><br><br><br><br><br>FE00<br><br><br><br>927A | 008B<br>090F<br>108F<br>10CB<br><br>394B<br>398B<br>39C9<br><br>028B<br>02CB |
| **FUK**<br>JP-40<br>Fukuoka | **Hayakaken**<br>はやかけん (いちょう)<br>*Ginkgo* | FC<br>Silver<br>1 | 0101<br>05<br>31 (RC-S114) | 0003<br><br><br><br><br><br>FE00<br><br><br><br>927A | 008B<br>090F<br>108F<br>10CB<br><br>394B<br>398B<br>39C9<br><br>028B<br>02CB |
| **FUK**<br>JP-40<br>Fukuoka | **nimoca**<br>-<br>- | NR<br>Silver<br>1 | 0101<br>05<br>31 (RC-S114) | 0003 | 008B<br>090F<br>108F<br>10CB | 
| **FUK**<br>JP-40<br>Fukuoka | **SUGOCA**<br>-<br>- | JK<br>Silver<br>1 | 0101<br>05<br>31 (RC-S114) | 0003 | 008B<br>090F<br>108F<br>10CB |
| **FUK**<br>JP-40<br>Fukuoka | **SUGOCA**<br>-<br>*mono* | JK<br>Silver<br>1 | 0101<br>05<br>31 (RC-S114) | 0003<br><br><br><br><br><br><br>FE00 | 008B<br>090F<br>108F<br>10CB<br><br>394B<br>398B<br>39C9 |
| **HKG**<br>CN-HK<br>Hong Kong | **Octopus**<br>迷你八達通<br>*Mini* | -<br>Black<br>0 | 0101<br>01<br>44 (RC-SA20/1) | 8008 | 0117<br>100B |
| **HKG**<br>CN-HK<br>Hong Kong | **Octopus**<br>普通版八達通<br>*On-Loan* | -<br>Black<br>0 | 0101<br>03<br>32 (RC-SA00/1) | 8008 | 0117<br>100B |
| **HKG**<br>CN-HK<br>Hong Kong | **Octopus**<br>八達通 – 全國通 (銷售版)<br>*Tourist T-Union* | -<br>White<br>0 | 0101<br>04<br>3B | 8008 | 0117<br>100B |
| **HND**<br>JP-13<br>Tokyo | **PASMO**<br>-<br>- | PB<br>Silver<br>1 | 1201<br>05<br>31 (RC-S114) | 0003<br><br><br><br><br><br><br>FE00 | 008B<br>090F<br>108F<br>10CB<br><br>394B<br>398B<br>39C9 |
| **HND**<br>JP-13<br>Tokyo | **Suica**<br>-<br>- | JE<br>Silver<br>1 | 1201/1401<br>05<br>31 (RC-S114) | 0003<br><br><br><br><br><br><br><br><br><br><br><br>FE00<br><br><br><br>86A7 | 008B<br>090F<br>108F<br>10CB<br>184B<br>194B<br>198B<br>234B<br>238B<br>23CB<br><br>394B<br>398B<br>39C9<br><br>004B<br>028B |
| **HND**<br>JP-13<br>Tokyo | **Suica**<br>-<br>*Welcome* | JE<br>White<br>0 | 1001<br>05<br>31 (RC-S114) | 0003<br><br><br><br><br><br><br><br><br>FE00<br><br><br><br>86A7 | 008B<br>090F<br>108F<br>10CB<br>184B<br>194B<br>198B<br><br>394B<br>398B<br>39C9<br><br>004B<br>028B |
| **KIX**<br>JP-27<br>Osaka | **ICOCA**<br>-<br>- | JW<br>Silver<br>1 | 0101<br>01<br>36 (RC-SA04/1) | 0003 | 008B<br>090F<br>108F<br>10CB |
| **KIX**<br>JP-27<br>Osaka | **PiTaPa**<br>ピタパ<br>- | SU<br>Silver<br>1 | 1001<br>04<br>01 (RC-S915)  | 0003 | 008B<br>090F<br>108F<br>10CB |
| **MYJ**<br>JP-38<br>Matsuyama | **ICOCA**<br>-<br>*Shikoku* | JW<br>Silver<br>2 | 1201<br>01<br>36 (RC-SA04/1)| 0003 | 008B<br>090F<br>108F<br>10CB |
| **NGO**<br>JP-23<br>Nagoya | **manaca**<br>マナカ<br>*DO!* | TP<br>Silver<br>1 | 0101<br>05<br>31 (RC-S114) | 0003<br><br><br><br><br><br><br><br><br><br>FE00 | 008B<br>090F<br>108F<br>10CB<br>988B<br>98CF<br>998B<br><br>394B<br>398B<br>39C9 |
| **NGO**<br>JP-23<br>Nagoya | **manaca**<br>マナカ<br>*μstar* | TP<br>Silver<br>1 | 0101<br>05<br>31 (RC-S114) | 0003<br><br><br><br><br><br><br><br><br><br>FE00 | 008B<br>090F<br>108F<br>10CB<br>988B<br>98CF<br>998B<br><br>394B<br>398B<br>39C9 |
| **NGO**<br>JP-23<br>Nagoya | **TOICA**<br>-<br>- | JC<br>Silver<br>1 | 1201<br>01<br>36 (RC-SA04/1)| 0003 | 008B<br>090F<br>108F<br>10CB<br>184B<br>1E8B<br>1ECF |
| **NGS**<br>JP-42<br>Nagasaki | **nimoca**<br>-<br>*nagasaki* | NR<br>Silver<br>1 | 1201<br>05<br>31 (RC-S114) | 0003 | 008B<br>090F<br>108F<br>10CB | 
| **NGS**<br>JP-42<br>Nagasaki | **N+ Card**<br>エヌタスカード<br>- | KA<br>Silver<br>1 | 1001<br>01<br>36 (RC-SA04/1) | 93EC<br><br><br><br><br><br><br><br><br><br>FE00 | 204B<br>304B<br>408B<br>500B<br>700B<br>80CF<br>A8CF<br><br>394B<br>398B<br>39C9 |
| **OKA**<br>JP-47<br>Okinawa | **OKICA**<br>-<br>- | OK<br>White<br>2 | 1601<br>01<br>20 (RC-S962) | 8FC1<br><br><br><br><br><br>FE00  | 028F<br>050F<br>060B<br><br>394B<br>398B<br>39C9 |
| **QGU**<br>JP-21<br>Gifu | **ayuca**<br>アユカ<br>- | GB<br>White<br>0 | 1201<br>01<br>36 (RC-SA04/1) | 83EE | 804B<br>884B<br>898F<br>924B | 
| **SIN**<br>SG-01<br>Singapore | **EZ-Link**<br>-<br>- | -<br>Blue<br>0 | 0101<br>03<br>00 (RC-S830) | 0102 | - |

> [!NOTE]
> 1. **HKG Octopus Tourist T-Union** is a dual-tech card.
> 2. **HKG Octopus Tourist T-Union**'s QR Code is a [**shortened URL**](https://www.octopus.com.hk/mot).
> 3. **HND Welcome Suica** has an Expiry Date in `MM/YY` and an Open Service Code of `### ### ABC DEF`.
> 4. **KIX PiTaPa** is a post-pay service within the [**PiTaPa**](https://www.pitapa.com) network.
> 5. **KIX PiTaPa** is a pre-pay service within the rest of the [**NMUS**](https://en.wikipedia.org/wiki/Nationwide_Mutual_Usage_Service) network.
> 6. **SIN EZ-Link** now uses the `Specification for Contactless e-Purse Application (CEPAS)` chip technology.

- [**Back to PTDex**](#randys-public-transport-index-ptdex)

---
## MIFARE-Based Cards
| IATA<br>ISO 3166-2<br>City | Name<br>Variant<br>Technology | Code | CCV/CVN<br>Emboss | Expiry Date<br>Magnetic Stripe<br>Printed Name |
| --- | --- | --- | --- | --- |
| **ABE**<br>US-PA<br>Allentown | **ValleyRide**<br>-<br>DESFire EV3 2k | 128 | -<br>- | -<br>-<br>- |
| **ADL**<br>AU-SA<br>Adelaide | **metroCARD**<br>-<br>DESFire EV1 2k | QR | -<br>- | -<br>-<br>- | 
| **AKL**<br>NZ-AUK<br>Auckland | **AT HOP**<br>-<br>DESFire EV1 4k | - | `###`<br>- | -<br>-<br>- |
| **AMS**<br>NL-NH<br>Amsterdam | **OV-chipkaart**<br>*Anonymous*<br>Classic 4k | EAN 13 | -<br>- | `DD-MM-YYYY`<br>-<br>- |
| **ATH**<br>GR-I<br>Athens | **ATH.ENA**<br>-<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>- |
| **ATL**<br>US<br>Atlanta | **breeze**<br>*Gen 2 (Silver)*<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>- |
| **BDL**<br>US-CT<br> Hartford | **Go CT**<br>-<br>DESFire EV1 4k | UPC A<br>128 | -<br>- | -<br>-<br>- |
| **BFS**<br>GB-NIR<br>Belfast | **Visitor Pass**<br>-<br>Classic EV1 1k | - | -<br>- | -<br>-<br>- |
| **BGO**<br>NO-46<br>Bergen | **Skyss Kort**<br>-<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>- |
| **BKK**<br>TH-10<br>Bangkok | **BEM SVC**<br>-<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>- |
| **BKK**<br>TH-10<br>Bangkok | **Rabbit**<br>-<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>- |
| **BNE**<br>AU-QLD<br>Brisbane | **go**<br>-<br>Classic EV1 1k | - | -<br>- | -<br>-<br>- |
| **BOS**<br>US-MA<br>Boston | **CharlieCard**<br>-<br>Classic 1k | - | -<br>- | `MM/YY`<br>-<br>- |
| **BRS**<br>GB-BST<br>Bristol | **ITSO**<br>*touch*<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>Yes |
| **CBR**<br>AU-ACT<br>Canberra | **MyWay+**<br>-<br>DESFire Light | QR | `###`<br>`T` | -<br>-<br>- |
| **CHC**<br>NZ-CAN<br>Christchurch | **Metrocard**<br>-<br>DESFire EV1 4k | - | -<br>`>` | -<br>-<br>- |
| **CMA**<br>US-CA<br>Camarillo | **Umo**<br>*VCbuspass*<br>DESFire EV2 2k | UPC A<br>128 | -<br>- | -<br>Yes<br>- |
| **CMH**<br>US-OH<br>Columbus | **Smartcard**<br>-<br>DESFire EV2 4k | 128 | -<br>- | -<br>-<br>- |
| **DAY**<br>US-OH<br>Dayton | **Tapp Pay**<br>-<br>DESFire EV2 8k | 128 | `###`<br>- | -<br>-<br>- |
| **DEN**<br>US-CO<br>Denver | **MyRide**<br>-<br>DESFire EV2 4k | 128 | `###`<br>- | -<br>-<br>- |
| **DOH**<br>QA-DA<br>Doha | **Travel Pass**<br>-<br>DESFire EV3 4k | - | -<br>- | -<br>-<br>- |
| **DUB**<br>IE-D<br>Dublin | **Leap**<br>-<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>- |
| **DUD**<br>NZ-OTA<br>Otago | **Bee**<br>-<br>DESFire EV1 4k | - | `###`<br>- | -<br>-<br>- |
| **ECN**<br>CY-01<br>Nicosia | **motion**<br>-<br>DESFire EV2 4k | - | -<br>- | -<br>-<br>- |
| **EMA**<br>GB-LCE<br>Leicester | **ITSO**<br>*Smartcard*<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>Yes |
| **EWR**<br>US-NJ<br>Jersey City | **SmartLink**<br>-<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>- |
| **EWR**<br>US-NJ<br>Jersey City | **TAPP**<br>-<br>DESFire EV1 256b | - | -<br>- | -<br>-<br>- |
| **EWR**<br>US-NJ<br>Newark | **FARE-PAY**<br>-<br>DESFire EV3 4k | UPC A<br>128 | `###`<br>- | -<br>Yes<br>- |
| **GEG**<br>US-WA<br>Spokane | **Connect**<br>-<br>DESFire EV3 2k | UPC A<br>128 | `###`<br>- | -<br>Yes<br>- |  
| **HBA**<br>AU-TAS<br>Hobart | **GreenCard**<br>-<br>Classic 4k | - | -<br>- | -<br>-<br>- |
| **HBA**<br>AU-TAS<br>Hobart | **Smartcard**<br>-<br>Classic 1k | - | -<br>- | -<br>-<br>- |
| **IAD**<br>US-DC<br>Washington, D.C. | **SmarTrip**<br>-<br>Plus X 2k | - | -<br>- | -<br>-<br>- |
| **IST**<br>TR-34<br>İstanbul | **İstanbulkart**<br>-<br>DESFire EV3 2k | QR | -<br>- | -<br>-<br>- |
| **JFK**<br>US-NY<br>New York City | **OMNY**<br>-<br>DESFire EV2 16k | 128 | `###`<br>- | `MM/YY`<br>-<br>- |
| **KUL**<br>MY-14<br>Kuala Lumpur | **Touch 'n Go**<br>-<br>Plus 4k | - | -<br>- | `MM/YY`<br>-<br>- |
| **KUL**<br>MY-14<br>Kuala Lumpur | **Touch 'n Go**<br>*Enhanced*<br>Plus EV2 4k | QR | -<br>- | `MM/YY`<br>-<br>- | 
| **LAX**<br>US-CA<br>Los Angeles | **TAP**<br>-<br>Classic EV1 1k | - | -<br>- | -<br>-<br>- |
| **LBA**<br>GB-LDS<br>West Yorkshire | **ITSO**<br>*MCard*<br>DESFire EV1 4k | EAN 13 | -<br>- | -<br>-<br>- |
| **LCY**<br>GB-LND<br>London | **ITSO**<br>*The Key*<br>DESFire EV1 4k | - | -<br>- | `DD/MM/YYYY`<br>-<br>Yes |
| **LHR**<br>GB-LND<br>London | **oyster**<br>-<br>DESFire EV1 2k | - | -<br>- | -<br>-<br>- |
| **LJU**<br>SI-061<br>Ljubljana | **Urbana**<br>-<br>DESFire EV2 8k | 128 | -<br>- | -<br>-<br>- |
| **LPL**<br>GB-LIV<br>Liverpool | **ITSO**<br>*MetroCard*<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>- |
| **MAN**<br>GB-MAN<br>Stockport | **ITSO**<br>*Stagecoach*<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>- |
| **MAD**<br>ES-MD<br>Madrid | **Tarjeta Transporte Público**<br>-<br>DESFire EV3 4k | - | -<br>- | -<br>-<br>- |
| **MEL**<br>AU-VIC<br>Melbourne | **myki**<br>-<br>DESFire EV3 4k | - | -<br>- | -<br>-<br>Optional |
| **MNL**<br>PH-00<br>Manila | **beep**<br>-<br>DESFire EV1 8k | - | -<br>- | `MMM/YYYY`<br>-<br>- |
| **MNL**<br>PH-00<br>Manila | **TRIPKO**<br>-<br>DESFire EV3 2k | - | -<br>- | -<br>-<br>- |
| **ORD**<br>US-IL<br>Chicago | **Ventra**<br>-<br>DESFire EV1 256b | - | `###`<br>- | `MM/YY`<br>-<br>- |
| **PDX**<br>US-OR<br>Portland | **hop fastpass**<br>-<br>DESFire EV1 256b | 128 | `###`<br>- | -<br>Yes<br>- |
| **PER**<br>AU-WA<br>Perth | **SmartRider**<br>-<br>Classic EV1 1k | - | -<br>- | -<br>-<br>- |
| **PHL**<br>US-PA<br>Philadelphia | **FREEDOM**<br>-<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>- |
| **PWM**<br>US-ME<br>Portland | **Umo**<br>*DiriGo*<br>DESFire EV2 2k | UPC A<br>128 | -<br>- | -<br>Yes<br>- |
| **SCL**<br>CL-RM<br>Santiago | **bip**!<br>-<br>Classic EV1 1k | 128 | -<br>- | -<br>-<br>- |
| **SEA**<br>US-WA<br>Seattle | **ORCA**<br>-<br>DESFire EV3 2k | 128 | `###`<br>- | -<br>-<br>- |
| **SFO**<br>US-CA<br>San Francisco | **Clipper**<br>-<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>- |
| **SMF**<br>US-CA<br>Sacramento | **Connect**<br>-<br>DESFire EV1 4k | - | `###`<br>- | -<br>-<br>- |
| **SOU**<br>GB-STH<br>Southampton | **ITSO**<br>*touch*<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>Yes |
| **SYD**<br>AU-NSW<br>Sydney | **Opal**<br>-<br>DESFire EV1 4k | - | `####`<br>- | -<br>-<br>- |
| **TPE**<br>TW-TPE<br>Taipei | **一卡通**<br>-<br>Classic EV1 1k | - | -<br>- | -<br>-<br>- |
| **TPE**<br>TW-TPE<br>Taipei | **一卡通 PLUS**<br>-<br>Plus EV2 2k | - | -<br>- | -<br>-<br>- |
| **YKF**<br>CA-ON<br>Kitchener | **EasyGO**<br>-<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>- |
| **YVR**<br>CA-BC<br>Vancouver | **Compass**<br>-<br>DESFire EV1 4k | UPC A | `###`<br>- | -<br>-<br>- | 
| **YVR**<br>CA-BC<br>Vancouver | **Compass**<br>*Mini*<br>DESFire EV1 4k | - | `###`<br>- | -<br>-<br>- |
| **YVR**<br>CA-BC<br>Vancouver | **Compass**<br>*Wristband*<br>DESFire EV1 8k | - | -<br>- | -<br>-<br>- |
| **YYZ**<br>CA-ON<br>Toronto | **PRESTO**<br>-<br>DESFire EV1 4k | - | `###`<br>`P` | `DD/MM/YYYY`<br>-<br>- |
| **ZAG**<br>HR-21<br>Zagreb | **Vrijednosna Karta**<br>-<br>Classic EV1 1k | - | -<br>- | -<br>-<br>- |

> [!NOTE]
>
> 1. **ADL metroCARD**'s QR Code directs commuters to [**register**](https://dit.sa.gov.au/metrocard-register) their metroCARD.
> 2. **AMS OV-chipkaart** in English is `Public Transport Chip Card`.
> 3. **AMS OV-chipkaart** is currently used across The Netherlands and is listed under its Capital City for `PTDex` purposes.
> 4. **AMS OV-chipkaart** also has a hologram, though this is the only known example within the PTDex collection.
> 5. **AMS OV-chipkaart** *Anonymous* does not always have an EAN 13 barcode at the back.
> 6. **ATL breeze** *Gen 2 Silver* are decommissioned in favour of EMV `Better Breeze`.
> 7. **BGO Skyss Kort** in English is `Skyss Card`.
> 8. **CBR MyWay+**'s emboss is dots in the shape of `T`.
> 9. **CBR MyWay+**'s QR Code is text that shows a card prefix (`00001`), card number, and CCV.
> 10. **CHC Metrocard**'s emboss is dots in the shape of `>`.
> 11. **EWR TAPP**'s `ISO-FID` is `3821`.
> 12. **EWR TAPP**'s `ISO DF-Name` is `637001FF4F5454205631`.
> 13. **KUL Touch n' Go Enhanced**'s QR Code directs commuters to download their [**eWallet App**](https://cdn.tngdigital.com.my/s/landing/index.html).
> 14. **IST İstanbulkart** in English is `Istanbul Card`.
> 15. **IST İstanbulkart**'s QR Code contains the card number, UID, and [**their website**](https://www.istanbulkart.istanbul).
> 16. **MAD Tarjeta Transporte Público** in English is `Public Transport Card`.
> 17. **MEL myki** prints the commuter's name if it's registered and requested at the time of online purchase/replacement.
> 18. **MNL TRIPKO** in English is `MYTRIP`.
> 19. **TPE 一卡通** in English is `iPASS`.
> 20. **YVR Compass Mini** and **YVR Compass Wearable** are only sold at Waterfront Station's TransLink Customer Service Centre.
> 21. **YVR Compass Wearable**'s CVN is written on the issued receipt.
> 22. **YYZ PRESTO**'s emboss is `P` in Braille.
> 23. **ZAG Value Card** in English is `Value Card`.

- [**Back to PTDex**](#randys-public-transport-index-ptdex)

---
## MIFARE-Based Tickets
| IATA<br>ISO 3166-2<br>City | Name<br>Technology | Code | CCV/CVN<br>Emboss | Expiry Time<br>Expiry Date | Magnetic Stripe<br>Printed Name |
| --- | --- | --- | --- | --- | --- |
| **AMS**<br>NL-NH<br>Amsterdam | **GVB 24 Hours Ticket**<br>Ultralight EV1 | UPC A | -<br>- | -<br>`31/12/YYYY` | -<br>- |
| **AMS**<br>NL-NH<br>Amsterdam | **NS 1 Day Ticket**<br>Ultralight EV1 | - | -<br>- | -<br>`31/12/YYYY` | -<br>- |
| **ATL**<br>US-GA<br>Atlanta | **breeze Ticket**<br>Ultralight C | - | -<br>- | -<br> - | -<br>- |
| **BKK**<br>TH-10<br>Bangkok | **BTS Ticket**<br> Ultralight C | QR | -<br>- | -<br>- | -<br>- |
| **BKK**<br>TH-10<br>Bangkok | **EBM Ticket**<br> Ultralight C | QR | -<br>- | -<br>- | -<br>- |
| **DOH**<br>QA-DA<br>Doha | **Day Pass**<br>Ultralight EV1 | - | -<br>- | `02:58`<br>`DD MMM YYYY` | -<br>- |
| **GLA**<br>GB-GLG<br>Glasgow | **SPT Ticket**<br>Ultralight | - | -<br>- | -<br>- | -<br>- |
| **HKG**<br>CN-HK<br>Hong Kong | **MTR Ticket**<br>Ultralight C | 128 | -<br>- | -<br>- | -<br>- |
| **LHR**<br>GB-LND<br>London | **oyster**<br>Classic EV1 | - | -<br>- | -<br>- | -<br>- |
| **MNL**<br>PH-00<br>Manila | **LRT Ticket**<br>Ultralight C | - | -<br>- | -<br>- | -<br>- |
| **MNL**<br>PH-00<br>Manila | **MRT Ticket**<br>Ultralight C | - | -<br>- | -<br>- | -<br>- |
| **OPO**<br>PT-13<br>Porto | **Adante Tour 1**<br>Ultralight EV1 | - | -<br>- | -<br>- | -<br>- |
| **ORD**<br>US-IL<br>Chicago | **Ticket**<br>Ultralight EV1 | - | -<br>- | -<br>- | -<br>- |
| **SYD**<br>AU-NSW<br>Sydney | **Ticket**<br>Ultralight C | - | -<br>- | `4am`<br>`DD.MM.YYYY` | -<br>- |
| **YUL**<br>CA-QC<br>Montréal | **The Occasional**<br>Ultralight EV1 | - | -<br>- | -<br>- | -<br>- |
| **YVR**<br>CA-BC<br>Vancouver | **Ticket**<br>Ultralight EV1 | - | -<br>- | -<br>- | -<br>- |
| **YYZ**<br>CA-ON<br>Toronto | **PRESTO Ticket**<br>Ultralight C | - | -<br>- | -<br>- | -<br>- |

> [!NOTE]
>
> 1. **BKK BTS Ticket**'s QR Code directs commuters to the [**BTS SkyTrain Route Map (PDF)**](http://www.bts.co.th/btsroutes).
> 2. **BKK EBM Ticket**'s QR Code directs commuters to the [**EBM System Map (PDF)**](https://www.ebm.co.th/qr/routes).
> 3. **GLA SPT Ticket**'s chip is a [**my-d move lean**](https://www.infineon.com/products/security-smart-card-solutions/contactless-memories/my-d-move-lean) *which is equivalent to MIFARE Ultralight*.
> 4. **HKG MTR Ticket** is an [**Airport Express Group of 2/3/4 Single Journey Ticket Set**](https://www.mtr.com.hk/en/customer/tickets/promotions_4persons.html).
> 5. **HKG MTR Ticket** in Chinese (Traditional) is `2/3/4人行-單程票`.
> 6. **LHR oyster** is a [**One Day Bus and Tram Pass**](https://tfl.gov.uk/fares/ways-to-pay/bus-and-tram-pass).
> 7. **SYD Ticket** expires at 4am the day after the purchase date.
> 8. **YUL The Occasional** in French (Canada) is `L'occasionnelle`.
> 9. **YYZ PRESTO Ticket** in French (Canada) is `PRESTO Billet`.

- [**Back to PTDex**](#randys-public-transport-index-ptdex)
