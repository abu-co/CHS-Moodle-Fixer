# CHS Moodle Fixer
*Imagine having to fix the school's Moodle yourself.*

Due to a recent migration of the school's intranet, heaps of stuff broke.

One of the most significant problems is that the school's 
[Moodle](http://web3.carlingfor-h.schools.nsw.edu.au/applications/moodle2/) is quite broken.  
Possibly due to some misconfiguration, one could barely access it at home.

As a feeble attempt to recover some of Moodle's features,  
this chromium extension makes necessary changes to the browser, including:
- Forcing the correct URI scheme to be used where necessary (e.g. HTTP)
- Mapping old URLs to new ones through chromium's built-in redirection feature

***However, this patch is extremely unstable; it is by no means a reliable solution to this persistent issue.***

Let's just hope somebody actually fixes Moodle before we all graduate.

> **NOTE**: Moodle is mostly working when you are connected to the school's Wi-Fi. 
Therefore, this extension is not needed if you only access it at school. 

## Installation
I really can't be bothered to put this up onto the Chrome Web Store.

Therefore, in order to install this extension, 
please refer to [Google Chrome](https://developer.chrome.com/docs/extensions/mv3/getstarted/#unpacked)
or [Microsoft Edge](https://docs.microsoft.com/en-us/microsoft-edge/extensions-chromium/getting-started/extension-sideloading)'s
official guides on loading unpacked extensions. This extension should also work on other Chromium-based browsers.

This also means that you might want to check out this page yourself 
once in a while and manually update the extension 
(i.e. delete the old extension and add the new one) 
if a newer release is published.

## Tips

- The easiest way to install this is to download this repository as a ZIP file and unzip the content into a folder,  
then load the folder as an unpacked extension.
  - *A repository can be downloaded by clicking on* `<> Code` *and selecting the* `Download ZIP` *option in the menu.*
- After installing the extension, you may (or may not) have to restart the browser or even the computer for it to take effect.  
- It is normal for pages to take a long time to load when accessing Moodle outside school.  
- It is also normal to see error popups. Just close them. 

