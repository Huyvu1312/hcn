==============================
TỔNG QUAN HỆ THỐNG QUẢN LÝ CHUỖI ĐIỂM BÁN
==============================

1. CÂU CHUYỆN & LÝ DO XÂY DỰNG HỆ THỐNG

1 cửa hàng hiện tại có nhiều điểm bán trải dài trên nhiều tuyến đường và khu vực khác nhau.

Việc quản lý nhân viên và vận hành hiện đang thực hiện thủ công nên phát sinh nhiều khó khăn trong quá trình vận hành.


QUY TRÌNH VẬN HÀNH HIỆN TẠI

Đối với nhân viên:

- Mỗi ngày nhân viên phải tự di chuyển tới điểm bán được phân công để làm việc.

- Chưa có hệ thống ghi nhận:
  + Giờ vào ca
  + Giờ nghỉ
  + Giờ kết thúc ca

- Sau mỗi ca bán hàng:
  + Nhân viên tự ghi chép doanh thu
  + Tự tổng hợp số liệu
  + Chụp hình báo cáo
  + Gửi báo cáo vào group chat (Zalo, Messenger,...)

- Nếu trong ca bán thiếu nguyên vật liệu (NVL):
  + Nhân viên tự kiểm kê
  + Thống kê nguyên vật liệu thiếu
  + Gửi tin nhắn lên group để yêu cầu bổ sung NVL


Đối với quản lý:

Hiện tại toàn bộ hoạt động quản lý đều thực hiện thông qua group chat:

- Theo dõi báo cáo doanh thu từ từng điểm bán
- Kiểm tra điểm bán chưa gửi báo cáo
- Nhắn tin nhắc nhở nhân viên
- Nhập lại dữ liệu thủ công vào Excel
- Theo dõi yêu cầu cấp phát nguyên vật liệu
- Kiểm kê và theo dõi tồn kho

=> Toàn bộ quy trình vận hành hiện phụ thuộc vào group chat.


KHÓ KHĂN HIỆN TẠI

Nhân viên:

- Không theo dõi được lịch sử chấm công
- Không xem được lịch sử doanh thu các ca trước
- Quy trình báo cáo thủ công, mất thời gian
- Khó theo dõi yêu cầu nguyên vật liệu

Quản lý:

- Khó kiểm soát thời gian làm việc nhân viên
- Khó quản lý doanh thu từng điểm bán
- Tốn thời gian nhập liệu Excel
- Khó kiểm soát cấp phát nguyên vật liệu
- Khó quản lý tồn kho


==============================
GIẢI PHÁP HỆ THỐNG
==============================

Xây dựng hệ thống quản lý tập trung trên Odoo kết hợp Mobile App.

Mục tiêu:

- Thay thế quy trình quản lý qua group chat
- Tập trung dữ liệu trên một hệ thống duy nhất
- Tự động hóa quy trình vận hành
- Quản lý doanh thu, nhân viên và nguyên vật liệu theo thời gian thực


==============================
CẤU TRÚC HỆ THỐNG
==============================

Hệ thống gồm 3 nhóm người dùng chính:

1. ADMIN ODOO (QUẢN TRỊ HỆ THỐNG)

Có quyền quản lý toàn bộ chuỗi cửa hàng.

Chức năng:

Quản lý cửa hàng:
- Tạo cửa hàng
- Quản lý điểm bán

Quản lý sản phẩm:
- Gán sản phẩm cho cửa hàng
- Thiết lập bảng giá riêng theo cửa hàng

Quản lý nguyên vật liệu:
- Quản lý danh sách NVL
- Quản lý tồn kho
- Kiểm soát cấp phát NVL

Quản lý nhân sự:
- Gán nhân viên vào cửa hàng
- Gán quản lý cửa hàng

Vận hành:
- Theo dõi chấm công
- Theo dõi doanh thu
- Quản lý yêu cầu NVL
- Báo cáo tổng hợp toàn hệ thống


2. ADMIN CỬA HÀNG

Quản lý các cửa hàng được phân quyền.

Chức năng:

- Dashboard tổng quan
- Quản lý điểm bán
- Quản lý nhân viên
- Theo dõi chấm công
- Theo dõi doanh thu
- Xử lý yêu cầu NVL
- Theo dõi tồn kho
- Báo cáo vận hành


3. MOBILE APP CHO NHÂN VIÊN

Ứng dụng dành cho nhân viên bán hàng tại quầy.

Chức năng:

Chấm công:
- Check-in / Check-out
- Lịch sử chấm công

Báo cáo doanh thu:
- Tạo báo cáo cuối ca
- Xem lịch sử doanh thu

Nguyên vật liệu:
- Gửi yêu cầu bổ sung NVL
- Theo dõi trạng thái xử lý

Thông báo:
- Nhận thông báo từ quản lý
- Theo dõi trạng thái yêu cầu


==============================
GIÁ TRỊ MANG LẠI
==============================

Nhân viên:

- Dễ dàng chấm công
- Quản lý lịch sử làm việc
- Báo cáo nhanh trên điện thoại
- Theo dõi yêu cầu NVL

Quản lý:

- Theo dõi nhân viên theo thời gian thực
- Kiểm soát doanh thu từng điểm bán
- Giảm nhập liệu thủ công
- Quản lý tồn kho và cấp phát NVL

Doanh nghiệp:

- Chuẩn hóa quy trình vận hành
- Tập trung dữ liệu
- Giảm phụ thuộc group chat
- Dễ dàng mở rộng chuỗi điểm bán