<div align="center">
  <a href="https://imgur.com/k4VWmn7">
    <img src="https://i.imgur.com/k4VWmn7.png" title="source: imgur.com" width="500" />
  </a>
</div>

# Secure, Automated, and Multi-Cloud Bitwarden Backup and Import System

Lazywarden is a Python automation tool for backing up and restoring data from your vault, including Bitwarden attachments. It allows you to upload backups to multiple cloud storage services and receive notifications on various platforms. It offers AES encrypted backups and Argon2 key derivation to ensure maximum security of your data.

## <span style="display: flex; align-items: center;"><img src="https://raw.githubusercontent.com/querylab/svg/main/start.gif" width="50" style="vertical-align: middle; margin-right: 10px;"> Features</span>

- 🔒 **Maximum Security:** Data protection with AES-256 encryption and Argon2 key derivation.
- 🔄 **Automated Backups and Imports:** Keep your Bitwarden vault up to date and secure.
- ✅ **Integrity Verification:** SHA-256 hash to ensure data integrity on every backup.
- ☁️ **Multi-Cloud Support:** Store backups to services such as Dropbox, Google Drive, pCloud, MEGA, NextCloud, Seafile, Filebase (IPFS) and via SMTP.
- 🖥️ **Local Storage:** Save backups to a local path for greater control.
- 🔔 **Real-Time Alerts:** Instant notifications on Discord, Telegram and Slack.
- 🗓️ **Schedule Management:** Integration with Todoist and CalDAV to manage your schedule.
- 🐳 **Easy Deployment:** Quick setup with Docker Compose.
- 🤖 **Full Automation and Custom Scheduling:** Automatic backups with flexible scheduling options (daily, weekly, monthly, yearly). Integration with CalDAV and Todoist for complete tracking and email notifications.
- 🔑 **Bitwarden Export to KeePass:** Export Bitwarden items to a KeePass database (kdbx), including TOTP-seeded logins, URI, custom fields, card, identity attachments and secure notes.

## <span style="display: inline-flex; align-items: center;"><img src="https://media.tenor.com/-AyTtMgs2mMAAAAi/nyan-cat-nyan.gif" width="60" style="vertical-align: middle; margin-right: 10px;"> Platform Compatibility</span>


<div style="display: flex; justify-content: space-around; gap: 8em;">
    <a href="https://imgur.com/Xz2k5O8"><img src="https://i.imgur.com/Xz2k5O8.png" title="source: imgur.com" width="30"/></a>
    <a href="https://imgur.com/9oZa9uU"><img src="https://imgur.com/9oZa9uU.png" title="source: imgur.com" width="30"/></a>
    <a href="https://imgur.com/jWZzbvl"><img src="https://imgur.com/jWZzbvl.png" title="source: imgur.com" width="30"/></a>
    <a href="https://imgur.com/O0PZyxN"><img src="https://i.imgur.com/O0PZyxN.png" title="source: imgur.com" width="30"/></a>
    <a href="https://imgur.com/aa100eH"><img src="https://i.imgur.com/aa100eH.png" title="source: imgur.com" width="30"/></a>
    <a href="https://imgur.com/Grlq9aN"><img src="https://i.imgur.com/Grlq9aN.png" title="source: imgur.com" width="30"/></a>
    <a href="https://imgur.com/UYGpfR8"><img src="https://i.imgur.com/UYGpfR8.png" title="source: imgur.com" width="30"/></a>
    <a href="https://imgur.com/G37MsuK"><img src="https://i.imgur.com/G37MsuK.png" title="source: imgur.com" width="30"/></a>
    <a href="https://imgur.com/XpWPF0w"><img src="https://i.imgur.com/XpWPF0w.png" title="source: imgur.com" width="30"/></a>
    <a href="https://imgur.com/YMGE85n"><img src="https://i.imgur.com/YMGE85n.png" title="source: imgur.com" width="30"/></a>
    <a href="https://imgur.com/w9PULK5"><img src="https://i.imgur.com/w9PULK5.png" title="source: imgur.com" width="30"/></a>
    <a href="https://imgur.com/hjuaEcF"><img src="https://i.imgur.com/hjuaEcF.png" title="source: imgur.com" width="30"/></a>
    <a href="https://imgur.com/BhI5DBR"><img src="https://imgur.com/BhI5DBR.png" title="source: imgur.com" width="30"/></a>
    <a href="https://imgur.com/krgaizW"><img src="https://imgur.com/krgaizW.png" title="source: imgur.com" width="30"/></a>
    <a href="https://imgur.com/QAawp1J"><img src="https://imgur.com/QAawp1J.png" title="source: imgur.com" width="30"/></a>
    <a href="https://imgur.com/hRwMM9n"><img src="https://imgur.com/hRwMM9n.png" title="source: imgur.com" width="30"/></a>
</div>





## <span style="display: inline-flex; align-items: center;"><img src="https://user-images.githubusercontent.com/74038190/212257472-08e52665-c503-4bd9-aa20-f5a4dae769b5.gif" width="36" style="vertical-align: middle; margin-right: 10px;"> Demo Backup</span>


