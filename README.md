# Meetup density
The purpose of this repository is to analyze the density of meetup groups in some German cities. The result could be used as a quick comparison of the socialness of cities.

## The data

### meetup data
The number of meetup groups was retrieved in the Chrome console through the following JavaScript expression
```javascript
$x("//*[@id='simple-view']/div[1]/ul[1]//li").length;
```
and executed on [meetup.com](https://www.meetup.com/de-DE/find/?allMeetups=true&radius=6&userFreeform=Kiel%2C+Deutschland&mcId=c1007729&change=yes&sort=recommended).

### population data
The population data is taken from [de.wikipedia.org](https://de.wikipedia.org/wiki/Liste_der_Gro%C3%9Fst%C3%A4dte_in_Deutschland). The translation into English through [en.wikipedia.org](https://en.wikipedia.org/wiki/List_of_cities_in_Germany_by_population).

## License
[Attribution-ShareAlike 3.0 Unported](https://creativecommons.org/licenses/by-sa/3.0/legalcode)