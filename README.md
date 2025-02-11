# support_level_detection
📉 Support Detection in Pine Script (v6)
This Pine Script v6 script automatically detects support levels by identifying local lows over a defined period. It filters out nearby support levels to avoid redundancy and displays them as horizontal lines on the chart.

🔍 Features
Identifies support levels based on local lows.
Filters out closely positioned levels to prevent duplication.
Dynamically plots detected support levels on the chart.
Adjustable parameters:
Analysis period (length): Defines the window for detecting local lows.
Deviation (%) (deviation): Prevents displaying excessively close support levels.
📌 Usage
Copy the code into Pine Script on TradingView.
Adjust the parameters as needed.
Apply the script to a chart to visualize support levels.
🛠️ Parameters
Parameter	Description	Default Value
length	Analysis period for detecting local lows	20
deviation	Tolerance to avoid redundant levels (%)	1.5
📜 Source Code
The full source code is available in this repository.

📢 Contributions
Contributions are welcome! Feel free to submit pull requests for improvements or report issues via Issues.

