# Langkah langkah Setup Django di Windows

1. Pastikan sudah install python
2. Buat folder untuk "belajar_django"
3. Buka CMD, lalu masuk ke folder yang sudah dibuat tadi 
6. (optional)  **python -m pip install --upgrade pip** (untuk upgrade pip) lalu # pip list
7. Gunakan perintah **python -m venv Env** (Env adalah nama folder Virtual Environment yang akan dibuat)
8. Masuk ke folder **Env\Scripts\activate.bat** (untuk masuk ke virtual environment)
9. (optional) cek **pip list** dan upgrade dengan perintah nomer 5
10. Sekarang sudah punya pip dan python yang terpisah environment nya
11. Gunakan perintah **pip install Django==4.1** (saat itu versi terbaru adalah 4.1)
12. Gunakan **pip list** untuk melihat Django apakah sudah terinstall
13. Buat project django dengan perintah **django-admin startproject mywebsite** (mywebsite = nama folder baru yang akan dibuat)
14. Masuk ke mywebsite dengan **cd mywebsite** lalu **dir** lalu lihat apakah sudah ada manage.py
15. Gunakan perintah **python manage.py runserver**
16. cek di browser http://127.0.0.1:8000/
17. Untuk berhentikan server bisa klik ctrl+c di cmd
18. Untuk keluar dari virtual environment gunakan perintah **deactivate**
19. Untuk activate Virtual Environment lagi gunakan perintah ke 8 yaitu ke folder yang berisi file activate dan **activate.bat**
20. Untuk jalankan server lagi masuk ke directory yang terdapat file manage.py dan gunakan perintah seperti no 15