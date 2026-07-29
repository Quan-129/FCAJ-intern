---
title: "Báo cáo Tuần 8"
date: 2026-07-20
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Mục tiêu tuần 8:

* Nắm vững các phương thức mã hóa dữ liệu, quản lý khóa bảo mật và thông tin xác thực tập trung.
* Xây dựng lớp phòng thủ chống lại các cuộc tấn công web phổ biến và quản trị máy chủ không cần mở cổng mạng (port) công khai.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                                                                                                                                                       | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Nghiên cứu mã hóa với AWS KMS (Key Management Service): <br>&emsp; + Mã hóa dữ liệu ở trạng thái nghỉ (At rest) và khi truyền tải (In transit) <br>&emsp; + Phân biệt Customer Managed Keys (CMK) và AWS Managed Keys         | 20/07/2026   | 20/07/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Khảo sát AWS Secrets Manager & SSM Parameter Store: <br>&emsp; + So sánh tính năng và chi phí của 2 dịch vụ <br>&emsp; + Cơ chế xoay vòng thông tin xác thực (Credential Rotation) tự động với RDS                            | 21/07/2026   | 21/07/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - **Triển khai lab Quản lý Bí mật:** <br>&emsp; + Mã hóa bucket S3 bằng KMS key tự tạo <br>&emsp; + Lưu trữ mật khẩu CSDL vào Secrets Manager <br>&emsp; + Viết code cho EC2/Lambda gọi API để lấy mật khẩu thay vì hardcode    | 22/07/2026   | 22/07/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Tìm hiểu bảo mật biên (Edge Security) với WAF & Shield: <br>&emsp; + Cơ chế chống DDoS của AWS Shield (Standard vs Advanced) <br>&emsp; + Cấu hình AWS WAF chặn các lỗ hổng OWASP Top 10 (SQLi, XSS) trên ALB/CloudFront      | 23/07/2026   | 23/07/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - Tìm hiểu AWS Systems Manager (SSM): <br>&emsp; + Cơ chế hoạt động của SSM Agent <br>&emsp; + **Thực hành:** Dùng SSM Session Manager kết nối terminal vào EC2 ở Private Subnet mà không cần Bastion Host hay mở port 22 (SSH) | 24/07/2026   | 24/07/2026      | <https://cloudjourney.awsstudygroup.com/> |


### Kết quả đạt được tuần 8:

* Nâng cao tiêu chuẩn bảo mật dữ liệu cho hệ thống:
  * Nắm rõ cách sử dụng AWS KMS để tạo và quản lý vòng đời của các khóa mã hóa.
  * Hiểu nguyên tắc tuyệt đối không hardcode (gắn cứng) mật khẩu, token vào mã nguồn.
  * Thành thạo việc sử dụng Parameter Store và Secrets Manager để lưu trữ, truy xuất an toàn các thông tin nhạy cảm.
  * ...

* Triển khai thành công các lá chắn bảo vệ ứng dụng (Application Protection):
  * Biết cách thiết lập quy tắc tường lửa ứng dụng web (AWS WAF) để chặn các truy cập độc hại, bảo vệ an toàn cho Load Balancer hoặc CloudFront.
  * Hiểu cách AWS Shield tự động bảo vệ hệ thống khỏi các đợt tấn công từ chối dịch vụ (DDoS) ở quy mô hạ tầng.
  * ...

* Tối ưu hóa vận hành hệ thống an toàn (SecOps):
  * Loại bỏ hoàn toàn rủi ro bảo mật từ việc mở cổng SSH (port 22) ra Internet.
  * Đăng nhập an toàn vào máy chủ thông qua giao diện web/CLI bằng SSM Session Manager, đồng thời ghi log lại toàn bộ lịch sử gõ lệnh để kiểm toán.
  * ...