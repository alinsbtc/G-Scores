G-Scores

Hướng dẫn chạy dự án Django (G-Scores)

1. Cài đặt môi trường

Người dùng cần cài đặt các công cụ cơ bản:

Python (phiên bản 3.8+)

Git (để tải mã nguồn từ GitHub)

Virtualenv (để tạo môi trường ảo)

2. Clone dự án từ GitHub

Tải mã nguồn từ GitHub về máy:

git clone https://github.com/alinsbtc/G-Scores.git

Di chuyển vào thư mục dự án:

cd G-Scores

3. Tạo và kích hoạt môi trường ảo

Tạo môi trường ảo để cách ly các gói Python:

python -m venv venv

Kích hoạt môi trường ảo:

Windows:

venv\Scripts\activate

Mac/Linux:

source venv/bin/activate

4. Cài đặt các gói phụ thuộc

Cài đặt các gói Python cần thiết từ file requirements.txt:

pip install -r requirements.txt

5. Cấu hình cơ sở dữ liệu

Tạo file .env trong thư mục gốc của dự án nếu có sử dụng dotenv.

Nếu dùng SQLite (mặc định):
Dự án đã được cấu hình sẵn để dùng SQLite. Bạn không cần làm thêm gì.

6. Chạy các lệnh migrate

Khởi tạo cơ sở dữ liệu bằng cách áp dụng các migrations:

python manage.py migrate

7. Tải dữ liệu mẫu (nếu có)

Nếu dự án cung cấp dữ liệu mẫu hoặc seeder, chạy lệnh sau (tùy chỉnh theo dự án):

python manage.py import_scores diem_thi_thpt_2024.csv

8. Chạy server

Chạy ứng dụng trên server phát triển:

python manage.py runserver

Truy cập trang web tại:http://127.0.0.1:8000/
