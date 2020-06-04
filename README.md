# Soal Ujian Python Data Science Fundamental

[![logopwdk.png](https://i.postimg.cc/66VC3Rgx/logopwdk.png)](https://postimg.cc/s1XMHB3T)



#

### **Soal 1 - Konversi Waktu (30 Poin)**

Buatlah sebuah __return function__ dengan __1 argumen__ yang akan menerima inputan __bilangan integer(Seconds)__.
Dan akan menghasilkan output __string__ dengan format waktu ("HH:MM:SS").

- __HH__ : Hours, 2 digits, range: 00 - 99
- __MM__ : Minutes, 2 digits, range: 00 - 59
- __SS__ : Seconds, 2 digits, range: 00 - 59

- __Case Flow__: Saat dieksekusi, program akan mencetak nilai return function.


  ```python
  def timeConverter(seconds):
        .....
   
  
  Masukkan detik : 3600
  Konversi : 01:00:00

  Masukkan detik : 3665
  Konversi : 01:01:05
  ```
  
- __Condition__: Program hanya menerima angka bulat, dengan __nilai maksimal 359999__, jika user memasukkan __nilai lebih dari 359999__, __bilangan desimal__ , __bilangan negatif__, maupun memasukkan __string__ akan keluar notifikasi. __Invalid Input__

  ```bash
  Masukkan detik : ujian
  Invalid Input!

  Masukkan detik : 20.5
  Invalid Input!
  ```
_**Catatan:**_

- _Untuk Student __BSD & Bandung__ Commit & push source code project ke __Github__ Anda, buatlah repo dengan nama __Konversi_Waktu__. Kemudian lampirkan __url link repo Github__ Anda via email ke khumaeni@purwadhika.com dan operational_bdg@purwadhika.com_

- _Untuk Student __Jakarta__ Kirim File Exam dengan nama __Konversi_Waktu.py__ ke email : nurrokim@purwadhika.com dan operational_jkt@purwadhika.com_


#

### **Soal 2 - List Spinner (30 Poin)**

Buatlah sebuah __return function__ dengan __1 argumen__ yang dapat memutar __list angka__ (Putaran 1X counter-clockwise) seperti keterangan di bawah ini .
- __List Awal__
    ```bash
    [[1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]]
    ```
    
 - __Function__
 
   ```python
   # Function Initialization
    def counterClockwise(...):
        .....
        
   # Use the Function
   print(counterClockwise(List_awal))
   ```
    
 - __List Output__
 
    ```bash
    [[3, 6, 9],
    [2, 5, 8],
    [1, 4, 7]]
    ```
    
    
_**Catatan:**_

- _Untuk Student __BSD & Bandung__ Commit & push source code project ke __Github__ Anda, buatlah repo dengan nama __List_Spinner__. Kemudian lampirkan __url link repo Github__ Anda via email ke khumaeni@purwadhika.com dan operational_bdg@purwadhika.com_

- _Untuk Student __Jakarta__ Kirim File Exam dengan nama __List_Spinner.py__ ke email : nurrokim@purwadhika.com dan operational_jkt@purwadhika.com_



#

### **Soal 3 - Mengurai dan Merajut Kata (40 Poin)**


Buatlah sebuah __file python__ yang berisi __2 buah return function__, dengan __1 argumen__ yang dapat digunakan untuk mengurai & merajut sebuah __string__



- fungsi __urai(...)__ akan mengurai string. contoh output yang diharapkan adalah sebagai berikut:

    ```python
    # Function Initialization :
    def urai(...):
        ......
     
    def rajut(...):
        ......
        
        
    # Use the function
    
    print(urai('Code'))
    print(urai('Python'))
    print(urai('Purwadhika'))

    # Output:
    CCoCodCode
    PPyPytPythPythoPython
    PPuPurPurwPurwaPurwadPurwadhPurwadhiPurwadhikPurwadhika
    ```

- Sedangkan fungsi __rajut(...)__ akan merajut kembali string yang terurai menjadi bentuk kata asalnya. contoh output yang diharapkan adalah sebagai berikut:

    ```python
    
    # Use the function
    
    print(rajut('CCoCodCode'))
    print(rajut('PPyPytPythPythoPython'))
    print(rajut('PPuPurPurwPurwaPurwadPurwadhPurwadhiPurwadhikPurwadhika'))
    
    # Output:
    
    Code
    Python
    Purwadhika
    ```
    
    
_**Catatan:**_

- _Untuk Student __BSD & Bandung__ Commit & push source code project ke __Github__ Anda, buatlah repo dengan nama __Urai_Rajut_Kata__. Kemudian lampirkan __url link repo Github__ Anda via email ke khumaeni@purwadhika.com dan operational_bdg@purwadhika.com_

- _Untuk Student __Jakarta__ Kirim File Exam dengan nama __Urai_Rajut_Kata.py__ ke email : nurrokim@purwadhika.com dan operational_jkt@purwadhika.com_



#

### *__Good Luck & HappyCoding__* 
