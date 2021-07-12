# Kill Touch Bar
An Alfred workflow to kill/restart the Touch Bar

![Kill Touch Bar Logo](./Touchbar.png)

I had the issue that sometimes my Touch Bar turned black. Searching for a solution I found that this seems to be a problem for other people as well. So I built this dead simple workflow.

Activate Alfred, type 'touchbar', and hit enter.

It runs

    pkill TouchBarServer; pkill ControlStrip

with administrator privileges and acknowledges execution with a notification. That's it.
