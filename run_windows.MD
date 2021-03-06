
#Running TGDP scripts on your Windows computer

##1. Setup complete?
Make sure you have completed the necessary [setup](https://github.com/tgdp/tools/blob/master/setup_windows.MD).

##2. Download the script you want to use. 
For instance, get the [Downloader](https://github.com/tgdp/tgdp/blob/master/summer16/downloader/README.MD) and save it to a convenient place.  

##3. Use the command prompt to navigate to the folder you saved the script in. 
To run the command prompt, search your *Programs* for "cmd" or find *cmd.exe* in the *C:\Windows\System32* folder. 
Navigate from folder to folder by typing `cd` and the name of the folder. 
For instance, `cd Downloads` if you have saved the script to *Downloads*. 
You can see a folder's content by typing `dir`. 
Here is a more in-depth tutorial on how to use the command prompt. 

##4. Run the script in Python.  
Once you are in the right folder, simply type python and the name of the script you want to run. For instance, `python downloader.py`. 

##5. Get the settings right.
Most scripts require some kind of input. 
The input usually follows right after the script name. For instance when running the Downloader, this is the full input:

    python downloader.py http://www.google.com C:\Users\ps\Desktop
 
As the [documentation](https://github.com/tgdp/tgdp/blob/master/summer16/downloader/README.MD) points out, 
the Downloader expects me to feed it a link ("http://www.google.com") and an output directory ("C:\Users\ps\Desktop"). 
Here is where the documentation specifies this:

 Arguments:

    downloader(link, directory):
    link -- needs to be a URL of the format "http://xy.z", pointing to a web site containing .zip files. 
    directory -- an existing folder, this is where the files will be downloaded to.

You will find a similar description of what input each tool expects in the tool's documentation. 
On each documentation page, you will also find a video that walks you through the process. 

##6. That's it.  
