- Công nghệ sử dụng: ngôn ngữ lập trình python, thư viện pandas
- Cách thức hoạt động:
  Bước 1:
  Đọc file CSV không có dòng tiêu đề
  Sử dụng `engine="python"` để xử lý các dòng lỗi định dạng
  Bỏ qua các dòng lỗi trong quá trình đọc dữ liệu
  Bước 2:
  Chuẩn hóa tên cột
  Xử lý các ký tự không phải ASCII trong dữ liệu văn bản
  Chuyển đổi dữ liệu ngày tháng về định dạng chuẩn
  Bước 3:
  Thay thế giá trị huyết áp bị thiếu theo thứ tự ưu tiên:
    Trung bình của giá trị liền trước và liền sau của cùng bệnh nhân
    Trung bình 2 giá trị liền trước
    Trung bình 2 giá trị liền sau
    Trung bình các giá trị huyết áp của bệnh nhân
    Trung bình theo nhóm giới tính
    Trung bình toàn bộ dữ liệu
  Bước 4:
  Loại bỏ các dòng trống
  Loại bỏ các dòng trùng lặp
  Loại bỏ các giá trị huyết áp không hợp lệ
  Bước 5:
  Chỉ giữ các cột cần thiết cho phân tích
  Reset lại chỉ số cho dữ liệu
  Lưu dữ liệu đã xử lý thành file CSV mới
- Kết quả:
  Dữ liệu huyết áp đã được làm sạch và chuẩn hóa
  Các giá trị huyết áp bị thiếu đã được xử lý hợp lý
  Loại bỏ dữ liệu trùng lặp và không hợp lệ
  Dữ liệu sẵn sàng cho phân tích
