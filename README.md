# t_meter

Kết nối Pzem và ESP8266
D1<=>TX
D2<=>RX
5v<=>5V
GND<=>GND


I. LẮP ĐẶT
T-Meter là công tơ điện tử ứng dụng trên công nghệ Wifi IoT được thiết kế dễ dàng lắp đặt vào nguồn cung cấp điện mà không phải tháo hay đấu nối phức tạp.
-	Chân số 1 và 2 tính từ trái sang đấu vào 2 chân của cảm biến dòng kèm theo. Kẹp cảm biến dòng vào đường dây điện đi vào nhà sau công tơ điện lực.
-	Chân số 3 và 4 nối trực tiếp vào nguồn điện 220v của nhà. Có thể đấu qua ổ cắm hoặc đấu trực tiếp vào aptomat, cầu dao,..

 


II. THÔNG SỐ KỸ THUẬT
1.1 Điện áp (U)

1.1.1 Điện áp: 80 260V

1.1.2 Độ phân giải: 0.1V

1.1.3 Độ chính xác của phép đo: 0,5%

1.2 Dòng điện (A)

1.2.1 Phạm vi đo: 0 ～ 100A

1.2.2 Dòng đo khởi động: 0,02A

1.2.3 Độ phân giải: 0,001A

1.2.4 Độ chính xác của phép đo: 0,5%

1.3 Công suất (kW)

1.3.1 Phạm vi đo: 0 ~23kW

1.3.2 Công suất đo khởi động: 0.4W

1.3.3 Độ phân giải: 0.1W

1.3.5 Độ chính xác của phép đo: 0,5%

1.4 Hệ số công suất (PF)

1.4.1 Phạm vi đo: 0,00 ~ 1,00

1.4.2 Độ phân giải: 0,01

1.4.3 Độ chính xác của phép đo: 1%

1.5 tần số (Hz)

1.5.1 Phạm vi đo: 45Hz ~ 65Hz

1.5.2 Độ phân giải 0.1Hz

1.5.3 Độ chính xác đo: 0,5%

1.6 Điện năng tiêu thụ (kWh)

1.6.1 Phạm vi đo: 0 ~ 9999,99kWh

1.6.2 Độ phân giải: 1Wh

1.6.3 Độ chính xác đo: 0,5%


III. SỬ DỤNG
1.	Khởi động và kết nối wifi
-	Khi bắt đầu cấp nguồn sau 15~30 giây nếu chưa có kết nối wifi được thiết lập. Thiết bị tự động phát wifi “T-Meter_XXXX” trong đó XXXX là ID của công tơ.
-	Người dùng sử dụng máy tính hoặc điện thoại di động thực hiện kết nối đến Wifi của công tơ, mật khẩu mặc định là “12345678”
-	Sau khi kết nối thành công, sử dụng trình duyệt truy cập đến địa chỉ: “http://192.168.4.1” để vào trang web của công tơ.
-	Vào mục “CONNECT”, chọn “Scan wifi” Sau đó chọn wifi cần kết nối. Nhập mật khẩu wifi cần kết nối và ấn “Save”.
-	Ấn tiếp “Khởi động lại” để thực hiện khởi động lại thiết bị và kết nối tới wifi được cài đặt.
-	Sau khi kết nối nếu Wifi “T-Meter_XXXX” không còn nữa thì thiết bị đã kết nối thành công. Lúc này người dùng truy cập cùng wifi với công tơ sau đó truy cập địa chỉ: “http://tmeter.local/” để truy cập vào xem chỉ số của công tơ.
