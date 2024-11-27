# Mạch thu phát MKE-M15 Bluetooth 3.0 SPP / BLE 4.2 Dual Mode module

![](/image/MKE_M15_1.jpg)

## Giới thiệu

Mạch thu phát MKE-M15 Bluetooth 3.0 SPP / BLE 4.2 Dual Mode module được sử dụng để truyền nhận dữ liệu qua Bluetooth với các Máy Tính, Điện Thoại Smart Phone hỗ trợ Bluetooth 3.0 SPP và BLE 4.2, ở chế độ Bluetooth 3.0 SPP mạch có thể được sử dụng để thay thế các mạch Bluetooth HC-05/HC-06 với độ tương thích gần như hoàn toàn (có thể thay thế mà không cần chỉnh sửa code), với BLE 4.2 mạch có thể kết nối với hầu hết các Smartphone mới nhất hiện nay sử dụng hệ điều hành Android / IOS như: Iphone, Ipad,..., mạch sử dụng chuẩn giao tiếp UART, hỗ trợ bộ tập lệnh AT Commands rất dễ dàng để kết nối và sử dụng.

Mạch thu phát MKE-M15 Bluetooth 3.0 SPP / BLE 4.2 Dual Mode module thuộc hệ sinh thái phần cứng Robotics MakerEdu nên có thể sử dụng trực tiếp an toàn với các mạch điều khiển trung tâm ở cả hai mức điện áp 3.3VDC và 5VDC như: Arduino, Raspberry Pi, Jetson Nano, Micro:bit,....với chuẩn kết nối Connector XH2.54 thông dụng.

## Thông số kỹ thuật

- Module Bluetooth sử dụng: JDY-33
- Điện áp hoạt động: 5VDC
- Điện áp giao tiếp: TTL 3.3VDC/5VDC
- Chuẩn giao tiếp: Digital UART
- Baudrate Default: 9600, N, 8, 1
- Hỗ trợ cấu hình qua bộ tập lệnh AT Commands.
- Chuẩn kết nối Bluetooth: Bluetooth 3.0 SPP và BLE 4.2 (tương thích Máy Tính, Điện Thoại Smart Phone hỗ trợ Bluetooth 2.0 / 3.0 và 4.0)
- Tần số sóng: 2.4Ghz
- Khoảng cách truyền nhận tối đa: 30m
- Tương thích hệ điều hành: Windows / Android / IOS
- Sử dụng trực tiếp an toàn với các board mạch giao tiếp ở cả hai mức điện áp 3.3VDC và 5VDC như: Arduino, Raspberry Pi, Jetson Nano, Micro:bit,....
- Bổ sung thêm các thiết kế ổn định, chống nhiễu.
- Chuẩn kết nối: Conector XH2.54 4Pins
- Thuộc hệ sinh thái phần cứng Robotics MakerEdu, tương thích tốt nhất khi sử dụng với các mạch điều khiển trung tâm của MakerEdu và MakerEdu Shield.

## Bộ tập lệnh AT Commands

Nếu muốn thay đổi các thiết lập mặc định (thường không cần thiết), bạn có thể sử dụng bộ tập lệnh cấu hình AT Commands để cấu hình lại cho Mạch thu phát MKE-M15 Bluetooth 3.0 SPP / BLE 4.2 Dual Mode module, tuy nhiên việc này cần sử dụng thêm mạch chuyển USB-UART hoặc lập trình qua Arduino, xin lưu ý thiết lập đúng **Baudrate Default: 9600, N, 8, 1** và sau các lệnh **AT** cần thêm **\r\n**:
![](/image/MKE_M15_2.jpg)

## Kích thước

![](/image/MKE_M15_3.jpg)

## Các chân tín hiệu
![](/image/MKE_M15_4.jpg)
<table><thead>
  <tr>
    <th>MKE-M15</th>
    <th>Ghi chú</th>
  </tr></thead>
<tbody>
  <tr>
    <td>GND</td>
    <td>Chân cấp nguồn âm 0VDC</td>
  </tr>
  <tr>
    <td>5V</td>
    <td>Chân cấp nguồn dương 5VDC</td>
  </tr>
  <tr>
    <td>TX</td>
    <td>Chân truyền tín hiệu UART Transmitter</td>
  </tr>
  <tr>
    <td>RX</td>
    <td>Chân nhận tín hiệu UART Receiver</td>
  </tr>
</tbody>
</table>


## Hướng dẫn sử dụng

### Các thiết bị sử dụng trong bài hướng dẫn

#### Arduino

