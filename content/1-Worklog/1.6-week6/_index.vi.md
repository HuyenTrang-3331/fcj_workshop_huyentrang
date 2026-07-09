---
title: "Worklog Tuần 6"
date: 2026-05-22
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Mục tiêu tuần 6:

* Hoàn thành nội dung học tập của **Module 05** về bảo mật và quản lý danh tính trên AWS trong chương trình **First Cloud AI Journey**.
* Hiểu mô hình **Shared Responsibility Model** và phân biệt trách nhiệm bảo mật giữa AWS và người dùng.
* Tìm hiểu các dịch vụ bảo mật và quản lý danh tính như **IAM**, **Amazon Cognito**, **AWS Organizations**, **AWS Identity Center**, **AWS KMS** và **AWS Security Hub**.
* Thực hành bật **AWS Security Hub**, kiểm tra điểm đánh giá bảo mật và dọn dẹp tài nguyên sau lab.
* Thực hành sử dụng **tag** để quản lý tài nguyên AWS, tạo Resource Group và thao tác với tag bằng AWS CLI.
* Thực hành tạo **IAM User**, **IAM Policy**, **IAM Role**, **Switch Role** và kiểm tra quyền truy cập theo điều kiện tag, region, IP và thời gian.
* Thực hành tạo restriction policy, IAM limited user và kiểm tra giới hạn quyền của IAM User theo nguyên tắc **least privilege**.
* Thực hành mã hóa dữ liệu với **AWS KMS**, ghi log bằng **CloudTrail**, truy vấn log bằng **Athena** và kiểm tra chia sẻ dữ liệu đã mã hóa trên S3.
* Tìm hiểu rủi ro khi sử dụng access key dài hạn và so sánh với cách cấp quyền an toàn hơn bằng IAM Role cho EC2.
* Rèn luyện kỹ năng phân tích quyền truy cập, kiểm tra policy, ghi chú lỗi cấu hình và áp dụng best practices trong bảo mật AWS.

### Các nhiệm vụ sẽ được thực hiện trong tuần này:

