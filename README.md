# Boxstarter Scripts for SharePoint Development Environment Configuration

Use these configuration files with [Boxstarter](http://boxstarter.org/) and its [web launcher technique](http://boxstarter.org/WebLauncher).


## How to use

Simply open up Internet Explorer and hit "http://boxstarter.org/package/nr/url?" appended with the path to one of the above configuration files (using the raw path). This will kick of the download of an auto-generated installer that will go through and install the components from the configuration file one by one. For example:

*Note:* You may need to disable Internet Explorer Enhanced Security Configuration for this to work.


## Boxstarter Scripts

**dev.txt**: Simple environment script for installing browsers, Fiddler, Notepad++, NodeJS, and change some annoying windows configurations (i.e. disable UAC, enable remote desktop)

	http://boxstarter.org/package/nr/url?https://gist.githubusercontent.com/ScottRoutley/5a9375fc6851f16b9a0e/raw/8d78ec00b6f1b382aae313f398b952ac302f0071/dev-vs2013.txt


** powershell/command promt command ** 

	START http://boxstarter.org/package/nr/url?https://gist.githubusercontent.com/ScottRoutley/5a9375fc6851f16b9a0e/raw/8d78ec00b6f1b382aae313f398b952ac302f0071/dev-vs2013.txt
