In order to download and use the code examples provided you should clone the repository. 
Assumimg you have Git installed on your computer (see https://github.com/git-guides/install-git) open a terminal window in Visual Studio Code ( or use a terminal window provided by your operating system). Type the following command to download the project from a remote server to the folder you are currently in locally
git clone https://github.com/FionaMacRaeFairlie/WAD2Lab7.git
Use cd to move to the root directory of the cloned project, npm install to get the node dependancies set up then run the project by typing node index.

Note: remember that, as discussed in the lecture,if you are using the lab computers you may experience issues using the nedb database. To avoid this use the up-to-date version of the database gray-nedb. You will firstly need to install gray-nedb: npm install gray-nedb then change line 1 at the top of the file guestbookModel.js in the models folder to const nedb = require('gray-nedb');
