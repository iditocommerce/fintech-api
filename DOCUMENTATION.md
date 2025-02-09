| Endpoint                    | Description                                  | Parameters                                                |
|-----------------------------|----------------------------------------------|-----------------------------------------------------------|
| GET /simple_interest_rate   | Calculate simple interest rates              | - `amount_paid` (float): The amount paid.                 |
|                             |                                              | - `principle_amount` (float): The principle amount.       |
|                             |                                              | - `months` (int): The number of months.                   |
| GET /future_sip             | Calculate Future Value of SIP                | - `interval_investment` (float): The interval investment  |
|                             |                                              | - `rate_of_return` (float): The rate of return.           |
|                             |                                              | - `number_of_payments` (int): The number of payments.     |
| --------------------------- | ----------------------------------------     | --------------------------------------------------------- |
| POST /capm                  | Calculate Capital Asset Pricing Model (CAPM) | - `risk_free_return` (float): Risk-free rate of return.            |
|                             |                                              | - `sensitivity` (float): Asset's sensitivity.            |
|                             |                                              | - `expected_market_return` (float): Expected return of the market. |
| --------------------------- | ----------------------------------------     | --------------------------------------------------------- |
| POST /debt_service_coverage_ratio | Calculate Debt Service Coverage Ratio  | - `revenue` (float): Amount of Company Revenue.           |
|                                   |                                        | - `operating_expenses` (float): Cost of operating expenses.|
|                                   |                                        | - `interest` (float): Amount of interest to be paid       |
|                                   |                                        | - `tax_rate` (float): The tax rate applied.               |
|                                   |                                        | - `principal` (float): Amount of principal borrowed.      |
| -------------------------------   | ------------------------------------   | --------------------------------------------------------- |
| POST /profit_percent | Calculate profit percentage  | - `profit` (float): Total profit earned.           |
|                                   |                                        | - `cost_price` (float): The original price of the item |
| POST /loss_percent | Calculate loss percentage  | - `loss` (float): Total loss occured.           |
|                                   |                                        | - `cost_price` (float): The original price of the item |
| POST /defensive_interval_ratio | Calculate Defensive Interval Ratio        | - `cash` (float): The amount of cash on hand.             |
|                                |                                           | - `marketable_securities` (float): The amount of marketable_securities.|
|                                |                                           | - `net_receivables` (float): The amount of net_receivables.|
|                                |                                           | - `annual_operating_expenses` (float): The amount of annual_operating_expenses.|
|                                |                                           | - `non_cash_charges` (float): The amount of non cash charges.|
| GET /financial_assest_ratio   | Calculate financial assest ratio           | - `current_assets` (float): used up within a short period.                 |
|                             |                                            | - `current_liabilities` (float): debts that are due .       |
|                             |                                              | - `total_debt` (float): aggregate amount of money.                   |
|                             |                                              | - `total_equity`(float): residual interest in the assets.                   |
|                             |                                              | - `net_income` (float): net earnings.                   |
|                             |                                              | - `total_revenue` (float): sum of all sales.                   |
| --------------------------- | ----------------------------------------     | --------------------------------------------------------- |