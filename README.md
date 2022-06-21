# Official exchange rates of the Bulgarian National Bank

[![Bulgarian National Bank - Official Currency Exchange Rates](https://github.com/LubomirGeorgiev/bnb-currency-exchange-rates/actions/workflows/update-rates.yml/badge.svg?branch=main)](https://github.com/LubomirGeorgiev/bnb-currency-exchange-rates/actions/workflows/update-rates.yml)

All exchange rates in the dataset are based on **Bulgarian Lev/BGN/Български лев** and are set as official rates by the [**Bulgarian National Bank**](https://www.bnb.bg/Statistics/StExternalSector/StExchangeRates/StERForeignCurrencies/index.htm?toLang=_EN).

This repository utilizes the [**schedule**](https://docs.github.com/en/actions/reference/events-that-trigger-workflows) function of Github Actions in order to update the dataset through a continuously running cronjob.

# Available datasets

<!-- START LINKS (DO NOT EVER FU*ING DELETE THIS COMMENT FOR THE LOVE OF YOUR LIFE!!! IF YOU ARE CURIOS HOW IT WORKS, YOU CAN HAVE A LOOK AT ./src/updateReadme.ts) -->

Last Update: Jun 21, 2022, 5:15:23 PM GMT+0 (2022-06-21T17:15:23.402Z)

| Currency | URL                                                                                             | Number of records | Number of missing days that were filled in |
| :------: | ----------------------------------------------------------------------------------------------- | :---------------: | :----------------------------------------: |
|   AUD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/AUD.csv |       8170        |                    2524                    |
|   CAD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/CAD.csv |       8170        |                    2524                    |
|   CHF    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/CHF.csv |       8170        |                    2524                    |
|   CZK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/CZK.csv |       8170        |                    2524                    |
|   DKK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/DKK.csv |       8170        |                    2524                    |
|   GBP    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/GBP.csv |       8170        |                    2524                    |
|   HUF    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/HUF.csv |       8170        |                    2524                    |
|   JPY    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/JPY.csv |       8170        |                    2524                    |
|   NOK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/NOK.csv |       8170        |                    2524                    |
|   NZD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/NZD.csv |       8170        |                    2524                    |
|   PLN    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/PLN.csv |       8170        |                    2524                    |
|   SEK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/SEK.csv |       8170        |                    2524                    |
|   USD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/USD.csv |       8170        |                    2524                    |
|   XAU    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/XAU.csv |       8170        |                    2526                    |
|   HKD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/HKD.csv |       7870        |                    2435                    |
|   KRW    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/KRW.csv |       7870        |                    2435                    |
|   SGD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/SGD.csv |       7870        |                    2435                    |
|   ZAR    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/ZAR.csv |       7870        |                    2435                    |
|   TRY    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/TRY.csv |       6351        |                    1964                    |
|   CNY    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/CNY.csv |       6231        |                    1928                    |
|   HRK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/HRK.csv |       6231        |                    1928                    |
|   IDR    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/IDR.csv |       6231        |                    1928                    |
|   MYR    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/MYR.csv |       6231        |                    1928                    |
|   PHP    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/PHP.csv |       6231        |                    1928                    |
|   THB    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/THB.csv |       6231        |                    1928                    |
|   RON    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/RON.csv |       6176        |                    1914                    |
|   RUB    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/RUB.csv |       6119        |                    1890                    |
|   BRL    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/BRL.csv |       5263        |                    1633                    |
|   MXN    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/MXN.csv |       5263        |                    1633                    |
|   ISK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/ISK.csv |       5168        |                    1600                    |
|   LTL    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/LTL.csv |       5150        |                    1579                    |
|   INR    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/INR.csv |       4896        |                    1519                    |
|   LVL    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/LVL.csv |       4787        |                    1467                    |
|   ILS    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/ILS.csv |       4174        |                    1302                    |
|   EEK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/EEK.csv |       3993        |                    1219                    |
|   SKK    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/SKK.csv |       2969        |                    911                     |
|   CYP    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/CYP.csv |       2903        |                    887                     |
|   MTL    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/MTL.csv |       2603        |                    798                     |
|   SIT    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/SIT.csv |       2539        |                    775                     |
|   TRL    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/TRL.csv |       1817        |                    558                     |
|   ROL    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/ROL.csv |       1694        |                    521                     |
|   GRD    | https://raw.githubusercontent.com/LubomirGeorgiev/bnb-currency-exchange-rates/main/data/GRD.csv |        359        |                    107                     |

<!-- END LINKS (DO NOT EVER FU*ING DELETE THIS COMMENT FOR THE LOVE OF YOUR LIFE!!! IF YOU ARE CURIOS HOW IT WORKS, YOU CAN HAVE A LOOK AT ./src/updateReadme.ts) -->
