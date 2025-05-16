<div align="center">
  <h1>Collection of commonly white listed domains for <br> Pi-Hole®</h1> 
</div>

</div>
<div align="center">
  
A robust collection of commonly white listed websites borrowed from various sources including Pi-Hole subreddit, Pi-Hole forum, Pi-Hole GitHub repository and more!
Add these domains to your Pi-Hole setup by running a script or manually and make your setup __trouble-free!__
Want to report a new domain? Want to report existing one? Feel free to file an [issue](https://github.com/anudeepND/whitelist/issues).

</div>

<div align="center">
  <h3>
    <a href="https://github.com/anudeepND/whitelist/releases">
      Releases
    </a>
    <span> | </span>
    <a href="https://github.com/anudeepND/whitelist/pulse/monthly">
      Pulse
    </a>
    <span> | </span>
    <a href="https://github.com/anudeepND/whitelist/issues">
      Submit Issue
    </a>
    <span> | </span>
    <a href="https://github.com/anudeepND/whitelist/pulls">
      Submit PR
    </a>
    <span> | </span>
    <a href="https://www.paypal.com/paypalme/anudeepND">
      Donate
    </a>
  </h3>
</div>       
&nbsp;

<br />

![Whitelist install demo gif](https://raw.githubusercontent.com/anudeepND/whitelist/master/images/whitelist.gif)

<br />

## <ins>Table of contents</ins>
- [Features](#features)
- [Overview](#overview)
- [Installation](#installation)
  * [For whitelist.txt](#for-whitelisttxt)
  * [For referral-sites.txt](#for-referral-sitestxt)
  * [For optional-list.txt](#for-optional-listtxt)
  * [For Docker installation (with Python3 support)](#for-docker-installation-with-python3-support)
  * [For Docker installation (without Python3 support) or /etc/pihole on different directory](#for-docker-installation-without-python3-support-or-etcpihole-on-different-directory)
- [Uninstall](#uninstall)
- [Automated Update](#automated-update)
- [How do I determine an ad domain?](#how-do-i-determine-an-ad-domain)
- [Stargazers over time ](#stargazers-over-time)
- [Support](#support)
- [License ](#license)

## <ins>Features</ins>

- The entire repo is curated.
- New domains are added frequently.
- Supports Pi-Hole Docker installation.
- Comes with a simple install/uninstall scripts i.e. you can add all domains with comments automatically at an instant.
- Domains are categorized and are included in 3 different files.
- All the domains will have comments to let you know about the domain.
- If you are a beginner to Pi-Hole, adding these sites will solve issues with host files that block legit websites.

## <ins>Overview</ins>
  <br />

| File Name | Domain Count | Description | Update Frequency | Raw Link |
|:-:|:-:|:-:|:-:|:-:|
| whitelist.txt | 191 | This file contain domains that are __safe__ to whitelist i.e. it does not contain any tracking or advertising sites. Adding this file fixes many problems like YouTube watch history, videos on news sites and so on. If you want to report additional domain feel free to file an [issue](https://github.com/anudeepND/whitelist/issues). | Occasionally | [link](https://raw.githubusercontent.com/anudeepND/whitelist/master/domains/whitelist.txt) |
| referral-sites.txt | 75 | People who use services like Slickdeals and Fatwallet needs a few sites (most of  them are either trackers or ads) to be whitelisted to work properly. This file contains some analytics and ad serving sites like __doubleclick.net__ and others. __If you don't know what these services are, stay away from this list.__ | Occasionally | [link](https://raw.githubusercontent.com/anudeepND/whitelist/master/domains/referral-sites.txt) |
| optional-list.txt | -- | This file contain domains that are needed to be whitelisted depending on the service you use. It may contain some tracking site but sometimes it's necessary to add bad domains to make a few services to work. Currently there is no script for this list, you have to add domains manually to your Pi-Hole. | Occasionally | [link](https://raw.githubusercontent.com/anudeepND/whitelist/master/domains/optional-list.txt) |
