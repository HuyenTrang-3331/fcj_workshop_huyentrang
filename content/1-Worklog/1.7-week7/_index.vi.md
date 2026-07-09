---
title: "Worklog Tuần 7"
date: 2026-05-29
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu tuần 7:

* Hoàn thành nội dung học tập của **Module 06** về **Database trên AWS** trong chương trình **First Cloud AI Journey**.
* Ôn tập các khái niệm nền tảng về cơ sở dữ liệu, relational database, non-relational database, schema, table, query và transaction.
* Tìm hiểu các dịch vụ database chính trên AWS như **Amazon RDS**, **Amazon Aurora**, **Amazon Redshift** và **Amazon ElastiCache**.
* Phân tích vai trò của database layer trong một kiến trúc AWS thực tế, bao gồm lưu trữ dữ liệu, kết nối ứng dụng, backup, restore, migration và tối ưu hiệu năng.
* Thực hành triển khai hệ thống sử dụng **Amazon RDS**, bao gồm VPC, Security Group, DB Subnet Group, EC2 Instance, RDS Database Instance và Application Deployment.
* Thực hành backup, restore và kiểm tra khả năng khôi phục dữ liệu sau khi triển khai RDS.
* Thực hành kết nối EC2 bằng **RDP Client** và **Fleet Manager** để chuẩn bị môi trường migration.
* Thực hành cấu hình source database và target database phục vụ quá trình migration từ SQL Server/Oracle sang MySQL.
* Thực hành chuyển đổi schema, tạo endpoint, tạo migration task, kiểm tra log và xử lý lỗi trong quá trình migration database.
* Rèn luyện kỹ năng kiểm tra kết nối database, theo dõi trạng thái migration, phân tích lỗi và dọn dẹp tài nguyên để tránh phát sinh chi phí.

### Các nhiệm vụ sẽ được thực hiện trong tuần này:

| Ngày | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| :--- | :--- | :--- | :--- | :--- |
| 1    | - Học Module 06-01: Database Concepts Review<br>- Ôn tập các khái niệm nền tảng về database, relational database, non-relational database, schema, table, record, query và transaction<br>- Học Module 06-02: Amazon RDS & Amazon Aurora<br>- Tìm hiểu vai trò của RDS và Aurora trong triển khai database được quản lý trên AWS<br>- Học Module 06-03: Redshift - ElastiCache<br>- Tìm hiểu tổng quan về data warehouse và caching trên AWS<br>- Phân tích cách database layer kết nối với application layer trong kiến trúc AWS<br>- Ghi chú các tiêu chí khi lựa chọn database service như hiệu năng, chi phí, khả năng mở rộng, backup và độ sẵn sàng | 29/05/2026 | 29/05/2026 | https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i |
| 2    | - Làm Lab05-2.1: Create a VPC<br>- Làm Lab05-2.2: Create EC2 Security Group<br>- Làm Lab05-2.3: Create RDS Security Group<br>- Làm Lab05-2.4: Create DB Subnet Group<br>- Làm Lab05-3: Create EC2 Instance<br>- Làm Lab05-4: Create RDS Database Instance<br>- Làm Lab05-5: Application Deployment<br>- Làm Lab05-6: Backup and Restore<br>- Làm Lab05-7: Clean up resources<br>- Phân tích luồng kết nối giữa EC2 Application và RDS Database<br>- Ghi chú vai trò của Security Group và DB Subnet Group trong bảo mật database | 01/06/2026 | 01/06/2026 | https://000005.awsstudygroup.com/ |
| 3    | - Làm Lab43-01: EC2 Connect RDP Client<br>- Làm Lab43-02: EC2 Connect Fleet Manager<br>- Làm Lab43-03: SQLSrv Src Config<br>- Làm Lab43-04: Oracle connect SrcDB<br>- Làm Lab43-05: Oracle config SrcDB<br>- Làm Lab43-06: Drop Constraint<br>- Làm Lab43-07: MSSQL to Aurora MySQL Target Config<br>- Chuẩn bị môi trường source database và target database phục vụ quá trình migration<br>- Ghi chú các bước kiểm tra kết nối, credential, network và database engine trước khi migration | 02/06/2026 | 02/06/2026 | https://000043.awsstudygroup.com/ |
| 4    | - Làm Lab43-08: MSSQL to MySQL Create Project<br>- Làm Lab43-09: MSSQL to MySQL Schema Conversion<br>- Làm Lab43-10: Oracle to MySQL Schema Conversion 1<br>- Làm Lab43-11: Create Migration Task and Endpoint<br>- Làm Lab43-12: Inspect S3<br>- Làm Lab43-13: Create Serverless Migration<br>- Ghi chú quy trình chuyển đổi schema và tạo migration task<br>- Phân tích vai trò của endpoint, migration task, schema conversion và S3 trong quá trình migration database | 03/06/2026 | 03/06/2026 | https://000043.awsstudygroup.com/ |
| 5    | - Làm Lab43-14: Create Event Notification<br>- Làm Lab43-15: Logs<br>- Làm Lab43-16: Troubleshoot Test Scenario Mem Pressure<br>- Làm Lab43-17: Troubleshoot Test Scenario Table Error<br>- Kiểm tra log, theo dõi trạng thái migration và xử lý lỗi phát sinh trong quá trình thực hành<br>- Ghi chú các lỗi thường gặp như memory pressure, table error, lỗi schema, lỗi endpoint và lỗi quyền truy cập<br>- Dọn dẹp tài nguyên sau khi hoàn thành lab để tránh phát sinh chi phí | 04/06/2026 | 04/06/2026 | https://000043.awsstudygroup.com/ |

