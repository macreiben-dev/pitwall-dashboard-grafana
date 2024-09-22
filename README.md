# pitwall-dashboard-grafana

On the shelf Grafana dashboards to use for virtual pitwall.

See those project to be able to use it: 
- [Pitwall Acquisition Plugin](https://github.com/macreiben-dev/pit-wall-acquisition) 
- [Pitwall API](https://github.com/macreiben-dev/pit-wall-api) 

Each dashboard requires you to select a car and a pilot in the top left comboboxes.

![Selecting source car and pilot](./docs/assets/screenshot_select_source_01.png)

## Overview

### Consistency and fuel

![Overview part 01](./src/overviews/assets/overview_fr_2024-09-22_part01.png)

### Race condition
![Overview part 02](./src/overviews/assets/overview_fr_2024-09-22_part02.png)

### Fuel

![Overview part 03](./src/overviews/assets/overview_fr_2024-09-22_part03.png)

### Tyres analysis

![Overview part 04](./src/overviews/assets/overview_fr_2024-09-22_part04.png)

## Pits

Displays an overview of who is in the pitlane. 1 means that the car is in the pitlane, 0 out. 

Select the source car and pilot at the top left of the screen to feed the dashboard.

![Pits](./src/pits/assets/screenshot_pit_01_2024-09-22.png)

### Display pits information for one car

The focus on car allows you to select one car to feed the top right graph.

To do, on the top of th dashboard fill the *FocusOnCar* combobox.

![Pits focus on car](./src/pits/assets/screenshot_pit_01_2024-09-22_focusOnCar.png)
