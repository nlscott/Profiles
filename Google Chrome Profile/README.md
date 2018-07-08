# Google Chrome Profile


## macOS configuration profile to manage Google Chrome

Edit the .plist file with the settings you want. Additional policies can be found at: [The Chromium Project](https://www.chromium.org/administrators/policy-list-3)

The use an MDM provider or somethings like [mcxToProfile](https://github.com/timsutton/mcxToProfile) to convert the .plist into a .mobileconfig file

---
## Policies in profile:
* Set home page
* Set restore web page on startup
* Disables Autofill for for logins, forms, and credit card information
* Disables "saved" logins and passwords
* Set defaults flash plugin behavior to ask user for first run
* Allows popups
* Enables safe browsing
* Set Chromes default printer to system default printer
* Sets black and white list for URLS
	* This profile is a test and blocks all websites in the black list, and only enables Apple, Google, and Chrome settings in the white list (adjust as you see fit)


