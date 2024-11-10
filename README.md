# RRG (Relative Rotation Graph) Indicator

A Python application that implements the Relative Rotation Graph (RRG) indicator for technical analysis of financial markets. The RRG visualizes the relative strength and momentum of financial instruments compared to a benchmark.

## Features

- Real-time data fetching from Yahoo Finance
- Interactive RRG visualization with four quadrants (Leading, Weakening, Lagging, Improving)
- Dynamic ticker selection and management
- Animation controls for time-series analysis
- Customizable display settings (tail length, time window)
- Comprehensive error handling and logging
- Data caching for improved performance

## Requirements

- Python 3.7+ (Tested on Python 3.10.10)
- Dependencies listed in requirements.txt:
  - pandas == 2.1.1
  - numpy == 1.26.0
  - yfinance == 0.2.31
  - matplotlib == 3.8.0
  - scipy == 1.11.3

## Installation

1. Clone the repository
2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

1. Run the application:
```bash
python RRGIndicator.py
```

2. Interface Controls:
- Date Slider: Navigate through different time periods
- Tail Slider: Adjust the length of historical data shown
- Play/Pause Button: Animate the RRG through time
- Ticker Table: 
  - Edit symbols by typing new ticker and pressing Enter
  - Toggle visibility using checkboxes
  - View current prices and changes

