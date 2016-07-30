# GitHelper
GitHelper is an audio based GitHub client.    
The artificial intelligence makes programming faster by doing tedious tasks for you!

## Installation
**still in developement**    
**There is no direct installation available yet, since there is no distribution yet.**
Please install all [requirements](https://github.com/CalderWhite/GitHelper-Documentation/blob/master/README.md#windows-1)
### Windows
#### gitpanion
You must install the [gitpanion](https://github.com/CalderWhite/gitpanion) library which makes calls to the github REST api.    
There's more documentation at the page's [changelog](https://github.com/CalderWhite/gitpanion/wiki/ChangeLog).
#### packages
`py -m pip install gitpanion`
## requirements
so far,  GitHelper is only windows supported.    
This is because it makes use of the windows text-to-speech engines built in.

### Windows
Here's an extensive list of all requirments and their source links.    
**Note: YOU MUST INSTALL THESE PROGRAMS IN THIS ORDER**    
This is because some programs in this list rely on EACH OTHER.
- PyWin32 : [source](https://sourceforge.net/projects/pywin32/files/pywin32/Build%20220/)
- pyaudio : `pip install SpeechRecognition`
- pyttsx : (custom version) [download source](https://github.com/Julian-O/pyttsx)
- speech_recognition : `pip install SpeechRecognition`

### gitpanion_api driver requirements
- gitpanion : `pip install gitpanion`
- requests : `pip install requests`

# Developer notes
It's important to understand how the software works before developement.    
[here](/#) is where you can find a guide of how the process works.    
class documentation is [here](/#)
