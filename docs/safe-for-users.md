# SAFE for users

This section covers the use of SAFE to:

  - Manage your personal details and preferences
  - Manage your user accounts on different systems and services


!!! warning
    This document is currently under development and may be incomplete and/or misleading in places.
    Please continue to refer to the <a href="http://www.archer.ac.uk/documentation/safe-guide/">existing documentation</a> until this work is completed and this warning removed.



<p>
  <a href="https://www.archer.ac.uk/safe">SAFE</a> is an online ARCHER2 service management system. Through SAFE, 
  individual users can request machine accounts, reset passwords, see available resources and track their usage. 
  All users must be registered on SAFE before they can apply for their machine account.
</p>
<!-- <p>A YouTube video walk-through is available wherever you see the Play Video 
symbol <img src="../../img/video_play_icon.jpg" alt="Play video"> by clicking on the symbol.</p> -->

<h5><a href="#reg-log-pass">Registering, logging in, passwords</a></h3>
<ul>
  <li><a href="#register"> How to register on SAFE </a> </li>
  <li><a href="#login">How to login to SAFE </a></li>
  <li><a href="#2fac">How to use 2-factor authentication to SAFE </a></li>
  <li><a href="#details">How to change your personal details on SAFE</a></li>
  <li><a href="#chemail">How to change your email address on SAFE</a></li>
  <li><a href="#chpass">How to change your SAFE password</a></li>
  <li><a href="#reset">How to reset your SAFE password if lost or forgotten</a></li>
  <li><a href="#getac">How to request a machine account</a></li>
	<li><a href="#accguest">How to request access to a guest budget</a></li>
  <li><a href="#reset_machine">How to reset a password on your machine account</a></li>
  <li><a href="#getpass">How can to pick up your password for the service machine</a></li>
  <li><a href="#package-group">How to request access to a Package Group</a></li>
</ul>


<h3><a href="#user-mailing">User Mailing Options</a></h3>
<ul>
  <li><a href="#mailings">How to view user mailings</a></li>
  <li><a href="#mlist">How to get added to, or removed from the email mailing list?</a></li>
</ul>


<h3><a href="#tracking">Tracking and managing available resources</a></h3>
<ul>
  <li><a href="#ures">How to check how much time and space are available</a></li>
  <li><a href="#resources">How to request more AUs/disk space</a></li>
  <li><a href="#uhist">How to review your usage of the service, or the activity of the service as a whole</a></li>
</ul>

<h3><a href="#pubs">Tracking Publications</a></h3>
<ul>
  <li><a href="#regdoi">How to register a publication on SAFE</a></li>
  <li><a href="#listdoi">How to list your publications in SAFE</a></li>
  <li><a href="#exportdoi">How to export your publications from SAFE</a></li>
</ul>

<h3><a href="#miscellaneous">Miscellaneous</a></h3>
<ul>
  <li><a href="#checkq">How to check the queries you have submitted to the helpdesk</a></li>
  <li><a href="#token">How to register your approval &mdash; or your annoyance</a></li>
	<li><a href="#delacc">How to delete your user account</a></li>
</ul>


<br />
<hr />



<h2 id="reg-log-pass">Registering, logging in, passwords</h2>

<h3 id="register">How to register on SAFE</h3>
<ol>
<!--   <a href="http://youtu.be/Kuk5bES22LQ"><img src="../../img/video_play_icon.jpg" alt="Play video" title="Play video" style="float:right; border:0"></a>
 -->
   <li>Go to the <a href="https://safe.epcc.ed.ac.uk/">SAFE logon page </a></li>
	 <li>Click "Create an account"</li>
  <li>Fill in your personal details.  You can come back later and change them if you wish</li>
  <li>Click "Register"</li>
  <li>
    You are now registered. Your SAFE password will be emailed to the email address you provided. You can then login 
    with that email address and password
  </li>
</ol>

<p>

<p>At this point your account is registered on the SAFE but you do not have a machine account for ARCHER2.
  To obtain a machine account you should follow the steps to <a href="#getac">Request a machine account</a>.
</p>


