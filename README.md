# gLabels-Templates
I'm gonna share my templates for gLabels I created to use my DYMO LabelWriter 450 Duo with gLabels-qt 3.99.
This is my first project on github, so please be clement, if it is not that fancy as expected.

# Where are the template-files?
Well, had to take a short break. Please come back in a few days. I'll upload them...

# What You may get...
I've written some templates for DYMO D1 tape labels and for some media covers / jewel boxes to print on generic plain paper. I'm from Germany, so all my templates are for the German DIN A4 paper size. Some media templates may already exist inside the gLabels-library, but because I do not use expensive preformated paper I found it hard to find the right template inside the library by searching for manufacturer or model codes. Also, some templates did not exist like a cover for a slim jewel box for CD/DVD.

# Support / FAQ
I've written those templates for my private use to create some jewel-box covers for my CD/DVD and print some stickers.

Feel free to use them, if they are helpful to You. But those templates may not be perfectly coded to fit anybodies needs. In that case You may open an issue and maybe me or someone else may help or answer Your questions. But please do not expect me to hurry. I do not promise any support or warranty. I'm just sharing those templates with You as some kind of prove-of-concept, that gLabels does support DYMO Tape printers very well and gLabels is a great tool for creating a quick and (not so) dirty label for anything in home or office. I hope someone finds it as usefull as I do.

# Known issues
I've my DYMO LabelWriter 450 Duo connected to a Linux Mint 20 system by USB. If You start printing, the printer immediately begins printing the content onto the D1 tape. The only free leading space on the printed label is the distance between the printing head and the cutting knife. So, different to the original DYMO software, gLabels does not do some kind of form-feed before printing on the tape. That's why my templates do not have a leading/tailing non-printable area of about 11mm like the DYMO software has.

Well, I've found out, that using the same template with the same gLabels-qt 3.99 on Windows 10 and then printing onto the shared printer on my Linux Mint, that non-printable space needs to be respected. I don't know if the problem is the driver or gLabels itself or anything else. So, that's why I wrote above: "..not perfectly coded...no warranty..."

# The Story Behind...
I've been using DYMO labelprinters for decades and never had problems until Windows 7 came up and my Labelmanager PC was not supported by Windows 7 x64. But the DYMO support was very friendly and changed my old LabelmanagerPC into a LabelWriter 450 Duo at quite a very low charge.
Unfortunately the new DYMO software was not that performant as the old WinXP variant was. On WinXP with my LabelmanagerPC I was able to place objects like text and images anywhere on the label, even stack them on top of each other to save space on the tape or place the object exactly where I needed it; e.g. when creating labels for 19" rack plates/patch fields or my DIY electronic devices. The new and current DYMO label software does not support that anymore. Objects can not overlap anymore. Why the h##l???

If I did not have a lot of D1 tapes in store, I would have sold my DYMO and bought a Brother p-touch, which software is fantastic! I did some feature-requests to DYMO and tried a lot of versions and other label-software to be able to use my DYMO LabelWriter with more flexibility. Finally, when I switched one of my systems from Windows to Linux, I came across gLabels-qt 3.99 (https://github.com/jimevins/glabels-qt).
Man! That's great!!! Try it, if You don't know it!
With a little research I got my DYMO LabelWriter 450 Duo running on Linux Mint 20 and printing from gLabels on tape and paper-labels. Because that day gLabels was supporting endless tape printing, but did not have any templates for DYMO D1 tapes and the template editor did not allow to create endless tape label templates. You have to code them yourself in XML. Well, so I did...
