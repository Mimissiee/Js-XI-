<!-- Switch & If else -->
Penjelasan Switch :
Jika Const/variabel (nilai) bernial "A" maka yang akan tercetak adalah case "A" = 'Wow anda Lulus dengan baik', case "B" dan case "C" kedua case ini di gabung maka hasilnya "Anda lulus", Jika Case "D" maka baris di bawahnya yg tercetak "Mungkin Anda salah Jurusan"
dan jika case memiliki nilai selain dari pada case tersebut maka hasil nya itu default

Penjelasan If else :
if (nilai === "A") = Jika Nilai === (Mengecek isi dan typedatanya) nya "A" maka, hasil nya "wow Anda Lulus dengan Baik"
else if (nilai === "B" || nilai === "C") = Dan jika nilainya "B" dan sama dengan "C" maka hasilnya "anda Lulus", || (mengecek jika salah satunya benar maka benar/true)
else if (nilai === "D") = jika nilai "D", Hasilnya "anda Tidak Lulus"
else = jika tidak ada kondisi yg terpenuhi, hasilnya "mungkin anda salah jurusan"

Perbedaan kedua nya

Kalau if else, fleksibel di pakai jika banyak kondisi, bisa berupa umur/angka/ atau kondisi yg pake > < =, fleksibel yg berarti mudah menyesuaikan / bisa di pakai banyak situasi
Switch, di gunakan kalau kondisinya sudah fix / tetap, seperti "A" , "B" , "C" dan sudah pasti nilainya, atau angka tertentu, atau Hari, jadi pilihan opsi nya sudah fix dan tetap

<!-- END -->

<!-- Hello World -->

Bisa menggunakan console.log ("Hello, World!" ); & document.writeln ("pelajar IQIS");
hasil dari console.log akan muncul di console, hasil dari document.writeln akan muncul di halaman depan

<!-- END -->

<!-- ARITMATIKA -->

let result = 1 + 2; // 3 = melakukan operasi 1 + 2 
document.writeln("<p> 1 + 2 = " + result + "</p>"); = mencetak 1 + 2 dan hasil dari result = 3
let originalResult = result; // 3 = menyimpan nilai result yaitu 3

result = result - 1; // 2 = melakukan operasi result yaitu 3 - 1 = 2
document.writeln("<p>" + originalResult + " - 1 = " + result + "</p>"); = mencetak originalresult yaitu 3 - 1 dan mencetak = hasil result yaitu 2
originalResult = result; // 2 = orinal resultnya 2 

result = result * 2; // 4 = operasi perkalian, hasil resut sebelumnya yaitu 2 di kali dengan 2
document.writeln("<p>" + originalResult + " * 2 = " + result + "</p>"); = mencetak orinalresult = result yaitu 2 dan di kali dengan 2, dengan hasil result, yaitu 2 * 2 = 4

<!-- END -->




