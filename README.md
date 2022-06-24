
Displays Inodes usage summary for a cPanel account.

<!--img src="https://raw.githubusercontent.com/stefanpejcic/inodes-usage-summary-cPanel-plugin/main/assets/img/screenshoot.png"></img-->

### Features

- displays inodes usage and size for each folder/file in cpšanel user home directory


### TO DO

- path to the script is hardcoded: /usr/local/cpanel/base/frontend/paper_lantern/inodes/./inodes
- cpanel user root directory is /home + username 
- 

### How to install the plugin

To install this free cpanel plugin you need access to the WHM and terminal. Login to SSH and run the following commands to install the plugin:


- PaperLatern theme:

`wget https://github.com/stefanpejcic/lastlogin-cpanel-plugin/archive/refs/heads/main.zip`
`unzip main.zip`
`/bin/cp lastlogin-cpanel-plugin-main -R /usr/local/cpanel/base/frontend/paper_lantern/lastlogin`
`/usr/local/cpanel/scripts/install_plugin /usr/local/cpanel/base/frontend/jupiter/lastlogin/info.json`

- Jupiter theme:

`wget https://github.com/stefanpejcic/lastlogin-cpanel-plugin/archive/refs/heads/main.zip`
`unzip main.zip`
`/bin/cp lastlogin-cpanel-plugin-main  -R /usr/local/cpanel/base/frontend/jupiter/lastlogin/`
`/usr/local/cpanel/scripts/install_plugin /usr/local/cpanel/base/frontend/jupiter/lastlogin/info.json`


### Changelog

#### v1.0.0
Released: June 23th, 2022

Stable Release

### Support

Because this is a free plugin, support is restricted to maintaining the source code and ensuring that the plugin functions on latest cPanel version.

Please see the additional services area below if you require assistance outside of this scope, such as with plugin installation, branding, or integrating it with your custom template.

### Whats next

In the next couple of months we're going to continue to improve the docs, create tutorials and fix bugs.

### Contribute

You can support me by giving [a GitHub star ★](https://github.com/stefanpejcic/lastlogin-cpanel-plugin/stargazers) and spread the word :)