<img src="https://raw.githubusercontent.com/querylab/svg/main/lazy_official.gif" />

<img src="https://raw.githubusercontent.com/querylab/svg/main/lazy-video.gif" />


## <span style="display: inline-flex; align-items: center;"><img src="https://user-images.githubusercontent.com/74038190/212257472-08e52665-c503-4bd9-aa20-f5a4dae769b5.gif" width="36" style="vertical-align: middle; margin-right: 10px;"> Demo Import</span>

<img src="https://raw.githubusercontent.com/querylab/svg/main/import-bitwarden.gif" />

<img src="https://raw.githubusercontent.com/querylab/svg/main/attach-import.gif" />




## <span style="display: inline-flex; align-items: center;"><img src="https://user-images.githubusercontent.com/74038190/212257472-08e52665-c503-4bd9-aa20-f5a4dae769b5.gif" width="36" style="vertical-align: middle; margin-right: 10px;"> Demo Schedule</span>

<img src="https://raw.githubusercontent.com/querylab/svg/main/lazy_schedule.gif" />

## <span style="display: inline-flex; align-items: center;"><img src="https://user-images.githubusercontent.com/74038190/212257472-08e52665-c503-4bd9-aa20-f5a4dae769b5.gif" width="36" style="vertical-align: middle; margin-right: 10px;"> Demo Import Keepass</span>

<img src="https://raw.githubusercontent.com/querylab/svg/main/keepass_convert.gif" />

<img src="https://raw.githubusercontent.com/querylab/svg/main/keepass_import.gif" />



###  <span style="display: inline-flex; align-items: center;"><img src="https://raw.githubusercontent.com/querylab/svg/main/mail3.gif" width="25" style="vertical-align: middle; margin-right: 10px;"> SMTP Backup</span>


<a href="https://imgur.com/mslQKF1"><img src="https://i.imgur.com/mslQKF1.png" title="source: imgur.com" /></a>

### <span style="display: inline-flex; align-items: center;"><img src="https://raw.githubusercontent.com/querylab/svg/main/mail3.gif" width="25" style="vertical-align: middle; margin-right: 10px;"> SMTP Scheduled</span>

<a href="https://imgur.com/HaHcCz2"><img src="https://i.imgur.com/HaHcCz2.png" title="source: imgur.com" /></a>

### <span style="display: inline-flex; align-items: center;"><img src="https://raw.githubusercontent.com/querylab/svg/main/caldav01.gif" width="24" style="vertical-align: middle; margin-right: 10px;"> CalDAV Backup</span>

<a href="https://imgur.com/UlQ85ys"><img src="https://i.imgur.com/UlQ85ys.png" title="source: imgur.com" /></a>

### <span style="display: inline-flex; align-items: center;"><img src="https://raw.githubusercontent.com/querylab/svg/main/caldav01.gif" width="24" style="vertical-align: middle; margin-right: 10px;"> CalDAV Schedule</span>

<a href="https://imgur.com/64ALZdj"><img src="https://i.imgur.com/64ALZdj.png" title="source: imgur.com" /></a>


### <span style="display: inline-flex; align-items: center;"><img src="https://raw.githubusercontent.com/querylab/svg/main/todoist04.gif" width="70" style="vertical-align: middle; margin-right: 10px;"> Todoist Backup</span>

<a href="https://imgur.com/RPgq7yh"><img src="https://i.imgur.com/RPgq7yh.png" title="source: imgur.com" /></a>

### <span style="display: inline-flex; align-items: center;"><img src="https://raw.githubusercontent.com/querylab/svg/main/todoist04.gif" width="70" style="vertical-align: middle; margin-right: 10px;"> Todoist Schedule</span>

<a href="https://imgur.com/iofaSLp"><img src="https://i.imgur.com/iofaSLp.png" title="source: imgur.com" /></a>


### <span style="display: inline-flex; align-items: center;"><img src="https://raw.githubusercontent.com/querylab/svg/main/slacke.gif" width="22" style="vertical-align: middle; margin-right: 10px;"> Slack</span>

<a href="https://imgur.com/cNuyygB"><img src="https://i.imgur.com/cNuyygB.png" title="source: imgur.com" /></a>
### <span style="display: inline-flex; align-items: center;"><img src="https://raw.githubusercontent.com/querylab/svg/main/discord.gif" width="22" style="vertical-align: middle; margin-right: 10px;"> Discord</span>

<a href="https://imgur.com/jYqRY6t"><img src="https://i.imgur.com/jYqRY6t.png" title="source: imgur.com" /></a>
### <span style="display: inline-flex; align-items: center;"><img src="https://raw.githubusercontent.com/querylab/svg/main/telegram1.gif" width="35" style="vertical-align: middle; margin-right: 10px;"> Telegram </span>

<a href="https://imgur.com/SSXBWJT"><img src="https://i.imgur.com/SSXBWJT.png" title="source: imgur.com" /></a>



