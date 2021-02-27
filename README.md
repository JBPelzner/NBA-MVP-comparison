# The NBA's Most Valuable MVP (2013-2018)
### _Final Project for UC Berkeley MIDS Program, W209 Data Visualization_

_By Isa Chau and Julian Pelzner_

[Link to the project website](http://people.ischool.berkeley.edu/~jbpelzner/NBA-MVP-comparison/)

[Link to a video demo of the project](https://www.youtube.com/watch?v=drUEo_xmK04&feature=youtu.be)




![](nba_mvp.gif)




This project is a visual story told with NBA players' statistics that investigates who the most valuable "Most Valuable Player" was out of the NBA's 2013 to 2018 seasons. The first 4 pages explain how we selected the best player of the cohort, and the last 4 pages show some statistics that explain what makes him stand out even among the best of the best.

Isa created the visualizations titled **MVP Basics** through **The Real MVP**. 
> They identified that Stephen Curry's 2015-2016 season showed the greatest contribution of any MVP to their respective team, and that Curry performed better than the other MVPs (incluing himself) in the categories of Ofensive Rating, Defensive Rating, and Net Rating.

Julian created the visualizations titled **Overview Revisited** through **eFG %**.
> He highlighted the underlying statistics that could be used to explain Stephen Curry's spectacular 2015-2016 season. These visualizations show that Curry had the highest Box Plus/Minus of any player in the league during 2013-2018, mostly because of his league-leading Offensive Box Plus/Minus values. Additionally, they show that Stephen Curry's exceptional 3-Point Shooting ability at his volume of shots and overall productivity levels are the primary reason why his True Shooting Percentage (and related Effective Field Goal Percentage) were also higher than any other MVP's.


## Instructions to view this project on your local machine
From your computer's command prompt, create a directory and enter it.
```
mkdir NBA-MVP
cd NBA-MVP
```
Clone this repository.
```
git clone https://github.com/JBPelzner/NBA-MVP-comparison.git
```
Enter the website's directory.
```
cd NBA-MVP/html-code
```
Start a local server.
```
python -m http.server 8080
```
View the website in a web browser with the following url.
```
localhost:8080
```
