---
title: "Event 3"
date: 2026-07-13
weight: 3
chapter: false
pre: " <b> 4.3. </b> "
---

# Báo cáo Sự kiện: FCAJ — Agentic AI Build Week: Ngày Demo & Pitch

**Ngày:** 25/07/2026  
**Địa điểm:** Văn phòng AWS Việt Nam  
**Vai trò:** Người tham dự  

---

## Tóm tắt nội dung và các hoạt động chính

Đây là ngày khép lại FCAJ Agentic AI Build Week — một cuộc thi hackathon nơi các đội xây dựng các sản phẩm agentic AI trên nền tảng AWS và thuyết trình (pitch) trước toàn thể hội trường kín người. Format của sự kiện vô cùng thẳng thắn và thực tế: mỗi đội lên sân khấu trình bày bài toán đã chọn, demo trực tiếp những gì họ thực sự làm được trong tuần qua, sau đó bước vào phiên hỏi đáp (Q&A).

**Các hoạt động trọng tâm của sự kiện:**

*   **Khai mạc sự kiện:** Bắt đầu ngày demo tại văn phòng AWS với sự tham gia của khoảng 100 người đam mê công nghệ.
![Khai mạc ngày demo Agentic AI Build Week](/images/4-EventParticipated/event3-1.jpg)
*   **Trình bày của đội 3KA (The Hackathon Journey):** Cung cấp một góc nhìn chân thực về quá trình làm việc dưới áp lực thời gian, được kể theo mạch cảm xúc: nghi ngờ → nhập cuộc → tự hào.
*   **Trình bày của đội One Team (Đặt hàng bằng hội thoại có AI):** Trình bày giải pháp cho phép khách đặt hàng ngay trong ứng dụng chat họ đang dùng thay vì phải cài một ứng dụng riêng.
![One Team trình bày "Ordering Without Leaving the Chat"](/images/4-EventParticipated/event3-3.jpg)
*   **Trình bày của đội Plan V (Solution Architect native app):** Ra mắt một agent giải quyết nút thắt của các solution architect. Agent này có khả năng nhận yêu cầu (ngôn ngữ tự nhiên hoặc có cấu trúc), phác thảo kiến trúc, tạo sơ đồ draw.io, xuất mã hạ tầng (IaC) và ước tính chi phí.
*   **Trình bày của đội Signal Scout (Phát hiện sớm thay đổi chiến lược của doanh nghiệp):** Giới thiệu giải pháp theo dõi tín hiệu công khai nhằm nhận ra doanh nghiệp đang chuyển hướng trước khi có công bố chính thức. Giải pháp kết hợp AWS, LangFuse, TinyFish, Apify và hiển thị qua một dashboard tự phục vụ.
![Một đội trình bày canvas tạo và phân phối giá trị](/images/4-EventParticipated/event3-2.jpg)

---

## Kết quả và Giá trị đạt được

### 1. Bóc tách và hoạch định chi phí AWS thực tế
* Việc quan sát bảng phân tích chi phí của đội Signal Scout đã giúp tôi nhận ra tầm quan trọng của việc chia nhỏ chi phí theo từng dịch vụ cụ thể (token Bedrock, AgentCore runtime, WAF, DynamoDB, Lambda, v.v.).
* Học được cách ước tính ba mốc con số (tối thiểu, trung bình, tối đa hằng tháng) thay vì một con số duy nhất, từ đó dự báo chính xác được thành phần dịch vụ nào sẽ chiếm phần lớn hóa đơn hoặc dễ "gãy" khi lưu lượng truy cập tăng lên.

### 2. Mở rộng tư duy về kiến trúc "Agentic AI"
* Bài toán của Plan V đã thay đổi hoàn toàn cách tôi hình dung về việc sử dụng LLM trên đám mây. Thay vì chỉ dùng AI như một lệnh gọi API phân loại đơn thuần, "agentic" là khả năng kết nối toàn bộ một quy trình nghiệp vụ (từ đọc tài liệu đến xuất mã hạ tầng) thông qua các khối dựng sẵn như Bedrock AgentCore.

### 3. Tối ưu hóa điểm chạm người dùng (User Touchpoint)
* Cách tiếp cận của One Team đã mang lại một bài học có thể áp dụng ngay cho dự án hiện tại của nhóm tôi: thay vì xây dựng một giao diện hoàn toàn mới, hãy mang sản phẩm đến nơi người dùng vốn đã ở đó.
* Điều này củng cố định hướng phát triển dịch vụ kiểm duyệt nội dung của nhóm tôi theo hướng "API-first", tích hợp ngầm vào bên trong các nền tảng thay vì chỉ hoạt động như một trang demo độc lập.

### 4. Giá trị của sự chân thực trong quá trình phát triển
* Phần chia sẻ từ 3KA mang lại một góc nhìn cực kỳ đồng cảm về "khúc giữa" của quá trình xây dựng sản phẩm — giai đoạn mã nguồn chưa chạy được và ngập tràn sự không chắc chắn. Sự thẳng thắn này là một đối trọng cần thiết giữa những bản demo hào nhoáng, phản ánh đúng thực tế công việc của các kỹ sư.

> "Ngày demo Agentic AI không chỉ là nơi phô diễn kỹ năng lập trình hay kiến trúc đám mây, mà còn là một bài học thực chiến sâu sắc về tư duy phát triển sản phẩm: từ việc hoạch định chi phí chi tiết, thiết kế luồng agentic AI tự động hóa hoàn toàn, cho đến việc thấu hiểu điểm chạm thực sự của người dùng cuối."