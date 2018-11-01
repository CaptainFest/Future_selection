# Future_selection

## Data:
<li> 99 objects with 10000 features train dataset
<li> 99 objects with 10000 features test dataset

## Classificator
<li> Random forest from sklearn library

## Used future selection methods:
<li> Filters: <li\>
1. feature_importances_ method from sklearn library
2. euclidean distance (data must be normalized)
3. coefficient correlation
<li> Wrapper: <li\>
1. Forward selection

## Results

1. Score without future selection:     0.7373737373737373
2. Score with feature_importances_:    0.797979797979798
3. Score with euclidean distance:      0.8080808080808081
4. Score with coefficient correlation: 0.8282828282828283
5. Score with wrapper:                 0.7777777777777778

<img src="https://imgur.com/awP2FBW.jpg">
