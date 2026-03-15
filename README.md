<h1>Lab Vi điều khiển - LED & 7 Segment</h1>

<h2> Mục tiêu</h2>
<ul>
  <li>Làm quen với <strong>STM32CubeIDE</strong> và cách sinh mã nguồn cơ bản.</li>
  <li>Thực hành điều khiển LED đơn, LED 7 đoạn (common anode) và kỹ thuật multiplexing.</li>
  <li>Sử dụng <strong>Timer Interrupt</strong> để quét LED và tạo hiệu ứng nhấp nháy.</li>
  <li>Mô phỏng chương trình trên <strong>Proteus</strong> bằng file HEX sinh từ CubeIDE.</li>
</ul>

<h2> Công cụ sử dụng</h2>
<ul>
  <li><strong>IDE:</strong> STM32CubeIDE (cấu hình chân, build HEX).</li>
  <li><strong>Phần mềm mô phỏng:</strong> Proteus.</li>
  <li><strong>Vi điều khiển:</strong> STM32F103C6.</li>
</ul>

<h2> Nội dung từng bài</h2>

<h3>Bài 1: Chuyển đổi trạng thái LED</h3>
<ul>
  <li>Điều khiển 2 đèn LED thay phiên nhau sáng/tắt sau mỗi <strong>2 giây</strong>.</li>
  <li>Làm quen với cấu hình GPIO Output và sử dụng <code>HAL_Delay()</code>.</li>
</ul>

<h3>Bài 2: Mô phỏng đèn giao thông cơ bản</h3>
<ul>
  <li>Thêm 1 LED để mô phỏng hành vi của <strong>đèn giao thông</strong>.</li>
  <li>Thời gian hoạt động:
    <ul>
      <li>Xanh: <strong>3 giây</strong></li>
      <li>Vàng: <strong>2 giây</strong></li>
      <li>Đỏ: <strong>5 giây</strong></li>
    </ul>
  </li>
</ul>

<h3>Bài 3: Mô phỏng đèn giao thông 4 chiều</h3>
<ul>
  <li>Sử dụng <strong>12 LED đơn</strong> bố trí dạng ngã tư.</li>
  <li>Mô phỏng chu kỳ hoạt động của <strong>đèn giao thông 4 hướng</strong>.</li>
</ul>

<h3>Bài 4: Hiển thị số trên LED 7 đoạn</h3>
<ul>
  <li>Hiện thực hàm <code>display7SEG(int num)</code> để hiển thị chữ số trên LED 7 đoạn.</li>
  <li>Thực hành ánh xạ số sang các chân của LED 7 đoạn (common anode).</li>
</ul>

<h3>Bài 5: Đèn giao thông + LED 7 đoạn đếm ngược</h3>
<ul>
  <li>Tích hợp LED 7 đoạn để hiển thị <strong>thời gian đếm ngược</strong> của đèn giao thông.</li>
  <li>Kết hợp logic của <strong>Bài 3</strong> và <strong>Bài 4</strong>.</li>
  <li>Code của Bài 3 và Bài 5 được hiện thực chung trong thư mục <code>EX_3</code>.</li>
</ul>

<h3>Bài 6 – 10: Mô phỏng đồng hồ bằng LED đơn</h3>
<ul>
  <li>Sử dụng <strong>12 LED đơn</strong> để mô phỏng kim đồng hồ.</li>
  <li>Các hàm và sơ đồ Proteus được hiện thực chung trong thư mục <code>EX_10</code>.</li>
</ul>

<h2> Kết quả mong đợi</h2>
<ul>
  <li>Sử dụng thành thạo <strong>STM32CubeIDE</strong> để viết các chương trình cơ bản.</li>
  <li>LED đơn và LED 7 đoạn hiển thị chính xác.</li>
  <li>Mô phỏng thành công các ứng dụng:
    <ul>
      <li>Đèn giao thông (cơ bản & 4 chiều).</li>
      <li>Đồng hồ với LED đơn.</li>
    </ul>
  </li>
  <li>Có thể mở rộng sang các bài toán nhúng khác.</li>
</ul>
