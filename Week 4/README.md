- Công nghệ sử dụng: Python, Pandas, NumPy, Matplotlib, Seaborn
- Cách hoạt động:
  B1: Load dữ liệu Titanic và hiển thị 10 dòng đầu tiên để quan sát tổng quan.
  B2: Phân tích dữ liệu thiếu bằng thống kê và trực quan hóa bằng biểu đồ Heatmap.
  B3: Xử lý dữ liệu gồm:
    Tách cột Name thành hai cột firstName và secondName.
    Chuẩn hóa cột Sex bằng cách thay thế male thành M và female thành F.
    Xử lý giá trị thiếu của Age bằng tuổi trung bình theo từng hạng vé Pclass.
    Xây dựng biến Agegroup gồm Kid, Teen, Adult và Older dựa trên độ tuổi.
    Trích xuất danh xưng xã hội namePrefix từ secondName.
    Tạo biến familySize dựa trên số thành viên gia đình đi cùng.
  B4: Áp dụng kỹ thuật function chain với pipe để xử lý dữ liệu theo từng bước liên tiếp.
- Kết quả:
  Dữ liệu được làm sạch, không còn thiếu ở các biến quan trọng
  Bổ sung các đặc trưng mới có ý nghĩa cho mô hình dự đoán
  Dataset sẵn sàng cho bước xây dựng mô hình Machine Learning
