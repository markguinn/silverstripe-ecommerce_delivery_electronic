###############################################
ecommerce delivery ELECTRONICALLY
Pre 0.1 proof of concept
###############################################

Allows you to let people download files based on
a sale.

THE KEY IS: add the following method to your buyable:

function DownloadFiles(){
 //return a DataObject Set of files here....
}

You can also add files to the Order Step.

Make sure that you send a receipt AFTER you have created
the files for download!

Developers
-----------------------------------------------
Nicolaas Francken [at] sunnysideup.co.nz

Requirements
-----------------------------------------------
Ecommerce 1.0+ / SSU Branch
SilverStripe 2.4+

Project Home
-----------------------------------------------
See http://code.google.com/p/silverstripe-ecommerce

Demo
-----------------------------------------------
See http://www.silverstripe-ecommerce.com

Installation Instructions
-----------------------------------------------
1. Find out how to add modules to SS and add module as per usual.
2. copy configurations from this module's _config.php file
into mysite/_config.php file and edit settings as required.
NB. the idea is not to edit the module at all, but instead customise
it from your mysite folder, so that you can upgrade the module without redoing the settings.

If you just want one or two things from this module
then of course you are free to copy them to your
mysite folder and delete the rest of this module.




