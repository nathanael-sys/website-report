<!DOCTYPE html>
<html lang="id">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Website Report Siswa</title>

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap"
        rel="stylesheet">

    <style>

        *{
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body{
            font-family: 'Poppins', sans-serif;
            background: #f5f7fb;
            color: #333;
            line-height: 1.7;
        }


        .container{
            max-width: 1200px;
            margin: auto;
            padding: 20px;
        }


        header{
            background: linear-gradient(135deg, #1e3a8a, #3b82f6);
            color: white;
            padding: 70px 20px;
            text-align: center;
            border-bottom-left-radius: 30px;
            border-bottom-right-radius: 30px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }

        header h1{
            font-size: 45px;
            margin-bottom: 10px;
        }

        header p{
            font-size: 18px;
            opacity: 0.95;
        }


        section{
            background-color: white;
            margin-top: 30px;
            padding: 30px;
            border-radius: 20px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.08);
            transition: 0.3s;
        }

        section:hover{
            transform: translateY(-3px);
        }

        section h2{
            margin-bottom: 20px;
            color: #1e3a8a;
            font-size: 28px;
        }


        .biodata{
            display: flex;
            align-items: center;
            gap: 40px;
        }

        .biodata img{
            width: 220px;
            height: 220px;
            object-fit: cover;
            border-radius: 20px;
            border: 5px solid #3b82f6;
            box-shadow: 0 5px 15px rgba(0,0,0,0.15);
        }

        .bio-text p{
            margin-bottom: 10px;
            font-size: 17px;
        }

        .bio-text strong{
            color: #1e3a8a;
        }


        .deskripsi p{
            text-align: justify;
            font-size: 17px;
        }


        table{
            width: 100%;
            border-collapse: collapse;
            overflow: hidden;
            border-radius: 15px;
            margin-top: 15px;
        }

        th{
            background-color: #1e3a8a;
            color: white;
        }

        th, td{
            padding: 15px;
            text-align: center;
            border: 1px solid #ddd;
        }

        tr:nth-child(even){
            background-color: #f1f5f9;
        }

        tr:hover{
            background-color: #dbeafe;
        }

        .card-container{
            display: flex;
            gap: 25px;
            flex-wrap: wrap;
            justify-content: center;
        }

        .card{
            background: linear-gradient(135deg, #eff6ff, #dbeafe);
            width: 320px;
            padding: 25px;
            border-radius: 20px;
            transition: 0.3s;
            box-shadow: 0 5px 15px rgba(0,0,0,0.08);
        }

        .card:hover{
            transform: translateY(-8px) scale(1.02);
        }

        .card h3{
            color: #1e3a8a;
            margin-bottom: 15px;
            font-size: 24px;
        }

        .card p{
            margin-bottom: 15px;
        }

        button{
            background: linear-gradient(135deg, #2563eb, #1d4ed8);
            color: white;
            border: none;
            padding: 12px 20px;
            border-radius: 10px;
            cursor: pointer;
            font-size: 15px;
            font-weight: 500;
            transition: 0.3s;
        }

        button:hover{
            transform: scale(1.05);
            opacity: 0.95;
        }


        footer{
            margin-top: 40px;
            background: #1e293b;
            color: white;
            text-align: center;
            padding: 25px;
        }


        .top-btn{
            position: fixed;
            bottom: 25px;
            right: 25px;
            background-color: #2563eb;
            color: white;
            border: none;
            padding: 15px 18px;
            border-radius: 50%;
            cursor: pointer;
            font-size: 18px;
            display: none;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }


        @media(max-width: 768px){

            header h1{
                font-size: 32px;
            }

            .biodata{
                flex-direction: column;
                text-align: center;
            }

            .biodata img{
                width: 180px;
                height: 180px;
            }

            .card{
                width: 100%;
            }

            section{
                padding: 20px;
            }
        }

    </style>

</head>

<body>


    <header>

        <h1>Website Report Siswa</h1>

        <p>Mata Pelajaran Teknologi Informasi dan Komunikasi</p>

        <p>Kelas XI SMA Kanisius Jakarta</p>

    </header>

    <div class="container">

        <section>

            <h2>Biodata Siswa</h2>

            <div class="biodata">

                <!-- GANTI FOTO -->
                <img src="foto.jpg" alt="Foto Profil">

                <div class="bio-text">

                    <p><strong>Nama Lengkap:</strong> Aloysius Nathanael Aditya Setyawan</p>

                    <p><strong>Kelas:</strong> XI-S8</p>

                    <p><strong>Sekolah:</strong> SMA Kanisius Jakarta</p>

                    <p><strong>Hobi:</strong> Bermain game dan mendengarkan musik</p>

                    <p><strong>Cita-cita:</strong> Business Man</p>

                </div>

            </div>

        </section>

        <section class="deskripsi">

            <h2>Deskripsi Singkat</h2>

            <p>
                Saya adalah siswa kelas XI yang sebenarnya tidak begitu memiliki minat
                terhadap bidang TIK/Informatika. Pada saat pelajaran TIK/Informatika,
                saya sering mengalami kesulitan dalam memahami materi maupun praktik
                yang diberikan. Namun, seiring berjalannya waktu, saya mulai memahami
                bahwa pembelajaran TIK memiliki manfaat yang besar dalam kehidupan modern,
                terutama dalam bidang teknologi dan pengembangan website. Melalui pembelajaran
                HTML, CSS, dan JavaScript, saya memperoleh pengalaman baru tentang bagaimana
                sebuah website dibuat dan dikembangkan. Saya berharap ilmu yang saya pelajari
                dapat bermanfaat bagi masa depan saya serta membantu saya untuk terus berkembang
                di era digital saat ini.
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
                        Website sederhana mengenai profil diri menggunakan HTML dasar.
                    </p>

                    <button onclick="project1()">
                        Lihat Project
                    </button>

                </div>

                <div class="card">

                    <h3>Project 2</h3>

                    <p>
                        Website galeri sederhana menggunakan desain CSS modern.
                    </p>

                    <button onclick="project2()">
                        Lihat Project
                    </button>

                </div>

                <div class="card">

                    <h3>Project 3</h3>

                    <p>
                        Website interaktif menggunakan JavaScript sederhana.
                    </p>

                    <button onclick="project3()">
                        Lihat Project
                    </button>

                </div>

            </div>

        </section>

    </div>

    <footer>

        <p>
            © 2026 Website Report Siswa | TIK Kelas XI
        </p>

    </footer>
    

    <button class="top-btn" id="topBtn" onclick="scrollToTop()">
        ↑
    </button>

    <script>

        console.log("Website berhasil dijalankan!");

        alert("Selamat datang di Website Report Siswa!");

        function project1(){

            alert(
                "Project 1\n\n" +
                "Website sederhana mengenai profil diri menggunakan HTML dasar."
            );

        }

        function project2(){

            alert(
                "Project 2\n\n" +
                "Website galeri sederhana menggunakan desain CSS modern."
            );

        }

        function project3(){

            alert(
                "Project 3\n\n" +
                "Website interaktif menggunakan JavaScript sederhana."
            );

        }


        let topBtn = document.getElementById("topBtn");

        window.onscroll = function(){

            if(document.body.scrollTop > 200 || document.documentElement.scrollTop > 200){

                topBtn.style.display = "block";

            } else {

                topBtn.style.display = "none";

            }

        };

        function scrollToTop(){

            window.scrollTo({
                top: 0,
                behavior: "smooth"
            });

        }

    </script>

</body>

</html>
