# 🔐NetworkWalks-Victor-B084-Cybersecurity-week1- Virtual Lab-setup Using Kali Linux & VirtualBox


## 📌 Project Overview

As part of my practical cybersecurity learning journey, I created a virtual cybersecurity lab using **Oracle VirtualBox** and **Kali Linux**.

The purpose of this project is to create a safe and controlled environment where I can practise Linux, networking, cybersecurity tools, and other security-related exercises without affecting my main Windows operating system.

This project also helped me understand how virtualization works and how a virtual machine can run another operating system inside a host computer.

---

## 🎯 Project Objectives

The objectives of this project were to:

- Install and configure Oracle VirtualBox
- Set up Kali Linux as a Virtual Machine (VM)
- Understand the difference between a host machine and a virtual machine
- Configure the VM's basic system resources
- Test Kali Linux inside the virtual environment
- Practise basic Linux commands
- Create a safe environment for future cybersecurity labs
- Document my practical work using screenshots

---

## 🧰 Tools Used

| Tool | Purpose |
|------|---------|
| Windows | Host operating system |
| Oracle VirtualBox | Virtualization platform |
| Kali Linux | Cybersecurity/Linux virtual machine |
| Linux Terminal | Running Linux commands and administrative tasks |

---

## 🖥️ Lab Architecture

My current lab setup is:

    Windows Host Machine
            |
            |
      Oracle VirtualBox
            |
            |
       Kali Linux VM
            |
            |
    Cybersecurity Practice

The Windows computer acts as the **host machine**.

VirtualBox provides the virtualization environment that allows me to create and manage virtual machines.

Kali Linux runs as a **guest operating system (VM)** inside VirtualBox.

---

## ⚙️ Setup Process

### Step 1: Install VirtualBox

I installed **Oracle VirtualBox** on my Windows computer.

VirtualBox acts as the hypervisor that allows me to create and run virtual machines on my physical computer.

![Oracle VirtualBox](https://github.com/ProffV/NetworkWalks-Victor-B084-Cybersecurity-week1-Lab-setup/blob/main/Screenshot%202026-10-27%20135326.png)

### Step 2: Set Up Kali Linux

I downloaded Kali Linux and configured it to run inside VirtualBox.

This created a separate virtual environment where I can practise cybersecurity without replacing my Windows operating system.

### Step 3: Allocate VM Resources

I allocated part of my computer's hardware resources to the Kali Linux virtual machine.

These resources include:

- RAM
- CPU
- Storage
- Network connectivity

This helped me understand that every VM uses resources from the physical host computer.

---

### Step 4: Start Kali Linux

After completing the configuration, I successfully started Kali Linux inside VirtualBox.

Kali Linux now operates as a virtual machine while Windows remains the host operating system.

---

## 🐧 Testing the Kali Linux Terminal

After setting up the VM, I used the Kali Linux terminal to practise basic Linux commands.

Some examples include:

```bash
pwd
```

Displays my current working directory.

```bash
ls
```

Lists files and directories.

```bash
whoami
```

Displays the currently logged-in user.

```bash
ip a
```

Displays network interface and IP address information.

```bash
sudo apt update
```

Updates Kali's local package information from configured software repositories.

---

## 📸 Project Evidence

Screenshots were taken during the lab setup to document my work.

### Kali Linux Running in VirtualBox

![Kali Linux Virtual Machine](https://github.com/ProffV/NetworkWalks-Victor-B084-Cybersecurity-week1-Lab-setup/blob/main/VirtualBox_kali-linux-2026.2-virtualbox-amd64_27_10_2026_14_52_16.png)

### Kali Linux Terminal

![Kali Linux Terminal](https://github.com/ProffV/NetworkWalks-Victor-B084-Cybersecurity-week1-Lab-setup/blob/main/VirtualBox_kali-linux-2026.2-virtualbox-amd64_27_10_2026_17_15_22.png)

### Network Configuration

![Kali Network Configuration](screenshots/kali-network.png)

## 💡 What I Learned

This practical project helped me understand several important concepts.

### 1. Virtualization

I learned that virtualization allows one physical computer to run multiple virtual computers using software such as VirtualBox.

### 2. Host vs Guest Operating System

My Windows operating system is the **host OS**, while Kali Linux running inside VirtualBox is the **guest OS**.

### 3. Virtual Machines

I learned that a virtual machine behaves like a separate computer but uses CPU, RAM, storage, and other resources provided by the physical host computer.

### 4. Kali Linux

I gained practical experience using Kali Linux and its terminal environment.

### 5. Linux Commands

I practised basic Linux commands and started becoming more comfortable working from the command line.

### 6. Cybersecurity Lab Environment

I now have a dedicated virtual environment that I can continue building and using for future cybersecurity projects.

---

## 🚀 Next Steps

I plan to continue developing this lab by learning and practising:

- Linux administration
- Networking
- SSH
- Network scanning
- Wireshark
- Nmap
- Incident response
- Digital forensics
- Vulnerability assessment
- Other cybersecurity tools and techniques

Additional virtual machines may also be added as I progress in my cybersecurity learning.

---

## ⚠️ Ethical Use Disclaimer

This cybersecurity lab is created strictly for **educational purposes and authorized security testing**.

Any cybersecurity tools or techniques demonstrated in this lab should only be used on systems, networks, and devices that I own or have explicit permission to test.

---

## 📚 Resources

- [Kali Linux](https://www.kali.org/)
- [Oracle VirtualBox](https://www.virtualbox.org/)

---

## 👤 Author

**Victor Kadiri**

Electrical & Electronics Engineer | Cybersecurity Learner

---

## 📌 Project Status

🟢 **Active — More cybersecurity labs and practical exercises will be added as I continue learning.**
