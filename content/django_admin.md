Title: A Tour of the Django Admin
Date: 2016-04-18 19:35
Category: Django

The admin is perhaps one of the most overwhelming components of the Django web framework once you decide that you want to set to work on customising it for your own needs; it's simple enough to do 

The admin is one of the most useful components of the Django web framework; simple enough to get up and running with, but very easy to get overwhelmed by once you decide that you need to customise it for your own ends.  

Before I go on, a few caveats. 

Firstly, while it may be difficult to assess this at the outset, there is a danger that you'll create more work for yourself if you try and customise the admin too much; you may find that it's ultimately less work to create your own views to manipulate your data.

Secondly. WHAT WERE THE OTHER CAVEATS?

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

### ChangeList

UNDOCUMENTED!

Got to 18 minutes or so into Pushing the ponies' boundaries. To be continued...




