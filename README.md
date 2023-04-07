# P2P-Radar
A Peer to Peer Radar for sharing your location privately.  Uses XMPP, OMEMO, and PGP.  

Setup:
Enter XMPP username, domain, and password.  
Enter option time/location offset if you desire added security.  
Enter the max amount of time friends will store your location.  
Enter your optional PGP private (receiver) key.  

Sending:
Turn Location Sharing On or Off.  
Add list of XMPP addresses to share with.  
Add a PGP public key optionally to add another layer of encryption for any address you send pings to.  

Receiving:
Enter the config file for the person you want to track (it contains their XMPP address, their time/location offsets, and the Max amount of time you should store their pings).  If it is encrypted with your PGP key it will be decrypted automatically.
Switch to the Receiving tab to view the location history of those who you have added (based on OSM).  

App requirements
Enable Background Location Access.  
Enable Network Access.  
Enable foreground service permission?