<h3 id="login">How to login to SAFE and Overview of Main Page</h3>
<ol>
<!--   <a href="http://youtu.be/8KRL8wL-5rs"><img src="../../img/video_play_icon.jpg" alt="Play video" title="Play video"  style="float:right; border:0"></a>
 -->
   <li>Go to the SAFE <a href="https://safe.epcc.ed.ac.uk/">https://safe.epcc.ed.ac.uk/</a></li>
  <li>Type in the email address you have registered with</li>
  <li>Type in your SAFE password</li>
  <li>Click "Login"</li>
  <li>You are now on the Main Page and here you can see Menus along the top which give access to SAFE functionality</li>
</ol>


<h3 id="2fac">How to turn on 2-factor authentication to SAFE</h3>
<p><a href="#login">Login to SAFE</a>. Then:</p>
<ol>
<!--   <a href="http://youtu.be/B-t1Hs2LQvA"><img src="../../img/video_play_icon.jpg" alt="Play video" title="Play video" style="float:right; border:0"></a> -->

<li>Go to the Menu <i>Your details</i> and select <i>Set 2 factor token</i>.  A scanable QR code will be displayed.</li>
<li>Install a suitable smart-phone app such as 
google-authenticator (<a href="https://play.google.com/store/apps/details?id=com.google.android.apps.authenticator2">android</a>, <a href="http://appstore.com/googleauthenticator">ios</a>)
on your phone or mobile device.</li>
<li>Follow the app instructions to add a new account and scan the displayed QR code (or type in the dispayed 26 character key).</li>
<li>Type the verification code generated by the app into the <i>Verification code</i> box.</li>
<li>Click <i>Set</i></li>
</ol>

<p>2-Factor Authentication is now enabled.  <br />
Each time you log in to the SAFE, in additon to requesting your SAFE password or Institutional login, 
you will also be asked for the current 6-digit authentication code from the app.
</p>
<h3>How to turn off 2-Factor Authentication on SAFE</h3>

<p><a href="#login">Login to SAFE</a>. Then:</p>
<ol>
<li>Go to the Menu <i>Your details</i> and select <i>Disable 2 factor authentication.</i></li>
</ol>



<h3 id="details">How to change your personal details on SAFE</h3>
<p><a href="#login">Login to SAFE</a>. Then:</p>
<ol> 
<!--   <a href="http://youtu.be/6sTdANKT9Ag"><img src="../../img/video_play_icon.jpg" alt="Play video" title="Play video" style="float:right; border:0"></a>
 -->
  <li>Go to the Menu <em>Your details</em> and select  <em>Update personal details</em></li>
  <li>Make the changes you wish</li>
  <li>Click <em>Update</em> to save the changes</li>
  <li>Go back to <em>Your details</em> and you will see the revised information</li>
</ol>

<p>
  Do not forget the <em>Update</em> step, or nothing will happen. Note that your postal address does not automatically 
  include the name of your department and institution; if you want these in your postal address, you must 
  type them again as part of Address Lines 1-4.
</p>


<h3 id="chemail">How to change your email address on SAFE</h3>
<p><a href="#login">Login to SAFE</a>. Then:</p>
<ol>
<!--   <a href="http://youtu.be/B-t1Hs2LQvA"><img src="../../img/video_play_icon.jpg" alt="Play video" title="Play video" style="float:right; border:0"></a>
 -->
  <li>Go to the Menu <em>Your details</em> and select <em>Update email</em></li>
  <li>Enter the new email address and click <em>Request</em></li>
</ol>

<p>
  A verification email will then be sent to the new email address. This email contains a link which you must 
  use to verify your new address. On acknowledging your new address the change will be committed and you must 
  use the new email address when logging into SAFE
</p>


<h3 id="chpass">How to change your SAFE website password</h3>
<p><a href="#login">Login to SAFE</a>. Then:</p>
<ol>
<!--   <a href="http://youtu.be/I47wu32SzfE"><img src="../../img/video_play_icon.jpg" alt="Play video" title="Play video"  style="float:right; border:0"></a>
 -->
  <li>Go to the Menu <em>Your details</em> and select <em>Change website password</em></li>
  <li>Type in the new password, and then again to confirm, and click <em>Change</em></li>
</ol>


