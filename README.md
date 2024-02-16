# Check Leverage and Spread

This code is an Expert Advisor (EA) developed by the Forex Robot Easy Team. It is designed to monitor the leverage and spread in real-time in the MetaTrader 5 platform.

## Functionality

The EA includes the following functions:

1. `MonitorLeverage()`: This function retrieves and prints the current leverage of the trading account.

2. `MonitorSpread()`: This function retrieves and prints the current spread for the selected symbol.

3. `IsSpreadManipulated()`: This function checks if the spread is manipulated by comparing it to a predefined range. If the spread is outside this range, it is considered manipulated.

4. `ProvideLotageInformation()`: This function provides information about the appropriate lot sizes based on the leverage.

5. `MonitorLeverageAndSpread()`: This function combines the previous functions to monitor leverage and spread in real-time. It calls `MonitorLeverage()`, `MonitorSpread()`, `IsSpreadManipulated()`, and `ProvideLotageInformation()`.

The EA also includes the following event functions:

1. `OnInit()`: This function is called when the EA is initialized. It calls `MonitorLeverageAndSpread()`.

2. `OnDeinit(const int reason)`: This function is called when the EA is deinitialized. It prints a message indicating that the EA has stopped.

3. `OnTick()`: This function is called on each tick of the selected symbol. It calls `MonitorLeverageAndSpread()`.

4. `OnStart()`: This function is called when the EA starts running. It continuously calls `MonitorLeverageAndSpread()` and sleeps for 1 second between each call.

5. `OnStop()`: This function is called when the EA is stopped. It prints a message indicating that the EA has stopped.

## Product Description

The 'Check Leverage and Spread' EA developed by the Forex Robot Easy Team is a powerful tool for monitoring leverage and spread in real-time in the MetaTrader 5 platform. It provides traders with valuable information about their trading conditions, allowing them to make informed decisions.

With this EA, traders can easily monitor their current leverage and spread for the selected symbol. The EA checks if the spread is manipulated by comparing it to a predefined range, providing an additional layer of security. Traders can also receive lotage information based on their leverage, helping them choose appropriate lot sizes for their trades.

The 'Check Leverage and Spread' EA is a reliable and efficient solution for traders who want to stay informed about their trading conditions. It can be used with any trading strategy and is suitable for both novice and experienced traders.

Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that demonstrates the functionality described in this product. To find the official developer of this product, please refer to the MQL5 platform.

For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/check-laverage-spread-real-time-forex-software-review/).
