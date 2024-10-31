# Sound Transcriber User Guide

This user guide aims to provide you with a comprehensive understanding of Sound Transcriber and help you make the most of its features.

We highly recommend reading this guide to ensure optimal usage of the program.

## Introduction to Sound Transcriber:

Sound Transcriber is an accessible audio-to-text conversion program designed to transcribe audio and video files, it offers support for extracting subtitle files and more.

Developed by Mahmoud Atef, Ahmed Bakr, and Qais Alrefai from the TecWindow team.

## Features:

Sound Transcriber offers the following features:

- Conversion of audio and video files to text using various transcription services.
- Saving conversion results as .txt and .doc files or as .SRT subtitle files.
- Convert videos from platforms like YouTube, Facebook, and X by downloading the file directly, with an option to save the file for easy access and future use.

## Planned features:

We have several planned features in the pipeline, including:

- Translation of conversion results into multiple languages.
- Spell check functionality with dictionaries.
- Conversion of results into audio using text-to-speech engines.

## Supported services:

The software currently only supports online conversion using Google's speech recognition, OpenAi's Whisper, and Meta's wit.ai.

## Important notes:

Please take note of the following important information:

- By default, the program uses the Google service. To utilize other services, you need to obtain an API key from the respective service provider.
- For the best results with Arabic language transcription, we recommend using wit.ai.
- OpenAI's Whisper has been included based on previous experiences, but it may not function as intended or may not work at all. We appreciate your feedback and experiences to help us resolve any issues.
- Unlike OpenAI, Wit.ai provides free API keys.
- When converting a file, ensure that you select the appropriate language before initiating the conversion process. If a file is multilingual, words in languages other than the selected language may not be accurately converted due to limitations of the services.
- Prior to conversion, files are split into segments of up to 60 seconds, depending on the limitations of each service. Consequently, some words may be lost during this process. To achieve optimal results, we recommend adjusting the segment duration based on the silence time, file length, and segment duration allowed by each service.
- For optimal results with .srt files, we recommend selecting a short duration, such as 5 seconds, for the segments.
- Sound Transcriber requires [Microsoft Visual C++ 2015-2022 Redistributable X64](https://aka.ms/vs/17/release/vc_redist.x64.exe) and [Microsoft Visual C++ 2013 Redistributable X64.](https://aka.ms/highdpimfc2013x64enu) If the program does not work for you, please use the previous links to download and install the required files.
- Currently, Sound Transcriber supports the following languages: Arabic, English, Spanish, French, Russian, Turkish, And Vietnamese.
- Sound Transcriber is compatible with Windows 8 and above, but only in 64-bit systems.
 
## Supported file extensions:

Sound Transcriber supports the following file extensions for conversion:

.mp3, .wav, .aac, .flac, .oga, .opus, .mp4, .avi, .mkv, .mov, .m4a, .ogg, .ram, .rm, .wma, .wmv, .3gp, .flv.

## Obtaining API Keys:

### Wit.ai:

If we were to include an API key within the program itself, it would likely be blocked after widespread usage by multiple users.
Moreover, wit.ai provides distinct API keys for each language. This means that you need to create an application in the desired language and obtain its corresponding API key.
Unfortunately, it is not feasible for us to gather API keys for all languages since they vary based on individual preferences.
Therefore, we will provide you with instructions on how to obtain your own private API key.
Although the following steps may appear extensive, they are straightforward and only need to be completed once.

- Open the [wit.ai website](https://wit.ai)
- Log in with your Meta account by clicking "Continue with Meta."
- Follow the normal account creation steps or press "Continue with Facebook"
- Go to the top of the page, press h or 1 for screen reader users.
- Click "New App" and give the app any English name, such as test or my app.
- You will find an options box for the app's language, open it and choose the appropriate language. The audio files will be converted to the language you choose.
- Finally click "Create".
- Find the name of the application you created, click on it, and then navigate to the "Management" button.
- When you reach this button, press the letter b to find a button called Settings. Press this button.
- Move with the number 4 or h for screen reader users until you find a heading called Client Access Token, scroll down and you will find your key as a button. You can select the text manually to copy it or press the same button to for it to be automatically copied.
- Return to Sound Transcriber and paste your API key into the provided field.

You can repeat these steps and create a new application with a different name to obtain an API key for transcribing in another language. If you want to use multiple languages with wit.ai, simply repeat the steps to obtain an API key for each language.

### Whisper:

Sound Transcriber supports transcription through the use of OpenAI's Whisper API keys, which are not available for free.

The pricing is based on the number of characters transcribed, and specific plans are not mentioned here.

To get detailed information about the limits and subscription options, please visit [this page/.](https://platform.openai.com/account/billing/overview) Keep in mind that signing in and adding a payment method is at your own risk.

To obtain an API key for Sound Transcriber, go to the [API key page](https://platform.openai.com/account/api-keys) and click on "Create new secret key." Copy the generated key and proceed to add it in the program settings as demonstrated later.

## Sound Transcriber Interface:

Upon opening the program, you will find an edit box displaying the transcribed result. Use the tab key to navigate through the other options.

The "Language" box allows you to specify the language of the file you want to transcribe. Select the appropriate language using the arrow keys.

Click the "Start" button to initiate the conversion process.

Next, you will find the "Save As" button, which allows you to specify the output saving preferences.

Below that, there is a read-only edit box indicating the path or the link of the file to be transcribed.

Use the "Browse" button to locate and select the file you want to transcribe.

Additionally, you can utilize keyboard shortcuts, which will be explained later.

Please note that the order of items on the screen may differ when navigating with the Tab key.

## Menus

The program includes several menus accessible by pressing the Alt key.

### File:

- Open: Use this option to browse your device and search for a file to transcribe.
- Save: Save the transcription result with the specified extension in the settings.
- Save As: Save the result with a specific extension.
- Settings: Access program options and customizations.
- Open Log File: allows you to view the Sound Transcriber log file.
- Exit: Exit the program.

### Services:

It contains the names of the services available for conversion, you can selecte any service.

### Help:

- User Guide: View the currently accessed file.
- What's new: View Sound Transcriber change log.
- Check for Updates: Search for program updates.
- Contact Us: Display menus with options to contact the program developers.
- Donate: donate to the developers of Sound Transcriber.
- Open Repository: Opens Sound Transcriber repository on GitHub, the program is not open source.
- About: Provides information about Sound Transcriber.

## Sound Transcriber Settings:

Similar to the NVDA screen reader settings, the Sound Transcriber settings are categorized into several sections, each containing various options. You can navigate between sections using the up and down arrows. Use the Tab and Shift+Tab keys to scroll through the options within the selected section.

### General:

This section includes various program-wide options:

- Interface Language: Specify the program's language.
- Service: Define the service used for file transcription.
- Files to transcribe simultaneously: This feature allows you to specify the number of files to be transcribed simultaneously. This feature controls the number of clips from the same file that will be sent simultaneously after it is split.
- Auto detect if there is a file in the clipboard: The program checks your clipboard on startup, and if it finds a supported file, it automatically selects its path for quick conversion.
- Ask what to do when a file is detected in the clipboard: If enabled, the program will prompt you on how to handle the detected file.
- Sounds: Activate alert sounds when the conversion starts and ends.
- Speak Actions: Enable the screen reader to provide conversion status information.
- Check for Updates Automatically: Automatically search for program updates upon startup.
- Include beta versions when checking for updates: enables you to receive beta updates for the program. More details can be found in the beta updates section of this guide.
- Enable Logging: This feature allows Sound Transcriber to write a log of the transcription process steps. It's particularly useful for troubleshooting errors. When needed, activate logging and send us the generated file. If logging is disabled, older logs will be deleted, but details of the last step will be retained, This ensures that the program can log errors that may occur, even if you are unable to run the program for the first time and activate logging.
- Restore Default Settings: Reset the settings to their default values.

### Save options:

The options in this section affect the saving functionality in the program's File menu.

- Auto Save Files: Enable automatic saving of the conversion results.
- Save Path: Displays the current path for saving files. Use the Browse button to change it.
- Save as .txt: Enable automatic file saving with the .txt extension.
- Save as .docx: Save the file with the .docx extension.
- Save as Subtitle File: Save the file with the .srt extension.
- Keep downloaded files. Files downloaded from the Internet will be kept after conversion. If it is disabled, the file will be downloaded, converted and then deleted.

If the AutoSave feature is disabled, the "Save" option in the "File" menu will perform the same function, saving files according to the specified extensions and path.

### Google:

This section requires you to enter a secure API key in the provided text box named "Secret Key." You can click the edit button to modify the key. Additionally, you can adjust the segment duration by specifying the duration of each part of the file when using this service.

Note that the file needs to be divided into several segments for conversion. The maximum duration per segment for this service is one minute.

### OpenAI:

Similar to the previous service, this section allows you to enter an API key. However, the maximum length for each file when using OpenAI is 30 seconds.

### Wit.ai:

As Wit.ai separates languages based on API keys, this section allows you to combine languages as follows:

You will find a list of currently added languages.

Each language has a corresponding hidden edit field for the API key.

You can edit the key by removing the old one, pasting the new key, and then use the Edit button. Alternatively, you can use the Add button to add a new key.

Select the language matching your application in Wit.ai, paste the key, and click Add.

Repeat these steps for each language you intend to use. After obtaining a key from the Wit.ai site, return to the settings window to add it.

You can delete individual keys or all saved keys associated with this service using the provided buttons.

Choose audio format: To specify the file extension when converting, choose ogg or mp3. If your internet connection is bad.

Choosing wav will quickly split the file, but it will be larger.

Lastly, you can specify the duration of each file segment, ranging from 4 to 20 seconds. Choose the duration that yields the best results.

Press OK when you have finished adjusting the settings.

## Keyboard Shortcuts::

Sound Transcriber provides several keyboard shortcuts to enhance speed and ease of use.

- Ctrl+O: Open the file browsing window to select a file for conversion.
- Ctrl+V: Paste a file from your clipboard for conversion.
- Ctrl+1: Switch to the Google service.
- Ctrl+2: Switch to the Wit.ai service.
- Ctrl+3: Switch to Whisper.
- Ctrl+Enter: Start the conversion process.
- P: Display the current percentage of conversion progress.
- Ctrl+S: Open the save options.
- Ctrl+Shift+S: Save the result as .srt.
- Ctrl+Shift+T: Save the result as .txt.
- Ctrl+Shift+D: Save the result as .docx.
- Ctrl+U or F3: Check for updates.
- Alt+S or F8: Open the Settings.
- F1: Open the user guide.
- F2: View updates.
- F5: Donate.
- F6: Open repository.
- F7: Open Log file.
- F9: About.
- Ctrl+W or Ctrl+F4: Close Sound Transcriber.

## How to Convert Files:

To convert files, open Sound Transcriber and either browse for the file by clicking "Browse" or use the shortcut Ctrl+O. Alternatively, you can copy the file from your device and paste it using Ctrl+V.

You can also utilize the option available in the context menu for supported files, the Send To menu in Windows, or simply drag and drop.

You can alternatively copy a video link from sites such as Facebook, Twitter (X), Youtube, SoundCloud among others.

Choose the desired language and service using the provided shortcuts or adjust them in the settings. Press "Start" or use the shortcut Ctrl+Enter to initiate the conversion.

Did you know, you can open Sound Transcriber by pressing Windows + R to open the Run dialog, and then typing st.

### Notes:

- While a conversion is underway, you have the option to pause it, be it during the extraction of text or the downloading of a file. However, it's important to note that initiating a new process will result in the disregard of anything associated with the previous process.
- If the process is stopped during splitting the files, it cannot be resumed.

## Report Bugs:

If you encounter any bug with Sound Transcriber, you can use the communication methods available in the "Contact Us" menu under the "Help" section. Provide a detailed explanation of the actions that led to the bug. We recommend sharing the Sound Transcriber.log file, which will assist us in understanding and resolving the bug more effectively.

Go to Settings > General and enable logging. Then repeat the steps that led to encountering the error. Don't forget to disable logging after sending the file. Note that keeping the option enabled may result in a large .log file. However, you can choose to keep the log enabled if you wish.
 
You can find the file in the following path:

AppData\Roaming\tecwindow\SoundTranscriber

## Beta Updates:

Sound Transcriber offers a beta update system, allowing you to test new features and assist us in identifying bugs. While activating this feature is straightforward, there are some important points to consider:

- Beta updates may be unstable, and we cannot guarantee the immediate release of fixes for any issues you encounter.
- In certain cases, we may release up to three updates within the same week.
- Some options may not always be translated into your preferred language when using beta versions.
- We recommend beta testing only if you are comfortable with identifying and sharing bugs.

To opt into beta updates, navigate to Settings > General, enable the "Include beta versions when checking for updates" option, and then search for updates.

If you wish to revert to stable versions, simply disable the same option and then download and install the latest stable version.

We extend our heartfelt gratitude to everyone who contributes to testing Sound Transcriber, finding bugs, and sharing their insights.

## How to Translate:

While Sound Transcriber currently supports only a limited number of languages in its interface options and user guide, it can transcribe speech to text in a wide array of languages.

However, we warmly welcome anyone interested in translating the program into their native language.

### Interface translation:

The translation of interface options primarily relies on .po files, which can be edited using the Poedit program. You can download Poedit from its official website, then navigate to the Sound Transcriber repository on GitHub or locate the program folder on your device. Next, locate the messages.pot file and open it in Poedit. From there, you can translate the strings into your preferred language, save the file (which will generate both a .po and a .mo file), and share these files with us.

### Test translation:

Sound Transcriber can recognize and accommodate new translations, allowing you to test your translation before submitting it to us. To do this, navigate to the Languages folder, create a folder with the code for your language (the first two letters of the language), then create a subfolder named LC_MESSAGES, and place the .po and .mo files inside. Don't forget to name the files as SoundTranscriber.po and SoundTranscriber.mo.

### Documentation translation:

While translation of the update log and user guide is not mandatory, you can translate them into your language using .pot files.

We use .md files to create .pot files, which we then send to translators. After that, we convert the .po files we receive from the translators back into .md files and then into .html files to include with the program.

This allows us to make corrections to any part of the manual and changelog, ensuring they are applied consistently across all supported languages. It also ensures that files in different languages remain in exactly the same format and structure.

To translate files, follow these steps:

- Get the .pot files from the repository on GitHub or from the Documentation folder in the Sound Transcriber directory.
- Translate them using Poedit.
- You may find some phrases repeated with additional periods. We use this to distinguish between phrases, ensuring they stay in the correct positions. Add the same number of periods, and we will remove them when incorporating the translation.
- Note that the texts may not appear in the correct order if the translation is incomplete. Once translated correctly, reopen the file to view them in the correct order.
- Finally, share your files with us.

### notes:

- If you choose not to translate the User Guide and Updates file, Sound Transcriber will display them in English.
- Software translation is an ongoing effort, and we will liaise with you before releasing new updates so you can translate any new content.

## Sound Transcriber website:

While there is no official website for Sound Transcriber, you can access all necessary resources in the Sound Transcriber repository on gitHub. This repository contains translation files and the latest version of the program.

Note: Sound Transcriber is not open source at this time, and the repository does not contain the source code for the program.

[Repository link.](https://github.com/tecwindow/SoundTranscriber)

## Contact us:

If you are unable to access our contact list within Sound Transcriber, you can reach us via email using the following addresses:

- Qais Alrefai: ww258148@gmail.com
- Mahmoud Atef: mahmoud.atef.987123@gmail.com
- Ahmed Bakr: AhmedBakr593@gmail.com

## special thanks:

- Many thanks to Riad Assoumfor translating Sound Transcriber into French, translating the user guide into English and proofreading the program's English and Arabic strings.
- Many thanks to Georgiana Frincu for translating Sound Transcriber into Spanish.
- Many thanks to Danil for translating Sound Transcriber into Russian.
- Many thanks to Kadir öz for translating Sound Transcriber into Turkish.
- Many thanks to Nguyen Anh Duc for translating Sound Transcriber into Vietnamese.