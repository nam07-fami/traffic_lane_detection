# Lane Detection System 🚗
Dự án sử dụng thị giác máy tính (Computer Vision) để phát hiện làn đường trên đường cao tốc thông qua video hoặc hình ảnh thực tế.

## 📌 Tổng quan
Dự án này triển khai một thuật toán xử lý ảnh cơ bản để xác định các vạch kẻ đường. Đây là một phần quan trọng trong việc phát triển hệ thống hỗ trợ lái xe nâng cao (ADAS) và xe tự lái.

## 🚀 Các tính năng chính
* **Tiền xử lý:** Chuyển đổi ảnh sang Grayscale và làm mờ (Gaussian Blur).
* **Phát hiện cạnh:** Sử dụng thuật toán Canny Edge Detection.
* **Vùng chọn (ROI):** Tập trung xử lý vùng chứa làn đường để tối ưu hiệu suất.
* **Biến đổi Hough:** Sử dụng Hough Line Transform để xác định các đường thẳng từ các điểm cạnh.
* **Output:** Hiển thị làn đường được tô màu đè lên video gốc.

## 🛠 Công nghệ sử dụng
* **Ngôn ngữ:** Python
* **Thư viện chính:** * OpenCV
    * NumPy
    * Matplotlib

## 📂 Cấu trúc thư mục
```text
├── data/               # Chứa video/hình ảnh đầu vào
├── src/                # Mã nguồn xử lý chính
├── output/             # Kết quả sau khi chạy thuật toán
├── main.py             # File chạy dự án
└── README.md           # Hướng dẫn dự án
