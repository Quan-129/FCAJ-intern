---
title: "Sự kiện 1"
date: 2026-06-06
weight: 1
chapter: false
pre: " <b> 4.1. </b> "
---

# Báo cáo Sự kiện: Hội thảo chia sẻ công nghệ - Cloud, DevOps & Ứng dụng AI/ML

**Ngày:** 06/06/2026  
**Địa điểm:** Tầng 26, Bitexco Tower, 02 Hải Triều, Phường Bến Nghé, TP.HCM  
**Vai trò:** Người tham dự  

---

## Tóm tắt nội dung và các hoạt động chính

Sự kiện là một buổi chia sẻ kỹ thuật chuyên sâu, quy tụ nhiều chuyên gia và kỹ sư trong các lĩnh vực System/DevOps, An ninh mạng và Trí tuệ nhân tạo (AI). Buổi gặp mặt bao gồm 3 phần trình bày chính:

1. **Phần 1 - Lộ trình System Admin & DevOps (Diễn giả: Trần Trung Vinh):**
   Chia sẻ thực tế về con đường phát triển sự nghiệp từ IT Helpdesk lên System Admin. Phân tích các tình huống xử lý sự cố hệ thống nghiêm trọng (ví dụ: hệ thống ngừng hoạt động do quá tải I/O ổ cứng). Đề xuất các giải pháp di chuyển hạ tầng lên Cloud và tối ưu hóa hệ thống bằng công nghệ Container (Docker).
2. **Phần 2 - Ứng dụng Machine Learning trong An ninh mạng (Diễn giả: Dai):**
   Trình bày giải pháp Tường lửa ứng dụng web (WAF) sử dụng Trí tuệ nhân tạo trên AWS. Phân tích những hạn chế của các WAF truyền thống (dựa trên bộ quy tắc tĩnh, dễ bỏ sót lỗ hổng) và đề xuất hệ thống sử dụng thuật toán Machine Learning (LightGBM) để thu thập log, tiền xử lý dữ liệu và phát hiện tấn công (SQL Injection, XSS) với độ chính xác cao.
3. **Phần 3 - Kiến trúc Game nhiều người chơi & Hệ thống RAG:**
   Khám phá cách xây dựng backend bằng AWS (API Gateway, Lambda, DynamoDB). Đánh giá và so sánh chuyên sâu giữa các giao thức mạng (HTTP Polling, WebSockets, UDP). Phần cuối tập trung giới thiệu kỹ thuật RAG (Retrieval-Augmented Generation) để tự động hóa phân tích tài liệu và truy xuất thông tin thông minh.

---

## Kết quả và Giá trị đạt được

### 1. Tích lũy kỹ năng kỹ thuật
* **Hạ tầng & Kiến trúc Cloud:** Hiểu rõ hơn về cách thiết kế hệ thống quy mô lớn trên AWS, tầm quan trọng của việc đóng gói ứng dụng (Docker) để giải quyết các lỗi liên quan đến môi trường triển khai.
* **Machine Learning thực chiến:** Nắm bắt bức tranh tổng thể về việc triển khai mô hình AI vào môi trường thực tế (thu thập dữ liệu -> tiền xử lý -> huấn luyện -> triển khai). Tư duy sử dụng AI để phát hiện bất thường rất hữu ích cho việc nghiên cứu các mô hình dự báo xu hướng.
* **Giao thức mạng:** Nắm vững sự khác biệt và ngữ cảnh sử dụng cụ thể của TCP, UDP và WebSockets trong việc thiết kế các hệ thống xử lý dữ liệu thời gian thực.

### 2. Giá trị ứng dụng cho dự án thực tế
* Kiến thức về Serverless Architecture (AWS Lambda) và luồng hoạt động của hệ thống RAG có giá trị tham khảo lớn cho kiến trúc backend của ứng dụng **Antygravity**. Việc định tuyến giao tiếp giữa Client và AI Agent có thể được tối ưu hóa dựa trên các mô hình đã học.
* Áp dụng tư duy thiết kế bảo mật từ hệ thống WAF để kiểm soát tốt hơn các luồng dữ liệu đầu vào, duy trì các nguyên tắc Clean Code khi xây dựng các API endpoint.

### 3. Kỹ năng mềm & Phát triển bản thân
* **Tư duy xử lý sự cố (Troubleshooting):** Học hỏi cách các kỹ sư cấp cao cô lập sự cố khi đối mặt với hệ thống lớn (từ kiểm tra CPU, RAM, Disk I/O đến xem Application Logs).
* **Kỹ năng tổng hợp thông tin:** Rèn luyện khả năng tập trung, lắng nghe và lọc các thuật ngữ kỹ thuật phức tạp từ diễn giả, tạo nền tảng vững chắc cho các buổi demo và thuyết trình phần mềm tại trường đại học sắp tới.

> Nhìn chung, sự kiện không chỉ cung cấp kho tàng kiến thức kỹ thuật mà còn giúp tôi hình dung rõ cách các công nghệ đang học như AWS, AI và DevOps kết hợp với nhau để giải quyết các vấn đề phức tạp trong thực tế.