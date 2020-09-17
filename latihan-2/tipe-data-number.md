## Tipe Data Number Di Go-Lang

di go-lang ada dua jenis tipe data number
1. integer
2. floating

didalam go-lang tipe data number memiliki detil

untuk integer

| tipe data | Nilai minimum | Nilai maksimum |
| ----------- | :---------: | ----------: |
| int8 | -128 | 127 |
| int16 | -32768 | 32767 |
| int32 | -2147483648 | 2147483647 |
| int64 | -9223372036854775808 | 9223372036854775807 |

jikalau kita ingin menggunakan nilai int hanya untuk perhitungan yang kecil, contohnya siswa di kelas. bisa menggunakan int8.
karena semakin besar nilainya maka akan besar juga memorinya

untuk unsign integer memiliki nilai minimum 0

| tipe data | Nilai minimum | Nilai maksimum |
| ----------- | :---------: | ----------: |
| uint8 | 0 | 255 |
| uint16 | 0 | 65535 |
| uint32 | 0 | 4294967295 |
| uint64 | 0 | 18446744073709551615 |

untuk tipe data floating

| tipe data | Nilai minimum | Nilai maksimum |
| ----------- | :---------: | ----------: |
| float32 | 1.18x10<sup>-38</sup> | 3.4x10<sup>38</sup> |
| float64 | 2.23x10<sup>-308</sup> | 1.80x10<sup>308</sup> |
| complex64 | complex numbers with float32 real and imaginary parts |
| complex128 | complex numbers with float64 real and imaginary parts |


### Alias

| tipe data | Alias untuk |
| ----------- | :---------: |
| byte | uint8 |
| rune | int32 |
| int | min int sesuai pada bit yang digunakan pada sistem operasi kita |
| uint | min uint sesuai pada bit yang digunakan pada sistem operasi kita |