---
title: "Báo cáo Tuần 11"
date: 2026-08-10
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Mục tiêu tuần 11:

* Nắm vững các mô hình kết nối mạng nâng cao trong môi trường Multi-account và Hybrid Cloud.
* Hiểu cách tối ưu hóa hiệu suất và độ trễ truyền tải dữ liệu giữa các hạ tầng khác nhau.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                                                                                                                                                       | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Nghiên cứu kết nối mạng nâng cao: <br>&emsp; + VPC Peering (Kết nối ngang hàng các VPC) <br>&emsp; + AWS Transit Gateway (Mô hình Hub-and-Spoke kết nối VPC tập trung) <br>&emsp; + VPC Endpoints (Interface & Gateway)         | 10/08/2026   | 10/08/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Khảo sát mô hình Hybrid Cloud: <br>&emsp; + VPN Site-to-Site (Kết nối qua Internet công cộng) <br>&emsp; + AWS Direct Connect (Kết nối riêng tư, chuyên dụng) <br>&emsp; + Ưu/nhược điểm so với hạ tầng truyền thống              | 11/08/2026   | 11/08/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - **Triển khai lab kết nối mạng:** <br>&emsp; + Thiết lập VPC Peering giữa 2 VPC trong cùng Region <br>&emsp; + Định tuyến (Route) để EC2 ở 2 VPC có thể giao tiếp với nhau bằng private IP                                       | 12/08/2026   | 12/08/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Tìm hiểu AWS PrivateLink: <br>&emsp; + Cơ chế chia sẻ dịch vụ an toàn giữa các VPC mà không cần public Internet <br>&emsp; + Ứng dụng PrivateLink trong kiến trúc Microservices phức tạp                                     | 13/08/2026   | 13/08/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - **Thực hành tối ưu hạ tầng:** <br>&emsp; + Cấu hình S3 Interface Endpoint để truy cập S3 từ private subnet mà không cần NAT Gateway <br>&emsp; + So sánh chi phí giữa NAT Gateway và VPC Endpoints cho lưu lượng lớn | 14/08/2026   | 14/08/2026      | <https://cloudjourney.awsstudygroup.com/> |


### Kết quả đạt được tuần 11:

* Thành thạo các kỹ thuật kết nối VPC nâng cao:
  * Hiểu rõ cách thức mở rộng hạ tầng từ một VPC đơn lẻ sang kiến trúc nhiều VPC kết nối chặt chẽ (Transit Gateway).
  * Biết cách sử dụng VPC Peering để kết nối dữ liệu giữa các môi trường cô lập một cách an toàn.
  * ...

* Hiểu sâu về kết nối Hybrid Cloud:
  * Nắm được các giải pháp kết nối trung tâm dữ liệu on-premises với AWS (VPN vs Direct Connect).
  * Biết cách chọn lựa giải pháp tối ưu cho doanh nghiệp dựa trên yêu cầu băng thông và độ trễ.
  * ...

* Tối ưu hóa hạ tầng mạng bằng VPC Endpoints:
  * Tận dụng tối đa PrivateLink để các dịch vụ AWS có thể "nói chuyện" với nhau mà không cần đi qua đường truyền công cộng (Public Internet).
  * Giảm đáng kể chi phí vận hành (Data transfer cost) và cải thiện bảo mật bằng cách dùng Gateway/Interface Endpoints thay vì NAT Gateway cho các dịch vụ AWS phổ biến (như S3, DynamoDB).
  * ...