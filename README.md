# Kill Touch Bar
An Alfred workflow to kill/restart the Touch Bar

I had the issue that sometimes my Touch Bar turned black. Searching for a solution I found that this seems to be a problem for other people as well. So I built this dead simple workflow.

It runs

    pkill TouchBarServer; pkill ControlStrip

with administrator privileges and acknowledges execution with a notification. That's it.
