# iconPlaceCall
hits a list of units GIcon API to place call to <extension> 
the list of units / IPs is defined in the exampleFile.txt file
  
USAGE: 
You can invoke this script in two ways

./placeCall.sh <Password> <exampleFile.txt> <extension>
  
  
./placeCall.sh <exampleFile.txt> <extension>

Notes*

  Customer needs Linux machine

  Recommendation is to run this from a cronjob
  
  Password parameter is optional. Script assumes a default password of ‘admin/admin’ if no password parameter is given.
  
  exampleFile.txt parameter is mandatory (This defines the list of units that will receive the placeCall command). See ExampleFile.txt for formatting examples. 

  Extension is mandatory (This is the extension that will be dialed by all units in the exampleFile.txt) 
  
  
