<!--
	Title: Current Zoom Issues
	Author: Glen Piper
	Date: 190905

	(A summary rundown of the current Zoom rollout issues reported to the SD)
-->

## Current Zoom Rollout Issues Reported to the SD  

(1) Original client Zoom account created with the same email alias/address as the “Preferred” alias used by SSO

|   SR   	|  Date/Time 	|    Client    	| Owned By 	| Notes            	|
|:------:	|:----------:	|:------------:	|:--------:	|------------------	|
|314107|9/3 5:19p|Kevin Crouch|DJ Viser|alias kevincrouch used|
|314176|9/4 9:00a|Andrew Oswald|Cody Willard|alias andy used| 
|314323|9/4 2:27p|Jessica Sides|Cody Willard|jjs083 used| 
|||||| 
| 314404 	| 9/4 6:19pm 	|  Julie Combs 	| DJ Viser 	| jpc002 used      	|


* Currently unable to access files from original/pre-SSO Zoom account
* Currently unable to get logged in via original or SSO


(2) SSO Auto-Redirect prevents client from logging in & accessing original account

|   SR   	|  Date/Time 	|    Client    	| Owned By 	| Notes            	|
|:------:	|:----------:	|:------------:	|:--------:	|------------------	|
|314501|9/5 10:17a|Richard Gebhardt|Cody Willard|Shared mailbox used for original Zoom| 
|314230|9/4 11:25a|Jennifer Adams|David Rice|Client can’t cancel prior license| 

* Whenever client tries to login to original account (web or app), the auto-redirect to SSO intercepts as soon as the login process sees the email with the @shsu.edu address and sends them right to the new SSO/preferred-alias account
* I have encountered this as well


(3) Zoom client (Win10) disappears & shows up in Software Center as still installed, even though previous installed version had been installed via SCCM package push.

|   SR   	|  Date/Time 	|    Client    	| Owned By 	| Notes            	|
|:------:	|:----------:	|:------------:	|:--------:	|------------------	|
|314213|9/4 10:25a|Andie Hampton|Travis Williams|Reinstall resolved issue| 
|314452|9/5 9:09a|Brenda McRae|Dylan De Leon|Restart resolved issue| 


(4) Zoom Outlook Add-in not available after node received SCCM package push

|   SR   	|  Date/Time 	|    Client    	| Owned By 	| Notes            	|
|:------:	|:----------:	|:------------:	|:--------:	|------------------	|
|314284|9/4 1:08p|Neal Whitney|Alanna Cooper|Fresh install resolved issue| 

* Issue has occurred on six SD student worker computers
* Add-in not available in Outlook under Add-in settings, but shows as installed in Software Center
* Zoom Add-in can be installed after downloading it from Zoom website; doesn’t require local admin; will this impact the SCCM package in the future?

