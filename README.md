My notes on how I recovered from a CryptoLocker ransomware incident.

## SYMPTON  (2014 05 11 Sunday)
My Win8 notebook booted to a desktop screen of CryptoLocker showing
some warning messages asking me to send 500 euro. It then open a Window
desktop app with same message & wont close.

### Login in as a different user seem fine
On switching off and then log in as a different user, the ransomware did not show up.
Via this log in, I duplicated my important recent data files to a quarantine
folder on a different PC, __sharedQ on MSI7597.

### Photo viewers not usable
I found that various win 8 default photo viewing tools & apps not able to read 
any of the picture or the bmp files.

### The "Refresh your PC" option couldnt clear the malware
I tried F9 boot "Refresh your PC" option but CryptLocker is still there.


## REMEDY REPORT  Delete the malware infected account

Manually disconnect the network cable.

Login to a separate admin user account. From there delete the infected account login.

Then set up the account again as a new user. On startup the desktop's background
image still shows a CryptoLocker message. But this is just a plain image 
that had been planted, but can be removed via Synched Theme settings.

However the malware seem to have gone.

Then I had to spend time going through the quarantine and remove
the suspect files that might have carried the malware or still infected.
(Involve manually looking names of suspect processes, and name and dates
of data and executable files, etc). It's probably a good time to
carry out the chore of manually sorting out which working files 
and folders to keep, and replace all unmodified folders with previously
archived backups.

AND THEN over the next few days install application programs as I
gradually need to use then.


## CONCLUSION
Having multiple admin accounts proved crucial in helping me quickly reset the PC.


## 2017 update and notes on the WannaCry (NHS) ransom commotion
This uses a separate simple program executable, rather than an image, to display 
message to victim.

#REF  https://securityintelligence.com/wannacry-ransomware-spreads-across-the-globe-makes-organizations-wanna-cry-about-microsoft-vulnerability/?cm_mmc=OSocial_VoiceStorm-_-IBM+Security+Generic-_-WW_WW-_-39932_Twitter

&nbsp;

##### BLOGS
#CrytoLocker hit my low use Win81. Lucky I kept a diff admin that seem unaffected. Put data files in quar-tine folder. Trying various fixes.

#CrytoLocker hit my low use Win81. Hope repaired it via a diff admin that seem unaffected. Put data files in quar-tine folder. http://www.webroot.com/blog/2014/05/05/evolution-encrypting-ransomware/?sf25801027=1

My memo on how recovered from a ransomeware 3 years ago.

&nbsp;

&nbsp;

(update & posted May 2017, KN | kaimagpie)
