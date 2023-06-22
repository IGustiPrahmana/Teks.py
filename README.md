# Elemen Teks Streamlit Phyton
Elemen Teks Streamlit biasanya dimulai dengan panggilan st.titleuntuk menyetel judul aplikasi. Setelah itu, ada 2 level heading yang bisa Anda gunakan: st.headerdan st.subheader.  Teks murni dimasukkan dengan st.text, dan Markdown dengan st.markdown.

Instal Streamlit
Daftar isi
Prasyarat
Instal Streamlit di Windows

Prasyarat
Sebelum memulai, Anda memerlukan beberapa hal:

IDE atau editor teks favorit Anda
Python 3.7 - Python 3.11
PIP
Siapkan lingkungan virtual Anda
Apa pun alat manajemen paket yang Anda gunakan, sebaiknya jalankan perintah di halaman ini di lingkungan virtual. Ini memastikan bahwa dependensi yang ditarik untuk Streamlit tidak memengaruhi proyek Python lain yang sedang Anda kerjakan.

Di bawah ini adalah beberapa alat yang dapat Anda gunakan untuk pengelolaan lingkungan:

venv
pipenv
puisi
virtualenv
konda
Instal Streamlit di Windows
Manajer lingkungan yang didukung secara resmi oleh Streamlit di Windows adalah Anaconda Navigator .

Instal Anakonda
Jika Anda belum menginstal Anaconda, ikuti langkah-langkah yang disediakan di halaman instalasi Anaconda .

Buat lingkungan baru dengan Streamlit
Selanjutnya Anda harus menyiapkan lingkungan Anda.

Ikuti langkah-langkah yang disediakan oleh Anaconda untuk menyiapkan dan mengelola lingkungan Anda menggunakan Anaconda Navigator.

Pilih ikon "▶" di sebelah lingkungan baru Anda. Kemudian pilih "Buka terminal":

"Buka terminal" di Anaconda Navigator
Di terminal yang muncul, ketik:

pip install streamlit

Menyalin
Uji apakah instalasi berhasil:

streamlit hello

Menyalin
Aplikasi Halo Streamlit akan muncul di tab baru di browser web Anda!

Gunakan lingkungan baru Anda
Di Anaconda Navigator, buka terminal di lingkungan Anda (lihat langkah 2 di atas).

Di terminal yang muncul, gunakan Streamlit seperti biasa:
streamlit run myfile.py
