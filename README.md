# Control-Centre
A nice Control Centre that looks like macOS Big Sur Control Centre

## Screenshots :)
![Dark mode](Screenshots/dark_centre.png)
Dark mode

![Light mode](Screenshots/light_centre.png)
Light mode

## Dependencies

   - install gambas3 package
   ```sh
   $ sudo apt-get install gambas3 -y
   ```

## Installation steps
 - From Source:

   - clone the project
   ```sh
   git clone https://github.com/alxb421/system-overview
   ```
   - Open gambas3 application (from terminal `$ gambas3`, or from application dashboard, search for gambas3)
   - Click `Open`
   - Navigate to cloned folder, and open the project
   - Click on `Project` > `Make` > `executable`
   - copy the new executable in the `/usr/bin` folder of your Linux machine
   - Enjoy :p

 - From Package:
   - Download the .deb package from `Releases` tab here, in GitHub
   - Install using gdebi/ dpkg
   ```sh
   $ sudo dpkg -i <path to downloaded deb file, or drag and drop>
   ```
