---
title: "Worklog Tuần 10"
date: 2026-06-19
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Mục tiêu tuần 10:

* Ôn tập và củng cố lại các dịch vụ hỗ trợ xây dựng ứng dụng cloud trên AWS.
* Củng cố kiến thức về kiến trúc **web application** trên AWS.
* Tìm hiểu luồng hoạt động giữa **User**, **Route 53**, **CloudFront**, **AWS WAF**, **Application Load Balancer**, **EC2**, **S3** và **RDS**.
* Ôn tập các thành phần mạng như **VPC**, **Subnet**, **Route Table**, **Internet Gateway**, **NAT Gateway** và **Security Group**.
* Rèn luyện kỹ năng phân tích, nhận xét và chỉnh sửa sơ đồ kiến trúc AWS theo đúng logic triển khai thực tế.
* Tìm hiểu các phương án bảo mật cho hệ thống nội bộ như **VPN**, **IP Allowlist**, **HTTPS**, **Authentication**, **API Key** và **HMAC**.
* Phân tích cách cân bằng giữa bảo mật, chi phí, độ phức tạp và tính phù hợp với quy mô project.
* Chuẩn bị ghi chú báo cáo tuần, tổng hợp kiến thức kiến trúc và hoàn thiện nội dung nhận xét sơ đồ AWS.

### Các nhiệm vụ sẽ được thực hiện trong tuần này:

| Ngày | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| :--- | :--- | :--- | :--- | :--- |
| 1    | - Ôn tập kiến trúc web application trên AWS<br>- Tìm hiểu luồng truy cập User → Route 53 → CloudFront/WAF → ALB → EC2<br>- Ghi chú vai trò của từng thành phần trong kiến trúc<br>- Phân tích sự khác nhau giữa luồng truy cập frontend, backend và static content<br>- Xác định vị trí phù hợp của CloudFront, WAF, ALB, EC2, S3 và RDS trong sơ đồ | 19/06/2026 | 19/06/2026 | https://aws.amazon.com/architecture/ |
| 2    | - Ôn tập VPC, Public Subnet, Private Subnet, Route Table, Internet Gateway và NAT Gateway<br>- Phân biệt tài nguyên nằm trong Region, VPC, Subnet và tài nguyên global<br>- Ghi chú cách đặt service đúng vị trí trong sơ đồ kiến trúc<br>- Phân tích vai trò của public subnet và private subnet trong bảo mật hệ thống<br>- Ghi chú các lỗi thường gặp khi đặt sai service trong kiến trúc AWS | 22/06/2026 | 22/06/2026 | https://docs.aws.amazon.com/vpc/ |
| 3    | - Tìm hiểu vai trò của ALB, CloudFront, WAF và S3 trong hệ thống web<br>- Phân biệt luồng CloudFront đến S3 và luồng CloudFront/WAF đến ALB<br>- Ghi chú các lỗi thường gặp khi vẽ sơ đồ kiến trúc AWS<br>- Phân tích cách CloudFront hỗ trợ phân phối nội dung tĩnh và giảm tải cho origin<br>- Ghi chú cách WAF được gắn với CloudFront hoặc ALB thay vì vẽ như một node mạng độc lập | 23/06/2026 | 23/06/2026 | https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/ |
| 4    | - Tìm hiểu các phương án bảo mật dashboard nội bộ<br>- So sánh WAF, VPN, IP Allowlist, HTTPS, Authentication, API Key và HMAC<br>- Ghi chú cách lựa chọn phương án bảo mật phù hợp với chi phí và nhu cầu project<br>- Phân tích trường hợp khi không dùng WAF thì cần có lớp bảo mật thay thế<br>- Đánh giá phương án bảo mật phù hợp cho dashboard nội bộ hoặc hệ thống quy mô nhỏ | 24/06/2026 | 24/06/2026 | https://docs.aws.amazon.com/waf/ |
| 5    | - Tổng hợp kiến thức kiến trúc AWS tuần 10<br>- Nhận xét và chỉnh sửa sơ đồ kiến trúc theo đúng logic<br>- Hoàn thiện ghi chú báo cáo tuần 10<br>- Dọn dẹp tài nguyên hoặc tài liệu lab không còn sử dụng<br>- Chuẩn bị checklist nhận xét sơ đồ AWS gồm flow truy cập, vị trí service, subnet, security group, database và cost optimization | 25/06/2026 | 25/06/2026 | https://aws.amazon.com/blogs/architecture/ |

### Kết quả đạt được tuần 10:

**Tổng quát:**

Trong tuần 10, tôi đã tập trung ôn tập và củng cố kiến thức về kiến trúc ứng dụng web trên AWS. Nội dung tuần này giúp tôi hiểu rõ hơn cách các dịch vụ như Route 53, CloudFront, WAF, ALB, EC2, S3 và RDS phối hợp với nhau để tạo thành một hệ thống web application hoàn chỉnh.

Ngoài việc ôn tập lý thuyết, tôi còn rèn luyện kỹ năng nhận xét sơ đồ kiến trúc AWS, xác định lỗi thiết kế, chỉnh sửa luồng truy cập và phân tích các phương án bảo mật phù hợp cho dashboard nội bộ. Qua đó, tôi có khả năng đánh giá kiến trúc theo các yếu tố như bảo mật, chi phí, tính dễ triển khai và khả năng mở rộng.

