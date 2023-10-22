<table>
  <tr>
    <th colspan="2">DATA MAHASISWA</th>
  </tr>
  <tr>
    <td>Nama</td>
    <td>Muhammad Arifin</td>
  </tr>
  <tr>
    <td>NIM</td>
    <td>312210330</td>
  </tr>
  <tr>
    <td>Kelas</td>
    <td>TI.22.A3</td>
  </tr>
</table>

# <p align="center">Praktikum4 : CSS Layout</p>

# 1. Membuat Box Element

### Langkah-langkah praktikum

- Persiapan membuat dokumen HTML dengan nama file <b>lab4_box.html</b> seperti berikut:

      <!DOCTYPE html>
      <html lang="en">
      <head>
          <meta charset="UTF-8">
          <meta http-equiv="X-UA-Compatible" content="IE=edge">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>Box Element</title>
      </head>
      <body>
          <header>
              <h1>Box Element</h1>
          </header>
      </body>
      </html>

### Membuat Box Element

- Kemudian tambahkan kode untuk membuat box element dengan tag div seperti berikut:

      <section>
          <div class="div1">Div 1</div>
          <div class="div2">Div 2</div>
          <div class="div3">Div 3</div>
          <div class="div4">Div 4</div>
      </section>

### CSS Float Property

- Selanjutnya tambahkan deklarasi CSS pada head untuk membuat float element, seperti berikut:

      <style>
          div {
          float:left;
          padding: 10px; 
          }
          .div1 {
          background: red;
          }
          .div2 {
          background: yellow;
          }
          .div3 {
          background: green;
          }
          .div4 {
          background-color: blue;
          clear: both;
          float: none;
          }
         </style>

- Kemudian buka browser untuk melihat hasilnya.
<img width="960" alt="Screenshot 2023-10-22 224813" src="https://github.com/marifinnnnn/Lab4Web/assets/115518274/eda32b5d-5cf5-4267-a64f-a20e70100f78">

### Mengatur Clearfix Element

- <b>Clearfix</b> digunakan untuk mengatur element setelah float element. Property <i>clear</i> digunakan untuk mengaturnya.

- Tambahkan element div lainnya seteleah div3 seperti berikut:

      <section>
        <div class="div1">Div 1</div>
        <div class="div2">Div 2</div>
        <div class="div3">Div 3</div>
        <div class="div4">Div 4</div>
      </section>

- Kemudian atur property clear pada CSS, seperti berikut:
  
      .div4 {
        background-color: blue;
        clear: left;
        float:
      ]

- Selanjutnya buka browser dan refresh kembali.
<img width="960" alt="Screenshot 2023-10-22 225009" src="https://github.com/marifinnnnn/Lab4Web/assets/115518274/acc0f0cb-e4de-4c95-a729-7ea376edce5c">

### Melakukan validasi dokumen html ```lab4_box.html``` dengan mengakses http://validator.w3.org
