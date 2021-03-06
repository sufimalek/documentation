.. _user-guide-activities:

Activities
===========


.. contents:: :local:
    :depth: 3



Overview
---------

Activities are actions that employees of your company perform on a daily basis. The range of these actions is quite wide. Employees define and fulfill job tasks, handle different issues, communicate with colleagues and customers, participate in events. Hence, it is important to have a good tool that gives a possibility to conveniently keep track on and manage all these actions. 

OroCRM provides such a tool. Its capabilities for managing activities are quite wide. They cover three logical directions: workflow management, communications, and adding useful remarks.

|

.. image:: ../img/activities/activities.png

| 

For each activity, it is possible to add links to the related records. For example, link to an email with the discussion in which the activity emerged, to the marketing campaign that the activity deals with, to the user concerned, etc. Such links are called ``contexts`` and they make it much easier to take account of all the details connected with the activity.

.. Note:: 
    As account is an entity that integrates customer entities, if one of the customers that constitute account is added as a context of some activity, account inherits this activity and you can see it note only on the customer view page but on the account's as well.  



In this document, you can find short descriptions of what each activity serves for. 


.. important:: 
 	By default, the list of activities available for each entity is determined by what is most commonly used by businesses. However, if your company's work process requires it, you can always turn the desirable activity on for almost any entity (except technical ones). If you need particular activities to be enabled for an entity, contact your administrator, or see steps 4 and 5 of the :ref:`Create an Entity <doc-entity-actions-create>` action description.


Workflow Management
--------------------

Managing Tasks
"""""""""""""""

What Is a Task? 
~~~~~~~~~~~~~~~~

Tasks are assignments that need to be accomplished by a user. Keeping track on tasks helps organize the work process and ensure that all the important work is done. 
'Create a regional sales report,' 'Compose an email to customer ABC,' 'Prepare everything required for marketing campaign A'—these are all examples of tasks that users can be assigned. 


What You Can Do with Tasks?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

With OroCRM you can create, assign tasks, organize them by priority, set their due date and manage them through their life cycles. 


|

.. image:: ../img/activities/activities_tasks.png

| 


  
Tasks can be created in 3 different ways. 

**1st Way**
If you need to distribute the work in your business unit and make sure that the work time of your employees is used in an optimal way, you can go to the user view page, check their current tasks in the corresponding section, and click the :guilabel:`Assign Task` action button to create and immediately assign a new task to this user.  

**2nd Way**
The second way is the most convenient when the idea of the task appears when you work with the certain entity record. For example, you work with the opportunity record and decide to create a task related to it. Click the :guilabel:`Add Task` action button to create a task. 

|

.. image:: ../img/activities/activities_tasks2.png

| 

You will see that the opportunity on which view page the task was added, appears as a context of the task being created.   

|

.. image:: ../img/activities/activities_tasks2-2.png

|
  


.. note::
    If you use the :guilabel:`Add Task` action button on a user view page, the user does not appear as a context for the task. 


**3rd Way**
The third way is the most traditional: you have the whole system section devoted to tasks where you can create, assign and manage tasks as you find it necessary.

|

.. image:: ../img/activities/activities_tasks3.png

|

Users can see tasks assigned to them on the **My Tasks** page and in the **Tasks** section of their view pages. 
If some entity record is marked as a context for a task, this task appears in the **Activity** section on the entity record view page. 


For more information about tasks, see the :ref:`Tasks <user-guide-activities-tasks>` guide.

  
Managing Cases
"""""""""""""""

What Is a Case? 
~~~~~~~~~~~~~~~~

Cases are issues, problems or failures reported by customers or found internally. It's important to record, monitor and solve cases in time to ensure that small and big issues do not harm your company business. 

'5 faulty details in the supply,' 'Missing picture for the product 01234,' 'User Jane Smith cannot log in' are examples of cases that you can create. 


What You Can Do with Cases?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can create, assign tasks, organize them by their source, priority, set their due date and manage them through their life cycles. 


In addition to this, the out-of-box integration with Zendesk customer support platform is available. When you activate it, you can load data from Zendesk tickets into OroCRM cases and vice verse. (Note that you need to have a configured Zendesk account).

You can create tasks in the dedicated system section devoted to tasks where you can create, assign and manage tasks as you find it necessary.

