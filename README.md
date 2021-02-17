# Coding Challenge Data Science Python Fundamental

[![logopwdk.png](https://i.postimg.cc/66VC3Rgx/logopwdk.png)](https://postimg.cc/s1XMHB3T)



#

### **Triangle Words**

Buatlah Sebuah Program dapat menerima inputan dari user dan memiliki __sebuah return function__ dengan __1 argumen__, output dari program membentuk pola segitiga sama kaki dengan elemen berupa karakter-karakter dari sebuah __string__ yang menjadi argumen function tersebut.

- __Case Flow__: Saat dieksekusi, program akan mencetak pola segitiga dari karakter-karakter string yang diinputkan. Jika jumlah karakter string memenuhi syarat terbentuknya pola, maka program akan menjalankannya. Namun jika jumlah karakter string tidak memenuhi syarat membentuk pola, maka akan muncul pesan bahwa string tidak memenuhi syarat membentuk pola.

    ```python
    Contoh Input:
    Masukkan kalimat : Purwadhika
    
    Masukkan kalimat : Purwadhika Digital Technology School JKT
    
    Masukkan kalimat : Python Code
    
    Masukkan kalimat : JCDS12
    
    Masukkan kalimat : Job Connector DS Jakarta 
    
    Masukkan kata : Code
    
    Masukkan kata : Digital
    
    Masukkan kata : Data Science
    ```

- __Output__ yang diharapkan:
  
    ```bash
    # input : Purwadhika
    
    P 
    u r     
    w a d   
    h i k a 
    p u r w 
    a d h   
    i k     
    a   

    # input : Purwadhika Digital Technology School JKT
    
    P
    u r
    w a d
    h i k a
    D i g i t
    a l T e c h
    n o l o g y S 
    c h o o l J K T
    P u r w a d h i
    k a D i g i t
    n o l o g
    y S c h
    o o l
    J K
    T

    # input : Python Code
    
    P
    y t
    h o n
    C o d e
    P y t h
    o n C
    o d
    e
    
    # input : JCDS12
    
    J
    C D
    S 1 2
    J C D
    S 1
    2
    
    # input : Job Connector DS Jakarta 
    
    J
    o b
    C o n
    n e c t
    o r D S J
    a k a r t a
    J o b C o n
    n e c t o
    r D S J
    a k a
    r t
    a
    
    # input : Code
    Mohon maaf, jumlah karakter tidak memenuhi syarat membentuk pola.
    
    # input : Digital
    Mohon maaf, jumlah karakter tidak memenuhi syarat membentuk pola.
    
    # input : Data Science
    Mohon maaf, jumlah karakter tidak memenuhi syarat membentuk pola.
    ```

### **NPWP Verification**

__NPWP__ (Nomor Pokok Wajib Pajak) memiliki kode seri dengan __15 angka__, yang menggunakan format sebagai berikut: __99.999.999.9-999.999__.

- Dua digit pertama, __(99)__.xxx.xxx.x-xxx.xxx menunjukkan Identitas Wajib Pajak, yaitu:
    - __01__ sampai __03__ adalah Wajib Pajak Badan
    - __04__ dan __06__ adalah Wajib Pajak Pengusaha
    - __05__ adalah Wajib Pajak Karyawan
    - __07__ sampai __09__ adalah Wajib Pajak Orang Pribadi

- Enam digit berikutnya, xx.__(999.999)__.x-xxx.xxx menunjukkan Nomor Registrasi / Urut yang diberikan Kantor Pusat Direktorat Jenderal Pajak kepada Kantor Pelayanan Pajak (KPP).

- Satu digit berikutnya, xx.xxx.xxx.__(9)__-xxx.xxx berfungsi sebagai Alat Pengaman untuk menghindari terjadinya pemalsuan atau kesalahan pada NPWP.

- Tiga digit berikutnya, xx.xx.xxx.x-__(999)__.xxx adalah Kode KPP. Jika misalkan kodenya adalah 015, berarti NPWP tersebut dikeluarkan di KPP berkode 015, yaitu KPP Pratama Jakarta Tebet.

- Tiga digit terakhir, xx.xxx.xxx.x-xxx.__(999)__ menunjukkan Status Wajib Pajak:
    - __000__ berarti berstatus Tunggal / Pusat (biasa disebut NPWP Pusat)
    - __00x__ (001,002 dst) berarti Cabang, dimana angka akhir menunjukkan urutan cabang (cabang ke-1 maka 001; cabang ke-2 maka 002; dst.).

<hr>

Berdasarkan uraian di atas, buatlah sebuah program yg menerima inputan dari user dan memiliki __sebuah return function__ untuk melakukan verifikasi kode seri NPWP & menguraikan artinya. Adapun eksekusi program tersebut beserta output yang diharapkan adalah sebagai berikut.

- ```Masukkan NPWP : 99.999.999.9-999.999```
    ```
    Output: Kode seri NPWP tidak valid!
    ```
    Kode seri NPWP ini tidak valid dikarenakan 2 digit pertama hanya bisa diisi __01__ sampai __09__.

- ```Masukkan NPWP : 091234565623179```
    ```
    Output: Kode seri NPWP tidak valid!
    ```
    Kode seri NPWP ini tidak valid dikarenakan tidak mengikuti format baku: __99.999.999.9-999.999__.

- ```Masukkan NPWP : 09.123.456.A-123.123```
    ```
    Output: Kode seri NPWP tidak valid!
    ```
    Kode seri NPWP ini tidak valid dikarenakan terdapat karakter bukan angka di dalamnya.
    
- ```Masukkan NPWP : 09.265.796.5-235.6987```
    ```
    Output: Kode seri NPWP tidak valid!
    ```
    Kode seri NPWP ini tidak valid dikarenakan lebih dari 15 digit angka.

- ```Masukkan NPWP : 05.885.434.4-215.000```
    ```
    Output: Kode seri NPWP valid!
            Identitas Wajib Pajak: 01 Wajib Pajak Pengusaha
            Nomor Registrasi: 885.434
            Alat Pengaman: 4
            Kode KPP: 215
            Status Wajib Pajak: 000
    ```
    Kode seri NPWP ini valid, maka program akan menjabarkan arti angka pada kode seri tersebut.


#

### *__Good Luck & HappyCoding__* 
