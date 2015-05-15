

## winlaunchargs - demo plugin

Simply shows that it is possible for a cordova-windows js based plugin to get the details of how the app was launched. 

This is a response to the following jira issue:
https://issues.apache.org/jira/browse/CB-8674 



    document.addEventListener('deviceready',function(){
    	var args = launchArgs();
    	console.log("LaunchArgs are :: " + JSON.stringify(args));
    });

    // {
	//   "type": "activated",
	//   "detail": {
	//     "target": null,
	//     "detail": [
	//       {
	        
	//       }
	//     ],
	//     "type": "activated"
	//   },
	//   "_deferral": {
	    
	//   },
	//   "_deferralID": "def0"
	// }




        

        
