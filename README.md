# Bug-Player
A local audio player for Windows 11. Black background, white Courier New font, and music from your folders. No registration, ads, or analytics.

<img width="1519" height="789" alt="Bug Player" src="https://github.com/user-attachments/assets/b62301e9-ffdf-4ccb-8777-092412c1577d" />

 # What It Can Do
- Load songs, folders (including subfolders), and M3U, M3U8, PLS, and XSPF playlists.
- Play songs sequentially, pause them, adjust the volume, and skip through supported files.
- Display the song duration, elapsed time, and remaining time of the playlist.
- Select multiple songs and save the selection or the entire playlist as an M3U8 file.
- Continue playback after minimizing the window to the Windows notification area.
- Pin the window on top of other windows, lock its position, and optionally start it with Windows.
- Restore the playlist, volume, window position, and last-used directory.

<img width="911" height="148" alt="Bug_Player_2" src="https://github.com/user-attachments/assets/14455ea8-1edd-4a06-9566-42c23eea0db7" />

 # Formats and Limitations
Supported file formats include, for example, MP3, WAV, FLAC, OGG, Opus, M4A, AAC, WMA, and AIFF. Audio is handled by Qt Multimedia. Actual playback capability depends on the codec, the file, and the available multimedia backend; the file extension alone does not guarantee it. Support for all formats, DRM, or corrupted files cannot be guaranteed.

Playlists support both relative and absolute file paths. Web addresses and nested playlists are not played. M3U8 export uses UTF-8 and absolute paths: a playlist may reveal folder names, and after being moved to another computer, the paths may need to be adjusted. The program does not provide internet radio, a cloud library, or an audio file editor.

 # Privacy
Bug Player does not send music, playlists, or settings to the developer. Files on the local disk can be played without an internet connection. Selecting network or synchronized storage may utilize the relevant external service.
Settings and paths to songs are stored in %APPDATA%\Bug Player\settings.ini. The “Start with Windows” option writes a BugPlayer entry to the current user’s registry. Disable this option before moving the program, and re-enable it after moving it.
Details and instructions for deleting stored data: [Privacy Policy](https://jxd.cz/code-is-poetry/bug-player/bug-player-privacy-policy/)

<img width="432" height="652" alt="Bug_Player_3" src="https://github.com/user-attachments/assets/07f27fb7-c1b6-4e3d-a3ff-3eb7cb567ea5" />

 # Credits
Software © [Jiri X. Dolezal](mailto:jxd@jxd.cz) Photo of the beetle: © [Jaroslav M. Soukup](mailto:jsoukup1@seznam.cz)

 # Contact
 ## [jxd.cz](https://jxd.cz)  [jxd@jxd.cz](mailto:jxd@jxd.cz)
 
 <img width="500" height="500" alt="JXD VibeLabs_white_500" src="https://github.com/user-attachments/assets/f44f76da-b1ef-4474-87ac-ba43e3b61730" />

 
