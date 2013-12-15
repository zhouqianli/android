#Android Learning Project

***

##How to create a android development environment (Windows)
1. Download ADT from [Google Android developer center].
1. Update java.exe path on adt-bundle-windows\sdk\tools\android.bat to the real path on your machine.  For example:<br/>
    `set java_exe=C:\Program Files\Java\jdk1.7.0_45\bin\java.exe`<br/>
    `rem call lib\find_java.bat`<br/>
1. Open Android SDK Manager and install *Extras/Android Support Repository*.
1. Setup IntelliJ IDEA from [JetBrains].
1. Setup fast Android simulator from [GenyMotion].
1. Install [GenyMotion] plugin on IntelliJ IDEA.
1. Install [Cygwin].  (Remember add bash-completion package when select features)
1. Setup [GoAgent].
1. Install useful GUI tool [SourceTree].  It is a good replacement of Git plugin on IDEA, you can do most of Git related operation on this GUI tool.


[Google Android developer center]:http://developer.android.com/sdk/index.html
[JetBrains]:http://www.jetbrains.com/idea/download/
[GenyMotion]:http://www.genymotion.com/
[Cygwin]:http://cygwin.com/install.html
[GoAgent]:https://code.google.com/p/goagent/
[SourceTree]:http://www.sourcetreeapp.com/download/