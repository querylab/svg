

<div class="icon-container">
    <img src="https://raw.githubusercontent.com/querylab/svg/main/bitwarden.svg" alt="Bitwarden" />
    <img src="https://raw.githubusercontent.com/querylab/svg/main/dropbox.svg" alt="Dropbox" />
    <img src="https://raw.githubusercontent.com/querylab/svg/main/googledrive.svg" alt="Google Drive" />
    <img src="https://raw.githubusercontent.com/querylab/svg/main/pcloud.svg" alt="pCloud" />
    <img src="https://raw.githubusercontent.com/querylab/svg/main/mega.svg" alt="Mega" />
    <img src="https://raw.githubusercontent.com/querylab/svg/main/smtp.svg" alt="Smtp" />
    <img src="https://raw.githubusercontent.com/querylab/svg/main/slack.svg" alt="Slack" />
    <img src="https://raw.githubusercontent.com/querylab/svg/main/discord.svg" alt="Discord" />
    <img src="https://raw.githubusercontent.com/querylab/svg/main/telegram.svg" alt="Telegram" />
    <img src="https://raw.githubusercontent.com/querylab/svg/main/todoist.svg" alt="Todoist" />
</div>


# 🔐🏛️Lazywarden: Your Automated, Secure, and Multi-Cloud Bitwarden Backup System

Lazywarden is a Python-based automation tool designed to back up your vault data, including Bitwarden attachments, and upload it to multiple cloud storage services. It supports notifications across multiple platforms and includes an AES encrypted backup feature with a key derived using Argon2 to ensure the security of your data.

## <span style="display: flex; align-items: center;"><img src="https://raw.githubusercontent.com/querylab/svg/main/start.gif" width="50" style="vertical-align: middle; margin-right: 10px;"> Features</span>

- 🔒 **Top-Level Security**: Protect your data with AES-256 encryption and Argon2 key derivation for maximum security.
- ☁️ **Multi-Cloud Compatibility**: Store your backups in multiple cloud storage services like Dropbox, Google Drive, pCloud, MEGA, and via SMTP.
- 🔔 **Real-Time Alerts**: Receive instant notifications through Discord, Telegram, and Slack to stay informed.
- 📅 **Schedule Tracking**: Easily track and manage your schedule with Todoist integration.
- 🐳 **Easy Deployment**: Quick and effortless setup with Docker Compose, ensuring a consistent environment.
- 🔄 **Full Automation:** Performs daily backups automatically without the need for manual intervention, ensuring the safety of your data at all times. Users can also adjust the backup frequency according to their needs, choosing from daily, monthly, or even hourly options.

## <span style="display: inline-flex; align-items: center;"><img src="https://user-images.githubusercontent.com/74038190/212257472-08e52665-c503-4bd9-aa20-f5a4dae769b5.gif" width="40" style="vertical-align: middle; margin-right: 10px;"> Demo</span>


<img src="https://raw.githubusercontent.com/querylab/svg/main/lazywarden6.gif" />



<img src="https://raw.githubusercontent.com/querylab/svg/main/lazyuploud.gif"/>




###  <span style="display: inline-flex; align-items: center;"><img src="https://raw.githubusercontent.com/querylab/svg/main/mail3.gif" width="25" style="vertical-align: middle; margin-right: 10px;"> SMTP</span>

<a href="https://imgur.com/xZREtUL"><img src="https://i.imgur.com/xZREtUL.png" title="source: imgur.com" /></a>
### <span style="display: inline-flex; align-items: center;"><img src="https://raw.githubusercontent.com/querylab/svg/main/slacke.gif" width="22" style="vertical-align: middle; margin-right: 10px;"> Slack</span>

<a href="https://imgur.com/TgC6ZmA"><img src="https://i.imgur.com/TgC6ZmA.png" title="source: imgur.com" /></a>

### <span style="display: inline-flex; align-items: center;"><img src="https://raw.githubusercontent.com/querylab/svg/main/discord.gif" width="22" style="vertical-align: middle; margin-right: 10px;"> Discord</span>

<a href="https://imgur.com/7XnwmpQ"><img src="https://i.imgur.com/7XnwmpQ.png" title="source: imgur.com" /></a>

### <span style="display: inline-flex; align-items: center;"><img src="https://raw.githubusercontent.com/querylab/svg/main/telegram1.gif" width="35" style="vertical-align: middle; margin-right: 10px;"> Telegram </span>

<a href="https://imgur.com/nKBCp4x"><img src="https://i.imgur.com/nKBCp4x.png" title="source: imgur.com" /></a>




