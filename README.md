# Official exchange rates of the Bulgarian National Bank

[![Bulgarian National Bank - Official Currency Exchange Rates](https://github.com/LubomirGeorgiev/bnb-currency-exchange-rates/actions/workflows/update-rates.yml/badge.svg?branch=main)](https://github.com/LubomirGeorgiev/bnb-currency-exchange-rates/actions/workflows/update-rates.yml)

All exchange rates in the dataset are based on **Bulgarian Lev/BGN/Български лев** and are set as official rates by the [**Bulgarian National Bank**](https://www.bnb.bg/Statistics/StExternalSector/StExchangeRates/StERForeignCurrencies/index.htm?toLang=_EN).

This repository utilizes the [**schedule**](https://docs.github.com/en/actions/reference/events-that-trigger-workflows) function of Github Actions in order to update the dataset through a continuously running cronjob.

# Available datasets

<!-- START LINKS (DO NOT EVER FU*ING DELETE THIS COMMENT FOR THE LOVE OF YOUR LIFE!!! IF YOU ARE CURIOS HOW IT WORKS, YOU CAN HAVE A LOOK AT ./src/updateReadme.ts) -->

Last Update: Nov 27, 2022, 5:06:43 PM GMT+0 (2022-11-27T17:06:43.346Z)

| Currency | URL                                                                                             | Number of records | Number of missing days that were filled in |
| :------: | ----------------------------------------------------------------------------------------------- | :---------------: | :----------------------------------------: |
|   AUD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/AUD.csv |       8330        |                    2573                    |
|   CAD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/CAD.csv |       8330        |                    2573                    |
|   CHF    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/CHF.csv |       8330        |                    2573                    |
|   CZK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/CZK.csv |       8330        |                    2573                    |
|   DKK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/DKK.csv |       8330        |                    2573                    |
|   GBP    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/GBP.csv |       8330        |                    2573                    |
|   HUF    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/HUF.csv |       8330        |                    2573                    |
|   JPY    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/JPY.csv |       8330        |                    2573                    |
|   NOK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/NOK.csv |       8330        |                    2573                    |
|   NZD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/NZD.csv |       8330        |                    2573                    |
|   PLN    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/PLN.csv |       8330        |                    2573                    |
|   SEK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/SEK.csv |       8330        |                    2573                    |
|   USD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/USD.csv |       8330        |                    2573                    |
|   XAU    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/XAU.csv |       8330        |                    2575                    |
|   HKD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/HKD.csv |       8028        |                    2482                    |
|   KRW    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/KRW.csv |       8028        |                    2482                    |
|   SGD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/SGD.csv |       8028        |                    2482                    |
|   ZAR    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/ZAR.csv |       8028        |                    2482                    |
|   TRY    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/TRY.csv |       6510        |                    2012                    |
|   CNY    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/CNY.csv |       6390        |                    1976                    |
|   HRK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/HRK.csv |       6390        |                    1976                    |
|   IDR    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/IDR.csv |       6390        |                    1976                    |
|   MYR    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/MYR.csv |       6390        |                    1976                    |
|   PHP    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/PHP.csv |       6390        |                    1976                    |
|   THB    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/THB.csv |       6390        |                    1976                    |
|   RON    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/RON.csv |       6331        |                    1958                    |
|   RUB    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/RUB.csv |       6121        |                    1892                    |
|   BRL    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/BRL.csv |       5420        |                    1679                    |
|   MXN    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/MXN.csv |       5420        |                    1679                    |
|   ISK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/ISK.csv |       5332        |                    1653                    |
|   LTL    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/LTL.csv |       5153        |                    1582                    |
|   INR    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/INR.csv |       5051        |                    1563                    |
|   LVL    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/LVL.csv |       4788        |                    1468                    |
|   ILS    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/ILS.csv |       4325        |                    1342                    |
|   EEK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/EEK.csv |       4002        |                    1228                    |
|   SKK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/SKK.csv |       2972        |                    914                     |
|   CYP    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/CYP.csv |       2906        |                    890                     |
|   MTL    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/MTL.csv |       2604        |                    799                     |
|   SIT    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/SIT.csv |       2544        |                    780                     |
|   TRL    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/TRL.csv |       1818        |                    559                     |
|   ROL    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/ROL.csv |       1697        |                    524                     |
|   GRD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/GRD.csv |        361        |                    109                     |

<!-- END LINKS (DO NOT EVER FU*ING DELETE THIS COMMENT FOR THE LOVE OF YOUR LIFE!!! IF YOU ARE CURIOS HOW IT WORKS, YOU CAN HAVE A LOOK AT ./src/updateReadme.ts) -->
