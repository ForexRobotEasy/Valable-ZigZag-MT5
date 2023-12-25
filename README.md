# Valable ZigZag MT5

This is a custom indicator called Valable ZigZag for MetaTrader 5 (MT5). It is designed to identify and plot zigzag patterns on the chart. The indicator uses the concept of fractals to determine the turning points in the price movement.

## Indicator Parameters

- `InpDepth`: Depth parameter for fractal calculation
- `InpDeviation`: Deviation parameter for fractal calculation
- `InpBackstep`: Backstep parameter for fractal calculation
- `InpTimeframe`: Timeframe for determining the trend's direction

## How it Works

The indicator works by scanning the price data to identify the highest and lowest points within a specified depth. It then checks if the difference between these points exceeds a certain deviation. If it does, it considers it as a zigzag pattern and plots the points accordingly.

The indicator uses the `High` and `Low` arrays to access the price data. It iterates through the price data using a main loop and checks if each point satisfies the zigzag criteria. If it does, it plots the zigzag points on the chart using the `ExtBuffer` array.

The indicator also keeps track of the direction of each zigzag point using the `ExtWaves` array. Positive values indicate an upward movement, while negative values indicate a downward movement.

## Product Description

Valable ZigZag is a powerful indicator for MetaTrader 5 that can help traders identify and visualize zigzag patterns on the chart. Zigzag patterns are commonly used in technical analysis to identify trend reversals and potential trade opportunities.

With Valable ZigZag, traders can easily spot these patterns and make more informed trading decisions. The indicator plots the zigzag points on the chart, making it easy to visually identify the turning points in the price movement.

Key Features:
- Identifies zigzag patterns based on fractal calculations
- Customizable depth, deviation, and backstep parameters
- Works on H4 timeframe
- Plots zigzag points on the chart
- Indicates the direction of each zigzag point

Please note that Forex Robot Easy is not the official developer of this product. We are showcasing a sample code that demonstrates how the Valable ZigZag indicator can work. To find the official developer of this product, please use MQL5 or visit the following link for detailed reviews and trading results: [Valable ZigZag MT5 Review](https://forexroboteasy.com/forex-robot-review/valable-zigzag-mt5-review-optimize-trading-with-wave-theory/).
