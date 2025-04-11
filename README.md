# Kombuchlanh
<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kombuch Lành</title>
  <style>
   
    body {
      background: url('IMG_5136.jpeg') no-repeat center center fixed;
      background-size: cover;
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
      color: #333;
    }
   
    .overlay {
      background: rgba(255, 255, 255, 0.9);
      padding: 20px;
      min-height: 100vh;
    }
   
    header {
      background: rgba(255, 255, 255, 0.95);
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      position: sticky;
      top: 0;
      z-index: 1000;
      padding: 10px 20px;
      transition: background-color 0.3s;
    }
    header h1 {
      margin: 0;
      color: #2e7d32;
      text-align: center;
    }
    nav {
      margin-top: 10px;
      text-align: center;
    }
    nav ul {
      list-style: none;
      padding: 0;
      margin: 0;
      display: inline-flex;
      flex-wrap: wrap;
      gap: 15px;
    }
    nav ul li a {
      text-decoration: none;
      color: #2e7d32;
      font-weight: bold;
      padding: 8px 12px;
      transition: background-color 0.3s, color 0.3s;
    }
    nav ul li a:hover {
      background-color: #c8e6c9;
      border-radius: 4px;
    }
   
    .content {
      max-width: 1200px;
      margin: 30px auto;
      background: rgba(255, 255, 255, 0.95);
      padding: 30px;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.15);
    }
    section {
      margin-bottom: 40px;
    }
    section h2 {
      color: #2e7d32;
      border-bottom: 2px solid #2e7d32;
      padding-bottom: 5px;
      margin-bottom: 20px;
    }
   
    #gioithieu p {
      line-height: 1.6;
      text-align: justify;
    }
   
    #loiich ul {
      list-style: disc inside;
      line-height: 1.6;
    }
    #loiich ul li {
      margin-bottom: 10px;
    }
   
    #sanpham ul {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      list-style: none;
      padding: 0;
    }
    #sanpham ul li {
      background: #e8f5e9;
      border: 1px solid #c8e6c9;
      padding: 15px;
      border-radius: 8px;
      text-align: left;
      transition: transform 0.3s;
    }
    #sanpham ul li:hover {
      transform: translateY(-5px);
    }
   
    .product-details {
      margin-top: 10px;
      font-size: 14px;
      line-height: 1.5;
    }
    .product-details ul {
      margin: 5px 0 0 15px;
      list-style: circle;
    }
   
    #baotri {
      margin-top: 40px;
    }
    #baotri ul {
      list-style: disc inside;
      line-height: 1.6;
    }
    #baotri ul li {
      margin-bottom: 10px;
    }
   
    .accordion {
      width: 100%;
    }
    .accordion-item {
      border-bottom: 1px solid #ccc;
    }
    .accordion-header {
      padding: 15px;
      cursor: pointer;
      background: #f1f8e9;
      color: #2e7d32;
      font-weight: bold;
      transition: background 0.3s;
    }
    .accordion-header:hover {
      background: #dcedc8;
    }
    .accordion-content {
      padding: 15px;
      display: none;
      background: #fafafa;
    }
   
    #lienhe form {
      display: flex;
      flex-direction: column;
      gap: 15px;
      max-width: 600px;
      margin: auto;
    }
    #lienhe input, #lienhe textarea {
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 4px;
      font-size: 16px;
    }
    #lienhe button {
      background: #2e7d32;
      color: #fff;
      border: none;
      padding: 12px;
      border-radius: 4px;
      cursor: pointer;
      transition: background 0.3s;
      font-size: 16px;
    }
    #lienhe button:hover {
      background: #1b5e20;
    }
   
    .address {
      margin-top: 15px;
      font-style: italic;
      color: #555;
      text-align: center;
    }
   
    footer {
      text-align: center;
      padding: 15px;
      background: rgba(255, 255, 255, 0.95);
      box-shadow: 0 -2px 4px rgba(0,0,0,0.1);
    }
   
    @media (max-width: 768px) {
      nav ul {
        flex-direction: column;
      }
    }
  </style>
