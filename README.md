# Team 19 - Improving Open Accessibility Tools
We have taken an existing browser extension called ReadAloud and added a few functions to increase its accessibility to more user groups. While this extension is already targeting users that may have dyslexia, reading impairments or just users that don't want to read, we want to expand upon this and add another option for users that don't want to interact with the extension using their mouse, or may be less tech savvy. We have added a system which allows the user to speak into their system to control the extension compared to pressing the buttons on the screen. We have also added a tutorial page which will further introduce the extension and teach any users that may be confused on how to use the extension.

## Instructions on setting up the extension in Chrome / Microsoft Edge
### [Chrome](https://developer.chrome.com/docs/extensions/mv3/getstarted/development-basics/) *images taken directly from this link
1. Navigate to the Extensions page by either inputting chrome://extensions in the URL of a new tab
    - Alternatively get there by clicking on the Extensions menu puzzle button and select Manage Extensions at the bottom of the menu.
    - Another alternative is to click More Tools and then select Extensions
2. Enable developer mode by the toggle switch next to Developer Mode
3. Click the Load unpacked button and select the folder in which the extension has been cloned to
	
 ![image](https://github.com/itsyefan/SOFTENG702-read-aloud-extension/assets/79778710/148ce7e5-3494-4ac2-9a4e-b1551c259b23)


### [Edge](https://learn.microsoft.com/en-us/microsoft-edge/extensions-chromium/getting-started/extension-sideloading) *images taken directly from this link
1. Navigate to the Extensions page by selecting Settings (the ... on the top right of the screen) and then clicking on Extensions
    - Alternatively, navigate to a new tab and input edge://extensions in the URL
2. Enable developer mode by the toggle switch next to Developer Mode on the bottom left of the screen
3. Click the Load unpacked button and select the folder in which the extension has been cloned to

![image](https://github.com/itsyefan/SOFTENG702-read-aloud-extension/assets/79778710/af9c8c2e-78de-42c0-9635-660b2792698d)
![image](https://github.com/itsyefan/SOFTENG702-read-aloud-extension/assets/79778710/6876a998-7fb7-4f4e-a47b-07d9d37686b3)
![image](https://github.com/itsyefan/SOFTENG702-read-aloud-extension/assets/79778710/31440a98-0e24-4ca6-b16e-8bacedcc9d8a)

After the extension is successfully loaded into the desired browser, it will be accessible from the extensions tab. From there the extension can be used normally.

## Extension Instructions
This extension will work on proper http web pages, such as google search results, Wikipedia, Youtube and so on. Pages like a new tab, or settings within the browser will be invalid. 
Once on a valid web page, press ```alt + p``` to activate the extension and start reading the web page.

To allow the extension to hear your voice command, press ```alt + v```. The browser may not have allowed for microphone access, so please navigate to the Read Aloud tab on the left of your tab list 

![image](https://github.com/itsyefan/SOFTENG702-read-aloud-extension/assets/79778710/69c227eb-b074-4e2d-aa9b-8c3df172ce2d)

If you see a little red x next to a microphone at the right side of the URL bar, please click on that to toggle access for your microphone. After enabling access, the voice commands will now work.
![image](https://github.com/itsyefan/SOFTENG702-read-aloud-extension/assets/79778710/a037b274-17b3-4be6-8029-acdd600787ac)
![image](https://github.com/itsyefan/SOFTENG702-read-aloud-extension/assets/79778710/637818b2-4aac-420b-a828-d2ad2331da77)

The extension will stop listening after each command, therefore you will have to press ```alt + v``` everytime you would like to use a voice command.

Current valid voice commands are:
- play
- pause
- stop
- rewind
- forward
- [help](https://softeng-702-read-aloud-extension-q49a.vercel.app) 

Due to browser limitations, only 4 keyboard default commands are able to be set. The original extension had keyboard commands for play/pause, stop, rewind and forward. We have removed the default command for rewind and changed it to a default command for voice commands. If you would like to change the extension shortcut commands to your liking please go to ```chrome://extensions/shortcuts``` or ```edge://extensions/shortcuts``` depending on your browser choice.

## Experiment Storyboard and Preparations
![image](https://github.com/itsyefan/SOFTENG702-read-aloud-extension/assets/79778710/5f4f5b15-38ec-45e9-bd7f-8f602e317ff3)

During the introduction of our experiment for the participant, a pre-recorded video with a small demo and instructions based on our [script](https://docs.google.com/document/d/1XPz83qeahT5E2BYfBPixCSbKpcWbsDBuqz34G8cD9W8/edit?usp=sharing) will be played to ensure all participants receive the same information.

This is our questionnaire based on the above storyboard: [Google Form Questionnaire](https://docs.google.com/forms/d/e/1FAIpQLSf8wenGA_b4MQ2ju9mN3Zl2NCuos-E2jDCURgmKK4V0yJHE7A/viewform?usp=sharing)


