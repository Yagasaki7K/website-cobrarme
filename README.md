# CobrarMe

> A modern, single-file debt calculator with interest. No backend, no dependencies, no tracking.

CobrarMe is a lightweight web tool that calculates the updated value of a debt based on the original amount and the date it was incurred. It applies the Brazilian legal interest rate of up to **1% per month**, as defined by Article 406 of the Brazilian Civil Code.

## Features

- Calculate the updated value of a debt with monthly interest
- Input the original amount and the debt start date
- Automatic calculation of months elapsed
- Displays original value, interest, period, and total updated value
- Clean, modern, dark-themed interface
- Responsive design for mobile and desktop
- Internationalization (i18n) support for English and Brazilian Portuguese
- Zero dependencies. Single HTML file.
- No backend, no data collection, no tracking

## How It Works

1. Enter the original debt amount in Brazilian Reais (R$)
2. Select the date the debt started
3. Click "Calculate updated value" (or "Calcular valor atualizado")
4. The tool calculates the number of months since the debt started and applies a 1% monthly interest rate
5. The result shows:
   - Original value
   - Period (in months)
   - Interest amount
   - Total updated value

## Legal Basis

The interest calculation follows the Brazilian Civil Code, Article 406, which allows a default interest rate of up to 1% per month for debts without a specified rate. This is a simplified estimation and does not replace legal advice.

## Internationalization (i18n)

CobrarMe supports two languages:

- **English (en)**
- **Brazilian Portuguese (pt-BR)**

The language is automatically detected from the browser settings, and users can manually switch between languages using the toggle in the top-right corner. All UI text, labels, placeholders, and results are translated.

## Getting Started

No installation required. Just open the HTML file in any modern browser.

```bash
git clone https://github.com/your-username/cobrarme.git
cd cobrarme
open index.html
```

Or simply download the `index.html` file and open it locally.

## Tech Stack

- HTML5
- CSS3 (custom properties, flexbox, responsive design)
- Vanilla JavaScript (no frameworks, no libraries)
- Google Fonts (Inter)

## Use Cases

- Freelancers and small business owners tracking overdue payments
- Individuals calculating how much a friend or family member owes them
- Anyone who needs a quick, private debt calculation without using a spreadsheet

## Limitations

- The interest rate is fixed at 1% per month (the legal maximum). Actual rates may vary depending on the agreement or jurisdiction.
- The calculation is a simplified estimate and does not account for inflation, fees, or other legal adjustments.
- Not intended as a substitute for professional legal or financial advice.

## Contributing

Contributions are welcome. Feel free to open an issue or submit a pull request.

1. Fork the repository
2. Create a branch: `git checkout -b feat/my-feature`
3. Commit your changes: `git commit -m "feat: my feature"`
4. Push: `git push origin feat/my-feature`
5. Open a Pull Request

## License

MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

Created by [Anderson Marlon (Yagasaki)](https://yagasaki.vercel.app)  
Feel free to reach out for feedback, suggestions, or collaboration.
