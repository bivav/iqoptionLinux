### Prerequisites:
1. Install wine stable:
```sudo apt-get update```
```sudo apt install wine-stable```
```sudo apt-get install --install-recommends winehq-stable```
2. Make Wine Default for launching **.exe** files.


### Installing IQOption.exe in Linux
1. Download msitools-0.100 or later
[msitools-0.100 download](http://ftp.gnome.org/pub/GNOME/sources/msitools/0.100/msitools-0.100.tar.xz)

2. Download **IQOption MSI** file from IQOption website.
3. Extract the file and cd to the extracted directory
4. Run following commands inside the directory one by one.
```
./configure
make
make install
```
Note: If you get library error while ./configure or make, try installing 'dev' versions for libraries like below:
```
sudo apt install libgcab-dev
sudo apt install uuid-dev
sudo apt install libgsf-1-dev
```
and so on..

5. After completion of "make install", Execute ```msiextract IQOption.msi```
6. It will create "Program Files/IQOption" directory with all exe files.
7. Enjoy!
