My notes on how I recovered from a CryptoLocker ransomware incident.

## SYMPTON  On 2014 05 11 (Sunday)
My Win8 notebook booted to a desktop screen of CryptoLocker showing
some warning messages asking me to send 500 euro. It then open a Window
desktop app with same message & wont close.

### Different user login seemed untouched
On switch off then log in as a different user, the ransomware did not show up.
Via this log in, I duplicated my important recent data files to a quarantine
folder on a different PC, _sharedQ on MSI7597.

### Photo viewers not usable
I found that various win 8 default photo viewing tools & apps not able to read 
any of the picture or the bmp files.

### The "Refresh your PC" option couldnt clear the malware
I tried F9 boot "Refresh your PC" option but CryptLocker is still there.


## REMEDY TRY3   Delete the malware infected account
Via a separate admin user account, I delete the infected account login.

Then set up the account again as a new user. When startup the desktop's background
image that has the message refering to CryptoLocker is still there.
But this is just a plain image planted via Synched Theme setting.

However the malware seem to have gone.

However still need to spend time going through the quarantine and remove
the suspect files that might have carried the malware.
(involve manually looking names of suspect processes, and name and dates
of data and executable files, etc)

AND THEN over the next few days install application programs as I 
gradually need to use then.


## CONCLUSION
Having multiple admin accounts proved crucial in helping me quickly reset the PC.


### BLOG
#CrytoLocker hit my low use Win81. Lucky I kept a diff admin that seem unaffected. Put data files in quar-tine folder. Trying various fixes.
#CrytoLocker hit my low use Win81. Hope repaired it via a diff admin that seem unaffected. Put data files in quar-tine folder. http://www.webroot.com/blog/2014/05/05/evolution-encrypting-ransomware/?sf25801027=1


(update & posted May 2017, KN kaimagpie)
