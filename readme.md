# Player Recommender Tool :soccer:

### Search for similar players in the Big 5 European leagues.

:bar_chart: Data credits: [FBref](https://fbref.com/en/) / [StatsBomb](https://statsbomb.com/). All units per 90.

_**Outfield players dataset**_ - Total number of players : **2040**. Features for each player : **164**. Minimum 90s played : **3**.

_**Goal-keepers dataset**_ - Total number of players : **173**. Features for each player : **40**. Minimum 90s played : **1.5**.

![demo](demo.png)

:heavy_exclamation_mark: :bulb: **Note:** The similarity values are totally based on the **statistical output of players**, in this case 40 statistical features for GK's and 164 features for outfield players. The similarity values are not probabilities but resemble more to percentiles (cosine distances normalized to the range 0 to 100).

:snake: Principal Component Analysis (PCA) was used for dimensionality reduction. The detailed blog covering the entire lifecycle of the project in detail including data preprocessing, exploratory data analysis.