## <span style="display: inline-flex; align-items: center;"> <img src="https://raw.githubusercontent.com/querylab/svg/main/server2.gif" width="50" style="vertical-align: middle; margin-right: 10px;"> <img src="https://raw.githubusercontent.com/querylab/svg/main/process2.gif" width="50" style="vertical-align: middle; margin-right: 15px;"> System Requirements </span>
- **Operating System**: Compatible with major Linux distributions

	- ✅ Ubuntu
	- ✅ Debian

## <span style="display: inline-flex; align-items: center;"><img src="https://github.com/Anmol-Baranwal/Cool-GIFs-For-GitHub/assets/74038190/2c0eef4b-7b75-42bd-9722-4bea97a2d532" width="60" style="vertical-align: middle; margin-right: 15px;">Installation</span>
###  Clone the repository

 ``` BASH
    git clone https://github.com/querylab/lazywarden.git
    cd lazywarden
```

### Configure Environment Variables & Bitwarden Secrets Manager

- Create a `.env` file based on the on this `.env.sample` example file and fill in the necessary variables.

``` BASH
GOOGLE_SERVICE_ACCOUNT_FILE=/home/lazywarden/config/bitwarden-drive-backup-google.json
GOOGLE_FOLDER_ID=1qt111fImyfolderJ6RiCc-b0M99vsF
BACKUP_DIR=/home/lazywarden/backup-drive/
DISCORD_WEBHOOK_URL=
SLACK_WEBHOOK_URL=
TELEGRAM_TOKEN=
TELEGRAM_CHAT_ID=
SMTP_SERVER=mail.smtp2go.com
SMTP_PORT=8025
SMTP_USERNAME=
SMTP_PASSWORD=
EMAIL_RECIPIENT=
SENDER_EMAIL=
API_URL=https://api.bitwarden.com             # Please No Modify No Touch
IDENTITY_URL=https://identity.bitwarden.com   # Please No Modify No Touch
ORGANIZATION_ID=232c12220-78f9-q888-b769-a14ddd88bf
ACCESS_TOKEN=0.50bf3g00-4fef-002b-a680-0000000000049.P1vlm2222222222bfiOUO:f3G1N40IoCVxNB4GtYJdmw==  #Access Token from Bitwarden Secrets Manager Ubuntu-Lazywarden Machine
CRON_SCHEDULE="*/15 * * * *" # For Docker Compose 
TIMEZONE=America/New_York    # For CalDAV and Todoist
TIMESTAMP=2024_07_16_20_30_20       # To decrypt all zip files in your backup or import them, just use the timestamp that was generated in the backup. For example, use the files that are generated in the backup like this: bw-backup_2024_07_16_20_30_20.zip.

```

### <img src="https://raw.githubusercontent.com/querylab/svg/main/ubuntu.gif" width="20" style="vertical-align: middle;"> Ubuntu Configuration

- Run the script to install all system dependencies and requirements
 
``` BASH

cd lazywarden/scripts

chmod +x setup-ubuntu-env.sh

./setup-ubuntu-env.sh

```


- Run this script to automatically install Docker & Docker-Compose:

```BASH

chmod +x docker-ubuntu.sh

./docker-ubuntu.sh

```

- First, ensure you are in the root directory of the project `lazywarden/`:

``` BASH
cd .. 

source venv/bin/activate

```

- Now Install Bitwarden CLI using the `bitwarden-cli-install.py` script, which will install all CLI dependencies:

``` PYTHON
python3 scripts/bitwarden-cli-install.py
```

- Run the Lazywarden program. Navigate to the `app/` folder and execute `main.py`:

``` PYTHON
cd app
python3 main.py

```

---

### <img src="https://raw.githubusercontent.com/querylab/svg/main/debian.png" width="20" style="vertical-align: middle;"> Debian Configuration

 - Run the script to install all system dependencies and requirements:
 
``` BASH
cd lazywarden/scripts
chmod +x setup-debian-env.sh
./setup-debian-env.sh

```

- Run this script to automatically install Docker & Docker-Compose:

```BASH

chmod +x docker-debian.sh
./docker-debian.sh

```

- First, ensure you are in the root directory of the project `lazywarden/`:

``` BASH
cd .. 
source venv/bin/activate
```

- Install Bitwarden CLI using the `bitwarden-cli-install.py` script, which will install all CLI dependencies:

``` PYTHON
python3 scripts/bitwarden-cli-install.py
```

- Run the Lazywarden program. Navigate to the `app/` folder and execute `main.py`:

``` PYTHON
cd app
python3 main.py

```





## <img src="https://raw.githubusercontent.com/querylab/svg/main/toolbox1.gif" width="30" style="vertical-align: middle;"> Steps to Configure Bitwarden Secrets Manager

To set up Secret Management in Bitwarden, first create a new organization in your account to serve as a container for shared secrets. Next, subscribe to the Secret Manager service, which allows you to securely store an unlimited number of secrets, such as API keys, passwords and certificates. This service provides end-to-end encryption, centralized management and access control.