## <span style="display: inline-flex; align-items: center;"> <img src="https://raw.githubusercontent.com/querylab/svg/main/server2.gif" width="50" style="vertical-align: middle; margin-right: 10px;"> <img src="https://raw.githubusercontent.com/querylab/svg/main/process2.gif" width="50" style="vertical-align: middle; margin-right: 15px;"> System Requirements </span>
- **Operating System**: Compatible with major Linux distributions

	- ✅ Ubuntu
	- ✅ Debian

## <span style="display: inline-flex; align-items: center;"><img src="https://raw.githubusercontent.com/querylab/svg/main/rocket1.gif" width="50" style="vertical-align: middle; margin-right: 15px;">Installation</span>
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
BW_URL=https://bitwarden.com #Modify this URL if your account is hosted in US/EU or if you are using self-hosted Bitwarden or Vaultwarden
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
ORGANIZATION_ID=232c1890-78f9-8888-b769-b14448888bf
ACCESS_TOKEN=0.50bf3g00-4fef-002b-a680-0000000000049.P1vlm2222222222bfiOUO:f3G1N40IoCVxNB4GtYJdmw==  #Access Token from Bitwarden Secrets Manager Ubuntu-Lazywarden Machine

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

- If you have an issue with the system time run the following command

``` BASH

timedatectl list-timezones

timedatectl set-timezone America/Chicago

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

- If you have an issue with the system time run the following command

``` BASH

timedatectl list-timezones

timedatectl set-timezone America/New_York

```






### Steps to Configure Bitwarden Secrets Manager <img src="https://raw.githubusercontent.com/querylab/svg/main/toolbox1.gif" width="30" style="vertical-align: middle;">

To set up Secret Management in Bitwarden, first create a new organization in your account to serve as a container for shared secrets. Next, subscribe to the Secret Manager service, which allows you to securely store an unlimited number of secrets, such as API keys, passwords and certificates. This service provides end-to-end encryption, centralized management and access control.

<a href="https://imgur.com/8rfhTnu"><img src="https://i.imgur.com/8rfhTnu.png" title="source: imgur.com" /></a>

- After creating your Organization, go to Secret Manager in the tab at the top right.

<a href="https://imgur.com/bT15xW3"><img src="https://i.imgur.com/bT15xW3.png" title="source: imgur.com" /></a>

- Then create your lazywarden Project.

<a href="https://imgur.com/ozqIyOu"><img src="https://i.imgur.com/ozqIyOu.png" title="source: imgur.com" /></a>

- After creating your lazywarden Project, you need to create the secrets that will be in the lazywarden project. Here are some examples:

<a href="https://imgur.com/OOfG53k"><img src="https://i.imgur.com/OOfG53k.png" title="source: imgur.com" /></a>

<a href="https://imgur.com/C8rI6Lc"><img src="https://i.imgur.com/C8rI6Lc.png" title="source: imgur.com" /></a>

<a href="https://imgur.com/VsV6S4k"><img src="https://i.imgur.com/VsV6S4k.png" title="source: imgur.com" /></a>

- If you have TOTP enabled on your Bitwarden account, put the seeds of your TOTP in the **BW_TOTP_SECRET** variable.

<a href="https://imgur.com/L0KquJ3"><img src="https://i.imgur.com/L0KquJ3.png" title="source: imgur.com" /></a>

- If you do not have TOTP enabled on your Bitwarden account, just put random characters as shown in the image below.

<a href="https://imgur.com/I0ZuVZ1"><img src="https://i.imgur.com/I0ZuVZ1.png" title="source: imgur.com" /></a>


- Continue filling in the other variables one by one. If you do not have an account, say for pCloud or MEGA, fill the variables with some random characters. For example, if you do not have a MEGA account, you would put the following:

<a href="https://imgur.com/apttibR"><img src="https://i.imgur.com/apttibR.png" title="source: imgur.com" /></a>

<a href="https://imgur.com/orCUZoG"><img src="https://i.imgur.com/orCUZoG.png" title="source: imgur.com" /></a>

- As you can see in the previous images, I do not have a MEGA account, so I used random strings. Always have something in the Secret Variables for the program to work. Now, the backup will only be stored locally in the directory you chose and in Google Drive, Dropbox, and pCloud, but not in MEGA as my account is not configured in the secrets.



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
"BW_USERNAME": "c6a5fc4d-6d36-486f-820a-a1dae99e2f43"
"BW_PASSWORD": "0de9c3be-253d-4761-be10-de0607329ffa"
"BW_TOTP_SECRET": "01726d37-0df7-476a-a78d-96fdc8efd59b"
"ENCRYPTION_PASSWORD": "588b0643-7ba4-4a78-ba3e-9467ad9c81a7"
"ZIP_PASSWORD": "3bcadf27-446d-47f0-b929-b1469fa58546"
"ZIP_ATTACHMENT_PASSWORD": "89d458e7-9ac4-431e-9f23-95cb4b8cff86"
"PCLOUD_USERNAME": "8d5f981b-705a-4096-a25d-a2abe925f4e4"
"PCLOUD_PASSWORD": "23351280-0184-4cbf-99b0-2b6a1bc921ae"
"MEGA_EMAIL": "1dafc95a-63c2-4b66-8c2b-bd7cd5a2ea5e"
"MEGA_PASSWORD": "51bec27b-7c79-4a63-9cef-1be72675a47f"
"DROPBOX_ACCESS_TOKEN": "647ff022-6bc1-47d9-a54f-fef635b23eff"
"DROPBOX_REFRESH_TOKEN": "873e5430-4abb-4d62-8bf2-acce1e915a9d"
"DROPBOX_APP_KEY": "81f259ae-d6e4-47b1-b77f-6bec568ddc85"
"DROPBOX_APP_SECRET": "0b407a02-ded5-45ed-b953-caf8fc79af99"
"TODOIST_TOKEN": "667321ac-2229-42a1-a0ff-3c568c9d73e6"
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
ZIP_ATTACHMENT_PASSWORD=HBLXL9!grer@Uay2edkwTXeZx!E9DxKphNxsNak$knb$dcfx2o   


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
  "uid": "1974034225",
  "account_id": "dbid:AAAnAyzGYtm3-WKsa2HkL1TL8FVgPp5s-VM"
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
├── app/       #This directory appears to contain the main application code
│   ├── backup.py                #Backup functions
│   ├── bitwarden_client.py      #Client to interact with Bitwarden
│   ├── config.py                #General application configurations
│   ├── imports.py               #Handles common imports
│   ├── main.py                  #Main entry point of the application
│   ├── notifications.py         #Handles notifications
│   ├── secrets_manager.py       #Manages secrets
│   ├── alldecrypt-zip.py        #General decrypt for all zip files
│   ├── json-only-decrypt.py     #Specific decrypt for JSON files
├── config/                      #Directory for configuration files
│   ├── bitwarden-drive-backup-google.json #Configuration for Google Drive
├── scripts/                     #Directory for installation and setup scripts
│   ├── bitwarden-cli-install.py #Script to install the Bitwarden CLI
│   ├── docker-debian.sh         #Setup script for Debian with Docker
│   ├── docker-ubuntu.sh         #Setup script for Ubuntu with Docker
│   ├── setup-debian-env.sh      #Environment setup for Debian
│   ├── setup-ubuntu-env.sh      #Environment setup for Ubuntu
├── backup-drive/
│   ├── (This is where the generated backups will be stored local)
├── .env                         #File for environment variables
├── Dockerfile       #Docker configuration file to create an application image
├── docker-compose.yml           #Docker Compose Configuration
├── entrypoint.sh                #Entrypoint script for Docker
└── requirements.txt  #File that lists the project Python dependencies

```



