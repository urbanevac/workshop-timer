# workshop-timer

A simple and customizable Pomodoro timer web application, suitable for workshops like Design Sprints, Foundation Sprints and Lightning Decision Jam.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [How to Use](#how-to-use)
- [Customization](#customization)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project is a Pomodoro timer designed to help small groups manage their time effectively in workshop activities.  It provides a visual timer with customizable work intervals. The timer features start, pause, reset functionality, as well as preset time intervals and a custom time input.  The user interface uses a flip card design to separate the timer display from the settings.

## Features

*   **Start/Pause/Reset:** Control the timer with intuitive buttons.
*   **Preset Timers:** Quickly select common Pomodoro intervals (25m, 20m, 15m, 5m).
*   **Custom Time Input:** Set your own work/break intervals in minutes.
*   **Visual Progress:** A circular progress bar shows the time remaining.
*   **Flip Card Design:** Settings are accessible on the back of the card.
*   **Responsive Design:** Adapts to different screen sizes. (Although not explicitly coded for responsiveness, the styling is somewhat adaptable due to percentages).

## How to Use

1.  Clone the repository: `git clone https://github.com/urbanevac/workshop-timer.git` 
2.  Open the `index.html` file in your web browser.
3.  Use the start/pause button to control the timer.
4.  Use the reset button to reset the timer.
5.  Click the settings cog to access the settings.
6.  Choose a preset time or enter a custom time in the input field.
7.  Click the back button to return to the timer.

## Customization

*   **Time Intervals:**  Use the preset buttons or the custom time input to adjust the work/break intervals.  The code currently only supports setting the *work* interval.  You could extend it to include separate break times.
*   **Styling:** The CSS is embedded in the HTML. You can modify the styles to change the appearance of the timer.  Consider moving the CSS to a separate file for better organization as the project grows.
*   **Functionality:** The JavaScript code can be extended to add more features, such as sound notifications, break timers, and more advanced settings.

## Technologies Used

*   HTML
*   CSS
*   JavaScript
*   Font Awesome (for icons)

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

1.  Fork the repository.
2.  Create a new branch: `git checkout -b feature/new-feature`
3.  Make your changes.
4.  Commit your changes: `git commit -m 'Add new feature'`
5.  Push to the branch: `git push origin feature/new-feature`
6.  Submit a pull request.

## License

MIT
