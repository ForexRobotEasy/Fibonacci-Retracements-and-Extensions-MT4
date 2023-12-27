# Fibonacci Retracements and Extensions MT4

This code is a sample implementation of a Fibonacci retracement and extension tool for MetaTrader 4 (MT4) platform. It calculates the retracement and extension levels based on a given start and end point, and displays the results.

## Functionality

The `calculateRetracements` function takes the start and end points as input and calculates the retracement and extension levels. It uses the following formulas:

- Retracement level = End point - (End point - Start point) * 0.382
- Extension level = End point + (End point - Start point) * 1.618

The calculated retracement and extension levels are then assigned to the `retracementLevel` and `extensionLevel` variables, respectively.

The `displayRetracements` function takes the start and end points as input, and calls the `calculateRetracements` function to calculate the levels. It then prints the retracement and extension levels using the `Print` function.

The `OnStart` function is the main function that executes the program. It defines an example start point and end point, and calls the `displayRetracements` function to display the levels.

## Product Description

This code is a sample implementation of a Fibonacci retracement and extension tool for MT4 platform. It provides a convenient way to calculate and display the retracement and extension levels based on a given start and end point.

Key features of this product include:

- Easy-to-use: Simply input the start and end points, and the retracement and extension levels will be calculated and displayed.
- Accurate calculations: The retracement and extension levels are calculated using the standard Fibonacci formulas, ensuring accurate results.
- Visual representation: The retracement and extension levels are displayed in the MT4 terminal, allowing traders to easily identify potential support and resistance levels.

Please note that ForexRobotEasy is not the official developer of this product. We are only showcasing a sample code that demonstrates how the Fibonacci retracement and extension tool can work. To find the official developer of this product, please refer to the MQL5 marketplace.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy - Fibonacci MT4 Software Review](https://forexroboteasy.com/forex-robot-review/fibonacci-mt4-software-review-dynamic-forex-trading-tool/).
