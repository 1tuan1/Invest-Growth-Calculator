# Investment Calculator

A web-based investment calculator that helps users project potential investment growth based on trading parameters. The calculator takes into account winning and losing trades, profit/loss percentages, and reinvestment rates to provide detailed daily results.

## Features

- Calculate investment growth over custom time periods
- Input parameters:
  - Initial investment amount
  - Start date for calculations
  - Currency selection (supports major world currencies and cryptocurrencies)
  - Number of winning trades per day
  - Optional losing trades per day
  - Profit percentage per winning trade
  - Loss percentage per losing trade (optional)
  - Reinvestment rate
  - Time period (7, 14, 30 days, or custom)
- Detailed results table showing:
  - Day number
  - Calendar date
  - Daily starting capital
  - Daily profit/loss
  - Daily growth percentage
  - Total growth percentage
  - Growth multiplier (×)
  - End capital
  - Reinvested amount
  - Win/Loss ratio
- Data persistence (saves your settings)
- Progressive Web App (PWA) support
- Responsive design for all devices

## Technologies Used

- HTML5
- Bootstrap 5.3.2
- Vanilla JavaScript
- Numeral.js for number formatting
- Progressive Web App (PWA) features
- Local Storage for data persistence

## Usage

1. Open `index.html` in a web browser
2. Enter your investment parameters:
   - Set your initial investment amount
   - Choose your preferred currency
   - Select a start date
   - Input your expected daily winning trades
   - Optionally add losing trades (toggle with checkbox)
   - Specify profit and loss percentages
   - Set your reinvestment rate
   - Choose the calculation period
3. Click "Calculate" to see the results
4. Review the detailed breakdown in the results table
5. Your settings will be automatically saved for next time

## Installation

No installation required. Simply clone the repository and open `index.html` in a web browser:

```bash
git clone https://github.com/your-repo/investment-calculator.git
cd investment-calculator
open index.html
```

For PWA installation:

1. Open the website in Chrome
2. Click the install button in the address bar
3. The app will install and can be used offline

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