| Ngày | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| :--- | :--- | :--- | :--- | :--- |
| 1    | - Học Module 05-01: Shared Responsibility Model<br>- Học Module 05-02: Amazon Identity and Access Management<br>- Học Module 05-03: Amazon Cognito<br>- Học Module 05-04: AWS Organization<br>- Học Module 05-05: AWS Identity Center<br>- Học Module 05-06: Amazon Key Management Service<br>- Học Module 05-07: AWS Security Hub<br>- Học Module 05-08: Hands-on and Additional Research<br>- Ghi chú các khái niệm quan trọng về bảo mật, IAM, quản lý danh tính, mã hóa, tổ chức tài khoản và giám sát bảo mật<br>- Phân tích vai trò của security layer trong một kiến trúc AWS thực tế | 22/05/2026 | 22/05/2026 | https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i |
| 2    | - Làm Lab18-02: Enable Security Hub<br>- Làm Lab18-03: Score for each set of criteria<br>- Làm Lab18-04: Clean up resources<br>- Làm Lab22-2.1: Create VPC<br>- Làm Lab22-2.2: Create Security Group<br>- Làm Lab22-2.3: Create EC2 Instance<br>- Làm Lab22-2.4: Incoming Webhooks Slack<br>- Làm Lab22-3: Create Tag for Instance<br>- Làm Lab22-4: Create Role for Lambda<br>- Làm Lab22-5.1: Function stop instance<br>- Làm Lab22-5.2: Function start instance<br>- Làm Lab22-6: Check Result<br>- Làm Lab22-7: Clean up resources<br>- Phân tích cách Security Hub hỗ trợ đánh giá bảo mật tài khoản AWS<br>- Ghi chú cách dùng tag, Lambda và Slack webhook để tự động hóa quản lý EC2 | 25/05/2026 | 25/05/2026 | https://000018.awsstudygroup.com/<br><br>https://000022.awsstudygroup.com/ |
| 3    | - Làm Lab27-2.1.1: Create EC2 Instance with tag<br>- Làm Lab27-2.1.2: Managing Tags in AWS Resources<br>- Làm Lab27-2.1.3: Filter resources by tag<br>- Làm Lab27-2.2: Using tags with CLI<br>- Làm Lab27-3: Create a Resource Group<br>- Làm Lab27-4: Clean up resources<br>- Làm Lab28-2.1: Create IAM User<br>- Làm Lab28-3: Create IAM Policy<br>- Làm Lab28-4: Create IAM Role<br>- Làm Lab28-5.1: Switch Roles<br>- Phân tích vai trò của tag trong quản lý tài nguyên, phân quyền và tối ưu vận hành<br>- Ghi chú cách IAM Policy và IAM Role kiểm soát quyền truy cập trong AWS | 26/05/2026 | 26/05/2026 | https://000027.awsstudygroup.com/<br><br>https://000028.awsstudygroup.com/ |
| 4    | - Làm Lab28-5.2.1: Initiating access to EC2 console in AWS Region - Tokyo<br>- Làm Lab28-5.2.2: Initiating access to EC2 console in AWS Region - North Virginia<br>- Làm Lab28-5.2.3: Proceed to create EC2 instance when there are no qualified Tags<br>- Làm Lab28-5.2.4: Edit Resource Tag on EC2 Instance<br>- Làm Lab28-5.2.5: Policy Check<br>- Làm Lab28-6: Clean up resources<br>- Làm Lab30-3: Create Restriction Policy<br>- Làm Lab30-4: Create IAM Limited User<br>- Làm Lab30-5: Test IAM User Limits<br>- Làm Lab30-6: Clean up resources<br>- Kiểm tra quyền truy cập theo điều kiện region, resource tag và policy<br>- Ghi chú cách áp dụng least privilege để giới hạn quyền của IAM User | 27/05/2026 | 27/05/2026 | https://000028.awsstudygroup.com/<br><br>https://000030.awsstudygroup.com/ |
| 5    | - Làm Lab33-2.1: Create Policy and Role<br>- Làm Lab33-2.2: Create Group and User<br>- Làm Lab33-3: Create Key Management Service<br>- Làm Lab33-4.1: Create Bucket<br>- Làm Lab33-4.2: Upload data to S3<br>- Làm Lab33-5.1: Create CloudTrail<br>- Làm Lab33-5.2: Logging to CloudTrail<br>- Làm Lab33-5.3: Create Amazon Athena<br>- Làm Lab33-5.4: Retrieve data with Athena<br>- Làm Lab33-6: Test and share encrypted data on S3<br>- Làm Lab33-7: Resource cleanup<br>- Làm Lab44-2: Create IAM Group<br>- Làm Lab44-3.1: Create IAM Users<br>- Làm Lab44-3.2: Check permissions<br>- Làm Lab44-4.1: Create Admin IAM Role<br>- Làm Lab44-4.2: Configure Switch Role<br>- Làm Lab44-4.3.1: Limit switch role by IP<br>- Làm Lab44-4.3.2: Limit switch role by Time<br>- Làm Lab44-5: Clean up resources<br>- Làm Lab48-1.1: Create EC2 Instance<br>- Làm Lab48-1.2: Create S3 Bucket<br>- Làm Lab48-2.1: Generate IAM User and Access Key<br>- Làm Lab48-2.2: Use Access Key<br>- Làm Lab48-3.1: Create IAM Role<br>- Làm Lab48-3.2: Using IAM Role<br>- Làm Lab48-4: Clean up resources<br>- Phân tích vai trò của KMS, CloudTrail và Athena trong mã hóa, audit và truy vấn log<br>- So sánh rủi ro giữa access key dài hạn và IAM Role cho EC2<br>- Dọn dẹp tài nguyên để tránh phát sinh chi phí | 28/05/2026 | 28/05/2026 | https://000033.awsstudygroup.com/<br><br>https://000044.awsstudygroup.com/<br><br>https://000048.awsstudygroup.com/ |

### Kết quả đạt được tuần 6:

**Tổng quát:**

Trong tuần 6, tôi đã hoàn thành nội dung học tập của **Module 05** về bảo mật và quản lý danh tính trên AWS. Nội dung tuần này giúp tôi hiểu rõ hơn cách AWS tổ chức bảo mật theo nhiều lớp, từ quản lý định danh, phân quyền, mã hóa dữ liệu, ghi log, giám sát bảo mật cho đến kiểm soát truy cập theo điều kiện.

Ngoài việc học module và thực hành lab, tôi còn bổ sung thêm phần phân tích policy, kiểm tra quyền truy cập, so sánh access key với IAM Role, đánh giá bảo mật bằng Security Hub và ghi chú các best practices như least privilege, tag-based access control, mã hóa dữ liệu và audit log.

**Lý thuyết đã học:**

* Hiểu được **Shared Responsibility Model**:

  * AWS chịu trách nhiệm bảo mật của cloud.
  * Người dùng chịu trách nhiệm bảo mật trong cloud.
* Nắm được vai trò của **IAM** trong quản lý:

  * IAM User.
  * IAM Group.
  * IAM Role.
  * IAM Policy.
  * Permission.
  * Access Key.
  * Switch Role.
