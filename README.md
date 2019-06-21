# Deribit NinjaTrader Adapter

[NinjaTrader](https://ninjatrader.com/) is a desktop application which allows trading. It also supports addons to allow third parties integrate their market data into the application.

Deribit NinjaTrader Adapter provides data from [Deribit](https://www.deribit.com/) platform which is bitcoin futures and options exchange. We provide live data, which can be used for analyzis, but we do not support trading.

## Installation

1. Download [Deribit NinjaTrader Adapter](https://github.com/deribit/deribit-ninjatrader-addon/releases/download/v1.0.0/DeribitNinjaTrader-addon-v1.0.0.zip)
2. Start NinjaTrader
3. Open Tools Menu

![img](images/install_1.png)

4. Choose Import -> NinjaScript Add-On...

![img](images/install_2.png)

5. Choose zip file with Deribit NinjaTrader Adapter which you downloaded earlier
6. Restart NinjaTrader

## Setup Connection

1. Open Connections Menu

![img](images/connection_1.png)

2. Click configure

![img](images/connection_2.png)

3. Choose deribit from Available list

![img](images/connection_3.png)

4. Click add in Configured section

![img](images/connection_4.png)

5. Fill properties. You can change Connection name if you wish. You have to fill User name and Password fields, it is required by NinjaTrader, but our addon do not use them, so you can type anything, for example test. Click OK to create new connection.

![img](images/connection_5.png)

## Connecting

1. Open Connections Menu

![img](images/connection_1.png)

2. Click "My deribit"

![img](images/connection_6.png)

## Setup Instruments

1. Open Tools Menu

![img](images/install_1.png)

2. Choose Instrument Lists

![img](images/instrument_list_1.png)

3. Click add in Lists section to create new list

![img](images/instrument_list_2.png)

4. Type Deribit and click OK

![img](images/instrument_list_3.png)

5. Deribit list will be created and selected. Click add in Instruments section to add instruments to list

![img](images/instrument_list_4.png)

6. Type DERIBIT and **click into magnifier**

![img](images/instrument_list_5.png)

7. Choose instrument which you want to add

![img](images/instrument_list_6.png)

8. Click OK

![img](images/instrument_list_7.png)

9. Instrument will be added to list. Last digits in instrument name determine when an instrument expires (09-18 means september 2018).

![img](images/instrument_list_8.png)

10. If you want to change instrument's rollover click edit.

![img](images/instrument_list_9.png)

11. Click Expiry

![img](images/instrument_list_10.png)

12. And select another one

![img](images/instrument_list_11.png)

13. Click OK

![img](images/instrument_list_12.png)

14. Now the instrument has changed rollover

![img](images/instrument_list_13.png)

15. You can add another instruments for example DERIBIT_PERPETUALBTC_USD or another DERIBIT_FUTURE_BTC_USD with different rollover. When you finish click OK to commit changes.

![img](images/instrument_list_14.png)

## Supported features

Deribit provide Level I & II data and historical data for charts, so you can use data provided by Deribit in following windows:

- SuperDOM (Dynamic/Static)
- Chart
- Level II
- T & S

## Uninstalling

1. Open Tools Menu

![img](images/install_1.png)

2. Choose Remove NinjaScript Assembly...

![img](images/uninstall_1.png)

3. Choose Deribit Assembly
