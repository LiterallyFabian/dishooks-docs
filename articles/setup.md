# Setting up Dishooks
To use Dishooks you will need at least one Discord webhook placed in the Dishook wrapper class. To create a webhook, follow these steps:

1. Open Discord and go to the channel you want to send messages to.
2. Right-click the channel name and select "Edit channel".
![Edit channel](images/setup1.png)

3. A new window will open. Click "Integrations" and then "Create Webhook".
![Click "Integrations"](images/setup2.png)

    ![Click "Create Webhook"](images/setup3-1.png)

4. Yet another window will open. Give the webhook a name, avatar and click "Create Webhook".
![Give the webhook a name and avatar](images/setup4.png)

5. Open Unity and navigate to the Dishooks folder in the Project window. Open the `Dishooks/Scripts/Dishook.cs` class and paste the webhook URL into the `DefaultUrl` field.
![Paste the webhook URL into the DefaultUrl field](images/setup5.png)
6. You're done! You can now send messages to Discord from your Unity game. Visit the `Dishooks/Example/Dishook examples` scene to see how it works.