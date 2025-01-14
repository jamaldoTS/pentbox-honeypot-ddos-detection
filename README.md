# pentbox-honeypot-ddos-detection
PentBox honeypot project for detecting DDoS attacks, including Slowloris testing.
# PentBox Honeypot for DDoS Detection (Slowloris Test)

This project sets up a **PentBox honeypot** designed to detect **DDoS attacks**, specifically **Slowloris attacks**. The honeypot logs incoming malicious traffic, and the project includes testing with the **Python-based Slowloris** attack script.

## 📦 Features
- 🛡️ **PentBox 1.8** for TCP/UDP honeypot detection  
- 🐍 **Python Slowloris Script** for DDoS testing  
- 📊 **Real-Time Logging** of suspicious traffic  

---

## 🚀 Setup Instructions

### *Step 1: Clone the Repository*

git clone https://github.com/jamaldoTS/pentbox-honeypot-ddos-detection.git

cd pentbox-honeypot-ddos-detection

### *Step 2: Download and Extract PentBox*

Use wget to download PentBox 1.8:
wget http://downloads.sourceforge.net/project/pentbox18realised/pentbox-1.8.tar.gz

Extract the downloaded file:
tar -zxvf pentbox-1.8.tar.gz

### *Step 3: Navigate to PentBox Directory*

Move into the pentbox-1.8 directory:
cd pentbox-1.8/

### *Step 4: Run PentBox Honeypot*

Run the honeypot with the following command:
./pentbox.rb

This command will start the PentBox honeypot, which will begin monitoring for incoming TCP/UDP traffic and logging any suspicious activity.

--------------------------------------------------------------------------------------------------------------------------

## 🎯 Simulating a DDoS (Slowloris Test)

## *Step 1: Clone the Slowloris Script*

Clone the Slowloris attack script repository:
git clone https://github.com/gkbrk/slowloris.git

cd slowloris

## *Step 2: Run the Slowloris Attack (Simulated Traffic)*

Run the Slowloris attack script with the following command (replace <your-ip-address> with your actual IP address):
## *python3 slowloris.py your-ip-address -s 500*
The -s 500 option sends 500 sockets to simulate a DDoS attack. You can adjust the number based on the severity you want to test.


--------------------------------------------------------------------------------------------------------------------------

## 📬 Contributing

## ⭐ Star the repo to show your support

## 🍴 Fork the repository and submit pull requests with improvements

## 💬 Feel free to share feedback or suggestions 

-------------------------------------------------------------------------------------------------------------------------

## 📄 License

This project is licensed under the MIT License. You can freely use, modify, and distribute this code as long as you follow the terms of the license.

--------------------------------------------------------------------------------------------------------------------------
## 📢 Disclaimer

This project is for educational purposes only. Please ensure that you have the proper authorization before using this honeypot in a real-world environment. Ethical hacking requires permission from the network owner.

--------------------------------------------------------------------------------------------------------------------------
