# Firmware T-Meter
## V2.3: 
	- Fix lỗi tự động reconnect blynk server mỗi 2 phút
	- Tự động kết nối lại khi mất điện và wifi nhà khởi động chậm
	- Tự động kết nối lại khi mất wifi và có wifi trở lại

## V2.4:
Update trạng thái led tốt hơn, nâng cấp chức năng click vào để thêm wifi vào ô SSID
Trạng thái led: 
- Lúc khởi động led off
- Lúc kết nối wifi led nhấp nháy 0.5s
- Lúc đã kết nối wifi led sáng
- Lúc đang đọc công tơ led chớp

## V2.5
- Update chế độ nút ấn:
	+ Ấn 1s nhả ra sẽ reset thiết bị
	+ Ấn >6s sẽ khôi phục mặc định thiết bị, xóa hết dữ liệu, chỉ số đo,..
- Update trạng thái led:
	+ Khởi dộng tìm kiếm kết nối wifi: led nhấp nháy
	+ Kết nối wifi thành công led sáng
	+ Không có kết nối wifi led tắt
	+ Đọc chỉ số và gửi server lớp chớp chớp

## V2.6
- Thêm một số chức năng ẩn dùng để chốt chỉ số theo ngày tháng bằng tay.
	+ "ip/chotngay" để thực hiện chốt chỉ số theo ngày ngay lập tức
	+ "ip/chotthang" để chốt chỉ số tháng ngay lập tức
