---
title: "Báo cáo Tuần 4"
date: 2026-06-22
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Mục tiêu tuần 4:

* Hiểu và thiết lập được hệ thống cân bằng tải (Elastic Load Balancing) và tự động mở rộng (Auto Scaling).
* Nắm bắt dịch vụ phân giải tên miền (Route 53) và mạng phân phối nội dung (CloudFront) để tối ưu hóa hiệu suất truyền tải.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                                                                                                                                                       | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Nghiên cứu dịch vụ Cân bằng tải (Elastic Load Balancing - ELB): <br>&emsp; + Phân biệt Application Load Balancer (ALB) và Network Load Balancer (NLB) <br>&emsp; + Khái niệm Listeners và Target Groups                       | 22/06/2026   | 22/06/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Tìm hiểu Auto Scaling Group (ASG): <br>&emsp; + Cách cấu hình Launch Templates <br>&emsp; + Các chiến lược mở rộng (Scaling Policies): Target tracking, Step scaling <br>&emsp; + Cơ chế kiểm tra sức khỏe (Health Checks)    | 23/06/2026   | 23/06/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - **Triển khai lab High Availability:** <br>&emsp; + Tạo Launch Template với Nginx/Apache <br>&emsp; + Thiết lập ASG kết hợp với Application Load Balancer (ALB) <br>&emsp; + Kiểm thử khả năng chịu lỗi khi tắt 1 instance     | 24/06/2026   | 24/06/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Khảo sát dịch vụ DNS Amazon Route 53: <br>&emsp; + Quản lý Hosted Zones và DNS Records (A, CNAME, Alias) <br>&emsp; + Các chính sách định tuyến (Routing Policies): Simple, Weighted, Failover                                | 25/06/2026   | 25/06/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - Tìm hiểu Amazon CloudFront (CDN): <br>&emsp; + Cơ chế caching và Edge Locations <br>&emsp; + **Thực hành:** Cấu hình CloudFront phân phối nội dung tĩnh từ S3 Bucket an toàn với Origin Access Control (OAC)                  | 26/06/2026   | 26/06/2026      | <https://cloudjourney.awsstudygroup.com/> |


### Kết quả đạt được tuần 4:

* Hiểu rõ khái niệm và tính năng của hệ thống tự động mở rộng và chịu lỗi:
  * Nắm được sự khác biệt giữa các loại Load Balancer (ALB, NLB).
  * Biết cách sử dụng Target Groups và Listeners để điều phối traffic.
  * Hiểu cơ chế hoạt động của Launch Templates và các chính sách mở rộng (Scaling Policies).
  * ...

* Triển khai thành công kiến trúc High Availability cơ bản:
  * Kết nối thành công Auto Scaling Group với Application Load Balancer.
  * Hệ thống tự động thêm mới hoặc loại bỏ EC2 instance dựa trên cấu hình Health Check.
  * ...

* Quản lý tên miền và tối ưu tốc độ phân phối nội dung:
  * Hiểu cách cấu hình các bản ghi DNS (Records) trong Route 53.
  * Phân biệt được Alias Record và CNAME Record trên AWS.
  * Tích hợp thành công CloudFront với S3 Bucket để làm CDN phân phối web tĩnh, giảm độ trễ (latency).
  * ...

* Linh hoạt kết hợp các dịch vụ mạng nâng cao để xây dựng một kiến trúc web an toàn, nhanh chóng và có khả năng chống chịu sự cố.
* ...