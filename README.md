# Sensor-Pi
A BASH script to check for temperature, voltage readings, clock frequencies of on-board sensor on Raspberry Pi.

To achieve the output, we’ll be using a BASH (Bourne Again Shell) script. Shell scripting is the easiest and least resource-intensive procedure to communicate with the system processes, the kernel of the Operating System and the system hardware in general.

# No amount of programming or scripting knowledge is required to utilize this script. Possessing knowledge of Linux commands and executing BASH scripts is recommended but not mandatory. #


If you’re accustomed with Linux:
Open the attached Script in a new tab. Copy the text and put it in a shell script file and run it.



Steps to setup the shell script:
For sake of convenience, download the text editor ‘Gedit’. It is a GUI text editor with syntax highlighting for various languages.
To Do so – sudo apt install gedit

Now,using ‘Gedit’ create a new file in a directory of your choice, naming it as you like. Add the extension ‘.sh’ to the end of the filename. In computing, extensions of files determine their types and behaviour. So adding the ‘sh’ makes the file a BASH executable file.
Here, I am creating the file in the default folder for the Pi user at ‘/home/pi’ and have named it as ‘sensor-read.sh’
To Do so – sudo gedit sensor-read.sh

Executing the above command will open a new blank file in the GUI text editor ‘Gedit’. Copy the code, Paste it into this newly created blank file which is open in ‘Gedit’. Remove the first line and save the file, then exit from it.

Change the file permissions.

For the first run of the script, make sure you have an active internet connection that the RPi3 is connected to. Run the script.
To Do so – ./sensor-read.sh


The first time that the script is run, it will download a package needed for its optimal performance. The package is automatically installed and run, showing you the intended output.The second run onward, internet connection is not required and the script works offline. Note that the sensor readings are invoked only once when the script is executed. To get an updated sensor reading the script needs to be run again. If you’re adept with Linux, setting up a cron job to execute this script at certain intervals will be a boon, as and when required.

-------------------------------------------- Aritra, KnowledgeOfThings.com -----------------------------------------------------------
