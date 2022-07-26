# recovery-builder
android 10 tested - pitch black / Twrp recovery 

Building recovery online made easy
Important notice
Users reported build errors forking to own account.
To fix this, create a new organization, fork to the new organization. This fixes the problem, for now.
What this is
This is an easy way for recovery maintainers or anyone who's interested in building recoveries to finish their dream without a server.

This works with GitHub actions, thank GitHub not me.

How to use
Here are some useful notes to using this tool brewed with black magic.

Fork the repo to a organization

Set the variables, as listed below.

Update : If you don't understand the manifest variable, check this

Some variables that you'd like to set:

DEVICE : Most likely your device codename, e.g. rosy, sakura, curtana, etc.

DT_LINK : Link to your recovery device tree.

DT_PATH : Path to clone your device tree

TARGET : recoveryimage 

Go to actions tab, enable workflows.

Star the repo, go to actions tab again, and let black magic go brrr.

If you don't know any of these, Ask Google or someone who builds recoveries, I don't provide TWRP building support.

You'd also like to do edits on your recovery device tree first if your recovery needs that ( TWRP,Pitch black)

And lastly, all TWRP compiling help from Google.

Enjoy buildbotting.
