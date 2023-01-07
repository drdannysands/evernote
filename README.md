# evernote
Danny's Alfred workflow for Evernote

I use Evernote frequently and wanted tools to be able to use it more efficiently. There were some Evernote workflows I had tried but they no longer worked with newer versions of Evernote.

This allows the automated creation of new Evernote notes or searching for a text string through keyword trigger or universal action. No configuration is needed. This workflow is compatible with Evernote 10+, which wass challenging because it has no AppleScript support.

Keyword

enn [optional note title]: creates a new note. If there is a parameter (or with Universal Action) sets the note title as parameter with today's date. (If Evernote is not open it is started prior to executing action.)

enp [optional note title]: creates a new note with contents being latest clipboard entry (from copy or cut action). If used as Universal Action then that text becomes note content. If there is a parameter (not available with Universal Action) sets the note title as parameter with today's date. (If Evernote is not open it is started prior to executing action.)

ens [optional search term]: opens Evernote search field. If there is a parameter (or from Universal Action) then that becomes search string and search is run. (If Evernote is not open it is started prior to executing action.)

en: opens Evernote with no action.

Danny Sands
danny@drdannysands.com
@DrDannySands
https://github.com/drdannysands/evernote
