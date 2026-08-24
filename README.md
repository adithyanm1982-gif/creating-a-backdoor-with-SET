# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

### DEVELOPER: ADITHYA NM
### REG NO: 212225040011
### DATE: 24-08-2026

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
1. Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:
## OUTPUT
<img width="1918" height="792" alt="image" src="https://github.com/user-attachments/assets/70e064b0-6a81-4c44-bc5d-1bd3d21f9178" />



2. The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT
<img width="917" height="240" alt="image" src="https://github.com/user-attachments/assets/c5c2cdfb-73ff-4243-92d9-a7d6e367772e" />



3. It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT
<img width="872" height="296" alt="image" src="https://github.com/user-attachments/assets/70f784c9-a8be-41c8-a198-d0f972cafc76" />



4. The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT
<img width="1918" height="465" alt="image" src="https://github.com/user-attachments/assets/f0851fa0-3c58-4150-a07c-e04546bcb804" />



5. It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT




6. It shows the following screen in which the option Google can be selected:
## OUTPUT




7. SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT
<img width="1202" height="188" alt="image" src="https://github.com/user-attachments/assets/d3a3b4cc-c064-42da-a699-597cdb65f6e0" />



8. In windows IE, on giving the url http://10.113.53.195 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT
<img width="1919" height="800" alt="Screenshot 2026-08-24 134022" src="https://github.com/user-attachments/assets/b50aacbf-1b25-480f-9649-d55005437d4b" />



9. SET logs the information regarding the Google credentials:
## OUTPUT
<img width="1674" height="450" alt="Screenshot 2026-08-24 140252" src="https://github.com/user-attachments/assets/54cf9915-46a6-41c6-a478-59721f9c6998" />



10. SET logs the information in the xml file under /root/.set directory:
## OUTPUT
<img width="1845" height="727" alt="Screenshot 2026-08-24 141200" src="https://github.com/user-attachments/assets/9ec1dc91-e7c2-4299-9fb0-136419e5d51e" />



## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
