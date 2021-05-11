# Market_Basket_Analysis-Retail

**Datasets:**
1. Products catalog: contains all the available information regarding all the products sold by the client and competitors.
2. Stores catalog: contains all the information available about the stores and distributors that sell the products.
3. Sellout sales files: contains history of sales and sellout price (from retailer to final consumer) for each product and store, for two different suppliers.
4. Sellin sale file: contains the sales history and sellin price (from manufacturer to retailer) for each product and store.

SellOut is the information of the sales processes that occur from the distributors of the client towards final customers (i.e. when someone buys a product from the client in a
supermarket). SellIn is the information of the sales processes of the client towards its distributors (that is, when a supermarket buys a batch of products from the client in order to sell them to final customers).

**Objective:** 
The objective is to clean and analyse the data, and generate a data structure that is easily searchable to be able to generate models afterwards. An example of a query from this data structure would be: "I need all the sellout and sellin records between the dates X and Y for products A, B, C and D in this specific list of stores: T1, T2, T3, T4, T5 and T6", where X, Y, A, B, C, D, T1, T2, T3, T4, T5, and T6 are variables. This requires that the data is not only clean, but also consistent and perfectly organized.

Finally, once the data structure has been generated for query, an initial data exploration could be included to provide a first insight into the dataset.
