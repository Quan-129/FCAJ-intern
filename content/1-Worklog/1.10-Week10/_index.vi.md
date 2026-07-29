---
title: "Báo cáo Tuần 10"
date: 2026-08-03
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Mục tiêu tuần 10:

* Nắm bắt và vận dụng 6 trụ cột của AWS Well-Architected Framework vào thiết kế hệ thống.
* Làm chủ các công cụ quản trị chi phí (FinOps) và thiết lập chiến lược Dự phòng thảm họa (Disaster Recovery - DR).

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                                                                                                                                                       | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Nghiên cứu AWS Well-Architected Framework: <br>&emsp; + Tìm hiểu 6 trụ cột: Vận hành xuất sắc, Bảo mật, Đáng tin cậy, Hiệu suất, Tối ưu chi phí, và Bền vững <br>&emsp; + Cách sử dụng AWS Well-Architected Tool              | 03/08/2026   | 03/08/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Khảo sát Tối ưu chi phí đám mây (Cloud FinOps): <br>&emsp; + Phân tích dữ liệu với AWS Cost Explorer và AWS Budgets <br>&emsp; + So sánh On-Demand, Reserved Instances, Savings Plans và Spot Instances                       | 04/08/2026   | 04/08/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Tìm hiểu Chiến lược Dự phòng thảm họa (Disaster Recovery): <br>&emsp; + Các khái niệm RTO (Recovery Time Objective) và RPO (Recovery Point Objective) <br>&emsp; + 4 chiến lược DR: Backup & Restore, Pilot Light, Warm Standby, Multi-Site | 05/08/2026   | 05/08/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - **Triển khai lab AWS Backup:** <br>&emsp; + Cấu hình Backup Plan tự động sao lưu định kỳ cho EC2 và RDS <br>&emsp; + Thiết lập vòng đời lưu trữ (Lifecycle) để tự động chuyển bản sao lưu sang vùng lưu trữ giá rẻ (Cold Storage) | 06/08/2026   | 06/08/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - **Thực hành Kiểm toán hệ thống:** <br>&emsp; + Sử dụng AWS Trusted Advisor để rà soát toàn bộ tài khoản AWS hiện tại <br>&emsp; + Thực hiện các biện pháp khắc phục (remediation) dựa trên các cảnh báo về bảo mật và chi phí rò rỉ | 07/08/2026   | 07/08/2026      | <https://cloudjourney.awsstudygroup.com/> |


### Kết quả đạt được tuần 10:

* Hình thành tư duy thiết kế hệ thống Cloud đạt chuẩn (Well-Architected):
  * Thuộc lòng 6 trụ cột thiết kế cốt lõi của AWS.
  * Biết cách tự đánh giá kiến trúc của một ứng dụng và xác định các rủi ro tiềm ẩn (high-risk issues) bằng Well-Architected Tool.
  * ...

* Quản trị và tối ưu hóa tài chính trên Cloud (FinOps):
  * Đọc hiểu báo cáo chi phí và thiết lập ngân sách cảnh báo tự động thông qua AWS Budgets.
  * Nắm được chiến lược lựa chọn mô hình tính giá (Pricing Models) phù hợp cho từng loại workload (dùng Spot cho batch processing, Savings Plan cho workload ổn định).
  * ...

* Đảm bảo tính liên tục của doanh nghiệp (Business Continuity):
  * Thiết lập thành công các kế hoạch sao lưu tập trung, tự động hóa bằng AWS Backup thay vì phải cấu hình thủ công từng dịch vụ.
  * Phân biệt và lựa chọn được chiến lược DR phù hợp với ngân sách cũng như yêu cầu RTO/RPO.
  * Khắc phục triệt để các lỗ hổng cấu hình tài khoản nhờ các khuyến nghị từ AWS Trusted Advisor.
  * ...