### Kết quả đạt được tuần 7:

**Tổng quát:**

Trong tuần 7, tôi đã hoàn thành nội dung học tập của **Module 06** về **Database trên AWS**. Nội dung tuần này giúp tôi hiểu rõ hơn vai trò của database trong kiến trúc cloud, từ việc triển khai relational database bằng Amazon RDS, sử dụng database được quản lý, cấu hình kết nối ứng dụng, cho đến backup, restore và migration dữ liệu.

Ngoài việc học module và thực hành lab, tôi còn bổ sung thêm phần phân tích kiến trúc database layer, kiểm tra bảo mật kết nối giữa EC2 và RDS, theo dõi trạng thái migration, đọc log, xử lý lỗi và đánh giá các yếu tố cần quan tâm khi triển khai database trên AWS như hiệu năng, chi phí, bảo mật và khả năng khôi phục dữ liệu.

**Lý thuyết đã học:**

* Ôn tập các khái niệm nền tảng về cơ sở dữ liệu:

  * Database.
  * Table.
  * Record.
  * Schema.
  * Query.
  * Transaction.
  * Relational Database.
  * Non-relational Database.
* Hiểu được vai trò của **Amazon RDS** trong việc triển khai và quản lý relational database trên AWS.
* Hiểu được vai trò của **Amazon Aurora** trong việc cung cấp database có hiệu năng cao, khả năng mở rộng tốt và độ sẵn sàng cao.
* Hiểu được vai trò của **Amazon Redshift** trong việc xây dựng data warehouse phục vụ phân tích dữ liệu quy mô lớn.
* Hiểu được vai trò của **Amazon ElastiCache** trong việc tăng tốc ứng dụng thông qua caching và giảm tải truy vấn trực tiếp đến database.
* Nắm được các thành phần chính khi triển khai RDS:

  * VPC.
  * EC2 Security Group.
  * RDS Security Group.
  * DB Subnet Group.
  * EC2 Instance.
  * RDS Database Instance.
  * Database endpoint.
* Hiểu được vai trò của **Security Group** trong việc kiểm soát kết nối từ application server đến database.
* Hiểu được lý do nên đặt database trong private subnet để hạn chế truy cập trực tiếp từ Internet.
* Nắm được vai trò của **backup và restore** trong việc bảo vệ dữ liệu và đảm bảo khả năng khôi phục khi xảy ra sự cố.
* Hiểu được quy trình migration database từ SQL Server/Oracle sang MySQL:

  * Chuẩn bị source database.
  * Chuẩn bị target database.
  * Chuyển đổi schema.
  * Tạo endpoint.
  * Tạo migration task.
  * Theo dõi log và xử lý lỗi.
