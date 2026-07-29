---
title: "Báo cáo Tuần 2"
date: 2026-06-08
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---

### Mục tiêu tuần 2:

* Nắm vững cơ chế quản lý danh tính, phân quyền và bảo mật tài khoản thông qua IAM.
* Hiểu và triển khai thực tế dịch vụ lưu trữ đối tượng (Amazon S3) cùng các phương thức kiểm soát chi phí cơ bản.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                                                                                                                                                       | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Nghiên cứu hệ thống Quản lý danh tính và Truy cập (IAM): <br>&emsp; + Phân tích các khái niệm: Users, Groups, Roles <br>&emsp; + Cấu trúc của Policies <br>&emsp; + Nguyên tắc quyền hạn tối thiểu (Least Privilege)          | 08/06/2026   | 08/06/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - **Triển khai thực tế IAM:** <br>&emsp; + Tạo lập người dùng (User) và nhóm (Group) <br>&emsp; + Gán quyền truy cập thông qua Policy <br>&emsp; + Kích hoạt bảo mật 2 lớp (MFA) cho tài khoản Root                             | 09/06/2026   | 09/06/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Khảo sát dịch vụ lưu trữ đối tượng Amazon S3: <br>&emsp; + Cơ chế hoạt động của Bucket và Object <br>&emsp; + Các phân lớp lưu trữ (Storage Classes) <br>&emsp; + Tính năng quản lý phiên bản (Versioning)                    | 10/06/2026   | 10/06/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - **Thực hành vận hành S3:** <br>&emsp; + Khởi tạo không gian lưu trữ (Bucket) <br>&emsp; + Thiết lập quyền truy cập cho tài nguyên (Bucket Policy) <br>&emsp; + Cấu hình lưu trữ trang web tĩnh (Static Website Hosting)       | 11/06/2026   | 11/06/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - Tìm hiểu cơ chế giám sát và quản trị chi phí: <br>&emsp; + Phân tích dịch vụ Amazon CloudWatch <br>&emsp; + Kiểm soát ngân sách với AWS Cost Explorer <br>&emsp; + Thiết lập cảnh báo chi phí (AWS Billing Alarm)           | 12/06/2026   | 12/06/2026      | <https://cloudjourney.awsstudygroup.com/> |


### Kết quả đạt được tuần 2:

* Nắm vững các nguyên tắc cốt lõi về bảo mật không gian Cloud thông qua dịch vụ IAM:
  * Thiết lập bảo mật đa lớp (MFA)
  * Áp dụng thành thạo nguyên tắc quyền hạn tối thiểu (Least Privilege)
  * Quản trị vòng đời của User, Group và Role
  * ...

* Hiểu và vận hành trơn tru không gian lưu trữ Amazon S3.

* Triển khai thành công các tác vụ thực tế trên S3 bao gồm:
  * Khởi tạo và tùy chỉnh thông số Bucket
  * Tải lên, truy xuất và quản lý vòng đời của Object
  * Tích hợp Bucket thành nơi lưu trữ và phân phối mã nguồn web tĩnh
  * ...

* Nắm bắt quy trình kiểm soát chi phí hoạt động trên AWS:
  * Đọc hiểu bảng điều khiển Billing
  * Kích hoạt thành công các ngưỡng cảnh báo khi hệ thống vượt ngân sách (Billing Alarm)
  * ...

* Duy trì thao tác mượt mà trên cả giao diện Web Console và CLI khi cấu hình quyền hạn và khởi tạo không gian lưu trữ.
* ...