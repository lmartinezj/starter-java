# Welcome to the Java Starter!

This project is pre-configured to have some interesting functionality built in using the Twilio Java helper library and the [Play Framework](http://www.playframework.com/).

## Setting Up

As a first step, you should [download this project](https://github.com/Beans0063/starter-java), or clone it if you are a Git user.  Navigate to the directory for this project, and open it with your favorite text editor.

Rename the file `{project root}/conf/application.conf.sample` to `{project root}/conf/application.conf`.  Open this file and locate the following three lines of configuration:

    twilio.accountSid="CHANGE_ME"
    twilio.authToken="CHANGE_ME"
    twilio.number="CHANGE_ME"

These values inside quotation marks will need to be replaced with the following information from your Twilio account:

* `twilio.accountSid` : Your Twilio "account SID" - it's like your username for the Twilio API.  This and the auth token (below) can be found [on your account dashboard](https://www.twilio.com/user/account).
* `twilio.authToken` : Your Twilio "auth token" - it's your password for the Twilio API.  This and the account SID (above) can be found [on your account dashboard](https://www.twilio.com/user/account).
* `twilio.number` : A Twilio number that you own, that can be used for making calls and sending messages.  You can find a list of phone numbers you control (and buy another one, if necessary) [in the account portal](https://www.twilio.com/user/account/phone-numbers/incoming).

Now that our project is ready, we need to [download and install the Play Framework](https://www.playframework.com/documentation/2.4.x/Installing) following the instructions on their web site.  Once the activator command has downloaded dependencies, and is available on your system path, navigate to your project's directory in a terminal window.

## Running the Application
To run the application, we first need to start a Play console session.  To start the Play console, navigate to the starter project directory in a Terminal and use the command `activator`.

To run the application, enter the command `run`.  This will download dependencies and start a local HTTP server [running on port 9000](http://localhost:9000/) on your computer:

![run command](https://dl.dropboxusercontent.com/u/11489766/twilio/starter-java_%E2%80%94_java_%E2%80%94_212%C3%9759.png)

When you vist [http://localhost:9000/](http://localhost:9000/) in a web browser, you should see a page UI.

Try out the text message and voice call demos by entering your mobile phone number and clicking the button.  If you receive a text message and a call, everything is working!

## Begin Learning Twilio!
This is your first step into the Twilio learning program.  Return to the site to continue on.  Huzzah!
