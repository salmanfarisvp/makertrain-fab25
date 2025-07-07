---
sidebar_position: 1
---

# 🛠️ Install Tools

Follow the guide to install the necessary tools for the workshop.

[![Part 1 Poster](/img/install-tools/part-1-poster.png)](https://www.hackster.io/Salmanfarisvp/1-makertrain-pre-departure-checklist-nrf-sdk-setup-e37098)

By Following this [hackster guide](https://www.hackster.io/Salmanfarisvp/1-makertrain-pre-departure-checklist-nrf-sdk-setup-e37098), or below steps , please install necessary tools for the workshop.

###  Step 1. Install SEGGER J-Link v8.18
Download the installer for your platform from [SEGGER J-Link Software](https://www.segger.com/downloads/jlink/#J-LinkSoftwareAndDocumentationPack). Run the installer; when you reach the ‘Choose Optional Components’ window during installation, be sure to select ‘Install Legacy USB Driver for J-Link’ This driver is necessary for some supported Development Kits.

---

### Step 2. Install nrfutil and the nrfutil device command
Download the binary compatible with your OS from the [nRF Util product page](https://www.nordicsemi.com/Products/Development-tools/nRF-Util/Download?lang=en#infotabs) and store it somewhere on your disk drive

**For windows:** `C:\nordic_tools\nrfutil.exe` and then

:::note

(Windows) Update your system’s **PATH** to include the location where **nrfutil** is stored. Open Edit environment variable for your account and add the path where you stored the **nrfutil binary**, as shown below:

:::

![Edit environment variable for your account](https://hackster.imgix.net/uploads/attachments/1853002/update_path_fIz9C3BmAJ.gif)

**For macOS or Linux:** You can store it in a folder that is already added in the system’s **PATH**.

The `nrfutil` binary you just downloaded does not come with any pre-installed commands. In this step, we will upgrade the core `nrfutil` and download the `device` command.

To make sure we have the latest `nrfutil` version, run the following command in a terminal (Command Prompt or PowerShell). It doesn’t matter which terminal since `nrfutil` is set globally.

```bash
nrfutil self-upgrade
```

and then run below command to install the device so we can flash binaries later.

```bash
nrfutil install device
```

You should see the following output :

```bash
[00:00:02] ###### 100% [Install packages] Install packages
```

---

### Step 3. Install VS Code.

Download and install VS Code from [here](https://code.visualstudio.com/download).

---

### Step 4. Install nRF Connect Extension Pack.

Install the nRF Connect Extension Pack for VS Code from the [Marketplace](https://marketplace.visualstudio.com/items?itemName=nordic-semiconductor.nrf-connect-extension-pack).

In the **Activity Bar**, click the **Extensions** icon, then type **nRF Connect for VS Code Extension Pack** in the search field, and click on **Install**, as shown in the illustration below:

![Install nRF Connect Extension Pack](https://hackster.imgix.net/uploads/attachments/1853005/image_dle5v2oBzg.png)

nRF Connect for VS Code extension pack consists of the following components:

- **nRF Connect for VS Code**: The main extension contains an interface to the build system and nRF Connect SDK. It also provides an interface to manage nRF Connect SDK versions and toolchains.
- **nRF DeviceTree**: Provides Devicetree language support and the Devicetree Visual Editor.
- **nRF Kconfig**: Provides Kconfig language support.
- **nRF Terminal**: A serial and RTT terminal.
- **C/C++ from Microsoft**: Adds language support for C/C++, including features such as IntelliSense.
- **CMake**: CMake language support.
- **GNU Linker Map Files**: Linker map files support.

---

### Step 5. Install Toolchain.

The toolchain is a set of tools that are used together to build nRF Connect SDK applications. It includes the assembler, compiler, linker, and CMake, among other tools.

Open the **nRF Connect** and choose the **manage toolchains**

![Manage toolchains](https://hackster.imgix.net/uploads/attachments/1853006/image_xOvy51jd8q.png)

then click the latest one, the toolchain will start download. If possible download the 2.9.0 also we need that for different example.

![Download toolchain](https://hackster.imgix.net/uploads/attachments/1853007/image_nsosyp1slN.png)

---

### Step 6. Install nRF Connect SDK.

In nRF Connect for VS Code, click on **Manage SDKs**. Through the **Manage SDKs** menu, we can install, uninstall nRF Connect SDK versions.

Click on **Install SDK**.

![Install SDK](https://hackster.imgix.net/uploads/attachments/1853009/image_NjbRZDUqlN.png)

It will list the available versions of the nRF Connect SDK that can be downloaded and installed on your machine. Choose the nRF Connect **SDK v3.0.0** for now.If possible download the **2.9.0** also we need that for different example.

![Install SDK](https://hackster.imgix.net/uploads/attachments/1853010/image_y7yF2sOGYk.png)

---

### Step 7: Install nRF Connect for Desktop

![Install nRF Connect for Desktop](https://hackster.imgix.net/uploads/attachments/1854504/image_8bSU7qDIHr.png?auto=compress%2Cformat&w=740&h=555&fit=max)

nRF Connect for Desktop is designed to be used with our development kits and dongles. The apps will detect which kit you connected to your computer and upload the needed firmware. The kits supported by each app are listed in the documentation.

Download your proffered version from [here](https://www.nordicsemi.com/Products/Development-tools/nRF-Connect-for-Desktop/Download#infotabs) Choose platform and version and then install it.

#### Step 7.1 Install nRF Programmer and Serial Terminal.

We will use these Programmer and Serial Terminal throughout our final project building. Please click install and install in your computer. You can also install other tools, later at the time of workshop you can try it out.

![Install nRF Programmer and Serial Terminal](https://hackster.imgix.net/uploads/attachments/1854505/image_7U4SuGdjuG.png)

**Programmer :** The Programmer app lets you program Nordic SoCs. You can drag and drop your files and read, write or erase the device.

**Serial Terminal :** This is a terminal emulator that can be used alongside other nRF Connect for Desktop applications as it allows COM Port sharing.

---

### With this, we have completed the installation of nRF Connect SDK and VS Code. Ready to start your MakerTrain journey 🎉

Double check you have installed all the tools and you are ready to start your MakerTrain journey 🎉

- [ ] SEGGER J-Link Software
- [ ] Dowbload and add `nrfutil` to your PATH
- [ ] Install VS Code.
- [ ] Install nRF Connect Extension Pack For VS Code.
- [ ] Install nRF Toolchain.
- [ ] Install nRF Connect SDK.
- [ ] Install nRF Programmer.

---

### Hackster Guide
-  **[MakerTrain: Pre-Departure Checklist - nRF SDK Setup](https://www.hackster.io/Salmanfarisvp/1-makertrain-pre-departure-checklist-nrf-sdk-setup-e37098)** by [Salman Faris](https://www.hackster.io/Salmanfarisvp)