</head>
<body>
  <div class="overlay">
    <!-- Header & Navigation -->
    <header>
      <h1>Kombuch Lành</h1>
      <nav>
        <ul>
          <li><a href="#trangchu">Trang chủ</a></li>
          <li><a href="#gioithieu">Giới thiệu</a></li>
          <li><a href="#loiich">Lợi ích</a></li>
          <li><a href="#sanpham">Sản phẩm</a></li>
          <li><a href="#baotri">Cách bảo quản</a></li>
          <li><a href="#faq">FAQ</a></li>
          <li><a href="#lienhe">Liên hệ</a></li>
        </ul>
      </nav>
    </header>

   
    <div class="content">
     
      <section id="trangchu">
        <h2>Trang chủ</h2>
        <p>Chào mừng bạn đến với Kombuch Lành – nơi sự kết hợp giữa truyền thống và hiện đại mang lại những trải nghiệm trà kombucha độc đáo. Hãy cùng khám phá hành trình hướng tới một cuộc sống lành mạnh và tràn đầy năng lượng thông qua những ly trà tuyệt vời của chúng tôi.</p>
      </section>
      
     
      <section id="gioithieu">
        <h2>Giới thiệu</h2>
        <p>Kombuch Lành được thành lập từ niềm đam mê với những giá trị tự nhiên và mong muốn mang lại lợi ích sức khỏe cho cộng đồng. Chúng tôi tự hào là thương hiệu chuyên sản xuất trà kombucha chất lượng cao, được làm từ các nguyên liệu tự nhiên, không hóa chất và được lên men theo quy trình nghiêm ngặt.</p>
        <p>Với kinh nghiệm nhiều năm trong lĩnh vực thực phẩm chức năng, chúng tôi luôn chú trọng đến việc nghiên cứu và cải tiến công nghệ sản xuất nhằm tạo ra sản phẩm an toàn, giàu dinh dưỡng và hương vị thơm ngon. Sứ mệnh của Kombuch Lành là truyền tải thông điệp sống xanh, sống khỏe và lan tỏa niềm tin vào những giá trị tốt đẹp của thiên nhiên.</p>
        <p>Thông qua trang web này, chúng tôi mong muốn mang đến cho khách hàng cái nhìn tổng quan về quy trình sản xuất cũng như các thành phần tự nhiên được sử dụng trong sản phẩm.</p>
      </section>
      
     
      <section id="loiich">
        <h2>Lợi ích</h2>
        <ul>
          <li><strong>Cải thiện hệ tiêu hóa:</strong> Trà kombucha giúp cân bằng hệ vi sinh vật trong đường ruột, hỗ trợ tiêu hóa và giảm các triệu chứng khó chịu sau bữa ăn.</li>
          <li><strong>Tăng cường hệ miễn dịch:</strong> Probiotic và dưỡng chất tự nhiên kích thích hệ miễn dịch, giúp cơ thể đề kháng lại các tác nhân gây bệnh.</li>
          <li><strong>Giàu chất chống oxy hóa:</strong> Các thành phần như polyphenol, vitamin và enzyme giúp trung hòa gốc tự do, làm chậm quá trình lão hóa và bảo vệ tế bào.</li>
          <li><strong>Hỗ trợ giảm cân & detox:</strong> Sản phẩm giúp loại bỏ độc tố, tăng cường trao đổi chất và hỗ trợ quá trình giảm cân khi kết hợp chế độ ăn uống lành mạnh.</li>
          <li><strong>Cải thiện sức khỏe tim mạch:</strong> Dưỡng chất tự nhiên giúp điều hòa huyết áp, giảm cholesterol và cải thiện tuần hoàn máu.</li>
          <li><strong>Cân bằng đường huyết:</strong> Uống trà kombucha đều đặn có thể hỗ trợ duy trì mức đường huyết ổn định.</li>
          <li><strong>Tăng cường sức khỏe não bộ:</strong> Các vitamin nhóm B và chất chống oxy hóa góp phần cải thiện trí nhớ và giảm stress.</li>
          <li><strong>Cải thiện tâm trạng:</strong> Hương vị tự nhiên và các dưỡng chất có trong kombucha giúp giảm căng thẳng, mang lại cảm giác thư giãn và sảng khoái.</li>
        </ul>
      </section>
      
     
      <section id="sanpham">
        <h2>Sản phẩm</h2>
        <p>Chúng tôi tự hào giới thiệu các loại trà kombucha độc đáo, được chế biến từ những thành phần tự nhiên và theo quy trình lên men truyền thống kết hợp công nghệ hiện đại:</p>
        <ul>
          <li>
            <strong>Trà kombucha truyền thống:</strong>
            <div class="product-details">
              <p>Hương vị cân bằng giữa chua nhẹ và vị đắng tự nhiên của trà lên men.</p>
              <p><em>Thành phần:</em></p>
              <ul>
                <li>Trà đen hoặc trà xanh</li>
                <li>Đường tự nhiên</li>
                <li>SCOBY (vi khuẩn và nấm men)</li>
                <li>Probiotic tự nhiên</li>
              </ul>
            </div>
          </li>
          <li>
            <strong>Trà kombucha dứa:</strong>
            <div class="product-details">
              <p>Sự kết hợp hài hòa giữa hương vị dứa tươi mát và vị đặc trưng của kombucha.</p>
              <p><em>Thành phần:</em></p>
              <ul>
                <li>Trà đen hoặc trà xanh</li>
                <li>Đường tự nhiên</li>
                <li>Nước ép dứa tươi</li>
                <li>SCOBY và probiotic</li>
              </ul>
            </div>
          </li>
          <li>
            <strong>Trà kombucha ổi:</strong>
            <div class="product-details">
              <p>Một sự kết hợp độc đáo của vị ngọt dịu của ổi và hương vị chua nhẹ của kombucha.</p>
              <p><em>Thành phần:</em></p>
              <ul>
                <li>Trà đen hoặc trà xanh</li>
                <li>Đường tự nhiên</li>
                <li>Nước ép ổi</li>
                <li>SCOBY và probiotic</li>
              </ul>
            </div>
          </li>
          <li>
            <strong>Trà kombucha dâu tằm:</strong>
            <div class="product-details">
              <p>Hương thơm của dâu tằm hòa quyện cùng vị trà truyền thống, mang đến cảm giác mới lạ.</p>
              <p><em>Thành phần:</em></p>
              <ul>
                <li>Trà đen hoặc trà xanh</li>
                <li>Đường tự nhiên</li>
                <li>Nước ép dâu tằm</li>
                <li>SCOBY và probiotic</li>
              </ul>
            </div>
          </li>
          <li>
            <strong>Trà kombucha táo:</strong>
            <div class="product-details">
              <p>Vị ngọt thanh của táo kết hợp với vị chua nhẹ của kombucha, tạo nên thức uống bổ dưỡng.</p>
              <p><em>Thành phần:</em></p>
              <ul>
                <li>Trà đen hoặc trà xanh</li>
                <li>Đường tự nhiên</li>
                <li>Nước ép táo tươi</li>
                <li>SCOBY và probiotic</li>
              </ul>
            </div>
          </li>
        </ul>
      </section>
      
     
      <section id="baotri">
        <h2>Cách bảo quản</h2>
        <p>Để giữ cho trà kombucha luôn tươi ngon và đảm bảo các dưỡng chất tự nhiên, vui lòng lưu ý các hướng dẫn bảo quản sau:</p>
        <ul>
          <li>Bảo quản sản phẩm ở nơi khô ráo, thoáng mát và tránh ánh sáng trực tiếp.</li>
          <li>Sau khi mở nắp, nên để trà kombucha trong tủ lạnh ở nhiệt độ từ 2-8°C và sử dụng trong vòng 7-10 ngày.</li>
          <li>Đảm bảo chai, lọ được đậy kín để tránh nhiễm khuẩn từ môi trường.</li>
          <li>Nên sử dụng sản phẩm trong thời gian ngắn sau khi mua để đảm bảo chất lượng và hương vị tốt nhất.</li>
          <li>Không nên để sản phẩm ở nơi nhiệt độ cao hoặc ẩm ướt, vì có thể làm thay đổi quá trình lên men tự nhiên.</li>
        </ul>
      </section>
      
     
      <section id="faq">
        <h2>FAQ - Câu hỏi thường gặp</h2>
        <div class="accordion">
          <div class="accordion-item">
            <div class="accordion-header">Trà kombucha là gì?</div>
            <div class="accordion-content">
              <p>Trà kombucha là thức uống lên men được tạo ra từ trà đen hoặc trà xanh, kết hợp với đường và một hỗn hợp vi khuẩn có lợi, giúp tạo ra enzyme, axit hữu cơ và probiotic tốt cho sức khỏe.</p>
            </div>
          </div>
          <div class="accordion-item">
            <div class="accordion-header">Làm thế nào để sử dụng sản phẩm?</div>
            <div class="accordion-content">
              <p>Bạn có thể thưởng thức trà kombucha trực tiếp sau khi làm lạnh, pha trộn với nước ép hoặc soda, hoặc dùng làm nguyên liệu cho các thức uống sáng tạo. Hãy thử nhiều cách để khám phá hương vị phù hợp với mình.</p>
            </div>
          </div>
          <div class="accordion-item">
            <div class="accordion-header">Sản phẩm có phù hợp với mọi đối tượng không?</div>
            <div class="accordion-content">
              <p>Chúng tôi sản xuất sản phẩm theo tiêu chuẩn an toàn và chất lượng cao. Tuy nhiên, trẻ nhỏ, phụ nữ mang thai và người có vấn đề sức khỏe nên tham khảo ý kiến bác sĩ trước khi sử dụng.</p>
            </div>
          </div>
        </div>
      </section>
      
     
      <section id="lienhe">
        <h2>Liên hệ</h2>
        <p>Nếu bạn có bất kỳ thắc mắc hoặc góp ý nào, vui lòng liên hệ với chúng tôi qua form bên dưới hoặc qua các thông tin liên lạc được liệt kê.</p>
        <form action="#" method="post">
          <input type="text" name="hoten" placeholder="Họ và tên" required>
          <input type="email" name="email" placeholder="Email" required>
          <textarea name="noidung" rows="5" placeholder="Nội dung" required></textarea>
          <button type="submit">Gửi</button>
        </form>
        <p>Email: <a href="mailto:trakombuchlanh@gmail.com">trakombuchlanh@gmail.com</a> | SĐT: 098 403 8063</p>
        <div class="address">
          <p><strong>Địa chỉ:</strong> Phường Quỳnh Dị, Thị xã Hoàng Mai, Nghệ An</p>
        </div>
      </section>
    </div>

   
    <footer>
      <p>&copy; 2025 Kombuch Lành. All rights reserved.</p>
    </footer>
  </div>

 
  <script>
    const headers = document.querySelectorAll('.accordion-header');
    headers.forEach(header => {
      header.addEventListener('click', () => {
        const content = header.nextElementSibling;
        const isVisible = content.style.display === 'block';
        document.querySelectorAll('.accordion-content').forEach(item => item.style.display = 'none');
        if (!isVisible) {
          content.style.display = 'block';
        }
      });
    });
  </script>
</body>
</html>
