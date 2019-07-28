# HOW TO
1. import both files into postman
2. Choose the environment "Volvo Env" and replace the values for "volvo_user" and "volvo_password" with your specific data
3. execute the requests "Account Data" and "Vehicle Relation" --> VIN of your car will be added to "Volvo Env"
**Remark**: If you have more than one car connected to your Account, the first in the list will be taken.
4. For some controll commands (e.g. blink&honk, start preclimatization, unlock car) you need the current location of the car --> execute the request "Position" to get the position stored in the environment and automatically be filled for following requests
**remark**: repeat step four if car was moved
