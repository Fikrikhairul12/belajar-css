Flexbox:
model layout 1 dimensi yg dpt mengatur jarak dn penjajaran antar item dl sbuah container

dimensi:
hanya dpt mengatur 1 dimensi pd saat tertentu, antara baris atau kolom, tidak bisa keduanya sekaligus

flexbox layout module:
sebuah modul yg menawarkan cara yg efektif untk menyusun, mensejajarkan dn mndistribusikan jarak antar item di dalam sebuah container, meskipun ukurannya dinamis atau bhkn tdk tau.

note:
- wadah sbgai 'container' dsbt juga dgn 'parent'
- element ddlm sbgai 'item' disebut juga dgn 'childs'
- main axis: ketika element sejajar scra horizontal / sumbu utama dri sefruit container yg mnentukan urutan dri penempatan items scra horizontal 
- cross axis: ketika element sejajar scra vertikal
- main size: ukuran container / ukuran (width/height) dari container yg akan membuat dimensi dari item ny relatif trhdp main size 
- cross size: ukuran item
- main start: awal element
- main end: akhir element
- untuk vertikal cross start dn cross end

property container:
- display: flex; | membuat element parent mnjdi flexbox, dan membuat element-element d dlmny bisa berperilaku flex juga
- flex-direction: row | row-reverse | column | column-reverse; | mengatur arah/urutan dlm container
- flex-wrap: nowrap | wrap | wrap-reverse; | wrap memungkinkn memindhkn items
- justify-content: flex-start | flex-end | center | space-between | space around | space-evently; | mengatur jarak antar item 
- align-items: flex-start | flex-end | center | stretch | baseline; | mengatur perilaku penjajaran item terhadap cross axis
- align-content: flex-start | flex-end | center | space-between | space-around; | mengatur jarak antar items terhadap cross axis (hanya berfungsi ketika items lebih dari 1 baris)

property items:
- order | mengatur urutan antar items
- flex-grow | ukuran items
- align-self: auto | flex-start | flex-end | center | baseline | stretch; | mengatur perilaku penjajaran sebuah item yg spesifik trhdp cross axis