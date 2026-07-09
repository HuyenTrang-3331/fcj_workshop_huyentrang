---
title: "Worklog Tuần 4"
date: 2026-05-08
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Mục tiêu tuần 4:

* Hoàn thành nội dung học tập của **Module 03** trong chương trình **First Cloud AI Journey**.
* Tìm hiểu nhóm dịch vụ **Compute VM trên AWS**, tập trung vào **Amazon EC2** và các thành phần liên quan.
* Nắm được các khái niệm quan trọng của EC2 như **Instance Type**, **AMI**, **Key Pair**, **EBS**, **Instance Store**, **User Data**, **Metadata** và **EC2 Auto Scaling**.
* Tìm hiểu thêm các dịch vụ mở rộng như **Amazon EFS**, **Amazon FSx**, **Amazon Lightsail** và **AWS Application Migration Service**.
* Phân tích vai trò của compute, storage, backup và content delivery trong một kiến trúc AWS thực tế.
* Thực hành triển khai **AWS Backup**, tạo backup plan, kiểm tra restore và dọn dẹp tài nguyên.
* Thực hành tạo **S3 Bucket**, **Storage Gateway** và **File Shares** để hiểu mô hình lưu trữ kết hợp trên AWS.
* Thực hành triển khai website tĩnh trên **Amazon S3**, cấu hình public access, CloudFront, bucket versioning, move objects và replication object multi-region.
* Rèn luyện kỹ năng kiểm tra kết quả sau lab, phân tích lỗi cấu hình, ghi chú best practices và dọn dẹp tài nguyên để tránh phát sinh chi phí.

### Các nhiệm vụ sẽ được thực hiện trong tuần này:

| Ngày | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| :--- | :--- | :--- | :--- | :--- |
| 1    | - Học Module 03-01: Compute VM on AWS<br>- Học Module 03-01-01: Amazon EC2 - Instance Type<br>- Học Module 03-01-02: Amazon EC2 - AMI / Backup / Key Pair<br>- Học Module 03-01-03: Amazon EC2 - Elastic Block Store<br>- Học Module 03-01-04: Amazon EC2 - Instance Store<br>- Học Module 03-01-05: Amazon EC2 - User Data<br>- Học Module 03-01-06: Amazon EC2 - Metadata<br>- Học Module 03-01-07: Amazon EC2 - EC2 Auto Scaling<br>- Học Module 03-02: EC2 Auto Scaling, EFS, FSx, Lightsail và MGN<br>- Phân tích vai trò của EC2 trong kiến trúc cloud thực tế<br>- So sánh EBS và Instance Store theo độ bền dữ liệu, hiệu năng và vòng đời tài nguyên<br>- Ghi chú các trường hợp nên dùng EC2, Lightsail hoặc Auto Scaling | 08/05/2026 | 08/05/2026 | https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i |
| 2    | - Làm Lab13-01: Deploy AWS Backup to the System - Introduction<br>- Làm Lab13-02.2: Deploy infrastructure<br>- Làm Lab13-03: Create Backup Plan<br>- Làm Lab13-05: Test Restore<br>- Làm Lab13-06: Clean up resources<br>- Phân tích vai trò của backup trong hệ thống production<br>- Ghi chú sự khác nhau giữa backup và snapshot<br>- Kiểm tra quy trình restore để đánh giá khả năng khôi phục dữ liệu khi xảy ra sự cố<br>- Bổ sung checklist dọn dẹp tài nguyên backup sau lab | 11/05/2026 | 11/05/2026 | https://000013.awsstudygroup.com/ |
| 3    | - Làm Lab24-01.1: Create S3 Bucket<br>- Làm Lab24-01.2: Create EC2 for Storage Gateway<br>- Làm Lab24-02.1: Create Storage Gateway<br>- Làm Lab24-02.2: Create File Shares<br>- Tìm hiểu vai trò của Amazon S3, AWS Storage Gateway và File Shares<br>- Phân tích mô hình lưu trữ hybrid giữa môi trường on-premises và AWS<br>- Ghi chú các trường hợp sử dụng Storage Gateway trong doanh nghiệp<br>- Kiểm tra cách dữ liệu được lưu trữ, chia sẻ và truy cập thông qua file share | 12/05/2026 | 12/05/2026 | https://000024.awsstudygroup.com/ |
| 4    | - Làm Lab57-02.1: Create S3 Bucket<br>- Làm Lab57-02.2: Load data<br>- Làm Lab57-03: Enable static website feature<br>- Làm Lab57-04: Configuring public access block<br>- Làm Lab57-05: Configuring public objects<br>- Làm Lab57-06: Test website<br>- Phân tích cách S3 hoạt động trong mô hình static website hosting<br>- Kiểm tra sự khác nhau giữa public bucket access và public object access<br>- Ghi chú rủi ro bảo mật khi public trực tiếp S3 Bucket ra Internet<br>- Kiểm tra website sau khi triển khai và ghi nhận kết quả truy cập | 13/05/2026 | 13/05/2026 | https://000057.awsstudygroup.com/ |
| 5    | - Làm Lab57-07.1: Block all public access<br>- Làm Lab57-07.2: Config Amazon CloudFront<br>- Làm Lab57-07.3: Test Amazon CloudFront<br>- Làm Lab57-08: Bucket Versioning<br>- Làm Lab57-09: Move objects<br>- Làm Lab57-10: Replication Object multi Region<br>- Làm Lab57-11: Clean up resources<br>- Phân tích vai trò của CloudFront trong việc tăng tốc truy cập và bảo vệ origin<br>- Ghi chú lợi ích của Bucket Versioning và Replication Object multi-region<br>- Hoàn thiện sơ đồ kiến trúc S3 Static Website kết hợp CloudFront<br>- Dọn dẹp tài nguyên để tránh phát sinh chi phí | 14/05/2026 | 14/05/2026 | https://000057.awsstudygroup.com/ |