<h3 id="reset">How to reset your SAFE password</h3>
<p>Go to <a href="https://safe.epcc.ed.ac.uk">https://safe.epcc.ed.ac.uk</a>.  Then:</p>
<ol>
<!--   <a href="http://youtu.be/VCIBJIpyroM"><img src="../../img/video_play_icon.jpg" alt="Play video" title="Play video"  style="float:right; border:0"></a>
 -->
  <li>Click <em>Forgot password?</em> next to the <em>Login</em> button</li>
  <li>Enter your email address</li>
  <li>Click <em>Send password recovery email</em></li>
  <li>SAFE will mail you a one-time password reset link</li>
</ol>

<p>
  SAFE will only mail a password reset link to email addresses already registered in SAFE. 
</p>

<p>
  Of course, anyone could go to SAFE, click "Forgot password?", and type your email address. If that happens you will receive an email message out of the blue with a password recovery link. This can be safely ignored - no changes will be made if the link is not used.
</p>


<h3 id="getac">How to request a machine account</h3>
<p><a href="#login">Login to SAFE</a>. Then:</p>
<ol>
<!--   <a href="http://youtu.be/Gjgdc3SGuCE"><img src="../../img/video_play_icon.jpg" alt="Play video" title="Play video" style="float:right; border:0"></a>
 -->
  <li>Go to the Menu <em>Login accounts</em> and select <em>Request login account</em> </li>
	<li>Choose the project you want the account for in the "Project" box.  </li>
	<li>Click "Next"</li>
	<li>Select the machine you want the account for from the available machines. </li>
	<li>Click "Next"</li>
  <li>Enter the username you would prefer to use on the service machine <br>
	<li>Click "Request"</li>
	
</ol>





    Every username must be unique.  Some machines including ARCHER2 and Cirrus require you to create a new machine account with 
    a unique username for each project you work on.  Usernames cannot be used on 
    multiple projects, even if the previous project has finished.  
    Some machines require you to have set up an ssh key in SAFE before you can request your machine account.

		
<p>
  Next you will be asked to accept the <a href="http://www.archer.ac.uk/about-archer/policies/">Terms and Conditions of Access</a>, 
  by clicking the appropriate button.  When you do this, you will be sent an acknowledgment by email.
</p>

<p>
  Now you have to wait for your PI or project manager to accept your request to register. When this has happened, the 
  systems team are prompted to create your account on the service machine. Once this has been done, you will be sent
  an email. You can then <a href="#getpass">pick up your password</a> for the service machine from your SAFE account.
</p>



<h3 id="accguest">How to request access to a guest budget</h3>

<p>A guest budget is a budget in one project which has been set up to permit access requests from users in a different project.</p>

<p><a href="#login">Login to SAFE</a>. Then:</p>

<ol>
  <a href="http://youtu.be/J_ATuU6YhTs"><img src="../../img/video_play_icon.jpg" alt="Play video" title="Play video" style="float:right; border:0"></a>
  <li>Go to the Menu <em>Login accounts</em> and select the login account you want to use to access the guest budget</li>
	
	<li>Click on <em>Request group/budget</em> <br />
	then from the drop-down list <em>Group to request</em> select the guest budget that you wish to use. </li>
	
	<li>Click on the <em>Request</em> button.</li>
</ol>	
  <p>The request will be sent to the PI of the project of the guest budget and once the request has been approved then you will be
	able to use the guest budget code in your jobs submit scripts.</p>




<h3 id="reset_machine">How to reset a password on your machine account</h3>
<p>If you still remember your current machine account password, you can simply log in to ARCHER2 as normal and then use the <code>passwd</code> command.</p>

<pre>
passwd
</pre>

<p>You will then be prompted to enter your current password, and then your new password twice.
Your password must comply with the <a href="https://www.archer2.ac.uk/about/policies/passwords_usernames">password policy</a>.</p>

<p>If you have forgotten your current password, or it has expired, then you can ask for it to be reset:</p>

<p><a href="#login">Login to SAFE</a>. Then:</p>
<ol> 
<!--   <a href="http://youtu.be/t8Bw8pPicHE"><img src="../../img/video_play_icon.jpg" alt="Play video" title="Play video" style="float:right; border:0"></a>
 -->
   <li>Go to the Menu <em>Login accounts</em> and select the account you need the new password for</li>
   <li>Click <em>username</em> which displays details of this service machine account.</li>
   <li>Click <em> Request Password Reset</em></li>
	 <li>Click <em>Yes</em> to confirm</li>
