<html>

<body>
<h1>2D BOY's Boy Framework</h1>

<h3>Overview</h3>


This is a trimmed down and slightly modified version of the framework
used in the
creation of World of Goo. &nbsp;It is provided as is, without any
license or warranty. &nbsp;If it destroys your life in any way,
don't
come crying to us. &nbsp;It has bugs, it's a little hacky in
places,
and it is severly lacking in style and functionality in some areas.
&nbsp;This code is unsupported, so please don't send us questions
about it.
Like a bad horoscope, it's for entertainment purposes only. There's a
new section in our forums called Boy Framework where
you can discuss this framework with others.<br>


<br>


On a more positive note, it does fulfill one basic need well:
&nbsp;it was build with rapid prototyping of 2D games in mind and
tries to minimize the amount of non-game setup work required to get
something running. &nbsp;All the stuff that 99.9% of 2D games have
in
common has been pulled out into this reusable framework.
&nbsp;It&nbsp;can render 2D graphics, read input from a variety
of
devices, and play sounds. &nbsp;It includes a resource manager for
loading/unloading resources, a
persistence layer for saving game state, and even a file access
abstraction. &nbsp;Two demos are included. &nbsp;One
illustrates a
minimalistic use of the framework (demo1) and the other is a quick
remake of the classic arcade game Asteroids made in 12 hours (demo2).<br>


<br>


We hope this inspires people to play around with new ideas and saves
them the annoyance of having to reinvent the wheel. &nbsp;If you
make
something cool, we encourage you to post it to our forum and share the
joy!<br>


<h3>Setup Instructions</h3>


<ol>


  <li>Unzip framework.zip into a new folder (I'll call this
folder <root> from this point on)</root></li>


  <li><root>Download irrKlang version 1.1.0 from here:
    <a href="http://www.ambiera.com/irrklang/downloads.html">http://www.ambiera.com/irrklang/downloads.html</a>.
Newer versions will
probably work too, but you'd have to update the paths in your project
if you want to use one. IMPORTANT NOTE: irrKlang is not free if you
intend to use it for commercial purposes.</root></li>


  <li><root>Unzip irrKlang-1.1.0.zip into <root>/libs.
It will create a direcory called irrKlang-1.1.0.</root></root></li>


  <li><root><root>Copy <root>&lt;root&gt;/libs/irrKlang-1.1.0/bin/win32-visualStudio/irrKlang.dll
into </root></root></root>&lt;root&gt;<root><root><root><root>/demo1
and <root></root></root></root></root></root>&lt;root&gt;<root><root><root><root><root>/demo2
(or add the above
directory to your path so that the demos can find the irrKlang dll)</root></root></root></root></root></li>


  <li><root><root><root><root><root>Run
    <root></root></root></root></root></root></root>&lt;root&gt;<root><root><root><root><root><root>/libs/dxsdk/200806/Redist/DXSetup.exe.
This will install the DirectX runtime version required by the
framework. Alternatively, you can just find yourself a copy of
d3dx9_38.dll and put a copy of it in the demo1 and demo2 directories.</root></root></root></root></root></root></li>


  <li><root><root><root><root><root><root>Start
up the Visual Studio solution &lt;root&gt;/2dboy.sln (requires Visual
Studio 2008)</root></root></root></root></root></root></li>


  <li><root><root><root><root><root><root>Build
and run!</root></root></root></root></root></root></li>


</ol>
<h3>Misc Notes</h3>
<ul>
  <li>You can create your own fonts for use in
your games. &nbsp;the font file format is that used by the Popcap
framework, which comes with a font builder tool. &nbsp;The resource
manifest (resource.xml) also uses a simpliefied version of the format
available in the Popcap Framework.</li>
  <li>Demo1 requires a dualshock style game controller (it simply does nothing without one)</li>
  <li>There is no documentation for this framework. &nbsp;There are
inline comments that should help you if you're looking at the innards.</li>
  <li>You can find PopCap Framework tools <a href="https://github.com/MlgmXyysd/PopCap-Games-Open-Source#tools">here</a>.</li>
</ul>


</body>
</html>

