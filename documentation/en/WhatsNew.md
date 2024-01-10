# What's new in Sound Transcriber?

## Version 1.3.3:

- Added Russian translation, many thanks to Danil.
- made code improvements that increased response speed and reduced size.
- replaced Accessible Output 2 with PythonUniversalSpeech.
- Sound Transcriber no longer uses Sapi5 to speak actions when used without a screen reader.
- Updated the version of Python used to Python 3.11.7.
- Several minor improvements.

## Version 1.3.2:

- You can now add files using drag and drop.
- Fixed a major bug that caused extracted text to appear in the wrong order when converting long files.
- Fixed a bug that caused the save option to be disabled if the conversion was canceled before completion.
- Several improvements to the Arabic translation. Many thanks to Zeinab Bahaa.
- Various minor improvements.

## Version 1.3.1:

Some fixes and improvements.

## Version 1.3.0:

- French translation added. Many thanks to Riad Assoum.
- You can now open files in Sound Transcriber to Transcribe them from the context menu of supported file types.
- You can now access Sound Transcriber swiftly by simply typing 'st' in the Run dialog.
- Sound Transcriber is now able to automatically recognize interface translations and integrate new help files. To contribute, translate the messages.pot file using Poedit and save the files in the same order as the existing language files.
- When the option to keep downloaded files is turned off, Sound Transcriber will retain them until the program is closed. This is particularly handy if you wish to repeat the conversion process with different options.
- Several bugs related to the paste from clipboard feature have been fixed. Like ignoring certain paths, failure to start conversions from the detection message, pasting links at any time, and more. Many thanks to Dawlat Hassan for the note that helped uncover many of these bugs associated with this feature.
- Fixed a bug that occasionally caused Sound Transcriber to start in a different language after the last update.
- You can no longer open two instances of Sound Transcriber simultaneously.
- Implemented changes to the conversion stopping method.
- Various minor improvements.

## Version 1.2.0:

Important, starting with this version, Sound Transcriber will only support 64 bit versions of Windows.

- Added Spanish translation. Many thanks to Georgiana Frincu.
- You can now convert videos from Youtube, Facebook, Twitter (X) and other services into text, so that Sound Transcriber will download the video and then convert it.
- You can choose to keep the original file after conversion or delete it from the settings.
- Pause and resume feature has been added to the transcription process.
- You can now paste file paths to be converted.
- You can specify the file extension that is sent to wit.ai for conversion from settings.
- Sound Transcriber will try to handle files with names contain Emojis.
- Sound Transcriber no longer stops during conversion. If this happens, you will still be able to continue the process.
- Small improvements here and there.

### Notes

- Pausing is supported while extracting text but not while splitting files.
- If you temporarily stop a process and then start a new conversion process, you will lose everything related to the previous process; Therefore, it is advisable to save the current result before starting a new conversion.
- Choosing the wav format in wit.ai settings speeds up file splitting but leads to slower conversion and increased data usage. Consider trying .ogg and sharing your feedback on the results.

## Version 1.1.2:

- Fixed a bug that prevented proper conversion of .mp4 files.
- Fixed a bug that caused the saved file format to retain the extension of the original file with the output files, and sometimes saved the output files with the same extension as the original file when opening a file via the clipboard.
- You can no longer switch between services and open Sound Transcriber settings during the conversion process.
- Sound Transcriber will now attempt to alert you when converting using an incorrect wit.ai API key.
- Fixed a bug that caused the "Edit" button to appear twice after adding a wit.ai key.
- Fixed a bug that caused the Update and Cancel buttons to appear in English when using Sound Transcriber in Arabic..
- Various other bug fixes.

## Version 1.1.1:

- Fixed a bug that caused the cursor position to move to the beginning of the text constantly with the screen reader while extracting text.
- Fixed a bug that caused the save options to not work after the text extraction process was finished.
- Fix some other bugs.

## Version 1.1:

This version includes several bug fixes and some new features.

- Support for various audio and video file formats has been added.
- Word files are now saved as .docx instead of .doc.
- Sound Transcriber will display a warning when closed during file conversion.
- If auto saving is disabled and the extracted text is not saved in any file, Sound Transcriber will prompt you for what to do upon closing. If you choose to save, the file will be saved according to the options specified in the Save Options section in the settings.
- Sound Transcriber now remembers the selected language for file conversion for each service.
- The extracted text is now displayed during the extraction process. In other words, if the extraction process stops for any reason, you will not lose the extracted text. The new text will be added as the process continues.
- You can now check the progress of the extraction by pressing P.
- Fixed a bug that prevented the auto save path "Browse" button from working.
- Fixed a bug that prevented changing API keys for languages other than the primary language in the wit.ai language list.
- Fixed a bug that prevented from converting files with a language other than the primary language using Wit.ai.
- Fixed a bug that prevented restoring default settings.
- Adjusted the layout of the settings dialog to display items correctly.
- Made some improvements to the Arabic translation.
- Fixed some minor bugs here and there.

## Version 1.0:

Initial release.