### Kết quả đạt được tuần 4:

**Tổng quát:**

Trong tuần 4, tôi đã hoàn thành nội dung học tập của **Module 03** về nhóm dịch vụ **Compute VM trên AWS**. Nội dung tuần này giúp tôi hiểu rõ hơn cách AWS cung cấp tài nguyên máy chủ ảo thông qua Amazon EC2, đồng thời mở rộng kiến thức sang các thành phần liên quan như lưu trữ, backup, Auto Scaling, Storage Gateway, S3 và CloudFront.

Ngoài việc học module và thực hiện các bài lab, tôi còn bổ sung thêm phần phân tích kiến trúc, so sánh các dịch vụ, kiểm tra lỗi cấu hình, ghi chú best practices và đánh giá chi phí khi sử dụng tài nguyên. Qua đó, tôi có cái nhìn thực tế hơn về cách triển khai một hệ thống AWS có khả năng lưu trữ, sao lưu, khôi phục và phân phối nội dung hiệu quả.

**Lý thuyết đã học:**

* Hiểu được vai trò của **Amazon EC2** trong việc cung cấp máy chủ ảo linh hoạt để triển khai ứng dụng và workload trên AWS.
* Nắm được các thành phần quan trọng của EC2:

  * Instance Type.
  * AMI.
  * Key Pair.
  * EBS.
  * Instance Store.
  * User Data.
  * Metadata.
  * EC2 Auto Scaling.
* Hiểu được cách lựa chọn **Instance Type** dựa trên nhu cầu về CPU, RAM, network performance và storage performance.
* Phân biệt được **EBS** và **Instance Store**:

  * EBS phù hợp cho dữ liệu cần lưu trữ lâu dài và có thể tồn tại độc lập với vòng đời EC2.
  * Instance Store phù hợp cho dữ liệu tạm thời, cache hoặc workload cần tốc độ cao nhưng không yêu cầu lưu trữ lâu dài.
