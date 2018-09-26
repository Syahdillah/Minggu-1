# Minggu-1
Cara install Python pada windows 10 dan Pengaturan Environment Variables.
Langkah pertama yang harus dilakukan yaitu :
1. Download dulu python versi 3.6.3 terbaru
   https://www.python.org/downloads/
2. instal (run/double klik seperti biasa).
   Ketika keluar opsi pemilihan path installer biarkan terinstall pada root C. “C:\Python36”
   selanjutnya ikuti proses install sampai selesai.
3. Setelah selesai test dulu apakah sudah berjalan dengan baik atau belum,
   buka cmd/Command Prompt dan ketik “python”  tanpa tanda petik
   biasanya python belum dikenali (not recognized) karena path nya tidak ketemu/dikenali oleh    windows.
   SOLUSI :
   Pengaturan Environment Variables.
   - Masuk ke system pada Control Panel
   Control Panel\System and Security\System
   - Kemudian klik   “Advanced system settings“
   - Lanjut klik “Environment Variables” maka akan muncul lagi pop up “Environment Variables”
   - Pada bagian System variables, scroll sampai ketemu Path. (Path adalah nama Variable)
   - Seleksi/klik Path dan kemudian klik Edit
   - Maka akan muncul lagi pop up “Edit System variable”
     sebelum mengedit Variable value bikin dulu backup untuk mencegah hal2 yang diluar dugaan,
     buka notepad copas semua Variable value.
   - Pada bagian paling kanan/ujung “Variable value”
     tambahkan path  “;C:\Python36\”  tanpa tanda petik
     dan klik OK pada jendela Edit System variable.
     klik OK pada jendela Environment Variables.
     klik OK pada jendela System Properties.
     dan close Control Panel.
