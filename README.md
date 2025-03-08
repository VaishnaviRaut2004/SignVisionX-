# SignVisionX-
# Sign Language Extension

A Chrome extension designed to enhance accessibility for the deaf community by overlaying sign language translations on video content.

## Features
✅ Seamlessly overlays sign language videos on compatible web pages.  
✅ Lets users switch between different sign language videos effortlessly.  
✅ Lightweight and user-friendly for better accessibility.  

## Folder Structure
```
sign-language-extension/
│── icons/               # Stores extension icons
│── videos/              # Contains sign language videos (MP4 format)
│── background.js        # Handles background tasks and event listeners
│── content.js           # Injects the sign language video overlay into web pages
│── manifest.json        # Defines extension metadata and permissions
│── popup.html           # Provides the user interface for the extension
│── popup.js             # Manages user interactions and video switching
│── sign-player.html     # Dedicated page for playing sign language videos
│── README.md            # Project documentation
```

## Installation Steps
1️⃣ **Download or Clone the Repository**  
   ```
   git clone https://github.com/VaishnaviRaut2004/sign-language-extension.git
   ```
2️⃣ **Enable Developer Mode in Chrome**  
   - Open Chrome and go to `chrome://extensions/`  
   - Toggle on **Developer Mode** in the top right corner.  

3️⃣ **Load the Extension**  
   - Click **Load Unpacked**  
   - Select the `sign-language-extension` folder.  

4️⃣ **Test the Extension**  
   - Click on the extension icon in the Chrome toolbar.  
   - A **sign language video player** should appear in the popup.  

## How It Works
1️⃣ **popup.html** provides the interface for users to interact with sign language videos.  
2️⃣ **popup.js** handles actions like switching videos and managing UI behavior.  
3️⃣ **content.js** injects the sign language video overlay into supported websites.  
4️⃣ **background.js** runs extension events in the background.  
5️⃣ **manifest.json** contains permissions, extension details, and configurations.  

## Future Enhancements
🔹 Automatically detect spoken words in videos and display real-time sign language translations.  
🔹 Integrate AI-based sign language avatars for dynamic translation.  
🔹 Support multiple sign languages and allow users to customize accessibility settings.  

## Contributing
We welcome contributions! Feel free to submit issues or pull requests on GitHub to help improve the extension.  

