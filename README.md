<img src="github_logo.png"></img>
<br>
<h1>Installation and Use</h1>

Saliibot requires an `API.json` file and `account.json` to run. Both files will be included but will not be populated with information.

<h2>Login to Saliibot Archival Systems</h2>

In order for your instance to submit data to Saliibot it needs to login to the Saliibot Database. This will require you to enter your Saliibot username and password into the 'Username' and 'Password' fields of the `account.json`.

<h2>Login to Social Platform</h2>

As social platforms require different login methods for their APIs to be accessible, you will be required to enter their credentials as they request. The `API.json` file will be populated with the platforms API fields but will not be populated.
You will be required to enter those credentials in order for the bot to access the data hosted on those platforms.

<h2>Containers</h2>

Docker container files will be available with all the programs that are publicly available and will be able to setup a Docker container with all required resources excluding the API and account credentials

<h1>Custom Utilization</h1>

If you are planning on using this bot for your own archives, you may want to take a look at the Saliibot Website and Database repositories. They will be available on the Saliibot account and will have all resources and information required to set them up.

<h1>Requirements and Dependencies</h1>

Saliibot is coded on the Python platform and will require the latest version of Python and PIP to be installed as well as several libraries.

On Debian systems just run this command:

`sudo ./installdebian.sh`

On Mac OS systems (Intel and Apple Silicon) just run this command:

`sudo ./installapple.sh`

On Windows systems just run:

`installwindows.bat`

<h2>To Do:</h2>

-Add filters (Phone number, address and other personally identifiable stuff)

-Clean up code
