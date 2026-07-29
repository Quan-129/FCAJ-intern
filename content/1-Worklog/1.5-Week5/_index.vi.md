---
title: "Báo cáo Tuần 5"
date: 2026-06-29
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu tuần 5:

* Nắm bắt tư duy thiết kế và vận hành kiến trúc Không máy chủ (Serverless Architecture).
* Hiểu cách kết nối và phân tách các thành phần trong hệ thống (Decoupling) bằng dịch vụ hàng đợi và thông báo.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                                                                                                                                                       | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Nghiên cứu dịch vụ AWS Lambda: <br>&emsp; + Khái niệm Serverless computing <br>&emsp; + Cấu hình hàm (Functions), Trigger và Destination <br>&emsp; + Tìm hiểu Execution Role và cơ chế tính phí                              | 29/06/2026   | 29/06/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Khảo sát Amazon API Gateway: <br>&emsp; + Phân biệt REST API và HTTP API <br>&emsp; + Các phương thức bảo mật API (IAM, API Keys, Cognito) <br>&emsp; + Cơ chế throttling và caching                                          | 30/06/2026   | 30/06/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - **Triển khai lab Serverless:** <br>&emsp; + Viết hàm Lambda bằng Python để xử lý dữ liệu <br>&emsp; + Dùng API Gateway tạo endpoint gọi hàm Lambda <br>&emsp; + Tích hợp ghi dữ liệu từ Lambda vào bảng DynamoDB              | 01/07/2026   | 01/07/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Tìm hiểu dịch vụ Tích hợp ứng dụng: <br>&emsp; + Hàng đợi Amazon SQS (Standard vs FIFO queues, Dead-letter queues) <br>&emsp; + Dịch vụ thông báo Amazon SNS (Topics, Subscriptions, Fanout architecture)                     | 02/07/2026   | 02/07/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - **Thực hành kiến trúc hướng sự kiện (Event-driven):** <br>&emsp; + Thiết lập S3 Event Notification khi có file upload <br>&emsp; + Dùng Lambda đọc sự kiện và đẩy thông báo qua SNS <br>&emsp; + Đăng ký nhận email qua SNS   | 03/07/2026   | 03/07/2026      | <https://cloudjourney.awsstudygroup.com/> |


### Kết quả đạt được tuần 5:

* Làm chủ tư duy lập trình và triển khai kiến trúc Serverless:
  * Khởi tạo và triển khai thành công mã nguồn Python trực tiếp trên nền tảng AWS Lambda mà không cần quản lý máy chủ.
  * Hiểu rõ cơ chế phân quyền thực thi (Execution Role) để Lambda truy cập an toàn các dịch vụ khác.
  * ...

* Có khả năng xây dựng và công bố API độc lập:
  * Sử dụng API Gateway để tạo các endpoint RESTful kết nối luồng dữ liệu từ người dùng đến backend (Lambda).
  * Biết cách kiểm soát lưu lượng truy cập (throttling) để bảo vệ hệ thống.
  * ...

* Hiểu và vận dụng kiến trúc hệ thống phân tán (Decoupled Microservices):
  * Cấu hình thành công hàng đợi SQS để lưu trữ tạm thời các tác vụ chưa xử lý.
  * Sử dụng SNS để phát sóng thông báo (Fanout) đến nhiều dịch vụ hoặc email người dùng.
  * ...

* Xây dựng thành công chuỗi tự động hóa cơ bản (Ví dụ: Upload file lên S3 -> Kích hoạt Lambda -> Gửi thông báo SNS).
* ...