Go task plugin to run Shell scripts.

*Usage:*

![alt tag](https://raw.githubusercontent.com/srinivasupadhya/script-executor-task/master/images/screenshot.png)

*Notes:*

This is only for convenience since you can run all commands directly through Go anyway.

This could be preferable because:
- Its exactly like shell script. Go's custom command takes a little getting used to.
- Its easier to CRUD commands since its a script, specially re-order them if required.

It should not be used as a replacement for important scripts like deployment scripts. They should remain in your repository.

*Usage:*

Download jar from releases & place it in `<go-server-location>/plugins/external` & restart Go Server.
