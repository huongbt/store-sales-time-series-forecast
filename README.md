# store-sales-time-series-forecast

We have dataset of thousands of product families sold at Favorita stores located in Ecuador. We need to predict the sales for these product families for the last 15 days in train data.The train data that we have consists of 1684 days from 2013-01-01 to 2017-08-15. 
Training data includes:

- store_nbr: identifies the store at which the products are sold.
- family: identifies the type of product sold.
- sales: gives the total sales for a product family at a particular store at a given date. Fractional values are possible since products can be sold in fractional units (1.5 kg of cheese, for instance, as opposed to 1 bag of chips).
- onpromotion: gives the total number of items in a product family that were being promoted at a store at a given date.

There are additional files provided in the competition:
- store.csv: Store metadata, including city, state, type, and cluster. cluster is a grouping of similar stores.
- oil.csv: Daily oil price. Includes values during both the train and test data timeframes. (Ecuador is an oil-dependent country and it's economical health is highly vulnerable to shocks in oil prices.)
- holidays_events.csv: Holidays and events with metadata including, date, type, locale, locale_name, description and transferred. 
