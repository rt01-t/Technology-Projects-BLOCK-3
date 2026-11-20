# Exploring Your System's Security

## Task 1 --- List System Users

Run:

    cat /etc/passwd

### Screenshot
<img width="1920" height="1200" alt="20261120_165041_grim" src="https://github.com/user-attachments/assets/8b17143e-6855-48ba-9a40-b7d5540afc24" />


### Questions

1.  How many users exist on the system?
2.  Which accounts appear to be system accounts?
3.  Why do operating systems create system accounts?

### Reflection

Explain why understanding system users is important for cybersecurity.

------------------------------------------------------------------------

## Task 2 --- Inspect Running Processes
cat /etc/passwd
Run:

    ps aux

### Screenshot
<img width="1920" height="1200" alt="20261120_165542_grim" src="https://github.com/user-attachments/assets/b129cd52-1e26-45f2-9713-090794b5e64c" />

<img width="1541" height="1182" alt="20261120_165854_grim" src="https://github.com/user-attachments/assets/7263e760-f1d8-44a8-b579-4aa1637a0af1" />
<img width="1885" height="1163" alt="20261120_165947_grim" src="https://github.com/user-attachments/assets/5ef376e7-dcea-42f4-b083-e985808cc229" />


### Questions

1.  Which processes are running as `root`?
2.  Why can processes running as root be dangerous?
3.  What could happen if a malicious program ran with root privileges?

### Reflection

What did you learn about system processes and security?

------------------------------------------------------------------------

## Task 3 --- Identify Open Network Ports

Run:

    ss -tuln

### Screenshot

(Add screenshot here)<img width="1917" height="1130" alt="20261120_170105_grim" src="https://github.com/user-attachments/assets/0369336c-8845-45cd-9221-9152cfc3fb82" />


### Questions

1.  Which ports are open?
2.  Which services appear to be listening?
3.  Why might open ports represent a security risk?

### Reflection

Explain the relationship between open ports and potential attack
surfaces.
