# smc_app
This is a child project of the Samuko Motor Control (**`smc`**) project. It contains source code of its GUI application. The application requires that you have the **`smc_l298n_pid_driver module`** is connected to your PC via the FTDI programmer for USB serial communication. Without the module, only the start page can be viewed.

## Running the GUI app (Using python virtual environment)
### Prequisite
- this would run on windows, linux and MAC
- ensure also that the FTDI driver is installed on your PC
- Ensure you have `python3` installed on your PC
- install python virtual environment
  ```shell
    pip3 install virtualenv   //linux or mac
  ```
  ```shell
    pip install virtualenv   //windows
  ```
- Ensure you have the **`smc_l298n_pid_driver module`** interfaced with the geared dc motors and connected to the PC.


### Run App First Time [ linux or mac ]
- Download (by clicking on the green Code button above) or clone the repo into your PC using `git clone`
- change directory into the root folder `smc_setup_application`
- create a python virtual environment named `.env` in the root folder 
	```shell
    python3 -m venv .env
  ```
- activate the virtual environment
  ```shell
    source .env/bin/activate
  ```
- you should see now that you are in the `.env` virtual environment
- install all required python modules
  ```shell
    pip3 install -r requirements.txt
  ```
- now you can run the app
  ```shell
    python3 app.py 
  ```
- once you are done using the application, just close and dectivate the environment
  ```shell
    deactivate
  ```

### Run App [ linux or mac ]
- change directory into the root folder `smc_setup_application`
- activate the virtual environment
  ```shell
    source .env/bin/activate
  ```
- you should see now that you are in the `.env` virtual environment
- now you can run the app
  ```shell
    python3 app.py 
  ```
- once you are done using the application, just close and dectivate the environment
  ```shell
    deactivate
  ```

### Run App First Time [ Windows ]
- Download (by clicking on the green Code button above) or clone the repo into your PC using `git clone`
- change directory into the root folder `smc_setup_application`
- create a python virtual environment named `.env` in the root folder 
	```shell
    python3 -m venv .env
  ```
- activate the virtual environment
  ```shell
    env/Scripts/activate.bat //In CMD  or
    env/Scripts/Activate.ps1 //In Powershel
  ```
- you should see now that you are in the `.env` virtual environment
- install all required python modules
  ```shell
    pip install -r requirements.txt
  ```
- now you can run the app
  ```shell
    python app.py 
  ```
- once you are done using the application, just close and dectivate the environment
  ```shell
    deactivate
  ```

### Run App [ Windows ]
- change directory into the root folder `smc_setup_application`
- activate the virtual environment
  ```shell
    env/Scripts/activate.bat //In CMD   or
    env/Scripts/Activate.ps1 //In Powershel
  ```
- you should see now that you are in the `.env` virtual environment
- now you can run the app
  ```shell
    python app.py 
  ```
- once you are done using the application, just close and dectivate the environment
  ```shell
    deactivate
  ````` 