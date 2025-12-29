<div align="center">

# SNA Dashboard: Tối ưu hóa Lan truyền trên Mạng xã hội

Đây là ứng dụng Web Demo tương tác (Interactive Dashboard) thuộc đồ án phân tích mạng xã hội Facebook. Ứng dụng cho phép trực quan hóa cấu trúc cộng đồng và chạy mô phỏng so sánh hiệu quả giữa các chiến lược Seeding (Hubs vs. Bridges).

## 1. Yêu cầu Hệ thống
- **Ngôn ngữ:** Python 3.8 trở lên.
- **Môi trường:** VSCode (khuyên dùng) hoặc Terminal/Command Prompt.

## 2. Cấu trúc Thư mục (Quan trọng)
Để ứng dụng chạy ổn định, vui lòng đảm bảo các file sau nằm trong **CÙNG MỘT THƯ MỤC**:

```text
Project_Folder/
 ├── app.py                        # Mã nguồn chính của Web Demo
 ├── facebook_combined_cleaned.txt # Dữ liệu đồ thị (Edge List)
 ├── role_table.csv                # Dữ liệu vai trò nút (Output từ Node2Vec)
 └── README.md                     # File hướng dẫn này