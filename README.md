# iphone_log_car_trip_time_duration
iPhone shortcuts script to save timestamps to a text file when bluetooth connects/disconnects to car.

I created two shortcuts and two automation scripts to take timestamps of when my phone connects to my car's bluetooth and when it disconnects. It also distinguishes between a connect/disconnect event when it logs the timestamp. I took screenshots of everything.

## Steps:

(1) Create a folder to save your logfile to (use the "Files" app and click on "On My iPhone", then click on the circle with 3 dots, and select "New Folder")

(2) Create the first shortcut by running the Shortcuts app and clicking on the plus sign (+) in the top right corner.

(3) In the new shortcut click "Search Actions" and enter "text", this will allow you to select "Text", the text value you will enter is "connect"

(4) Click "Search Actions" again and enter "append", this will allow you to select "Append to Text File"

(5) You should see that the "Text" is connected to "Append Text".

(6) Click on "Shortcuts" word in the "Append Text to Shortcuts", this will allow you to select the folder where the logfile will be stored.

(7) Click the "Search Actions" again and enter "date", this will allow you to select "Date", "Current Date" variable is now shown.

(8) Click the "Search Actions" again and enter "append", this will allow you to select "Append to Text File"

(9) You should see that the "Date" is connected to "Current Date"

(10) Congratulations, click "Done" and save the new shortcut (put "connect" in the name to make it easy to identify)

(11) Repeat steps 2 -> 10 for another shortcut, but instead of "connect" use "disconnect" as the text

(12) Save and rename the shortcut with "disconnect" in the name

(13) Click the "Automation" icon at the bottom of the Shortcuts app and click the plus sign (+)

(14) In the search box enter "bluetooth" and select "Bluetooth"

(15) In the "Device" section select your car bluetooth connection (this should have already have existed)

(16) Select "Is Connected" and "Run immediately", click "Next"

(17) You can now select the Shortcut you created (with "connect" in the name)

(18) Repeat steps 14 -> 17 for another automation, but instead of connect to bluetooth, use disconnect

What a pain in the ass! I wish that shortcuts could be saved to a text file script and imported/exported that way.
Also, automations require that you are signed into your phone... if you turn off your phone, you have to enter your passcode before automations can run.
Enjoy!
