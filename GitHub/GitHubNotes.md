# Introduction
I did NOT find it all that easy.  Even, after watching several videos and creating a GitHub account.  I want to fill in some of those details.  I particularly want to expain it's use with **PyCharm** and the **UV environment manager** [UV site](https://docs.astral.sh/uv/pip/environments/).    I will focus on my particular work flow.

My friends call me **biG**  (my enemies should NOT call me!) My daily driver OS on my PC is **MX_LINUX** and I use a very abbreviated cursur for the terminal command line: **">"**.  Yep, without any space after it.

# Create GitHub account & initial settings
Well, I don't remember how I actually created it. Here is [biG's GitHub](https://github.com/RichardGoodrich/).  I *Bookmark* it. I also *bookmark* my [repo link](https://github.com/RichardGoodrich?tab=repositories).  (Sometimes I can't seem to get back to it from within certain pages within GitHub?).

*Login* by your **email** or by your **user name**.  I created my login name as: "Richard Goodrich".  However, in use the space is removed to render:  **RichardGoodrich**.  Use a **password management** system to record the details. There are several details **NOT** to forget!  An entry should look something like this:

```
link:    https://github.com/RichardGoodrich
login:  [USER NAME] | [EMAIL]
pwd:    [PWD]
token:  [TOKEN]
```
I stay logged in most of the time.  That may NOT be a good idea!  I get a lot of **SPAM** because of it.  You can login with your [USER NAME] or [EMAIL].  I like to use my [USER NAME].  However, in using GitHub it demands your [EMAIL].  **MOST IMPORTANTLY**, if you want to actually **use** your account you **MUST** create a **TOKEN** and tweak the settings.  GitHub quit allowing use of your **PWD**.

There are two sets of setting that confused me!  There is the **USER ICON** settings found under that top right widget.  I loaded a **PNG** file of myself to make that clear.  Then there is a settings menu on a specific respository page.  Call that the **REPO SETTINGS**. Don't confuse these two!

### token
First get that **token** and record it.  It will disappear from even GitHub.  Watch the video from **References** [1].  Paricularly the short segment on "create token"

```
[USER ICON] - settings - <> developer settings - Personal access tokens -
Tokens (classic) - Generate new token dropdown - Generate new token (classic) -
New Note (write something: "biGtoken") - Expiration dropdown - No Expiration (there are other choices) -
Select Scopes - just check **repo** - push "green" Generate Token -
(copy it - there is a copy icon after it)

Coming back to this path will only allow you to see the name you created in "New Note" and
change some of the token settings or add a new one, etc.
```
### email seeting - Privacy etc.
You need an email setting.  However, you may NOT want it exposed to the 'world"  For a while I did.  I got a lot of spam.  However, if you make it private (without tweaking) you can't work with your respositories from your PC.  My workflow is to work with them from the comand line. (versus say from within PyCharm IDE).  There is more control and flexibility this way.  Tweak those settings.  There is a setting for keeping your email private.  I recommend that.  Do it and there is an additional setting.

```
[USER ICON] - settings - Emails

Scroll to the bottom.   "Keep my email settings private"  On/Off slider to ON
Now an additional On/Off slider appears:  Turn OFF: "Block command line pushes that expose my email"

Push **SAVE** button at bottom.
```
### Public Profile
[USER ICON] - settings - Public Profile.  You should be able to tweak this to your liking.

### Action Settings for a specific repo
Now go to a specific repository.  The default for a new respository is to have the Action workflow to be read only.  If you
want to push and pull from it, tweak as follows:

```
Go to that specific repository.  Choose the settings dropdown across the top. On the left side:
Open the **Actions** dropdown and choose **General**  Scroll to the bottom under the section:
**Work permission** the default choice is:  **Read repository contents and package permission contents**
Uncheck that one and choose: **Read and Write permission**

Push **SAVE** button at bottom.
```
### Other Settings
A lot of other things to set.  I just don't know what those might be!  This should get you started.

# Making a Repository
Yes, there is no way to do this remotely in my workflow.  It starts with creating one on GitHub.

todo - the details

# Workflow
This is the everyday stuff.  That first part is very tricky though.  MUST get it right first or this is an NON Starter.

todo - A lot of Corey Schafer suff here.

# References
### [1]  How to Push Code to GitHub on the Command Line (2024 updated) - with Authentication
**Infinite Codes** Apr 7, 2024 [YouTube](https://youtu.be/G7vMhsTUzWI)
create token: 01:50 to 02:50


