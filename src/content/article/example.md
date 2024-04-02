---
title: Sebuah Judul Acrticle Yang Mungkin Sangat Bisa Panjang Sekali Untuk Kamu Yang Baru Memulai Untuk Membaca
slug: example
author: Naufal Rabbani
date: 2020-03-29
time: "11:39"
tags: refleksi, minimalism
is_draft: true
---

Ini harusnya mantul sih jadi kita kek bisa fokus ke kontennya langsung ketimbang harus fokus ke lain-lain.

## Mantul

Yaa gitu jadinya, harus mantul. Kita harus berusaha. Ayok semangat yok.

## Jangan Menyerah

Ayok semangat jangan menyerah

Ada beberapa cara untuk menuliskan CSS, yaitu: Inline Styling, via Style Tag, dan external CSS file. Gimana sih caranya? yuk kita coba satu persatu. Beneran dicoba lho.

### Ini sub Judul gitu ceritanya

Lorem ipsum dolor sit amet, qui minim labore adipisicing minim sint cillum sint consectetur cupidatat.

## Inline Styling

Pada HTML yang telah kita buat sebelumnya, terdapat tag `<h1>` coba tambahkan inline styling pada tag tesebut.

```html
<!-- file location: belajar-santuy/index.html -->

<h1 style="color: blue;">Halo, saya sedang belajar CSS</h1>
```

Jangan bingung dengan titik-titiknya yaa.. itu maksudnya supaya fokus pada tag atau bagian tertentu saja pada file html kita. Kalau versi utuhnya, maka konten dari file HTML teman-teman harusnya seperti gambar di bawah ini:

![inline styling HTML content](/images/baju.jpg)

Coba buka pada browser, maka akan menghasilkan tampilan Heading Text yang berwarna biru. Seperti di bawah ini:

![contoh inline styling CSS](/images/baju.jpg)

Selanjutnya, mari kita breakdown, maksud dari masing-masing syntaxnya.

##### `style="value"`

attribute `style` HTML yang memungkinkan kita untuk melakukan styling pada tag secara langsung. Sedangkan `value` nya adalah syntax CSSnya.

##### `color`

salah satu **property** yang ada di CSS. Fungsinya untuk memberi warna pada text.

##### `blue`

value dari property `color`. property `color` menerima value warna yang berupa text ataupun hex code. misal: `#000000`.

Gimana udah [mulai bingung](https://github.com/BosNaufal)? gapapa... namanya juga belajar, pelan-pelan pemahannnya akan bertambah. Semangat terus yak.

## Style Tag

Selain melakukan styling secara langsung pada tag HTML, kita juga bisa menggunakan tag `<style>`. apa dan gimana sih tag `<style>` itu? yuk kita coba praktikkan.

> Ini halo apa sih ini?

Pada HTML yang telah kita buat sebelumnya, terdapat tag `<head>` coba tambahkan tag `<style>` di dalam tag `<head>` tersebut. Seperti ini:

```html:2-4
<!-- file location: belajar-santuy/index.html -->

<head>
  <title>Belajar CSS santuy</title>
  <style>
    b {
      background: #6E75A8;
      color: white;
      font-size: 20px;
    }
  </style>
</head>
```

Tampilan ketika di browser

![Tampilan saat menggunakan style tag](/images/baju.jpg)

Yuk kita breakdown lagi masing-masing syntaxnya.

##### `<style>...</style>`

Tag yang digunakan untuk **menuliskan CSS pada file HTML**.

##### `b`

**selector** CSS untuk menyeleksi _element_ apa yang hendak kita _styling_. Yang di styling pada contoh di atas adalah element `<b>`.

##### `{...}`

pembuka dan penutup syntax styling pada masing-masing selector. fungsinya sama seperti tag pembuka dan penutup dari HTML. Tapi ini digunakan untuk CSS.

##### `background`

property CSS yang digunakan untuk memberi warna pada latar belakang _element_.

##### `#6E75A8`

value dari property `background` yaitu berupa **kode warna** yang ditulis menggunakan _hexcode_.

##### `font-size`

property CSS yang digunakan untuk mengatur ukuran text atau font pada laman web. valuenya bukan berupa warna, melainkan angka dalam satuan pixel--Bisa juga dalam satuan yang lain.

##### `20px`

value dari property `font-size` yang berupa angka dengan satuan pixel. Tidak harus pixel yaa.. kita juga bisa menggunakan satuan `rem` maupun `em`.

Kali ini lebih menarik karena teman-teman telah berkenalan dengan selector dan lebih banyak lagi `property` CSS dengan `value` selain warna. Kita juga berkenalan dengan angka dengan satuan pixel. Jadi property CSS itu bisa bervariasi value nya. tergantung property nya.

## External CSS File

Dengan menggunakan tag `<style>`, kita telah menuliskan CSS dengan cara yang "lebih rapi". Tapi ada lagi cara yang lebih rapi untuk menuliskan CSS. Tidak hanya rapi, cara ini juga lebih _maintainable_. Yaitu dengan menuliskannya pada file eksternal yang berekstensi `.css`. Yuk praktik lagi yuk.

Buat file kosong, lalu beri nama `santuy.css`.

![Membuat file CSS baru](/images/baju.jpg)

Lah terus bedanya apa dong? bedanya adalah file CSS kita lebih rapi karena berada di luar file HTML. Coba bayangkan jika kita punya laman web yang konten HTML nya saja sudah panjang, terus mau kita tambahkan file CSS nya juga di dalamnya? maka file kita akan sangat amat panjang sekali. Nah, oleh sebab itu, dengan memisahkan antara file HTML dan CSS, maka file HTML kita gak panjang-panjang amat.

Sudah paham kan bagaimana cara menuliskan CSS? Mari kita lanjut dengan memperdetil pemahaman pada bagian-bagian dari syntax CSS. Skuy lah~

---

## Penutup

Setiap detil isi konten dalam artikel ini tidak bermaksud untuk show off, ataupun menghakimi. Melainkan hanya refleksi untuk diri yang ditulis agar dikoreksi.

Sangat terbuka untuk kritik dan saran. Kalau saya salah, mohon dengan sangat untuk diingatkan. Semoga bermanfaat dan jangan lupa **Like and Share~**
