# Nation Planet

**FIX ME** (This section still represent old BeLL application)

## Objectives

* Learn to sync your Community with the Nation
* Use the Nation interface to check whether your Community successfully joined the Nation
* Update your Community Planet to the latest version

## Introduction

In [Step 1 - Planet Installation - Configuration](vi-configurations-vagrant.md) you registered your community Planet with the nation. Now, you will learn how to keep your community Planet in sync with the nation.

There should be constant communication between the nation and the communities. While it is not necessary for remote communities in the field, it is ideal for our goals of "improving the software and testing the increasing forms of communication and feedback between the nation and the communities". This communication takes the form of a syncing process from the community side, where you select material to send to the nation.

Make sure vagrant is running and then click [here](http://localhost:3100) to access your Community Planet.

**NOTE**: After you register your community, but before you can sync with the nation, you need to create an additional dummy user on your community. Therefore, create a quick additional user under "Become a Member" on the login page (HINT: When creating the dummy user, don't give it a password that you actually use). Then, login to dummy account you just created and double-check that you're listed under Members. Then, log out and log back in with your admin account. Now that your community has a user, you can sync with the nation.

![Clicking on "Dummy User"](images/vi-become-member.png "Dummy User")

## Sync With the Nation

In [Step 4](vi-bellapps.md#Different_Kinds_of_Updates_to_Your_Community), we listed 3 kinds of updates that you might receive on the community side: updates, publications, and surveys. Another important type of update is the reverse: syncing with the nation. This sends data about your community to the nation.

As you can see from the picture below, click on "Manager".

![Clicking on "Manager"](images/vi-nation-manager.png "Dashboard in your localhost")

Next, click on "Sync with Nation".

![Clicking on "Sync with Nation"](images/vi-nation-sync.png "Community Manage Page in your localhost")

Then, "Select All" and click "Send".

![Clicking on "Select All" and "Send"](images/vi-nation-sync-send.png "Community Manage Page in your localhost")

You have now sent all activities on your community to the nation. To explain further, the nation receives a number of data points: number of resources opened, number of logins, number of members, resource ratings, technical feedback, and resource requests. We don't get specific information on individual users, but rather usage and feedback as whole.

## Check Sync Status

On the nation side ([vi.ole.org](http://vi.ole.org)), you can log in with the username `admin` and the password `password` and check that the sync worked. Click on "Manager" once again.

![Clicking on "Manager" after logging in to the nation](images/vi-nation-manager.png "Dashboard in ole site")

Then, click on "Report Details" to access reports from various communities on the nation.

![Clicking on "Communities"](images/vi-nation-communities.png "Community Manage Page in ole site")

Finally you should see a list of communities and the option to generate a report of community you created.

![Generate Report](images/vi-nation-report.png "Communities Requests Page in ole site")

## Useful Links

[Helpful links and videos](vi-faq.md#Helpful_Links)

#### Return to [First Steps](vi-first-steps.md#Step_7_-_Nation_Planet)
