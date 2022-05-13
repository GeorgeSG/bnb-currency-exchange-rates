# Official exchange rates of the Bulgarian National Bank

[![Bulgarian National Bank - Official Currency Exchange Rates](https://github.com/LubomirGeorgiev/bnb-currency-exchange-rates/actions/workflows/update-rates.yml/badge.svg?branch=main)](https://github.com/LubomirGeorgiev/bnb-currency-exchange-rates/actions/workflows/update-rates.yml)

All exchange rates in the dataset are based on **Bulgarian Lev/BGN/Български лев** and are set as official rates by the [**Bulgarian National Bank**](https://www.bnb.bg/Statistics/StExternalSector/StExchangeRates/StERForeignCurrencies/index.htm?toLang=_EN).

This repository utilizes the [**schedule**](https://docs.github.com/en/actions/reference/events-that-trigger-workflows) function of Github Actions in order to update the dataset through a continuously running cronjob.

# Available datasets

<!-- START LINKS (DO NOT EVER FU*ING DELETE THIS COMMENT FOR THE LOVE OF YOUR LIFE!!! IF YOU ARE CURIOS HOW IT WORKS, YOU CAN HAVE A LOOK AT ./src/updateReadme.ts) -->

Last Update: May 13, 2022, 5:11:57 PM GMT+0 (2022-05-13T17:11:57.885Z)

| Currency | URL                                                                                             | Number of records | Number of missing days that were filled in |
| :------: | ----------------------------------------------------------------------------------------------- | :---------------: | :----------------------------------------: |
|   AUD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/AUD.csv |       8137        |                    2517                    |
|   CAD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/CAD.csv |       8137        |                    2517                    |
|   CHF    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/CHF.csv |       8137        |                    2517                    |
|   CZK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/CZK.csv |       8137        |                    2517                    |
|   DKK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/DKK.csv |       8137        |                    2517                    |
|   GBP    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/GBP.csv |       8137        |                    2517                    |
|   HUF    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/HUF.csv |       8137        |                    2517                    |
|   JPY    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/JPY.csv |       8137        |                    2517                    |
|   NOK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/NOK.csv |       8137        |                    2517                    |
|   NZD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/NZD.csv |       8137        |                    2517                    |
|   PLN    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/PLN.csv |       8137        |                    2517                    |
|   SEK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/SEK.csv |       8137        |                    2517                    |
|   USD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/USD.csv |       8137        |                    2517                    |
|   XAU    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/XAU.csv |       8137        |                    2519                    |
|   HKD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/HKD.csv |       7837        |                    2428                    |
|   KRW    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/KRW.csv |       7837        |                    2428                    |
|   SGD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/SGD.csv |       7837        |                    2428                    |
|   ZAR    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/ZAR.csv |       7837        |                    2428                    |
|   TRY    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/TRY.csv |       6317        |                    1956                    |
|   CNY    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/CNY.csv |       6197        |                    1920                    |
|   HRK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/HRK.csv |       6197        |                    1920                    |
|   IDR    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/IDR.csv |       6197        |                    1920                    |
|   MYR    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/MYR.csv |       6197        |                    1920                    |
|   PHP    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/PHP.csv |       6197        |                    1920                    |
|   THB    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/THB.csv |       6197        |                    1920                    |
|   RON    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/RON.csv |       6138        |                    1902                    |
|   RUB    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/RUB.csv |       6124        |                    1895                    |
|   BRL    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/BRL.csv |       5227        |                    1623                    |
|   MXN    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/MXN.csv |       5227        |                    1623                    |
|   LTL    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/LTL.csv |       5157        |                    1586                    |
|   ISK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/ISK.csv |       5137        |                    1595                    |
|   INR    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/INR.csv |       4858        |                    1507                    |
|   LVL    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/LVL.csv |       4792        |                    1472                    |
|   ILS    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/ILS.csv |       4132        |                    1286                    |
|   EEK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/EEK.csv |       4002        |                    1228                    |
|   SKK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/SKK.csv |       2974        |                    916                     |
|   CYP    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/CYP.csv |       2906        |                    890                     |
|   MTL    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/MTL.csv |       2606        |                    801                     |
|   SIT    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/SIT.csv |       2544        |                    780                     |
|   TRL    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/TRL.csv |       1818        |                    559                     |
|   ROL    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/ROL.csv |       1699        |                    526                     |
|   GRD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/GRD.csv |        359        |                    107                     |

<!-- END LINKS (DO NOT EVER FU*ING DELETE THIS COMMENT FOR THE LOVE OF YOUR LIFE!!! IF YOU ARE CURIOS HOW IT WORKS, YOU CAN HAVE A LOOK AT ./src/updateReadme.ts) -->
