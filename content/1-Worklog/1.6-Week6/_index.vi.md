---
title: "Báo cáo Tuần 6"
date: 2026-07-06
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Mục tiêu tuần 6:

* Hiểu và triển khai các ứng dụng được đóng gói (Containerized Applications) bằng hệ sinh thái AWS (ECR, ECS và Fargate).
* Nắm bắt tư duy tự động hóa cơ sở hạ tầng (Infrastructure as Code - IaC) thông qua AWS CloudFormation.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                                                                                                                                                       | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Nghiên cứu Container và Amazon ECR: <br>&emsp; + Kiến thức nền tảng về Docker và Container <br>&emsp; + Giới thiệu Amazon Elastic Container Registry (ECR) <br>&emsp; + Quản lý vòng đời của Container Images                 | 06/07/2026   | 06/07/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Khảo sát Amazon ECS & AWS Fargate: <br>&emsp; + Phân biệt mô hình chạy EC2 và Fargate (Serverless compute cho containers) <br>&emsp; + Các khái niệm cốt lõi: Clusters, Task Definitions và Services                          | 07/07/2026   | 07/07/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - **Triển khai lab Container:** <br>&emsp; + Build một Docker image cho ứng dụng web cơ bản <br>&emsp; + Xác thực và Push image lên kho lưu trữ ECR <br>&emsp; + Triển khai ứng dụng chạy trên ECS sử dụng Fargate              | 08/07/2026   | 08/07/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Tìm hiểu tư duy IaC và AWS CloudFormation: <br>&emsp; + Khái niệm Infrastructure as Code <br>&emsp; + Cấu trúc của một CloudFormation Template (YAML/JSON) <br>&emsp; + Tìm hiểu các khối: Resources, Parameters, Outputs     | 09/07/2026   | 09/07/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - **Thực hành Tự động hóa hạ tầng (IaC):** <br>&emsp; + Viết template YAML để tự động tạo EC2 Instance và Security Group <br>&emsp; + Triển khai (Deploy) và cập nhật (Update) Stack qua giao diện Console/CLI <br>&emsp; + Xóa Stack để dọn dẹp | 10/07/2026   | 10/07/2026      | <https://cloudjourney.awsstudygroup.com/> |


### Kết quả đạt được tuần 6:

* Làm chủ quy trình đóng gói và triển khai ứng dụng bằng Container trên AWS:
  * Hiểu cách xây dựng Docker image và lưu trữ an toàn trên Amazon ECR.
  * Cấu hình thành công Task Definitions để quy định tài nguyên (CPU, RAM) cho container.
  * Triển khai dịch vụ (Service) trên ECS sử dụng Fargate, loại bỏ hoàn toàn việc phải quản lý hệ điều hành của máy chủ.
  * ...

* Thay đổi tư duy triển khai hạ tầng từ thủ công (ClickOps) sang tự động hóa (IaC):
  * Hiểu cách khai báo cơ sở hạ tầng dưới dạng mã nguồn (CloudFormation Templates).
  * Nắm được quy trình tạo, cập nhật và xóa toàn bộ môi trường (Stack) chỉ bằng một thao tác thống nhất.
  * ...

* Tối ưu hóa được quy trình dọn dẹp tài nguyên (Resource cleanup) thông qua việc xóa Stack của CloudFormation, giúp kiểm soát tốt chi phí học tập.
* ...