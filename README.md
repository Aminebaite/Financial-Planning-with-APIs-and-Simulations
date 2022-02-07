In this project, we take the rule of a fintech consulting firm that focuses on projects to benefit local communities. We just won your first contract with a large credit union. The project entails building a tool to help credit union members evaluate their financial health. Specifically, the credit union board wants the members to be able to do two things. First, they should be able to assess their monthly budgets. Second, they should be able to forecast a reasonably effective retirement plan based on their current holdings of cryptocurrencies, stocks, and bonds. The chief technology officer (CTO) of the credit union wants you to develop a prototype application to present at its next assembly.
We ll create two financial analysis tools by using a single Jupyter notebook:

A financial planner for emergencies. The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.

A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

We will use the information from the Monte Carlo simulation to answer questions about the portfolio in your Jupyter notebook.

##Technologies This application is developed on Python. It incorporates the 7 following required  dependencies. These dependencies include the folowing imports:
1.os =
2.requests =
3.json =
3. pandas =
4. dotenv =
5. alpaca_trade_api =
6.MCForecastTools =
7.%Matplotlib inline =

##Installation Guide The following PIP installation must be performed before running the program. They include:
Jupyter lab

#Cotributor : Amine Baite Email: aminebaite@gmail.com
