6.10
========================================

Teamwork
*********
- Using a new way to provision teams - approver who approves a team no longer becomes owner (#127793, #127652, #127793)
- Default values for properties on Teamwork is now available (#115969).
- Naming policies can now be configured on Teamwork.
- Additional general policies can now be configured on Teamwork (minimum length description, minimum number of members).
- Default property values can now be set on a teamwork template.
- Teamwork can now be created in app context. Allowing the possibilities of only having self-service of MS Teams through Omnia.
- The create Teamwork wizard has been completely remade and fixes (#136225, #126909).
- Teamwork provisioning now supports sensitivity labels.
- Corrected validation of group names already existing. 
- Corrected URL validation in all scenarios (#124846, #120614).
- Teamwork rollup now uses the correct date format configured (#120436, #120434).
- Better usage of space in the teamwork rollup in narrow columns (#122146).
- Teamwork image can now be set in Omnia and will be synchronized to the O365 Group or Site.
- Updated people picker to only allow picking valid options (#132420, #133052).
- Teamwork templates can now be targeted.
- Time zone can now be selected by the end user when provisioning a teamwork instance. 
- Fixed an issue where properties would not safe if placed after a custom step (#121168).
- Detaching a teamwork instance no longer sends email (#133240).
- Improved error message when editing a teamwork app that you do not have permissions on (#120426).
- Email send outs have been reviewed (#134224).
- Inactive teamwork can now be reviewed in Omnia Admin.
- Fixed an issue where the wrong feature UI could sometimes be loaded in Omnia Admin.
- Long word site titles will now work as expected (#123672).
- Teamwork layouts can now be created and included as a tab in MS Teams. (To display for example Controlled Documents Authoring).
- Its now possible to provision a MS Teams Teamwork from an existing MS Team.
- MS Teams standard templates are now supported in Omnia templates.
- A Planner board can now be provisioned together with the Teamwork.



Process Management
*****
- Using “Add as favorite” action button on processes now adds the process with the correct title (#135579).
- Processes can now be printed or exported to PDF.
- Mouse over no longer shows cursor:pointer if there is no link (#120202, #123510).
- Process search can now be combined with other kinds of data.

Workplace
************
- The User Profile Competition block now has configurable button labels (#116581).
-  Mega menu rendering in mobile and tablet improved (#125709).
- Corrected an issue with the action bar rendering when navigating via direct links (#119504).
- Corrected hover effect on links in the top navigation (#114578).
- App Instance Posts Block available. See main release notes.
- The Logo now correctly renders as unclickable if no link is configured (#133844).
- Its now possible to configure if "My subscriptions" will show up or not in the user profile card.
- Team channel feed now handles System events correctly.
- The calendar rollup no longer contains a broken link to the calendar item in Outlook.
- Publishing apps now have a contribute role, making it possible to control who can comment/like/rate etc.

Web Content Management
*************
- Label padding now aligns better (#138463).
- Possibility to move pages between page collections (#113462, #132221).
- Possibility to move page collections between publishing apps (#113462, #132221).
- Related links can now use more options on how to open links (#133631, #119645, #120098).
- Related links now handles long links better including line breaks (#113899).
- RSS Feed block can now handle more kinds of images (#115862, #116968).
- Media properties can now have default values (#116730).
- SVG files now provide correct thumbnails when picked from a SharePoint library (#136801)
- Show more button in the Quick Links block now have the correct color settings (#117529, #117911)
- Corrected an issue with color settings in the enterprise glossary (#136443).
- Sorting by columns now has a larger clickable area (#119772).
- Fixed a cache issue on the page collection settings page (#137099).
- The variation picker no longer shows drafts as selectable (#128061).
- Improved UI in the edit banner form for small screens (#136671).
- Corrected the design of bullet lists in the FAQ block (#114117). 
- Automatic translation options are now correct when inheriting from tenant (#115062).
- Added possibility to resync Omnia Search Index, stability improvements to sync of SharePoint data. (#137857). 
- Improved page view statistics gathering. 
- Fixed an intermittent error where the preview of pages would sometimes give access denied (#136471, #138372, #134866, #136157).
- Authors can no longer delete page collections.
- Reworked action menus, icons, and option placement.
- Performance improvements for automatic translations.
- Performance improvements for editing Channels.
- Improved support for right to left languages when using auto translate.
- Emails sent from Web Content Management now fallback to the Business profile language.
- “Controlled Documents” and “Process Library” can now be activated on the backend site of a publishing app. 
- Channels can now be categories in to one Default Channel and Additional Channels.
- Blocks from a Layout/Page Type can now be configured to be unlockable. Allowing the editor on the page to change its configuration.
- Updated link picker UX with more options.
- Page Versioned Documents allow the editor to tie a document to the page versioning. It also allows first line works / Kaizala users to download the document. 
- Automatically translated pages can now be edited. NOTE: The edit will be overwritten upon a new publish of the default page.
- When moving a page in the navigation structure to a childless node, the page is now selected after the move (#118661).
- A generic integration is now available to connect omnia to third party big screen providers. 
- Additional blocks supported for automatic translation.
- Publishing app settings tabs have been reorganized.
- Reusable content pages with many connections, now needs to be manually triggered.
- AD Groups can now be set as publishers on Channels. 

Search
*******
- Corrected rendering of links in search (#138299).
- Layout updates to search to better use the space when using promoted links and feedback (#136188, #136341, #136593).
- Improvements to the Omnia Free Text search generation (#136940, #136892).
- Corrected rendering of Teams Presence in Quick Search.
- Added missing shadow of dropdown.

Controlled documents
****
- Added support for icons on .msg files (#120880).
- Updating multiple draft documents properties will now work correctly (#138671).
- Added a missing space to the default text in the Feedback dialog (#120819, #122188).
- Document rollup now correctly resets filters when navigating between multiple rollups with different settings (#119636).
- All metadata in a document rollup can now be exported to Excel. 
- User Language ({UserLanguage}) can now be used as a token in the query of the document rollup.


System
**********
- The Azure AD Sync has received several updates to improve stability (#138948).
- Default content features can now be upgraded without error (#120974).
- Feature naming and categories have been updated. 
- User profile completeness now reaches 100% even when the user profile picture is included (#119425, #134770).
- Improved rendering of Icons in all system (#120369).
- Corrected the z-index of the “Your session has expired” message (#120381).
- General performance improvements for page loads and page rollups.
- The login flow has been simplified, leading to better performance on login.
- The setup Wizard is now available for all tenants.
- The Script block MSGraph client now refreshes its tokens automatically in case they expire.
- New definitions of built-in groups, see main release notes.
- Multiple targeting properties can now be linked to the same enterprise property (#116344).
- A Teamwork app generator is now available to make deployments to MS Teams easier.

Page Rollup
*********
- Possibility to view and sort by Most visited (#118520).
- Better overflow for the page rollup in narrow columns (#133906).
- Its now possible to sort on text in the page rollup (#119522, #127382, #128932, #124725).
- Possibility to show pages in a calendar view.
- Possibility to query on All pages (Tenant) or all pages in a Business Profile.
- Possibility to query on Language.
- Possibility to query on and show pages that has never been published.
- Possibility to query on Workflow status (Scheduled).
- Possibility to query on statistics. 
- Possibility to sort by most viewed. (#115241, #121723).
- The page rollup results can now be exported to Excel.
- Possibility to filter on Channels for all scopes. 
- Corrected background color from theming in the navigation view. (#131977).
- Its now possible to have custom labels in the List View.
- Social period has been renamed Time Period in settings. 
- The Page rollup can now be configured to open the target page in the editor. Allowing for editorial tools to be created using the page rollup.
- Corrected line height in the dynamic roller.



WCAG and UI/UX
***************
- alt text when hovering term picker icon corrected. (#115442).
- Better rendering of term picker with many terms at the top of the screen (#133753).
- When selecting multiple terms, the picker will not close between selections (#116627, #121832).
- Corrected color for the close button of the notification panel admin blade (#126112).
- aria-describedby is now used to connect error messages in user profile completeness to the correct form input.
- Configurable alt-text now available on the tenant and BP logos.
- Browser title updated to better comply with WCAG recommendations. 
- Updated aria-labels for navigation components.
- no-script message added if Omnia is started without JavaScript enabled. 
- Corrected heading structure to better comply with WCAG standard. 
- Better element IDs for the search panel.
- Improved keyboard control feedback.
- Several corrections to rendering in Safari.
- Teams presence is now available on all components where applicable. 
- Corrected background color on the skeleton loader.
- Close button and click out added to the tutorial.

Also fixes preview bugs (#138042, #138335, #138527, #138224, #138538, #138239, #138050, #137947, #138216)
