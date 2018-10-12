# disaster_manager
Disaster happens without warning, You or anybody could be stuck in one. Internet shutdown is one of the major communication setbacks in such times. This is where we come.Our project is aimed at helping you and others like you in times of such distress.We take info provided from <https://www.gdacs.org/> in .xml files which is used to provide the affected regions of the calamity, if you are in the said region you will be sent a sms using twilio's api using python.Your responses will be noted and according to your response we will send message to your loved ones whose phone phones will be registered while opening the account on our web app.We are using sms instead of internet related communication becuase it's more reliable. If the user requires directions from a said location to another location we will use google maps geocode api .Turn by turn directions will be sent to the user at once using text messages.

## Features ##

1. __Sms alert:__ Sms alert will only be sent to the user if he is in the estimated affected region as shown on <https://www.gdacs.org/>.
user has to respond to the queries in a predeined format. If the user says he/she is safe then assurance messages will be given to the phone no. stored while the user is registering his/her account on our web app.
If no response is recorded in a specifed amount of time then sos messages will be sent to the phone no.'s about users condition.

2. __Map Directions:__ This will help in getting to the desired location when there is no internet connectivity.
                       The user will enter his location and the destination in an SMS in a predefined format.Our service will use google maps api to get the co-ordinates if the location entered.Then we will send the turn by turn directions at once using text messages this also done through online navigation api.
                       
##  Technologies and Sevices ##

A--WEB APP

 1. Bootstrap for front end
 2. django for back end

B -- Text Mesagging

 1. Twillios API using python

C-- Misc

 1. google maps Api
 2. parsing .xml available on <https://www.gdacs.org/>
 
