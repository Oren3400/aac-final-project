a11lyaxe plugin for moodle (https://moodle.org)

this is moodle plugin for Accessibility Testing in atto editor
implementing Axe engine (https://www.deque.com/axe) (https://github.com/dequelabs/axe-core)

MOODLE INSTALLATION
===================

Here is a short summary of the installation process (which can take just a few
minutes):

1. Move the Moodle files into your web directory.

2. Create a single database for Moodle to store all its tables in (or choose an
   existing database).

3. Visit your Moodle site with a browser. You should be taken to the
   install.php script, which will lead you through creating a config.php file
   and then setting up Moodle, creating an admin account etc.

4. Set up a cron task to call the file admin/cron.php every minute.

For more information, see <https://docs.moodle.org/en/Installing_Moodle>.

Good luck and have fun!

PLUGIN INSTALLATION
===================

install in GUI by drag & drop the zip file or put the folder that in the zip file in this path:
lib\editor\atto\plugins

add it to editor in Site administration->Plugins->Atto toolbar settings->Toolbar config

we also added the icons that used for this plugin
put the icons in this path:
\pix\e
 
thanks alot to @nadavkav our mentor for the guidness and the help
