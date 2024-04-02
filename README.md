<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Laundry Form</title>
</head>

<body>


<h2>Form Laundry</h2>

<form action="/submit_laundry" method="post">
    <label for="nama">Nama Pelanggan:</label><br>
    <input type="text" id="nama" name="nama"><br><br>

    <label for="nomor">nomor :</label><br>
    <input type="text"id="nomor hp" name="nomor hp"><br><br>
    
    <label for="berat">Berat Pakaian (kg):</label><br>
    <input type="number" id="berat" name="berat" min="1" step="any"><br><br>
    
    <label for="jenis">Jenis Layanan:</label><br>
    <select id="jenis" name="jenis">
        <option value="Cuci Kering Setrika">Cuci Kering Setrika</option>
        <option value="Cuci Kering">Cuci Kering</option>
        <option value="Setrika">Setrika</option>
    </select><br><br>
    
    <label for="alamat">Alamat Pengantaran:</label><br>
    <textarea id="alamat" name="alamat" rows="4" cols="50"></textarea><br><br>
    
    <input type="submit" value="Submit">
</form>

</body>
</html>
