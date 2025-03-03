# Vagrant IaC Profiles  

A collection of Vagrant Infrastructure as Code (IaC) profiles for setting up various development and testing environments with provisioning scripts.  

## 📂 Available Profiles  

- **mini_finance** - Deploys a finance-related website on a CentOS-based Vagrant box with Apache.  
- **wordpress** - Deploys a WordPress site on an Ubuntu-based Vagrant box with Apache, MySQL, and PHP.  

## 🚀 Getting Started  

### 1️⃣ Clone the Repository  

```bash
git clone https://github.com/Flack74/vagrant-iac-profiles.git
cd vagrant-iac-profiles
```

### 2️⃣ Navigate to the Desired Profile  

```bash
cd wordpress  # Or cd mini_finance
```

### 3️⃣ Start the Vagrant Environment  

```bash
vagrant up
```

### 4️⃣ Access the Web Application  

Once provisioning is complete, open your browser and visit:  

```
http://192.168.56.28  # mini_finance
http://192.168.56.30  # wordpress
```

## 📌 Requirements  

- **Vagrant** (Download: [https://www.vagrantup.com/downloads](https://www.vagrantup.com/downloads))  
- **VirtualBox** (Download: [https://www.virtualbox.org/wiki/Downloads](https://www.virtualbox.org/wiki/Downloads))  

## 🔄 Managing the Vagrant Machine  

- **Stop the VM**:  
  ```bash
  vagrant halt
  ```
- **Destroy the VM** (removes all data):  
  ```bash
  vagrant destroy
  ```
- **Rebuild the VM**:  
  ```bash
  vagrant up --provision
  ```

## 🛠 Contributing  

Feel free to submit pull requests or open issues if you have suggestions!  
