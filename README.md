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
> *GH/`@kormax` may use this repository to guide any potential [**FeliCa Tool**](https://github.com/kormax/felica-tool) updates.*<br>
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
| **CDG**<br>FR-75C<br>Paris | [**Navigo Easy**](https://www.iledefrance-mobilites.fr/en/titres-et-tarifs/supports/passe-navigo-easy) |
| **CDG**<br>FR-75C<br>Paris | [**Navigo Easy**](https://www.iledefrance-mobilites.fr/en/titres-et-tarifs/supports/passe-navigo-easy)<br>[*Paris 2024*](https://www.iledefrance-mobilites.fr/en/actualites/passe-paris-2024-transport-jo) |
| **NCE**<br>FR-06<br>Nice | [**The Card**](https://www.lignesdazur.com/en/tickets-and-fares)<br>[*Solo Rescue*](https://www.lignesdazur.com/fr/solo-secours) |
| **YUL**<br>CA-QC<br>Montréal | [**OPUS**](https://www.stm.info/en/info/fares/opus-cards-and-other-fare-media/opus-card#titre-h2-OPUS_card_purchase--1) |

> [!NOTE]
> 1. **NCE The Card** *Solo Rescue* in French is `La Carte - Solo Secours`.
> 2. **NCE The Card** *Solo Rescue*'s QR Code is a shortened URL to download their [**Android App**](https://play.google.com/store/apps/details?id=eu.mobeepass.walletapplication).

- [**Back to PTDex**](#randys-public-transport-index-ptdex)

---
## Felicity Cards (*FeliCa*)
| IATA<br>ISO 3166-2<br>City | Name<br>Native Name<br>Variant | Prefix<br>Colour<br>Notches | Manufacturer<br>ROM<br>IC | System | Service |
| --- | --- | --- | --- | --- | --- |
| **CTS**<br>JP-01<br>Hokkaido | [**Kitaca**](https://www.jrhokkaido.co.jp/global/english/ticket/kitaca/kitaca02.html)<br>-<br>- | JH<br>Silver<br>1 | 0101<br>05<br>31 (RC-S114) | 0003 | 008B<br>090F<br>108F<br>10CB<br>184B<br>208B<br>20CB<br>210B<br>214B<br>218B |
| **FUK**<br>JP-40<br>Fukuoka | [**Hayakaken**](https://subway.city.fukuoka.lg.jp/eng/fare/one/#no02)<br>はやかけん<br>- | FC<br>Silver<br>1 | 0101<br>05<br>31 (RC-S114) | 0003<br><br><br><br><br><br>FE00<br><br><br><br>927A | 008B<br>090F<br>108F<br>10CB<br><br>394B<br>398B<br>39C9<br><br>028B<br>02CB |
| **FUK**<br>JP-40<br>Fukuoka | [**Hayakaken**](https://subway.city.fukuoka.lg.jp/eng/fare/one/#no02)<br>はやかけん (いちょう)<br>*Ginkgo* | FC<br>Silver<br>1 | 0101<br>05<br>31 (RC-S114) | 0003<br><br><br><br><br><br>FE00<br><br><br><br>927A | 008B<br>090F<br>108F<br>10CB<br><br>394B<br>398B<br>39C9<br><br>028B<br>02CB |
| **FUK**<br>JP-40<br>Fukuoka | [**nimoca**](https://www.nimoca.jp/language/en)<br>-<br>- | NR<br>Silver<br>1 | 0101<br>05<br>31 (RC-S114) | 0003 | 008B<br>090F<br>108F<br>10CB | 
| **FUK**<br>JP-40<br>Fukuoka | [**SUGOCA**](https://www.jrkyushu.co.jp/sugoca/buy/new/)<br>-<br>- | JK<br>Silver<br>1 | 0101<br>05<br>31 (RC-S114) | 0003 | 008B<br>090F<br>108F<br>10CB |
| **FUK**<br>JP-40<br>Fukuoka | [**SUGOCA**](https://www.jrkyushu.co.jp/sugoca/buy/new/)<br>-<br>[*mono*](https://www.kitakyushu-monorail.co.jp/fare/ic-card.php) | JK<br>Silver<br>1 | 0101<br>05<br>31 (RC-S114) | 0003<br><br><br><br><br><br><br>FE00 | 008B<br>090F<br>108F<br>10CB<br><br>394B<br>398B<br>39C9 |
| **HKG**<br>CN-HK<br>Hong Kong | [**Octopus**](https://www.octopus.com.hk/en/consumer/tourist/channels/index.html)<br>迷你八達通<br>[*Mini*](https://www.octopus.com.hk/en/consumer/octopus-cards/products/sold-octopus/mini-octopus.html) | -<br>Black<br>0 | 0101<br>01<br>44 (RC-SA20/1) | 8008 | 0117<br>100B |
| **HKG**<br>CN-HK<br>Hong Kong | [**Octopus**](https://www.octopus.com.hk/en/consumer/tourist/channels/index.html)<br>普通版八達通<br>[*On-Loan*](https://www.octopus.com.hk/en/consumer/octopus-cards/products/on-loan/standard.html) | -<br>Black<br>0 | 0101<br>03<br>32 (RC-SA00/1) | 8008 | 0117<br>100B |
| **HKG**<br>CN-HK<br>Hong Kong | [**Octopus**](https://www.octopus.com.hk/en/consumer/tourist/channels/index.html)<br>八達通 – 全國通 (銷售版)<br>[*Tourist T-Union*](https://www.octopus.com.hk/en/consumer/octopus-cards/products/sold-tourist/mot.html) | -<br>White<br>0 | 0101<br>04<br>3B | 8008 | 0117<br>100B |
| **HND**<br>JP-13<br>Tokyo | [**PASMO**](https://www.pasmo.co.jp/visitors/en/)<br>-<br>- | PB<br>Silver<br>1 | 1201<br>05<br>31 (RC-S114) | 0003<br><br><br><br><br><br><br>FE00 | 008B<br>090F<br>108F<br>10CB<br><br>394B<br>398B<br>39C9 |
| **HND**<br>JP-13<br>Tokyo | [**Suica**](https://www.jreast.co.jp/en/multi/pass/suica.html)<br>-<br>- | JE<br>Silver<br>1 | 1201/1401<br>05<br>31 (RC-S114) | 0003<br><br><br><br><br><br><br><br><br><br><br><br>FE00<br><br><br><br>86A7 | 008B<br>090F<br>108F<br>10CB<br>184B<br>194B<br>198B<br>234B<br>238B<br>23CB<br><br>394B<br>398B<br>39C9<br><br>004B<br>028B |
| **HND**<br>JP-13<br>Tokyo | [**Suica**](https://www.jreast.co.jp/en/multi/pass/suica.html)<br>-<br>[*Welcome*](https://www.jreast.co.jp/en/multi/welcomesuica/welcomesuica.html) | JE<br>White<br>0 | 1001<br>05<br>31 (RC-S114) | 0003<br><br><br><br><br><br><br><br><br>FE00<br><br><br><br>86A7 | 008B<br>090F<br>108F<br>10CB<br>184B<br>194B<br>198B<br><br>394B<br>398B<br>39C9<br><br>004B<br>028B |
| **KIX**<br>JP-27<br>Osaka | [**ICOCA**](https://www.westjr.co.jp/global/en/howto/icoca/)<br>-<br>- | JW<br>Silver<br>1 | 0101<br>01<br>36 (RC-SA04/1) | 0003 | 008B<br>090F<br>108F<br>10CB |
| **KIX**<br>JP-27<br>Osaka | [**PiTaPa**](https://www.pitapa.com/link/card_lineup)<br>ピタパ<br>- | SU<br>Silver<br>1 | 1001<br>04<br>01 (RC-S915)  | 0003 | 008B<br>090F<br>108F<br>10CB |
| **JKT**<br>ID-JK<br>Jakarta | [**Kartu Multi Trip**](https://kci.id/kmt/informasi-kmt)<br>[*Commet*](https://kci.id/kmt/informasi-kmt)<br>- | -<br>Black<br>0 | 012E<br>03<br>35 (RC-SA01/2) | 90B7 | 1010<br>1012<br>1017<br>200C<br>200F<br>3008<br>300B<br>3048<br>304A<br>3088<br>30C8<br>30CB<br>4008<br>5008<br>500B<br>5048<br>504B<br>5088<br>508B<br>50C8<br>50CB<br>5108<br>510B<br>5148<br>51C8 |
| **MYJ**<br>JP-38<br>Matsuyama | [**ICOCA**](https://www.jr-shikoku.co.jp/icoca/icoca01-type.html)<br>-<br>*Shikoku* | JW<br>Silver<br>2 | 1201<br>01<br>36 (RC-SA04/1)| 0003 | 008B<br>090F<br>108F<br>10CB |
| **NGO**<br>JP-23<br>Nagoya | [**manaca**](https://manaca.jp/)<br>マナカ<br>[*DO!*](https://www.kotsu.city.nagoya.jp/rp/ticket/trp0000775.htm) | TP<br>Silver<br>1 | 0101<br>05<br>31 (RC-S114) | 0003<br><br><br><br><br><br><br><br><br><br>FE00 | 008B<br>090F<br>108F<br>10CB<br>988B<br>98CF<br>998B<br><br>394B<br>398B<br>39C9 |
| **NGO**<br>JP-23<br>Nagoya | [**manaca**](https://manaca.jp/)<br>マナカ<br>[*μstar*](https://www.meitetsu-bus.co.jp/rosen/manaca/type/0) | TP<br>Silver<br>1 | 0101<br>05<br>31 (RC-S114) | 0003<br><br><br><br><br><br><br><br><br><br>FE00 | 008B<br>090F<br>108F<br>10CB<br>988B<br>98CF<br>998B<br><br>394B<br>398B<br>39C9 |
| **NGO**<br>JP-23<br>Nagoya | [**TOICA**](https://global.jr-central.co.jp/en/tickets/buy/toica/)<br>-<br>- | JC<br>Silver<br>1 | 1201<br>01<br>36 (RC-SA04/1)| 0003 | 008B<br>090F<br>108F<br>10CB<br>184B<br>1E8B<br>1ECF |
| **NGS**<br>JP-42<br>Nagasaki | [**nimoca**](https://www.nimoca.jp/language/en)<br>-<br>*nagasaki* | NR<br>Silver<br>1 | 1201<br>05<br>31 (RC-S114) | 0003 | 008B<br>090F<br>108F<br>10CB | 
| **NGS**<br>JP-42<br>Nagasaki | [**N+ Card**](https://www.ntasu.co.jp/card_apply)<br>エヌタスカード<br>- | KA<br>Silver<br>1 | 1001<br>01<br>36 (RC-SA04/1) | 93EC<br><br><br><br><br><br><br><br><br><br>FE00 | 204B<br>304B<br>408B<br>500B<br>700B<br>80CF<br>A8CF<br><br>394B<br>398B<br>39C9 |
| **OKA**<br>JP-47<br>Okinawa | [**OKICA**](https://info.okica.jp/buy.html)<br>-<br>- | OK<br>White<br>2 | 1601<br>01<br>20 (RC-S962) | 8FC1<br><br><br><br><br><br>FE00  | 028F<br>050F<br>060B<br><br>394B<br>398B<br>39C9 |
| **QGU**<br>JP-21<br>Gifu | [**ayuca**](https://www.gifubus.co.jp/info/post728)<br>アユカ<br>- | GB<br>White<br>0 | 1201<br>01<br>36 (RC-SA04/1) | 83EE | 804B<br>884B<br>898F<br>924B | 
| **SIN**<br>SG-01<br>Singapore | [**EZ-Link**](https://ezlink.simplygo.com.sg/card-charm/ezlink/)<br>-<br>- | -<br>Blue<br>0 | 0101<br>03<br>00 (RC-S830) | 0102 | - |

> [!NOTE]
> 1. **HKG Octopus Tourist T-Union** is a dual-tech card.
> 2. **HKG Octopus Tourist T-Union**'s QR Code is a [**shortened URL**](https://www.octopus.com.hk/mot).
> 3. **HND Welcome Suica** has an Expiry Date in `MM/YY` and an Open Service Code of `### ### ABC DEF`.
> 4. **JKT Kartu Multi Trip**'s `Commet` is a portmanteau of **Comm**uter **E**lectronic **T**icket.
> 5. **KIX PiTaPa** is a post-pay service within the [**PiTaPa**](https://www.pitapa.com) network.
> 6. **KIX PiTaPa** is a pre-pay service within the rest of the [**NMUS**](https://en.wikipedia.org/wiki/Nationwide_Mutual_Usage_Service) network.
> 7. **SIN EZ-Link** now uses the `Specification for Contactless e-Purse Application (CEPAS)` chip technology.

- [**Back to PTDex**](#randys-public-transport-index-ptdex)

---
## MIFARE-Based Cards
| IATA<br>ISO 3166-2<br>City | Name<br>Variant<br>Technology | Code | CCV/CVN<br>Emboss | Expiry Date<br>Magnetic Stripe<br>Printed Name |
| --- | --- | --- | --- | --- |
| **ABE**<br>US-PA<br>Allentown | [**Masabi Justride**](https://www.masabi.com/justride/)<br>[*ValleyRide*](https://lantabus.com/valleyride/)<br>DESFire EV3 2k | 128 | -<br>- | -<br>-<br>- |
| **ADL**<br>AU-SA<br>Adelaide | [**metroCARD**](https://forms.sa.gov.au/#/form/5e7c47e8ad9c65369c64bc95)<br>-<br>DESFire EV1 2k | QR | -<br>- | -<br>-<br>- | 
| **AKL**<br>NZ-AUK<br>Auckland | [**AT HOP**](https://at.govt.nz/bus-train-ferry/at-hop-card/buy-hop-card/buycard)<br>-<br>DESFire EV1 4k | - | `###`<br>- | -<br>-<br>- |
| **ALB**<br>US-NY<br>Albany | [**Genfare e-Fare**](https://genfare.com/products/e-fare/)<br>[*Navigator*](https://nav.cdta.org/efare/store/loadProducts)<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>- |
| **AMS**<br>NL-NH<br>Amsterdam | [**OV-chipkaart**](https://www.ov-chipkaart.nl/en)<br>*Anonymous*<br>Classic 4k | EAN 13 | -<br>- | `DD-MM-YYYY`<br>-<br>- |
| **ATH**<br>GR-I<br>Athens | [**ATH.ENA**](https://www.athenacard.gr/index.jsp)<br>-<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>- |
| **ATL**<br>US<br>Atlanta | [**breeze**](https://www.breezecard.com/)<br>*Gen 2 (Silver)*<br>DESFire EV1 4k | 128 | -<br>- | -<br>-<br>- |
| **BDL**<br>US-CT<br>Hartford | [**Go CT**](https://buypasses.storesecured.com/)<br>-<br>DESFire EV1 4k | UPC A<br>128 | -<br>- | -<br>Yes<br>- |
| **BFS**<br>GB-NIR<br>Belfast | [**Belfast Visitor Pass**](https://www.translink.co.uk/tickets/travelcards/belfast-visitor-pass)<br>-<br>Classic EV1 1k | - | -<br>- | -<br>-<br>- |
| **BGO**<br>NO-46<br>Bergen | [**Skyss Kort**](https://www.skyss.no/en/tickets-and-prices/buying-tickets/order-skyss-travelcard/)<br>-<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>- |
| **BKK**<br>TH-10<br>Bangkok | [**BEM SVC**](https://metro.bemplc.co.th/Ticket-Token?ty=3)<br>-<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>- |
| **BKK**<br>TH-10<br>Bangkok | [**Rabbit**](https://www.bts.co.th/eng/tickets/ticket-rabbit.html)<br>-<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>- |
| **BLI**<br>US-WA<br>Bellingham | [**Cubic Umo**](https://umomobility.com/)<br>-<br>DESFire EV2 2k | 128 | -<br>- | -<br>Yes<br>- |
| **BNE**<br>AU-QLD<br>Brisbane | [**go**](https://gocard.translink.com.au/webtix/tickets-and-fares/go-card/online/buy/step-one)<br>-<br>Classic EV1 1k | - | -<br>- | -<br>-<br>- |
| **BOS**<br>US-MA<br>Boston | [**CharlieCard**](https://www.mbta.com/fares/charliecard)<br>-<br>Classic 1k | - | -<br>- | `MM/YY`<br>-<br>- |
| **BRS**<br>GB-BST<br>Bristol | [**ITSO**](https://www.itso.org.uk/)<br>*touch*<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>Yes |
| **CAK**<br>US-OH<br>Canton | [**Genfare e-Fare**](https://genfare.com/products/e-fare/)<br>*SCORE*<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>- |
| **CBR**<br>AU-ACT<br>Canberra | [**MyWay+**](https://mywayplus.transport.act.gov.au/core/buy-card)<br>-<br>DESFire Light | QR | `###`<br>`T` | -<br>-<br>- |
| **CHC**<br>NZ-CAN<br>Christchurch | [**Metrocard**](https://metrocard.metroinfo.co.nz/#/orderCard)<br>-<br>DESFire EV1 4k | - | -<br>`>` | -<br>-<br>- |
| **CMH**<br>US-OH<br>Columbus | [**Masabi Justride**](https://www.masabi.com/justride/)<br>[*Smartcard*](https://www.cota.com/smartcard/)<br>DESFire EV2 4k | 128 | -<br>- | -<br>-<br>- |
| **DAY**<br>US-OH<br>Dayton | [**Masabi Justride**](https://www.masabi.com/justride/)<br>[*Tapp Pay*](https://www.iriderta.org/pay/fares)<br>DESFire EV2 8k | 128 | `###`<br>- | -<br>-<br>- |
| **DEN**<br>US-CO<br>Denver | [**Masabi Justride**](https://www.masabi.com/justride/)<br>[*MyRide Gen 2a*](https://www.rtdonlinestore.com/product/myride/166)<br>DESFire EV2 4k | 128 | `###`<br>- | -<br>-<br>- |
| **DEN**<br>US-CO<br>Denver | [**Masabi Justride**](https://www.masabi.com/justride/)<br>[*MyRide Gen 2b (VanillaDirect)*](https://www.rtdonlinestore.com/product/myride/166)<br>DESFire EV3 8k | 128 | `###`<br>- | -<br>-<br>- |
| **DOH**<br>QA-DA<br>Doha | [**Travel Pass**](https://www.qr.com.qa/fares-and-travel-cards)<br>-<br>DESFire EV3 4k | - | -<br>- | -<br>-<br>- |
| **DUB**<br>IE-D<br>Dublin | [**Leap**](https://leapcard.ie/en/NavigationPages/CardPurchase.aspx)<br>-<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>- |
| **DUD**<br>NZ-OTA<br>Otago | [**Bee**](https://beecard.co.nz/GetACard)<br>-<br>DESFire EV1 4k | - | `###`<br>- | -<br>-<br>- |
| **ECN**<br>CY-01<br>Nicosia | [**motion**](https://motionbuscard.org.cy/ticket)<br>-<br>DESFire EV2 4k | - | -<br>- | -<br>-<br>- |
| **EUG**<br>US-OR<br>Eugene | [**Cubic Umo**](https://umomobility.com/)<br>-<br>DESFire EV2 2k | UPC A<br>128 | -<br>- | -<br>Yes<br>- |
| **EMA**<br>GB-LCE<br>Leicester | [**ITSO**](https://www.itso.org.uk/)<br>*Smartcard*<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>Yes |
| **EWR**<br>US-NJ<br>Jersey City | [**SmartLink**](https://www.pathsmartlinkcard.com/)<br>-<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>- |
| **EWR**<br>US-NJ<br>Jersey City | [**TAPP**](https://www.tappandride.com/purchase/new-tapp-card)<br>-<br>DESFire EV1 256b | - | -<br>- | -<br>-<br>- |
| **EWR**<br>US-NJ<br>Newark | [**FARE-PAY**](https://www.njtransit.com/farepay)<br>-<br>DESFire EV3 4k | UPC A<br>128 | `###`<br>- | -<br>Yes<br>- |
| **GEG**<br>US-WA<br>Spokane | [**Connect**](https://www.staconnectcard.com/buy-online/)<br>-<br>DESFire EV3 2k | UPC A<br>128 | `###`<br>- | -<br>Yes<br>- |
| **GRR**<br>US-MI<br>Grand Rapids | [**Wave**](https://wave.ridetherapid.org/customeraccount/order-a-card/)<br>-<br>DESFire EV1 256b | UPC A<br>128 | `###`<br>- | -<br>Yes<br>- |
| **HBA**<br>AU-TAS<br>Hobart | [**GreenCard**](https://greencard.metrotas.com.au/signup/details)<br>-<br>Classic 4k | - | -<br>- | -<br>-<br>- |
| **HBA**<br>AU-TAS<br>Hobart | [**Smartcard**](https://www.transport.tas.gov.au/public_transport/bus_timetables/ticketing)<br>-<br>Classic 1k 7b | - | -<br>- | -<br>-<br>- |
| **HNL**<br>US-HI<br>Honolulu | [**HOLO**](https://www.holocard.net/where-to-buy-a-card/)<br>-<br>DESFire EV1 256b | - | `###`<br>- | -<br>-<br>- |
| **IAD**<br>US-DC<br>Washington, D.C. | [**SmarTrip**](https://smarttrip.wmata.com/Storefront)<br>-<br>Plus X 2k | - | -<br>- | -<br>-<br>- |
| **IAH**<br>US-TX<br>Houston | [**RideMetro**](https://fares.ridemetro.org/ridemetro-card-app/order-a-card/)<br>-<br>DESFire EV1 256b | UPC A<br>128 | `###`<br>- | -<br>Yes<br>- |
| **IST**<br>TR-34<br>İstanbul | [**İstanbulkart**](https://www.istanbulkart.istanbul/OurCards)<br>-<br>DESFire EV3 2k | QR | -<br>- | -<br>-<br>- |
| **ITH**<br>US-NY<br>Ithaca | [**Genfare e-Fare**](https://genfare.com/products/e-fare/)<br>[*Tcard*](https://tcat-prod.gfcp.io/efare/store/loadProducts)<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>- |
| **JFK**<br>US-NY<br>New York City | [**OMNY**](https://omny.info/omny-card)<br>-<br>DESFire EV2 16k | 128 | `###`<br>- | `MM/YY`<br>-<br>- |
| **KUL**<br>MY-14<br>Kuala Lumpur | [**Touch 'n Go**](https://www.touchngo.com.my/consumer/toll/card/)<br>[*Classic*](https://www.touchngo.com.my/consumer/toll/card/classic-card/)<br>Plus 4k | - | -<br>- | `MM/YY`<br>-<br>- |
| **KUL**<br>MY-14<br>Kuala Lumpur | [**Touch 'n Go**](https://www.touchngo.com.my/consumer/toll/card/)<br>[*Enhanced*](https://shop.touchngo.com.my/touch-n-go-enhanced-nfc.html)<br>Plus EV2 4k | QR | -<br>- | `MM/YY`<br>-<br>- | 
| **LAX**<br>US-CA<br>Los Angeles | [**TAP**](https://www.taptogo.net/TAPPurchase)<br>-<br>Classic EV1 1k | - | -<br>- | -<br>-<br>- |
| **LBA**<br>GB-LDS<br>West Yorkshire | [**ITSO**](https://www.itso.org.uk/)<br>[*MCard*](https://m-card.co.uk/the-cards/travelcash/)<br>DESFire EV1 4k | EAN 13 | -<br>- | -<br>-<br>- |
| **LCY**<br>GB-LND<br>London | [**ITSO**](https://www.itso.org.uk/)<br>[*The Key*](https://ticket.southeasternrailway.co.uk/search?modal=register)<br>DESFire EV1 4k | - | -<br>- | `DD/MM/YYYY`<br>-<br>Yes |
| **LHR**<br>GB-LND<br>London | [**oyster**](https://tfl.gov.uk/fares/contactless-and-oyster-account)<br>-<br>DESFire EV1 2k | - | -<br>- | -<br>-<br>- |
| **LHR**<br>GB-LND<br>London | [**oyster**](https://tfl.gov.uk/fares/contactless-and-oyster-account)<br>[*Visitor*](https://visitorshop.tfl.gov.uk/en/london-visitor-oyster-card)<br>DESFire EV1 2k | - | -<br>- | -<br>-<br>- |
| **LJU**<br>SI-061<br>Ljubljana | [**Urbana**](https://www.lpp.si/en/frequently-asked-questions-and-answers#)<br>-<br>DESFire EV2 8k | 128 | -<br>- | -<br>-<br>- |
| **LPL**<br>GB-LIV<br>Liverpool | [**ITSO**](https://www.itso.org.uk/)<br>*MetroCard*<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>- |
| **MAN**<br>GB-MAN<br>Stockport | [**ITSO**](https://www.itso.org.uk/)<br>*Stagecoach*<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>- |
| **MAD**<br>ES-MD<br>Madrid | [**Tarjeta Transporte Público**](https://crtm.es/billetes-y-tarifas/#Tarjetas)<br>-<br>DESFire EV3 4k | - | -<br>- | -<br>-<br>- |
| **MEL**<br>AU-VIC<br>Melbourne | [**myki**](https://transport.vic.gov.au/manage-myki#buy/fare-type)<br>*Gen 2C (Purple)*<br>DESFire EV3 4k | - | -<br>- | -<br>-<br>Optional |
| **MEL**<br>AU-VIC<br>Melbourne | [**myki**](https://transport.vic.gov.au/manage-myki#buy/fare-type)<br>*Gen 2C (Youth)*<br>DESFire EV3 4k | - | -<br>- | -<br>-<br>Optional |
| **MIA**<br>US-FL<br>Miami | [**EASY Card**](https://transitstore.miamidade.gov/)<br>-<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>- |
| **MKE**<br>US-WI<br>Milwaukee | [**Cubic Umo**](https://umomobility.com/)<br>[*WisGo*](https://www.ridemcts.com/fares/where-to-buy#Buy_Online)<br>DESFire EV3 2k | UPC A<br>128 | -<br>- | -<br>Yes<br>- |
| **MNL**<br>PH-00<br>Manila | [**beep**](https://beep.com.ph/where-to-buy-a-beep-card/)<br>-<br>DESFire EV1 8k | - | -<br>- | `MMM/YYYY`<br>-<br>- |
| **MNL**<br>PH-00<br>Manila | [**TRIPKO**](https://www.tripko.com.ph/)<br>-<br>DESFire EV3 2k | - | -<br>- | -<br>-<br>- |
| **OMA**<br>US-NE<br>Omaha | [**Cubic Umo**](https://umomobility.com/)<br>[*Umo*](https://www.ometro.com/umo/)<br>DESFire EV2 2k | UPC A<br>128 | `###`<br>- | -<br>Yes<br>- |
| **ORD**<br>US-IL<br>Chicago | [**Ventra**](https://www.ventrachicago.com/purchase/)<br>-<br>DESFire EV1 256b | - | `###`<br>- | `MM/YY`<br>-<br>- |
| **OXR**<br>US-CA<br>Camarillo | [**Cubic Umo**](https://umomobility.com/)<br>*VCbuspass*<br>DESFire EV2 2k | UPC A<br>128 | -<br>- | -<br>Yes<br>- |
| **PBI**<br>US-FL<br>West Palm Beach | [**Genfare e-Fare**](https://genfare.com/products/e-fare/)<br>[*Paradise Pass*](https://www.myparadisepass.com/efare/store/loadProducts)<br>DESFire EV1 4k | UPC A<br>128 | -<br>- | -<br>Yes<br>- |
| **PDX**<br>US-OR<br>Portland | [**hop fastpass**](https://myhopcard.com/home/get-card)<br>-<br>DESFire EV1 256b | 128 | `###`<br>- | -<br>Yes<br>- |
| **PER**<br>AU-WA<br>Perth | [**SmartRider**](https://www.transperth.wa.gov.au/smartrider/types-of-smartrider/standard-smartrider)<br>-<br>Classic EV1 1k | - | -<br>- | -<br>-<br>- |
| **PHL**<br>US-PA<br>Philadelphia | [**FREEDOM**](https://www.ridepatco.org/schedules/FREEDOM.html)<br>-<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>- |
| **PHX**<br>US-AZ<br>Phoenix | [**Copper**](https://www.valleymetrofares.org/copper-card/buy-card/)<br>-<br>DESFire EV1 256b | UPC A<br>128 | `####`<br>- | -<br>Yes<br>- |
| **PVD**<br>US-RI<br>Providence | [**Wave**](https://wave.ripta.com/customeraccount/my-cards/order-cards/)<br>-<br>DESFire EV1 256b | UPC A<br>128 | `###`<br>- | -<br>Yes<br>- |
| **PWM**<br>US-ME<br>Portland | [**Cubic Umo**](https://umomobility.com/)<br>[*DiriGo Pass*](https://dirigopass.org/)<br>DESFire EV2 2k | UPC A<br>128 | -<br>- | -<br>Yes<br>- |
| **RDU**<br>US-NC<br>Raleigh | [**Cubic Umo**](https://umomobility.com/)<br>[*GoPass*](https://www.paypal.com/ncp/payment/Z7TYYN966ZPG4)<br>DESFire EV1 2k | UPC A<br>128 | -<br>- | -<br>Yes<br>- |
| **RSW**<br>US-FL<br>Fort Meyers | [**Genfare e-Fare**](https://genfare.com/products/e-fare/)<br>[*TropiCard*](https://www.mytropicard.com/efare/store/loadProducts)<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>- |
| **SCL**<br>CL-RM<br>Santiago | [**bip!**](https://www.red.cl/en/rates-and-top-ups/bip-card/)<br>-<br>Classic EV1 1k | 128 | -<br>- | -<br>-<br>- |
| **SEA**<br>US-WA<br>Seattle | [**ORCA**](https://www.myorca.com/buy-online/)<br>-<br>DESFire EV3 2k | 128 | `###`<br>- | -<br>-<br>- |
| **SFO**<br>US-CA<br>San Francisco | [**Clipper**](https://www.clippercard.com/checkout-get)<br>-<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>- |
| **SLC**<br>US-UT<br>Salt Lake City | [**FAREPAY**](https://farepay.rideuta.com/cart/cart.html)<br>-<br>Ultralight | UPC A<br>128 | -<br>- | -<br>Yes<br>- |
| **SMF**<br>US-CA<br>Sacramento | [**Connect**](https://www.connecttransitcard.com/Home/GetCard)<br>-<br>DESFire EV1 4k | - | `###`<br>- | -<br>-<br>- |
| **SNA**<br>US-CA<br>Orange | [**Wave**](https://wave.octa.net/buy-card-online/)<br>-<br>DESFire EV3 2k | UPC A<br>128 | `###`<br>- | -<br>Yes<br>- |
| **SOU**<br>GB-STH<br>Southampton | [**ITSO**](https://www.itso.org.uk/)<br>[*touch*](https://auth.southwesternrailway.com/swr/registrations)<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>Yes |
| **SYD**<br>AU-NSW<br>Sydney | [**Opal**](https://www.opal.com.au/ordercard)<br>-<br>DESFire EV1 4k | - | `####`<br>- | -<br>-<br>- |
| **TPE**<br>TW-TPE<br>Taipei | [**一卡通**](https://www.i-pass.com.tw/en/Page/StandardAdult)<br>-<br>Classic EV1 1k | - | -<br>- | -<br>-<br>- |
| **TPE**<br>TW-TPE<br>Taipei | [**一卡通 PLUS**](https://www.i-pass.com.tw/en/Page/StandardAdult)<br>-<br>Plus EV2 2k | - | -<br>- | -<br>-<br>- |
| **YKF**<br>CA-ON<br>Kitchener | [**EasyGO**](https://forms.regionofwaterloo.ca/grt/ePay/PRODUCTION-FORMS-LIVE/Order-a-new-EasyGO-fare-card)<br>-<br>DESFire EV1 4k | - | -<br>- | -<br>-<br>- |
| **YVR**<br>CA-BC<br>Vancouver | [**Compass**](https://www.compasscard.ca/OrderCard)<br>-<br>DESFire EV1 4k | UPC A | `###`<br>- | -<br>-<br>- | 
| **YVR**<br>CA-BC<br>Vancouver | [**Compass**](https://www.compasscard.ca/OrderCard)<br>[*Mini*](https://www.translink.ca/transit-fares/compass-card)<br>DESFire EV1 4k | - | `###`<br>- | -<br>-<br>- |
| **YVR**<br>CA-BC<br>Vancouver | [**Compass**](https://www.compasscard.ca/OrderCard)<br>[*Wristband*](https://www.translink.ca/transit-fares/compass-card)<br>DESFire EV1 8k | - | -<br>- | -<br>-<br>- |
| **YYZ**<br>CA-ON<br>Toronto | [**PRESTO**](https://www.prestocard.ca/en/products/physical-presto-card)<br>-<br>DESFire EV1 4k | - | `###`<br>`P` | `DD/MM/YYYY`<br>-<br>- |
| **ZAG**<br>HR-21<br>Zagreb | [**Vrijednosna Karta**](https://www.zet.hr/tickets-and-fares/stored-value-card-and-multi-day-ticket/604)<br>-<br>Classic EV1 1k | - | -<br>- | -<br>-<br>- |

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
> 11. **DEN MyRide** has added a `VanillaDirect` barcode to the back of the card since `Tuesday 2 December 2025`.
> 12. **EWR SmartLink** is being phased out in favour of **EWR TAPP**.
> 13. **EWR TAPP**'s `ISO-FID` is `3821`.
> 14. **EWR TAPP**'s `ISO DF-Name` is `637001FF4F5454205631`.
> 15. **EWR TAPP** is an abbreviation for `Total Access PATH Payment`.
> 16. **KUL Touch n' Go Enhanced**'s QR Code directs commuters to download their [**eWallet App**](https://cdn.tngdigital.com.my/s/landing/index.html).
> 17. **IST İstanbulkart** in English is `Istanbul Card`.
> 18. **IST İstanbulkart**'s QR Code contains the card number, UID, and [**their website**](https://www.istanbulkart.istanbul).
> 19. **LAX TAP** is an abbreviation for `Transit Access Pass`.
> 20. **MAD Tarjeta Transporte Público** in English is `Public Transport Card`.
> 21. **MEL myki** prints the commuter's name if it's registered and requested at the time of online purchase/replacement.
> 22. **MNL TRIPKO** in English is `MYTRIP`.
> 23. **SLC FAREPAY** is listed here *rather than in [**MIFARE-Based Tickets**](#mifare-based-tickets)* because this card is reloadable.
> 24. **TPE 一卡通** in English is `iPASS`.
> 25. **YVR Compass Mini** and **YVR Compass Wearable** are only sold at Waterfront Station's TransLink Customer Service Centre.
> 26. **YVR Compass Wearable**'s CVN is written on the issued receipt.
> 27. **YYZ PRESTO**'s emboss is `P` in Braille.
> 28. **ZAG Value Card** in English is `Value Card`.

- [**Back to PTDex**](#randys-public-transport-index-ptdex)

---
## MIFARE-Based Tickets
| IATA<br>ISO 3166-2<br>City | Name<br>Technology | Code | CCV/CVN<br>Emboss | Expiry Time<br>Expiry Date | Magnetic Stripe<br>Printed Name |
| --- | --- | --- | --- | --- | --- |
| **AMS**<br>NL-NH<br>Amsterdam | [**GVB 24 Hours Ticket**](https://www.gvb.nl/en/travel-products/hour-and-day-tickets/gvb-day-ticket)<br>Ultralight EV1 | UPC A | -<br>- | -<br>`31/12/YYYY` | -<br>- |
| **AMS**<br>NL-NH<br>Amsterdam | [**NS 1 Day Ticket**](https://www.ns.nl/en/tickets/day-return)<br>Ultralight EV1 | - | -<br>- | -<br>`31/12/YYYY` | -<br>- |
| **ATL**<br>US-GA<br>Atlanta | [**breeze Ticket**](https://itsmarta.com/breeze-tickets.aspx)<br>Ultralight C | - | -<br>- | -<br> - | -<br>- |
| **BKK**<br>TH-10<br>Bangkok | [**BTS Ticket**](https://www.bts.co.th/eng/tickets/ticket-journey.html)<br> Ultralight C | QR | -<br>- | -<br>- | -<br>- |
| **BKK**<br>TH-10<br>Bangkok | [**EBM Ticket**](https://ebm.co.th/en/ticket-journey/)<br> Ultralight C | QR | -<br>- | -<br>- | -<br>- |
| **DOH**<br>QA-DA<br>Doha | [**Day Pass**](https://www.qr.com.qa/fares-and-travel-cards)<br>Ultralight EV1 | - | -<br>- | `02:58`<br>`DD MMM YYYY` | -<br>- |
| **GLA**<br>GB-GLG<br>Glasgow | [**SPT Ticket**](https://www.spt.co.uk/tickets/subway-tickets/)<br>Ultralight | - | -<br>- | -<br>- | -<br>- |
| **HKG**<br>CN-HK<br>Hong Kong | [**MTR Ticket**](https://www.mtr.com.hk/en/customer/tickets/promotions_4persons.html)<br>Ultralight C | 128 | -<br>- | -<br>- | -<br>- |
| **LHR**<br>GB-LND<br>London | [**oyster**](https://tfl.gov.uk/fares/ways-to-pay/bus-and-tram-pass)<br>Classic EV1 | - | -<br>- | -<br>- | -<br>- |
| **MNL**<br>PH-00<br>Manila | [**LRT Ticket**](https://www.lrta.gov.ph/tickets-and-fares/)<br>Ultralight C | - | -<br>- | -<br>- | -<br>- |
| **MNL**<br>PH-00<br>Manila | [**MRT Ticket**](https://www.dotrmrt3.gov.ph)<br>Ultralight C | - | -<br>- | -<br>- | -<br>- |
| **OPO**<br>PT-13<br>Porto | [**Adante Tour 1**](https://andante.pt/en/purchase/andante-tour/)<br>Ultralight EV1 | - | -<br>- | -<br>- | -<br>- |
| **ORD**<br>US-IL<br>Chicago | [**Ticket**](https://www.transitchicago.com/fares/)<br>Ultralight EV1 | - | -<br>- | -<br>- | -<br>- |
| **SYD**<br>AU-NSW<br>Sydney | [**Ticket**](https://transportnsw.info/tickets-fares/fares/opal-single-tickets)<br>Ultralight C | - | -<br>- | `4am`<br>`DD.MM.YYYY` | -<br>- |
| **YUL**<br>CA-QC<br>Montréal | [**The Occasional**](https://www.stm.info/en/info/fares/opus-cards-and-other-fare-media/occasional-card)<br>Ultralight EV1 | - | -<br>- | -<br>- | -<br>- |
| **YVR**<br>CA-BC<br>Vancouver | [**Ticket**](https://www.translink.ca/transit-fares/where-to-buy#compass-tickets)<br>Ultralight EV1 | - | -<br>- | -<br>- | -<br>- |
| **YYZ**<br>CA-ON<br>Toronto | [**PRESTO TTC Ticket**](https://prestocard.ca/en/products/presto-ttc-tickets)<br>Ultralight C | - | -<br>- | -<br>- | -<br>- |

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