<a href="https://imgur.com/8rfhTnu"><img src="https://i.imgur.com/8rfhTnu.png" title="source: imgur.com" /></a>

- After creating your Organization, go to Secret Manager in the tab at the top right.

<a href="https://imgur.com/bT15xW3"><img src="https://i.imgur.com/bT15xW3.png" title="source: imgur.com" /></a>

- Then create your lazywarden Project.

<a href="https://imgur.com/ozqIyOu"><img src="https://i.imgur.com/ozqIyOu.png" title="source: imgur.com" /></a>

- After creating your lazywarden Project, you need to create the secrets that will be in the lazywarden project. Here are some examples:

<a href="https://imgur.com/TFY5Hmu"><img src="https://i.imgur.com/TFY5Hmu.png" title="source: imgur.com" /></a>


<a href="https://imgur.com/C8rI6Lc"><img src="https://i.imgur.com/C8rI6Lc.png" title="source: imgur.com" /></a>


<a href="https://imgur.com/VsV6S4k"><img src="https://i.imgur.com/VsV6S4k.png" title="source: imgur.com" /></a>

- If you have TOTP enabled on your Bitwarden account, put the seeds of your TOTP in the **BW_TOTP_SECRET** variable.

<a href="https://imgur.com/L0KquJ3"><img src="https://i.imgur.com/L0KquJ3.png" title="source: imgur.com" /></a>

- If you do not have TOTP enabled on your Bitwarden account, just put random characters as shown in the image below.

<a href="https://imgur.com/CWSeqIV"><img src="https://i.imgur.com/CWSeqIV.png" title="source: imgur.com" /></a>


- Continue filling in the other variables one by one. If you do not have an account, for example for pCloud, MEGA, Filebase, Seafile, NextCloud or Dropbox fill in the variables with some random characters. For example, if you don't have a MEGA account, put the following:

<a href="https://imgur.com/apttibR"><img src="https://i.imgur.com/apttibR.png" title="source: imgur.com" /></a>

<a href="https://imgur.com/orCUZoG"><img src="https://i.imgur.com/orCUZoG.png" title="source: imgur.com" /></a>

- As you can see in the images above, I don't have a MEGA account, so I used random strings. You always have to have something in the Secret Variables for the program to work. Now, the backup will only be stored locally in the chosen directory and in Google Drive, Dropbox, pCloud, NextCloud, Seafile and Filebase but not in MEGA as my account is not configured 


- After creating all your secrets, create a Machine Account that will hold our ACCESS_TOKEN.


<a href="https://imgur.com/nATZchh"><img src="https://i.imgur.com/nATZchh.png" title="source: imgur.com" /></a>


<a href="https://imgur.com/pSWJfqR"><img src="https://i.imgur.com/pSWJfqR.png" title="source: imgur.com" /></a>


- Add and save the lazywarden project to your Machine Account.

<a href="https://imgur.com/SbyDk7m"><img src="https://i.imgur.com/SbyDk7m.png" title="source: imgur.com" /></a>

<a href="https://imgur.com/ipvIXhM"><img src="https://i.imgur.com/ipvIXhM.png" title="source: imgur.com" /></a>

- Finally, go to Access Tokens and create one to use in our lazywarden project.

<a href="https://imgur.com/K1wKCOR"><img src="https://i.imgur.com/K1wKCOR.png" title="source: imgur.com" /></a>


- With these secrets added, we can now modify our **secrets_manager.py** file to contain our secrets.

