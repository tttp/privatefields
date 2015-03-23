# civicrm extension to hide custom fields
When you create a group of custom fields, they are displayed by default on the event info page.
If you have fields you want to keep private (eg information for your team that aren't super useful to display to the public) install this extension.

Every group with a name that starts with "private" will be hidden, so the group "private stuff" won't be visible, as won't "private Ryan". All the other groups are still displayed normally.

What matters is the name you give when creating the group, once created, you can rename the group later (eg. to "internal info") and it will still be only visible from the back office.

All the other features work the same, these fields are still visible from the reports and other backoffice screens. The only thing the extension does it to not display the group on the info page.

## existing groups
Ahh, if you have already created the group with a different name than "private something", it won't be enough to change the title of the group, as the name has already be defined and you can't change it.

We haven't found the budget to improve the UI to change that (hint, hint), but as a workaround, you can either change it directly in the database or use the api explorer to alter the name (the later is safer). entity is CustomGroup, change the name (only lowercase and underscore, it has to start with private) 

## Thank you
This extension has been developped for muntpunt.