### <img src="https://raw.githubusercontent.com/querylab/svg/main/snake1.gif" width="30" style="vertical-align: middle;"> Cron Job for Python

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

version: '3.8'

services:
  lazywarden:
    build: .
    container_name: lazywarden_backup
    environment:
      - BW_URL=${BW_URL}
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

- **Important Note:** If you have attachments in your Bitwarden account that are very large (MP4 videos, MP3s, high resolution photos, etc.), the backup process may take some time to complete. The larger the size of the backup file, the longer it will take to upload to the cloud. However, local storage of the backup is much faster.
- Note that if your account contains many attachments, this could significantly influence the total time of the backup process.

### <span style="display: inline-flex; align-items: center;"> <img src="https://user-images.githubusercontent.com/74038190/216122069-5b8169d7-1d8e-4a13-b245-a8e4176c99f8.png" width="30" style="vertical-align: middle; margin-right: 10px;"> Motivations </span>

- I was looking for an automated solution to manage Bitwarden backups without manual intervention or exposure of sensitive data. After trying several complicated and cumbersome tools, I discovered Bitwarden Secret Manager, which keeps secrets within the same platform. With Lazywarden, I automate the management of secrets and backups through Bitwarden to then uploud to Google Drive, Dropbox, pCloud and MEGA, plus integrate notifications with Telegram, Discord, Slack and backup tracking through Todoist. 

- If you like this project, please consider giving it a ⭐

<div style="text-align: center;">
    <img src="https://user-images.githubusercontent.com/74038190/216644507-4f06ea29-bf55-4356-aac0-d42751461a9d.gif" width="150" />
</div>

