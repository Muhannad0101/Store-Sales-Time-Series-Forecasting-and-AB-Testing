## Project Overview: Time Series Forecasting of Store Sales with Holiday, Event, and Transaction Analysis
Objective: To build a predictive model for forecasting store sales, integrating an analysis of holidays, special events, and transaction trends.

#### Datasets Utilized:

- Train.csv: Features historical sales data, detailing store number (store_nbr), product type (family), promotional status (onpromotion), and sales figures.
- Test.csv: Used for future sales predictions, mirroring the training data structure.
- Stores.csv: Offers metadata about each store, including location, type, and cluster classification.
- Oil.csv: Provides daily oil prices, essential for understanding economic conditions in oil-dependent Ecuador.
- Holidays_Events.csv: Lists holidays and events, emphasizing the transferred column for officially altered holiday dates.
- Transactions Data: Records the number of transactions for each store, offering insights into customer traffic and purchasing behaviors.
#### Methodology:

- Employed time series modeling to forecast sales based on historical data.
- Conducted A/B testing to evaluate the influence of holidays and events on sales patterns.
- Analyzed the interplay of promotions, store-specific factors, and transaction volumes on sales.
#### Key Challenges:

- Handling fractional sales and a variety of product families.
- Incorporating external economic indicators, like oil prices, into the sales forecast.
- Adapting the model to account for the complexities of holiday and event scheduling, including transferred and additional holidays.
- Integrating transaction data to gain a comprehensive view of customer engagement and spending.

#### Outcome:
The model effectively predicts sales trends, highlighting the significant impact of holidays, events, promotions, and customer transaction patterns. These insights are crucial for optimizing inventory management, marketing strategies, and overall store performance.


![Capture1](https://github.com/Muhannad0101/Store-SalesTime-Series-Forecasting-and-AB-Testing/assets/102443619/1e1fcf15-30bd-4891-9254-7fbafa85111c)
![Capture4](https://github.com/Muhannad0101/Store-SalesTime-Series-Forecasting-and-AB-Testing/assets/102443619/e449d24a-d393-41bf-913d-dbfe7d517822)
![Capture3](https://github.com/Muhannad0101/Store-SalesTime-Series-Forecasting-and-AB-Testing/assets/102443619/bab22d5e-675e-4936-a9de-3ba4d70e2a6f)
![Capture2](https://github.com/Muhannad0101/Store-SalesTime-Series-Forecasting-and-AB-Testing/assets/102443619/2558b6b1-3023-4ffe-939a-eacb730dce9c)
