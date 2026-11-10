Tính toán, thiết kế một bộ nguồn di động có khả năng cấp ra điện áp từ điều chỉnh được bằng núm xoay vặn bằng tay, sau này sẽ nâng cấp lên điều chỉnh trên phần mềm điện thoại/ máy tính. Ngoài ra còn có thể quan sát được điện áp hiện tại, dòng điện tiêu thụ của tải, hiển thị trên màn hình OLED 0.98" và sau này có thể hiển thị lên phần mềm điện thoại/ máy tính.


Yêu cầu kĩ thuật:
- Phải có một sơ đồ tổng quát cụ thể 
- Phải tính toán được các tất cả các thông số chứ không nói đại
- điều chỉnh từ 0 đến 12V bằng núm xoay (không nhất thiết phải về 0V), nếu có thể sau này sẽ điều chỉnh trên phần mềm
- có thể cấp dòng tối đa 6A --> 12*6 = 78W
- Hệ thống sẽ dùng pin, chứ không dùng nguồn adapter, các bộ phận quản lý pin (BMS) nằm riêng
- Có khả năng hiển thị các thông số lên một màn hình OLED, nếu có thể sau này sẽ quan sát trên phần mềm
- Đang hướng tới tạo thêm xung clock nữa chu kỳ 1 giây và các 
- Hệ thống sẽ có các khối bảo vệ quá dòng, quá áp, quá nhiệt,...
- Sẽ thiết kế toàn bộ trên PCB mà không dùng module ghép lại, riêng chỉ có ESP32 là dùng module gắn lên PCB
- Sau này sẽ nâng cấp lên thiết kế vỏ đi in 3D


Linh kiện sẽ sử dụng
- ESP32 WROOM 32D: 120.000
- OLED 0.98" giao tiếp I2C: 45.000
- IC nguồn XL4016 - ADJ/8A: 25.000
- IC LM2596 5V/3A: 15.000
- Nguồn 4 cell pin 18650 mắc nối tiếp 16V, các phụ kiện BMS: xx 100.000
- Module đo dòng ACS712-5A: 40.000
- Các linh kiện và ngoại vi khác thêm vào trong quá trình làm: xx 200.000
- Mạch in PCB 2 lớp, gia công: 200.000
- Vỏ 3D nếu hoàn thành: 200.000


Các kiến thức cơ bản cần phải có:
- Giao thức và Ngoại vi: I2C, ADC, GPIO, Timer, PWM
- Buck converter
- ArduinoIDE và ESP-IDF


