# Detecting Suspicious Activity

## Objective

Learn about **detective security controls**.

---

## Step 1 – View authentication logs

```bash
sudo cat /var/log/auth.log
```

## Step 2 – Search for login attempts
```bash
grep "Failed password" /var/log/auth.log
```

## Step 3 – View recent logins
```bash
last
```

## Questions
- What information appears in authentication logs?
  Authentication logs show login attempts, usernames,  login times, IP addresses, and whether the login was successful or failed.
  
- Why are logs important in cybersecurity?
  Logs are important because they help track system activity, identify security problems, investigate attacks, and detect suspicious behaviour.
  
- What might indicate suspicious activity?
  Multiple failed login attempts, logins from unknown locations, unusual login times, and unauthorised access may indicate suspicious activity.

## Deliverables
Include screenshots of:
- authentication logs
- failed login search results
  <img width="778" height="705" alt="20261127_170351_grim" src="https://github.com/user-attachments/assets/20ba8c87-7049-49f1-bb1f-5b1988b16820" />
