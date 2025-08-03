# Countdown Timer

A simple Python script that functions as a countdown timer. Enter the desired time in seconds, and the program will display the remaining time in `HH : MM : SS` format, updating every second until time's up.

## Technologies Used

- Python 3
- Built-in `time` module

## Features

- Accepts user input for countdown duration (in seconds)
- Displays time in hours, minutes, and seconds
- Updates every second using `time.sleep(1)`
- Prints a final message when the countdown ends

## Installation

No external dependencies required. Just make sure Python 3 is installed.

##  Usage

1. Clone the repository or copy the script.
2. Run the script using Python:

```bash

python countdown.py

```

3. Enter the countdown duration in seconds when prompted.
4. Watch the timer tick down in real time!


## Example Output

```bash

Enter the time in seconds :  90
00 : 01 : 30
00 : 01 : 29
...
00 : 00 : 01
TIME'S UP!

```

## Future Improvements
- Add GUI using Tkinter
- Allow input in HH:MM:SS format
- Add sound alert when time is up

## License

This project is open-source and available under the MIT License.
