WB Datadict Plugin
==================

WB Datadict is a plugin for MySQL Workbench Community Edition 5.2.33. This
plugin allows you to generate an HTML data dictionary from the schema
loaded in the application.

Installation
------------

   1. Download WB Datadict (using the "Downloads" tab above or the
      "get source" link).
   2. Extract the contents wherever you want.
   3. Open MySQL Workbench.
   4. Select the option Scripting → Install Plugin/Module.
   5. Browse to the WB Datadict directory (extracted in step 2) and select
      the "datadict_grt.py" file.

You should see a message like this:

    Plugin Installed
    Plugin /path/to/datadict_grt.py was installed, please restart Workbench
    to use it.

Lastly, press "ok" and restart MySQL Workbench.

Now you should find the plugin available in
Plugins → Catalog → Generate HTML Data Dictionary.

Remember you have to be on a "EER Diagram" tab to use it.
