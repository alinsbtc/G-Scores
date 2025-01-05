# G-Scores
## Features

- Nhập dữ liệu thô vào cơ sở dữ liệu
- Tính năng kiểm tra điểm số từ số báo danh
- Tính năng báo cáo (Report)
- Danh sách top 10 học sinh nhóm A (Toán, Lý, Hóa)
- Responsive Design

## Hướng dẫn chạy dự án Django (G-Scores)
- **Python**: 3.11.5
- **Django**: 5.1.3
## Installation
1. **Clone the repository**
   ```bash
   git clone https://github.com/alinsbtc/G-Scores.git
## Create and activate a virtual environment:
   1. Create and activate a virtual environment:
       ```bash
       python -m venv ven
   - **Windows**: venv\Scripts\activate
   - **Mac/Linux**: source venv/bin/activate
       
## Setup Instructions
1. Set up the database
    ```bash
   python manage.py migrate
2. Tải dữ liệu mẫu (nếu có)
    ```bash
    python manage.py import_scores diem_thi_thpt_2024.csv
3. Run the development server
    ```bash
    python manage.py runserver
Now, you can access the application at http://127.0.0.1:8000/.
# Tính năng kiểm tra điểm số từ số báo danh:

# Nhập số báo danh và kiểm tra điểm số chi tiết.

# Tính năng báo cáo (Report):

- Phân chia thành 4 mức điểm:



# Thống kê số lượng học sinh theo từng mức điểm cho từng môn học.

- Hiển thị báo cáo dạng biểu đồ.

# Danh sách top 10 học sinh nhóm A (Toán, Lý, Hóa):

- Liệt kê top 10 học sinh có tổng điểm cao nhất của các môn Toán, Vật Lý, Hóa Học.

# Responsive Design:

- Giao diện hiển thị tốt trên mọi thiết bị: máy tính, máy tính bảng, và điện thoại di động.


