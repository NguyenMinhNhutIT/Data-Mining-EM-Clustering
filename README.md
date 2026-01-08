# 📊 Student Performance Analysis using EM Algorithm

Dự án báo cáo giữa kỳ môn **Khai thác dữ liệu và Khai phá tri thức** Tập trung nghiên cứu và ứng dụng thuật toán **Expectation-Maximization (EM)** trong việc xử lý dữ liệu thiếu và phân tích kết quả học tập của sinh viên.


## 🎯 Mục tiêu dự án
1. **Tìm hiểu lý thuyết**: Khái niệm, lịch sử và quy trình hoạt động của thuật toán EM.
2. **Tiền xử lý dữ liệu**: Làm sạch dữ liệu từ bộ `STU_Dataset.csv`, xử lý các bản ghi lỗi và ngoại lệ.
3. **Ứng dụng thuật toán**: 
   - Sử dụng EM để điền giá trị thiếu (Imputation).
   - Phân cụm dữ liệu dựa trên các đặc trưng: Study Hours, Attendance Rate, Previous Grades.
4. **Đánh giá**: So sánh thuật toán EM với K-Means để thấy sự khác biệt về hiệu quả.



## 📂 Cấu trúc thư mục
- `STU_Dataset.csv`: Dữ liệu thô ban đầu (40,000 bản ghi).
- `valid_records.csv`: Dữ liệu sau khi lọc các bản ghi không hợp lệ.
- `imputed_data.csv`: Dữ liệu hoàn chỉnh sau khi áp dụng EM để xử lý Missing Values.
- `Demo_code.ipynb`: File Notebook chứa toàn bộ mã nguồn xử lý và trực quan hóa.

## 🛠️ Công cụ sử dụng
- **Ngôn ngữ**: Python
- **Thư viện chính**: `pandas`, `numpy`, `seaborn`, `matplotlib`.

## 🚀 Hướng dẫn chạy
1. Tải toàn bộ các file `.csv` và file `.ipynb` về cùng một thư mục.
2. Mở file `Demo_code.ipynb` bằng Jupyter Notebook hoặc Google Colab.
3. Chạy các Cell theo thứ tự để xem quy trình tiền xử lý và kết quả phân tích.