# Observing Network Traffic on Rapsberry Pi

## Task 1 --- Install tcpdump

Run:

    sudo apt install tcpdump

### Screenshot

(Add screenshot)<img width="779" height="398" alt="20261127_163230_grim" src="https://github.com/user-attachments/assets/9a5e3331-aeaf-445d-b1ec-833952c25c78" />


------------------------------------------------------------------------

## Task 2 --- Capture Network Traffic

Run:

    sudo tcpdump

Let the capture run for about 20 seconds.

### Screenshot

(Add screenshot)<img width="1546" height="1180" alt="20261127_163611_grim" src="https://github.com/user-attachments/assets/84fc2df2-5fb3-4a50-afd8-896de7f207f5" />

<img width="1893" height="1167" alt="20261127_163628_grim" src="https://github.com/user-attachments/assets/084242df-4766-40b4-a16a-ee6138d550ce" />
<img width="1901" height="1158" alt="20261127_163644_grim" src="https://github.com/user-attachments/assets/81a5d51d-2b42-4d63-9d6b-08e67ec9848e" />


### Questions

1.  What types of traffic do you observe?
   I observed different types of network traffic such as TCP, UDP, DNS, and HTTPS traffic. These are used for communication between devices and servers.
2.  Can you identify IP addresses?
   yes. These show which device is sending data and which device is receiving it.
3.  Do you see DNS queries?
    Yes, DNS queries can be observed.

### Reflection

Explain what network monitoring can reveal about system activity.
Network monitoring helps us see what is happening on a system, such as which devices are connected, what data is being sent and received, and whether there is any unusual activity. It helps identify network problems and possible security threats.
------------------------------------------------------------------------

## Task 3 --- Security Discussion

### Questions

1.  Could sensitive information appear in network traffic?
   Yes, sensitive information such as username, passwords, personal details or messages could appear in network traffic if the communication is not properly encrypted.

2.  Why is HTTPS important for protecting communications?
    HTTPS encrypts the communication between a user and a website. It helps protect sensitive information from intercepted or read by others and also helps verify that the user is connecting to the correct website.

### Reflection

Describe what you learned about network visibility and security.
I learned that network monitoring helps us understand how devices communicate and identify unusual activity.I also earned that encryption, such as HTTPS, is impoertant for protecting sensitive information and maintaining privacy.