``` PYTHON
	
    "BW_URL": "d71e13be-12ab-4567-89ef-9c8d50f2c6a1",
    "BW_USERNAME": "b7c8a4d2-1c34-4568-9f23-a5e9c47b3c29",
    "BW_PASSWORD": "9f1a4b6c-3452-4a79-890d-b0e5d35c8f6e",
    "BW_TOTP_SECRET": "a9c1e8d3-1f67-4563-8f7e-2c5b8e3d4f6a",
    "ENCRYPTION_PASSWORD": "c8a5b4d3-3e1f-4a6c-8e9d-5c3b4e6f8d2a",
    "ZIP_PASSWORD": "e1c9a3b6-4f7a-4d6e-8f2b-3c5e7d9f8a1c",
    "ZIP_ATTACHMENT_PASSWORD": "f3a8b5c7-9d1e-4f6c-8e2a-4b6d7e9f2a3c",
    "PCLOUD_USERNAME": "d9e1c8a3-6b4f-4a7c-8d2e-5c3a6f8b4d1c",
    "PCLOUD_PASSWORD": "b4e7d1a8-1c9f-4a5c-8d6e-2e5f7b3a4c8d",
    "MEGA_EMAIL": "e7c1a8b3-9d4f-4a6c-8f2e-3b5d8e1f4a7c",
    "MEGA_PASSWORD": "c3e9a1b5-4f6a-4d7c-8e2d-6b5a3e4d7f9c",
    "DROPBOX_ACCESS_TOKEN": "d6e3a1c9-8f4a-4b7c-8e2d-5c4a6f1b8d7e",
    "DROPBOX_REFRESH_TOKEN": "a3e8d1b7-4c9f-4a6e-8d2b-7c5e9b1d4a6f",
    "DROPBOX_APP_KEY": "e9c1a8b3-7f4d-4a6c-8d2e-1b3f5e9a7c6d",
    "DROPBOX_APP_SECRET": "c1e7d9a3-4b6f-4a7c-8d2e-3b5a9e4f1c6d",
    "TODOIST_TOKEN": "a9e1d3b7-4c6f-4a7c-8d2e-5b1e9a6d4f7c",
    "CALDAV_URL": "e3a8d1c7-4b6f-4a7c-8e2d-1b5f9e4a7c6d",
    "CALDAV_USERNAME": "c9e1a3d7-4f6b-4a7c-8d2e-3b5d7e1f9a6c",
    "CALDAV_PASSWORD": "b1e8d3a9-4f6c-4a7c-8e2d-7c3e9a1f5b6d",
    "NEXTCLOUD_URL": "a7e1c9b3-4f6d-4a7c-8e2d-5b3d9e1a7f4c",
    "NEXTCLOUD_USERNAME": "e1c8a3d9-4f6b-4a7c-8d2e-3b5e9a1f7c6d",
    "NEXTCLOUD_PASSWORD": "d3e1a8b7-4f6c-4a7c-8e2d-1b5f9d3a6c7e",
    "SEAFILE_SERVER_URL": "c1e8d9a3-4f6b-4a7c-8d2e-7c3e1b5f9a6d",
    "SEAFILE_USERNAME": "b9e1d3a8-4f6c-4a7c-8e2d-5b1f9e4d7c6a",
    "SEAFILE_PASSWORD": "e7a3d9b1-4f6c-4a7c-8d2e-3b5d1a9f6e7c",
    "SEAFILE_REPO_NAME": "a1c9e8d3-4f6b-4a7c-8e2d-9c3e5b1f7d4a",
    "FILEBASE_ACCESS_KEY": "e3c1a9d8-4f6b-4a7c-8d2e-1b5f7d4a9e6c",
    "FILEBASE_SECRET_KEY": "b7e1d3a9-4f6c-4a7c-8e2d-5c3e9a1b6f7d",
    "FILEBASE_BUCKET_NAME": "c3e1d9a7-4f6b-4a7c-8d2e-7b5f1e9a4c6d",
    "KEEPASS_PASSWORD": "d1e7a3b9-4f6c-4a7c-8e2d-3b5f9c4a7e6d"
    
```

- To find the **ORGANIZATION_ID** variable for our **.env** you can get it by visiting the URL when you are in your organization or by running the following command:

``` BASH
bw list organizations
```

``` BASH
ORGANIZATION_ID=212A4880-22f9-1114-b00e-b1950234278ac

ACCESS_TOKEN=0.345f5e9c-8730-4a4c-917b-b10000331f56.Oj4XzcyGFF22222L22l7LZL333A7VkwzV:e5mC4d11111117bS8/3EQ==
```

# <img src="https://raw.githubusercontent.com/querylab/svg/main/alert1.gif" width="30" style="vertical-align: middle;"> Attention: Security Critical Variables <img src="https://raw.githubusercontent.com/querylab/svg/main/pad2.gif" width="30" style="vertical-align: middle;"> <img src="https://raw.githubusercontent.com/querylab/svg/main/key2.gif" width="30" style="vertical-align: middle;">


``` BASH
### These variables contain the passwords for encrypting the backup.
### Change the passwords according to your preferences.

#Contains the encryption password for the JSON file
ENCRYPTION_PASSWORD=p3mTd5SqDqkXQqE!Tpwv27Ecx  


#Contains the encryption password for the first ZIP file
ZIP_PASSWORD=ZCGvq@gwS7QhV@&R3k*x*xN72anybyFHW2RWiBTr  


# Contains the encryption password for the attached ZIP file.
# Where our files will be stored if Bitwarden Premium is enabled.
# If Bitwarden Premium is not enabled, the attachment folder will be empty.
ZIP_ATTACHMENT_PASSWORD=HBLXL9!grer@Uay2edkwTXeZx!E9DxKphNxsNak1knb3dcfx2o   


```

## <img src="https://raw.githubusercontent.com/querylab/svg/main/dropbox.gif" width="70" style="vertical-align: middle;"> Dropbox API Configuration

By following these steps, your Dropbox Token will remain active and will not expire every 4 hours.

1. Go to https://www.dropbox.com/developers/apps/create 
 -  Create a new project.
 
 <a href="https://imgur.com/1YcSkdv"><img src="https://i.imgur.com/1YcSkdv.png" title="source: imgur.com" /></a>


<a href="https://imgur.com/G0b4moU"><img src="https://i.imgur.com/G0b4moU.png" title="source: imgur.com" /></a>



- Create Permissions

<a href="https://imgur.com/t0nCg9h"><img src="https://i.imgur.com/t0nCg9h.png" title="source: imgur.com" /></a>


