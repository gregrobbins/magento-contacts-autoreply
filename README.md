magento-contacts-autoreply
==========================

Magento module that makes the standard contact form send an automatic reply to the user.

This works in a way similar to the existing contact funcionality. The file at:

    locale/en_US/templates/email/contact_form_autoreply.html

contains the template for the autoreply email.

To install this module simply rsync to your existing Magento insallation. Be sure to add the command --exclude=.git so you don't overwrite an existing git repository (I learned this the hard way).
