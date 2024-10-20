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