2. Obtain the Authorization Code

- Open a browser and navigate to the following URL, replacing `<App key>` with your App Key:

``` HTML
https://www.dropbox.com/oauth2/authorize?token_access_type=offline&response_type=code&client_id=<App key>
```

<a href="https://imgur.com/IWjIhNa"><img src="https://i.imgur.com/IWjIhNa.png" title="source: imgur.com" /></a>


<a href="https://imgur.com/qtTh6DG"><img src="https://i.imgur.com/qtTh6DG.png" title="source: imgur.com" /></a>



<a href="https://imgur.com/tjlD8Ez"><img src="https://i.imgur.com/tjlD8Ez.png" title="source: imgur.com" /></a>



3. Obtain the Authorization Token

Run the following command in the terminal, making sure to replace `<received code>`, `<App key>`, and `<App secret>` with the correct values:

``` BASH
curl https://api.dropbox.com/oauth2/token \
-d code=<received code> \
-d grant_type=authorization_code \
-u <App key>:<App secret>

#Example
curl https://api.dropbox.com/oauth2/token \
-d code=G4sTbrY9DMoAAAAAAAAAQTeLtVHACmv1tVaWYLYCGvA \
-d grant_type=authorization_code \
-u 7on1ofss5fu26ki:b6bl6jgjmrlm8iz
```

- When you run the command, you will receive a response like this:

``` BASH
 "access_token": "sl.B3hxfHXrUAVg5nhPOO9z8_TS230pcLcLNbJj019MyrVHj-ccZmG5XCcQrN-Wb6ESMs0PSzwOtROxLb6XRaj6mUzHU1g8G60canTvjkWBBaNzVYP15cx5hH2FEOhlwseaNcnQ9RyPn6vh",
  "token_type": "bearer",
  "expires_in": 14400,
  "refresh_token": "WtG6MI5YdccAAAAAAAAAAcAvuFd9usnB6skR3BmpgH3x5Reb-ae7FsLuNQ5-mZkk",
  "scope": "account_info.read",
  "uid": "143786425",
  "account_id": "dbid:BBAnJyzGYtm3-WP9a2HkL1TL8FVgPl5s-VM"
```

- Now use this new `refresh_token`, `access_token` along with the previous `<App key>`, and `<App secret>` to fill in the secret variables needed in Bitwarden Secret Manager:

``` BASH
#Example
      DROPBOX_ACCESS_TOKEN=sl.B3hxfHXrUAVg5nhPOO9z8_TS230pcLcLNbJj019MyrVHj-ccZmG5XCcQrN-Wb6ESMs0PSzwOtROxLb6XRaj6mUzHU1g8G60canTvjkWBBaNzVYP15cx5hH2FEOhlwseaNcnQ9RyPn6vh
      DROPBOX_REFRESH_TOKEN=WtG6MI5YdccAAAAAAAAAAcAvuFd9usnB6skR3BmpgH3x5Reb-ae7FsLuNQ5-mZkk
      DROPBOX_APP_KEY=7on1ofss5fu26ki
      DROPBOX_APP_SECRET=b6bl6jgjmrlm8iz

```



## <img src="https://raw.githubusercontent.com/querylab/svg/main/drive3.gif" width="70" style="vertical-align: middle;"> Google Drive API Configuration

