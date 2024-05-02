# `03` Schedule the task

Once your script is working properly you can move on to the next step to automate its execution from time to time. To do this you must create a cron job and tell it to run the update script every day.

## 📝 Instructions:

1. Create a cron job that runs the update script every day at midnight.

2. You must dump the output of the script to the `/var/log/update-server.log` file.

3. Dump the error output of the script to the `/var/log/update-server-error.log` file.

## 💡 Hint:

> The crontab manual (type in the console `man crontab`) contains not only information about the specific command, but also how all scheduled tasks work in general, you can find a lot of useful information there.
>
> Remember that you can use the `>>` characters to redirect the output of a command to a file, as well as `2>>` to redirect error output.
