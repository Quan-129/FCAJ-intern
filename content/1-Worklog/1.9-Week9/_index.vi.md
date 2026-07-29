---
title: "Báo cáo Tuần 9"
date: 2026-07-27
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu tuần 9:

* Xây dựng tư duy về Data Lake và làm quen với các công cụ phân tích dữ liệu tự động (Serverless Analytics) trên AWS.
* Khám phá và tích hợp các dịch vụ Trí tuệ nhân tạo (AI) và Học máy (ML) quản lý sẵn vào ứng dụng thực tế.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                                                                                                                                                       | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Nghiên cứu kiến trúc Data Lake và AWS Glue: <br>&emsp; + Sự khác biệt giữa Data Lake (S3) và Data Warehouse (Redshift) <br>&emsp; + Dịch vụ tích hợp dữ liệu AWS Glue (ETL) <br>&emsp; + Cơ chế hoạt động của Glue Data Catalog | 27/07/2026   | 27/07/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Khảo sát Amazon Athena: <br>&emsp; + Khái niệm truy vấn dữ liệu Serverless <br>&emsp; + **Thực hành:** Sử dụng Athena để viết các câu lệnh SQL truy vấn trực tiếp file log (CSV/JSON) lưu trữ trong S3 Bucket                 | 28/07/2026   | 28/07/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Tìm hiểu hệ sinh thái AWS Managed AI Services: <br>&emsp; + Amazon Rekognition (Phân tích hình ảnh/video) <br>&emsp; + Amazon Comprehend (Phân tích ngôn ngữ tự nhiên - NLP) <br>&emsp; + Amazon Textract (Trích xuất văn bản)| 29/07/2026   | 29/07/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Khảo sát nền tảng Machine Learning - Amazon SageMaker: <br>&emsp; + Tổng quan về vòng đời của một dự án ML (Build, Train, Deploy) <br>&emsp; + Tìm hiểu SageMaker Studio và các tính năng hỗ trợ nhà khoa học dữ liệu         | 30/07/2026   | 30/07/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - **Triển khai lab AI Integration:** <br>&emsp; + Viết một hàm Lambda được kích hoạt khi người dùng upload ảnh lên S3 <br>&emsp; + Hàm Lambda gọi API của Rekognition để nhận diện nhãn (labels) trên ảnh <br>&emsp; + Lưu kết quả vào DynamoDB | 31/07/2026   | 31/07/2026      | <https://cloudjourney.awsstudygroup.com/> |


### Kết quả đạt được tuần 9:

* Nắm vững khái niệm về lưu trữ và xử lý dữ liệu lớn (Big Data) trên Cloud:
  * Hiểu nguyên lý xây dựng Data Lake tiết kiệm chi phí với Amazon S3.
  * Có khả năng dùng AWS Glue để tự động thu thập metadata và tạo danh mục dữ liệu (Data Catalog).
  * Truy vấn thành công dữ liệu thô (raw data) bằng SQL thông qua Amazon Athena mà không cần thiết lập máy chủ database.
  * ...

* Bước đầu làm chủ việc tích hợp AI vào hệ thống:
  * Nhận biết được các dịch vụ AI quản lý sẵn (Managed AI) của AWS để giải quyết bài toán thị giác máy tính và xử lý ngôn ngữ tự nhiên.
  * Biết cách dùng mã nguồn (SDK/CLI) để gọi API các dịch vụ như Rekognition, Comprehend để phân tích dữ liệu một cách nhanh chóng.
  * ...

* Hiểu quy trình huấn luyện mô hình học máy:
  * Nắm được bức tranh tổng thể về vòng đời Machine Learning trên nền tảng AWS thông qua Amazon SageMaker.
  * Xây dựng thành công một kiến trúc serverless tự động nhận diện và phân loại hình ảnh.
  * ...