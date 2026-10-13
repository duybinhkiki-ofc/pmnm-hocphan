# Chương 3 - Flask căn bản

Họ tên: Phạm Lê Duy Bình
MSV: 23T1020633

## Bài 3 - Lời chào

File: b03_loi_chao.py

Chạy chương trình:
python -m flask --app b03_loi_chao run --debug --port 8000

Các URL kiểm thử:

- /hello/ -> Xin chào, bạn!
- /hello/Binh -> Xin chào, Binh!
- /hello/An -> Xin chào, An!

Chương trình sử dụng escape() để xử lý
dữ liệu người dùng khi hiển thị HTML.

## Bài 4 - Bình phương

File: b04_binh_phuong.py

Chạy chương trình:
python -m flask --app b04_binh_phuong run --debug --port 8000

Các URL kiểm thử:

- /square/12 -> Bình phương của 12 là 144
- /square/abc -> 404 Not Found
- /square/2.5 -> 404 Not Found
- /square/-3 -> Bình phương của -3 là 9

Sử dụng int(signed=True) để cho phép
nhận số nguyên âm.
