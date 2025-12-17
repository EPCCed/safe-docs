# SAFE for EPCC TRE Research Coordinators

This section covers the use of SAFE within the EPCC TRE to:

  - Manage research studies within your Safe Haven
  - Manage users of your Safe Haven

!!!important
    To remain consistent with other usage of SAFE and other parts of this documentation site, SAFE uses terminology which may be different from your internal documentation or from other documentation regarding the EPCC TRE.
    In particular, SAFE, and the rest of this document, uses the term *Project* to represent a Safe Haven, *Group* (or *sub-group*) to represent a research study, and *Machine* to represent resources within your Safe Haven or that it has access to, most commonly one Remote Desktop Gateway (VDI) and one set of desktop VMs.
    Additionally, much functionality listed elsewhere on this documentation site may be currently disabled (or not relevant) within the EPCC TRE SAFE.

## <a name="getting-started"></a>Getting Started

### <a name="login"></a>How to access the EPCC TRE SAFE

After your Safe Haven has been enabled for use with the EPCC TRE SAFE instance, you will be provided with the address to access the service.
This access to the EPCC TRE SAFE is currently only available from within the EPCC TRE itself.
You should access your Safe Haven using your [usual service URL](https://docs.eidf.ac.uk/safe-haven-services/safe-haven-access/) and a [Remote Desktop Session](https://docs.eidf.ac.uk/safe-haven-services/virtual-desktop-connections/#connecting-to-a-remote-desktop-session).
From within the remote desktop session, you can open a browser and enter the address for the EPCC TRE SAFE.
Each research coordinator will be provided with a username and initial password to use to [login to SAFE](safe-for-users#login).

If you have any questions about access, please contact your relevant service desk.

### <a id="andnext"></a>Your first steps.

Here are some of the things you should consider doing (you will be required to do some of them on first login):

- [Change your own SAFE password](safe-for-users#chpass)
- [Turn on MFA (multi-factor authentication)](safe-for-users#2fac)
- [List your own accounts](#selflist)
- [List the groups within your project](#listgroups)
- [List the users within your project and their access](#listusers)

### <a id="selflist"></a>How to list your own accounts

1. [Login to SAFE](#login)
2. Click on the Menu *Login accounts*

You will be shown a list of all your login accounts.
For each research study to which you have direct access, as well as for your research coordinator account, you will usually see two accounts.
These accounts will have the same username but will be on different machines - one for the VDI machine and one for desktop VMs.

### <a id="listgroups"></a>How to list the groups within your project

1. [Login to SAFE](#login)
2. Go to the Menu *Projects* and select the project you wish to view
3. This will display a screen with a variety of options for managing the project
4. Click the small arrow beside *Project Groups* to expand this section

You will be shown a list of all your project groups.
There is always one group which contains all project members, and which has the same name as the project, but additional sub-groups represent each research study.

### <a id="listusers"></a>How to list the users within your project and their access

1. [Login to SAFE](#login)
2. Go to the Menu *Projects* and select the project you wish to view
3. This will display a screen with a variety of options for managing the project
4. Scroll down to *Project accounts* click on *View*

You will be shown a list of all the people in your project.
For each one, the list will include all their accounts, as well as what machine and group they refer to.

You can also list all the people in your project by clicking *View* next to *Project members*.
This will not tell you which machines or groups they have access to (and may include some people who do not have any accounts, e.g. project admins), but can be a more manageable list if you have many users.

You can also view just the accounts in a specific group by selecting the group from the [list of groups](#listgroups) and clicking on *List Members*.

## <a id="managing-groups"></a> Managing Project Groups

### <a id="projgrp"></a> How can I set up project groups within my project?

1. [Login to SAFE](#login)
1. Go to the Menu *Projects* and select the project you wish to view
1. This will display a screen with a variety of options for managing the project
1. Click the small arrow beside *Project Groups* to expand this section
1. Click on the first entry (which will match the project ID)
1. Click *Add new sub-group* at the bottom of the section
1. This will take you to the screen for creating new project groups
1. Fill in a suffix to your project code in the box
1. Click *Create*

This will request the group to be created.
Currently, after creating a new group, you **must** contact your service desk to notify them and discuss which VM the group's users should have access to *before* attempting to add any users to the group.

!!!important
    Requests to create groups (as well as any other requests that interact with the TRE such as creating users or resetting passwords) are completed by automated processes.
    These processes are completed in the background, with SAFE reflecting the results once completed.
    These requests are not instant, and you will have to wait until they are completed, which is variable depending on the type of request and other activity.
    However, they should usually be completed within the order of minutes, and so you should contact your service desk if a request has not completed in the expected time.

## <a id="managing-users"></a> Managing Project Users

### <a id="regusers"></a> How can project users get registered?

!!!important
    You should not add users to a newly-created group until you have confirmed with the service desk that the group has been allocated to a VM.
    If you do, the user will not be able to see any connections when they login to the remote desktop gateway.

1. [Login to SAFE](#login)
1. Go to the Menu *Projects* and select the project you wish to view
1. This will display a screen with a variety of options for managing the project
1. Click *Create accounts* (within the *Manage members* section)
1. This will take you to the screen for creating new accounts for a user
1. In most cases, your Safe Haven will have access to one remote desktop gateway (VDI) and one set of desktop VMs, and these will be displayed in the row labelled *Machines*. If your Safe Haven has access to additional VDIs/VMs, you should check the boxes to select exactly one VDI and one set of VMs.
1. Choose the group you want the account to belong to in the drop-down labelled *Group*
1. Enter the email address of the person to whom the account will belong in the text box labelled *Email*
1. Enter the planned expiry date of the account in the text box labelled *ExpiryDate*
1. Click *Next*
1. Enter the user's name into the text fields (title & initials are optional). If the email address you entered in the previous step has already been associated with an account in the EPCC TRE SAFE, details will be presented to you and you will not be able to change them. If these details do not match what you were expecting, you should query this with the user and/or service desk.
1. Click *Next*
1. You will be shown the planned username for the user, although you should note that this is not confirmed until the account is created
1. If your Safe Haven has one or more webproxies available, select whether you wish the user to have access to one in the drop-down labelled *Webproxy*
1. Click *Create*

You will be shown a page which contains links to two accounts (one for the VMs and one for the VDI).
These accounts have now been requested to be created.
Clicking on each link will take you to a page showing more details about the account.
In particular, the *Status* row will show you that the account is *Pending*.
When the account has been created, this will change to *Active* (you will need to refresh the page to see any changes).

Once the account is *Active*, you can view the initial password for the account by clicking *View Login Account Password*.
You should supply this password to the user using your normal processes.
Remember that you need to provide the user with passwords for both accounts.
Note that this screen is only ever intended to show you the initial password - when the user changes the password (as they will be forced to upon first login) this change will not be visible to the SAFE, and only the user will know the new password.

### <a id="resetpwd"></a> How can I reset the password for an account

1. [Login to SAFE](#login)
1. [List the users for your Safe Haven](#listusers)
1. Find the account for which you wish to reset the password. Ensure that you select the account for the correct research study, and the correct type of account (VM or VDI)
1. Click *Request Password Reset*
1. Click *Yes*

This will request a new password to be set for the account.
Once the password reset has been completed, you will be able to view and supply the password to the user in the same manner as for [new users](#regusers).

## <a id="track-usage"></a> Tracking your Project Usage

### <a id="autorep"></a> How to request automatic project reports

SAFE can be configured to send automatic reports.
Currently, the EPCC TRE SAFE can send a report listing the project managers for each project.

1. [Login to SAFE](#login)
1. Go to the Menu *Projects* and select the project you wish to work on. This will display a screen with a variety of options for managing the project.
1. Click on *Update*
1. Enter the email addresses which the reports should be sent to in *Recipients for automatic reports.*
1. Set the *Frequency of Automatic Reports* to the preferred frequency.
1. Click *Update* to confirm the changes.

