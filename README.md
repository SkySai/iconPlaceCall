# iconPlaceCall
Access the GICON API from a list of IP addresses to place call to <extension> 
the list of units / IPs is defined in the listOfIPs.txt file

USAGE: 
You can invoke this script in two ways

placeCall.sh Password listOfIPs.txt extension

placeCall.sh listOfIPs.txt extension

Notes*
Password parameter is optional. Script assumes a default password of 'admin/admin' if no password parameter is given.
listOfIPs.txt parameter is mandatory (This defines the list of units that will receive the placeCall command). See listOfIPs.txt for formatting examples. 
Extension is mandatory (This is the extension that will be dialed by all units in the listOfIPs.txt) 
 
