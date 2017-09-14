# ShushMe
Google Places API demo app

## Screenshots dan Penjelasan
- Aplikasi yang kita kerjakan dalam latihan ini merupakan aplikasi yang bernama ShushMe dengan icon Android atau masih icon custom<br>
![project](https://user-images.githubusercontent.com/21364340/30411227-e63fd732-9939-11e7-9b4e-686034e085c4.png)<br> <br>
Untuk commitan pertama atau initial commit tampilan aplikasi SushMe seperti dibawah ini, kita bisa tekan Enable Geofences : <br>
![screenshot_20170911-090615](https://user-images.githubusercontent.com/21364340/30411228-e663befe-9939-11e7-9657-6412d708a1a4.png)
![screenshot_20170911-090618](https://user-images.githubusercontent.com/21364340/30411229-e67316f6-9939-11e7-8cd6-ca0dc6866e09.png)<br>
Namun button ADD NEW LOCATION masih belum berfungsi
<br> <br>
- Commitan yang kedua adalah GoogleApiClient commit dalam commit an ini kita menambahkan location permission yang berfungsi sebagai pengijinan untuk memperlihatkan lokasi, jadi secara otomatis location kita akan hidup dan menunjukkan dimana lerak kita sekarang. maka tinggal kita centang dan akan ada notif pemberitahuan untuk pengizinan aplikasi mengakses lokasi secara otomatis <br>
![screenshot_20170911-153402](https://user-images.githubusercontent.com/21364340/30411231-e6853b6a-9939-11e7-95c6-795531c77d27.png)
![screenshot_20170911-153404](https://user-images.githubusercontent.com/21364340/30411233-e6862598-9939-11e7-93b4-30594c000875.png)
![screenshot_20170911-153409](https://user-images.githubusercontent.com/21364340/30411232-e685b61c-9939-11e7-8f4c-d92ba273bb2b.png)<br> Button ADD NEW LOCATION jika ditekan akan muncul notif Location Premission Granted.
<br> <br>
- PlacePicker commmit disini kita menambahkan kode untuk bisa menggakses maps, dan memfungsikan button ADD NEW LOCATION, tampilan aplikasi menjadi seperti dibawah ini. Dan saat ditekan ADD NEW APLICATION maka akan memunculkan maps dengan lokasi kita berada. Dan saat dipilih akan muncul lokasi yang kita pilih. dan akan menyimpan data lokasi yang dipilih<br>
![screenshot_20170912-085013](https://user-images.githubusercontent.com/21364340/30411234-e69500a4-9939-11e7-8a22-df61cdc955cf.png)
![screenshot_20170912-085241](https://user-images.githubusercontent.com/21364340/30411238-e6b83718-9939-11e7-826e-6159d9252608.png)
![screenshot_20170912-095900](https://user-images.githubusercontent.com/21364340/30411237-e6b81cd8-9939-11e7-91fc-6bd1977927e3.png)
<br> <br>
- kemudian commitan selanjutanya adalah GetPlaceById commit dan Genofencing  dimana dalam commitan ini ditambahkan kode untuk memunculkan gambar lokasi yang dipilih <br>
![screenshot_20170912-095942](https://user-images.githubusercontent.com/21364340/30411236-e6b7ee52-9939-11e7-990b-10a12158f316.png)
<br> <br>
- Yang terakhir adalah SilentMode commit ini berfungsi untuk mengatur notif yang akan ditampilkan, maka jika kita berda pada posisi yang kita pilih maka akan muncul notif suara dan tulisan<br>
![screenshot_20170912-104648](https://user-images.githubusercontent.com/21364340/30411241-e6d7a814-9939-11e7-90a1-fdc94a1e88b8.png)

