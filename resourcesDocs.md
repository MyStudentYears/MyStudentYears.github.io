---
layout: page
title: Resources Plugin
permalink: /resources_plugin/
---

# MSY Resources Plugin #

This plugin adds the ability to display links for online resources in a convenient and visually appealing way on the dashboard of the plugin. 

The main functionality of the plugin is adding resources to and removing resources from the resource display via a couple of settings pages. This should be reflected in any instances of the resources display present in the Moodle website. The resources display also matches the rest of the MSY Moodle theme. 

## Plugin Functionality: ##
  
The plugin has a few features which are as follows:
1. Add a resources block to your dasbboard:
    - You can do that via logging into your admin account, 
    - Going to the dashboard,
    - Enabling edit mode,
    - Click on "Add Block",
    - Choose "MSY Resources Block"

2. Add a resource:
    - You can do this via logging into your admin account, 
    - Go to the required page, 
    - Enable edit mode, 
    - Find your carousel block and click on the cog wheel, 
    - Click on "Configure MSY Annoucement Carousel", 
    - Click on "Add a Slide"
    
3. Removing a slide:
    - For this you can follow number (2)'s steps until the last one, 
    - Click on "Remove A Resource",
    - Enter the name of the resource you want to delete
    
Numbers (2) and (3) could also be done via the following steps:
    - Visit "Site Adminstraion", 
    - Navigate to "Server",
    - In the first section you will see "MSY Admin Page", click on that,
    - There you will find two hyperlinks to do what steps (2) and (3) will do.

4. Delete the block:
    - Go to the required page, 
    - Enable edit mode, 
    - Find the block and click on the cog wheel, 
    - Press "Delete MSY Resource Block" and confirm your decision.

## Installing via uploaded ZIP file ##

1. Log in to your Moodle site as an admin and go to _Site administration >
   Plugins > Install plugins_.
2. Upload the ZIP file with the plugin code. You should only be prompted to add
   extra details if your plugin type is not automatically detected.
3. Check the plugin validation report and finish the installation.

## Installing manually ##

The plugin can be also installed by putting the contents of this directory to

    {your/moodle/dirroot}/blocks/msy_resources

Notice, you need to rename the folder to be "msy_resources" exactly.

Afterwards, log in to your Moodle site as an admin and go to _Site administration >
Notifications_ to complete the installation.

Alternatively, you can run

    $ php admin/cli/upgrade.php

to complete the installation from the command line.

## License ##

2022 SH05 <2554268W@student.gla.ac.uk>

This program is free software: you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation, either version 3 of the License, or (at your option) any later
version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with
this program.  If not, see <https://www.gnu.org/licenses/>.
