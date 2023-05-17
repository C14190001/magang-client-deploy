# Client untuk Magang
## Catatan
- LogOff akan dianggap status OFF.
- Memerlukan `ServerConfig.txt` yang berisikan (per baris): `IP Server, Port Database, Nama Database, Username Database, Password Database`.
- `VC_redist.x64.exe` diperlukan jika tidak ada `Visual C++ Redistributable` dalam Client.

## Instalasi
1. `Download ZIP` lalu *extract* ke tujuan yang diinginkan (*misal C:\CLientGUI*).
2. Buat `ServerConfig.txt` yang berisikan (per baris): `IP Server, Port Database, Nama Database, Username Database, Password Database`.
3. Jalankan `ClientSetup.exe`, pilih `Existing PC` jika Client sebelumnya sudah ada di Database atau `New PC` jika Client tidak ada di Database.
4. Buat Shortcut dari `ClientGUI.exe` di folder `Startup` di PC Client.
5. Restart PC Client (Supaya program `Client GUI` dapat berjalan).
