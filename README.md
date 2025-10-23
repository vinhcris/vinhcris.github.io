<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Giới thiệu về Nguyễn Tiến Vinh - Vinh Cris, cầu thủ bóng đá với đam mê cháy bỏng và ý chí kiên cường.">
    <meta name="keywords" content="Vinh Cris, Nguyễn Tiến Vinh, cầu thủ bóng đá, Schalke 04, Becamex Bình Dương">
    <title>Giới thiệu Vinh Cris - Nguyễn Tiến Vinh</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        body {
            font-family: 'Roboto', Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: #333;
            min-height: 100vh;
            line-height: 1.6;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        header {
            background: linear-gradient(135deg, #007bff 0%, #0056b3 100%);
            color: white;
            text-align: center;
            padding: 80px 20px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
            position: relative;
            overflow: hidden;
        }
        header::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('https://via.placeholder.com/1200x400?text=Soccer+Field') no-repeat center center;
            background-size: cover;
            opacity: 0.1;
            z-index: 1;
        }
        header .container {
            position: relative;
            z-index: 2;
        }
        header h1 {
            margin: 0;
            font-size: 3.5em;
            font-weight: 700;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }
        header p {
            font-size: 1.4em;
            margin: 15px 0;
            font-weight: 300;
        }
        header img {
            width: 200px;
            height: 112px; /* Tỷ lệ 16:9 cho width 200px */
            object-fit: cover;
            border-radius: 10px; /* Bỏ tròn, làm góc bo nhẹ */
            border: 3px solid white;
            box-shadow: 0 4px 12px rgba(0,0,0,0.3);
            margin-top: 20px;
            transition: transform 0.3s ease;
        }
        header img:hover {
            transform: scale(1.05);
        }
        nav {
            text-align: center;
            background-color: rgba(255, 255, 255, 0.95);
            padding: 20px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            backdrop-filter: blur(10px);
        }
        nav button {
            background: linear-gradient(135deg, #007bff 0%, #0056b3 100%);
            color: white;
            border: none;
            padding: 15px 30px;
            margin: 0 10px;
            cursor: pointer;
            font-size: 1.1em;
            font-weight: 500;
            border-radius: 30px;
            transition: all 0.3s ease;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
            display: inline-flex;
            align-items: center;
        }
        nav button i {
            margin-right: 8px;
        }
        nav button:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 12px rgba(0,0,0,0.3);
        }
        nav button.active {
            background: linear-gradient(135deg, #0056b3 0%, #003d82 100%);
            transform: translateY(-2px);
        }
        section {
            max-width: 900px;
            margin: 40px auto;
            padding: 40px;
            background-color: white;
            border-radius: 20px;
            box-shadow: 0 8px 16px rgba(0,0,0,0.1);
            display: none;
            opacity: 0;
            transform: translateY(20px);
            transition: all 0.5s ease;
        }
        section.active {
            display: block;
            opacity: 1;
            transform: translateY(0);
        }
        section h2 {
            color: #007bff;
            border-bottom: 3px solid #007bff;
            padding-bottom: 15px;
            font-size: 2.2em;
            font-weight: 700;
            margin-bottom: 20px;
        }
        section p {
            font-size: 1.1em;
            margin-bottom: 15px;
        }
        #lien-he form {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }
        #lien-he input, #lien-he textarea {
            padding: 12px;
            border: 1px solid #ddd;
            border-radius: 8px;
            font-size: 1em;
        }
        #lien-he button {
            background: linear-gradient(135deg, #007bff 0%, #0056b3 100%);
            color: white;
            border: none;
            padding: 12px;
            border-radius: 8px;
            cursor: pointer;
            font-size: 1.1em;
            transition: background 0.3s ease;
        }
        #lien-he button:hover {
            background: linear-gradient(135deg, #0056b3 0%, #003d82 100%);
        }
        footer {
            text-align: center;
            padding: 30px;
            background: linear-gradient(135deg, #007bff 0%, #0056b3 100%);
            color: white;
            font-weight: 300;
        }
        footer a {
            color: white;
            text-decoration: none;
            margin: 0 10px;
        }
        footer a:hover {
            text-decoration: underline;
        }
        @media (max-width: 768px) {
            header h1 {
                font-size: 2.5em;
            }
            nav button {
                display: block;
                margin: 10px auto;
                width: 80%;
            }
            section {
                padding: 20px;
            }
        }
    </style>
</head>
<body>

    <header>
        <div class="container">
            <h1>Nguyễn Tiến Vinh - Vinh Cris</h1>
            <p>Cầu thủ bóng đá với đam mê cháy bỏng và ý chí kiên cường</p>
            <img src="https://i.pinimg.com/736x/dc/9f/0e/dc9f0ea1a49e80ab8f50391df42fafac.jpg" alt="Ảnh Vinh Cris">
        </div>
    </header>

    <nav>
        <button id="btn-gioi-thieu" onclick="showSection('gioi-thieu')"><i class="fas fa-user"></i> Giới thiệu</button>
        <button id="btn-hanh-trinh" onclick="showSection('hanh-trinh')"><i class="fas fa-route"></i> Hành trình</button>
        <button id="btn-thanh-tu" onclick="showSection('thanh-tu')"><i class="fas fa-trophy"></i> Thành tựu</button>
        <button id="btn-hien-tai" onclick="showSection('hien-tai')"><i class="fas fa-clock"></i> Hiện tại</button>
        <button id="btn-lien-he" onclick="showSection('lien-he')"><i class="fas fa-envelope"></i> Liên hệ</button>
    </nav>

    <section id="gioi-thieu" class="active">
        <h2>Giới thiệu</h2>
        <p>Nguyễn Tiến Vinh, hay còn được gọi với cái tên thân mật Vinh Cris, chào đời vào ngày 04 tháng 01 năm 2007, trong một con hẻm nhỏ tĩnh lặng tọa lạc tại Gò Vấp, Sài Gòn. Ngay từ thuở bé, cậu đã sớm bộc lộ một tình yêu mãnh liệt và không thể tách rời với trái bóng tròn. Niềm đam mê ấy nảy mầm thành ước mơ cháy bỏng: trở thành một cầu thủ bóng đá chuyên nghiệp.</p>
        <p>Tuổi thơ của Vinh gắn liền với những buổi chiều khuấy động con hẻm, nơi cậu bé nhỏ tuổi ấy đã "bón hành" cho không biết bao nhiêu anh lớn, bạn bè trong xóm. Với đôi chân thoăn thoắt, những kỹ năng (skill) cậu trình diễn trên sân gạch, sân đất sét nhỏ bé ấy có lẽ là điều hiếm thấy ở những đứa trẻ cùng trang lứa.</p>
    </section>

    <section id="hanh-trinh">
        <h2>Hành trình bóng đá</h2>
        <p>Cơ duyên mỉm cười với Vinh vào năm cậu lên 7. Khi tham gia một tiết học thể dục dạy môn bóng đá tại trường tiểu học, màn trình diễn đầy ấn tượng của cậu đã lọt vào mắt xanh của thầy giáo thể dục. Tình cờ, thầy còn là một người thầy đang giảng dạy tại lò đào tạo bóng đá danh tiếng Becamex Bình Dương. Tài năng thiên bẩm của Vinh đã khiến cậu được thử chân và tuyển thẳng vào lò. Tưởng chừng cánh cửa ước mơ đã mở rộng, nhưng niềm vui ngắn chẳng tày gang. Chỉ sau chưa đầy một năm, gia đình đã cấm cản cậu theo đuổi con đường này. Những nỗi lo sợ quen thuộc như chấn thương, và mong muốn con trai phải tập trung vào việc học tập đã buộc Vinh phải gác lại tài năng bẩm sinh ấy, tạm biệt màu áo và những buổi tập luyện chuyên nghiệp.</p>
        <p>Sự thiếu vắng "món ăn tinh thần" là bóng đá khiến con đường học tập và cuộc sống của Vinh trở nên khó khăn và thiếu sức sống. Cuộc đời cậu có một bước ngoặt lớn vào năm lớp 5, khi cậu chuyển ra Hà Nội sinh sống và học tập. Tại mảnh đất mới, Vinh làm quen được nhiều bạn bè mới, và may mắn thay, họ đều chung một niềm đam mê cháy bỏng: bóng đá. Lên cấp 2, niềm vui của cậu nhân đôi khi ngôi trường mới cậu theo học có một sân bóng. Từ đó, ngọn lửa đam mê tưởng chừng đã tắt lại bùng cháy dữ dội. Vinh bắt đầu lao vào tập luyện điên cuồng, cố gắng lấy lại những gì mình đã từng có. Thời gian đầu đầy gian khổ, cậu cảm thấy mình rất yếu và kém cỏi sau một thời gian dài không chạm vào bóng.</p>
        <p>Với tinh thần khổ luyện bền bỉ và sự chăm chỉ không ngừng nghỉ qua nhiều năm, Vinh không chỉ lấy lại được phong độ mà còn kết bạn được với rất nhiều người, làm quen được với những anh, những thầy, những chú nổi tiếng trong giới bóng đá Hà thành. Cậu tham gia tranh tài ở vô số trận đấu trên khắp thủ đô, từ sân 7, sân 9 cho đến sân 11. Vinh trở thành linh hồn không thể thiếu của đội bóng, là đội trưởng dẫn dắt ba đội bóng khác nhau, và hơn hết, cậu là người đặt nền móng, là nguồn cảm hứng cho những thế hệ trẻ, cho những người bạn không có cơ hội phát triển bản thân. Vinh vừa là một cầu thủ tài năng trên sân cỏ, vừa là huấn luyện viên truyền đạt kỹ năng, và là người động viên tinh thần cho đồng đội. Sự kết hợp giữa tài năng và đạo đức khiến cậu trở thành một nhân vật được nể trọng.</p>
        <p>Đỉnh cao của hành trình này đến vào năm lớp 12, năm cuối cấp. Khi tham gia một giải bóng đá sân 11 cùng các bạn ngoại quốc và các anh lớn, tài năng nổi bật của Vinh đã được chú ý. Cậu được chọn để tham gia kỳ thi try-out của câu lạc bộ danh tiếng Schalke 04, một sự kiện có quy mô rất lớn, mở ra cơ hội vàng để sang Đức thực tập và thi đấu chuyên nghiệp.</p>
        <p>Tuy nhiên, số phận lại thử thách Vinh một lần nữa. Vào khoảng tháng 3 năm 2025, cậu đã gặp phải một chấn thương dây chằng rất nặng, nghiêm trọng nhất từ trước đến giờ. Chấn thương này buộc cậu phải nghỉ thi đấu trong một thời gian dài, bỏ lỡ biết bao trận bóng quan trọng, và tiếc nuối nhất là không thể giúp đội bóng lớp của cậu lên ngôi vô địch. Chấn thương nghiệt ngã ấy cũng ảnh hưởng nặng nề đến kỳ thi try-out. Dù vậy, với ý chí kiên cường, Vinh vẫn cố gắng tham gia và đạt được điểm số nằm trong Top 47 trên tổng số 1000 thí sinh. Tiếc thay, buổi try-out vô cùng khắt khe và chỉ chọn ra Top 20. Sự tiếc nuối và buồn bã bao trùm lấy cậu, một cảm giác day dứt rằng: "Giá như mình không mắc chấn thương ấy, thì có lẽ bây giờ ước mơ làm cầu thủ chuyên nghiệp đã rất gần rồi."</p>
    </section>

    <section id="thanh-tu">
        <h2>Thành tựu và Tầm ảnh hưởng</h2>
        <p>Vinh là linh hồn không thể thiếu của đội bóng, là đội trưởng dẫn dắt ba đội bóng khác nhau, và hơn hết, cậu là người đặt nền móng, là nguồn cảm hứng cho những thế hệ trẻ, cho những người bạn không có cơ hội phát triển bản thân. Vinh vừa là một cầu thủ tài năng trên sân cỏ, vừa là huấn luyện viên truyền đạt kỹ năng, và là người động viên tinh thần cho đồng đội. Sự kết hợp giữa tài năng và đạo đức khiến cậu trở thành một nhân vật được nể trọng.</p>
        <p>Trong các trận đấu trên khắp thủ đô, Vinh đã chứng minh kỹ năng vượt trội, từ sân 7 đến sân 11. Cậu không chỉ thi đấu mà còn truyền cảm hứng, giúp đỡ bạn bè và thế hệ trẻ phát triển đam mê bóng đá.</p>
    </section>

    <section id="hien-tai">
        <h2>Hiện tại và Lời hứa</h2>
        <p>Tính đến thời điểm hiện tại, cậu bé 18 tuổi ấy vẫn giữ trong mình niềm đam mê rực lửa ấy. Vinh Cris vẫn đang cố gắng cân bằng giữa công việc học tập và bóng đá, luôn mang trong mình tham vọng chinh phục giới hạn của bản thân với bộ môn đã gắn bó với cuộc đời cậu.</p>
        <p>Và một lời hứa được thắp lên: Năm 2026, Nguyễn Tiến Vinh sẽ quay trở lại!</p>
    </section>

    <section id="lien-he">
        <h2>Liên hệ</h2>
        <form action="#" method="post">
            <input type="text" name="name" placeholder="Tên của bạn" required>
            <input type="email" name="email" placeholder="Email của bạn" required>
            <textarea name="message" rows="5" placeholder="Tin nhắn của bạn" required></textarea>
            <button type="submit">Gửi tin nhắn</button>
        </form>
    </section>

    <footer>
        <a href="https://www.facebook.com/cristiano.vinhh"><i class="fab fa-facebook"></i></a>
        <a href="https://www.instagram.com/vinh.ngtiene/"><i class="fab fa-instagram"></i></a>
        <a href="https://www.youtube.com/results?search_query=G_Matrix+gaming"><i class="fab fa-youtube"></i></a>
    </footer>

    <script>
        function showSection(sectionId) {
            // Ẩn tất cả sectionss
            const sections = document.querySelectorAll('section');
            sections.forEach(section => section.classList.remove('active'));
            
            // Xóa active class từ buttons
            const buttons = document.querySelectorAll('nav button');
            buttons.forEach(button => button.classList.remove('active'));
            
            // Hiển thị section được chọn
            const activeSection = document.getElementById(sectionId);
            activeSection.classList.add('active');
            
            // Thêm active class cho button tương ứng
            const activeButton = document.getElementById('btn-' + sectionId);
            activeButton.classList.add('active');
        }
        
        // Mặc định hiển thị Giới thiệu
        showSection('gioi-thieu');
    </script>

</body>
</html>
