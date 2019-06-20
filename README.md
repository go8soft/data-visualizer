# data-visualizer

The purpose of this repo is to write a Web Javascript Application that generates consequently random numbers and visualizes them in a bar like style.

Demo: http://5.189.138.212:8110/

There are 2 channels – each channel is a random numbers generator. Each channel generates a random number in the range 0 - 10 each second. 
There are "Start" and "Stop" commands. 

Each channel visualizes its data in a separate display in a bar like style. Both displays are placed on a view one above other. Whenever a new number arrives to each display, a new bar is placed on the right on the prior one, straight on the X - axis. The height of the bar corresponds to the generated number.

## Installation

1. Checkout the project:
```
git clone git@github.com:go8soft/data-visualizer.git
```

2. Open the `index.html` file in web browser.

## Configuration

### Change channels number

To change channels number, change value of: 
```javascript
var defaultChannelsNumber = 2
```

### Change charts settings

It is using Google charts: https://developers.google.com/chart/interactive/docs/gallery/columnchart
