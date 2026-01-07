#Dwell-
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <title>DWELL - Bất động sản Nhà Phố Sài Gòn</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', sans-serif;
        }

        body {
            background: #f5f5f5;
            color: #333;
        }

        header {
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)),
                        url('https://images.unsplash.com/photo-1501183638710-841dd1904471') center/cover;
            height: 100vh;
            color: white;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
        }

        header h1 {
            font-size: 60px;
            letter-spacing: 4px;
            color: #f4c430;
        }

        header p {
            font-size: 20px;
            margin: 20px 0;
        }

        .btn {
            display: inline-block;
            padding: 12px 30px;
            background: #f4c430;
            color: #000;
            text-decoration: none;
            font-weight: bold;
            border-radius: 30px;
        }

        section {
            padding: 80px 10%;
            background: white;
        }

        section h2 {
            text-align: center;
            font-size: 36px;
            margin-bottom: 40px;
            color: #0b2c3d;
        }

        .about, .services, .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
        }

        .box {
            padding: 30px;
            border-radius: 10px;
            background: #f9f9f9;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }

        .box h3 {
            color: #f4c430;
            margin-bottom: 15px;
        }

        .contact {
            background: #0b2c3d;
            color: white;
        }

        .contact form {
            max-width: 500px;
            margin: auto;
            display: flex;
            flex-direction: column;
        }

        .contact input, .contact textarea {
            margin: 10px 0;
            padding: 12px;
            border-radius: 5px;
            border: none;
        }

        footer {
            background: #000;
            color: #aaa;
            text-align: center;
            padding: 20px;
        }

        @media(max-width:768px) {
            header h1 {
                font-size: 40px;
            }
        }
    </style>
</head>
<body>

<header>
    <div>
        <h1>DWELL</h1>
        <p>Bất Động Sản Nhà Phố Sài Gòn</p>
        <a href="#contact" class="btn">Liên hệ ngay</a>
    </div>
</header>

<section>
    <h2>Về DWELL</h2>
    <div class="about">
        <div class="box">
            <h3>Chuyên nhà phố</h3>
            <p>Tập trung vào nhà phố trung tâm Sài Gòn, pháp lý rõ ràng, giá trị cao.</p>
        </div>
        <div class="box">
            <h3>Uy tín – Minh bạch</h3>
            <p>Thông tin chính xác, hỗ trợ pháp lý từ A–Z cho khách hàng.</p>
        </div>
        <div class="box">
            <h3>Giá trị bền vững</h3>
            <p>Đầu tư an toàn, sinh lời ổn định theo thời gian.</p>
        </div>
    </div>
</section>

<section style="background:#f5f5f5;">
    <h2>Dịch vụ</h2>
    <div class="services">
        <div class="box">
            <h3>Mua bán nhà phố</h3>
            <p>Tư vấn và giao dịch nhà phố khu trung tâm TP.HCM.</p>
        </div>
        <div class="box">
            <h3>Đầu tư BĐS</h3>
            <p>Phân tích tiềm năng và chiến lược đầu tư hiệu quả.</p>
        </div>
        <div class="box">
            <h3>Tư vấn pháp lý</h3>
            <p>Hỗ trợ sổ hồng, công chứng, sang tên.</p>
        </div>
    </div>
</section>

<section>
    <h2>Dự án tiêu biểu</h2>
    <div class="projects">
        <div class="box">
            <h3>Nhà phố Quận 1</h3>
            <p>Vị trí vàng – giá trị sinh lời cao.</p>
        </div>
        <div class="box">
            <h3>Nhà phố Quận 3</h3>
            <p>Khu dân trí cao – pháp lý chuẩn.</p>
        </div>
        <div class="box">
            <h3>Nhà phố Phú Nhuận</h3>
            <p>Giao thông thuận tiện – khai thác tốt.</p>
        </div>
    </div>
</section>

<section class="contact" id="contact">
    <h2>Liên hệ DWELL</h2>
    <form>
        <input type="text" placeholder="Họ và tên" required>
        <input type="tel" placeholder="Số điện thoại" required>
        <textarea rows="4" placeholder="Nhu cầu của bạn"></textarea>
        <button class="btn" type="submit">Gửi thông tin</button>
    </form>
</section>

<footer>
    <p>© 2026 DWELL – Bất động sản Nhà phố Sài Gòn</p>
</footer>

</body>
</html>
