# GSM_THINGSPEAK
Sending data from arduino to thingspeak using GSM
After collecting our data about how many people were in a certain room by the use of the two ultrasonics, we went ahead and sent the data
to an online servre(thingspeak) using their api.
To push the data to the server, we used a SIM800L gsm and configured it to the field we created on thingspeak platform(field 1).
We needed to establish a connection at first, then send the data and finally terminate the connection.
We were sending the data after every 1 minute(60000millis).
