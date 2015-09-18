# Security-Best-Practices
An Incomplete Security / Privacy Guide for the Masses

##About

This guide is intended to help people who care about their online privacy / security but need more information to make better security aware decisions.

##Goals
Often with security and privacy concerns there exist tradeoffs with usability and complexity. The safest user is often the one who doesn't use the Internet, but if you would like to climb out from under your rock to join us, this guide is here to help you. Getting to a point where you can be reasonably confident in your personal security and privacy online can take a lot of effort, due diligence, and technical vigilance. All of the items in this guide can be overwhelming. Don't treat these items as hard and fast rules to tackle all at once, rather over time do your best to improve your security posture by implementing and trying out more of these practices. Once you have tried many of them out, you can then decide for yourself what your security and privacy needs are compared to your risk tolerance and how inconvenienced it makes your life.

##Topics

###Email

####Threat
When sending an email there are no guarantees that the data is secure or encrypted completely from the sender to the receiver. Often your connection to your email provider will be secured but after that you have no way of knowing if your email will be read or stored at some point before it reaches its destination. For this reason any sensitive information should not be transmitted over email without being properly encrypted. 

####Easy Solution
If you have a sensitive file that you want to send to someone, consider compressing it into an archive file (.zip or .rar for ex.) then set a strong passphrase on it to encrypt it. This is often done using the advanced settings of your achieving application. Then email the recipient the file and send them the password via another means. NOT OVER EMAIL. Consider using SMS or calling them to give them the password.

####Hard Solution
Strong email security usually requires some technical forethought from the company / parties involved. Two leading solutions are PGP/GPG and SMIME. --More details to be added

###Text Messaging SMS

####Threat
The SMS protocol is another protocol where all data is sent in clear text and could be read by anyone who can view it in transit. This includes the Wireless cell providers of both the sender and receiver as well as any cell towers that the phones are connected to. Apple's iMessaging is a little different, they send the messages over an encrypted channel and claim that not even they can read them although this claim has not be validated and is often refuted. There are also a number of government agencies that are attempting to subpoena Apple to reveal this information and laws proposed to force vendors to put in security backdoors for governments.

####Easy Solution
Make use of 3rd party applications to communicate securely with friends who would both install the same application. TextSecure for Android and Signal for iOS are decent solutions although their security can't be guaranteed it is better than sending messages in plain text. Some chat applications with a history of breaches / vulnerabilities or that ask for excessive permissions to operate should be avoided (Snapchat, Whatsapp). 

###Chat (Gtalk / other messengers)

####Threat
In using 3rd party chat applications like Skype, Gtalk, Facebook message, and countless others, you are opening yourself up to having all of your private communication stored on that applications server indefinitely. There have also been many attempts (successful and unsuccessful) by governments to gain access to this data by court orders or by forcing the companies to install backdoor access. Additionally if any of these chat applications gets hacked, and it happens a lot (cough Snapchat), all of your conversations could be exposed.

####Modest Solution
Off-The-Record (OTR) is an encryption library that plugs into popular chat clients (Adium for Mac or Pidgin for Windows and Nix). The setup steps for all parties that wish to communicate security is as follows:
1. Download the chat client - <links>
2. Connect your desired accounts (Gtalk, etc.)
3. Install the OTR plugin -<links>
4. Enable OTR and generate a private key / fingerprint
5. Force encryption on all chats

###Local Storage

####Threat
If you have ever lost or had a device stolen you know that it can be pretty devastating. What's worse is if the data is not encrypted not only will you have lost the data but it could also be in the hands of someone else.

####Solution
Anywhere sensitive data is stored whether that be on a desktop computer, laptop, mobile device, tablet, USB drive, or memory chip. Full disk encryption should be implemented and a strong passphrase should be used to lock it.

####Device Specific Solutions 
*Windows
*iOS
*Android
*USB Drives

###iOS Mobile Devices
There are many iOS security guidelines -- Link to a few

###Android Mobile Devices
There are many android security guidelines -- Link to a few

###Passwords

####Threat
Passwords are probably one of the weakest parts of the Internet (authors ramblings). They can be guessed, stolen, stored incorrectly, overused in repetition, found written next to computers, forcibly reset, and many more weaknesses.

####Solutions
First of all whenever you hear password, you should think passphrase, gone are the days where you can use one word as a passphrase.

Passphrases should be:
*10-20 Characters long in almost all cases the longer the better
*Make use of upper and lower case
*Make use of special characters and numbers (space bar and tab often counts too)
*Something you can remember (sometimes)
*Not used on other sides (You shouldn't re-use the same password on your email, for banking etc.)

#####Tips
*Use a password manager whenever possible
*Enable 2-Factor Authentication wherever possible

#####Password Managers
Password managers allow you to use unique, strong, randomly generated passwords across a variety of accounts and store them securely in an encrypted database on your machine or 'in the cloud'. This database should be encrypted with a strong passphrase and not shared with anyone. One drawback is that this creates a central repository of all your passwords. This is often seen as a convenience / ease of use tradeoff between using a password manager and having to remember multiple weaker passwords across many sites. Given the central repository of passwords that could unlock all of your accounts there is an additional risk of using a password manager that syncs with a remote server and shares your passwords with all devices. If you are more risk adverse look for a password manager that does not sync remotely or disable this feature.

#####2-Factor Authentication (2FA)

There are three main types of authentication mechanisms in use today, what you know (passwords, usernames, SIN number); what you have (keys, access badges, your cell phone); and what you are (biometrics). Two or multi factor authentication refers to using 2 or more nof these methods to prove you are how you claim to be. Where ever possible you should enable 2FA for all of your online accounts. The common method that most applications are using is password + a special verification code sent to your cell phone. That way if you know your password and have your cell phone you will be permitted to login to the application. Facebook, Google, and Twitter all support 2FA so you should start by enabling these and then expand from there.

Steps for each Site:
*Facebook - add link
*Google - add link
*Twitter - add link

###SSL /TLS

###Social Media and Dating Sites

###GPS Tagging

###Updates

###Social Engineering

###Browser Security

###Safe Torrenting

###Backups and iCloud

###VPN

###Proxies

##Resources and References
1. https://gist.github.com/grugq/353b6fc9b094d5700c70 - Point for quick free security advice. Some points come from this source but are expanded on for more accessibility
2. https://storify.com/thegrugq/opsec-for-dating-websites - Specific advice for online dating safety
3. http://www.irongeek.com/i.php?page=videos/bsidessf2015/201-fck-these-guys-practical-countersurveillance-lisa-lorenzin -- Still need to pull a few apps mentioned in this talk out and include them.

