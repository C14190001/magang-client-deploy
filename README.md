# Client untuk Magang
## Catatan
- LogOff akan dianggap status OFF.
- Memerlukan `ServerConfig.txt` yang berisikan (per baris): `IP Server, Port Database, Nama Database, Username Database, Password Database`.
- `VC_redist.x64.exe` diperlukan jika tidak ada `Visual C++ Redistributable` dalam Client.

## Instalasi
1. Buat `ServerConfig.txt` yang berisikan (per baris): `IP Server, Port Database, Nama Database, Username Database, Password Database`.
2. Jalankan `ClientSetup.exe`, pilih `Existing PC` jika Client sebelumnya sudah ada di Database atau `New PC` jika Client tidak ada di Database.
3. Buat Shortcut dari `ClientGUI.exe` di folder Startup.
4. Restart PC Client (Supaya program `Client GUI` dapat berjalan).
