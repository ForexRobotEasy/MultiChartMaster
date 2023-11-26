# MultiChartMaster

MultiChartMaster is a Forex trading software developed by the Forex Robot Easy Team. This software is designed to facilitate trading on multiple charts simultaneously, allowing traders to easily navigate between different symbols and perform various trading operations.

## Features

- Symbol Panel: The Symbol Panel provides an easy-to-use interface for navigating between different charts. Traders can select a symbol from the panel, and the software will automatically switch to the corresponding chart.

- Slave Indicator: The Slave Indicator is an included library that provides additional functionality for drawing levels and objects on charts. Traders can use keyboard shortcuts to quickly draw levels, change chart time frames, and select or deselect drawn objects.

## How It Works

The MultiChartMaster software is written in MQL5, a programming language specifically designed for trading strategies and indicators on the MetaTrader 5 platform. The code is divided into several sections, each serving a specific purpose:

1. Libraries and Indicators: The code includes the necessary libraries and indicators, such as the SlaveIndicator library, which provides additional functionality for drawing objects on charts.

2. Global Variables: The code declares a global variable `SymbolPanel` of type `CPanel`, which represents the Symbol Panel used for navigating between charts.

3. Custom Initialization Function: The `OnInit` function is called during the initialization of the software. It initializes the Symbol Panel and the Slave Indicator.

4. Custom Deinitialization Function: The `OnDeinit` function is called when the software is being deactivated or closed. It deinitializes the Symbol Panel and the Slave Indicator.

5. Custom Start Function: The `OnStart` function is the main loop of the software. It runs continuously until the software is stopped. In each iteration of the loop, the Symbol Panel is updated, and user input is checked. If a symbol is selected in the Symbol Panel, the software switches to the corresponding chart. If keyboard shortcuts in the Slave Indicator are pressed, various actions are performed, such as drawing levels and objects, changing chart time frames, and selecting or deselecting drawn objects. Finally, trading operations are performed, and the loop pauses for a while to reduce CPU usage.

## Product Description

MultiChartMaster is a powerful Forex trading software developed by the Forex Robot Easy Team. This software is designed to enhance traders' efficiency by allowing them to trade on multiple charts simultaneously. With the Symbol Panel feature, traders can easily navigate between different symbols and quickly switch to the desired chart. Additionally, the Slave Indicator provides advanced functionality for drawing levels and objects on charts, making technical analysis easier and more efficient.

Please note that Forex Robot Easy is not the official developer of this product. We only provide this sample code as an illustration of how the software works. To find the official developer and obtain the complete version of MultiChartMaster, please visit the MQL5 website.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/multichartmaster-forex-software-user-review-and-real-results/).
