---
title: "Worklog Tuần 5"
date: 2026-05-15
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu tuần 5:

* Hoàn thành nội dung học tập của **Module 04** về nhóm dịch vụ lưu trữ trên AWS trong chương trình **First Cloud AI Journey**.
* Tìm hiểu các dịch vụ lưu trữ chính trên AWS như **Amazon S3**, **AWS Storage Gateway**, **Snow Family**, **Disaster Recovery**, **AWS Backup** và **Amazon FSx**.
* Nắm được các khái niệm quan trọng của Amazon S3 như **Bucket**, **Object**, **Object Key**, **Access Point**, **Storage Class**, **Static Website Hosting**, **CORS**, **Control Access**, **Performance** và **Glacier**.
* Phân tích vai trò của storage trong kiến trúc AWS, bao gồm lưu trữ dữ liệu, sao lưu, khôi phục, phân phối nội dung và hỗ trợ migration.
* Thực hành tạo S3 Bucket, triển khai infrastructure, tạo backup plan, thiết lập notification, kiểm tra restore và dọn dẹp tài nguyên.
* Thực hành migration máy ảo từ môi trường on-premises lên AWS thông qua VMware Workstation, export/import virtual machine và triển khai EC2 Instance từ AMI.
* Thực hành cấu hình **AWS Storage Gateway**, tạo File Shares và mount file shares trên máy on-premises.
* Thực hành tạo và quản lý **Amazon FSx file system**, kiểm tra hiệu năng, giám sát hiệu năng, bật data deduplication, shadow copies, user quotas và scale capacity.
* Thực hành triển khai website tĩnh trên Amazon S3, cấu hình CloudFront, bucket versioning, move objects, replication object multi-region và dọn dẹp tài nguyên sau lab.
* Rèn luyện kỹ năng kiểm tra kết quả sau lab, ghi chú lỗi phát sinh, phân tích chi phí lưu trữ và áp dụng best practices khi sử dụng AWS Storage.

### Các nhiệm vụ sẽ được thực hiện trong tuần này:

| Ngày | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| :--- | :--- | :--- | :--- | :--- |
| 1    | - Học Module 04-01: Storage Services on AWS<br>- Học Module 04-02: Amazon Simple Storage Service S3 - Access Point - Storage Class<br>- Học Module 04-03: S3 Static Website, CORS, Control Access, Object Key, Performance và Glacier<br>- Học Module 04-04: Snow Family, Storage Gateway và Backup<br>- Ghi chú các khái niệm quan trọng về S3, Storage Class, Glacier, Storage Gateway, Snow Family và AWS Backup<br>- Phân tích vai trò của storage trong kiến trúc cloud thực tế<br>- So sánh các nhóm lưu trữ: object storage, file storage, backup storage và hybrid storage | 15/05/2026 | 15/05/2026 | https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i |
| 2    | - Làm Lab13-02.1: Create S3 Bucket<br>- Làm Lab13-02.2: Deploy Infrastructure<br>- Làm Lab13-03: Create Backup Plan<br>- Làm Lab13-04: Set up notifications<br>- Làm Lab13-05: Test Restore<br>- Làm Lab13-06: Clean up resources<br>- Phân tích vai trò của backup trong việc bảo vệ dữ liệu hệ thống<br>- Ghi chú sự khác nhau giữa backup, restore và disaster recovery<br>- Kiểm tra notification để theo dõi trạng thái backup job<br>- Bổ sung checklist dọn dẹp tài nguyên backup sau lab | 18/05/2026 | 18/05/2026 | https://000013.awsstudygroup.com/ |
| 3    | - Làm Lab14-01: VMware Workstation<br>- Làm Lab14-02.1: Export Virtual Machine from On-premises<br>- Làm Lab14-02.2: Upload virtual machine to AWS<br>- Làm Lab14-02.3: Import virtual machine to AWS<br>- Làm Lab14-02.4: Deploy Instance from AMI<br>- Làm Lab14-03.1: Setting up S3 Bucket ACL<br>- Làm Lab14-03.2: Export virtual machine from Instance<br>- Làm Lab14-05: Resource Cleanup on AWS Cloud<br>- Phân tích quy trình migration máy ảo từ on-premises lên AWS<br>- Ghi chú vai trò của S3 Bucket, ACL, AMI và EC2 trong quá trình migration | 19/05/2026 | 19/05/2026 | https://000014.awsstudygroup.com/ |
| 4    | - Làm Lab24-2.1: Create Storage Gateway<br>- Làm Lab24-2.2: Create File Shares<br>- Làm Lab24-2.3: Mount File Shares on On-premises Machine<br>- Làm Lab24-3: Clean up resources<br>- Làm Lab25-2.2: Create an SSD Multi-AZ File System<br>- Làm Lab25-2.3: Create an HDD Multi-AZ File System<br>- Làm Lab25-3: Create New File Shares<br>- Làm Lab25-4: Test Performance<br>- Làm Lab25-5: Monitor Performance<br>- Phân tích mô hình hybrid storage giữa hệ thống on-premises và AWS<br>- So sánh SSD Multi-AZ và HDD Multi-AZ theo hiệu năng, chi phí và tình huống sử dụng | 20/05/2026 | 20/05/2026 | https://000024.awsstudygroup.com/<br><br>https://000025.awsstudygroup.com/ |
| 5    | - Làm Lab25-6: Enable Data Deduplication<br>- Làm Lab25-7: Enable Shadow Copies<br>- Làm Lab25-8: Manage User Sessions and Open Files<br>- Làm Lab25-9: Enable User Storage Quotas<br>- Làm Lab25-11: Scale Throughput Capacity<br>- Làm Lab25-12: Scale Storage Capacity<br>- Làm Lab25-13: Delete Environment<br>- Làm Lab57-2.1: Create S3 Bucket<br>- Làm Lab57-2.2: Load Data<br>- Làm Lab57-3: Enable Static Website Feature<br>- Làm Lab57-4: Configuring Public Access Block<br>- Làm Lab57-5: Configuring Public Objects<br>- Làm Lab57-6: Test Website<br>- Làm Lab57-7.1: Block All Public Access<br>- Làm Lab57-7.2: Config Amazon CloudFront<br>- Làm Lab57-7.3: Test Amazon CloudFront<br>- Làm Lab57-8: Bucket Versioning<br>- Làm Lab57-9: Move Objects<br>- Làm Lab57-10: Replication Object Multi Region<br>- Làm Lab57-11: Clean up resources<br>- Phác thảo sơ đồ S3 Static Website kết hợp CloudFront và multi-region replication<br>- Ghi chú các best practices về public access, versioning, replication và tối ưu chi phí lưu trữ | 21/05/2026 | 21/05/2026 | https://000025.awsstudygroup.com/<br><br>https://000057.awsstudygroup.com/ |

