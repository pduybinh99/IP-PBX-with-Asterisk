# IP-PBX-with-Asterisk
Cấu hình tổng đài Asterisk sử dụng cho VoIP

*Kịch bản:
Công ty BEdu thiết lập tổng đài tự động với thông tin như sau:

- Số tổng đài 18001900

- Các số phòng ban nội bộ:
	101: Lễ Tân
	1021: Tư vấn 1
	1022: Tư vấn 2
	103: Nhân sự
	104: Marketing & Chăm sóc khách hàng

- Kịch bản gọi:
	=> Khách hàng sử dụng số 0286778899 gọi đến tổng đài 18001900 của công ty BEdu
	1. Nhạc chờ được phát tự động
	2. Nhấn phím * để có thể lặp lại nhạc chờ
	3. Nhấn phím 1 để gặp bộ phận Lễ Tân => điện thoại của Lễ Tân đổ chuông
	4. Nhấn phím 2 để gặp bộ phận Tư Vấn => điện thoại của Tư Vấn Viên 1 và Tư Vấn Viên 2 đổ chuông đồng 
thời. 
		4.1.Nếu 1 người nhấc máy thì người còn lại sẽ tự động tắt. 
		4.2.Nếu 1 người tắt thì điện thoại người còn lại vẫn đổ chuông
		4.3.Nếu cả 2 cùng tắt thì quay lại tổng đài, nhạc chờ được phát
	5. Nhấn phím 3 để gặp bộ phận Nhân Sự => điện thoại của Nhân Sự đổ chuông
	6. Nhấn phím 4 để gặp bộ phận Marketing & CSKH => điện thoại MKT & CSKH đổ chuông
	7. Nhấn phím # để kết thúc cuộc gọi
	=> Ngoài ra các phòng ban nội bộ có thể liên lạc cho nhau thông qua các số đã cấu hình sẵn.
* Khách hàng sử dụng số 0286778899

