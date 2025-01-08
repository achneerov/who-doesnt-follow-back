# Who Doesn't Follow Back on Instagram?

This project helps Instagram users identify who among their followers is not following them back. It compares the list of followers and following data downloaded from Instagram and highlights those who don't follow back. The tool is available for both desktop and mobile usage.

## Features

- **Easy-to-Use Interface**: Upload your Instagram followers and following data and compare them to identify users who don’t follow you back.
- **Step-by-Step Guides**: Detailed guides for desktop and mobile users to walk through the process of downloading the necessary Instagram data.
- **Interactive Table**: Displays a list of users who do not follow you back after comparing the two files.

## Requirements

- **Instagram Account**: You will need to download your Instagram followers and following lists in JSON format.
- **Modern Web Browser**: Compatible with the latest versions of Chrome, Firefox, Safari, and Edge.

## How to Use

### 1. Download Your Instagram Data

Follow these steps to download your Instagram followers and following data:

#### Desktop Guide
1. Go to [Instagram](https://instagram.com) and log in.
2. Open the menu by clicking the three dashes icon.
3. Navigate to Settings > Accounts Center > Your Information > Download Your Information.
4. Request a download for "followers" and "following" information in **JSON** format.
5. Wait for an email from Instagram confirming that your download is ready, then reload the page and download the files.

#### Mobile Guide
1. Go to [Instagram](https://instagram.com) on your mobile device and log in.
2. Follow the same steps as described in the desktop guide.
3. Refer to the [TikTok video](https://www.tiktok.com/@achneerov/video/7336789211862912262) for an overview of how to use the website on mobile.

### 2. Upload Files to Compare

1. On the homepage, click the "Choose File" buttons to upload your **followers** and **following** JSON files.
2. Click the "Compare" button to begin the comparison.

### 3. View Results

Once the comparison is complete, a table will appear listing the users who follow you but whom you don’t follow back.

### 4. Troubleshooting

- **No File Selected**: Ensure you select both the followers and following JSON files before clicking "Compare".
- **File Format Error**: Make sure the files are in the correct JSON format.

## Files

1. **index.html**: The main page where the user uploads their followers and following files.
2. **guide-desktop.html**: A guide for desktop users to download their Instagram data.
3. **guide-mobile.html**: A guide for mobile users to download their Instagram data and use the site.
4. **script.js**: JavaScript file handling the file comparison logic and displaying the results.
5. **styles.css**: Custom styles for the website to make it look professional and clean.

## Custom Styles

### File Upload Button Styling

- Custom styling for file input buttons with hover effect.

```css
input[type=file]::file-selector-button {
  background: #084cdf;
  border-radius: 10px;
  padding: 10px 20px;
  color: white;
}

input[type=file]::file-selector-button:hover {
  background: #0d45a5;
}
```

### Container and Layout

- Flexbox layout for a responsive and clean design, with a sticky footer to ensure copyright visibility.

```css
body {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}
.container {
  flex: 1;
}
.footer {
  text-align: center;
}
```

## License

This project is open-source and can be freely modified and distributed under the MIT License.

## Credits

- Created by **Alexander Chneerov**.
- The guide for using Instagram data was inspired by official Instagram settings and user feedback.
  
Feel free to contribute by opening an issue or a pull request!