</ol>

<p>
  Now the systems team will change your password. When this has been done, you will be informed by email;  this means 
  that you can come back to SAFE and <a href="#getpass">pick up your new password</a>.
</p>


<h3 id="getpass">How can I pick up my password for the service machine?</h3>
<p>Wait till you receive the email with your details.  Then:</p>
<ol>
<!--   <a href="http://youtu.be/OSHVivtanuA"><img src="../../img/video_play_icon.jpg" alt="Play video" title="Play video" style="float:right; border:0"></a>
 -->
  <li><a href="#login">Login to SAFE</a>.</li>
  <li>Go to the Menu <em>Login accounts</em> and click on the account username for which you want to look up the password.<br />
This will display details of your account. 
	<li>Click <em>View Login Account Password</em></li>
  <li>Your password to the service machine will be displayed</li>
  </li>
</ol>

<p>  This password is generated randomly by the software. It's best to copy-and-paste it across when you log in to the 
  service machine.</p> 
	
	<p>After you login, you will be prompted to change it. You should paste in the password retreived from SAFE again, and then 
  you will be prompted to type in your new, easy-to-remember password, twice. Your password must 
	comply with the <a href="https://www.archer2.ac.uk/about/policies/passwords_usernames"> Service password policy</a>.</p>
	
	<p>Note that when you change your password on the service
   machine  in this way, this is not reflected on the SAFE.</p>


	 
<h2 id="package-group">How to request access to a Package Group</h2>

<p>
Some software which is installed on ARCHER2 can only be accessed once the user's
license has been confirmed.</p> 

<p>For some of these packages, such as gamessuk, VASP4 and VASP5 you can request access
via SAFE</p>

<ol>
<!--   <a href="http://youtu.be/4S6-IzdAVrI"><img src="../../img/video_play_icon.jpg" alt="Play video" title="Play video" style="float:right; border:0"></a>
 -->
  <li><a href="#login">Log in to SAFE</a></li>
  <li>Go to the Menu <em>Login accounts</em> and select the account which requires access to the package</li>
  <li>Click "Request Access to Package"</li>
  <li>Select the package from the list of available packages and click "Select"</li>
  <li>Fill in as much information as possible about your license, at the very least, the information
  requested at the top of the screen such as the licence holder's name and contact details.<br />
  If you are covered by the license because the licence holder is your supervisor, for example,
  please state this.</li>
  <li>Click "Submit"</li>
</ol> 

<p>Your request will then be processed by the ARCHER2 support team who will confirm
your license with the package developers before enabling your access to the
package on ARCHER2.  This can take several days but you will be advised once this
has been done.</p>

<p>If you require access to a package which does not yet appear in the list of available
packages then please just send an email to the Service Desk to request access.  We are
still working to add all the available packages. </p>

<br />





<h2 id="user-mailing">User Mailing Options</h2>

<h3 id="mailings">How to view user mailings</h3>
<!-- <ul>
  <a href="http://youtu.be/W23Gd3JjiMU"><img src="../../img/video_play_icon.jpg" alt="Play video" title="Play video" style="float:right; border:0"></a>
</ul> -->
<p>
  All mailings are archived and can be viewed in <a href="https://safe.epcc.ed.ac.uk/">SAFE</a>. 
</p>	
	<ol>
			<li><a href="#login">Log in to SAFE</a></li>
			<li>Select "Service information"</li>
			<li>Select the mailing type you wish to read</li>
			<li>Click on "View"</li>
</ol>




<h3 id="mlist">How to get added to, or removed from the email mailing list?</h3>
<p>There are three mailing list options available.</p>
<ul>
  <li>
    The <em>Major Announcements</em> mailings will contain information on major service upgrades and future plans.
    This option is enabled for all users by default.
  </li>
  <li>
    The <em>Service News</em> mailings will contain information on training courses, newsletters, events, and other 
    general announcements. This option is enabled for all users by default.
  </li>
  <li>
    The <em>System Status Notifications</em> will inform users when the service goes up or down, including the 
    reminders of the next planned maintenance shutdowns. This option is not enabled by default, those wishing to receive 
    this information will need to explicitly subscribe to it.
  </li>
