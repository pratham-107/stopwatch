
### index.html

The main HTML file that contains the structure of the stopwatch application. It includes buttons to start, stop, and reset the timer.

### style.css

The CSS file that styles the stopwatch application, including the layout, colors, and button styles.

### script.js

The JavaScript file that contains the logic for the stopwatch functionality, including starting, stopping, and resetting the timer.

## Usage

1. Open `index.html` in a web browser.
2. Click the "Start" button to start the stopwatch.
3. Click the "Stop" button to stop the stopwatch.
4. Click the "Reset" button to reset the stopwatch to 00:00:00.

## Functions

- `updateTime()`: Updates the displayed time on the stopwatch. It converts the elapsed seconds into a formatted time string (HH:MM:SS) and updates the text content of the stopwatch element.

- `start()`: Starts the stopwatch by setting an interval that increments the `seconds` variable every 100 milliseconds and calls `updateTime()` to refresh the displayed time.

- `stop()`: Stops the stopwatch by clearing the interval set by the `start()` function.

- `reset()`: Resets the stopwatch by clearing the interval, setting the `seconds` variable to 0, and calling `updateTime()` to reset the displayed time to 00:00:00.

## License

This project is licensed under the MIT License.
