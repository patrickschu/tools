#Setting up your Windows computer

##1. Install Python for Windows.
Download [here](https://www.python.org/) and install on your computer. 

##2. Make sure you know how to run the command prompt. 
Search your Programs for *cmd* or find *cmd.exe* in the *C:\Windows\System32* folder. 

##3. Change your environment variables to run Python in the command prompt. 
- Locate *python.exe*. Copy its path by clicking on "Properties", then copying the path provided in the "Location" box. 
- Access your system's environment variables by right-clicking on "Computer", then selecting "Properties", 
"Advanced system settings" and "Environment Variables". 
- Edit the *Path* variable by adding the path to *python.exe* which you copied earlier. Separate it from other entries with a *;*. 
This video walks you through the process. 

##4. Install the *pandas* and *Beautiful Soup* packages. 
- Make sure you have completed step 3. 
- Open your command prompt. 
- type
`python -m pip install pandas`

  This installs [pandas](http://pandas.pydata.org/pandas-docs/stable/). 

- then type
`python -m pip install beautifulsoup4`

  This installs [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/). 
  
  This video walks you through the process. 

##5. You're good to go. 
