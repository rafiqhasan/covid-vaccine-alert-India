## **COVID-19 Vaccine alerter for India**
Latest release 1.12 ( 9th May - 12:20 AM IST ):
- Fixed issue crash issue on some OS versions
- Added option to provide age limit

## **Features**:
- Script runs in local, directly from EXE
- Searches cowin site on basis of pincode every 5s
- Feature to provide age limit
- If slot found then gives alert sound( Dekstop alerts ) and  ( Whatsapp alerts ) to configured number

### Steps to run directly from EXE( Windows 10 ):
1. Download ZIP package from here - https://drive.google.com/file/d/1TsuTwMOAGhaY7lLXER38-qxIOX1RUyAA/view?usp=sharing
2. Unzip folder, it will unzip and show 2 files
3. Open file config.json
4. *Optional step( for Whatsapp alerts ) - Setup Twilio* - https://www.twilio.com/blog/send-whatsapp-notifications-python-twilio
5. In config.json, replace values for **</PINCODE TO SEARCH/>, </TWILIO TOKEN/>, </TWILIO SID/>, </WHATSAPP_NUMBER/>**. If TWILIO is not setup then leave <TWILIO***> and <WHATSAPP***> fields as it is.
6. In config.json also change **min_age_limit** value as 18 or 45 as per your choice( Please note system will NOT alert for 45+ centers if you set up limit as 18+ )
7. Save file
8. Double click covid_alert_whatsapp_exe.exe to run
9. Script will start searching, as soon as a slot is open it will give Desktop audio alert and Whatsapp notification ( if configured )
10. For exiting script press: CTRL + C

### Steps to install from Code( Any OS ):
1. Download code from here( connect with me on https://www.linkedin.com/in/sam04/ to request access to source as people can misuse and overload ) -  https://drive.google.com/file/d/1fCzyZC0CWoy0RtwKeZjGXKfUvqk0WX7v/view?usp=sharing
2. Install Python 3.6.7+ ( https://www.python.org/ftp/python/3.6.7/python-3.6.7-amd64.exe ) , during installation please checkbox on "Add Python to PATH"
3. Restart system for Python installation completion
4. Unzip file
5. *Optional step( for Whatsapp alerts ) - Setup Twilio* - https://www.twilio.com/blog/send-whatsapp-notifications-python-twilio
6. For windows users: Open the package folder, in the address bar above type CMD, press enter
7. Run command: ```pip install -r requirements.txt``` in CMD
8. Right click and open the file covid_alert_whatsapp.py in NOTEPAD
9. Replace all variables in script( in notepad in section ```#### Begin: VARIABLES TO CHANGE ####``` ) with your values ex: PinCode, Phone number, Twilio details and SAVE
10. Double click covid_alert_whatsapp.py to run
11. SCript will start searching, as soon as a slot is open it will give Desktop audio alert and Whatsapp notification ( if configured )
12. For exiting script press: CTRL + C
