CRYPTOCURRENCY PRICE PREDICTION
https://github.com/samuzaffar99/Crypto-Price-Pred
Project by -
18K0169 Syed Abdullah Muzaffar
18K1103 Muhammad Ahmed Khan
18K0357 Ali Azlan Aziz

The following files/folders are present:
-Crypto_ProjectReport.docx --The project report
-fbprophet.ipnyb --Contains the main prediction model
-data/ --Contains the dataset for various cryptocurrencies
-extra/ --Contains rejected models/test files

The following models/techniques were used/explored:
- Facebook's Prophet Model - The main prediction model used in this project.
- Time Series Analysis
- ARIMA
- SARIMAX
- XGBoost

How to use the model?

-To run the fbprophet.ipnyb file, one must first install all the required dependencies (in the import section).
The first few cells will load the dataset.
A list of coins whose dataset is available will be shown:
	Aave
	BinanceCoin
	Bitcoin
	Cardano
	ChainLink
	Cosmos
	CryptocomCoin
	Dogecoin
	EOS
	Ethereum
	Iota
	Litecoin
	Monero
	NEM
	Polkadot
	Solana
	Stellar
	Tether
	Tron
	Uniswap
	USDCoin
	WrappedBitcoin
	XRP

-Set the variable coin to the string of the Cryptocurrency's name that you went to predict.
-Run all the cells
-Cell #12 will have the predictions shown in a graph
The black line is the actual data, the blue line is the prediction. The light blue region is the confidence interval.
-Other details are also shown (performance metrics, RMSE, seasonal trends). You may need to scroll some diagrams.
-Estimated time to run the notebook locally is 5-10 mins on an 8-Core CPU. It is advised to run it in google colab.