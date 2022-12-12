# Payload Library for the USB Rubber Ducky by Kris Yotam

This repository contains payloads and extensions for the Hak5 USB Rubber Ducky. These payloads created by other's and myself are of personal favorites and one's utilized often.


## Disclaimer
Generally, payloads may execute commands on your device. As such, it is possible for a payload to damage your device. Payloads from this repository are provided AS-IS without warranty. While Hak5 makes a best effort to review payloads, there are no guarantees as to their effectiveness. As with any script, you are advised to proceed with caution. In addition payloads in this repository is for payloads that may or may not be modifed by me so please check source before using!

## Legal
Payloads from this repository are provided for educational purposes only.  Hak5 gear is intended for authorized auditing and security analysis purposes only where permitted subject to local and international laws where applicable. Users are solely responsible for compliance with all laws of their locality. Hak5 LLC and affiliates claim no responsibility for unauthorized or unlawful use.

## Contributing
You can send payloads through a pull request if you so wish, however i do not check very frequently and I will not spend time reviewing payloads that don't seem useful

Please adhere to the following best practices and style guide when submitting a payload.

### Naming Conventions
Please give your payload a unique and descriptive name. Do not use spaces in payload names. Each payload should be submit into its own directory, with `-` or `_` used in place of spaces, to one of the categories such as exfiltration, phishing, remote_access or recon. Do not create your own category.

### Comments
Payloads should begin with `REM` comments specifying the title of the payload, the author, the target, and a brief description.

    REM Title: Invasive Koi
	REM Author: Kris Krazy
	REM Description: Opens hidden powershell and connects to canary webserver using Invoke-WebRequest alerting you to spies and snoops.
	REM Target: Windows 10 (Powershell)
	REM Props: Hak5, Thinkst
	REM Version: 1.0
	REM Category: General


