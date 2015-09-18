# Security-Best-Practices
A Incomplete Security / Privacy Guide for the Masses

##About

This guide is intended to help people who care about their online privacy / security but need more information to make better security aware decissions.

##Goals
Often with security and privacy concerns there exist trade offs with usability and complexity. The safest user is often the one who doesn't use the Internet, but if you would like to climb out from under your rock to join us, this guide is here to help you. Getting to a point where you can be reasonably confident in your personal security and privacy online can take a lot of effort, due diligence, and technical vigilence. All of the items in this guide can be overwhelming. Don't treat these items as hard and fast rules to tackle all at once. Over time do your best to improve your security posture by implementing and trying out more of these practices. Once you have tried many of them out, you can then decided for yourelf what your security and privacy needs are compared to your risk tolerance and how inconvenienced it makes your life.

##Topics

###Email

####Threat
When sending an email there are no guarantees that the data is secure or encrypted completely from the sender to the reciever. Often your connection to your email provider will be secured but after that you have no way of knowing if your email will be read or stored at some point before it reaches its destination. For this reason any sensitive information should not be transmitted over email without being properly encrypted. 

####Easy Solution
If you have a sensitive file that you want to send to someone, consider compressing it into an archieve file (.zip or .rar for ex.) then set a strong passphrase on it to encrypt it. Tnhis is often done using the advanced settings of your archieving application. Then email the reciepient the file and send them the password via another means. NOT OVER EMAIL. Consider using SMS or calling them to give them the password.

####Hard Solution
Strong email security usually requires some technical forthought from the company / parties involved. Two leading solutions are PGP/GPG and SMIME. --More details to be added

###Text Messaging SMS

####Threat
The SMS protocol is another protocol where all data is sent in clear text and could be read by anyone who can view it in transit. This includes the Wireless cell providers of both the sender and receiver as well as any cell towers that the phones are connected to. Apple's imessaging is a little different, they send the messages over an encrypted channel and claim that not even they can read them although this claim has not be validated and is often refuted. There are also a number of government agencies that are attempting to supeoan Apple to reveal this information and laws proposed to force vendors to put in security backdoors for governments.

####Easy Solution
Make use of 3rd party applications to communicate securely with friends who would both install the same application. TextSecure for Android and Signal for iOS are decent solutions although their security can't be guaranteed it is better then sending messages in plain text. Some chat applications with a history of breaches / vulnerabilities or that ask for excessive permissions to operate should be avoided (snapchat, whatsapp). 

###Chat (gtalk / other messagengers)

###Local Storage

###iOS Mobile Devices

###Android Mobile Devices

###VPN

###Proxies

###Passwords

###Password Managers

###2-Factor Authenticion

###SSL /TLS