### Kết quả đạt được tuần 5:

**Tổng quát:**

Trong tuần 5, tôi đã hoàn thành nội dung học tập của **Module 04** về nhóm dịch vụ lưu trữ trên AWS. Nội dung tuần này giúp tôi hiểu rõ hơn cách AWS hỗ trợ lưu trữ, sao lưu, khôi phục, migration, hybrid storage và phân phối nội dung thông qua các dịch vụ như Amazon S3, AWS Backup, Storage Gateway, Amazon FSx và CloudFront.

Ngoài việc học lý thuyết và thực hành lab, tôi cũng bổ sung thêm phần phân tích kiến trúc lưu trữ, so sánh dịch vụ, kiểm tra restore, đánh giá hiệu năng file system và ghi chú các lưu ý về bảo mật, chi phí và dọn dẹp tài nguyên sau lab.

**Lý thuyết đã học:**

* Hiểu được vai trò của các dịch vụ lưu trữ trên AWS trong việc lưu trữ, bảo vệ, sao lưu và phân phối dữ liệu.
* Nắm được các dịch vụ chính:

  * Amazon S3.
  * AWS Backup.
  * AWS Storage Gateway.
  * Amazon FSx.
  * Snow Family.
  * Disaster Recovery on AWS.
* Hiểu được các khái niệm quan trọng trong Amazon S3:

  * Bucket.
  * Object.
  * Object Key.
  * Access Point.
  * Storage Class.
  * Static Website Hosting.
  * CORS.
  * Glacier.
* Hiểu được cách chọn S3 Storage Class phù hợp để tối ưu chi phí theo tần suất truy cập dữ liệu.
* Hiểu vai trò của **AWS Backup** trong việc quản lý backup và restore tập trung.
* Hiểu quy trình migration máy ảo từ on-premises lên AWS thông qua S3, AMI và EC2.
* Hiểu vai trò của **Storage Gateway** trong mô hình hybrid storage.
* Hiểu vai trò của **Amazon FSx** trong việc cung cấp file system được quản lý trên AWS.
* Hiểu vai trò của **CloudFront** trong việc phân phối nội dung từ S3, tăng tốc truy cập và bảo vệ origin.
* Ghi nhận một số best practices:

  * Không public bucket nếu không cần thiết.
  * Sử dụng CloudFront thay vì truy cập trực tiếp vào S3.
  * Bật versioning cho dữ liệu quan trọng.
  * Kiểm tra restore sau khi cấu hình backup.
  * Theo dõi chi phí khi dùng replication, FSx, Storage Gateway và backup.

**Thực hành với bài lab:**

* Hoàn thành bài lab về **AWS Backup**:

  * Tạo S3 Bucket.
  * Deploy infrastructure.
  * Tạo Backup Plan.
  * Thiết lập notification.
  * Test Restore.
  * Dọn dẹp tài nguyên.
* Thực hành migration máy ảo từ môi trường on-premises lên AWS:

  * Export virtual machine.
  * Upload VM lên AWS.
  * Import VM thành AMI.
  * Deploy EC2 Instance từ AMI.
  * Dọn dẹp tài nguyên sau lab.
* Hoàn thành bài lab về **AWS Storage Gateway**:

  * Tạo Storage Gateway.
  * Tạo File Shares.
  * Mount file shares trên máy on-premises.
* Hoàn thành bài lab về **Amazon FSx**:

  * Tạo SSD/HDD Multi-AZ file system.
  * Test và monitor performance.
  * Bật data deduplication, shadow copies và user quotas.
  * Scale throughput/storage capacity.
* Hoàn thành bài lab **S3 Static Website và CloudFront**:

  * Tạo S3 Bucket.
  * Upload dữ liệu.
  * Bật static website hosting.
  * Cấu hình public access.
  * Cấu hình CloudFront.
  * Bật bucket versioning.
  * Move objects.
  * Cấu hình replication object multi-region.
* Phác thảo sơ đồ storage layer gồm S3, CloudFront, AWS Backup, Storage Gateway, FSx và on-premises environment.
* Dọn dẹp tài nguyên sau khi hoàn thành lab để tránh phát sinh chi phí.
