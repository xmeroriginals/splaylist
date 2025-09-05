If you've downloaded **"ffmpeg"** to your system files, this code will work directly. If not, download the latest version from **"https://www.gyan.dev/ffmpeg/builds/"** and place the **"ffmpeg.exe"** file in the root directory of the **"bin"** folder. **"ffmpeg.exe"** is not included in this project; you'll need to do it manually.


_Note that **"ffmpeg.exe"** is included in the SPlaylist applications in the Releases section._

---

Once everything is ready you can run it and get the exe parts.
```bash
pyinstaller --onefile --windowed --name="SPlaylist" --icon="logo.ico" --add-data "ffmpeg.exe;." splaylist_downloader.py
```
_The output **"SPlaylist.exe"** in the **"dist"** folder will be your prepared application._
