wedding-invitation/

│

├── index.html

├── style.css

├── script.js

└── assets/

&nbsp;   ├── foto1.jpg

&nbsp;   ├── foto2.jpg

&nbsp;   └── music.mp3 (optional)

<!DOCTYPE html>

<html lang="id">

<head>

<meta charset="UTF-8">

<title>Undangan Pernikahan</title>

<link rel="stylesheet" href="style.css">

</head>



<body>



<header>

&nbsp; <h1>Undangan Pernikahan</h1>

&nbsp; <h2>Andi \& Sinta</h2>

&nbsp; <p>12 Desember 2026</p>

</header>



<section class="event">

&nbsp; <h3>Akad Nikah</h3>

&nbsp; <p>Sabtu, 12 Desember 2026</p>

&nbsp; <p>08.00 WIB</p>

&nbsp; <p>Hotel Bahagia, Surabaya</p>

</section>



<section class="event">

&nbsp; <h3>Resepsi</h3>

&nbsp; <p>12.00 - 15.00 WIB</p>

</section>



<section class="gallery">

&nbsp; <img src="assets/foto1.jpg">

&nbsp; <img src="assets/foto2.jpg">

</section>



<section class="rsvp">

&nbsp; <h3>RSVP</h3>

&nbsp; <form>

&nbsp;   <input type="text" placeholder="Nama">

&nbsp;   <select>

&nbsp;     <option>Hadir</option>

&nbsp;     <option>Tidak Hadir</option>

&nbsp;   </select>

&nbsp;   <button>Kirim</button>

&nbsp; </form>

</section>



<footer>

&nbsp; <p>Terima kasih atas doa restunya</p>

</footer>



</body>

</html>

body {

&nbsp; font-family: serif;

&nbsp; margin: 0;

&nbsp; text-align: center;

&nbsp; background: #faf6f2;

}



header {

&nbsp; padding: 80px 20px;

&nbsp; background: #e8dcd0;

}



h1, h2 {

&nbsp; margin: 10px 0;

}



.event {

&nbsp; padding: 40px;

}



.gallery img {

&nbsp; width: 200px;

&nbsp; margin: 10px;

&nbsp; border-radius: 12px;

}



button {

&nbsp; padding: 10px 20px;

&nbsp; border: none;

&nbsp; background: #c7a17a;

&nbsp; color: white;

&nbsp; border-radius: 8px;

}

console.log("Wedding Invitation Loaded");

