# GoPhish Phishing Simulation Lab: Facebook Credential Capture

## Objective
This project demonstrates the setup and execution of a phishing attack simulation using GoPhish. The lab focuses on capturing login credentials through a fake Facebook page, highlighting the importance of cybersecurity awareness and phishing defense techniques. By setting up a phishing campaign, users gain hands-on experience with tools commonly used in phishing simulations.

## Skills Learned
- Configuring and running the GoPhish phishing simulation tool.
- Setting up a phishing campaign targeting login credentials.
- Crafting phishing emails, landing pages, and campaigns.
- Understanding the process of phishing attacks and their detection.
- Collecting and analyzing phishing data using GoPhish’s reporting tools.

## Tools Used
- **GoPhish**: Phishing simulation tool used to launch phishing campaigns.
- **HTML**: Used to create a fake login page for capturing credentials.
- **SMTP Server**: For sending phishing emails (e.g., Gmail’s SMTP server).
- **Web Browser**: Used to access the phishing login page.

## Steps and Screenshots

### Step 1: Installing GoPhish
- Download GoPhish from the official website based on your operating system.
- Extract the ZIP file to a known location, such as your desktop.

**Ref 1: GoPhish Download Page**  
![GoPhish Download Page](imgsrc)  
_Explanation_: Screenshot of GoPhish’s download page showing available versions for different operating systems.

**Ref 2: GoPhish ZIP Extracted**  
![GoPhish Extracted](imgsrc)  
_Explanation_: Screenshot showing the extracted GoPhish folder.

### Step 2: Running the GoPhish Server
- Navigate to the extracted GoPhish folder.
- Run the GoPhish server by executing `gophish.exe` (Windows) or the corresponding executable for your OS.
- GoPhish will provide a link to the local server, e.g., `http://localhost:3333`.

**Ref 3: Running GoPhish Server**  
![GoPhish Server](imgsrc)  
_Explanation_: Screenshot showing the GoPhish executable being run and the command line displaying the link to the local server.

### Step 3: Logging into the GoPhish Dashboard
- Open your web browser and navigate to the link provided by GoPhish (`http://localhost:3333`).
- Use the default credentials provided in the command line for the first login.

**Ref 4: GoPhish Login Page**  
![GoPhish Login Page](imgsrc)  
_Explanation_: Screenshot of the GoPhish login page and default credentials.

### Step 4: Configuring Phishing Campaign Settings

#### 4.1 Creating a Sending Profile
- Go to the Sending Profiles section in GoPhish.
- Create a new profile by filling in details such as “From Name,” “From Email,” and the SMTP server details.

**Ref 5: Sending Profile Creation**  
![Sending Profile](imgsrc)  
_Explanation_: Screenshot of the Sending Profiles form where fields like “From Name” and “SMTP Server” are being filled.

#### 4.2 Creating a Landing Page
- In the GoPhish dashboard, create a fake login page that mimics Facebook’s login.
- Use HTML to capture login credentials and set the Redirect URL to the legitimate Facebook page.

**Ref 6: Landing Page Creation**  
![Landing Page Creation](imgsrc)  
_Explanation_: Screenshot showing the fake Facebook login page being previewed, with the HTML code used for capturing credentials.

#### 4.3 Crafting the Phishing Email (Email Templates)
- Create a phishing email template that mimics a legitimate Facebook email, encouraging the user to log in via the fake landing page.

**Ref 7: Phishing Email Template**  
![Phishing Email Template](imgsrc)  
_Explanation_: Screenshot showing the email template form and the HTML preview of the phishing email.

#### 4.4 Adding Users and Groups
- Add the email addresses of your targets (e.g., yourself for testing) in the Users & Groups section.

**Ref 8: Adding Target Users**  
![Adding Users](imgsrc)  
_Explanation_: Screenshot showing the Users & Groups section where the target email addresses are added.

### Step 5: Launching the Phishing Campaign
- Go to the Campaigns section and create a new campaign.
- Select the email template, landing page, sending profile, and users, and then launch the campaign.

**Ref 9: Launching the Campaign**  
![Launching Campaign](imgsrc)  
_Explanation_: Screenshot of the campaign creation form, showing the email template, landing page, and sending profile selection.

### Step 6: Testing and Results
- Open the phishing email from your inbox, click the link, and try logging in via the fake Facebook page.
- Check the GoPhish dashboard for captured credentials and data on user actions.

**Ref 10: Phishing Email in Inbox**  
![Phishing Email](imgsrc)  
_Explanation_: Screenshot showing the phishing email received in the inbox.

**Ref 11: Captured Credentials**  
![Captured Credentials](imgsrc)  
_Explanation_: Screenshot showing captured login credentials and user actions in the GoPhish dashboard.

## Challenges and Solutions
- **SMTP Configuration**: Some SMTP servers (like Gmail) require additional authentication steps, such as enabling less secure apps or generating app-specific passwords.
- **Landing Page Setup**: The HTML code used for the fake Facebook page must be carefully crafted to mimic a real login page while capturing user credentials.

## Results
- Successfully launched a phishing campaign using GoPhish.
- Captured login credentials and monitored user actions via the GoPhish dashboard.
- Demonstrated how phishing attacks work and how to protect against them.

## Learning Outcomes
- Gained practical experience in setting up and launching a phishing campaign using GoPhish.
- Learned how phishing emails and fake landing pages are created and deployed.
- Improved understanding of phishing attacks, social engineering tactics, and ways to detect and prevent such attacks.

## Next Steps
- Expand the project by simulating phishing campaigns targeting multiple users.
- Explore more sophisticated landing pages and phishing templates.
- Analyze the effectiveness of the phishing campaign by tracking user responses and improving email and landing page design.