- [Mạch Vietduino Uno (Arduino Uno Compatible)](https://www.makerlab.vn/vuno)
- [Mạch MakerEdu Shield for Vietduino](https://www.makerlab.vn/vietduinosd)
- [Mạch màn hình MKE-M07 LCD1602 I2C Display Module](https://www.makerlab.vn/mkem07)

#### mBlock

- [Mạch MakerEdu Creator (Arduino Uno Compatible)](https://www.makerlab.vn/creator)
- [Mạch màn hình MKE-M07 LCD1602 I2C Display Module](https://www.makerlab.vn/mkem07)

#### Micro:bit:

- [Mạch Micro:bit V2](https://hshop.vn/products/kit-hoc-lap-trinh-stem-cho-tre-em-micro-bit-v2) hoặc các phiên bản tương thích.
- [Mạch MakerEdu Shield for Micro:bit](https://www.makerlab.vn/microbitsd)
- [Mạch màn hình MKE-M07 LCD1602 I2C Display Module](https://www.makerlab.vn/mkem07)

### Hướng dẫn sử dụng với Arduino (Code C)

[Hướng dẫn cài đặt phần mềm, nạp chương trình, cài đặt bộ thư viện Arduino cơ bản.](https://github.com/makerlabvn/Arduino-Vietduino)

- Tải và cài đặt [phần mềm Arduino tại đây.](https://www.arduino.cc/en/software)
- Trong Tools / Library Manager, tìm và cài đặt bộ thư viện tổng hợp "MAKERLABVN" by MakerLab.vn
- Mở chương trình mẫu "MKE_M15_Bluetooth_LCD_Serial.ino" tại File / Examples / MAKERLABVN / Module / MKE_M15_Bluetooth_LCD_Serial hoặc [tải chương trình mẫu tại đây](/arduino)
- Chọn board là Arduino Uno (mạch Vietduino Uno tương thích với Arduino Uno), chọn đúng cổng COM Port của mạch và tiến hành nạp chương trình.
- Kết nối mạch Vietduino Uno với MakerEdu Shield, kết nối màn hình LCD vào cổng [I2C] trên MakerEdu Shield, cấp nguồn qua cổng USB của Vietduino Uno để thấy chương trình hoạt động.

### Hướng dẫn lập trình với mBlock (kéo thả khối)

[Hướng dẫn cài đặt phần mềm, nạp chương trình, cài đặt Extension mBlock cơ bản.](https://github.com/makerlabvn/mBlock-MakerEdu-Creator)

- Tải và cài đặt phần mềm mBlock 5 ([Windows](https://www.mediafire.com/file/ma55iajd7glwmbo/%255BMakerLab.vn%255D_mBlock_V5.4.3_for_Windows.zip/file) / [Mac Intel](https://www.mediafire.com/file/pjfngy6d7ktb55f/%255BMakerLab.vn%255D_mBlock_V5.4.3_for_Mac_Intel.zip/file) / [Mac M1M2](https://www.mediafire.com/file/mfdkgpgnpa7uv2s/%255BMakerLab.vn%255D_mBlock_V5.4.3_for_Mac_M1M2.zip/file))
- Thêm Device "MakerEdu Creator" by MakerEduVN
- Thêm Extension "Upload Mode Broadcast" by mBlock Official
- Thêm Extension "MakerEdu Hardware" by MakerEduVN
- Mở [chương trình mẫu tại đây](/mBlock5), kết nối MakerEdu Creator với máy tính và nạp chương trình.
- Kết nối màn hình LCD vào cổng [I2C] trên MakerEdu Creator, cấp nguồn qua cổng USB của MakerEdu Creator để thấy chương trình hoạt động.

### Hướng dẫn lập trình với Micro:bit (kéo thả khối)

[Hướng dẫn nạp chương trình, cài đặt Extension Micro:bit cơ bản.](https://github.com/makerlabvn/MakeCode-microbit)

- Khởi động phần mềm MakeCode tại: [https://makecode.microbit.org/](https://makecode.microbit.org/)
- Chọn My Projects / Import / Import URL theo đường link của chương trình mẫu: [https://github.com/devmakerlabvn/](https://github.com/devmakerlabvn/makecode-mke-s01-ultrasonic-distance-sensor)
- Kết nối Micro:bit với máy tính và nạp chương trình.
- Kết nối mạch Micro:bit với MakerEdu Shield, màn hình LCD vào cổng [I2C] trên MakerEdu Shield, **cấp nguồn qua cổng USB của MakerEdu Shield** để thấy chương trình hoạt động.

## Hỗ trợ và liên hệ

- Website: [https://www.makerlab.vn/](https://www.makerlab.vn/)
- Facebook: [https://www.facebook.com/makerlabvn](https://www.facebook.com/makerlabvn)

## Nhà phân phối

- Các bạn có thể mua sản phẩm của MakerLab tại các [Nhà Phân Phối.](https://www.makerlab.vn/distributor/)