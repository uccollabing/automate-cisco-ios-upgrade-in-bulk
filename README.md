
# Cisco IOS Upgrade in bulk for Cisco routers and Cisco Switches using Python script

_I am new to python and have written this script based on my experience so far with python and I am sure that this script can be optimized and enhanced in much better way. Please do share your comments/review and optimization ideas._
_

**When python script is run, it will follow the below sequence:**

* The script will fetch a pre-upgrade report and the report will have information (like IP address, hostname, uptime, current version, current image, serial number, device model and device memory of the router) before it is upgraded.

* Then it will push the IOS image on the cisco router/switch.

* It will check the MD5 checksum.

* It will change the boot configuration and save the configuration.

* It will then reload the router.

* The script will then wait for 300 seconds and then it will fetch a post-upgrade report.


**The following files will be generated by the python script while running the script:**

* Pre-Upgrade.csv
* Post-Upgrade.csv
* Logs.txt

## Cisco IOS Upgrade in bulk for Cisco routers and Cisco Switches using Python script

Follow the below URL link to see the script.
https://www.uccollabing.com/automate-cisco-router-and-switches-ios-upgrade-in-bulk-using-python/

### To see the demo, see the following YouTube video.

Follow the below YouTube URL link to see the demo.
https://youtu.be/MX-42YVoXL0


