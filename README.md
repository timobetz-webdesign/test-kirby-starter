# Install and configuration of developement envoirement

## Clone Kirby Repo

1. Go to Github and login
2. Click the "Use this template" Button and create a new Repo
3. open "GitKraken" and clone repo from GitHub account

## Download, load CSS and install packages for SASS

4. create assets folder in project folder 
5. Download bulma-start npm package from
https://github.com/jgthms/bulma-start/releases/download/0.0.3/bulma-start-0.0.3.zip
6. unzip and copy files/folders into assets folder 
7. open terminal and move to assets folder
8. run in terminal: npm install
9. run in terminal: npm start

## Install and activate BrowserSync

10. open new terminal and move to project folder
11. run in terminal: npm install browser-sync --save-dev
12. start MAMP and apache server
13. run in terminal: browser-sync start --proxy "http://localhost:8888" --files "**/*"

# Kirby Plainkit

Kirby is a file-based CMS.
Easy to setup. Easy to use. Flexible as hell.

## Trial

You can try Kirby on your local machine or on a test
server as long as you need to make sure it is the right
tool for your next project.

## Buy a license

You can purchase your Kirby license at
<https://getkirby.com/buy>

A Kirby license is valid for a single domain. You can find
Kirby's license agreement here: <https://getkirby.com/license>

## The Plainkit

Kirby's Plainkit is the most minimal setup you can get started with.
It does not include any content, styles or other kinds of decoration,
so it's perfect to use this as a starting point for your own project.

## The Panel

You can find the login for Kirby's admin interface at
http://yourdomain.com/panel. You will be guided through the signup
process for your first user, when you visit the panel
for the first time.

## Installation

Kirby does not require a database, which makes it very easy to
install. Just copy Kirby's files to your server and visit the
URL for your website in the browser.

**Please check if the invisible .htaccess file has been
copied to your server correctly**

### Requirements

Kirby runs on PHP 7.1+, Apache or Nginx.

### Download

You can download the latest version of the Plainkit
from https://github.com/getkirby/plainkit/archive/master.zip

### With Git

If you are familiar with Git, you can clone Kirby's
Plainkit repository from Github.

    git clone https://github.com/getkirby/plainkit.git

## Documentation

<https://getkirby.com/docs>

## Issues

If you have a Github account, please report issues
directly on Github: <https://github.com/getkirby/kirby/issues>

Otherwise you can use Kirby's forum: https://forum.getkirby.com
or send us an email: <support@getkirby.com>

## Ideas & Feature Requests

If you have ideas for new features, please submit a ticket in our ideas repository:
<https://github.com/getkirby/kirby/ideas>

## Support

<https://getkirby.com/support>

## Copyright

© 2009-2019 Bastian Allgeier (Bastian Allgeier GmbH)
<https://getkirby.com>
