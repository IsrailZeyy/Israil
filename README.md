<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Top Up Game</title>
    <style>
    body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: silver; /* ubah latar belakang menjadi silver */
    color: #000; /* ubah warna teks menjadi hitam */
    margin: 20px auto;
    text-align: center;
    max-width: 1200px;
    padding: 0 20px;
}

h1 {
    font-size: 36px;
    font-weight: bold;
    color: #3498db; /* biru */
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
}

h2 {
    font-size: 24px;
    color: #FFFF00; /* kuning */
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
    margin-top: 40px;
}

/* Ubah warna teks judul Free Fire dan Mobile Legends menjadi biru */
.game-title {
    color: #3498db; /* biru */
}

.price-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 20px;
    margin-top: 20px;
    text-align: center; /* Posisikan konten di tengah */
}

.price-item {
    background-color: rgba(255, 255, 255, 0.1);
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
    width: 200px; 
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    animation: float 3s infinite ease-in-out;
    text-align: center; /* Posisikan konten di tengah */
}

.price-item:hover {
    transform: translateY(-5px);
    box-shadow: 0 15px 30px rgba(0, 0, 0, 0.5);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.price-item h3 {
    margin-top: 0;
    color: #f1c40f; /* ubah warna teks menjadi kuning */
    font-size: 20px;
    margin-bottom: 15px;
    transition: color 0.3s ease;
}

.price-item p {
    color: #f1c40f; /* ubah warna teks menjadi kuning */
    font-size: 16px;
    margin-bottom: 15px;
    transition: color 0.3s ease;
}

.whatsapp-link {
    text-decoration: none;
    color: #fff;
    background-color: #27ae60; /* hijau */
    padding: 10px 15px;
    border-radius: 5px;
    display: inline-block;
    transition: background-color 0.3s ease, transform 0.3s ease;
}

.whatsapp-link:hover {
    background-color: #219653; /* hijau gelap */
    transform: translateY(-3px);
}

@keyframes float {
    0% {
        transform: translateY(0);
    }
    50% {
        transform: translateY(-10px);
    }
    100% {
        transform: translateY(0);
    }
}

/* Tambahkan margin pada elemen-elemen yang diinginkan */
.price-item input,
.whatsapp-link {
    margin-top: 10px;
}

    </style>
</head>
<body>
<h1>Top Up Game</h1>
<h2>Free Fire</h2>
<div class="price-container">
    <div class="price-item">
        5 DM: Rp. 3.000 
        <input type="text" id="nomorTujuanFF5" placeholder="Nomor tujuan">
        <a href="#" onclick="beliProduk('Free Fire', 5, document.getElementById('nomorTujuanFF5').value)" class="whatsapp-link">Beli</a>
    </div>
    <div class="price-item">
        12 DM: Rp. 5.000 
        <input type="text" id="nomorTujuanFF12" placeholder="Nomor tujuan">
        <a href="#" onclick="beliProduk('Free Fire', 12, document.getElementById('nomorTujuanFF12').value)" class="whatsapp-link">Beli</a>
    </div>
    <div class="price-item">
        50 DM: Rp. 10.000 
        <input type="text" id="nomorTujuanFF50" placeholder="Nomor tujuan">
        <a href="#" onclick="beliProduk('Free Fire', 50, document.getElementById('nomorTujuanFF50').value)" class="whatsapp-link">Beli</a>
    </div>
    <div class="price-item">
        75 DM: Rp. 14.000 
        <input type="text" id="nomorTujuanFF75" placeholder="Nomor tujuan">
        <a href="#" onclick="beliProduk('Free Fire', 75, document.getElementById('nomorTujuanFF75').value)" class="whatsapp-link">Beli</a>
    </div>
    <div class="price-item">
        100 DM: Rp. 20.000 
        <input type="text" id="nomorTujuanFF100" placeholder="Nomor tujuan">
        <a href="#" onclick="beliProduk('Free Fire', 100, document.getElementById('nomorTujuanFF100').value)" class="whatsapp-link">Beli</a>
    </div>
    <div class="price-item">
        140 DM: Rp. 25.000 
        <input type="text" id="nomorTujuanFF140" placeholder="Nomor tujuan">
        <a href="#" onclick="beliProduk('Free Fire', 140, document.getElementById('nomorTujuanFF140').value)" class="whatsapp-link">Beli</a>
    </div>
    <div class="price-item">
        200 DM: Rp. 31.000 
        <input type="text" id="nomorTujuanFF200" placeholder="Nomor tujuan">
        <a href="#" onclick="beliProduk('Free Fire', 200, document.getElementById('nomorTujuanFF200').value)" class="whatsapp-link">Beli</a>
    </div>
    <div class="price-item">
        250 DM: Rp. 38.000 
        <input type="text" id="nomorTujuanFF250" placeholder="Nomor tujuan">
        <a href="#" onclick="beliProduk('Free Fire', 250, document.getElementById('nomorTujuanFF250').value)" class="whatsapp-link">Beli</a>
    </div>
    <div class="price-item">
        300 DM: Rp. 45.000 
        <input type="text" id="nomorTujuanFF300" placeholder="Nomor tujuan">
        <a href="#" onclick="beliProduk('Free Fire', 300, document.getElementById('nomorTujuanFF300').value)" class="whatsapp-link">Beli</a>
    </div>
    <div class="price-item">
        355 DM: Rp. 52.000 
        <input type="text" id="nomorTujuanFF355" placeholder="Nomor tujuan">
        <a href="#" onclick="beliProduk('Free Fire', 355, document.getElementById('nomorTujuanFF355').value)" class="whatsapp-link">Beli</a>
    </div>
    <div class="price-item">
        500 DM: Rp. 70.000 
        <input type="text" id="nomorTujuanFF500" placeholder="Nomor tujuan">
        <a href="#" onclick="beliProduk('Free Fire', 500, document.getElementById('nomorTujuanFF500').value)" class="whatsapp-link">Beli</a>
    </div>
    <div class="price-item">
        720 DM: Rp. 97.000 
        <input type="text" id="nomorTujuanFF720" placeholder="Nomor tujuan">
        <a href="#" onclick="beliProduk('Free Fire', 720, document.getElementById('nomorTujuanFF720').value)" class="whatsapp-link">Beli</a>
    </div>
    <div class="price-item">
        Membership Mingguan: Rp. 35.000 
        <input type="text" id="nomorTujuanFFMembershipMingguan" placeholder="Nomor tujuan">
        <a href="#" onclick="beliProduk('Free Fire', 'Membership Mingguan', document.getElementById('nomorTujuanFFMembershipMingguan').value)" class="whatsapp-link">Beli</a>
    </div>
    <div class="price-item">
        Membership Bulanan: Rp. 90.000 
        <input type="text" id="nomorTujuanFFMembershipBulanan" placeholder="Nomor tujuan">
        <a href="#" onclick="beliProduk('Free Fire', 'Membership Bulanan', document.getElementById('nomorTujuanFFMembershipBulanan').value)" class="whatsapp-link">Beli</a>
    </div>
</div>
<h2>Mobile Legends</h2>
<div class="price-container">
    <div class="price-item">
        5 DM: Rp. 3.000 
        <input type="text" id="nomorTujuanML5" placeholder="Nomor tujuan">
        <a href="#" onclick="beliProduk('Mobile Legends', 5, document.getElementById('nomorTujuanML5').value)" class="whatsapp-link">Beli</a>
    </div>
    <div class="price-item">
        12 DM: Rp. 5.000 
        <input type="text" id="nomorTujuanML12" placeholder="Nomor tujuan">
        <a href="#" onclick="beliProduk('Mobile Legends', 12, document.getElementById('nomorTujuanML12').value)" class="whatsapp-link">Beli</a>
    </div>
    <div class="price-item">
        28 DM: Rp. 11.000 
        <input type="text" id="nomorTujuanML28" placeholder="Nomor tujuan">
        <a href="#" onclick="beliProduk('Mobile Legends', 28, document.getElementById('nomorTujuanML28').value)" class="whatsapp-link">Beli</a>
    </div>
    <div class="price-item">
        36 DM: Rp. 14.000 
        <input type="text" id="nomorTujuanML36" placeholder="Nomor tujuan">
        <a href="#" onclick="beliProduk('Mobile Legends', 36, document.getElementById('nomorTujuanML36').value)" class="whatsapp-link">Beli</a>
    </div>
    <div class="price-item">
        44 DM: Rp. 16.000 
        <input type="text" id="nomorTujuanML44" placeholder="Nomor tujuan">
        <a href="#" onclick="beliProduk('Mobile Legends', 44, document.getElementById('nomorTujuanML44').value)" class="whatsapp-link">Beli</a>
    </div>
    <div class="price-item">
        75 DM: Rp. 24.000 
        <input type="text" id="nomorTujuanML75" placeholder="Nomor tujuan">
        <a href="#" onclick="beliProduk('Mobile Legends', 75, document.getElementById('nomorTujuanML75').value)" class="whatsapp-link">Beli</a>
    </div>
    <div class="price-item">
        86 DM: Rp. 27.000 
        <input type="text" id="nomorTujuanML86" placeholder="Nomor tujuan">
        <a href="#" onclick="beliProduk('Mobile Legends', 86, document.getElementById('nomorTujuanML86').value)" class="whatsapp-link">Beli</a>
    </div>
    <div class="price-item">
        172 DM: Rp. 50.000 
        <input type="text" id="nomorTujuanML172" placeholder="Nomor tujuan">
        <a href="#" onclick="beliProduk('Mobile Legends', 172, document.getElementById('nomorTujuanML172').value)" class="whatsapp-link">Beli</a>
    </div>
    <div class="price-item">
        240 DM: Rp. 67.000 
        <input type="text" id="nomorTujuanML240" placeholder="Nomor tujuan">
        <a href="#" onclick="beliProduk('Mobile Legends', 240, document.getElementById('nomorTujuanML240').value)" class="whatsapp-link">Beli</a>
    </div>
    <div class="price-item">
        250 DM: Rp. 38.000 
        <input type="text" id="nomorTujuanML250" placeholder="Nomor tujuan">
        <a href="#" onclick="beliProduk('Mobile Legends', 250, document.getElementById('nomorTujuanML250').value)" class="whatsapp-link">Beli</a>
    </div>
    <div class="price-item">
        296 DM: Rp. 82.000 
        <input type="text" id="nomorTujuanML296" placeholder="Nomor tujuan">
        <a href="#" onclick="beliProduk('Mobile Legends', 296, document.getElementById('nomorTujuanML296').value)" class="whatsapp-link">Beli</a>
    </div>
    <div class="price-item">
        370 DM: Rp. 102.000 
        <input type="text" id="nomorTujuanML370" placeholder="Nomor tujuan">
        <a href="#" onclick="beliProduk('Mobile Legends', 370, document.getElementById('nomorTujuanML370').value)" class="whatsapp-link">Beli</a>
    </div>
    <div class="price-item">
        Weekly DM Pass: Rp. 40.000 
        <input type="text" id="nomorTujuanMLWeekly" placeholder="Nomor tujuan">
        <a href="#" onclick="beliProduk('Mobile Legends', 'Weekly DM Pass', document.getElementById('nomorTujuanMLWeekly').value)" class="whatsapp-link">Beli</a>
    </div>
</div>
<script>
function beliProduk(game, jumlahDM, nomorTujuan) {
    // Logika untuk memproses pembelian
    console.log(`Membeli ${jumlahDM} DM di ${game} untuk nomor tujuan ${nomorTujuan}`);
    
    // Ganti link WhatsApp di bawah ini dengan link WhatsApp yang baru
    var nomorWhatsApp = '6282245184223'; // Nomor WhatsApp yang baru
    var pesan = encodeURIComponent(`Halo, saya tertarik untuk membeli ${jumlahDM} DM di ${game}. Mohon dibantu prosesnya.`);
    var url = `https://wa.me/${nomorWhatsApp}?text=${pesan}%20-%20Nomor%20tujuan%3A%20${nomorTujuan}`;
    window.open(url, '_blank');
}

</script>
</body>
</html>
