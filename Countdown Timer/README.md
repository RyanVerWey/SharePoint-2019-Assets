# Countdown Timer for SharePoint

This countdown timer script can be added to a SharePoint page using the Script Editor web part. It displays the number of days, hours, minutes, and seconds remaining until a specified target date.

## How to Add the Countdown Timer to SharePoint

1. **Open SharePoint** and navigate to the page where you want to add the countdown timer.
2. **Edit the page** and add a **Script Editor Web Part**.
3. **Copy the HTML, CSS, and JavaScript** from the provided code.
4. **Paste the code** into the Script Editor and save the changes.

## How It Works

- The HTML structure displays the countdown in a `div` container with the ID `countdown`.
- CSS ensures responsive design and styles the countdown.
- JavaScript calculates the difference between the current date and the target date and updates the display every second.

## How to Update the Target Date

To change the countdown target date:
1. Open the Script Editor.
2. Find the following line in the JavaScript section:

   ```javascript
   const countToDate = new Date('2025-07-30T23:59:59').getTime();
   ```
3. Modify the date and time within the new Date() function to your desired end date and time.
4. Save the changes and the countdown will automatically adjust.

## How to Update the Target Date
Ensure all HTML, CSS, and JavaScript are in the same Script Editor block.
If you encounter issues, verify that the target date format follows this structure: 'YYYY-MM-DDTHH:MM:SS'.

This timer will display "Countdown finished" when the target date is reached.