Tinymice is a simple auto clicker for linux that support profiles.
I don't have any plan to support a windows version but if you remove codebotctrls from the dependency, 
it can also be compiled for windows.
This software need Sqlite. To avoid libsqlite3.so error, you need to install libsqlite3-dev.

License:

	GPL V3

Ubuntu users:

	sudo apt-get install libsqlite3-dev


Linux dependency(tested with Linux Mint XFCE 19.3)

Compile:

	Lazarus 2.0.6
	FPC 3.0.4
	Cross.Codebot 
	libxtst-dev
	libgl-dev
  
Execute:

	libsqlite3-dev


External Download:

	Lazarus && FPC: https://sourceforge.net/projects/lazarus/files/
	Cross.Codebot:	https://github.com/sysrpl/Cross.Codebot
	Sqlite:	https://www.sqlite.org/download.html

