# Live-Camera-Replay-Balena.io-Viewer
View the picamera server that we made earlier


There are no files. What you need to do is:

1.Create a new Application(if you don't already have one)


2.Create a new device


3.Flash the downloaded image onto micro sd card


4.Put sd card onto the new pi(not the server pi, we don't touch that one in this tutorial)


5.Once pi is powered on, you need to run these commands on your local terminal:


<code>$ git clone https://github.com/Screenly/screenly-ose.git</code>

<code>$ cd screenly-ose</code>

<code>$ git remote add balena username@git.balena-cloud.com:username/app name.git</code>
  
<code>$ git push balena master</code>


6.Turn on the public device url


7.Go to the public device url and add an asset

8.add the asset link 
