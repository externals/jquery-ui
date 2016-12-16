# jquery-ui

this is a repo to hold different versions of jquery-ui you may need 
and also to make them available for the toolbax application as default

Downloaded from jquery.com and set to the "toolbox" branch the versions you prefer for the toolbox as default

Checkout the version you need or create a new branch including the version you want

if you need them toolbox wide? then merge it to the toolbox branch

example:
# toolbox branch
./v0.1.2/jquery-ui.min.js
./v0.1.2/README.txt

If a new version exists and you need it for the toolbox globaly:
don't drop other versions! Add your version to it:

Eg: You need verion 1.0.1 system wide:
checkout the master branch and create a new branch: "v1-0-1" (branches needs - NOT dots!)
create a folder: mkdir v1.0.1/
Download the jquery-ui.min.js to v1.0.1/
commit & push the new vesion branch

Then checkout the "toolbox" branch and merge your version into it. result:
# toolbox branch
./v0.1.2/jqery.min.js
./v0.1.2/README.txt
./v1.0.1/jqery.min.js
./v1.0.1/README.txt