* Hiểu được vai trò của **schema conversion** khi di chuyển dữ liệu giữa các hệ quản trị cơ sở dữ liệu khác nhau.
* Hiểu được vai trò của **Amazon S3** trong việc lưu trữ dữ liệu trung gian hoặc artifact liên quan đến quá trình migration.
* Ghi nhận một số best practices khi triển khai database trên AWS:

  * Không public database trực tiếp ra Internet.
  * Chỉ mở port database cho nguồn truy cập cần thiết.
  * Sử dụng Security Group rõ ràng cho EC2 và RDS.
  * Luôn kiểm tra backup/restore thay vì chỉ tạo backup.
  * Theo dõi log khi migration để phát hiện lỗi sớm.
  * Dọn dẹp RDS, EC2, endpoint, migration task và tài nguyên liên quan sau lab để tránh phát sinh chi phí.

**Thực hành với bài lab:**

* Hoàn thành bài lab triển khai **Amazon RDS**:

  * Create a VPC.
  * Create EC2 Security Group.
  * Create RDS Security Group.
  * Create DB Subnet Group.
  * Create EC2 Instance.
  * Create RDS Database Instance.
  * Application Deployment.
  * Backup and Restore.
  * Clean up resources.
* Thực hành tạo hạ tầng mạng, Security Group và DB Subnet Group để chuẩn bị môi trường cho RDS.
* Thực hành tạo EC2 Instance làm môi trường kết nối hoặc triển khai ứng dụng truy cập database.
* Thực hành tạo RDS Database Instance và kiểm tra kết nối giữa ứng dụng với database.
* Thực hành backup và restore database để kiểm tra khả năng khôi phục dữ liệu.
* Hoàn thành bài lab chuẩn bị môi trường migration:

  * EC2 Connect RDP Client.
  * EC2 Connect Fleet Manager.
  * SQL Server source configuration.
  * Oracle source database connection.
  * Oracle source database configuration.
  * Drop Constraint.
  * MSSQL to Aurora MySQL target configuration.
* Thực hành kết nối vào EC2 bằng RDP Client và Fleet Manager.
* Thực hành cấu hình source database và target database phục vụ migration.
* Hoàn thành bài lab về chuyển đổi schema và migration:

  * MSSQL to MySQL Create Project.
  * MSSQL to MySQL Schema Conversion.
  * Oracle to MySQL Schema Conversion.
  * Create Migration Task and Endpoint.
  * Inspect S3.
  * Create Serverless Migration.
* Thực hành tạo migration project, chuyển đổi schema, tạo endpoint và migration task.
* Thực hành kiểm tra S3 để quan sát dữ liệu hoặc artifact liên quan đến migration.
* Hoàn thành bài lab về monitoring và troubleshooting migration:

  * Create Event Notification.
  * Logs.
  * Troubleshoot Memory Pressure.
  * Troubleshoot Table Error.
* Thực hành kiểm tra log, theo dõi trạng thái migration và xử lý một số lỗi cơ bản trong quá trình migration.
* Ghi chú các điểm cần kiểm tra khi migration gặp lỗi:

  * Kết nối source database.
  * Kết nối target database.
  * Credential.
  * Security Group.
  * Endpoint.
  * Schema conversion.
  * Migration task status.
  * Error logs.
* Phác thảo sơ đồ database layer gồm:

  * Application/EC2.
  * RDS Database.
  * DB Subnet Group.
  * Security Group.
  * Source Database.
  * Target Database.
  * Migration Task.
  * S3.
  * Logs/Event Notification.
* Dọn dẹp các tài nguyên như EC2, RDS, Security Group, DB Subnet Group, migration task, endpoint, S3 artifact và các tài nguyên liên quan sau khi hoàn thành lab.
