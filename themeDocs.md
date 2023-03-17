---
layout: page
title: Theme Plugin 
permalink: /theme_plugin/
---
# MSY Theme #

This plugin has all the design and styling features for MSY. This plugin also makes the website mobile responsive.

## Plugin Functionality: ##

The plugin has many functionalities. However, the only one that is changable via the browser, i.e. without changing the code, is changing the website logo and the window logo, to do that:
- Log in as admin, 
- Go to "Site Adminstration"
- Apperance
- Logos
- Upload your new file

## Installing via uploaded ZIP file ##

1. Log in to your Moodle site as an admin and go to _Site administration >
   Plugins > Install plugins_.
2. Upload the ZIP file with the plugin code. You should only be prompted to add
   extra details if your plugin type is not automatically detected.
3. Check the plugin validation report and finish the installation.

## Installing manually ##

The plugin can be also installed by putting the contents of this directory to

    {your/moodle/dirroot}/theme/msy

Notice, you need to ename the folder to be "msy" exactly.

Afterwards, log in to your Moodle site as an admin and go to _Site administration >
Notifications_ to complete the installation.

Alternatively, you can run

    $ php admin/cli/upgrade.php

to complete the installation from the command line.

## License ##

2023 SH05 <2572157H@student.gla.ac.uk>

This program is free software: you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation, either version 3 of the License, or (at your option) any later
version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with
this program.  If not, see <https://www.gnu.org/licenses/>.
