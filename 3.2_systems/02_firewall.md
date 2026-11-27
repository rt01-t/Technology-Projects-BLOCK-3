# Basic Firewall Configuration

## Task 1 --- Install the Firewall

Run:

    sudo apt install ufw

### Screenshot

(Add screenshot) <img width="948" height="505" alt="20261127_153544_grim" src="https://github.com/user-attachments/assets/c5b4fbe7-770b-4173-87a3-ff3602fe482c" />


------------------------------------------------------------------------

## Task 2 --- Enable the Firewall

Run:

    sudo ufw enable

### Screenshot

(Add screenshot) <img width="830" height="474" alt="20261127_153744_grim" src="https://github.com/user-attachments/assets/2ca81053-09e0-4127-9b31-0cc06acfbd9a" />


### Questions

1.  What message appears after enabling the firewall?
    Firewall is active and enabled on system startup.
2.  Why are firewalls important?
    they protect computer systems from unauthorised access and help block unwanted network traffic.
------------------------------------------------------------------------

## Task 3 --- Allow SSH Access

Run:

    sudo ufw allow ssh
    sudo ufw status

### Screenshot

(Add screenshot) <img width="751" height="303" alt="20261127_153922_grim" src="https://github.com/user-attachments/assets/53131b72-2fc4-40bd-add3-8adf3255f23a" />


### Questions

1.  What rule was added?
    A rule was added to allow SSH connections through the firewall.
2.  Why must SSH be allowed?
    to ensure remote access to the computer from another device.
### Reflection

Explain how firewalls help protect systems from unauthorised access.
Firewalls help protect systems by monitoring and controlling incoming and oputgoing netwrok traffic. They block unwanted or suspicious connections and allow authorised traffic, helping prevent unauthorised access.
