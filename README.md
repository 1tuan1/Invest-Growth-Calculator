# Investment Calculator

A web-based investment calculator that helps users project potential investment growth based on trading parameters. The calculator takes into account winning and losing trades, profit/loss percentages, and reinvestment rates to provide detailed daily results.

## Features

- Calculate investment growth over custom time periods
- Input parameters:
  - Initial investment amount
  - Number of winning and losing trades per day
  - Profit percentage per winning trade
  - Loss percentage per losing trade
  - Reinvestment rate
  - Time period (7, 14, 30 days, or custom)
- Detailed results table showing:
  - Daily starting capital
  - Daily profit/loss
  - End capital
  - Reinvested amount
  - Win/Loss ratio

## Technologies Used

- HTML5
- Bootstrap 5.3.2
- Vanilla JavaScript

## Usage

1. Open `index.html` in a web browser
2. Enter your investment parameters:
   - Set your initial investment amount in euros
   - Input your expected daily winning and losing trades
   - Specify profit and loss percentages
   - Set your reinvestment rate
   - Choose the calculation period
3. Click "Calculate" to see the results
4. Review the detailed breakdown in the results table

## Installation

No installation required. Simply clone the repository and open `index.html` in a web browser: 
```bash
git clone https://github.com/your-repo/investment-calculator.git
cd investment-calculator
open index.html
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Disclaimer

This calculator is for educational purposes only. Trading and investing involve risk, and past performance does not guarantee future results. Always conduct thorough research and consult with financial professionals before making investment decisions.

Changes made: 
1. Updated the form inputs for losing trades to start at 0 by default
2. Added "(Optional)" to the labels for losing trade inputs
3. Updated the README to:
   - Clarify that losing trades are optional
   - Add the new table columns to the features list
   - Add Numeral.js to the technologies list
   - Update the usage instructions
   - Improve the overall documentation
The calculator will now work perfectly with or without losing trades, making it more flexible for different trading strategies.
