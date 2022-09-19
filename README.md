# Flutter Transform and Rotate

## Set elevated button with modified rotate & scaling
<img src="/sss/1.png" title="Screenshot 1"/>
Widget yang ingin berubah akan dibungkus didalam widget Transform dan dapat disesuaikan opsi-opsinya seperti rotationZ, scale, offset hingga menjadi sesuai yang diinginkan

## Set perspective layout based on gesture
<img src="/sss/2.png" title="Screenshot 2"/>
Widget parent Scaffold dimasukkan kedalam sebuah fungsi baru. Untuk build akan diisi oleh widget Transform yang telah diberikan option dan widget Transform itu sendiri akan diberikan child GestureDetector sehingga perspective layout akan berubah sesuai dengan gesture jari yang kita berikan.

## Create Flip panel for flipping animation
<img src="/sss/3.png" title="Screenshot 3"/>
Menggunakan package dari flip panel kita membuat sebuah stream untuk flipped widget yang akan menampilkan angka mulai dari 1 - 9.

## Flutter Transform and Rotate

Transform, perspective layout, flipped panel.

- https://pub.dev/packages/flip_panel
- run with unsound null safety - https://dart.dev/null-safety/unsound-null-safety