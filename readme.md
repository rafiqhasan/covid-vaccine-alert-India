## **COVID-19 Vaccine slot alert( for India )**
Get Covid vaccine availability - **Desktop alerts** as well as optional **Whatsapp notifications**( Twilio setup needed ), whenever a vaccine slot gets available for your pincode as per CoWin site. Run directly from EXE with minimum steps and least complexity.

<img src="/scrn_shot.jpg" width="33%"/>

**screenshot is generated only for reference*

## **Features**:
- Script runs in local, directly from EXE
- Searches cowin site on basis of pincode / district every 5s
- No need to register on any 3rd party site and share details
- Feature to provide age limit, on which alert should be given
- Feature to provide minimum number of slots, on which alert should be given
- If slot found then gives alert sound( Dekstop alerts ) and  ( Whatsapp alerts ) to configured number
- *For Twilio Whatsapp setup, refer this link* - https://www.twilio.com/blog/send-whatsapp-notifications-python-twilio

### Steps to run( Windows 10 ):
1. Download ZIP package from here - https://github.com/rafiqhasan/covid_vaccine_alert_IN/raw/main/exe_package.zip
2. Unzip file, it will unzip and show 1 file: covid_alert_whatsapp_exe.exe
3. Double click covid_alert_whatsapp_exe.exe and follow on-screen instructions for one time auto configuration
4. Script will alert automatically when a slot is available

### Steps to run from Code( Any OS ):
1. Please connect with me on https://www.linkedin.com/in/sam04/ to request access to source as people can misuse and overload CoWin site
2. Unzip package ZIP
3. Install Python 3.6.7+ , during installation please checkbox on "Add Python to PATH"
4. Restart system for Python installation completion
5. *Optional step( for Whatsapp alerts ) - Setup Twilio* - https://www.twilio.com/blog/send-whatsapp-notifications-python-twilio
6. For windows users: Open the package folder, in the address bar above type CMD, press enter
7. Run command: ```pip install -r requirements.txt``` in CMD
8. *Optional step( for Whatsapp alerts ) - Setup Twilio( complex )* - https://www.twilio.com/blog/send-whatsapp-notifications-python-twilio
9. Double click covid_alert_whatsapp_exe.exe follow on-screen instructions for one time auto configuration

## Release History:
Release 1.18 ( 06 June - 09:30 PM IST ):
- Added Dose-1 and Dose-2 filters
- Added filters for vaccine type

Release 1.17 ( 19th May - 08:59 PM IST ):
- Added logic to bypass cache on API
- Handled the Slot1 and Slot2 logic from API
- Added option for State and District ID search

Release 1.16 ( 14th May - 02:11 AM IST ):
- Created a simple UI for the application

Release 1.15 ( 11th May - 10:46 PM IST ):
- Whatsapp alert also shows the available slots at a center
- Also added feature, alert shows any slot available in future from today's date( not just today's availability )

Release 1.14 ( 10th May - 8:21 PM IST ):
- Replaced complexity of config.json manual setup with one time on-screen setup
- Made age limit as optional filter
- Whatsapp alert also shows the Center name

Release 1.13 ( 9th May - 12:35 PM IST ):
- Added feature to provide minimum number of slots as filter, on which alert should be given

Release 1.12 ( 9th May - 12:20 AM IST ):
- Fixed crash issue on some OS versions
- Added option to provide age limit, on which alert should be given
