# Neighbourhood App

To develop a single-page application featuring a map of your neighborhood or a neighborhood you would like to visit. Then add additional functionality to this application, including: map markers to identify popular locations or places you’d like to visit, a search function to easily discover these locations, and a listview to support simple browsing of all locations.

![picture](https://github.com/Shadmanwaris/Neighbourhood-App/blob/master/images/screenshot.png)

# How to play with the App

1. Open latest Google Chrome on your PC.
2. Click here to open Neighbourhood Map link : https://shadmanwaris.github.io/Neighbourhood-App/
3. Click markers or list items to select a location and retrieve info about it.
4. Use Dropdown menu to filter places based on different category (e.g Restaurant, Museum, Cafe).
5. By default all marker will be displayed.
6. Click green arrow on the top right of the navigation bar to hide/show Sidebar.
7. Click close sign to close the information window that opens.

# About this App

1. All application components render on-screen in a responsive manner.
2. All application components are usable across modern desktop, tablet, and phone browsers.
3. Dropdown menu that filters the map markers and list items to locations matching the selection. Filter function runs error-free.
4. A list-view of location names is provided which displays all locations by default on sidebar , and displays the filtered subset of     locations when a filter is applied.
5. Clicking a location on the list displays unique information about the location, and animates its associated map marker (e.g. bouncing, color change.)
6. List functionality is responsive and runs error free.
7. Map displays all location markers by default, and displays the filtered subset of location markers when a filter is applied.
8. Clicking a marker displays unique information about a location in infoWindow.
9. Markers will animate when clicked (e.g. bouncing, color change.)
10. All data requests are retrieved in an asynchronous manner.

# Setting up Local server :

1. First of all download ngrok.
2. Then to install (On Windows OS), open the .rar file and extract the files from it to a separate folder save ngrok.exe in it and to      run double click the ngrok.exe file.
3. Then go to repo https://github.com/Shadmanwaris/Neighbourhodd-App, clone or download the repository to your local computer to make change to your site for optimisation purpose.
4. Open the folder of your local repo, and copy the ngrok.exe file in it.
5. Now open bash from your current file location.And write following command to start the local server

  ```bash
  $> cd /path/to/your-project-folder
  $> python -m http.server 8080  or python -m SimpleHTTPServer 8080
  ```

6. Now double click to run ngrok.exe from local repo.
7. Type following command to be online from ngrok cmd.

 ```ngrok
  $> ./ngrok http 8080
  ```
8. Now open the browser and type 127.0.0.1:4040 localhost
9. It will provide you with two links, eg. https://d498d579.ngrok.io/ and other http://d498d579.ngrok.io/,please use https link because    it is more secure and safe.
10. Through these link you can check the pagespeed by using your local server.