|

.. image:: ../img/activities/activities_cases.png

|

Users can see cases assigned to them in the **Cases** section of their view pages. 
If some entity record is marked as a context for a case, this case appears in the **Activity** section on the entity record view page. 


For more information about cases, see the :ref:`Cases <user-guide-activities-cases>` guide.


Calendar Events
""""""""""""""""

What Is a Calendar Event? 
~~~~~~~~~~~~~~~~~~~~~~~~~

It is very easy for a busy employee who is working hard on some task to forget about some meeting or appointed call. It is also easy to imagine a situation when you send emails to your colleague hoping to find a quick answer to an urgent question and nobody answers. It usually takes you a bit of time and a few more calls to find out that the said colleague is on the business trip or at a conference.
     
While such incidents can negatively affect the reputation of your business and work performance, it is very easy to avoid them: for each important meeting, conference, call, etc. create an event in an OroCRM calendar. 


What You Can Do with Calendar Events?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can create calendar events, define who is to participate in them and when and how reminders about an upcoming event will be sent to participants.  

If more than one person should participate in the event, add them as guests and the event will appear on their calendars as well. 

As with tasks, there are three ways to create a calendar event: 

- By clicking :guilabel:`Assign Calendar Event` action button on the view page of the user you want to assign this event to.
- By clicking the :guilabel:`Add Calendar Event` action button on the view page of the entity record related to this event. For example, if you want to discuss a certain account with your colleagues, you can go to the account's view page and add a new calendar event from it. The account will become a context for this event.   
- By clicking the :guilabel:`Create Calendar Event` button in the dedicated system section. 

|

.. image:: ../img/activities/activities_calendarevents.png

|

After you have created an event, an invitation is sent to the expected participants.    

Users can track events on the **My Calendar** page or via the dashboard widget (**Today's calendar**). They can also see calendars of your colleagues or any additional calendars added by an administrator.

If some entity record is marked as a context for a calendar event, this event appears in the **Activity** section on the entity record view page. 


For more information about calendar events, see the :ref:`Calendar Events <user-guide-activities-events>` guide.


Communications
----------------

Making and Logging Calls
"""""""""""""""""""""""""

While not every company employee makes calls very often, calls play one of the driving roles in sales and are of significant help for support teams. For those users who make and receive many calls per day or / day communicates by phone with clients, it is convenient to have an instrument that enable them to make records of who they called to and what they talked with that person about. Such instrument also helps managers monitor whether everything important is done, whether all key contacts receive enough attention.

OroCRM's call logging functionality allows users record whom was the call with, which party initiated it, when it was made and what was its duration, its subject. A user can also make additional notes about conversation content and mention what entity records it dealt with.  

Additionally, OroCRM integration with Google Hangouts enables users to make Hangouts voice or video calls from within OroCRM, providing an advantage for sales and support teams, as they will be able to connect with customers directly.
Users can make voice calls to one phone number, or launch a video conference with up to 5 participants. Call data will be logged automatically, including any notes you have made during the call. 


There are three ways to start making or logging a call: 

- By clicking the :guilabel:`Log Call` button in the dedicated system section.
- By clicking the **Hangouts call** or **Log Call** icons that appear near phone fields throughout the system when you hover over them.  
- By clicking :guilabel:`Log Call` action button on the view page of the entity the call is connected to.


|

.. image:: ../img/activities/activities_calls3.png

|


.. image:: ../img/activities/activities_calls.png

|

Users can access logged calls in the dedicated system section, in the **Activities** section of their user page, via the **Recent calls** dashboard widget. If some entity record is marked as a context for a call, this call appears in the **Activity** section on the entity record view page. 


|


.. image:: ../img/activities/activities_calls2.png

|





For more information about logging calls, see the :ref:`Calls <user-guide-activities-calls>` guide.


For information about whether Hangouts calls are available for you, contact an administrator or see the :ref:`Voice and Video Calls via Hangouts <user-guide-hangouts>` guide.



Sending and Receiving Emails
"""""""""""""""""""""""""""""
    
It is a fact that in the majority of modern companies a significant amount of important information is being exchanged via emails. Company employees may not use phones or messengers, but email box is a must. 

