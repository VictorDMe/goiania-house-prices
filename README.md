# goiania-house-prices
Model developed for predicting house prices in Goiânia.

## Metric Used

$$ \sqrt{\frac{1}{n} \sum_{i=1}^{n}(y_i - \hat{y}_i)^2} $$

## Notes

It was not considered the ADDRESS column because it would require a lot of work to convert it into latitude and longitude features.

## Models

| Model                   	| RMSE   	|
|-------------------------	|--------	|
| Random Forest Regressor 	| 125143 	|
| Linear Regressions      	| 171934 	|
