# INFORMATION ASSURANCE - FINAL PROJECT
**BSCS 3B**
- Sayson, Nestor Jr. B.
- Tagum, Mark B.
- Salvino, Vincent James O.
- Vela, Angelica P.

##  Step-By-Step Documentation

### 1. Prepare and Install Headless Raspbian OS in Raspberry Pi

#### Step 1: Reformat the SD Card
Insert the SD card into your computer and reformat it using a tool like SD Card Formatter.

#### Step 2: Download Raspbian OS
Visit the official Raspberry Pi website and download the latest Raspbian OS image.

#### Step 3:  Install Raspbian OS on SD Card

#### Step 4: Configure
Change the Username and Password and Connect to Wi-Fi and Make sure to enable the ssh

#### Step 5: Insert SD Card
Insert the SD card into the Raspberry Pi and power it up.

### 2. Connecting to Raspberry Pi via SSH using the terminal

#### Step 1: Find Raspberry Pi IP
Connect the Raspberry Pi in monitor to check your Raspberry Pi IP in and type in command prompt ifconfig and get the inet. 

#### Step 2: Open Terminal
Open the terminal on your computer.

#### Step 3: SSH Connection
Use the following command to connect to the Raspberry Pi:
```bash
ssh username@<RaspberryPiIP>
```
Enter your password when prompted.

### 3. Deploying LAMP Stack in Raspberry Pi

#### Step 1: Update and Upgrade
Run the following commands to update and upgrade the Raspberry Pi:
```bash
sudo apt update
```
```bash
sudo apt upgrade
```
#### Step 2: Install LAMP Components
Install Apache, MySQL, and PHP using:
```bash
sudo apt install apache2 
```
```bash
sudo apt install mariadb-server
```

#### Step 3: Secure MySQL
Run the MySQL secure installation script to enhance security.
```bash
sudo mysql_secure_installation
```
```bash
sudo apt install php libapache2-mod-php php-mysql
```
```bash
sudo apt-get install php*
```
```bash
sudo apt install phpmyadmin
```

### 4. Enabling and Controlling Raspberry Pi using VNC

#### Step 1: Enable VNC
Run the following command to enable VNC:
```bash
sudo raspi-config
```
Navigate to 'Interface Options' > 'VNC' and enable it.

#### Step 2: Download and Install VNC Viewer
On your computer, visit the official RealVNC website: [RealVNC Download](https://www.realvnc.com/en/connect/download/viewer/)

#### Step 3: Connect via VNC Viewer
Connect to the Raspberry Pi using its IP address.

#### Step 4: Control Raspberry Pi
You can now control the Raspberry Pi desktop using VNC Viewer.
