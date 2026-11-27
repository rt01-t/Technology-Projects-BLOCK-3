# Exploring the CIA Triad

## Objective

Understand the **Confidentiality, Integrity and Availability (CIA)** principles using practical tasks on a Raspberry Pi.

---

# Part 1 – Confidentiality

1. Create a confidential file.

    ```bash
    nano secrets.txt
    ```

1. Write some confidential information.

1. Save the file.

1. Now restrict access:
    ```bash
    chmod 600 secrets.txt
    ```
1. Check permissions:
    ```bash
    ls -l secrets.txt
    ```

**Questions**
- Who can read this file?
-  only the file owner can read this file.
- How does file permission protect confidentiality?
-  It prevents other users from reading or accessing the confidential.

## Part 2 – Integrity

1. Create a hash of the file.
    ```bash
    sha256sum secrets.txt
    ```
    _What does "hash" do?
   A hash generate a unique digital value from a file. It helps check whether the file has been changed.

1. Save the output.
    

1. Modify the file.
    ```bash
    nano secrets.txt
    ```

1. Run the hash again.


** Questions**
- Did the hash change?
-  yes, the hash changed because the file content was modified.
- Why do security systems use hashing?
  Security systems use hashing to check data integrity and detect unauthorised changes.

# Part 3 – Availability

1. Check system uptime:
    ```bash
    uptime
    ```

1. List running processes:
    ```bash
    top
    ```

**Questions**
- Why is system uptime important?
  It shows how long a compouter has been running.
- What happens if a system is unavailable?
   user cannot access its services or data.

## Deliverables
Include:
- Screenshot of file permissions
- Screenshot of hash results
- Answers to questions
- Reflection
    >Explain how this activity demonstrated the CIA triad.
