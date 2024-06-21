---
layout: default
title: Getting Started
nav_order: 2
---

# Getting Started
{: .no_toc }

A SaaS modular web app to manage users and content (e.g., Revit Families), complemented by a powerful Revit content browser plugin.
Not permitted:
-	Sell/resell
-	make modifications to the software.

## Main Modules

- User Management System
- Content Management System

Both modules provide seamless integration with Autodesk Revit.

{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Access the Web Application & Revit Plugin

### On-premises Deployments

- To access the web application use the URL provided to you by your account manager (e.g., your-company-name.dikeeper.com).
- To download the Revit plugin use the URL provided to you by your account manager.

### Other Deployments

- Coming Soon.

## Revit Content Browser Plugin Installation 

### Compatibility

- Windows 7, 8, 10 and 11.
- Revit 2018, 2019, 2020, 2021, 2022, 2023, 2024, and 2025.

### First web application access

1. First of all, make sure you have created your DiKeeper account. Ask your manager to send you an invitation to register on DiKeeper.
You will receive an invitation by email, and you should click on "Join Now" and then will be directed to the registration page.

![DiKeeper Invitation](..\assets\images\GIFs\GettingStarted\DK-Invitation.png)

2. Enter your e-mail address and click on "Send verification code", then access the e-mail to obtain the verification code to check your e-mail account.

![DiKeeper verification code](..\assets\images\GIFs\GettingStarted\DK-Code.png)

3. Fill all personal information fields and click on “Create” button to conclude.

![DiKeeper personal informartion](..\assets\images\GIFs\GettingStarted\DK-UserInformation.png)

---

### Standard Revit Plugin Installation

```yaml
This method is ideal for individuals who want to install DiKeeper in one computer.
```

1. Run DiKeeper installer.

2. Select the Revit versions and click 'Install'.

3. Wait for the installation to complete and click 'Finish'.

![DiKeeper Installation First Step](..\assets\images\GIFs\GettingStarted\DK-Install.gif)

### Silent Installation

```yaml
This method is ideal for IT administrators who want to deploy DiKeeper to multiple computers.
```

- Install for all compatible Revit versions.

```yaml
# This method will silently install DiKeeper for all compatible Revit versions.
<installer-name>.exe /i // /qn accept_eula=1
```

- Exclude specific Revit versions.

```yaml
# In this example DiKeeper will NOT be installed for Revit 2017, 2018, and 2019.
<installer-name>.exe /i // /qn accept_eula=1 revit2017="" revit2018="" revit2019=""
```

## Uninstall

### Using the installer User Interface

1. Run DiKeeper installer.

2. Select and click 'Remove'.

![DiKeeper Uninstall](..\assets\images\GIFs\GettingStarted\DK-RemovePlugin.gif)

3 . Wait for the uninstallation to complete and click 'Finish'.

### Using the installer silently

Uninstall DiKeeper without user interaction.

```yaml
# This method will remove DiKeeper from your computer.
<installer-name>.exe /x // /qn
```

### From the control panel

1. In the search box on the taskbar, type Control Panel and select it from the results.

2. Select Programs > Programs and Features.

3. Press and hold (or right-click) on the program you want to remove and select Uninstall or Uninstall/Change. Then follow the directions on the screen.

## Updates

DiKeeper includes an updater to help you keep it up to date. 
The updater will:

- notify you whenever a new version is released (the action is triggered on Revit close event).
- ask you to install now or to remind you tomorrow.