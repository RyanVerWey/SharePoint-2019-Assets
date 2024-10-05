# SharePoint World Clock

## Table of Contents
- [General Info](#general-info)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Screenshots](#screenshots)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## General Info
The **SharePoint World Clock** is a customizable, visually appealing clock designed to replicate the professional aesthetic of world clocks commonly found in government offices or corporate environments. It integrates seamlessly into SharePoint pages, offering a familiar and functional way to display multiple time zones. This tool is perfect for organizations with global teams, providing a clear and flexible way to keep track of different time zones right within the SharePoint interface.

## Technologies Used
- **HTML**
- **CSS**
- **JavaScript**
- Compatible with **SharePoint 2010**, **2013**, and **2019**

## Features
- **Easy to Update**: The clock is simple to configure, allowing users to quickly add or rearrange time zones as needed.
- **Clear Layout**: Displays multiple time zones in a clean and easy-to-read format, ensuring accessibility and efficiency for global teams.

## Screenshots
![World Clock Screenshot](World Clock\WorldClockPreview.PNG)

## Setup
1. **Add the Script Editor Web Part:**
   - Navigate to the desired SharePoint page.
   - Enter **Edit Mode** by clicking the gear icon in the top-right corner and selecting **Edit Page**.
   - In the page section where you'd like to display the clock, click **Add a Web Part**.
   - Under the **Media and Content** category, select **Script Editor** and click **Add**.
   
2. **Insert the Clock Code:**
   - After adding the Script Editor, click **Edit Snippet** in the Script Editor web part.
   - Copy the HTML, CSS, and JavaScript code for the World Clock and paste it into the Script Editor.
   - Click **Insert** to apply the code.

3. **Adjust for SharePoint Compatibility:**
   - Ensure that any custom CSS or JavaScript adheres to SharePoint’s content editor policies. Inline styles may need to be updated to avoid conflicts with SharePoint’s existing CSS.
   - Depending on the SharePoint version (2010, 2013, or 2019), slight adjustments to margins, paddings, or widths may be required to ensure the clock displays properly within the page layout.

4. **Publish the Page:**
   - Once the code has been added and tested, click **Stop Editing** and then **Publish** the page to make the World Clock visible to all users.

## Usage
- The **SharePoint World Clock** automatically updates every second, ensuring that the displayed time is always accurate.
- It adjusts for **Daylight Savings Time** based on the system settings, requiring no manual updates for time changes.

## Contributing
Contributions are welcome from anyone who has adapted the **SharePoint World Clock** for their unique SharePoint environment. If you’ve made adjustments or improvements to ensure compatibility, feel free to share your code snippets and solutions.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
