## **COVID-19 Vaccine slot alert( for India )**
Get audio alerts on Desktop as well as Whatsapp notification( Twilio needed ), whenever a vaccine slot gets available for your pincode as per CoWin site. Run directly from EXE with minimum steps and least complexity.

## **Features**:
- Script runs in local, directly from EXE
- Searches cowin site on basis of pincode every 5s
- Feature to provide age limit, on which alert should be given
- Feature to provide minimum number of slots, on which alert should be given
- If slot found then gives alert sound( Dekstop alerts ) and  ( Whatsapp alerts ) to configured number

### Steps to run directly from EXE( Windows 10 ):
1. Download ZIP package from here - https://drive.google.com/file/d/1TsuTwMOAGhaY7lLXER38-qxIOX1RUyAA/view?usp=sharing
2. Unzip file, it will unzip and show 2 files: config.json and covid_alert_whatsapp_exe.exe
3. *Optional step( for Whatsapp alerts ) - Setup Twilio( complex ) - https://www.twilio.com/blog/send-whatsapp-notifications-python-twilio
4. Right click config.json file and Open-with notepad to edit:
    1. Replace values for **</PINCODE TO SEARCH/>, </TWILIO TOKEN/>, </TWILIO SID/>, </WHATSAPP_NUMBER/>**. If TWILIO is not setup then leave <TWILIO***> and <WHATSAPP***> fields as it is.
    2. Change **min_age_limit** value as 18 or 45 as per your choice( Please note system will NOT alert for 45+ centers if you set up limit as 18+ )
    3. Change **min_slots_for_alert** value as 1 or higher. System will alert when minimum these many slot are available at a location.
    4. Save file
5. Double click covid_alert_whatsapp_exe.exe to start search, it will alert whenever slot gets available

### Steps to run from Code( Any OS ):
1. Please connect with me on https://www.linkedin.com/in/sam04/ to request access to source as people can misuse and overload CoWin site
2. Install Python 3.6.7+ , during installation please checkbox on "Add Python to PATH"
3. Restart system for Python installation completion
4. Unzip file
5. *Optional step( for Whatsapp alerts ) - Setup Twilio* - https://www.twilio.com/blog/send-whatsapp-notifications-python-twilio
6. For windows users: Open the package folder, in the address bar above type CMD, press enter
7. Run command: ```pip install -r requirements.txt``` in CMD
8. Right click config.json file and Open-with notepad to edit:
    1. Replace values for **</PINCODE TO SEARCH/>, </TWILIO TOKEN/>, </TWILIO SID/>, </WHATSAPP_NUMBER/>**. If TWILIO is not setup then leave <TWILIO***> and <WHATSAPP***> fields as it is.
    2. Change **min_age_limit** value as 18 or 45 as per your choice( Please note system will NOT alert for 45+ centers if you set up limit as 18+ )
    3. Change **min_slots_for_alert** value as 1 or higher. System will alert when minimum these many slot are available at a location.
    4. Save file
9. Double click covid_alert_whatsapp_exe.exe to start search, it will alert whenever slot gets available

## Release History:
Release 1.13 ( 9th May - 12:35 PM IST ):
- Added feature to provide minimum number of slots, on which alert should be given

Release 1.12 ( 9th May - 12:20 AM IST ):
- Fixed crash issue on some OS versions
- Added option to provide age limit, on which alert should be given
