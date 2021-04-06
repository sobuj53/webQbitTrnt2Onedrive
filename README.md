[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github.com/sobuj53/webQbitTrnt2Onedrive/blob/main/WebQbittorrent_2_Onedrive.ipynb)

# webQbitTrnt2Onedrive
Using power of colab to torrent with powerful web interface of qbittorrent directly to OneDrive

The use of this notebook very straightforward. Download `WebQbittorrent_2_Onedrive.ipynb` and import it to Gdrive, then open it using Google colaboratory. It only requires 5 arguments, `rclone.conf` 1st Create a Rclone cofig offline. You may watch this video https://www.youtube.com/watch?v=T6MN009EB1M to know more. Set `rclone_config_name` = the name you used during config creation, eg `onedrive`, `local_mount_location` = `./onedrive`, `savePath` = `./<local_mount_location>/<dl_folder_name>/` and `ngrok_Token`. Specify your personal Authtoken that you have acquired from https://ngrok.com/ in `ngrok_Token` field.

After running 1, 2, and 4 field, you'll get a link for web UI of qbittorrent as output, like `https://*.ngrok.io` you'll need to copy that link and open it in a separate tab, direct click won't work. Once it is opened, it's not mandatory to have the colab tab opened while torrenting using webUI.

##
It's only for educational purposes and meant to help you for downloading legal content. You're solely responsible for your actions and usages of this notebook.  
DO NOT ABUSE OR ELSE YOUR ACCOUNT MIGHT BE BANNED ¯\_(ツ)_/¯. 
