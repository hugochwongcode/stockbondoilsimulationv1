# Portfolio Simulator
This repository contains a Python script for simulating the growth of a financial portfolio over a specified number of years. The script allows users to model the performance of portfolios with allocations to stocks, bonds, and oil.

## Usage on Google Colab
1. Download the IPYNB file into your local machine
2. Upload it to the Google Colab
3. Run the simulation by executing the necessary cells.
4. Input values for initial balance, stock allocation percentage, bond allocation percentage and oil allocation percentage

## Simulation Parameters
Default values for simulation parameters are provided in the script. You can modify these values directly in the script if needed. The parameters include:

1. num_years: Number of years for which to simulate the portfolio growth. (Default: 10)
2. num_steps_per_year: Number of steps per year. Used for simulating daily growth. (Default: 252)
3. stock_mu: Drift constant for stocks. (Default: 0.07)
4. stock_sigma: Standard deviation of returns for stocks. (Default: 0.2)
5. bond_mu: Drift constant for bonds. (Default: 0.03)
6. bond_sigma: Standard deviation of returns for bonds. (Default: 0.05)
7. oil_mu: Drift constant for oil. (Default: 0.05)
8. oil_sigma: Standard deviation of returns for oil. (Default: 0.1)

## Classes
1. Portfolio: Manages the allocation and growth of a financial portfolio.
2. StockPortfolio: Inherits from Portfolio. Represents a portfolio consisting only of stocks.
3. BondPortfolio: Inherits from Portfolio. Represents a portfolio consisting only of bonds.
4. OilPortfolio: Inherits from Portfolio. Represents a portfolio consisting only of oil.
5. MixedPortfolio: Inherits from Portfolio. Represents a portfolio with mixed allocations to stocks, bonds, and oil.

## Output
The script generates plots showing the growth of the total portfolio balance, as well as the individual balances of stocks, bonds, and oil over the specified simulation period. It also includes a correlation matrix heatmap and drawdown analysis.

## License
This project is licensed under the MIT License - see the LICENSE file for details. 
The MIT License is a permissive free software license originating at the Massachusetts Institute of Technology (MIT). It allows users to do almost anything they want with the code, including modifying, distributing, and using it for commercial purposes, as long as they include the original copyright and license notice. 

## Contact
For any inquiries or assistance, feel free to reach out: Email: hugochwong123@gmail.com Linkedin: https://www.linkedin.com/in/hugochw/
