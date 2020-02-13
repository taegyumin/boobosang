# Boobosang(부보상, 負褓商)
Problem Description and Solution of the 'Boobosang' which is the final project of the lecture 'OR1' in 2019 Fall semester.

## What(Who) is Boobosang?
**Boobosang** is a retailer man who carry a bundle on one's back for trading regional products in [Joseon Dynasty](https://en.wikipedia.org/wiki/Joseon).

<img src="https://user-images.githubusercontent.com/50398078/74434655-2f1a1e80-4ea6-11ea-9562-0c79829b9bf5.png">

## Problem Description
There is a retailer man who will leave **Pyongyang** and go to **Pusan**. The man can buy the regional product from each region and sell the item to person in other region. He wants to maximize his profit.

He can visit the following 7 cities sequentially: **Gaesung, Seoul, Anseong, Daejeon, Geumsan, Sungju and Daegu**. He start journey in 'Pyongyang' and end in Pusan.

He decides whether to visit the city in consideration of the value of local specialties.

For example, if the pear which is a special product in Anseong is undervalued or the profit is low due to low demand for the pear, he can skip to visit Anseong and go straight to Daejeon.

He can't move in opposite direction. Therefore, he is not able to move from Seoul to Pyongyang or to Gaesung.

- [1] Prices of specialty products are as high as the distance from purchased areas. (See the given data.)
- [2] Each specialty has a different weight, and the sum of weight he can carry is up to 100 kilograms.
- [3] There is a limit to the quantity to purchase available for each local specialty.(See the given data.)`
- [4] The more he carries, the longer he travels, the more his moving costs increase. His movement cost is `$0.1` per 1 km, and another `$0.1` (additional cost) if he walks 1km carrying a kilogram of specialty products. If he move 10km with 10kg bundle, the cost of moving is $11.
- [5] When he arrives in a new city, he sells as many specialties as he wants and then purchases the specialties of the city he arrived in.
- [6] When he moves to the next city after completing a transaction in the city, there is a cost of transportation to the next city.
- [7] At the beginning point Pyongyang, he has $400.
- [8] He can't make debt. In other words, his profit is non-negative at any point.


## Formulation and Modeling
### decision variables
    cities C = {0:Pyongyang, 1:Gaesung, 2:Seoul, 3:Anseong, 4:Daejeon, 5:Geumsan, 6:Sungju, 7:Daegu, 8:Pusan}
    V_c = 1 if he visit the city c else 0
    x_ij = the amount he buy at city i and sell at city j

### Objective Function

### Constraints

## Code

## Result
### Optimal Solution
