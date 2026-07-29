---
title: "Báo cáo Tuần 1"
date: 2026-06-01
weight: 1
chapter: false
pre: " <b> 1.1. </b> "
---

### Mục tiêu tuần 1:

* Giao lưu, hội nhập cùng đội ngũ nhân sự tại First Cloud AI Journey.
* Nắm bắt nền tảng AWS, thao tác thành thạo trên cả giao diện web (Console) và công cụ dòng lệnh (CLI).

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                                                                                                                                                           | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Gặp gỡ và kết nối với mạng lưới thành viên FCAJ <br> - Tìm hiểu và nắm rõ các quy chế, văn hóa làm việc của công ty                                                                                                               | 01/06/2026   | 01/06/2026      |                                           |
| 3   | - Nghiên cứu tổng quan hệ sinh thái AWS và các nhóm cốt lõi: <br>&emsp; + Năng lực tính toán (Compute) <br>&emsp; + Không gian lưu trữ (Storage) <br>&emsp; + Hạ tầng mạng (Networking) <br>&emsp; + Quản trị cơ sở dữ liệu (Database) <br>&emsp; + ... | 02/06/2026   | 02/06/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Đăng ký tài khoản AWS bậc miễn phí (Free Tier) <br> - Phân tích giao diện AWS Console và công cụ AWS CLI <br> - **Triển khai lab:** <br>&emsp; + Thiết lập account AWS <br>&emsp; + Cài đặt & khai báo cấu hình cho CLI <br> &emsp; + Thao tác các lệnh CLI nền tảng | 03/06/2026   | 03/06/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Khảo sát dịch vụ máy chủ ảo EC2: <br>&emsp; + Các dòng cấu hình (Instance types) <br>&emsp; + Ảnh hệ điều hành (AMI) <br>&emsp; + Phân vùng ổ cứng (EBS) <br>&emsp; + ... <br> - Tìm hiểu các phương thức kết nối SSH an toàn <br> - Đọc hiểu cơ chế cấp phát IP tĩnh (Elastic IP)  | 04/06/2026   | 05/06/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - **Triển khai thực tế:** <br>&emsp; + Khởi tạo một máy chủ EC2 <br>&emsp; + Truy cập server qua giao thức SSH <br>&emsp; + Đính kèm (mount) bộ nhớ EBS vào instance                                                                             | 05/06/2026   | 05/06/2026      | <https://cloudjourney.awsstudygroup.com/> |


### Kết quả đạt được tuần 1:

* Nắm vững khái niệm về hệ sinh thái Cloud AWS và nhận diện được các trụ cột dịch vụ: 
  * Năng lực tính toán (Compute)
  * Không gian lưu trữ (Storage)
  * Hạ tầng mạng (Networking) 
  * Hệ quản trị CSDL (Database)
  * ...

* Hoàn tất đăng ký và thiết lập an toàn cho tài khoản AWS Free Tier.

* Thành thạo điều hướng trên AWS Management Console, có thể dễ dàng tra cứu và vận hành dịch vụ trực tiếp trên trình duyệt.

* Cài đặt thành công công cụ dòng lệnh AWS CLI lên thiết bị cá nhân với các thông số:
  * Khóa định danh (Access Key)
  * Khóa bí mật (Secret Key)
  * Khu vực triển khai mặc định (Default Region)
  * ...

* Vận dụng AWS CLI để thực thi các tác vụ quản trị cốt lõi như:

  * Truy xuất dữ liệu tài khoản và cấu hình hiện tại
  * Liệt kê danh sách các Region khả dụng
  * Truy vấn thông số của dịch vụ EC2
  * Khởi tạo và kiểm soát cặp khóa bảo mật (Key pair)
  * Giám sát trạng thái hoạt động của các tài nguyên
  * ...

* Linh hoạt chuyển đổi, kết hợp giữa nền tảng Web Console và CLI trong việc điều khiển, cấp phát tài nguyên song song.
* ...