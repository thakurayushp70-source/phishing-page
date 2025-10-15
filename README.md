## Phishing-page
Step 1 – Open Kali Linux

Start your Kali Linux operating system, which is a penetration testing Linux distribution preloaded with many cybersecurity tools.

Purpose: Kali Linux provides the right environment for ethical hacking tools like Zphisher.


---

Step 2 – Go to Terminal

Click on the Terminal icon or press Ctrl + Alt + T to open the command-line interface.

 Purpose: The terminal is where you’ll type and execute all Linux commands for installation and running of Zphisher.

![WhatsApp Image 2025-10-14 at 12 06 14 PM](https://github.com/user-attachments/assets/c774192c-3e00-4d0a-ba24-a50e875533b3)

---

Step 3 – Git Clone

Type the following command:

git clone https://github.com/htr-tech/zphisher.git

 Purpose:
This command downloads (clones) the Zphisher repository from GitHub into your local machine.
After completion, a new folder named zphisher will be created in your current directory.


---

Step 4 – Type ls

ls

Purpose:
ls lists all the files and folders in your current directory. You should now see a folder named zphisher among them, confirming successful download.

![WhatsApp Image 2025-10-14 at 12 06 14 PM](https://github.com/user-attachments/assets/07680df8-0b18-4294-b7d7-b460d4639b3d)

---

Step 5 – Change Directory to Zphisher

cd zphisher

 Purpose:
This command moves you inside the zphisher folder, where all tool files are stored.
Now you’re in the correct working directory to run the tool.

![WhatsApp Image 2025-10-14 at 12 06 14 PM (1)](https://github.com/user-attachments/assets/be99e76b-7eb3-4e70-93a9-41209ef8ee10)

---

Step 6 – Run the Zphisher Script

bash zphisher.sh

 Purpose:
This runs the main Zphisher script, launching the tool. You’ll now see a menu interface in your terminal where you can choose options for phishing page setup.
![WhatsApp Image 2025-10-14 at 12 06 14 PM (2)](https://github.com/user-attachments/assets/94d950db-b787-488a-abc6-8dd4d645b6aa)


---

Step 7 – Select Any Social Media (e.g., Instagram)

Zphisher will show a list of popular platforms like:

Instagram

Facebook

Gmail

Twitter
and others.


Select your desired one (e.g., Instagram) by typing its number.

 Purpose:
This selects the target website you want to simulate for the phishing demonstration.
![WhatsApp Image 2025-10-14 at 12 06 14 PM (3)](https://github.com/user-attachments/assets/58bc3583-7f85-4d1c-b437-b4d927be85e7)


---

Step 8 – Select Traditional Login Page

Choose the “Traditional Login Page” option when asked.

 Purpose:
This will use a simple login clone page that looks identical to the official site but is used here for learning how phishing templates are structured.

![WhatsApp Image 2025-10-14 at 12 06 14 PM (4)](https://github.com/user-attachments/assets/793cb86e-ce70-4c89-9ce0-fd305266abf6)

---

Step 9 – Select Localhost

Choose “Localhost” when asked how to host the phishing page.

 Purpose:
This means your phishing page will be hosted locally on your computer, not online — safe for practice because no one else can access it.


---

Step 10 – Get the Link

After setup, Zphisher will generate a localhost link (something like http://127.0.0.1:8080).

 Purpose:
This link opens your phishing simulation page locally.

![WhatsApp Image 2025-10-14 at 12 06 14 PM (5)](https://github.com/user-attachments/assets/1a7d8973-3c10-4ff0-8cdf-7f8adccadc56)

---

Step 11 – Open the Link in Browser

Copy the generated link and paste it into your browser (e.g., Firefox or Chrome inside Kali).

 Purpose:
You’ll see the fake login page (for example, Instagram’s login page copy) loaded locally.
This demonstrates how phishing pages appear to users.
![WhatsApp Image 2025-10-14 at 12 06 14 PM (6)](https://github.com/user-attachments/assets/6f45b5aa-34db-416f-8d0b-bb06ec38d862)


---

Step 12 – Check Details in Terminal

When you (or a test user) enter credentials on that page, the details appear in the terminal window.

 Purpose:
This shows how phishing captures credentials, helping you understand how attackers steal data — and thus, how to prevent it.

![WhatsApp Image 2025-10-14 at 12 06 14 PM (7)](https://github.com/user-attachments/assets/40d9c06c-7694-456b-af5f-8b6294772486)

---

Step 13 – Stop the Program

Press:

Ctrl + C

 Purpose:
This stops Zphisher and ends the local server. Always close it after your testing session.
![WhatsApp Image 2025-10-14 at 12 06 14 PM (8)](https://github.com/user-attachments/assets/8ef08a56-7490-44cf-979c-e8dbdcd263b3)
