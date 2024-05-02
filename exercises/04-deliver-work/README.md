# `05` Validate your work

This step consists of executing a verification script to validate what has been requested in this practice, to do so follow the steps below:

## 1. Enable the public port

So that learnpack can receive the information that will be sent from your machine, it is necessary to enable the public access of the port, that for security is private by default.

To do this select the “Ports” tab in the bottom panel of codespace, there you will see the ports that are being used. You need to publish port `3001` and to do this right click on the port, go to the `Port Visibility` menu and select the `Public` option.

![Public pocrt](../../.learn/assets/public-ports.png)

## 2. Run the validation script `validate-update-script.sh`.

Once you have run the script to see it work, and added it to the cron jobs, it is time to validate.

On the desktop of your Debian machine you will get a folder called `cybersecurity-scripts` and inside it a folder corresponding to the `02-linux` module. Inside this folder you must execute with bash the script `validate-update-script.sh`. When you run it, it will ask you for the exact path of your script and the learnpack address that you can see in the `url.txt` file of this repository.

If all goes well, in the terminal you will see a message confirming that the data was sent. 

## 3. Upload your results

Once the script has been successfully executed, you will be able to upload your results. To do this you must generate a commit from this repository and upload the changes to github.

The first step is to go to the version control icon and generate a new commit. To do this you must place a message and click on the `Commit` button.

![Generate commit](../../.learn/assets/commit.png) button.

It will probably ask you to agree to add the recent changes to your commit. You can skip this action in the future if you select the `Always` option.

![Accept stage of changes](../../.learn/assets/accept-stage.png)

Finally you are going to make a push to upload the changes from your local instance to github

![Make push](../../.learn/assets/push.png)

## 4. Done!

If you have any problems, don't hesitate to reach out to a mentor or the other support channels offered by 4Geeks.
