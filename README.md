
This project requires a MIllicast.com account. 
https://millicast.com/

Screen Share with audio currently will only work for publishing stream in a Chrome browser.Sample with audio video frames can be added.

1. In your Millicast portal(+) Add a new token M Make sure to select Use ANY name!

Open you js/screenshare.js file and edit the following lines 40 47 and 49 .

   let yourUrl = "https://YOURSITE.com/millicast/screenshare/player/?id=";
   let accountId = 'YOURID'; //let accountId ADD YOUR ACCOUNT ID from your Millicast portal
   let streamName = params.get('id');
   let token ="YOUR LONG TOKEN STRING FROM PORTAL";  // YOUR TOKEN GOES Here
   
Open Your js/viewer.js file and edit line 2.
   let accountId = 'YOURID'; //let accountId ADD YOUR ACCOUNT ID HERE 
   
Place the ScreenShare contents on your site. 
You will use an ID=YOUR_STREAM_NAME.

Go to your site link https://YOUR_WEB_SITE.com/screenshare/?id=YOUR_STREAM_NAME


  