1. Go to this web page [https://console.developers.google.com/iam-admin/serviceaccounts](https://console.developers.google.com/iam-admin/serviceaccounts)
2. Create a New Project.

<a href="https://imgur.com/evhyf31"><img src="https://i.imgur.com/evhyf31.png" title="source: imgur.com" /></a>



3.  Then go to "Service Accounts" and create a new service.

<a href="https://imgur.com/h8HOeJI"><img src="https://i.imgur.com/h8HOeJI.png" title="source: imgur.com" /></a>


<a href="https://imgur.com/BqtT80X"><img src="https://i.imgur.com/BqtT80X.png" title="source: imgur.com" /></a>

<a href="https://imgur.com/p45sVX5"><img src="https://i.imgur.com/p45sVX5.png" title="source: imgur.com" /></a>

4.  Select the role "Actions Admin".

<a href="https://imgur.com/ew9hXRq"><img src="https://i.imgur.com/ew9hXRq.png" title="source: imgur.com" /></a>


5.  Download the key in JSON format. This key will be used in our project to upload the Bitwarden backup to Google Drive. Once you obtain the JSON file, store it in the **/config** folder of the project. Name the JSON file **bitwarden-drive-backup-google.json**.

``` BASH
# Place the Google credentials file in the specified path /config

GOOGLE_SERVICE_ACCOUNT_FILE=/home/lazywarden/config/bitwarden-drive-backup-google.json

```

<a href="https://imgur.com/AhhWgDM"><img src="https://i.imgur.com/AhhWgDM.png" title="source: imgur.com" /></a>

<a href="https://imgur.com/GwbnFyr"><img src="https://i.imgur.com/GwbnFyr.png" title="source: imgur.com" /></a>

6. Go to the following link and enable the Google Drive API:[https://console.cloud.google.com/apis/library](https://console.cloud.google.com/apis/library)

<a href="https://imgur.com/sWRw0sb"><img src="https://i.imgur.com/sWRw0sb.png" title="source: imgur.com" /></a>

7. Now that you have enabled the API, go to your Google Drive and create a folder named "Bitwarden-Backup".

<a href="https://imgur.com/7pCl08b"><img src="https://i.imgur.com/7pCl08b.png" title="source: imgur.com" /></a>


8. Share the "Bitwarden-Backup" folder by clicking on "Share" and share it with the email address created in the Service Account when you set up the project.

<a href="https://imgur.com/ozawjb7"><img src="https://i.imgur.com/ozawjb7.png" title="source: imgur.com" /></a>

<a href="https://imgur.com/B4w8Mtu"><img src="https://i.imgur.com/B4w8Mtu.png" title="source: imgur.com" /></a>

<a href="https://imgur.com/kko5vkh"><img src="https://i.imgur.com/kko5vkh.png" title="source: imgur.com" /></a>

9. After sharing the folder, you need to get the ID of this folder to store it in your **.env** file. To find the ID of the "Bitwarden-Backup" folder, open the folder and look at the URL in your browser.

``` BASH
GOOGLE_FOLDER_ID=1qtV4vfIjmXyhDdzIzJ6RiCc-b0M22vsF
```

<a href="https://imgur.com/fNJ07Yb"><img src="https://i.imgur.com/fNJ07Yb.png" title="source: imgur.com" /></a>



### <img src="https://raw.githubusercontent.com/querylab/svg/main/tree2.gif" width="30" style="vertical-align: middle;">Tree Structure 

``` PYTHON

lazywarden/
├── app/                           # This directory appears to contain the main application code
│   ├── backup.py                  # Backup functions
│   ├── bitwarden_client.py        # Client to interact with Bitwarden
│   ├── config.py                  # General application configurations
│   ├── imports.py                 # Handles common imports
│   ├── main.py                    # Main entry point of the application
│   ├── notifications.py           # Handles notifications
│   ├── secrets_manager.py         # Manages secrets
│   ├── import_to_bitwarden.py     # Import your bitwarden vault
│   ├── import_to_keepass.py       # Create kdbx database 
│   ├── schedule_backup.py         # For create Schedule Backup
├── config/                        # Directory for configuration files
│   ├── bitwarden-drive-backup-google.json # Configuration for Google Drive
├── scripts/                       # Directory for installation and setup scripts
│   ├── bitwarden-cli-install.py   # Script to install the Bitwarden CLI
│   ├── docker-debian.sh           # Setup script for Debian with Docker
│   ├── docker-ubuntu.sh           # Setup script for Ubuntu with Docker
│   ├── setup-debian-env.sh        # Environment setup for Debian
│   ├── setup-ubuntu-env.sh        # Environment setup for Ubuntu
│   ├── alldecrypt-zip.py          # Decrypt all zip files 
│   ├── json-only-decrypt.py       # Decrypt only json files (optional)
├── backup-drive/
│   ├── (This is where the generated backups will be stored local)
├── .env                           # File for environment variables
├── Dockerfile                     # Docker configuration file to create an application image
├── docker-compose.yml             # Docker Compose Configuration
├── entrypoint.sh                  # Entrypoint script for Docker
└── requirements.txt               # File that lists the project Python dependencies


```



### <img src="https://raw.githubusercontent.com/querylab/svg/main/snake1.gif" width="30" style="vertical-align: middle;"> Cron Job for Python (optional)

To automatically run the backup script in the background using cron, follow these steps:

1. Open the crontab for editing:

```BASH
crontab -e
```

2. Select an editor if you dont have one configured:

``` BASH

Select an editor.  To change later, run 'select-editor'.
  1. /bin/nano        <---- easiest
  2. /usr/bin/vim.basic
  3. /usr/bin/vim.tiny
  4. /bin/ed
Choose 1-4 [1]: 1

```


3. Add the following line to schedule the `lazywarden.py` script to run at midnight every day:


``` BASH 

0 0 * * * /usr/bin/python3 /home/lazywarden/app/main.py >> /home/lazywarden/app/lazywarden.log 2>&1


```


4. Save and close the file. Verify that the cron job is set up correctly:

``` BASH
crontab -l
```



### <img src="https://raw.githubusercontent.com/querylab/svg/main/whale1.gif" width="30" style="vertical-align: middle;"> Docker Compose

The Docker container will run the `main.py` script every 24 hours to back up Bitwarden and upload it to the configured cloud services. Notifications will be sent to the specified services in case of success or failure. You can modify the backup frequency according to your needs, such as monthly, daily, or hourly.

``` BASH

version: '3.0'

services:
  lazywarden:
    build: .
    container_name: lazywarden_backup
    environment:
      - TELEGRAM_TOKEN=${TELEGRAM_TOKEN}
      - TELEGRAM_CHAT_ID=${TELEGRAM_CHAT_ID}
      - GOOGLE_SERVICE_ACCOUNT_FILE=/config/bitwarden-drive-backup-google.json
      - GOOGLE_FOLDER_ID=${GOOGLE_FOLDER_ID}
      - API_URL=${API_URL}
      - IDENTITY_URL=${IDENTITY_URL}
      - ORGANIZATION_ID=${ORGANIZATION_ID}
      - ACCESS_TOKEN=${ACCESS_TOKEN}
      - BACKUP_DIR=/bitwarden-backup/backup-drive/
      - DISCORD_WEBHOOK_URL=${DISCORD_WEBHOOK_URL}
      - SLACK_WEBHOOK_URL=${SLACK_WEBHOOK_URL}
      - SMTP_SERVER=${SMTP_SERVER}
      - SMTP_PORT=${SMTP_PORT}
      - SMTP_USERNAME=${SMTP_USERNAME}
      - SMTP_PASSWORD=${SMTP_PASSWORD}
      - EMAIL_RECIPIENT=${EMAIL_RECIPIENT}
      - SENDER_EMAIL=${SENDER_EMAIL}
      - CRON=${CRON}
      - TIMEZONE=${TIMEZONE}
      - TIMESTAMP=${TIMESTAMP}
    volumes:
      - /home/lazywarden/config:/config  
      - /home/lazywarden/backup-drive:/home/lazywarden/backup-drive/
    restart: unless-stopped

```

#### Run Docker Compose

- Run the Docker container

```DOCKER
docker compose up -d
```

#### Dockerfile

- The `Dockerfile` sets up the environment, installs dependencies, and copies necessary files into the container.

#### docker-compose.yml

- The `docker-compose.yml` file defines the lazywarden service and sets up environment variables and volumes for persistent storage.

### <img src="https://raw.githubusercontent.com/querylab/svg/main/alert1.gif" width="30" style="vertical-align: middle;"><img src="https://raw.githubusercontent.com/querylab/svg/main/cloud1.gif" width="30" style="vertical-align: middle;"><img src="https://raw.githubusercontent.com/querylab/svg/main/process2.gif" width="30" style="vertical-align: middle;"> Security Recommendation: Run in Local Environment 

- For security, run this project only in a local environment within your personal network. This significantly reduces the risk of exposure to external attacks, ensuring that sensitive data and credentials remain protected within a controlled environment.


### 📢 Warning

#### **Important Note**

- If you have large attachments in your Bitwarden account (e.g., MP4 videos, MP3 files, high-resolution photos), the backup process may take some time to complete. Larger backup files will take longer to upload to the cloud. Local storage of the backup is significantly faster, and the same applies to importing data.
- A large number of attachments in your account can significantly increase the total backup time. Errors may occur when uploading the file to Dropbox, Google Drive, pCloud, MEGA, Seafile, Nextcloud, or Filebase. If errors occur, try again; the backup may succeed on a subsequent attempt.
- Setting up the Bitwarden Secret Manager is mandatory for the program to function correctly. Even if you do not have an account, you must declare a random variable to ensure proper operation.
- This program works for Selfhosted Bitwarden and Vaultwarden.
- Importing for Vaultwarden and self-hosted Bitwarden has not yet been implemented in the Bitwarden API.
- The CalDAV calendar integration has only been tested with Baikal [https://github.com/sabre-io/Baikal](https://github.com/sabre-io/Baikal), Fruux [https://fruux.com](https://fruux.com), Memotoo [https://www.memotoo.com](https://www.memotoo.com), Posteo [https://posteo.de](https://posteo.de), and SOGo [https://www.sogo.nu/](https://www.sogo.nu/).
- Rotate the secrets in Bitwarden Secret Manager regularly.




### <span style="display: inline-flex; align-items: center;"> <img src="https://user-images.githubusercontent.com/74038190/216122069-5b8169d7-1d8e-4a13-b245-a8e4176c99f8.png" width="30" style="vertical-align: middle; margin-right: 10px;"> Motivations </span>

- I wanted an automated solution to manage Bitwarden backups without manual intervention or risk of exposing sensitive data. After trying several complicated and frustrating tools, I discovered Bitwarden Secret Manager, which keeps secrets secure within the same platform. This inspired me to create Lazywarden, a tool that not only automates the management of secrets and backups through Bitwarden, but also automatically uploads backups to Google Drive, Dropbox, pCloud, MEGA, Seafile, Nextcloud and Filebase. In addition, I have integrated notifications with Telegram, Discord, Slack and backup tracking with Todoist and CalDAV calendars. What makes Lazywarden truly special is that, in addition to backing up, it allows you to import those encrypted backups back into your Bitwarden. This project was born out of the need to simplify and secure backup management in an efficient and reliable way.

- If you like this project, please consider giving it a ⭐


<div align="center">
  <a href="https://imgur.com/k4VWmn7">
    <img src="https://user-images.githubusercontent.com/74038190/216644507-4f06ea29-bf55-4356-aac0-d42751461a9d.gif" title="source: imgur.com" width="150" />
  </a>
</div>



