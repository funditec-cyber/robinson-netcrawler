# NetCrawler
### Install pipenv to create a virtual environment
### Execute: 
- pipenv install -r requirements.txt
- sudo apt-get install pythonX.Y-tk, being X.Y your version of python.
- Configure the file config.ini with the number of octects required for your subnet and their corresponding values, usually setting their values to scan a wider of narrower network range (working with two octects so far).
- In the bash (``pipenv run python3 interface.py``) or inside the virtual environment (``pipenv shell``) execute the runner with the command: ``python3 interface.py`` which is going to take a while.

![Capture](https://i.imgur.com/cZ28LVQ.png)

NetCrawler is a network discovery tool (currently under development) that attempts to reveal information about connected devices within a network.

This tool may be suited for:
  - Those wishing to perform a basic visibility/pen test of their network
  - Systems Administrators
  - Curious folk

#### Discovery Methods
  - Multi-threaded (brute force) pinging
  - ARP (Address Resolution Protocol)
 
#### Future Enhancements
  - Generate pen test reports of a given network
  - Provide more detailed information of discovered devices (OS/ port activity/ etc)
  - Give the ability for user to enter a specific IP address/range
  - Linux support

#### Tech
* [Tkinter] - Tkinter Graphical libraries to build GUI elements
* [Python 3] - Python for everything else

#### OS Support
* Linux (Tested on Kubuntu 18.04)


[![paypal](https://i.imgur.com/wsX84nD.png)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=W2FJJJAM7EESC&item_name=Development+efforts/+coffee+fund&currency_code=USD&source=url)
