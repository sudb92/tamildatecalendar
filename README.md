1. Download file to /suitable/directory/tamildatecalendar
2. In a terminal, run the following:
   ```
   chmod +x /suitable/directory/tamildatecalendar
   sudo cp /suitable/directory/tamildatecalendar /usr/local/bin/ 
   ```
   The first command sets it executable, the second puts it in the default search path for bash executables.
3. An edit I like is to make 'tamildatecalendar' the default command that runs when clicking the desktop clock. Works especially nice with the use of borderless feh as discussed in the program. If using this approach, run
   ```
   sudo apt install feh
   ```
   in a terminal, uncomment the line starting with 'feh' in the file, and comment out the line starting with 'xdg-open' before running step 2 above. 
   
