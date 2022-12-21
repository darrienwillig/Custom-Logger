# Custom Logger
	

## Technologies
 [Moment](https://momentjs.com/)<br/>
 [Chalk](https://github.com/chalk/chalk)
ㅤ

## How to install
Install moment :

    npm install -g moment

Install chalk version 4.1.2:

    npm install -g chalk@4.1.2

## How to use

At the top of your file:

    const log = require(filpath/to/logger.js)

Below will be examples on different types of colors:

    log(x, 'error) -> Red
    log(x, 'success') -> Green
    log(x, 'info') -> Blue
    log(x, 'yellow') -> Yellow
    log(x, 'lightpurple') -> Light Purple
    log(x, 'lightgray') -> Light Gray
    log(x, 'debug') -> Purple
    log(x, 'reset') -> Clear
    

## Screenshot of colors

   <img src="https://i.imgur.com/K6IWKI9.png"/>
