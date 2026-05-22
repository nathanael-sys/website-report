<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Website Report Siswa</title>

    <style>

        *{
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body{
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.6;
        }

        header{
            background-color: #1e3a8a;
            color: white;
            text-align: center;
            padding: 25px;
        }

        header h1{
            margin-bottom: 10px;
        }

        section{
            background-color: white;
            margin: 20px;
            padding: 20px;
            border-radius: 10px;
        }

        .biodata{
            display: flex;
            align-items: center;
            gap: 20px;
        }

        .biodata img{
            width: 170px;
            height: 170px;
            object-fit: cover;
            border-radius: 10px;
            border: 3px solid #da7f11;
        }

        .deskripsi p{
            margin-top: 10px;
            text-align: justify;
        }

        table{
            width: 100%;
            border-collapse: collapse;
            margin-top: 15px;
        }

        table, th, td{
            border: 1px solid #999;
        }

        th{
            background-color: #d43313;
            color: white;
        }

        th, td{
            padding: 10px;
            text-align: center;
        }

        tr:nth-child(even){
            background-color: #f2f2f2;
        }

        .card-container{
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
            margin-top: 15px;
            justify-content: center;
        }

        .card{
            background-color: #e5e7eb;
            padding: 20px;
            border-radius: 10px;
            width: 300px;
            transition: 0.3s;
        }

        .card:hover{
            transform: scale(1.03);
        }

        .card h3{
            margin-bottom: 10px;
        }

        button{
            margin-top: 10px;
            padding: 10px 15px;
            border: none;
            background-color: #6d7ea2;
            color: white;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover{
            background-color: #1d4ed8;
        }


        footer{
            text-align: center;
            padding: 20px;
            background-color: #616d8f;
            color: white;
            margin-top: 20px;
        }

        /* RESPONSIVE */

        @media(max-width: 768px){

            .biodata{
                flex-direction: column;
                text-align: center;
            }

            .card-container{
                flex-direction: column;
            }

            .card{
                width: 100%;
            }
        }

    </style>
</head>

<body>

    <header>
        <h1>Website Report Siswa</h1>

        <p>Mata Pelajaran Teknologi Informasi dan Komunikasi</p>

        <p>Kelas XI SMA</p>
    </header>

    <section>

        <h2>Biodata Siswa</h2>

        <div class="biodata">

            <!-- GANTI FOTO -->
            <img src="WhatsApp Image 2026-05-19 at 16.18.35.jpeg" alt="Foto Profil">

            <div>

                <p><strong>Nama Lengkap:</strong> Aloysius Nathanael Aditya Setyawan</p>

                <p><strong>Kelas:</strong> XI-S8</p>

                <p><strong>Sekolah:</strong> SMA Kanisius Jakarta</p>

                <p><strong>Hobi:</strong> Bermain game dan mendengarkan musik</p>

                <p><strong>Cita-cita:</strong>Business Man</p>

            </div>

        </div>

    </section>


    <section class="deskripsi">

        <h2>Deskripsi Singkat</h2>

        <p>
            Saya adalah siswa kelas XI yang sebenarnya tidak begitu memiliki minat 
            terhadap bidang TIK/Informatika. Pada saat pelajaran TIK/Informatika,
            tentu saja saya mengalami kesulitan untuk memahami materi atau praktik
            yang diberikan, sehingga seringkali meminta bantuan kepada teman/guru. Namun
            seiring berjalannya waktu, pembelajaran TIK memberikan berbagai makna dan
            pembelajaran penting terkait pembuatan website, hal dasar HTML, CSS, yang
            banyak digunakan dalam pembuatan website-website brand ternama. Saya berharap
            pembelajaran TIK ini dapat memberikan pengalaman dan penambahan ilmu yang berguna
            untuk masa depan saya.
        </p>

    </section>


    <section>

        <h2>Tabel Nilai Semester</h2>

        <table>

            <tr>
                <th>No</th>
                <th>Materi</th>
                <th>Nilai</th>
            </tr>

            <tr>
                <td>1</td>
                <td>Akuntansi</td>
                <td>90</td>
            </tr>

            <tr>
                <td>2</td>
                <td>Agama</td>
                <td>88</td>
            </tr>

            <tr>
                <td>3</td>
                <td>PJOK</td>
                <td>85</td>
            </tr>

            <tr>
                <td>4</td>
                <td>Ekonomi</td>
                <td>92</td>
            </tr>

            <tr>
                <td>5</td>
                <td>Matematika</td>
                <td>89</td>
            </tr>

        </table>

    </section>

    <section>

        <h2>Project Website</h2>

        <div class="card-container">

            <div class="card">

                <h3>Project 1</h3>

                <p>
                    Website sederhana tentang profil diri menggunakan HTML.
                </p>

                <button onclick="project1()">
                    Lihat Project
                </button>

            </div>


            <div class="card">

                <h3>Project 2</h3>

                <p>
                    Website galeri foto sederhana menggunakan CSS.
                </p>

                <button onclick="project2()">
                    Lihat Project
                </button>

            </div>


            <div class="card">

                <h3>Project 3</h3>

                <p>
                    Website interaktif sederhana menggunakan JavaScript.
                </p>

                <button onclick="project3()">
                    Lihat Project
                </button>

            </div>

        </div>

    </section>

    <footer>

        <p>
            © 2026 Website Report Siswa | TIK Kelas XI
        </p>

    </footer>


    <script>

        console.log("Website berhasil dijalankan!");

        alert("Selamat datang di Website Report Siswa!");

        function project1(){

            alert(
                "Project 1\n\n" +
                "Website sederhana tentang profil diri menggunakan HTML."
            );

        }

        function project2(){

            alert(
                "Project 2\n\n" +
                "Website galeri foto sederhana menggunakan CSS."
            );

        }

        function project3(){

            alert(
                "Project 3\n\n" +
                "Website interaktif sederhana menggunakan JavaScript."
            );

        }

    </script>

</body>
</html>
