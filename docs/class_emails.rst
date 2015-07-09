Class Emails
============

Composing and Sending an Email
------------------------------

On the main course page:

1. Click the instructor tab
2. Email
3. Compose the email using the HTML editor (copy and paste the template
   below)
4. Test the email by sending it to yourself first (be sure to preview it
   in both Gmail and another email client such as Outlook)

.. note:: Outlook will often block images from being displayed

.. figure:: ../../images/SendClassEmail.png
   :alt: Send Class Email

   Send Class Email

.. note:: The email Subject no longer automatically includes the course name ([Course Name] used to appear before emails automatically).

Template
--------

::

    <p>We're back! ATOC185x: Natural Disasters is being re-offered starting Wednesday, January 14th.</p>
    <p>If life got busy and you ran out of time or you completed the course but want to take part in the discussion, please join us again.</p>
    <p>We are happy to announce for this offering you can choose to complete a verified attestation of completion (equivalent to an edX verified certificate). For more information click <a href="https://www.edx.org/verified-certificate" target="_blank">here</a>.</p>
    <p>Hope to see you again!</p>
    <p><img src="https://courses.edx.org/c4x/McGillX/ATOC185x/asset/email_to_summer_professors_campus_600px.jpg" alt="picture of professors" /></p>
    <p>Professors John Stix and John Gyakum</p>

Adding an Image to an Email
---------------------------

In studio.edx.org:

1. upload the image to the course page with the following
   specifications:

-  A unique name with no special characters or spaces
-  A width of 600px or less (!Important, do not try using html to resize
   the image, it will not work for email clients such as outlook)

2. Copy the **external** URL
3. Replace the highlighted portion of the html below with the external
   URL

::

    "<img src="https://courses.edx.org/c4x/McGillX/ATOC185x/asset/email_to_summer_professors_campus_600px.jpg" alt="picture of professors" />"

4. Replace the alt text with a short description of the picture

::

    <img src="https://courses.edx.org/c4x/McGillX/ATOC185x/asset/email_to_summer_professors_campus_600px.jpg" alt="picture of professors" />

Share This Course Icons
-----------------------

- Be sure the icons are uploaded to the course
- The urls linking to the share icons should match the course from which the email is being sent

.. code-block:: html
    :linenos:
    <h1>code block example</h1>
    
    <div align="center">
    <p>Share this course</p>
    <p>
   <a href="http://www.facebook.com/sharer.php?u=https://www.edx.org/course/natural-disasters-mcgillx-atoc185x#.VH3YpzHF98E" target="_blank"><img src="courses.edx.org/c4x/McGillX/ATOC185x_2/asset/facebook-icon.png" alt="Facebook"/></a> &nbsp;&nbsp;
     <a href="https://plusone.google.com/_/+1/confirm?hl=en&amp;url=https://www.edx.org/course/natural-disasters-mcgillx-atoc185x#.VH3YpzHF98E" target="_blank"><img src="courses.edx.org/c4x/McGillX/ATOC185x_2/asset/google-plus-icon.png" alt="Google+"/></a> &nbsp;&nbsp;
     <a href="http://twitter.com/share?url=https://www.edx.org/course/natural-disasters-mcgillx-atoc185x#.VH3YpzHF98E;text=Description" target="_blank"><img src="courses.edx.org/c4x/McGillX/ATOC185x_2/asset/twitter-icon.png" alt="Twitter"/></a>&nbsp;&nbsp;
    </p>
   </div>
