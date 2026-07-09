---
title: "Worklog Tuần 9"
date: 2026-06-12
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu tuần 9:

* Ôn tập và củng cố lại các nội dung đã học trong chương trình **First Cloud AI Journey**.
* Hệ thống lại kiến thức về các nhóm dịch vụ AWS chính như Compute, Storage, Networking, Database, Security và Management Tools.
* Tìm hiểu sâu hơn về bảo mật trên AWS, đặc biệt là **IAM**, **MFA**, **Policy**, **Role** và nguyên tắc **Least Privilege**.
* Tìm hiểu cách quản lý chi phí trên AWS thông qua **AWS Budgets**, **Cost Explorer**, Free Tier và quy trình dọn dẹp tài nguyên sau lab.
* Rèn luyện kỹ năng phân tích sơ đồ kiến trúc AWS và xác định vai trò của từng dịch vụ trong hệ thống.
* Ghi chú các lỗi thường gặp khi cấu hình IAM, phân quyền, Billing access và quản lý tài nguyên.
* Chuẩn bị nội dung báo cáo, ghi chú học tập và bài chia sẻ liên quan đến AWS IAM, bảo mật tài khoản và tối ưu chi phí.

### Các nhiệm vụ sẽ được thực hiện trong tuần này:

| Ngày | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| :--- | :--- | :--- | :--- | :--- |
| 1    | - Ôn tập các kiến thức nền tảng về AWS Cloud<br>- Hệ thống lại các nhóm dịch vụ chính như Compute, Storage, Networking, Database, Security và Management Tools<br>- Ghi chú vai trò của từng nhóm dịch vụ trong kiến trúc cloud<br>- Phân tích cách các dịch vụ AWS phối hợp trong một hệ thống thực tế<br>- Tổng hợp lại các kiến thức quan trọng từ các tuần trước | 12/06/2026 | 12/06/2026 | https://cloudjourney.awsstudygroup.com/vi/ |
| 2    | - Ôn tập AWS IAM<br>- Tìm hiểu lại User, Group, Role, Policy và Permission<br>- Tìm hiểu nguyên tắc Least Privilege trong cấp quyền<br>- Ghi chú các lỗi thường gặp khi cấu hình quyền IAM<br>- Phân tích sự khác nhau giữa IAM User và IAM Role<br>- Ghi chú các best practices khi cấp quyền cho người dùng và dịch vụ | 15/06/2026 | 15/06/2026 | https://docs.aws.amazon.com/iam/ |
| 3    | - Tìm hiểu MFA, IAM Identity Center và quản lý truy cập an toàn<br>- Ôn tập cách cấp quyền xem Billing cho IAM User<br>- Tìm hiểu vai trò của IAM trong bảo mật tài khoản AWS<br>- Ghi chú cách bảo vệ Root User, bật MFA và hạn chế sử dụng access key dài hạn<br>- Phân tích vai trò của đăng nhập tập trung trong môi trường có nhiều AWS Account | 16/06/2026 | 16/06/2026 | https://docs.aws.amazon.com/IAM/latest/UserGuide/ |
| 4    | - Tìm hiểu tối ưu chi phí trên AWS<br>- Ôn tập AWS Budgets, Cost Explorer và Free Tier<br>- Ghi chú các nguyên nhân dễ phát sinh chi phí như NAT Gateway, EC2, RDS, CloudWatch Logs và Load Balancer<br>- Thực hành kiểm tra và dọn dẹp tài nguyên không còn sử dụng<br>- Lập checklist kiểm tra chi phí sau khi hoàn thành bài lab<br>- Phân tích cách tagging hỗ trợ theo dõi chi phí theo project hoặc môi trường | 17/06/2026 | 17/06/2026 | https://aws.amazon.com/aws-cost-management/ |
| 5    | - Tổng hợp nội dung học tập tuần 9<br>- Viết ghi chú/bài chia sẻ về IAM và tối ưu chi phí<br>- Chuẩn bị nội dung báo cáo tuần<br>- Hoàn thiện phần kết quả đạt được trong tuần<br>- Rà soát lại các kiến thức quan trọng về bảo mật, chi phí và kiến trúc AWS<br>- Chuẩn bị nội dung để trình bày hoặc chia sẻ lại trong nhóm học tập | 18/06/2026 | 18/06/2026 | https://aws.amazon.com/blogs/security/ |

### Kết quả đạt được tuần 9:

**Tổng quát:**

Trong tuần 9, tôi đã tập trung ôn tập và hệ thống lại các kiến thức đã học trong chương trình **First Cloud AI Journey**. Nội dung tuần này giúp tôi củng cố lại vai trò của các nhóm dịch vụ AWS chính, đồng thời hiểu rõ hơn cách các dịch vụ kết hợp với nhau trong một kiến trúc cloud thực tế.

