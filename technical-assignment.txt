( Soal nomor 1 )

Kamu adalah seorang mahasiswa IT yang baru memulai perjalanan, kemudian kamu juga sudah belajar tentang adanya pseudocode. 
Kemudian dosenmu memmberikan sebuah tugas untuk membuat sebuah pseudocode tentang cara kerja sebuah thermometer yang akan merubah 
semua jenis suhu menjadi celcius.

Berikut adalah 3 cara konversi suhu ke dalam celcius:

fahrenheit to celcius = (N - 32) * (5/9)
kelvin to celcius = (N - 273.15)
celcius to celcius = N


1. User menginput type Temperature
2. User menginput nilai Temperature
3. konversi suhu dari fahrenheit ke celcius
4. konversi suhu dari kelvin ke celcius 
5. Celcius


N = celcius

START
 
IF Type is `(TypeTemperature == Fahrenheit)`
        CONVERT `(fahrenheit to celcius = (N - 32) * (5/9)`= N
ELSE IF `(TypeTemperature == Kelvin)` 
        CONVERT `(kelvin to celcius = (N - 273.15)` = N
ELSE
        DISPLAY `(Temperature)`
END


(Soal Nomor 2)

Write a program that prints the numbers from 1 to n

for multiples of 3 print "Fizz" instead of the number
for the multiples of 5 print "Buzz" instead of the number
for numbers which are multiplies of both 3 and 5 print "FizzBuzz"
for numbers not divisible by, 3, 5, or both, print the number as is

 Pseudocode

START

SET n = 20

FOR i = `1 to 20` 

IF `( i%3 )`
    DISPLAY `(i = FIZZ)`
ELSE IF `( i%5 )`
    DISPLAY `(i = BUZZ)`
ELSE IF `( i%3 ) && ( i%5 )`
    DISPLAY `( i = FIZZBUZZ )`
ELSE

END

(Soal Nomor 3)

Palindrome adalah adanya sebuah kata, frasa, atau angka yang dapat dibaca dengan sama baik dari depan maupun belakang.

Buatlah sebuah program untuk mengecek apakah 1 buah nilai bersifat palindrome. Jika iya program akan mengembalikan status TRUE jika tidak program akan mengembalikan status FALSE.

Input hanya dapat menerima tipe data berupa string/teks.

START

i = kata


STORE = i with any string
READ = i
IF = i++ == i--
    DISPLAY `(true)`
ELSE IF = i++ !== i--
    DISPLAY `(FALSE)`
ELSE

END


    

( Soal nomor 4)

Skilvul ingin memberikan penilaian terhadap siswa

Setiap siswa akan menerima penilaian skala 0 - 100
Nilai di bawah 70 dianggap tidak lulus
Dalam memberikan nilai ada 2 tahapan penting yaitu:

Untuk proses pembulatan nilai kelipatan 5, syaratnya adalah nilai tersebut harus kurang/lebih kecil dari 3 jaraknya dengan nilai pembulatan ke atas.
Jika nilai kurang dari 68, tidak dapat melakukan pembulatan karena tetap dianggap tidak lulus.
Input berupa Nilai Awal

Output berupa Nilai Akhir baik yang dapat dilakukan pembulatan ataupun tidak

deklarasi
kelipatan, batas_kelipatan: integer

START

STORE `nilai` to any number
FOR  x = 3 to 5
     x += 5
     DISPLAY `(kelipatan nilai)`
IF `nilai` >68 
    DISPLAY `lulus`
ELSE IF `nilai`<68
    DISPLAY `tidak lulus`
ELSE

END 













