# Understanding File Permissions

## Task 1 --- Create a File

Run:

    touch secret.txt
    ls -l secret.txt

### Screenshot

(Add screenshot here)<img width="1917" height="1130" alt="20261120_170105_grim" src="https://github.com/user-attachments/assets/e0f78a94-c43a-4863-8b2d-b8fa9ce3b56a" />


### Questions

1.  Who owns the file?
2.  What are the default permissions?

### Reflection

Why is file ownership important in Linux systems?

------------------------------------------------------------------------

## Task 2 --- Restrict File Permissions

Run:

    chmod 600 secret.txt
    ls -l secret.txt

### Screenshot

(Add screenshot here)<img width="1917" height="1130" alt="20261120_170105_grim" src="https://github.com/user-attachments/assets/21059768-c2a5-4dae-907c-c8bf84af1087" />


### Questions

1.  Who can read the file now?
2.  Who cannot access it?


------------------------------------------------------------------------

## Task 3 --- Open Permissions (Security Risk)

Run:

    chmod 777 secret.txt
    ls -l secret.txt

### Screenshot

(Add screenshot here)<img width="751" height="317" alt="20261120_170745_grim" src="https://github.com/user-attachments/assets/de8e92a7-d350-49ce-a671-2fd709d978d9" />


### Questions

1.  Who can access the file now?
2.  Why might this configuration be dangerous?

