Title: A Tour of the Django Admin
Date: 2016-04-18 19:35
Category: Django

The admin is perhaps one of the most overwhelming components of the Django web framework once you decide that you want to set to work on customising it for your own needs; it's simple enough to do 

The admin is one of the most useful components of the Django web framework; simple enough to get up and running with, but very easy to get overwhelmed by once you decide that you need to customise it for your own ends.  

Before I go on, a few caveats and warnings.

Firstly, you may end up creating more work for yourself if you try to over-customise the admin; there are a wealth of overridable methods in the classes that make up the admin, many of which can be customised with relatively minor adjustments once you understand how they work, but you may find yourself going down a huge rabbit hole if you try to extend it far beyond what it was originally designed to do. If you find the customisations that you have in mind are becoming too much of a time sink it may well be time to take a step back to assess whether what you're trying to do might best be achieved by writing your own forms and views.

It will be difficult to assess what is and isn't customisable when you're taking your first steps with admin customisation, so this will unfortunately entail quite a lot of playing things by ear until you gain more experience.

Secondly, the admin is most certainly not intended to be a tool for end users to manipulate their own content. Don't do this.

On a somewhat related note, be very careful with admin permissions. Given the ease with which a superuser can destroy or modify valuable data you'd be wise to restrict this amount of power only to your technical staff; and perhaps only to a trusted subset of them.


***

## Admin Components

There are three main components of the Django admin that you may have an interest in customising: the ModelAdmin, the AdminSite, and ChangeList. {some of the most complex and difficult to understand parts of the framework, for my money}

The admin framework has been present in the Django framework since the early days, and hasn't been 


### AdminSite

{{encapsulates an instance of the Django admin application, ready to be hooked into your URLconf}}

### ModelAdmin

{{encapsulates all admin options and functionality for any given model}}

Many, many customisation options available.

action_on_top
action_on_bottom

fieldsets: control which fields are displayed.

list_display_links

list_editable

ordering

radio_fields

save_as (should really be named 'save_as_new' -- enable save as new button)

show_full_result_count - 

### ChangeList

UNDOCUMENTED!

Got to 18 minutes or so into Pushing the ponies' boundaries. To be continued...




