---
title: "Hệ thống giám sát nhiệt độ LM35"
excerpt: "Dự án sử dụng Arduino đọc cảm biến LM35, xử lý dữ liệu định dạng JSON và giao tiếp Serial với máy tính. <br/><img src='/assets/images/arduino_logo.png' width='100px'>"
collection: portfolio
---

## Tổng quan dự án
Dự án này tập trung vào việc xây dựng một hệ thống đo lường và giám sát nhiệt độ sử dụng cảm biến **LM35** và bo mạch **Arduino**. Hệ thống có khả năng đọc dữ liệu từ nhiều kênh, đóng gói dữ liệu theo định dạng **JSON** và truyền tải qua giao tiếp Serial để hiển thị trên máy tính.

## Các tính năng chính
* Đọc giá trị nhiệt độ từ cảm biến analog LM35 với độ chính xác cao.
* Hỗ trợ đọc dữ liệu đa kênh (A0, A1) đồng thời.
* Chuyển đổi dữ liệu sang định dạng JSON chuyên nghiệp, sẵn sàng cho các ứng dụng web/máy tính.
* Quản lý phiên bản và lịch sử commit chặt chẽ thông qua hệ thống Git.

## Công nghệ sử dụng
* **Phần cứng:** Arduino Uno/Nano, cảm biến nhiệt độ LM35.
* **Ngôn ngữ:** C++ (Arduino Sketch).
* **Quản lý mã nguồn:** Git, GitHub.

## Liên kết kho mã nguồn (Repository)
Bạn có thể xem chi tiết toàn bộ mã nguồn, sơ đồ mô phỏng Proteus và ứng dụng C# đi kèm tại đây:

👉 [**GitHub: Arduino_LM35_TempMonitor**](https://github.com/pthinh18/Arduino_LM35_TempMonitor)
