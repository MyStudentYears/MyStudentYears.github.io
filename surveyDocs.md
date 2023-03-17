---
layout: page
title: Survey Plugin Documentation
permalink: /survey_plugin/
---

# MSY Registration Survey #

This plugins allows the user to generate an authentication code for a specific school to allow students, representatives, and teachers to sign up.

# Plugin functionality #

To explore this plugin's functionality, you can access the administration pages through the relevant links on the administration page. **It is worth noting that, for security reasons, once a code has been generated it cannot be displayed again within Moodle. As a result, you should make note of any codes you generate.**

## Installing via uploaded ZIP file ##

1. Log in to your Moodle site as an admin and go to _Site administration >
   Plugins > Install plugins_.
2. Upload the ZIP file with the plugin code. You should only be prompted to add
   extra details if your plugin type is not automatically detected.
3. Check the plugin validation report and finish the installation.

## Installing manually ##

The plugin can be also installed by putting the contents of this directory to

    {your/moodle/dirroot}/auth/msy_registration

Notice, please ensure that the folder is named exactly "msy_registration"

Afterwards, log in to your Moodle site as an admin and go to _Site administration >
Notifications_ to complete the installation.

Alternatively, you can run

    $ php admin/cli/upgrade.php

to complete the installation from the command line.

## License ##

2023 SH05 <2554268W@student.gla.ac.uk>

This program is free software: you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation, either version 3 of the License, or (at your option) any later
version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with
this program.  If not, see <https://www.gnu.org/licenses/>.