OroCRM allows users send and receive emails from within the system. Users can utilize personal and system (company-wide) mailboxes. They can neatly design their letters using HTML and in-built text editor, create and use email templates, attach files to emails, configure signatures of their liking. It is also a possible to configure auto-actions (for example, for each email received to a certain mailbox, a lead record or a case may be created in the system) and auto-responses.

There is also such feature as auto-assignment to contact: new emails synced into Oro are automatically linked to contacts if email addresses of these contacts appeared in the correspondence. Usual for activities possibility to link an email to mentioned context is also available. Moreover, when an email contains a file as an attachment, it is possible to reattach the file to the entity record itself manually or automatically. 


For Oro CRM Enterprise Edition supports integration with Microsoft Exchange Server and Outlook.


Users can access their emails on the personal **My Emails** page, via the **Recent Emails** menu button and the ** Recent Emails** dashboard widget. 

|

.. image:: ../img/activities/activities_emails1.png

|

When some entity record has been mentioned as a context in an email, or if an email has been sent using **Send Email** action button from the entity record view page, this email will be also available in the **Activities** section on the record  view page. Emails linked to contacts appear in the same section on the corresponding contact view pages.


|

.. image:: ../img/activities/activities_emails2.png

|

For more information about how you can use emails, see the :ref:`Emails <user-guide-using-emails>` guide.

For how to configure emails, ask your administrator or see the :ref:`Email Configuration <user-guide-email-admin>` guide.


Creating Contact Requests
""""""""""""""""""""""""""

Imagine that your company participates in an exhibition. Visitors advance your representers asking for more detailed information about the company's products to be sent to them via email or telling that they already use your products but would like some assistance with them. 

To maintain such requests, use the contact request functionality in OroCRM. With it you can create a contact request record in which you define who you need to contact and how (via email or phone), the request type (i.e. what a requester needs: more information, assistance, make a complaint, etc.) and fill in any details that concern this request.

Users can see and manage contact request in the dedicated system section.


|

.. image:: ../img/activities/activities_contactrequests.png

|

Contact requests can be also created automatically. For this, put an embedded form like 'Contact Us' on your site. After a user fills the form in and submits it, the corresponding contact request will appear in your Oro application. See more about embedded forms in the :ref:`Embedded Forms <admin-embedded-forms>` guide.

For more information about contact requests, see the :ref:`Contact Requests <user-guide-activities-requests>` guide.


Adding Useful Remarks
------------------------


Making Notes
"""""""""""""

Sometimes you need to leave additional information about an entity record. For example, you now that you need to refer to one of your foreign contacts strictly in a certain way. While it is possible to add an additional field to an entity to store this information, it is not very rational when it concerns only one or to contacts, while other contacts may require very different but also specific remarks. 

For such cases, there is an in-built functionality in OroCRM that enables you to leave notes of any kind on entity records. 


|

.. image:: ../img/activities/activities_notes.png

|

You can add a note by clicking the :guilabel:`Add Note` action button on the view page of the entity record that the note relates to. You can format note as required and attach files to them. 
Notes are displayed in the **Activities** section of the entity record view page.


For more information about notes, see the :ref:`Notes <user-guide-add-note>` guide.


Leaving Comments
"""""""""""""""""

Discussing work with colleagues can boost a work process. Use comments functionality to hold a discussion on an entity record view page.  Thus users can be sure that everything important that emerged during this discussion will not be lost and can be easily found.   
Users can also use comments to express their personal opinion about the entity record or anything connected with it (while notes can serve for storing some objective information regarding an entity record.

You can leave a comment in the **Comments** section of the entity view page. 

|

.. image:: ../img/activities/activities_comments.png

|


For more information about comments, see the :ref:`Comments <user-guide-activities-comments>` guide.


Add Attachments
"""""""""""""""""

When you need to provide additional information about an entity record and this information is fully included in a file (for example, you want to add a calculation sheet), add this file as an attachment directly to the entity record. 

You can attach files by clicking the :guilabel:`Add Attachment` action button on the view page of the entity record that the attachment relates to.

Files attached to the entity record appear in the **Attachments** section of the entity record. 


|

.. image:: ../img/activities/activities_attachments.png

|


For more information about attachments, see the :ref:`Attachments <user-guide-activities-attachments>` guide.



