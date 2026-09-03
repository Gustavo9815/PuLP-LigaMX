# Linear Programing applied to Liga MX (Clausura 2025 season)

The world of sports data is increasing everyday. However, most projects are implemented in data-rich leagues, mostly from the US following a tradition of deep statistical analysis from the MLB. Data in soccer is making it's way into the data analysis universe. Now there are libraries to display the pith in the notebook! This said, most soccer projects are made with European leagues (La Liga, The Premier League, Bundesliga). In this project I decided to apply a linear programing approach to the problem of selecting the best possible team in the Mexican Liga Mx.

The project is based on the Clausura 2025 season. The Mexican league does not have a public API for data extraction. Thus, I had to check, clean and merge the data from two sources:

1. [Transfermarkt](https://www.transfermarkt.mx/)
2. [FBREF](https://fbref.com/en/)

The data I used can be fount in "[datos_completos.xlsx](datos_completos.xlsx)"

The project followed the ideas from Philip Kalinda's article "[Keep It Simplex](https://www.philipkalinda.com/ds9.html)" and Tom McNamara's article "[Finding the Best Lazy Fantasy Football Team](https://statnamara.wordpress.com/2021/02/05/finding-the-best-lazy-fantasy-football-team-using-pulp-in-python/)". 
