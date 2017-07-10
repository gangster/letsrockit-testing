# Testing HOW TO
## Setup

### Install Loom
Loom is a video capture tool that comes packaged as a Chrome extension.   It's easy to use and self-explanatory to install.  To do so, go to here https://www.useloom.com?ref=34628 and follow the instructions for installing the extension.   

### Invite 2 Colleagues and Remove Limits
By default, recording time is limited to 10 minutes and videos expire after 10 days of creation.   To remove these limits,  Loom requires you to get 2 new people to sign up using your unique sign up link, which can be retrieved by going to [https://www.useloom.com/get-started](https://www.useloom.com/get-started) and scrolling down to the bottom of the page.

![](images/referral-link.png)

### Configuring Loom
To activate Loom on any page, click the extension icon.

![](images/activate-extension.png)

#### Configure Capture Settings
![](images/camera-settings.png)

#### Configure Mic settings

![](images/mic-settings.png)
#### Disable Webcam

![](images/camera-settings%201.png)

## Record a Video
Once you’ve configured Loom, you’re ready to start recording your testing sessions.    As you may have guessed, clicking the big red **Start Recording** button will  in fact start recording all of the interaction on your browser / desktop (depending on your capture settings above).   

When recording is active, you’ll see the icons as indicated below.   

![](images/recording.png)

When you have adequately captured the unexpected behavior you’re reporting, clicking the ✔︎ icon will save the video and redirect you to a page where you can view the video you just recorded.


![](images/post-recording.png)

You’ll notice a few text boxes on the screen for leaving comments and descriptions and such.   Please leave these blank.   Instead what you want to do is file a bug report and Trello and link to this video.    The Trello / Loom integration makes this a simple process as described below.

## Submitting a Bug Report to Trello
Bug reports are being tracked  in a [Trello](https://trello.com) board.    You should have received an invite to your rockitrecruiting.com email address inviting you to the project.   If you have not, please reach out to Cedric to receive an invite.  And if you have never used Trello before, it’s super easy and intuitive to use and they have great content on how to get started.    Please see Noah or Jane for an accelerated primer.

To get started, go to the  [letsrockit.co issues Trello board](https://trello.com/b/mfQTyZkd/issues) and login.    Upon doing so, you should see something like…

![](images/trello.png)

The screen is divided into 6 columns.   As a tester, you will only ever be adding new items (what Trello calls “Cards”) to the **New** column.    The rest
of the columns represent a workflow for addressing the issue to completion and for the most part, you can completely ignore them.

### Step 1:  Add a Card

Clicking **Add a card*** in the **New** column.

![](images/add-new.png)

In the subsequently revealed text field, write a short (< 150 characters)
description of the issue and click **Add**

![](images/add-new-2.png)

After adding, you’ll see this.   

![](images/add-new-3.png)

As indicated above, click the newly created card to edit it and add more detail.  When you do, a window pops up and in it you can add a more detailed description, among other things.    For now, all we care about is attaching our video to the new card.   Clicking the description field reveals
the Loom icon, which gives us access to our videos through a handy little embedded UI.

![](images/add-new-loom-icon.png)

When you hover over the Loom icon, it expands and reveals an (…) icon and when you click that, a menu  drops down.   The first option, **My Most Recent Recording** will attach and embed your video to the card.   

![](images/add-new-attach-video.png)

After attaching the video, you’ll notice Loom has automatically inserted the link to your video into the text field.    This is expected.   Click **Save**.

![](images/add-new-post-attach.png)

Upon saving, you’ll see that the video is now viewable directly in Trello, which is exactly what we want.   

![](images/add-new-post-attach-2.png)

### Step 2:  Fill out Bug Report Template

You may have noticed in the previous screen shots that there is a card sitting at the top of the **New** column called **Bug Report Template**.    This card’s description contains a text-based “form” that asks a few simple questions, the answers to which will help us determine how to address your issue.    Expanding the card reveals its contents:

![](images/bug-report-template.png)

And clicking on the description field, reveals an editable version of the template.   Select all of the content in that text field and copy it to your clipboard.   

![](images/bug-report-template-editable.png)

Next, go back to the card you just created and edit the description.   Your Loom link should still be there.   Paste the bug report template  just above the Loom link.  Then, in the **Steps to Reproduce** section, delete the instructional / placeholder text and cut / paste the Loom link there.   If you did not take a video, then please write out the steps you took instead.

With those steps complete, please fill out the other sections of the template.   When you are done, click **Save**, and that’s it.   You have successfully submitted a bug report, and I thank you for doing it!
