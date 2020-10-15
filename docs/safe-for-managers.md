# SAFE for PIs and Project Managers

This section covers the use of SAFE to:

  - Manage project users on different systems and services
  - Manage project resources on different systems and services
 


Principal Investigators (grant holders) can manage their allocations efficiently via [SAFE](https://safe.epcc.ed.ac.uk)

<!--

### [Getting started](#getting-started)


- [How to activate your new allocation](#activate)
- [Your allocation has been set up as a project on 	the service. Your first steps.](#andnext)
- [How to get your own account on the service machine](#selfac)
- [How to check project alerts](#projalert)


### [Managing your allocated resources](#managing-resources)

<ul>
	<li><a href="#period">What is "period allocation"?</a></li>
	<li><a href="#projgrp">How to set up project groups within the project</a></li>
	<li><a href="#projgrp">How to set up a guest budget</a></li>	
	<li><a href="#delgrp">How to delete a project group</a></li>
	<li><a href="#time">How can I administer time within my project?</a></li>
	<li><a href="#mvtime">How to move time between budgets</a></li>
	<li><a href="#oneuser">How to allocate time to individual user</a></li>
	<li><a href="#space">How to administer disk space</a></li>
	<li><a href="#mvspace">How to create a quota for a project group, or
			move space between quotas</a></li>
	<li><a href="#persquota">How to set a quota for an individual user</a></li>
</ul>


<h3>
	<a href="#managing-users">Managing project users</a>
</h3>
<ul>
	<li><a href="#regusers">How can project users get registered</a></li>
	<li><a href="#approve">How to approve user sign up requests</a></li>
	<li><a href="#signup">How to track user sign up requests</a></li>
	<li><a href="#projman">How to designate a user as a project manager</a></li>
	<li><a href="#groupman">How to designate a user as a project sub-group
			manager</a></li>
	<li><a href="#addu">How to add a user to a project group</a></li>
	<li><a href="#remu">How to remove a user from a project group</a></li>

	<li><a href="#remuser">How to remove a user (or users) from your
			project</a></li>
	<li><a href="#projmailing">How to send a mailing to all users in your
			project</a></li>
</ul>


<h3>
	<a href="#track-usage">Tracking your project usage</a>
</h3>
<ul>
	<li><a href="#snap">How to check the current state of your project's
			time and space</a></li>
	<li><a href="#phist">How to track what my project's users and project
			groups are doing?</a></li>
	<li><a href="#udisk">How to check how much space my project's users are
			occupying</a></li>
	<li><a href="#autorep">How to request automatic project reports</a></li>
	<li><a href="#more">How to request more resources (time and disk space)</a></li>
</ul>


<br />
<hr />


-->


## <a name="getting-started"></a>Getting Started

### <a name="activate"></a>How to activate your new allocation


After your application for access to ARCHER2 has been approved by the relevant funding body, your new allocation will need to be activated. This can be 	done by sending an email to [ARCHER2 Service desk](mailto:support@archer2.ac.uk). Please quote your grant reference number, the start and 	the end date of the grant, and the name of the PI.

The details will be checked and your new allocation will be set up on the service machine. If your new allocation is a follow-on to your existing  project, you can request for it to be set up as a new [period allocation](#period) under the same project. Alternatively you can request for it to be set up as a new project. Once the project is set up, the PI will receive an email with all the project details.



### <a id="andnext"></a>Your allocation has been set up as a project on the service. Your first steps.

Here are some of the things you should consider doing; not all of 	them will be needed for every project.


-  [Change your own SAFE password](../safe-for-users#chpass)
-  [Set up an account on the service machine for yourself](#selfac)
-  [Make sure other project users get registered](#regusers)
-  [Designate one or more users as managers of your project](#projman)
-  [Decide whether you need project groups within your project, in order to administer time and other resources](#projgrp)



### <a id="selfac"></a>How to get your own account on the service machine

If you are not going to work on the machine yourself, you do not need to do this. You can administer your project through SAFE alone. But if you want a service machine account:

- Go to the Menu *Login accounts* and select *Request login account* 
- Choose the project you want the account for in the "Project" box. 
- Click "Next"
- Select the machine you want the account for from the available machines. 
- Click "Next"
- Enter the username you would prefer to use on the service machine 

- Click "Request"
	

You will get an acknowledgement screen, from which you can return to your main page. 
Now (as PI) you have to [approve your own request](#approve) for an account.



### <a id="projalert"></a>How to check project alerts

[Login to SAFE](../safe-for-users#login)</a>. Then:

		
- Go to the Menu *Projects* and select the *project* you wish to check

!!! note
    if there are account approvals waiting, the project name will be highlighted in this list and clicking on the highlight will take you straight to that [Project Notifications](#signup) page.


- This will display a page with a variety of options for managing your project.
- Project alerts and warning are highlighted in Amber and Red
- To request emails for alerts, or to change the frequency of the emails
- Click *Update*
- Beside "Frequency of Alerts" select the required frequency
- If the emails should go to someone other than the PI, enter the email address(es) into the 'Recipients for alerts' box. If the PI still wishes to receive alerts their email must be included in this box.
- Click *Update* to save the changes.


Do not forget the *Update* step, or nothing will happen.



## <a id="managing-resources"></a> Managing your allocated resources

### <a id="period"></a> What is "period allocation"

A period allocation is an amount of compute time which has been allocated for a project to use within the specified time period. Period allocations are valid for a specific resource pool (machine) and have definitive start and end dates, which usually coincide with the dates of your EPSRC grant or project award. When the end date of the period allocation passes, any leftover compute time will automatically expire.

You can view and manage your period allocation via SAFE.

[Login to SAFE](../safe-for-users#login). Then:

- Go to the Menu *Projects* and select the *project* you wish to work with 
- This will display a screen with a variety of options for managing the project.
- Scroll down to Time Budgets and Click on *Manage Group Time Allocations*
- Click on the small arrow beside *How to Manage Your Budgets* for detailed instructions.


You will then see the details of your current live allocation.

!!! Important
    Please check the dates by *Allocation Period* to make sure you are looking at the correct one.

    You can skip between the period allocations by clicking on the "Next period>>>"  and "<<< Previous period"  buttons at the bottom of the page.

1. **Resource Pool (machine)**. "XC" refers to ARCHER.
1. **Allocation**
1. **Dates** It is possible to have multiple successive period allocations, but they can never overlap if they are for the same resource pool. Before carrying out any project management tasks please check the dates and make sure you are managing the correct allocation.
You can skip between the period allocations by clicking on the "Next period>>>" and "<<< Previous period"  buttons at the bottom of the page.


You can manage the allocation by [setting up project groups](#projgrp) and [allocating compute time to project groups]("#mvtime).
Project management tasks for the period allocation can be carried out at any time, but the allocation will be active, i.e. usable, only between the specified dates. Thus, you can set up project groups in advance.


### <a id="projgrp"></a> How can I set up project groups within my project?

Project groups can be used to administer time and other resources within your project.
	
[Login to SAFE](../safe-for-users#login) Then:


1. Go to the Menu *Projects* and select the *project* you wish to create the group

1. This will display a screen with a variety of options for managing the project.
1. Click the small arrow beside *Project Groups* to expand this section
1. Click on the first entry (which will match the project ID)
1. Click *Add new sub-group* at the bottom of the section
1. This will take you to the screen for creating new project groups.
Fill in a suffix to your project code in the box: for example, if your project code is t01, you might chose t01-a. Project group names cannot
be more than eight characters in total.
		

1. <a id="guestbudget"></a>If this group is to be used for <strong>guest budget</strong> users, tick "Guest 	Budget"</br>		
A *guest budget* is a budget in one project which is set up to permit access requests from users in a different project.</li>

1. Click *Create*


### <a id="delgrp"></a>How can I delete a project group?

You can only delete a project group if it has no resources or members.
You must remove all its [members](#remu) and all its [time](#mvtime). Also, if it has [disk quotas
set](#space), it cannot be deleted; they will have to be removed first.

Then:
				
1. Go to the Menu *Projects* and select the *project* you wish to delete the sub-group from.	
1. Scroll down to project groups and click on the small arrow beside Project Groups to expand and display all the groups in the project.
1. Select the project sub-group you want to delete.
1. Scroll to the bottom of the page and click *Delete*. This will ask for  confirmation that you wish to delete the sub-group. Click *Yes*.



Deleting a group involves removing its various directories. A human has to do this, so there will be a short delay.


### <a id="time"></a>How can I administer time within my project?

Compute Time is held in *budgets*. Every project group has its own budget. There are always at least two project groups 	in your project:

- The *general group*, which has the same code as the project itself. Every member of the project is a member of this group, so the time in its budget is available to them all.

- The *reserve* project group, which has a name of form *t01-reserve*.
It has no members, so no one can use the time in its budget. This budget can be used to hold time which the PI or project manager wishes to hold in reserve for later use.



Initially, all your time is in the general group's budget. If you are  happy with all your users using the same budget, you can leave things as they are.

If you wish to divide the time up between groups, you can [create a project group](#projgrp) for each group. In this case you will probably want to move all the time out the general group, since this can be used by everyone. 


You may wish to [give time just to a single user](#oneuser).
This is a special case of a project group: one with only one member.


The reserve budget is provided so that if you wish you can control
the use of time by your project members: you can keep most of the time
in your reserve budget, and move it to the other budgets as required.
We recommend that you should do this, even if you don't need to create
other project groups.


### <a id="mvtime"></a> How can I move time between budgets?


[Login to SAFE](../safe-for-users#login), and then:


1. Go to the Menu *Projects* and select the *project* you wish to work with. This displays a panel with information for the project.

1. Scroll down to *Time Budgets*
1. Click *Manage Group Time Allocations*
1. Click the small arrow beside "How to Manage your Budgets" to expand the instructions.
1. Click the *Move From* and *Move To* buttons of the project groups you want to change
1. Enter the amount of compute time you wish to move in the box
1. Click the *Move* button
1. Click the *Submit Budget Allocation Changes* button.

Do not forget the Submit step, or nothing will happen.


### <a id="oneuser"></a> How can I allocate time to a single user?

As all the time in a project group is shared by all its members, the only way to reserve some time for a single user is to create a project group for that user alone.


1. [Create a new project group](#projgrp) for the user. For example, if we are in project *t01* and the user is *fred*, you might call the new project group *t01-fred*
1. [Add the user to the new project group](#addu)
1. [Move the time](#mvtime) you wish the user to have into the new project group

Remember that time in the general group's budget is accessible to all, so you will probably want to move all of the project's time away from there.


### <a id="space"></a> How can I administer disk space?

Start by reading the discussion of the [administration of time](#time), as the administration of disk space is related to this, and is also done using project groups. The two project groups which 	exist in each project can also be used for administering space.

- The *general group*, which has the same code as the project itself, includes every member of the project. The disk quotas of this project group can therefore be used by them all.
- The *reserve* project group, which has a name of form *t01-reserve*, has no members, so no one can use the disk space which is in its quotas. You can use these quotas to hold space which you want to hold in reserve for later.

Homespace and workspace are administered separately. A project has an overall limit for each of these. Within that limit, every portion of space must belong to one or other of the project group quotas. Thus, to 	start with, all the homespace (for example) allocated to a project is either in the general homespace quota or the reserve homespace quota.
Space never belongs to more than one group quota. [The reserve quota is not a real quota, in fact. It has no existence on the service machine - just in the database.]

Beyond the general and reserve quotas, you can also have quotas for the project groups which you create. But this is not compulsory. If you're thinking about using project group quotas, you need to be aware that they are implemented using Unix groups, which are only just adequate for the task.

Let's use homespace as an example &mdash; workspace is similar. Suppose you are project *t01*. To start with, one Unix group will be assigned to this project. The homespace directories for all users will be in directory `/home/t01/t01/` &mdash; this is where the general group is held. User *john*, for example, will have directory `/home/t01/t01/john/` as his homespace directory. (In fact, if this is the first project he joined, that's where he will log in.) Any file created in any of the directories under `/home/t01/t01/` will belong to the Unix group for project *t01*.


If you create a project group *t01-a* with no homespace quota, this will not change. But the moment you give a homespace quota to this project group, a Unix group will be assigned to it and a directory will be created for it: `/home/t01/t01-a/`
If user *john* is a member of this project group, he will have a directory `/home/t01/t01-a/john/`.  Any files he creates under that directory will belong to *t01-a* and will be counted against its quota.


Of course, *john* is still a member of the general project group, so he can still create files there. If he belongs to other project groups which have quotas, he'll have directories for these as well. He can only create files in the project groups he is a member of, since he can't access the directories of the other groups. It's up to him to make sure that he creates his files in the right places, so that they get charged to the right project groups.


<!--
<p>That's the theory, but unfortunately there are ways for users to get round this system (by mistake and on purpose), and there's nothing we can do about this, apart from changing the group IDs of files when we notice it happening.  We are at the limit of what the operating
system's technology can do.</p>
-->

You should also note that once you have instituted project group quotas, there's no easy way back. Removing them and reassigning all the files to other groups is a complex job and will require special arrangement with the system team &mdash; send a request to the [Service desk](mailto:support@archer2.ac.uk) if you need to do this.


Most projects in fact use their project groups only for administering time, and allow their users to have access to all their space. You could if you wish make use of [user quotas](#persquota) to stop individual users from taking too much space.


!!! Note 
    The above points do not apply to the reserve quotas, since they don't exist on the service machine. They're just a book-keeping fiction, and using them is cost free. We recommend this to any project which is concerned about running out of space.]


### <a id="mvspace"></a> How can I create a quota for a project group, or move space between quotas?

First, read the [discussion of space administration](#space). 
If you are still determined to use project group quotas, this is how.

[Login to SAFE](../safe-for-users#login) Then:


1. Go to the Menu *Projects* and select the *project* you wish to work on. This will display a panel with the project information.
1. Scroll down and click the small arrow beside "Disk Quotas" to expand the section. 
1. In the *Group Quotas* section, click on button beside the File System you wish to work on.	
1. You will now see a list of your project groups, including the general and reserve groups. Project groups which have no quota will show the note *No quota set*
1. Click the small arrow beside "Instructions..." to display detailed instructions.
1. Click the *Move From* and *Move To* buttons of the groups you want to change
1. Fill in the number of Gb to move in the box
1. Click *Move*
1. Repeat until you have entered all the moves you wish to make
1. Click *Submit* and the move instructions will then be carried out.


Do not forget the final Submit step, or nothing will happen. The act of moving quota space to a project group which has no quota set converts that project group to one with a group quota, administered by a Unix group, as discussed [earlier](#space).


Quota changes are actually carried out by a human being. Once this has been done, you will receive an email informing you. If you ask for the quota to be reduced below the current size of the files in the project group, the human will reject your request, and you will get an email saying this.




### <a id="persquota"></a>How can I set a quota for an individual user?

User disk quotas are completely separate from project group quotas. A user quota simply places a limit on the amount of space which a particular user can occupy in workspace or homespace. There's nothing to stop you setting user quotas which add up to more (or less) than the total space. To set a quota for a user or users:

[Login to SAFE](../safe-for-users#login) Then:


1. Go to the Menu *Projects managed* and select the *project* you wish to work on. This will display a panel with the project information.
1. Scroll down to *Disk Quotas*
1. In the *User Quotas* section, click *Home* or *Work*
1. You will see a list of users. Enter a value for each of the users whose quota you wish to change
1. Click *Submit Changes*

Once again, these quota changes are carried out by a human. Once they have finished, you will receive an email.

As with group quotas on the work file-system you can only be absolutely sure of writing data when you are more than 7Gb below your quota limit.



## <a id="managing-users"></a> Managing Project Users

### <a id="regusers"></a> How can project users get registered?

You must not apply for machine accounts on behalf of other users, or let others use accounts that belong to you. Account sharing is strictly forbidden on ARCHER2. 
Every user must [register on SAFE](../safe-for-users#register) and then [apply for their own machine account](../safe-for-users#getac)

In order to get an account, a potential user just needs to know the project machine and  code.

		
1. Give the users the project code and any advice on what username they should request in your project if you wish.
1. Every user must [register on SAFE](../safe-for-users#register) and then [apply for their own machine account](../safe-for-users#getac)

	
### <a id="approve"></a> How to approve user sign up requests
	
If you notice that the Menu *Projects managed* is highlighted, then this indicates that there is a request for project membership awaiting approval. 
		
You can also set up to [receive email alerts](#projalert) whenever a signup request is waiting.
		
You have to accept (or reject) each user's request.

[Login to SAFE](../safe-for-users#login) Then:

1. Go to the Menu *Projects* and click on the highlighted project and you will see the details of the user who has applied.	
1. Click on the Full name (with email) link to see full details of the person requesting the account.
1. Click on the User name link to see details of the requested account.
1. Click the "Accept/Reject" button next to the user to see basic details about the person, including their Nationality, Institution and Department
1. Click on either the "Reject" or "Approve" button to reject or accept them.

If you now accept the user, they will get an account. This is the last chance to stop someone who should not be there! Take a few seconds to check the user's details, especially their email address, to make sure that they are who they say they are. Please check their nationality as well: it's your responsibility to make sure this is right.

When you accept a user, the systems team is automatically requested to create the account on the service machine. When this has been done, the user is emailed; allow a working day for this. The user can then login to SAFE and [pick up their password on the service machine](../safe-for-users#getpass).


When you click Accept you will then be taken to a list of all the [Project Groups](#projgrp) in your project, so you can easily add the new user to the group(s) they will be using.
Simply tick the box against any groups they should be a member of, and then click "OK".



### <a id="projman"></a> How can I designate a user as a project manager?
A project manager can do everything in a project that a PI can do, except designate another project manager. You can designate as many project managers as you wish.

 
1. Make sure the user has an account in your project.
1. [Login to SAFE](../safe-for-users#login)
1. Go to the Menu *Projects* and select the *project* you wish to appoint a project manager for. This will display a screen with a variety of options for managing the project.
1. Scroll down to "Manage members"
1. Click *Add project manager*
1. A drop down list will be displayed which contains all the users within the project. Select the user you wish to make a manager and click *Add*


If you later wish to remove a project manager, click *Remove project manager*, select the *project manager* and then click *Remove*.

You may want to enable a project user to perform some, but not all, of the project manager roles.

The options available are

- Approve Users
- Make Sub Groups
- Move Budget
- Move Group Quota


<p>You can enable these using the "Set member permissions" button</p>


### <a id="groupman"></a> How can I designate a user as a project sub-group	manager?

A project sub-group manager can only move time and disk quota between the groups they manage. They can also create new sub-groups underneath these groups. (If you manage a parent group you automatically manage all its children). Sub-group managers can also accept new people into the project and run reports on the project.

		
1. Make sure the user has an account in your project.
1. [Login to SAFE](../safe-for-users#login).
1. Go to the Menu *Projects* and select the *project* you wish to appoint a project sub-group manager for. 
1. Scroll down to project groups and click on the small arrow beside *Project Groups* to expand and display all the groups in the project.
1. Select the project-subgroup that you wish to assign a sub-group manager for. 		
1. Scroll to the bottom of the page and Click on *Add Manager*.
1. You will now have a drop down list of all the users who are sub-group members but not currently managers. Select the new manager from this list and click *Add* and then confirm the change.

To add users to the new project group, see the next question. A user can belong to more than one project group.


### <a id="addu"></a> How can I add users to an existing project group?


[Login to SAFE](../safe-for-users#login). Then:
		
1. Go to the Menu *Projects* and select the *project* you wish to are work on. 
1. Scroll down to project groups and click on the small arrow beside *Project Groups* to expand and display all the groups in the project.
1. Select the project-subgroup that you wish add or remove users to or from. 
1. Scroll down to the bottom and click on *Add accounts*
1. This lists all of the active users accounts within project, select the users that you should have access to the project group clicking the boxes next to their names and click *Add* 
1. To remove existing members from a group, use *Remove accounts*

To see which members have access to the project group, select *project sub-group* and click *List Members.*

If the project group is using [disk quotas](#space), this operation is carried out by a human, so there may be a short delay. 
Otherwise, it happens at once.

A user can belong to more than one project group.


### <a id="remuser"></a> How can I remove a user (or users) from my project?


Please check the [ARCHER2 policy](https://www.archer2.ac.uk/about/policies/project_account_closing) on on end  of life procedures for ARCHER2 user accounts.

If you wish to remove a user from your project, please email [support@archer2.ac.uk](mailto:support@archer2.ac.uk) giving the username of the user to be deleted.
Service desk staff will arrange for the account to be deleted, in line with the policy.  
 
  

### <a id="projmailing"></a> How can I send a mailing to all users in my project

[Login to SAFE](../safe-for-users#login) Then:

1. Go to the Menu *Projects* and select the *project* you wish to work on. This will display a screen with a variety of options for managing the project.
1. Scroll down to *Project mailings* click on *View*
1. You will see a list of all of the previous project mailings, and the option to compose a new one.
1. Select *Compose*
1. To change the mailing or content, you can use the *Edit Subject* and *Edit* buttons. Once you have changed the text select *Update*.
1. To send the mail click *Send*. There is an option to *Start Over* - this will wipe the content of the email. The *Abort* option will take you out of the mailing page completely.


## <a id="track-usage"></a> Tracking your Project Usage

### <a id="snap"></a> How to check the current state of your project's time and space


[Login to SAFE](../safe-for-users#login) Then:

1. Go to the Menu *Projects* and select the *project* you wish to work on.
1. Under *Project groups* you can see the current state of each project group's budgets. If it uses disk quotas, you will see these, together with how much of is in use.



If a project group's use of a quota is getting close to the maximum, it is highlighted.</p>

The budget values displayed are updated every morning, and the values shown for disk use are updated four times a day. For this reason, these values may not all be completely up-to-date. If there is a lot of activity in your project, the numbers shown could be significantly different from the current ones.

### <a id="phist"></a> How to track what my project's users and project groups are doing

This can be done using the Report Generator

[Login to SAFE](../safe-for-users#login) Then:

1. Go to the Menu *Service information* and select *Report generator*
1. Choose a report format: Preview, HTML, PDF or CSV (comma-separated values &mdash; good for input to Excel, *etc.*)
1. Select the start and end dates of the period you are interested in
1. Select *Project Information*. (Only PIs and project managers see this section)
1. Select the information you need.
1. Click *Generate Report*
1. If you initially selected Preview and would now like this report in one of the other formats, you can now click the format you wish and the same report parameters will be used to generate the report.

### <a id="autorep"></a> How to request automatic project reports

[Login to SAFE](../safe-for-users#login) Then:

1. Go to the Menu *Projects* and select the *project* you wish to work on. This will display a screen with a variety of options for managing the project.
1. Click on *Update*
1. Enter the email addresses which the reports should be sent to in *Recipients for automatic reports.*
1. Set the *Frequency of Automatic Reports* to the preferred frequency.
1. Click *Update* to confirm the changes.

### <a id="udisk"></a> How to check how much space my project's users are occupying

Use the Report Generator (see the [previous question](#phist)), and select *User disk use*. The Report Generator displays the history of disk use &mdash; to see the current use, make sure that the reporting period includes the present moment. The disk usage values known to the database are updated four times a day, so if there is a lot of activity in your project, the numbers shown could be significantly different from the current ones.


There's an unresolvable problem with this: if a user has an account which belongs to more than one project, the disk usage shown for that account will be the total that the account is using in all those projects combined.

### <a id="more"></a> How to request more resources (AUs and disk space)

If you need more home or work space, contact the [Service desk](https://www.archer2.ac.uk/support-access/servicedesk.html). We will always receive such requests sympathetically, and it is likely that we will be able to allocate some more to your project. 

If you need extra time, you should contact the research council which is funding your project. The helpdesk cannot allocate time without authorisation from them.</p>


