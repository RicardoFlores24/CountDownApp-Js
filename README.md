# Coming Soon Page

This is an example of a "Coming Soon" page that displays a message indicating that the website is under maintenance and will be launching soon. The page includes a countdown timer that shows the remaining days, hours, minutes, and seconds until the launch. Additionally, there's a "Learn More" button that visitors can click to find out more information.

## File Contents

The HTML file (`index.html`) contains the following elements:

- **Maintenance Message**: A message is displayed indicating that the website is under maintenance.
- **Launch Title**: A heading is displayed with an emphasized message about the upcoming launch.
- **Countdown Timer**: A countdown timer is displayed, indicating the time remaining until the launch. The countdown timer updates in real-time using JavaScript.
- **"Learn More" Button**: A button that visitors can click to learn more.
- **Rocket Image**: An image of a rocket is displayed, adding a visual touch to the design.

## Countdown Timer

The countdown timer is implemented using JavaScript and updates every second to display the time remaining until the specified launch date. Here's the code snippet that handles the countdown timer:

```javascript
// JavaScript code for the countdown timer
var countDownDate = new Date("Sept 20, 2023 00:00:00").getTime();
var x = setInterval(function() {
    // Calculations to calculate remaining days, hours, minutes, and seconds
    // Update of HTML elements to display the countdown timer
    // Clearing the countdown timer when the launch date is reached
}, 1000);
