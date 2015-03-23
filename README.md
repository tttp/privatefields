# civicrm extension to hide custom fields
When you create a group of custom fields, they are displayed by default on the event info page.
If you have fields you want to keep private (eg information for your team that aren't super useful to display to the public) install this extension.

Every group with a name that starts with "private" will be hidden

## existing groups
Ahh, if you have already created the group with a different name than "private something", it won't be enough to change the title of the group, as the name has already be defined and you can't change it.

We haven't found the budget to improve the UI to change that (hint, hint), but as a work around, you can either change it directly in the database or use the api explorer to alter the name (the later is safer)


