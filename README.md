# Future_selection

**IF YOU DONT SEE THE CODE YOU SHOULD GO HERE** <https://nbviewer.jupyter.org/github/CaptainFest/Future_selection/blob/master/code/Future_selection.ipynb>

## Data:
<li> 99 objects with 10000 features train dataset
<li> 99 objects with 10000 features test dataset

## Classificator
<li> Random forest from sklearn library

## Used future selection methods:
<li> Filters: </li>
  <ol>
    <li> feature_importances_ method from sklearn library </li>
    <li> euclidean distance (data must be normalized) </li>
    <li> coefficient correlation </li>
  </ol>
<li> Wrapper: </li>
  <ol>
    <li> Forward selection </li>
  </ol>

## Results

1. Score without future selection:     0.7373737373737373
2. Score with feature_importances_:    0.7474747474747475
3. Score with euclidean distance:      0.8080808080808081
4. Score with coefficient correlation: 0.8282828282828283
5. Score with wrapper:                 0.7676767676767676

<img src="https://imgur.com/awP2FBW.jpg">
