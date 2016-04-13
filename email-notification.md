#Email Notification

TODO: Make updates to this article

##Adding Emails Back to the Queue

The R5MAILEVENTS table contains the Emails (these are the ones from Administration, E-Mail Messenger, E-mail Viewer). Set the MAE_SEND to "-" and MAE_RSTATUS to "N" to add the messages back to the queue.

update R5MAILEVENTS set mae_send='-', mae_rstatus='N' where ...
