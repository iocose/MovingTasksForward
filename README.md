# MovingTasksForward


## Requirements
You need to be able to run a local server. If you do not want to set up apache or nginx, have a look at this [quick alternatives](https://github.com/processing/p5.js/wiki/Local-server)

You need a Trello Account containing the board with your tasks, and an [API key](https://trello.com/app-key). As "allowed origin" for that API Key, enter the address of your local server, for example `http://localhost:5000`.

Get the ID of the board containing the tasks that you want to move forward.

## Installation
Download and unzip this repository. Open the file index.html, change the value of the variable `const BOARD_TO_MOVE_FORWARD_ID = "YOUR_BOARD_ID";` with the ID of your board.

