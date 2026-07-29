---
title: "Báo cáo Tuần 3"
date: 2026-06-15
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Mục tiêu tuần 3:

* Hiểu kiến trúc và có khả năng thiết lập hạ tầng mạng ảo độc lập (Amazon VPC).
* Nắm bắt và triển khai thực tế các dịch vụ cơ sở dữ liệu trên AWS (Amazon RDS và DynamoDB).

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                                                                                                                                                       | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Nghiên cứu Hạ tầng mạng ảo Amazon VPC: <br>&emsp; + Phân tích các thành phần: Subnets, Route Tables <br>&emsp; + Vai trò của Internet Gateway (IGW) và NAT Gateway <br>&emsp; + Phân biệt Security Groups và NACL             | 15/06/2026   | 15/06/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - **Triển khai thực tế VPC:** <br>&emsp; + Khởi tạo một Custom VPC <br>&emsp; + Thiết lập Public Subnet và Private Subnet <br>&emsp; + Cấu hình Route Table để EC2 có thể truy cập Internet an toàn                             | 16/06/2026   | 16/06/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Khảo sát dịch vụ Cơ sở dữ liệu quan hệ (Amazon RDS): <br>&emsp; + Các engine hỗ trợ (MySQL, PostgreSQL,...) <br>&emsp; + Kiến trúc dự phòng Multi-AZ <br>&emsp; + Cơ chế sao chép đọc (Read Replicas)                         | 17/06/2026   | 17/06/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - **Thực hành vận hành RDS:** <br>&emsp; + Khởi tạo Database Instance (MySQL/PostgreSQL) <br>&emsp; + Cấu hình Security Group cho phép kết nối từ EC2 <br>&emsp; + Dùng client truy cập và thao tác dữ liệu mẫu                 | 18/06/2026   | 18/06/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - Tìm hiểu dịch vụ CSDL phi quan hệ Amazon DynamoDB: <br>&emsp; + Khái niệm NoSQL, Tables, Items và Attributes <br>&emsp; + Tầm quan trọng của Partition Key và Sort Key <br>&emsp; + **Thực hành:** Tạo bảng và truy vấn data  | 19/06/2026   | 19/06/2026      | <https://cloudjourney.awsstudygroup.com/> |


### Kết quả đạt được tuần 3:

* Nắm vững kiến trúc mạng và luồng giao tiếp dữ liệu bên trong AWS thông qua VPC:
  * Phân tách thành công môi trường mạng nội bộ bằng cách sử dụng Public và Private Subnet.
  * Cấu hình chính xác Internet Gateway và Route Table.
  * Hiểu và áp dụng đúng các lớp bảo mật mạng (Security Groups và Network ACLs).
  * ...

* Hiểu cấu trúc và vận hành trơn tru dịch vụ cơ sở dữ liệu Amazon RDS:
  * Khởi tạo thành công Database Instance theo chuẩn.
  * Hiểu rõ cơ chế Multi-AZ để đảm bảo tính sẵn sàng cao (High Availability).
  * Kết nối thành công ứng dụng trên máy chủ ảo EC2 tới RDS nội bộ.
  * ...

* Bước đầu làm quen với hệ quản trị CSDL NoSQL thông qua Amazon DynamoDB:
  * Hiểu cách tổ chức dữ liệu phi cấu trúc.
  * Khởi tạo bảng và thao tác dữ liệu cơ bản từ AWS Console.
  * ...

* Tự tin thiết lập một môi trường kiến trúc 2 lớp cơ bản (Web Server trên EC2 nằm ở Public Subnet, Database nằm ở Private Subnet).
* ...