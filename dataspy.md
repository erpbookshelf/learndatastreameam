## Dataspy - Cannot Delete, Has References

If a Dataspy cannot be removed from the system because of a reference to it ("Unable to delete dataspy - it is associated to another record in the system"), check in the following locations:

* Security Group - Screen Permissions (r5permissions)
* Inbox link
* KPI link
* Hyperlinks (r5hyperlinks)

Do not delete the row from r5permissions (this doesn't correctly disassociate from the user group). Instead, go to the user group indicated in the row, add the screen if it isn't already in the menu, and go to screen permissions to remove the security dataspy.
