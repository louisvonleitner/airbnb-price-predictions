# airbnb-price-predictions
Guess the prices of AirBNB accomodations in Lissabon using publically available data.

One model uses amenity data, for example if an oven is in the apartment or not.

One model uses location data, (x, y) coordinates to see pricing trends over neighbourhoods.

One model uses scalar data like the number of beds.

The models were ensembled by using another small neural network and a final test MAE of 22 was reached.
