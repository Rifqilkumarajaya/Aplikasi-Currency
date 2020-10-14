# Aplikasi-Currency

1. Review kembali percobaan 1 sampai dengan 3 dengan menjawab pertanyaan-pertanyaan pada latihan tersebut. Percobaan 1
	a. ketika user menginputkan angka ke dalam usd maka di box rupiah akan muncul value yang sama karena belum ada logika untuk mengkonversinya
	b. setiap value yang diinputkan ke dalam box usd akan dikali 10000. Maka dari itu value yang ditampilkan dalam box rupiah adalah hasil perkalian tersebut
	c. aplikasi belum bisa menghandle inputan huruf maka aplikasi akan menutup dengan sendirinya (force close)
	d.Jika box usd diinput angka maka hasilnya akan tampil dari perkalian dari value yang diinput dikali 4
	e. Jika user menginput huruf maka value yang akan ditampilkan adalah "invalid", karena sudah ada logika yang akan menghandle jika user menginput huruf
	f. Jika user menginput huruf maka box rupiah akan menampilkan "invalid"


2. Mengapa perlu membuat class CurrencyController.cs pada percobaan 4 ? 
Jawab : agar lebih pendek source codenya dan lebih mudah dibaca codenya jika ada code yang error maka akan lebih mudah untuk memperbaikinya atau untuk mengembangkan aplikasi

3. Jelaskan kegunaan method isAllowed pada percobaan 4!
Jawaba : untuk memvalidasi inputan user

4. Jelaskan secara singkat mengenai Regex pada percobaan 4!
Jawab : digunakan untuk menemukan karakter apa pun yang bukan digit. Digit di dalam tanda kurung dapat berupa angka atau rentang angka dari 0 hingga 9.
