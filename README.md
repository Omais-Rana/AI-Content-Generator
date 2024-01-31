# AI-Content-Generator
 
# Features:
* Text Generation<br>
* Image Analysis<br>

# Installation

Follow the steps mentioned below to install and run the project. You may find more details about Gemini from Google's official documentation.

1. Clone or download the repository
2. You will have to obtain your free API key from [Get API Key.](https://makersuite.google.com/app/apikey) and paste it into the .env file in place of `your-api-key`.<br>
3. In the 

# Working:
- You will have to obtain your free API key from [Get API Key.](https://makersuite.google.com/app/apikey) and paste it into the .env file.<br>
- You may use the following account credentials to login. The sign up option is not accessible but the module has been built.<br>

```
User: user@user.com
Pass: secret
```

<h2>General uses</h2>
- Provides the option of downloading codes as PNG files in the user's default Download directory.<br>
- In storage/app/qrcodes or /barcodes the codes are automatically stored (as PNG) after being generated.<br>
- Original URLs and their shortened versions are stored in the database with the table named as "url_mappings". <br>
- The prefix "sho.rt/" is used in shortened links which can be changed from URL controller and the web route files.


    
# Links:
[QR Code Package.](http://www.simplesoftware.io/#/docs/simple-qrcode) <br>
[Barcode Package.](https://github.com/picqer/php-barcode-generator) <br>
[Laravel Template.](http://www.github.com/nasirkhan/laravel-starter)