* Hiểu được vai trò của **Amazon Cognito** trong xác thực và phân quyền cho người dùng ứng dụng.
* Hiểu được vai trò của **AWS Organizations** và **AWS Identity Center** trong quản lý nhiều tài khoản AWS và đăng nhập tập trung.
* Hiểu được vai trò của **AWS KMS** trong tạo, quản lý và sử dụng khóa mã hóa để bảo vệ dữ liệu.
* Hiểu được vai trò của **AWS Security Hub** trong tổng hợp, đánh giá và theo dõi trạng thái bảo mật tài khoản AWS.
* Nắm được cách dùng **tag** để phân loại tài nguyên, lọc tài nguyên, tạo Resource Group và hỗ trợ kiểm soát quyền truy cập.
* Hiểu cách IAM Policy có thể kiểm soát quyền dựa trên điều kiện như:

  * Region.
  * Resource tag.
  * IP address.
  * Time.
* Hiểu được vai trò của **CloudTrail** trong ghi nhận hoạt động API và hỗ trợ audit.
* Hiểu được cách **Athena** có thể được dùng để truy vấn log lưu trên S3.
* Nhận thức được rủi ro khi sử dụng **access key dài hạn** và lợi ích của **IAM Role** trong việc cấp quyền tạm thời, an toàn hơn cho workload.
* Ghi nhận một số best practices:

  * Áp dụng nguyên tắc least privilege.
  * Không dùng Root User cho công việc hằng ngày.
  * Hạn chế sử dụng access key dài hạn.
  * Ưu tiên IAM Role cho EC2 và Lambda.
  * Bật MFA cho tài khoản quan trọng.
  * Mã hóa dữ liệu nhạy cảm bằng KMS.
  * Theo dõi hoạt động tài khoản bằng CloudTrail và Security Hub.
  * Dọn dẹp user, role, policy, access key và tài nguyên sau lab.

**Thực hành với bài lab:**

* Hoàn thành bài lab về **AWS Security Hub**:

  * Enable Security Hub.
  * Kiểm tra score theo từng nhóm tiêu chí.
  * Clean up resources.
* Thực hành tạo VPC, Security Group, EC2 Instance, gắn tag cho instance và tự động start/stop EC2 bằng Lambda.
* Thực hành tích hợp **Slack Webhook** để nhận thông báo khi xử lý tự động.
* Hoàn thành bài lab về **tag management**:

  * Tạo EC2 Instance có tag.
  * Quản lý tag trên AWS Resources.
  * Lọc tài nguyên theo tag.
  * Sử dụng tag với AWS CLI.
  * Tạo Resource Group.
* Hoàn thành bài lab về **IAM User, IAM Policy, IAM Role và Switch Role**:

  * Tạo IAM User.
  * Tạo IAM Policy.
  * Tạo IAM Role.
  * Thực hành Switch Role.
  * Kiểm tra quyền theo region và resource tag.
* Hoàn thành bài lab về **restriction policy và IAM limited user**:

  * Tạo restriction policy.
  * Tạo IAM Limited User.
  * Kiểm tra giới hạn quyền của IAM User.
* Hoàn thành bài lab về **AWS KMS, S3, CloudTrail và Athena**:

  * Tạo policy, role, group và user.
  * Tạo KMS Key.
  * Tạo S3 Bucket và upload dữ liệu.
  * Tạo CloudTrail và ghi log.
  * Tạo Athena và truy vấn log.
  * Kiểm tra chia sẻ dữ liệu đã mã hóa trên S3.
* Hoàn thành bài lab về **Switch Role có điều kiện**:

  * Tạo IAM Group và IAM Users.
  * Tạo Admin IAM Role.
  * Cấu hình Switch Role.
  * Giới hạn switch role theo IP.
  * Giới hạn switch role theo thời gian.
* Hoàn thành bài lab về **Access Key và IAM Role cho EC2**:

  * Tạo EC2 Instance.
  * Tạo S3 Bucket.
  * Tạo IAM User và Access Key.
  * Sử dụng Access Key.
  * Tạo IAM Role.
  * Gắn IAM Role cho EC2.
* Ghi chú các lỗi hoặc điểm cần kiểm tra:

  * Policy condition.
  * Resource tag.
  * Region restriction.
  * Access key permission.
  * Role trust policy.
  * KMS key permission.
  * CloudTrail log location.
  * Athena query result.
* Dọn dẹp user, group, role, policy, access key, EC2, S3, Lambda, Security Hub và các tài nguyên liên quan sau khi hoàn thành lab.
