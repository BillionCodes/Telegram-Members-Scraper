Telegram Members Scraper + Bulk Adder
-----------------------------------

This scripts perform two things
scraper.py
This script is for scraper all members in a telegram group, you have to be in the group to be able to extract members.
The members are extracted to a file called 'members.csv' by default but you can change it if you know python. cheers

Adder.py
--------------------------------------------
This script automatically picks the 'member.csv' file in the same directory, and adds all members to your telegram group by choice.
note: telegram limits adding users to 200 per day so you might start getting floodcrm error message. once that happens just stop script to avoiding getting temporary ban. Thank you

instructions:
Log in to your Telegram core: https://my.telegram.org.
Go to 'API development tools' and fill out the form.
You will get basic addresses as well as the api_id and api_hash parameters required for user authorization.
For the moment each number can only have one api_id connected to it.
copy api_id and api_hash 
open scraper.py and assign api_id and api_hash to the first two variables respectively. also assign your phone number to phone variable

command:
python3 scraper.py
python3 adder.py members.csv

Note: first time of running scraper.py will require login code so check your telegram app. enjoy!!
