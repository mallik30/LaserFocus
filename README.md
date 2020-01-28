# LaserFocus (Pro)

***Find the Add-on [Here](https://addons.mozilla.org/en-US/firefox/addon/laserfocus/)***

Used [nude.js](https://github.com/pa7/nude.js/) to filter out adult content from the browser, and it works remarkably well !

***
Comments are welcome
Your critical analysis and support on this extension will be helpful for this project.
***
##### PS: This add-on was actually made as a part of personal project, but still users can fork (or clone) this repository and customize it accordingly.

To make the project work according to your needs,
1. Clone / fork this repo.
2. Go to ```content.js``` file
a. ```findString``` method finds the strings in the argument and blocks the webpage
b. ```findStringMulti``` method takes in 3 strings as a parameter and blocks the webpages which contain all three.
c. ```findURL``` blocks only the main domain names and does NOT block the subdomains.
d. ```findAllURL``` blocks domains as well as all the subdomains.
e. Do NOT Modify the ```include()``` method. It's used to include ```nude.js``` into the extension.
8. For Firefox users:
a. Goto [this link](https://addons.mozilla.org/en-US/developers/addons). (Make sure you are logged into your firefox account)

b. My Add-ons > Submit a new Add-on

c. On your own > Select a file (Submit the compressesed folder) > Sign add-on > Yes > Submit the zipped file again

d. Wait till you receive an email confirmation.

e. Goto [this link](https://addons.mozilla.org/en-US/developers/addons). Find your add-on > Edit product page > View All (Near Upload new version) > Click on your version > Click on the ```.xpi``` file.

f. Accept all permissions and allow it into private window.
4. Chrome users:
[Note : Remove ```"applications" : { ... }``` from ```manifest.json```]

a. Go to [Here](chrome://extensions/).

b. Switch on developer mode > Load Unpacked > Select the root folder of your files

c. The chrome will run the extension on your PC. But, it will always ask to Disable developer mode extensions when you open a new chrome window, until you submit it as a chrome extension (with a small fee). That's why I chose Firefox :)

***
For any discrepancies or queries, contact: [br37hg@gmail.com](mailto:br37hg@gmail.com)
