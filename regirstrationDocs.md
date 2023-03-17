---
layout: page
title: Registration Plugin 
permalink: /registration_plugin/
---

# MSY Registration Plugin #

This plugin allows authentication for students and their school.

## Plugin Functionality: ##

1. Add code:
    - Login as admin
    - Navigate to "Site Administration"
    - Navigate to "Server"
    - Navigate to "Visit regestration plugin > Create registration code"
    - Please do make note of this code and the school name elsewhere, as these codes cannot be changed, and due to security reasons we have implemented a one way hash, which means you need to know the code in order to delete it, you CANNOT check it via the website
    - Create the code

2. Delete code:
    - Navigate to the MSY Admin page, 
    - Look for the registration section, 
    - Click on the delete code link, 
    - Complete the deletion process


## Installing via uploaded ZIP file ##

1. Log in to your Moodle site as an admin and go to _Site administration >
   Plugins > Install plugins_.
2. Upload the ZIP file with the plugin code. You should only be prompted to add
   extra details if your plugin type is not automatically detected.
3. Check the plugin validation report and finish the installation.

## Installing manually ##

The plugin can be also installed by putting the contents of this directory to

    {your/moodle/dirroot}/blocks/msy_course_chooser

Notice, you need to ename the folder to be "msy_course_chooser" exactly.

Afterwards, log in to your Moodle site as an admin and go to _Site administration >
Notifications_ to complete the installation.

Alternatively, you can run

    $ php admin/cli/upgrade.php

to complete the installation from the command line.

## License ##

2023 SH05 <2554268W@student.gla.ac.uk>, <2565536R@student.gla.ac.uk>, <2572157H@student.gla.ac.uk>, <2551657A@student.gla.ac.uk>

This program is free software: you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation, either version 3 of the License, or (at your option) any later
version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with
this program.  If not, see <https://www.gnu.org/licenses/>.
