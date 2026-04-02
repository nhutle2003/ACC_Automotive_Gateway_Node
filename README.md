# MÔ HÌNH ĐIỀU KHIỂN BƯỚM GA ĐIỆN TỬ TÍCH HỢP ACC VÀ CAN BUS

## 📌 Giới thiệu

Đề tài tập trung thiết kế và xây dựng mô hình điều khiển bướm ga điện tử (Electronic Throttle Control - ETC) phục vụ giảng dạy, tích hợp mô phỏng hệ thống kiểm soát hành trình thích ứng (Adaptive Cruise Control - ACC) sử dụng Simulink và giao tiếp CAN Bus.

Mục tiêu của đề tài là xây dựng một hệ thống hoàn chỉnh kết hợp giữa mô phỏng phần mềm và phần cứng thực tế, giúp sinh viên tiếp cận hệ thống điều khiển điện tử trong ô tô hiện đại.

---

## 🛠 Công nghệ và nền tảng sử dụng

- Vi điều khiển STM32
- Giao tiếp CAN Bus (mô hình 3 node)
- Matlab/Simulink
- Matlab App Designer (giao diện điều khiển)
- PWM điều khiển động cơ DC
- Cảm biến vị trí bướm ga (TPS)
- Driver H-Bridge

---

## ⚙ Kiến trúc hệ thống

Hệ thống bao gồm:

- Node điều khiển trung tâm (MCU STM32)
- Node giao tiếp CAN
- Node mô phỏng ACC trên Simulink
- Cơ cấu bướm ga điện tử
- Giao diện điều khiển và giám sát trên Matlab App

Dữ liệu tốc độ và góc mở bướm ga được truyền qua CAN và hiển thị trực quan trên giao diện máy tính.

---

## 🔎 Nội dung thực hiện

- Thiết kế thuật toán điều khiển bướm ga
- Xử lý tín hiệu cảm biến TPS
- Điều khiển động cơ bằng PWM
- Thiết lập và cấu hình giao tiếp CAN giữa các node
- Xây dựng mô hình ACC trên Simulink
- Thiết kế giao diện giám sát và điều khiển
- Kiểm thử và hiệu chỉnh hệ thống thực tế

---

## 👨‍💻 Vai trò thực hiện

Trong đề tài, tôi phụ trách phát triển phần mềm nhúng trên vi điều khiển STM32, bao gồm:

- Thiết kế và lập trình thuật toán điều khiển bướm ga điện tử
- Đọc và xử lý tín hiệu cảm biến vị trí bướm ga (TPS)
- Điều khiển động cơ DC bằng PWM thông qua H-Bridge
- Xây dựng và cấu hình giao tiếp CAN giữa các node
- Xử lý truyền nhận dữ liệu và đảm bảo hệ thống hoạt động ổn định

Phần mô phỏng ACC và giao diện Matlab được thực hiện bởi các thành viên khác trong nhóm.

---

## 📊 Kết quả đạt được

- Mô hình hoạt động ổn định, sai số nhỏ
- Góc mở bướm ga bám theo giá trị đặt
- Truyền nhận dữ liệu CAN chính xác
- Giao diện giám sát hiển thị dữ liệu thời gian thực
- Phù hợp phục vụ giảng dạy và thực hành hệ thống điều khiển ô tô

---

## 🎥 Video Demo
[Watch the demo video](https://drive.google.com/file/d/19ns-zEEYxKTt7lhtvhN1aRVujSTEGcxB/view?usp=drive_link)