</ul>

<p>Any combination of these three options may be selected via SAFE:</p>
<ol>
  <li><a href="#login">Login to SAFE</a>.</li>
  <li>Go to the Menu <em>Your details</em> click <em>Update Email settings</em></li>
  <li>In the panel headed <em>Update email settings </em> make sure there are ticks beside the options you would like to subscribe to.
  <li>Click <em>Update List Preferences</em></li>
</ol>

<p>
  <b>Note 1:</b> There is an option to unsubscribe from the user mailings completely, which overrides any option enabled 
  in <em>Mailing list preferences</em> panel.   
</p>
<p>This will be set automatically to unsubscribe you if mailings sent to an email address are returned to us as "undeliverable".  If you change your email
address we recommend you check you have not been unsubscribed if your previous email address had gone out of service.</p>
<ol></li>
  <li>Click on the Menu <em>Your details</em> 
	<li>Click <em>Update personal details</em> </li>
	<li>Tick <em>Opt out of user emails</em> field to unsubscribe, remove the tick to re-subscribe</li>
  <li>Click <em>Update</em> at the foot of the screen</li>           
</ol>

<p>Do not forget the <em>Update</em> step, or nothing will happen.</p>

<p>
  <b>Note 2:</b> Regardless of whether you are subscribed to a particular mailing list, you can still view ALL user mailings 
  which have been sent, in SAFE. See <a href="#mailings">here </a> for details. 
</p>


<br />



<h2 id="tracking">Tracking and Managing Available Resources</h2>

<h3 id="ures">How to check how much time and space are available to you</h3>

<!-- <ul>
  <a href="http://youtu.be/9MOdQJBRgwg"><img src="../../img/video_play_icon.jpg" alt="Play video" title="Play video" style="float:right; border:0"></a>

</ul>
 -->
<p>
  <a href="#login">Login to SAFE</a> and Go to the Menu <em>Login accounts</em>, select the <em>username</em> which you wish to 
see details for.  

  You will then see the information for this account. You will see the quotas for the disk space (if the
  project group is using these) and how much is in use.  You can also see which file systems your project is using under the heading 'Volume', 
	followed by the current usage by your project, and total quota.  Quotas that are close to being full are hightlighted.
</p>

<p>	
  The budget values displayed are updated every morning, and the values shown for disk use are updated four times a day. For this 
  reason, all these values may not be completely up-to-date. If there is a lot of activity in your project, the numbers shown could
  be significantly different from from the current ones.
</p>


<h3 id="resources">How to request more budget or disk space</h3>
<p>
  In the first instance, please contact the principal investigator, or the project manager of your project. The PI will 
  then take the necessary steps to either allocate you more resources out of the project reserve, or to request an increase
  from the helpdesk/research councils.
</p>
<p>
  The helpdesk does not own project resources and has no authority to allocate them to individual users. This responsibility
  lies with the project PI/project manager.
</p>


<h3 id="uhist">How to review the use you have made of the service, or the activity of the service as a whole</h3>

<p><a href="#login">Login to SAFE</a>. Then:</p>
<ol> 
<!--   <a href="http://youtu.be/6KVtrKpvvEY"><img src="../../img/video_play_icon.jpg" alt="Play video" title="Play video" style="float:right; border:0"></a>
 -->
  <li>Go to the Menu <em>Service information</em> and select <em>Reports</em></li>
  <li>Select the report you wish to run</li>
  <li>Complete the required information in the form: this will usually consist
  of at least a date range to analyse and may have other options depending on
  the report you are running.</li>
	<li>Click on the output format you want to use (Preview, HTML, PDF, CSV)</li>
</ol>	

	<p>The report will be generated and displayed.</p>
	

	<p>If you initially selected Preview and would now like this report in one of the other formats, scroll down to the bottom of the report and
	you can now click the format you want and the same report parameters will be used to generate the report.</p>


<p>If you are a PI or Project Manager, you will have access to additional reports
to generate information on whole projects or groups as well as your own usage
and the usage of the service as a whole.</p>


