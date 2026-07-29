---
title: "Báo cáo Tuần 7"
date: 2026-07-13
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu tuần 7:

* Xây dựng và vận hành chuỗi tự động hóa tích hợp và triển khai phần mềm (CI/CD Pipeline) với AWS Developer Tools.
* Nắm vững cơ chế giám sát hiệu suất, thu thập log và kiểm toán bảo mật toàn hệ thống.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                                                                                                                                                       | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Nghiên cứu khái niệm CI/CD và AWS CodeBuild: <br>&emsp; + Sự khác biệt giữa Continuous Integration, Delivery và Deployment <br>&emsp; + Cấu hình file buildspec.yml <br>&emsp; + Biên dịch và chạy test tự động               | 13/07/2026   | 13/07/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Khảo sát AWS CodeDeploy & CodePipeline: <br>&emsp; + Các chiến lược triển khai (In-place, Blue/Green deployment) <br>&emsp; + Cấu hình file appspec.yml <br>&emsp; + Thiết kế luồng Pipeline tự động hóa từ Source tới Deploy | 14/07/2026   | 14/07/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - **Triển khai lab CI/CD:** <br>&emsp; + Kết nối GitHub repository với AWS <br>&emsp; + Xây dựng CodePipeline tự động build và deploy một ứng dụng web lên EC2 khi có commit mới                                                | 15/07/2026   | 15/07/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Khảo sát hệ thống giám sát Amazon CloudWatch: <br>&emsp; + Phân biệt Metrics, Alarms và Events (EventBridge) <br>&emsp; + Thu thập và phân tích nhật ký tập trung với CloudWatch Logs <br>&emsp; + Tạo Dashboard giám sát     | 16/07/2026   | 16/07/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - Tìm hiểu kiểm toán bảo mật với AWS CloudTrail: <br>&emsp; + Khái niệm API Call Tracking và Event History <br>&emsp; + **Thực hành:** Tạo CloudWatch Alarm cảnh báo khi CPU EC2 vượt ngưỡng 80% và truy xuất log CloudTrail    | 17/07/2026   | 17/07/2026      | <https://cloudjourney.awsstudygroup.com/> |


### Kết quả đạt được tuần 7:

* Làm chủ quy trình phát triển và triển khai phần mềm hiện đại (DevOps):
  * Hiểu và viết được các file cấu hình tiêu chuẩn (`buildspec.yml`, `appspec.yml`) để định tuyến quá trình đóng gói và cài đặt ứng dụng.
  * Thiết lập thành công một CI/CD Pipeline hoàn chỉnh, giúp giảm thiểu thao tác thủ công và lỗi con người khi release tính năng mới.
  * Hiểu rõ ưu/nhược điểm của các chiến lược triển khai (Blue/Green vs In-place).
  * ...

* Thiết lập được hệ thống "mắt thần" giám sát toàn bộ tài nguyên trên Cloud:
  * Đẩy thành công log từ các instance EC2 về CloudWatch Logs để quản lý tập trung.
  * Tự động hóa việc phản ứng với các sự cố hệ thống thông qua CloudWatch Alarms (ví dụ: cảnh báo quá tải).
  * ...

* Nâng cao năng lực bảo mật và tuân thủ (Compliance):
  * Sử dụng CloudTrail để truy vết mọi hành động (API calls) được thực hiện trong tài khoản AWS, phục vụ cho việc điều tra sự cố (troubleshooting) và kiểm toán.
  * ...