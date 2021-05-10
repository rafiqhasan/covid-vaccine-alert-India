## **COVID-19 Vaccine slot alert( for India )**
Get Covid vaccine availability - **Desktop alerts** as well as optional **Whatsapp notifications**( Twilio setup needed ), whenever a vaccine slot gets available for your pincode as per CoWin site. Run directly from EXE with minimum steps and least complexity.

<img src="/scrn.jpg" width="33%">

## **Features**:
- Script runs in local, directly from EXE
- Searches cowin site on basis of pincode every 5s
- Feature to provide age limit, on which alert should be given
- Feature to provide minimum number of slots, on which alert should be given
- If slot found then gives alert sound( Dekstop alerts ) and  ( Whatsapp alerts ) to configured number

### Steps to run directly from EXE( Windows 10 ):
1. Download ZIP package from here - https://github.com/rafiqhasan/covid_vaccine_alert_IN/raw/main/exe_package.zip
2. Unzip file, it will unzip and show 1 file: covid_alert_whatsapp_exe.exe
3. *Optional step( for Whatsapp alerts ) - Setup Twilio( complex )* - https://www.twilio.com/blog/send-whatsapp-notifications-python-twilio
4. Double click covid_alert_whatsapp_exe.exe and follow on-screen instructions for one time auto configuration
5. Script will alert automatically when a slot is available

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
Release 1.15 ( 10th May - 10:46 PM IST ):
- Whatsapp alert also shows the available slots at a center
- Also added feature, alert shows any slot available in future from today's date( not just today's availability )

Release 1.14 ( 10th May - 8:21 PM IST ):
- Remove complexity of config.json manual setup
- Made age limit as optional
- Whatsapp alert also shows the Center name
- Also added feature, alert shows any slot available in future from today's date

Release 1.13 ( 9th May - 12:35 PM IST ):
- Added feature to provide minimum number of slots, on which alert should be given

Release 1.12 ( 9th May - 12:20 AM IST ):
- Fixed crash issue on some OS versions
- Added option to provide age limit, on which alert should be given
