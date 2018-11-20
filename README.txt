EX81
====

This is a simple example of creating a custom form in Drupal 8.

Here is the folder structure:
web/modules/custom/ex81
|-- ex81.info.yml
|-- ex81.routing.yml
`-- src
    `-- Form
        `-- HelloForm.php

In this module we create a custom form with two fields, a text field
and a checkbox field, we’ll validate those fields, display them in a
message and finally redirect the user to the home page.

See the full blog post here:
http://karimboudjema.com/en/drupal/20181013/create-custom-form-form-api-drupal-8

INSTALL
=======
Download the module in your module folder.
Install it with: drupal moi ex81