* Hiểu được vai trò của **User Data** trong việc tự động chạy script khi EC2 Instance được khởi tạo.
* Hiểu được vai trò của **Metadata** trong việc cung cấp thông tin cấu hình của EC2 Instance.
* Nắm được vai trò của **EC2 Auto Scaling** trong việc tự động tăng hoặc giảm số lượng instance theo tải hệ thống.
* Tìm hiểu thêm các dịch vụ liên quan:

  * **Amazon EFS**: file storage dùng chung cho nhiều instance.
  * **Amazon FSx**: file system được quản lý cho các workload chuyên biệt.
  * **Amazon Lightsail**: dịch vụ đơn giản hóa việc triển khai server, phù hợp với website hoặc ứng dụng nhỏ.
  * **AWS Application Migration Service**: hỗ trợ migration workload từ môi trường hiện tại lên AWS.
* Hiểu được vai trò của **AWS Backup** trong quản lý sao lưu và khôi phục dữ liệu tập trung.
* Hiểu được vai trò của **Amazon S3** trong lưu trữ object, triển khai static website và quản lý dữ liệu.
* Hiểu được vai trò của **AWS Storage Gateway** trong việc kết nối môi trường lưu trữ hiện có với AWS.
* Hiểu được vai trò của **Amazon CloudFront** trong phân phối nội dung, giảm độ trễ, tăng tốc truy cập và bảo vệ origin.
* Nắm được các khái niệm liên quan đến quản lý object:

  * Bucket Versioning.
  * Move objects.
  * Replication Object multi-region.
  * Public access block.
  * Static website hosting.
* Ghi nhận một số best practices:

  * Không public S3 Bucket nếu không thật sự cần thiết.
  * Nên dùng CloudFront để phân phối nội dung thay vì truy cập trực tiếp vào bucket.
  * Cần kiểm tra khả năng restore sau khi cấu hình backup.
  * Cần dọn dẹp EC2, backup plan, bucket, CloudFront distribution và các tài nguyên liên quan sau lab.
  * Cần theo dõi chi phí khi sử dụng NAT Gateway, EC2, Storage Gateway, CloudFront và replication multi-region.

**Thực hành với bài lab:**

* Hoàn thành bài lab **Deploy AWS Backup to the System**:

  * Deploy infrastructure.
  * Create Backup Plan.
  * Test Restore.
  * Clean up resources.
* Thực hành triển khai **AWS Backup**, tạo backup plan và kiểm tra khả năng restore dữ liệu.
* Ghi chú quy trình backup/restore để hiểu cách bảo vệ dữ liệu trong hệ thống thực tế.
* Hoàn thành bài lab về **Storage Gateway**:

  * Create S3 Bucket.
  * Create EC2 for Storage Gateway.
  * Create Storage Gateway.
  * Create File Shares.
* Thực hành tạo **S3 Bucket**, **Storage Gateway** và **File Shares** để hiểu mô hình lưu trữ kết hợp trên AWS.
* Kiểm tra cách dữ liệu được chia sẻ và truy cập thông qua file share.
* Hoàn thành bài lab triển khai **S3 Static Website**:

  * Create S3 bucket.
  * Load data.
  * Enable static website hosting.
  * Configure public access.
  * Configure public objects.
  * Test website.
* Thực hành triển khai website tĩnh trên Amazon S3 và kiểm tra kết quả truy cập từ Internet.
* Thực hành cấu hình **CloudFront** để phân phối nội dung website từ S3.
* Kiểm tra sự khác nhau giữa truy cập website trực tiếp từ S3 và truy cập thông qua CloudFront.
* Thực hành các thao tác quản lý object trong S3:

  * Bucket Versioning.
  * Move objects.
  * Replication Object multi-region.
* Phác thảo sơ đồ kiến trúc website tĩnh gồm:

  * User/Client.
  * CloudFront.
  * S3 Bucket.
  * Public access / Block public access.
  * Object versioning.
  * Multi-region replication.
* Ghi chú các lỗi hoặc điểm cần kiểm tra sau khi cấu hình:

  * Bucket policy.
  * Public access block.
  * Object permission.
  * CloudFront distribution status.
  * S3 website endpoint.
  * Replication rule.
* Dọn dẹp tài nguyên sau khi hoàn thành lab để tránh phát sinh chi phí không cần thiết.
