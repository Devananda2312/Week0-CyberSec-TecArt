260530911110  
I Nyoman Devananda Satria Wibawa  
Cyber Security  
# Week0-CyberSec-Tecart    
Homework 00 bertujuan untuk memastikan setiap peserta telah memiliki lingkungan kerja dan tools dasar yang diperlukan untuk mengikuti pembelajaran serta kompetisi Cyber Security, khususnya Capture The Flag (CTF)  

# Tools 
<img src="https://github.com/Devananda2312/Week0-CyberSec-TecArt/blob/master/instalasi%20tools.png">  

Instalasi tools umum yang telah diinstall:  
- WSL (Windows Subsytem for Linux) Distro Kali Linux  
- Git dan Github  
- Python

# Pengujian WSL
<img src="https://github.com/Devananda2312/Week0-CyberSec-TecArt/blob/master/Pengujian%20WSL%20(1).png">    
<img src="https://github.com/Devananda2312/Week0-CyberSec-TecArt/blob/master/Pengujian%20WSL(2).png">   

Pengujian WSL dilakukan sepenuhnya melalui Command Line Interface (CLI). Langkah - langkah yang dilakukan:  

1. Membuat sebuah folder dengan nama Week0-CyberSec-TecArt dengan command mkdir [nama_direktori].  
2. Masuk ke dalam folder tersebut dengan command cd [direktori].  
3. Membuat file baru dengan nama README.md dengan command nano [nama_file].  
4. Lalu menuliskan informasi berikut pada file tersebut:  
- NIM  
- Nama  
- Divisi

# Pengujian Python  
<img src="https://github.com/Devananda2312/Week0-CyberSec-TecArt/blob/master/Python%20(1).png">  
<img src="https://github.com/Devananda2312/Week0-CyberSec-TecArt/blob/master/Python%20(2).png">  
Pengujian python dengan membuat program sederhana dilakukan dengan langkah - langkah berikut:  
1. Membuat program menggunakan nano [nama program] dengan ekstensi file .py  
2. Menuliskan kode program python  
3. Menjalankan program menggunakan command python3 [nama_program.py]  

# Challenge  
Kerjakan challenge “Undo” pada platform CYLAB Academy: https://learn.cylabacademy.org/library/766
Dokumentasikan langkah-langkah penyelesaian challenge dalam write-up.  

## Challenge Undo  
### Step 1  
<img src="https://github.com/Devananda2312/Week0-CyberSec-TecArt/blob/master/menu%20undo.png">  
<img src="https://github.com/Devananda2312/Week0-CyberSec-TecArt/blob/master/step%201.png">  

- Tekan tombol Launch Instance untuk memulai.  
- Hubungkan server soal dengan command nc [ip_address] [port]

Untuk mendecode string yang didecode dengan base64, gunakan command base64 -d

### Step 2  
<img src="https://github.com/Devananda2312/Week0-CyberSec-TecArt/blob/master/step%202.png">  

Untuk reverse sebuah text, gunakan command rev  

### Step 3
<img src="https://github.com/Devananda2312/Week0-CyberSec-TecArt/blob/master/step%203.png">  
Untuk mengganti seluruh dash menjadi underscore pada text, gunakan command  tr "-" "_" 

### Step 4  
<img src="https://github.com/Devananda2312/Week0-CyberSec-TecArt/blob/master/step%204.png">  

