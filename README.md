# Boobosang(부보상, 負褓商)
Problem description and solution of the **Boobosang problem** which is the final project of the lecture Operations Research 1 in 2019 Fall semester.

## Who is a Boobosang?
**Boobosang** is a retailer who carry a bundle on one's back for trading regional products in [Joseon Dynasty](https://en.wikipedia.org/wiki/Joseon).

<img src="https://user-images.githubusercontent.com/50398078/74434655-2f1a1e80-4ea6-11ea-9562-0c79829b9bf5.png">

## Problem Description
There is a retailer man who will leave **Pyongyang** and go to **Busan**. The man can buy the regional product from each region and sell the item to person in other region. He wants to maximize his profit.

He can visit the following 7 cities sequentially: **Kaesong, Seoul, Anseong, Daejeon, Geumsan, Seongju** and **Daegu**. He start journey in **Pyongyang** and end in **Busan**.

He decides which cities to visit in consideration of the value of local specialties.

For example, if the pear which is a specialty in Anseong is undervalued or the profit is low due to low demand for the pear, he can skip to visit Anseong and go straight to Daejeon.

He can't move in opposite direction. Hence, he is able to move from Seoul to Anseong, but not to Kaesong.

- [1] Prices of specialty products are as high as the distance from purchased areas. See the given data.
- [2] Each specialty has a different weight, and the sum of weight he can carry is up to 100 kilograms.
- [3] There is a limit to the quantity to purchase available for each local specialty. See the given data.
- [4] The more he carries, the longer he travels, the more moving costs increase. His movement cost is `$0.1` per 1 km, and another `$0.1` (additional cost) if he walks 1km carrying a kilogram of specialty products. If he move 10km with 10kg bundle, the cost of moving is $11.
- [5] When he arrives in a new city, he sells as many specialties as he wants and then purchases the specialties of the city he arrived in.
- [6] When he moves to the next city after completing a transaction in the city, there is a cost of transportation to the next city.
- [7] He starts with a capital of $400 in the Pyongyang.
- [8] He can't make debt. In other words, his profit is non-negative in any point of time.


## Formulation & Modeling
[here](https://github.com/taegyumin/Boobosang/blob/master/Formulation_and_Modeling.ipynb)

## Computation & Result
[here]()
