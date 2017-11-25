Stopwatch
=========

Create a web page that can be used as a stopwatch.

## Functional specification

When the page loads, the following are visible on screen:

- The text "Elapsed: 00:00:00"
- A button with the text "Start"
- A button with the text "Stop"

When the Start button is clicked:

- The timer begins counting up one second at a time.
- The text "Start" should change to "Stop".

When the "Stop" button is clicked:

- The timer stops counting.
- The text "Stop" should change to "Start".

When the "Reset" button is clicked:

- The timer resets to 00:00:00.
- If the timer was counting when Reset was clicked, it continues counting from 00:00:00.

## Hints

### Hint #1

To perform work every _N_ milliseconds, try using [`setInterval`][setInterval].

[setInterval]: https://developer.mozilla.org/en-US/docs/Web/API/WindowOrWorkerGlobalScope/setInterval
