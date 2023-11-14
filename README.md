<p align="center">
  <img src="https://raw.githubusercontent.com/dampestwriter/Orange-ontime-offline/main/image.png" width="154">
  <h1 align="center">Orange-ontime-offline</h1>
<p>
    <p align="center">
    <a href="https://github.com/timgrossmann/InstaPy/blob/master/LICENSE">
      <img src="https://img.shields.io/badge/license-GPLv3-blue.svg" />
    </a>
    <a href="https://www.python.org/">
    	<img src="https://img.shields.io/badge/built%20with-Python3-yellow.svg" />
    </a>
    <a href="https://github.com/dampestwriter">
      <img src="https://img.shields.io/badge/by-dampestwriter-6c13b1?style=flat&labelColor=grey" />
    </a>
    <a href="https://github.com/dampestwriter">
    	<img src="https://img.shields.io/badge/with-%E2%9D%A4%EF%B8%8F-red" />
    </a>
    <p>
<p>
a simple Discord bot written in Python that allows users to reorganize and display their data whenever they need.

This project is for educational purposes and it's not correleated in any way to Marangoni.

Project is not sharing any kind of sensitive, private or copyrighted data.

# Index:
**Table of Contents:**
- [Requirements](#requirements)
- [Getting your Discord Token](#getting-your-discord-token)
- [Python Libraries](#python-libraries)
- [Configuration](#configuration)
- [Disclaimer](#disclaimer)



## Requirements

To get things up and running, ensure you have the following:

• [Python](https://www.python.org/downloads/) installed into your system.

• [Discord](https://discord.com/) account.

• iOS device.


## Getting your discord token

Before we start we need to [Create](https://discord.com/developers/applications?new_application=true) your new discord application.

-  Navigate to Url generator under the OAuth section.
-  Select "bot" as "Scopes."
-  Mark all "text permission" under "Bot permission."
-  Copy/Paste generated URL into your browser.
  
Once done:

-  Go to Bot section and click reset token.
-  Your token goes into `Orange-ontime-offline.py` code (line 14).


## Python libraries

Execute the following commands in your terminal or command prompt to install the necessary Python libraries:

```
pip install discord.py
```
```
pip install python-barcode
```

## Configuration

Data is not packaged into code's project for mentioned reason, end user is the only one responsible to get, secure and manager their own. 

If something is unclear you may need to do some research as dev won't assist you through the process.

-  [Download](https://proxyman.io/) & install Proxyman on your system / iOS device
-  In order to capture data you need to install certificate, official [guide](https://docs.proxyman.io/debug-devices/iOS-device).
-  Open Marangoni's app's and capture some data.
-  You'll notice that everytime you click something, traffic will show into your computer, tap your planning and find where data came from.
-  Once you find out the url click it, then navigate on Response, enable SSL Proxying.
-  Close Marangoni's app's, relaunch it and navigate again into timetables, if all done correctly you will see into new Responses, you guessed, your data.
-  Save it as `data.json` (replace extension if any) into your icloud drive, open file's app and share `data.json` with your computer.
-  Now, specify the path where you stored the data.json file into the Orange-ontime-offline.py code (line 12).
-  Hint, if you don't know how to get the `path` of `data.json`, drag and drog 'data.json' into terminal app, `path` will apper automatically.
-  Scan your badge and write the code into `Orange-ontime-offline.py` code (line 13)
-  Now you're all set to run your Discord bot.


## Running

Launch Terminal or command prompt, write:
```
python3 
```
followed by your `Orange-ontime-offline.py` file's `path`.

To get familiar with commands, go to your discord seever and type `!ohelp` .

## Disclaimer

This tool, Orange-ontime-offline, is designed exclusively for educational purposes and is not associated with Marangoni in any manner. The project strictly refrains from involving the sharing of sensitive, private, or copyrighted data.

Users are urged to thoroughly read and comprehend the following points:

### Data Usage Responsibility

Orange-ontime-offline empowers users to reorganize and present data of their choice. Users assume complete responsibility for the selection, usage, and management of the displayed data. It is imperative to use the app responsibly, ensuring compliance with applicable laws and the terms of service of the platforms they interact with.

### Education Emphasis

Orange-ontime-offline is specifically crafted for educational purposes. Users are encouraged to explore its functionalities to enhance their understanding of data organization and presentation. The developer emphasize that the tool is not intended for misuse or unethical use.

### Developer Disclaimer

The developers of Orange-ontime-offline provide the following disclaimer:

- **Accuracy, Legality, and Appropriateness**: The developers are not responsible for the accuracy, legality, or appropriateness of the data displayed by the app.

- **Responsible and Ethical Use**: Users are strongly encouraged to use the app responsibly and ethically. Be mindful of the data you choose to display and adhere to applicable laws and terms of service.

- **Assumption of Responsibility**: By using Orange-ontime-offline, you agree to assume full responsibility for the data you choose to display and how you use the app. The developers disclaim any liability for the use or misuse of the app or the data it displays.

- **Code Disclaimer**: The code is provided as-is, without warranties or guarantees. If you have any questions or concerns about the code, please contact the developers for assistance.

- **Non-Commercial and Open-Source**: Orange-ontime-offline is a non-commercial and open-source project.

- **Educational Purposes**: The guide to retrieve data is solely for educational purposes and does not involve accessing or sharing any API.
  
- **Images Licenses**: Attribution-NonCommercial 4.0 International License.


For any inquiries or assistance, feel free to contact .



