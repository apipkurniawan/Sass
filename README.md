# Sass
learn about sass

doc: https://sass-lang.com/

Sass (Syntactically Awesome Style Sheets) adalah css pre processor, yg memiliki lebih banyak feature css.

kekurangan pada Css :
- tidak ada variable
- tidak ada function
- tidak ada modularisasi
- tidak bisa melakukan operasi & logika pemrograman
- banyak duplikasi kode

solusi dari pre processor :
- variable
- mixin
- import & uses
- operator & built-in function
- nested css

macam-macam css pre processor : 
- sass
- stylus
- postCss
- less
- stylecow
- ....

alasan menggunakan Sass : 
- mempermudah penulisan
- mempermudah pengelolaan
- memiliki banyak fungsi built-in
- kita dapat membuat fungsi sendiri
- kita dapat memodifikasi framework css (bootstrap / materialize)
- banyak perusahaan menggunakan Sass

alasan untuk tidak menggunakan Sass :
- banyak fitur Sass yang sekarang sudah dimiliki oleh css
- tidak untuk project kecil
- styled components / css in js

.SASS :
- tidak pakai ';' dan '{}'
.SCSS :
- pakai ';' dan '{}'
 
how started :
- instalasi compiler sass ada beberapa pilihan :
  (aplikasi tools)
  (VSCode Extention) => Live Sass Compiler
  (Command line) : npm install -g sass
  jika menggunakan command line, harus buka terminal dan untuk menjalankannya menggunakan command 'sass scss/main.scss css/main.css'
  format : sass path_main_scss path_main_css 

configuration sass :
- Preferences => Settings => Live Sass Compile => Formats => edit in settings.json => "savePath": "css"
  untuk mengenerate ke folder css -> main.css


