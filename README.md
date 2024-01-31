# AI-Content-Generator
 
# Features:
* Text Generation<br>
* Image Analysis<br>

# Installation

Follow the steps mentioned below to install and run the project. You may find more details about Gemini from Google's official documentation.

1. Clone or download the repository
2. You will have to obtain your free API key from [Get API Key.](https://makersuite.google.com/app/apikey) and paste it into the .env file in place of `your-api-key`
3. Open cmd in the same directory and install Node using `npm i` command
4. Run the "gemini.js" server by `npm start` command from terminal or using VS Code's run feature.
5. In "Modules" folder you will find the text and image pages. You can open them and use their respective functionality

# Working:
- Gemini Pro and Gemini Pro Vision models have been used for text and image processing<br>
- Both functionalities have separate HTML pages<br>
- Image Analysis makes use of a hardcoded prompt "Describe this image". You can change it inside the JavaScript part of the image.html page<br>
- The prompt for image analysis can also be made dynamic to accept input from the user. I have not done it here but it is possible<br>
- Image needs to be lesser than 4MB. This is Gemini's current limitation<br>

