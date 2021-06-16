### HOW TO transfer passwords in a new FireFox installation.
#### FireFox Password files:
- key3.db [v58+] 
- key4.db 
- logins.json 
#### How to proceed:
1. Create a new Profile.
2. In the new profile, remove the password files. 
3. Copy those same files from the old profile.\
Steps 2 & 3 must be done using file Explorer and with Firefox __closed!__ 
#
### Restore Real Working Search Box on New Tab Page in Firefox 89 and Later
1. Start Firefox and open the "notorious" __about:config__ settings page by typing it in the address bar.
2. Now type (or copy-paste) `awesomebar` in the 'Search preference name' textbox; the following line will be shown:
`browser.newtabpage.activity-stream.improvesearch.handoffToAwesomebar`
3. Double-click on that line (or click the `toggle`icon at the right of the line) and change the value from _`true`_ to ___`false`___. 
4. Now, (quickly and before the mozilla dragon come back and catch you messing up secret settings, a case which usually leads him to blow up dragon-flames against mischievous boys --well, rumor has it,  with girls he's way more tolerant), close the `about:config` page and ... you're done!
 - credits: https://www.askvg.com/fix-restore-real-working-search-box-on-new-tab-page-in-firefox-89-and-later/
