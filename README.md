# University of Waterloo HTML email system

This is summarized documentation for how to use this HTML email template system. For more comprehensive information, refer to the [documentation](https://github.com/joekwan/uw-html-email-system/tree/master/documentation) in the Documentation folder.


## Layout variations

There are two layout variations available: one column and two column. Each of these layouts has their own available options within. Please keep in mind that all options are meant to be commented or un-commented depending on whether the design calls for them to be used. Be dilligent when adding/removing comment tags so that the overal layout is not adversely affected.

### ONE-COLUMN
This template has options for:
- Additional row of images underneath the hero image.
- Right-aligned body copy inline image
- Left-aligned body copy image
- Button row below body copy

### TWO-COLUMN
This template has options for:
- Left column inline image (full column width)
- Right column right-aligned body copy image
- Right column left-aligned body copy image
- Right column button row below body copy

## Pre-production

Each major section of the templates will be wrapped in comments that have a number and a description of what the section is for.
```(html)
<!-- ********************* -->
<!-- 5 START highlight bar -->
<!-- ********************* -->
(code goes here)
<!-- ***************** -->
<!-- END highlight bar -->
<!-- ***************** -->
```
Note that Zurb's Ink templates are previewed best in Google Chrome or Safari. The templates do not always display properly in Firefox.

Once you have completed building the email you must go through a series of steps to get the code ready to be distributed.

### Inlining CSS
This is the most important step since most email clients do not support linking external stylesheets. There are a number of online inliners but the one we recommend is the [Inky inliner by Zurb](http://zurb.com/ink/inliner.php) since we are using their Ink email framework to begin with.

You must paste the contents of the base stylesheet and the custom stylesheet (in that order) into ```<style>``` tags in the head of the HTML. Then paste that code into the inliner. The code it renders is the inlined version.

## Customization
While the templates are meant to be the underlying framework for the evites. However, if customization is needed for a certain evite, or if you would like to make improvements, see Zurb's [Ink documentation](http://zurb.com/ink/docs.php).
