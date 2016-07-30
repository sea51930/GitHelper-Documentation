# Process explanation
This page was created to give a little insight for how the software works, without you    
having to read through hundreds of lines of code.    

## A Basic Rundown
The base idea of this software is that a main program will create a class (which will contain a bit of data fit to your    
preferances) that acts as an artificial intelligence. When run it will listen for its name, and when called    
it will send a driver module the said text via `.run(user's words)`.

## Drivers
To make this software more customizable, we've created the feature of drivers.    
The idea is that you run the [main software file](https://github.com/CalderWhite/GitHelper/blob/master/py3Speech.py), which acts as kernel of sorts.    
It contains a [class](https://github.com/CalderWhite/GitHelper/blob/master/py3Speech.py#L17) that contains all you will need to easily start using the software.    
It can run a main loop that listens for audio, and specifically listens for a couple keywords such as "shutdown" or its    
own name (when the class is constructed you must give it a name, since it is a "artificial intelligence").    
When it hears its name it will then take the text it found from the audio it recorded and "ship"    
it off to the selected driver for the classes instance.    

==========
For more notes go to the developer documentation on [creating a driver]().
