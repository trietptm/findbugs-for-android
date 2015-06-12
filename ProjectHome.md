Findbugs plugin for Android specific coding.

[Findbugs](http://findbugs.sourceforge.net/) is a static code analysis tool for standard Java. This adds detector for Android specific coding to it. You can find error on the source code of Android specific coding. You can use it through Eclipse Findbugs plugin or standalone Findbugs GUI.

Download is available in [here](https://drive.google.com/folderview?id=0B5f_w66hl8tZVXZJSUN0dnNUaUU&usp=sharing).

# How to use it #
## With Eclipse ##
Install Findbugs plugin to Eclipse (For installation of Findbugs Eclipse plugin, please refer to [here](http://findbugs.cs.umd.edu/eclipse/)), download [jar file](https://drive.google.com/file/d/0B5f_w66hl8tZVnAwN2hzalZLa1E/edit?usp=sharing) and put it into
```
<path-of-eclipse>\plugins\edu.umd.cs.findbugs.plugin.eclipse_***\plugin
```
## With Standalone Findbugs ##
Download [jar file](https://drive.google.com/file/d/0B5f_w66hl8tZVnAwN2hzalZLa1E/edit?usp=sharing) and put it into
```
<path-of-findbugs>\plugin
```
Note that looks like Findbugs 2.0.0 is not able to dispatch plugin on text ui or standalone GUI. This detector does not work with CUI so far.

# Available Detectors #
ANDROID\_UNCLOSED\_CURSOR: Un-closed Cursor instance of Android

ANDROID\_OPEN\_STREAM: Un-closed stream of Android