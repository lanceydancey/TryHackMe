#My Notes

team number: 95


Anomaly1:
We received a message that somone compromised out system, but we were able to aprehend them and get their thumbdrive which has a disk image.
It is in the form of a .E01 file. We were supllied with enough information to know that the file was created by FTK imager.

Starting with ftk imager we are able to mount the image and view the contents. Right away we see that there is a file folde labeled
"Agent of Chaos". Inside are three file folders:

Documents - has s folder that contains varoious things, chiefly another folder that contains emails, as well as a set of instructions...
"
Start by playing the game, and find my first message. That is key to dealing with the images.
Look for the images with the right stuff hidden in them, put the fragments in chronological order by picture (DATE TAKEN - EXIF) and decode.
When you get that far, take a look at the brochure - use the same keyword from the images.
Lastly, find what's locked behind the Monthly-Update.
Unlock that with what you've found and you've got the stuff.

"
This leads me to believe there is a clue in the games folder.

Also, the brochure in this folder has a usernmae/password fields.

Games - there is a pytohn game that you can play to get a hint. Or you can take the encrypted message over to cyberchef and get the clue...

Message - WW91IHdvbiB0aGUgZ2FtZSEgWW91ciByZXdhcmQgaXMgYSBoaW50IC0geW91IHNob3VsZCBwcm9iYWJseSB0YWtlIGEgY2xvc2VyIGxvb2sgYXQgdGhlIHBpY3R1cmVzIGZvbGRlci4gVGhlcmUgbWlnaHQgYmUgc29tZXRoaW5nIGhpZGRlbiBpbiB0aGVyZS4gVXNlIHRoZSBQVyAvIEtFWVdPUkQ6IEZVTExZQ0hBUkdFRA==

Using base64 decoder from cyber chef we get...

You won the game! Your reward is a hint - you should probably take a closer look at the pictures folder. There might be something hidden in there. Use the PW / KEYWORD: FULLYCHARGED.

This could be useful, time to look closely in the picture folder.

Pictures - Has a bunch of random pitcures
Some of them have data to extract using steghide and the Passphrase "FULLYCHARGED"
Here is a list of what has packets:

Spiderweb - date from exif 2009:11:01 - piece od code  - QjBsV2
Mushrooms - date from exif 2015:10:22 - piece of code - 8wZF
Pretty_Bird_2 - date from exif 2019:08:19 - piece of code - ZvZVZ
Rockport - date from exif 2019:09:19 - piece of code - SaWZZ
Lake2 - date from exif 2020:09:22 - piece of code - bHp5
Western_MA - date from exif 2022:05:27  - piece of code - WVB
Vermont_Farm - date from exif 2022:07:24 - piece of code  - rVHlrV
Apple_Orchard - date from exif 2022:07:30 - piece of code - 3pObk5T


each of these photos contained an image hidden in the image, and they need to be put in chronological order


B0lWo0dVoeVRifYlzyYPkTykWzNnNS

fed this into the brochure with fullycharged and got:

w0rld0ftheelectronandtheswitch

last step is to find what is locked behind the monthly-update










