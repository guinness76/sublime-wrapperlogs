Installation:

1) Within Sublime Text, navigate to Preferences -> Browse Packages. This will open a Packages folder in the file explorer. Copy sublime-ignition-wrapper-log.tmLanguage and sublime-gateway-thread-dump.tmLanguage to this folder.

2) Navigate to the User folder and copy Eiffel.tmTheme here.

2) Restart Sublime Text. After restart, open an Ignition wrapper log. Navigate to View -> Syntax and select 'Ignition Wrapper Log'.

3) For thread dumps, open an Ignition gateway thread dump file. Navigate to View -> Syntax and select 'Gateway Thread Dump'.

4) To stop using either style, navigate to View -> Syntax and select 'Plain Text'.

Updates:
https://www.sublimetext.com/docs/3/scope_naming.html

The regex is in sublime-ignition-wrapper-log.tmLanguage and the color settings are in Eiffel.tmTheme (the support.class scope entry is defined here for exception stacktrace formatting).

Open Regex Tester in Intellij and create regular expressions as needed. Within Sublime Text, navigate to Preferences -> Browse Packages. This will open a Packages folder in the file explorer. Open sublime-ignition-wrapper-log.tmLanguage and add the regexes there. Restart Sublime Text to see the changes. Be sure to copy sublime-ignition-wrapper-log.tmLanguage to the development folder for archiving within Git.

To push to git:
git push https://guinness76:THEPASSWORD@github.com/guinness76/sublime-wrapperlogs

Eiffel.thTheme color scheme (paste into Slack to see the actual colors)
#CD0000
#C5060B
#585CF6
#FFFFFF
#000000
#000000
#BFBFBF
#000000
#C3DCFF
#00B418
#0206FF
#0100B6
#CD0000
#C5060B
#585CF6
#D80800
#26B31A
#1A921C
#0C450D
#0000A2
#70727E
#3C4C72
#6D79DE
#06960E
#21439C
#687687
#990000
#FFFFFF
#FFD0D0
#427FF5
#68685B
#888888
#1C02FF
#0C07FF
#000000
#B90690