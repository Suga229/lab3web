<h1>pertanyaan dan tugas</h1>
<h3>Buatlah form yang menampilkan dropdown menu dan listbox dengan multiple selection.</h3>

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Form dengan Dropdown dan Listbox</title>
    </head>
    <body>
        <h2>Pilih fakultas dan Tempat anda kuliah saat ini</h2>

        <form action="#" method="POST">
            <fieldset>
            <label for="dropdown">Pilih Fakultas:</label>
            <select id="dropdown" name="dropdown_option">
                <option value="option1">Teknik</option>
                <option value="option2">Feb</option>
                <option value="option3">Hukum</option>
                <option value="option4">FISIP</option>
            </select>
            <br><br>

            <label for="listbox">Kuliah Di:</label>
            <select id="listbox" name="listbox_options[]" multiple size="3">
                <option value="option1">UPB</option>
                <option value="option2">UPH</option>
                <option value="option3">BSI</option>
                <option value="option4">PRESIDENT</option>
                <option value="option5">UNSIKA</option>
            </select>
            <br><br>
    
            <input type="submit" value="Submit">
            </fieldset>
        </form>
    </body>
    </html>

![image](https://github.com/user-attachments/assets/d61d6414-0e0e-4dcd-afa8-564087c50e84)

<h1>Laporan praktikum</h1>
<h2>membuat list</h2>

        <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
    </head>
    <body>
        <h1>Membuat list</h1>
    </body>
    </html>

<h2>membuat ordered list</h2>

       <section id="order-list">
            <h2>Ordered List</h2>
            <ol>
                <li>Pemrograman Web</li>
                <li>Sistem Informasi</li>
                <li>Basis Data 2</li>
            </ol>
        </section>
        
![image](https://github.com/user-attachments/assets/2d7427fa-bf4a-4832-8a60-5dedd78f8f2f)

<h2>membuat unorder list</h2>

    <section id="unorder-list">
        <h2>Unordered List</h2>
        <ul type="square">
            <li>Jaringan Komputer</li>
            <li>Struktur Data</li>
            <li>Algoritma &amp; Pemrograman</li>
        </ul>
    </section>

![image](https://github.com/user-attachments/assets/e21a2ba0-d701-42f4-a916-20380e3a4011)

<h2>Membuat description list</h2>

    <section id="unorder-list">
        <h2>Description List</h2>
        <dl>
            <dt>Fakultas Teknik</dt>
            <dd>Teknik Industri</dd>
            <dd>Teknik Informatika</dd>
            <dd>Teknik Lingkungan</dd>
            <dt>Fakultas Ekonomi dan Bisnis</dt>
            <dd>Akuntansi</dd>
            <dd>Manajemen</dd>
            <dd>Bisnis Digital</dd>
        </dl>
    </section>

![image](https://github.com/user-attachments/assets/57d34492-d4cb-4b04-a397-71c2356241e2)

<h2>membuat table</h2>

    <table border="1" cellpadding="4" cellspacing="0">
        <thead>
            <tr>
                <th>No.</th>
                <th>Fakultas</th>
                <th>Program Studi</th>
                </tr>
        </thead>
        <tbody>
            <tr>
                <td>1.</td>
                <td>Teknik</td>
                <td>Teknik Informatika</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>Teknik</td>
                <td>Teknik Industri</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>Teknik</td>
                <td>Teknik Lingkungan</td>
            </tr>
        </tbody>
    </table>

![image](https://github.com/user-attachments/assets/21956fcd-16a0-4ab3-86db-994c5bf1fb88)

<h2>menggabungkan sel data</h2>

    <table border="1" cellpadding="4" cellspacing="0">
        <thead>
            <tr>
                <th>No.</th>
                <th>Fakultas</th>
                <th>Program Studi</th>
                </tr>
        </thead>
        <tbody>
            <tr>
                <td>1.</td>
                <td rowspan="3">Teknik</td>
                <td>Teknik Informatika</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>Teknik Industri</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>Teknik Lingkungan</td>
            </tr>
        </tbody>
    </table>

![image](https://github.com/user-attachments/assets/c2d3182a-62e6-4c9a-a105-3b7e8b32d938)

<h2>membuat form</h2>


    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>HTML LANJUTAN</title>
    </head>
    <body>
        <header>
            <h1>membuat form</h1>
        </header>
        
        <form action="proses.php" method="post">
            <fieldset>
                <legend> Data pelanggan</legend>
                <p>
                    <label for="nama">nama</label>
                    <input type="text" id="nama" name="nama">
                </p>
                <p>
                    <label for="alamat">alamat</label>
                    <textarea name="alamat" id="alamat" cols="20" rows="3"></textarea>
                </p>
                <p>
                    <label>Jenis kelamin</label>
                    <input type="radio" id="jk_1" name="kelamin" value="L">
                    <label for="jk_1">laki laki</label>
                    <input type="radio" id="jk_p" name="kelamin" value="P">
                    <label for="jk_p">Perempuan</label>
                </p>
                <p><input type="submit" value="login"></p>
            </fieldset>
        </form>
    </body>
    </html>

![image](https://github.com/user-attachments/assets/f81efb92-4353-4646-863e-972144af8e21)


