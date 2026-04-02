# Electronic Throttle Control Model with ACC and CAN Bus

## Giới thiệu

Đề tài xây dựng mô hình điều khiển bướm ga điện tử (Electronic Throttle Control - ETC) tích hợp mô phỏng Adaptive Cruise Control (ACC) và giao tiếp CAN Bus.

Hệ thống kết hợp phần mềm nhúng trên STM32 với phần mô phỏng trên máy tính nhằm minh họa cách các hệ thống điều khiển điện tử trong ô tô hiện đại trao đổi dữ liệu giữa các node ECU và công cụ giám sát bên ngoài. Đề tài được thực hiện với mục tiêu học tập, mô phỏng thực tế và hỗ trợ giảng dạy.

---

## Công nghệ và nền tảng sử dụng

- Vi điều khiển STM32
- Giao tiếp CAN Bus (mô hình 3 node)
- MATLAB / Simulink
- MATLAB App Designer
- PWM điều khiển động cơ DC
- Cảm biến vị trí bướm ga (TPS)
- Driver H-Bridge

---

## Kiến trúc hệ thống

Hệ thống tổng thể bao gồm:

- Node điều khiển trung tâm sử dụng STM32
- Node giao tiếp CAN
- Node mô phỏng ACC xây dựng trên Simulink
- Cơ cấu bướm ga điện tử
- Giao diện giám sát và điều khiển trên MATLAB

Dữ liệu tốc độ xe và góc mở bướm ga được truyền qua CAN Bus và hiển thị trên giao diện máy tính theo thời gian thực.

---

## Phạm vi đề tài

Phạm vi toàn bộ đề tài bao gồm:

- Thuật toán điều khiển bướm ga điện tử
- Đọc và xử lý tín hiệu cảm biến TPS
- Điều khiển động cơ bằng PWM
- Giao tiếp CAN giữa nhiều node
- Mô phỏng ACC trên Simulink
- Giao diện giám sát và điều khiển trên máy tính
- Kiểm thử và hiệu chỉnh hệ thống

---

## Vai trò thực hiện

Tôi phụ trách phát triển phần mềm nhúng trên STM32, bao gồm:

- Xây dựng firmware điều khiển cho mô hình bướm ga điện tử
- Đọc và xử lý tín hiệu từ cảm biến vị trí bướm ga (TPS)
- Điều khiển động cơ DC bằng PWM thông qua H-Bridge
- Cấu hình và xử lý giao tiếp CAN giữa các node
- Xử lý dữ liệu truyền nhận để hệ thống hoạt động ổn định

Phần mô phỏng ACC và giao diện MATLAB được thực hiện bởi các thành viên khác trong nhóm.

---

## Kết quả đạt được

- Mô hình ETC hoạt động ổn định với sai số nhỏ
- Góc mở bướm ga bám theo giá trị đặt tương đối tốt
- Dữ liệu CAN được truyền nhận ổn định giữa các node
- Giao diện giám sát hiển thị dữ liệu theo thời gian thực
- Mô hình phù hợp cho mục đích giảng dạy và mô phỏng hệ thống điều khiển ô tô

---

## Video Demo

[Xem video demo](https://drive.google.com/file/d/19ns-zEEYxKTt7lhtvhN1aRVujSTEGcxB/view?usp=drive_link)
