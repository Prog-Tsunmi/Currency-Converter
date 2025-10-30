# Simple Currency Converter

A clean, responsive web-based currency converter with real-time exchange rates and historical trend visualization.

![Currency Converter](https://img.shields.io/badge/Currency-Converter-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## Features

- 💱 **Real-time Currency Conversion** - Convert between 20+ major currencies
- 📊 **Historical Trend Chart** - Visualize 7-day exchange rate trends
- 🔄 **Quick Swap** - Instantly swap source and target currencies
- 📱 **Responsive Design** - Works perfectly on desktop and mobile devices
- ⚡ **Auto-convert** - Real-time conversion as you type
- 🎨 **Modern UI** - Clean, professional interface with smooth animations

## Supported Currencies

- USD (US Dollar)
- EUR (Euro)
- GBP (British Pound)
- JPY (Japanese Yen)
- CAD (Canadian Dollar)
- AUD (Australian Dollar)
- CHF (Swiss Franc)
- CNY (Chinese Yuan)
- SEK (Swedish Krona)
- NZD (New Zealand Dollar)
- MXN (Mexican Peso)
- SGD (Singapore Dollar)
- HKD (Hong Kong Dollar)
- NOK (Norwegian Krone)
- KRW (South Korean Won)
- TRY (Turkish Lira)
- INR (Indian Rupee)
- BRL (Brazilian Real)
- ZAR (South African Rand)
- PHP (Philippine Peso)

## How to Use

1. **Select Currencies**
   - Choose your source currency from the "From" dropdown
   - Choose your target currency from the "To" dropdown

2. **Enter Amount**
   - Type the amount you want to convert in the "Amount" field
   - The conversion happens automatically as you type

3. **View Results**
   - See the converted amount in the "Result" field
   - Check the current exchange rate below the form
   - View the 7-day trend chart for historical perspective

4. **Swap Currencies**
   - Click the "Swap Currencies" button to instantly reverse the conversion

## API Used

This project uses the [ExchangeRate-API](https://www.exchangerate-api.com) for real-time exchange rate data.

**Rate Limits:**
- Free tier: 1,500 requests per month
- Requests are cached to minimize API calls

## Technical Details

### Built With
- **Frontend**: HTML5, Tailwind CSS, JavaScript
- **Charts**: Chart.js for historical trend visualization
- **Icons**: Font Awesome
- **API**: ExchangeRate-API

### Browser Support
- Chrome (recommended)
- Firefox
- Safari
- Edge

## Project Structure
currency-converter/
├── index.html # Main application file
├── README.md # Project documentation
└── (optional assets)


## Installation

No installation required! This is a single HTML file application:

1. Download `index.html`
2. Open it in any modern web browser
3. Start converting currencies!

## Error Handling

- Network connectivity issues
- API rate limit exceeded
- Invalid currency pairs
- Invalid input amounts

## License

**All Rights Reserved**

This project is proprietary and confidential. No part of this work may be reproduced, distributed, or transmitted in any form or by any means, including photocopying, recording, or other electronic or mechanical methods, without the prior written permission of the copyright holder.

**Third-party API**: This project uses ExchangeRate-API. Please refer to their [terms of service](https://www.exchangerate-api.com/terms) for API usage restrictions.

## Disclaimer

Exchange rates are provided by third-party APIs and may not be accurate for financial transactions. This tool is for informational purposes only. Always verify rates with official financial institutions for critical transactions.

## Contributing

This is a personal project and not open for contributions.

## Support

If you encounter any issues:
1. Check your internet connection
2. Verify the API service status
3. Ensure you're using a supported browser

---

**Note**: This is a client-side application. All currency conversion happens in your browser using live exchange rate data from ExchangeRate-API.