<h2 id="pubs">Tracking Publications (DOI)</h2> 

<p>The SAFE includes functionality for tracking pulications associated with
projects by registering DOI (Digital Object Identifiers) and automatically
collecting metadata.</p>

<p>Once registerd, lists of DOIs can be exported in a format suitable for
uploading to ResearchFish.</p>

<p>This functionality can be particularly useful for large projects where 
there is a requirement to capture outputs from a large number of users.</p>

<h3 id="regdoi">How to register a publication in SAFE</h3>

<p>You will need a DOI for the publication you wish to register. A DOI 
has the form of an set of ID strings separated by slashes. For example,
<tt>10.7488/ds/1505</tt>, you should not include the web host address which
provides a link to the DOI.</p>

<p><a href="#login">Login to SAFE</a>. Then:</p>
<ol>
  <li>Go to the Menu <em>Your details</em> and select <em>Publications</em> </li>
  <li>Select the project you wish to associate the publication with from the list
  and click <em>View</em>.</li>
  <li>The next page will list currently registered publications, to add one click
  <em>Add</em>.
  <li>Enter the DOI in the text field provided and click <em>Add</em>
</ol>

<h3 id="listdoi">How to list your publications in SAFE</h3>

<p><a href="#login">Login to SAFE</a>. Then:</p>
<ol>
  <li>Go to the Menu <em>Your details</em> and select <em>Publications</em> </li>
  <li>Select the project you wish to list the publications from using the dropdown
  menu and click <em>View</em>.</li>
  <li>The next page will list your currently registered publications.</li>
</ol> 

<h3 id="exportdoi">How to export your publications from SAFE</h3>

<p>At the moment we support export lists of DOIs to comma-separated values (CSV)
files. This does not export all the metadata, just the DOIs themselves with
a maximum of 25 DOIs per line.. This format is primarily useful for importing 
into ResearchFish (where you can paste in the comma-separated lists to import
publications). We plan to add further export formats in the future.</p>

<p><a href="#login">Login to SAFE</a>. Then:</p>
<ol>
  <li>Go to the Menu <em>Your details</em> and select <em>Publications</em> </li>
  <li>Select the project you wish to list the publications from using the dropdown
  menu and click <em>View</em>.</li>
  <li>The next page will list your currently registered publications.</li>
  <li>Click <em>Export</em> to generate a plain text comma-separated values (CSV)
  file that lists all DOIs.</li>
  <li>If required, you can save this file using the Save command your web browser.</li>
</ol>

<h2 id="miscellaneous">Miscellaneous</h2>

<h3 id="checkq">How to check the queries you have submitted to the helpdesk</h3>
<p><a href="#login">Login to SAFE</a>. Then:</p>
<ol>
  <li>Go to the Menu <em>Help and Support </em> and select <em>Your support requests</em> </li>
  <li>Click the Query ID of a query to check the contents of the query log</li>
</ol>

<p>
  This will show you the queries of yours that haven't yet been resolved. Note that some of the internal correspondence 
  about a query will not be shown.  
</p>

<p>You can also use SAFE to submit a query &mdash; use <em>Submit support request</em>.</p>

<!-- 
<h3 id="token">How to register your approval &mdash; or your annoyance</h3>
<p><a href="#login">Login to SAFE</a>. Then:</p>
<ol>
  <li>Go to the Menu <em>Help and Support</em> and select <em>Service feedback</em> </li>
  <li>Click on the scale somewhere between 5 penalty points  and 5 gold stars indicating your level of anger or delight.</li>
  <li>Optionally: enter a comment in the comment box.</li>
  <li>Click <em>Set Token</em>
</ol>

<p>
  The tokens may appear in the public service reports, although your name will not be published with them.  Although an entry 
  in the comment field is optional, it necessarily gives greater weight to your feelings&mdash;without it we cannot tell why 
  you have set a token.
</p>
 -->
 
 
	
<h3 id="delacc">How to delete your user account</h3>

 <p>Please check the Service policy on on end 
 of life procedures for user accounts.<br />
<br />
If you wish your user account on the Service machine to be deleted, please contact the Service Desk giving the username to be deleted.<br />
Service desk staff will arrange for the account to be deleted, in line with the policy.  
 </p>



