If connecting to Plex on a different server follow the steps outlined https://support.plex.tv/articles/200288586-installation/. Specifically
1. Open a Terminal window or your command prompt
2. Enter the following command (substituting the IP address of your server as appropriate):
3. ssh -L 8888:127.0.0.1:32400 ip.address.of.server
4. Open a browser window
5. Type http://127.0.0.1:8888/web into the address bar
6. The browser will connect to the server as if it were local and load Plex Web App
