THE GCA 
=============

This is the repository for the GCA App, procedures for installation and contribution are below:

0. In order to work on the GCA there are several [software requirements](#software requirements).
0. [Install](#installation) the app for local development.
0. Work can be carried out and branches started, for an explination of GitHub Branches see[GitHub procedures](#github procedures).

Software Requirements
-------

The following software is required.  Note these items may require there own dependencies.

* [Ionic](http://http://ionicframework.com/)
* Some kind of IDE, I recommend [Sublime Text](http://www.sublimetext.com/)
* In order to test the build on a device emulator (optional) you require [Xcode](https://developer.apple.com/xcode/) or [Android Studio](https://developer.android.com/sdk/index.html)

Installation
-----------
With the above software installed:

0. Create a local directory for you project.
0. Open your command line interface and enter directory.
```
git clone https://github.com/parrotfarter/GCA.git
```
With Ionic installed you are able to run command:
```
ionic
```
This displays options for running the App.

For more info read the [documentation](http://docs.ionic.io/)

Github Procedures
-----

In order to keep edits tidy and in a logical order you should create a branch before uploading to Github. This allows for community reviewing of changes before they are applied to project.

```
git branch testing
```
Where testing can be changed to reflect a relevant branch name. For the duration of this project, the branching convention should be nameFeature. e.g hoggUserchat

For more on using Git and understanding commits see [docs](http://git-scm.com/)
