# -LT-14_If_Expression

`if` dalam JavaScript adalah pernyataan kondisional yang memungkinkan Anda mengeksekusi suatu blok kode hanya jika kondisi tertentu terpenuhi. Ini bisa berguna untuk mengontrol aliran program Anda dan mengeksekusi hanya bagian yang diinginkan dari kode Anda pada situasi yang tepat. Penggunaan dasar `if` dapat ditulis seperti ini:

    if (condition) {
      // code to be executed if condition is true
    }

Di mana "condition" adalah ekspresi yang akan dievaluasi sebagai benar atau salah. Jika hasil evaluasi `condition` adalah benar, maka blok kode di dalam kurung kurawal akan dijalankan. Jika `condition` adalah salah, maka blok kode tersebut tidak akan dijalankan.

Anda juga dapat menambahkan blok `else` untuk mengeksekusi kode jika "condition" adalah salah: 

    if (condition) {
      // code to be executed if condition is true
    } else {
      // code to be executed if condition is false
    }

Anda juga dapat menambahkan lebih dari satu blok `else if` untuk menguji kondisi yang berbeda:

    if (condition1) {
      // code to be executed if condition1 is true
    } else if (condition2) {
      // code to be executed if condition1 is false and condition2 is true
    } else {
      // code to be executed if condition1 and condition2 are both false
    }

Oke. Selain itu, Anda juga dapat menggunakan operator ternary untuk menulis pernyataan `if` dalam bentuk yang lebih singkat. Operator ternary adalah operator yang memiliki tiga operand dan bisa digunakan untuk mengevaluasi kondisi dan mengembalikan nilai yang sesuai. Penggunaannya dapat ditulis seperti ini:

    condition ? value1 : value2

Di mana `condition` akan dievaluasi. Jika `condition` adalah benar, maka operator ternary akan mengembalikan `value1`. Jika `condition` adalah salah, operator ternary akan mengembalikan `value2`. Contohnya:

    let x = 10;
    let y = 20;

    let min = (x < y) ? x : y;
    console.log(min); // Output: 10

Di sini, kita mengevaluasi apakah x lebih kecil dari y. Jika benar, maka min akan diisi dengan nilai x. Jika salah, maka min akan diisi dengan nilai y.
