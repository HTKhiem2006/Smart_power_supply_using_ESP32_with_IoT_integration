Tính toán và thiết kế một bộ nguồn cung cấp điện áp có khả năng điều chỉnh điện áp từ 0-12V với khả năng chịu được dòng điện tối đa 5A

12 * 5 = 60W

- OLED SPI/ I2C: dùng để hiển thị thông số trên màn hình lớn
- ESP32-WROOM-32D: Vi điều khiển
- LM2596: hạ áp xuống 5V
- XL4016: hạ áp và điều chỉnh được 0-12V
- ACS712-5B: cảm biến đo dòng 5A
- MCP41010: biến trở số để ESP32 giao tiếp với XL4016 thông qua chân FB
- Các nút nhấn và công tắc để tương tác với hệ thống
- Còi bíp và LED để báo hiệu