Ngoài phần ôn tập, tôi cũng tìm hiểu sâu hơn về **IAM**, bảo mật tài khoản, quản lý truy cập, tối ưu chi phí và dọn dẹp tài nguyên sau lab. Qua đó, tôi hình thành được thói quen kiểm tra quyền truy cập, theo dõi chi phí và đánh giá tài nguyên trước khi triển khai hoặc kết thúc một bài thực hành.

**Lý thuyết đã học:**

* Hệ thống lại các nhóm dịch vụ chính trong AWS:

  * Compute.
  * Storage.
  * Networking.
  * Database.
  * Security.
  * Management Tools.
* Hiểu rõ hơn vai trò của từng nhóm dịch vụ trong kiến trúc AWS.
* Nắm được vai trò của **IAM** trong việc quản lý định danh và phân quyền trên AWS.
* Ôn tập các thành phần chính trong IAM:

  * User.
  * Group.
  * Role.
  * Policy.
  * Permission.
* Hiểu được nguyên tắc **Least Privilege** và lý do chỉ nên cấp quyền tối thiểu cần thiết cho người dùng hoặc dịch vụ.
* Phân biệt được **IAM User** và **IAM Role**:

  * IAM User phù hợp cho người dùng hoặc tài khoản cần đăng nhập trực tiếp.
  * IAM Role phù hợp để cấp quyền tạm thời cho dịch vụ hoặc workload.
* Hiểu được tầm quan trọng của **MFA** trong việc bảo vệ tài khoản AWS.
* Hiểu được vai trò của **IAM Identity Center** trong quản lý đăng nhập tập trung.
* Biết được cách cấp quyền liên quan đến **Billing** cho IAM User.
* Nắm được một số nguyên nhân dễ phát sinh chi phí trên AWS:

  * EC2 Instance chạy liên tục.
  * RDS Database Instance chưa dừng hoặc chưa xóa.
  * NAT Gateway phát sinh chi phí theo giờ và theo dung lượng xử lý.
  * CloudWatch Logs lưu quá nhiều log.
  * Load Balancer không còn sử dụng nhưng chưa xóa.
  * S3 lưu trữ dữ liệu, versioning hoặc replication không được kiểm soát.
* Hiểu được vai trò của **AWS Budgets** và **Cost Explorer** trong việc theo dõi, cảnh báo và phân tích chi phí.
* Ghi nhận một số best practices:

  * Bật MFA cho Root User và IAM User quan trọng.
  * Không dùng Root User cho công việc hằng ngày.
  * Hạn chế sử dụng access key dài hạn.
  * Ưu tiên dùng IAM Role cho EC2, Lambda và workload.
  * Gắn tag cho tài nguyên để dễ quản lý và theo dõi chi phí.
  * Kiểm tra tài nguyên sau mỗi bài lab để tránh phát sinh chi phí không cần thiết.

**Thực hành và tổng hợp:**

* Ôn tập lại kiến thức nền tảng về AWS Cloud và các nhóm dịch vụ chính.
* Tổng hợp vai trò của từng nhóm dịch vụ trong một kiến trúc AWS cơ bản.
* Rà soát lại các nội dung quan trọng về IAM:

  * User.
  * Group.
  * Role.
  * Policy.
  * Permission.
  * MFA.
  * Billing access.
* Phân tích một số lỗi thường gặp khi cấu hình IAM:

  * Cấp quyền quá rộng.
  * Gán policy sai đối tượng.
  * Chưa bật MFA.
  * Sử dụng access key dài hạn.
  * Chưa hiểu rõ trust policy khi dùng role.
* Thực hành tư duy kiểm tra quyền truy cập theo nguyên tắc least privilege.
* Ôn tập cách theo dõi chi phí bằng AWS Budgets, Cost Explorer và Free Tier.
* Lập checklist kiểm tra tài nguyên sau lab:

  * EC2 Instance.
  * RDS Database.
  * NAT Gateway.
  * Load Balancer.
  * CloudWatch Logs.
  * S3 Bucket.
  * IAM User, Role, Policy không còn sử dụng.
* Ghi chú các dịch vụ có thể phát sinh chi phí cao nếu không kiểm soát tốt như NAT Gateway, RDS, CloudWatch Logs và Load Balancer.
* Chuẩn bị nội dung chia sẻ về **IAM**, bảo mật tài khoản và tối ưu chi phí trên AWS.
* Rèn luyện kỹ năng phân tích sơ đồ kiến trúc AWS, xác định vai trò từng dịch vụ và nhận diện điểm cần cải thiện về bảo mật hoặc chi phí.