**Lý thuyết đã học:**

* Hiểu rõ hơn luồng truy cập cơ bản của một web application trên AWS:

  * User.
  * Route 53.
  * CloudFront.
  * AWS WAF.
  * Application Load Balancer.
  * EC2 Backend.
  * RDS Database.
* Hiểu được **CloudFront** có thể dùng để phân phối nội dung tĩnh từ Amazon S3 hoặc chuyển tiếp request đến backend thông qua ALB.
* Hiểu được **AWS WAF** không nên vẽ như một node mạng trung gian độc lập, mà thường được gắn với CloudFront hoặc Application Load Balancer.
* Nắm được vai trò của **Application Load Balancer** trong việc phân phối traffic đến các EC2 backend.
* Hiểu được vai trò của **Amazon S3** trong lưu trữ static content hoặc hosting website tĩnh.
* Hiểu được vai trò của **Amazon RDS** trong lưu trữ dữ liệu cho ứng dụng.
* Ôn tập lại các thành phần mạng quan trọng trong AWS:

  * VPC.
  * Public Subnet.
  * Private Subnet.
  * Route Table.
  * Internet Gateway.
  * NAT Gateway.
  * Security Group.
* Phân biệt được tài nguyên nằm trong VPC, tài nguyên nằm ngoài VPC và tài nguyên global.
* Hiểu được **Internet Gateway** dùng cho kết nối Internet của tài nguyên trong public subnet.
* Hiểu được **NAT Gateway** chủ yếu dùng cho outbound traffic từ private subnet ra Internet.
* Hiểu được vai trò của **Security Group** trong việc kiểm soát traffic vào/ra tài nguyên như EC2, ALB hoặc RDS.
* Nắm được một số lỗi thường gặp khi vẽ sơ đồ kiến trúc AWS:

  * Vẽ IAM như một luồng xử lý dữ liệu chính.
  * Đặt WAF sai vị trí.
  * Nhầm lẫn giữa Internet Gateway và Application Load Balancer.
  * Thiếu Security Group hoặc Route Table.
  * Không thể hiện rõ public subnet và private subnet.
  * Đặt database ở vị trí có thể truy cập trực tiếp từ Internet.
* Hiểu được các phương án bảo mật dashboard nội bộ:

  * VPN.
  * IP Allowlist.
  * HTTPS.
  * Authentication.
  * API Key.
  * HMAC.
* Biết rằng nếu không dùng WAF thì hệ thống vẫn cần có lớp bảo mật thay thế phù hợp.
* Ghi nhận một số best practices:

  * Không public backend hoặc database trực tiếp ra Internet.
  * Đặt ALB trong public subnet và backend/database trong private subnet.
  * Dùng HTTPS cho luồng truy cập người dùng.
  * Kết hợp Authentication với API Key hoặc HMAC nếu cần bảo vệ API nội bộ.
  * Dùng IP Allowlist hoặc VPN cho dashboard nội bộ.
  * Theo dõi chi phí khi dùng NAT Gateway, ALB, CloudFront, WAF và RDS.

**Thực hành và tổng hợp:**

* Ôn tập lại kiến trúc web application trên AWS và vai trò của từng service trong hệ thống.
* Phân tích luồng truy cập chính:

  * User → Route 53 → CloudFront/WAF → ALB → EC2 → RDS.
* Phân tích luồng phân phối nội dung tĩnh:

  * User → Route 53 → CloudFront → S3.
* Thực hành tư duy nhận xét sơ đồ kiến trúc AWS theo các tiêu chí:

  * Luồng truy cập có đúng logic hay không.
  * Service có đặt đúng vị trí hay không.
  * Public subnet và private subnet có rõ ràng hay không.
  * Database có được bảo vệ trong private subnet hay không.
  * Security Group và Route Table có được thể hiện hợp lý hay không.
  * Có lớp bảo mật phù hợp cho frontend, backend và dashboard nội bộ hay không.
* Tổng hợp checklist kiểm tra sơ đồ kiến trúc:

  * Kiểm tra điểm vào hệ thống.
  * Kiểm tra vị trí CloudFront, WAF và ALB.
  * Kiểm tra public/private subnet.
  * Kiểm tra luồng từ backend đến database.
  * Kiểm tra các lớp bảo mật.
  * Kiểm tra các dịch vụ có thể phát sinh chi phí cao.
* Phân tích phương án bảo mật dashboard nội bộ:

  * Nếu cần bảo mật mạnh và truy cập nội bộ: dùng VPN.
  * Nếu project nhỏ và người truy cập cố định: dùng IP Allowlist.
  * Nếu có API nội bộ: kết hợp HTTPS, Authentication, API Key hoặc HMAC.
  * Nếu public ra Internet và có nguy cơ bị tấn công web: cân nhắc WAF.
* Ghi chú các điểm cần tối ưu chi phí:

  * Không để EC2, RDS, ALB hoặc NAT Gateway chạy khi không còn sử dụng.
  * Kiểm soát CloudWatch Logs để tránh lưu log quá nhiều.
  * Chỉ dùng WAF hoặc NAT Gateway khi thật sự cần.
  * Dọn dẹp tài nguyên lab sau khi hoàn thành.
