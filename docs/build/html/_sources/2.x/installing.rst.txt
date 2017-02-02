Installation
============

.. _installing_uikitty:

Installing UIkitty
------------------

.. note::
    Make sure you are using the right version of UIkitty. Sub-themes follow the same versioning as UIkitty, so if you are using a 8.x-2.x sub-theme, you want to use the 2.x version of UIkitty. If you are using a 8.x-3.x sub-theme, you want to use the 3.x version of UIkitty


Download and Install Uikitty
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Once youve completed your Drupal installation, its time to download and install Uikitty. Go to Uikitty project page on Drupal.org and right click the tar.gz file for the current release and copy the link location.

Go to your new Drupal 8 installation and log in with the admin account.
Browse to /admin/appearance and click the "install new theme" button.
Paste in the link location you just copied from the Uikitty downloads page. It should start with "https://ftp.drupal.org/", if its not, then you copied the wrong file.
Click Install
On the the appearance page /admin/appearance, find the new uikitty theme screenshot and click the "install and set default" link for Uikitty.
At this point, Uikitty is fully installed and usable however to use it, you will need to set up a sub theme for Uikitty. You can either download a contributed sub theme for Uikitty or use the Uikitty Starter Kit to generate an empty sub theme that you can build from scratch.


Install a contributed sub theme for Uikitty
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

There are a number of preconfigured sub-themes for Uikitty and are freely available on drupal.org. Just search for uikitty on drupal.org to see what is available. For this example, we will download the "Architect", a contributed sub theme for Uikitty and install it.

Go to the Architect's project page on drupal.org and copy the link location of the tar.gz file for the newest release.
Browse to ``/admin/appearance`` and click the "install new theme" button.
Paste in the link location for the Architect's newest release.
Click install
In admin/appearance find the screenshot for the Architect sub theme and click "install and set default".


Site setup is easy
~~~~~~~~~~~~~~~~~~

Create a new custom block(in the custom block library) named "Front headline".
Add some headline text into the body field(something like "Uikitty Rocks!")
Add some more text for a subheading beneath the text you just entered.
Change the top headline text to be Heading 2 by using the wysiwyg dropdown or go into source and change the tag to h2.
Now save the custom block and make sure to add it to the "Front Headline" region on the next screen.
All other blocks go in like named regions and must be updated in block layouts and saved. Additionally 2 image styles are recommended to be setup as follows:

HDBG 1920x1080 - Scale effect set to 1920x1080px
w860x - Scale set to 860x nothing (dont enter anything in the height field)
Now create a new image field called "Reference Background" in both Article and Page content types.
Now set each content type's default display to use HDBG 1920x1080 for the default image and reference background style using the cog on the right side. (/admin/structure/types/manage/page/display)
Set the teaser view style to use the w860x image style and set it to link to the content
