
### Installing IQOption.exe in Linux

1. Download msitools-0.100 or later
	[msitools-0.100 download](http://ftp.gnome.org/pub/GNOME/sources/msitools/0.100/msitools-0.100.tar.xz)
2. Extract the file
3. Run following commands inside the directory
```
	./configure
	make
	make install

	Note: If you get library error while ./configure, install dev versions like:

	sudo apt install libgcab-dev
	sudo apt install uuid-dev
	sudo apt install libgsf-1-dev
```
and so on..

4. msiextract IQOption.msi
5. It will create "Program Files/IQOption" directory with all exe files.
6. Enjoy!
