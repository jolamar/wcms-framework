# Copy these files to your home area
1. Go to the Home area of your WCMS site and create a folder called `_internal` if it doesn't already exist
2. Edit the `_internal` folder and uncheck `Include when publishing` and `Include when indexing`
3. In the `_internal` folder create 4 new folders called: `blocks`, `velocity`, `templates`, `assets`
4. Go to the `blocks` folder and click `New` > `Default` > `Block` > `Text`<sup>*</sup> and give it the exact name and text as the file you are copying and pasting from.
5. Repeat step 4 for all the blocks
6. Go to the `velocity` folder and click `New` > `Default` > `Format` > `Velocity` and give it the exact name and text as the file you are copying and pasting from.
7. Repeat step 6 for all the velocity formats
8. Go to the `templates` folder and click `New` > `Default` > `Template` and give it the exact name and text as the file you are copying and pasting from. 
9. After submitting the template edit it again and click on the `Regions` sub-tab and place the blocks and velocity scripts in their appropriate regions. At the top of each template file there is a mapping of regions to blocks/velocity to guide you.
10. Repeat steps 8 and 9 for all templates.
11. Go to the `assets` folder and click `New` > `Default` > `Page` and give it the exact name as is in the screenshot, then go to the system subtab and choose the content type shown in the screenshot.
12. Repeat step 11 for all assets

<sup>* you can use an `XHTML/Data Definition` block in place of a `Text` block. The only difference is you'll be given a WYSIWYG editor.</sup> 
