.. _user-guide-activities-attachments:

Add Attachment
==============

You can add an attachment to a record in OroCRM.

.. important::
    By default, the list of activities available for each entity is determined by what is most commonly used by businesses. However, if your company's work process requires it, you can always turn the desirable activity on for almost any entity (except technical ones). If you need particular activities to be enabled for an entity, contact your administrator, or see steps 4 and 5 of the :ref:`Create an Entity <doc-entity-actions-create>` action description
    
.. hint::

    The attachment settings depend on the specific entity settings. See step 5 of the :ref:`Create and Entity <doc-entity-actions-create>` action description.


Add Attachments
---------------

Once a record has been created, an attachment can be added from its View page.

.. caution::

   The ability to view and upload attachments depends on the :ref:`permissions <user-guide-user-management-permissions>` 
   defined for the entity.

- Go to the record view page.

- Click the :guilabel:`Add Attachment` action button.

.. image:: ../img/activities/add_attachment.png

- In the form emerged:

  - Choose the file to attached.

  - Leave a comment, if necessary.

  - Define the attachment owner. Only the owner and users with whose 
    :ref:`roles <user-guide-user-management-permissions>` that enable management/viewing of the owner's attachments will 
    be able to manage/view the attachment.

.. image:: ../img/activities/add_attachment_form.png


   
View and Manage Attachments
---------------------------

The attachment is now available from the record View page in the grid in the *Attachments* section:

.. image:: ../img/activities/add_attachment_view.png

From the :ref:`grid <user-guide-ui-components-grids>`, you can

- Delete the attachment: |IcDelete|
- Get to the edit form of the attachment: |IcEdit|

You can also :ref:`add the attachment <user-guide-using-emails>` to emails related to the record.



.. |IcDelete| image:: ../../img/buttons/IcDelete.png
   :align: middle

.. |IcEdit| image:: ../../img/buttons/IcEdit.png
   :align: middle