# auto-bat-detector
Bats emit echo location calls at high frequencies to enable them to 'see' in the dark and we humans need to be able to monitor the species to help prevent destruction of their environment during our ever increasing exploitation of the planet. Recording and analysing bat call audio is a great way to achieve this monitoring, especially if it can be fully automated.

This particular bat detector device can be run off 12 volt batteries and be deployed in the wild for days / weeks at a time with data being transmitted every now and again via a LoRa radio link. Essentially, it records 30 second chunks of audio, does a quick analysis of that audio using machine learning, and then renames the audio file with species, confidence and date if it detected a bat. All other recordings are automatically deleted to save disc space and time for the biologist / researcher.

This auto bat detector project is originally created by Tecwyn Twmffat:
(alias the ugly pirate roaming the seas in search of Treasure :)
https://hackaday.io/project/169854-intelligent-wildlife-species-detector
https://www.instructables.com/Intelligent-Bat-Detector/
https://github.com/paddygoat/ultrasonic_classifier 
https://learn.adafruit.com/using-lorawan-and-the-things-network-with-circuitpython/wiring 
https://thingspeak.com/ 
