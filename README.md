# Stoch price prediction With Machine Learing

scikit-learn does not provide method to deal with time series data, but here we try to get time series prediction using "RandomForestRegressor". This is time series, data depend on other data(multilinearity), Therefore we can't use regression we can't predicted holidays, becase these days haven't stock market.

I try to forecast **Apple** stock price using **yahoo finance** stock price dataset. I use *close* stock price to forecast.
