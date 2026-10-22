\# Dự án Quản lý Trung tâm Tiếng Anh TTA

\## Giới thiệu dự án

Hệ thống này được xây dựng nhằm \*\*quản lý học phí\*\*, ghi nhận log truy cập và \*hỗ trợ vận hành trực tuyến\* cho Trung tâm Tiếng Anh TTA

\## Cấu trúc thư mục và tài nguyên

Dưới đây là các thư mục chính và chức năng tương ứng trong hệ thống:

| Thư mục | Nội dung |

| :--- | :--- |

| `logs/` | Chứa các file log ghi nhận lịch sử truy cập (`access.log`) và thanh toán (`payment.log`) |

| `data/` | Lưu trữ các bảng dữ liệu Excel về thông tin học viên và bảng học phí tháng 10 |

| `docs/` | Chứa tài liệu lịch học chi tiết và hướng dẫn dành cho học viên |

\## Quy trình đăng ký học tại TTA

1\. Học viên tra cứu thông tin khóa học và học phí tương ứng

2\. Tiến hành điền phiếu đăng ký và thanh toán học phí qua hệ thống

3\. Hệ thống ghi nhận log thanh toán và kích hoạt tài khoản học tập

\## Lệnh kiểm tra cấu trúc dự án:

Get-ChildItem -Recurse -Force

\## Công việc

\- \[x] Tạo cấu trúc thư mục

\- \[ ] Hoàn thiện Excel

\*\*Lưu ý:\*\* Giữ file .env cục bộ, tuyệt đối không upload file .env lên GitHub

