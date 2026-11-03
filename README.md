# untuk_adel
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday Adel! 🎉</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            /* Menggunakan gambar bunga lily pink estetik online agar latar belakang pasti muncul di HP */
            background: linear-gradient(rgba(255, 240, 245, 0.45), rgba(255, 194, 209, 0.45)), 
                        url('https://unsplash.com') no-repeat center center fixed;
            background-size: cover;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            overflow-x: hidden;
            padding: 40px 0;
        }
        .wrapper {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 30px;
            width: 100%;
            z-index: 10;
        }
        .container {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
            padding: 35px 30px;
            border-radius: 24px;
            box-shadow: 0 15px 35px rgba(255, 112, 150, 0.25);
            text-align: center;
            max-width: 460px;
            width: 90%;
            border: 2px solid rgba(255, 133, 161, 0.5);
        }
        h1 {
            color: #d9406f;
            font-size: 2.3rem;
            margin-bottom: 10px;
            font-family: 'Georgia', serif;
        }
        .age-badge {
            display: inline-block;
            background: linear-gradient(45deg, #ff7096, #ff85a1);
            color: white;
            padding: 6px 20px;
            border-radius: 50px;
            font-weight: bold;
            font-size: 1.1rem;
            margin-bottom: 25px;
            box-shadow: 0 4px 10px rgba(255, 112, 150, 0.3);
        }
        .letter-box {
            background: rgba(255, 240, 243, 0.85);
            border: 1.5px dashed #ff85a1;
            border-radius: 18px;
            padding: 22px;
            text-align: left;
            color: #4a4a4a;
            line-height: 1.7;
            font-size: 1.05rem;
            margin-bottom: 25px;
        }
        .gallery-title {
            color: #d9406f;
            font-family: 'Georgia', serif;
            font-size: 1.6rem;
            margin-top: 15px;
            background: rgba(255,255,255,0.85);
            padding: 6px 20px;
            border-radius: 50px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
        }
        .gallery-container {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 20px;
            width: 90%;
            max-width: 460px;
        }
        .polaroid {
            background: white;
            padding: 10px 10px 30px 10px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.15);
            border-radius: 8px;
            transition: transform 0.3s ease;
        }
        .polaroid img {
            width: 100%;
            height: 180px;
            object-fit: cover;
            border-radius: 4px;
            background-color: #f5f5f5;
        }
        .p1 { transform: rotate(-3deg); }
        .p2 { transform: rotate(3deg); }
        .p3 { transform: rotate(-2deg); }
        .p4 { transform: rotate(4deg); }
        
        .polaroid:hover {
            transform: scale(1.05) rotate(0deg) !important;
            z-index: 20;
            box-shadow: 0 15px 35px rgba(217, 64, 111, 0.35);
        }
        .btn-surprise {
            background: linear-gradient(45deg, #d9406f, #ff7096);
            color: white;
            border: none;
            padding: 14px 35px;
            font-size: 1.1rem;
            font-weight: bold;
            border-radius: 50px;
            cursor: pointer;
            box-shadow: 0 6px 20px rgba(217, 64, 111, 0.4);
        }
        .petal {
            position: absolute;
            background: #ffb3c6;
            border-radius: 150% 0 150% 0;
            opacity: 0.6;
            z-index: 1;
            animation: floatDown 7s linear infinite;
            bottom: 100vh;
        }
        @keyframes floatDown {
            0% { transform: translateY(0) rotate(0deg); opacity: 0; }
            10% { opacity: 0.7; }
            100% { transform: translateY(110vh) rotate(360deg); opacity: 0; }
        }
    </style>
</head>
<body>

    <div class="wrapper">
        <div class="container">
            <h1>Happy Birthday, Adel! 🌸</h1>
            <div class="age-badge">19 Years Old ✨</div>
            
            <div class="letter-box">
                <p>HAPPY BIRTHDAY ADEL, udahh ga kerasa ajaa mu umur 19 ni yaaa, bentarr lagii kepala dua tuu, mampuslah mau udah dekat kepala dua hahaha...</p>
                <br>
                <p>Semogaa diumur mu yang sekarang sampe seterusnya banyakk kebahagiaan yang datang, semogaa dikelilingi orang orangnya sayang kepada mu, salah satu nya akuu hehee. Segala doa yang baik untuk mu yaa dell, hidup lebih lamaa yaa del, sehat selalu... ❤️</p>
            </div>

            <button class="btn-surprise" onclick="popSurprise()">Klik Kejutan! 🎉</button>
        </div>

        <h2 class="gallery-title">Our Moments ✨</h2>
        <div class="gallery-container">
            <div class="polaroid p1">
                <!-- Foto 1: Bunga mawar estetik online -->
                <img src="https://unsplash.com" alt="Flowers">
            </div>
            <div class="polaroid p2">
                <!-- Foto 2: Momen kembang api estetik online -->
                <img src="https://unsplash.com" alt="Moments">
            </div>
            <div class="polaroid p3">
                <!-- Foto 3: Siluet estetik senja online -->
                <img src="https://unsplash.com" alt="Together">
            </div>
            <div class="polaroid p4">
                <!-- Foto 4: Bunga tulip pink estetik online -->
                <img src="https://unsplash.com" alt="Adel">
            </div>
        </div>
    </div>

    <script>
        function createPetal() {
            const petal = document.createElement('div');
            petal.classList.add('petal');
            const size = Math.random() * 15 + 10;
            petal.style.width = size + 'px';
            petal.style.height = (size * 1.5) + 'px';
            petal.style.left = Math.random() * 100 + 'vw';
            petal.style.animationDuration = (Math.random() * 4 + 5) + 's';
            
            const colors = ['#ffb3c6', '#ffc2d1', '#ffe5ec', '#ffa6c9'];
            petal.style.backgroundColor = colors[Math.floor(Math.random() * colors.length)];
            petal.style.transform = `rotate(${Math.random() * 90}deg)`;
            
            document.body.appendChild(petal);
            setTimeout(() => { petal.remove(); }, 9000);
        }
        setInterval(createPetal, 400);

        function popSurprise() {
            alert("Selamat 19 tahun, Adel! Ditunggu traktirannya sebelum masuk kepala dua yaaa! 🌸✨🥳");
        }
    </script>
</body>
</html>
