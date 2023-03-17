---
layout: page
title: Admin Plugin Documentation
permalink: /admin_plugin/
---

# MSY Admin Plugin #

This plugin adds a page that aids the admin of MSY to gain access to other plugin's settings

## Plugin Functionality: ##

The plugin has a few features which are as follows:

1. Announcement caresoul 
   - Add slide to the caresoul and, 
   - Manage slides for the caresoul

2. Survey management
   - Add survey questions and, 
   - Manage questions and,
   - Pick madetory courses and, 
   - Manage mandetory courses and, 
   - Survey management page which shows:
     - Out of the people who have interacted with the survey, who comepleted it
       - This works for both the pre registration and the after surveys.

3. Data visualisation
   - View data visulisation

4. Registration plugin
   - This allows you to create a code for a particular school to allow students to register to the website

5. Resources block
   - This allows you to add resources to the dashboard and, 
   - Remove resources from the dashboard

## Installing via uploaded ZIP file ##

1. Log in to your Moodle site as an admin and go to _Site administration >
   Plugins > Install plugins_.
2. Upload the ZIP file with the plugin code. You should only be prompted to add
   extra details if your plugin type is not automatically detected.
3. Check the plugin validation report and finish the installation.

## Installing manually ##

The plugin can be also installed by putting the contents of this directory to

    {your/moodle/dirroot}/report/msy_admin

Notice, you need to ename the folder to be "msy_admin" exactly.

Afterwards, log in to your Moodle site as an admin and go to _Site administration >
Notifications_ to complete the installation.

Alternatively, you can run

    $ php admin/cli/upgrade.php

to complete the installation from the command line.

## License ##

2023 SH05 <2554268W@student.gla.ac.uk>, <2565536R@student.gla.ac.uk,>

This program is free software: you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation, either version 3 of the License, or (at your option) any later
version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with
this program.  If not, see <https://www.gnu.org/licenses/>.
