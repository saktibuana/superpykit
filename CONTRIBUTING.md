# Pedoman Menyumbang Code

Terima kasih yang teramat banyak terhatur untuk Anda yang telah berminat menyumbang code. Segala jenis sumbangan sangat berharga bagi kami. 📝

Pastikan telah membaca dokumentasi sebelum memberikan sumbangan! Sehinga akan mempermudah kami yang memelihara proses  yang terlibat. 💚

## Jika Anda memiliki pertanyaan mengenai proyek ini, bagaimana cara menggunakannya, ataupun hanya ingin memperjelas sesuatu

* Buka sebuah issue [di sini](https://github.com/saktibuana/superpykit/issues)
* Berikan  konteks sebanyak mungkin, mengenai apa saja yang sedang dialami.
* Berikan informasi proyek dan versi platform (python, pip, dan lain-lain), dan apapun yang sekiranya bersangkutan dengan proyek ini. Jika tidak disebutkan di awal, maka mohon siapkan sehingga ketika para pemelihara repository ini bertanya, bisa segera diberikan sebagai jawaban.

## Meminta sebuah fitur baru

Jika proyek ini tidak menyediakan apa yang Anda perlukan atau tidak mengerjakan apa yang diinginkan, maka:

* Bukalah  [halaman ini](https://pywhatkit.herokuapp.com/request-feature)
* Berikan informasi konteks (keadaan) sebanyak mungkin  perihal apa yang sebenarnya diinginkan atau dicari.
* Jika Anda sendiri bermaksud ingin menyumbang code perihal fitur tersebut, mohon buatlah konsep pull request tersebut [di sini](https://github.com/saktibuana/superpykit/pulls).

## Pemformatan Code

Mohon dipastikan bahwa code yang Anda tulis mengikuti  standar PEP8 dan menyediakan hint (petunjuk keterangan) atas functon dan parameter dengan spacing yang pantas.
Anda bisa mengikuti cara dalam panduan [ini](https://black.readthedocs.io/en/stable/integrations/editors.html) yang berisi cara mengintegrasikan `black formatter` dengan berbagai IDE dan Editor.

Untuk para pengguna VSCode, buatlah folder `.vscode` dalam direktori proyek dan file `settings.json` di dalamnya. Dalam file tersebut tambahkan baris code berikut ini:

```json
{
    "python.formatting.provider": "black",
    "editor.formatOnSave": true,
    "editor.defaultFormatter": "ms-python.python"
}
```

Bisa juga menggunakan `black filename` dalam terminal untuk melakukan format pada masing-masing file secara terpisah.

**Make sure to use pre-commit with `pre-commit run --all-files` before pushing your changes.**

## Contributing Code

Code contributions of just about any size are acceptable!

Setting up a development environment:

1. Fork the repository and then clone it to your local computer.
2. PILIHAN INI TIDAK HARUS, TAPI SANGAT DISARANKAN: Buatlah environment virtual baru menggunakan `virtualenv` dengan code `python3 -m venv venv`.
3. Aktifkan environment virtual dan pasanglah dependency terkait proyek ini menggunakan code `pip3 install -r requirements-dev.txt`.
4. Selamat 🎉, sekarang Anda telah siap untuk memberikan sumbangan code.

Langkah untuk menyumbang code:

1. Persiapkan environment untuk melakukan development.
2. Lakukan perubahan yang diperlukan terhadap source code.
3. Jika memungkinan, pastikan menyertakan komentar yang menjelaskan apa saja yang dilakukan code Anda.
4. Tuliskan dengan pesan-pesan commit dengan jelas dan singkat.
5. Lakukan push pada repository yang sudah dilakukan fork dan ketika perubahan code Anda telah siap ditinjau, lakukanlah pull reques dari repository yang telah dilakukan fork sebelumnya.
6. Jika pull request tersebut ternyata memperbaiki sebuah issue yang masih berstatus open, tambahkan sebuah baris dalam keterangan pull request yang menyatakan `menutup #123`, dalam hal ini `#123` adalah nomor issue yang telah diperbaiki.
7. Seseorang di antara para pemelihara repository ini akan melakukan peninjauaan terhadap pull request dan akan memberikan tindak lanjut berikutnya.

CATATAN: Untuk menyumbang dalam bentuk Dokumentasi, ikuti langkah yang sama dengan langkah di atas.

## Menambahkan Fitur Baru

Here are some few things to keep in mind before working on a new feature:

* We really want this library to be lightweight so please don't add features with heavy dependencies.
* Keep the features relevant to the library.
* Before adding a new feature, open up an Issue to discuss it or ping any mods on discord.

## Memberikan Bantuan pada Issue

Saling bantu antar para pengguna terkait pertanyaan-pertanyaan yang diajukan merupakan cara membantu yang terbaik pada komunitas mana pun. Jika Anda bisa membantu siapapun lakukanlah dengan cara terbaik. 🙂
