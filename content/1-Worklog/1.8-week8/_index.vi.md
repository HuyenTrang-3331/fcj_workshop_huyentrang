---
title: "Worklog Tuần 8"
date: 2026-06-05
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Mục tiêu tuần 8:

* Hoàn thành nội dung học tập và thực hành của **Module 07** về dữ liệu, phân tích dữ liệu và xử lý dữ liệu serverless trên AWS.
* Tìm hiểu quy trình xây dựng một **data pipeline** trên AWS, bao gồm ingest data, store data, catalog data, transform data, analyze data và visualize data.
* Thực hành tạo **S3 Bucket**, Delivery Stream, sample data, Glue Crawler và kiểm tra dữ liệu đầu ra trên S3.
* Tìm hiểu cách phân tích dữ liệu bằng **Amazon Athena** và trực quan hóa dữ liệu bằng **Amazon QuickSight**.
* Thực hành với **Amazon DynamoDB**, bao gồm khám phá DynamoDB Console, backup, clean up, advanced design patterns, global serverless application và event-driven architecture.
* Tìm hiểu cách sử dụng tagging, cost allocation và usage để theo dõi chi phí khi làm việc với database và dữ liệu.
* Thực hành sử dụng **CloudShell**, AWS Console, SDK và Cloud9 trong quá trình xử lý dữ liệu.
* Thực hành xử lý dữ liệu với **AWS Glue DataBrew**, **AWS Glue**, **Amazon EMR**, **Athena**, **Kinesis Data Analytics**, **QuickSight**, **Lambda** và **Amazon Redshift**.
* Rèn luyện kỹ năng xây dựng dashboard, cải thiện dashboard và tạo interactive dashboard phục vụ phân tích dữ liệu.
* Bổ sung kỹ năng kiểm tra kết quả sau lab, ghi chú lỗi phát sinh, phân tích luồng dữ liệu và dọn dẹp tài nguyên để tránh phát sinh chi phí.

### Các nhiệm vụ sẽ được thực hiện trong tuần này:

| Ngày | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| :--- | :--- | :--- | :--- | :--- |
| 1    | - Làm Lab35-3.1: Create S3 Bucket<br>- Làm Lab35-3.2: Creating a Delivery Stream<br>- Làm Lab35-3.3: Create Sample Data<br>- Làm Lab35-4.1: Create Glue Crawler<br>- Làm Lab35-4.2: Data Check<br>- Làm Lab35-5.1: Explain code in Vietnamese version<br>- Làm Lab35-5.2: S3 store output<br>- Làm Lab35-5.3: Session connect setup<br>- Làm Lab35-6.1: Analysis with Athena<br>- Làm Lab35-6.2: Visualize with QuickSight<br>- Làm Lab35-7: Clean up resources<br>- Phân tích luồng dữ liệu từ ingestion, lưu trữ trên S3, catalog bằng Glue Crawler, truy vấn bằng Athena và trực quan hóa bằng QuickSight | 05/06/2026 | 05/06/2026 | https://000035.awsstudygroup.com/ |
| 2    | - Làm Lab39-1: LHOL - Hands-on Labs for Amazon DynamoDB<br>- Làm Lab39-2: Explore DynamoDB<br>- Làm Lab39-3: Explore DynamoDB Console<br>- Làm Lab39-4: Back up<br>- Làm Lab39-5: Clean up<br>- Làm Lab39-6: LADV - Advanced Design Patterns for Amazon DynamoDB<br>- Làm Lab39-7: LMR - Build and Deploy a Global Serverless Application with Amazon DynamoDB<br>- Làm Lab39-8: LEDA - Build a Serverless Event Driven Architecture with DynamoDB<br>- Ghi chú vai trò của DynamoDB trong ứng dụng serverless, global application và kiến trúc event-driven | 08/06/2026 | 08/06/2026 | https://000039.awsstudygroup.com/ |
| 3    | - Làm Lab40-2.1: Preparing the database<br>- Làm Lab40-2.2: Building a database<br>- Làm Lab40-3.1: Data in the Table<br>- Làm Lab40-3.2: Cost<br>- Làm Lab40-3.3: Tagging and Cost Allocation<br>- Làm Lab40-3.4: Usage<br>- Làm Lab40-3.5: Addition result query<br>- Làm Lab40-4: Clean up resources<br>- Làm Lab60-1: CloudShell 2.2<br>- Làm Lab60-2: Console<br>- Làm Lab60-3: SDK<br>- Phân tích cách theo dõi chi phí, usage và tagging khi làm việc với database trên AWS<br>- So sánh các cách thao tác với AWS thông qua Console, CloudShell và SDK | 09/06/2026 | 09/06/2026 | https://000040.awsstudygroup.com/<br><br>https://000060.awsstudygroup.com/ |
| 4    | - Làm Lab70-1.1: Creating a Cloud9 Instance<br>- Làm Lab70-1.2: Download Dataset<br>- Làm Lab70-1.3: Upload Dataset to S3<br>- Làm Lab70-2.1: Setting up DataBrew<br>- Làm Lab70-2.2: Data Profiling<br>- Làm Lab70-2.3: Clean & Transform data<br>- Làm Lab72-2: Preparatory steps<br>- Làm Lab72-3: Ingest and Store<br>- Làm Lab72-4: Catalog Data<br>- Ghi chú quy trình chuẩn bị dữ liệu, upload dataset lên S3, profiling, cleaning, transforming và cataloging dữ liệu<br>- Phân tích vai trò của Cloud9, S3, DataBrew và Glue trong bước chuẩn bị dữ liệu | 10/06/2026 | 10/06/2026 | https://000070.awsstudygroup.com/<br><br>https://000072.awsstudygroup.com/ |
| 5    | - Làm Lab72-5: Transform Data with AWS Glue interactive sessions<br>- Làm Lab72-6: Transform Data with AWS Glue GUI<br>- Làm Lab72-7: Transform Data with AWS Glue DataBrew<br>- Làm Lab72-8: Transform Data with EMR<br>- Làm Lab72-9: Analysis with Athena<br>- Làm Lab72-10: Analysis with Kinesis Data Analytics<br>- Làm Lab72-11: Visualize in QuickSight<br>- Làm Lab72-12: Serve with Lambda<br>- Làm Lab72-13: Warehouse on Redshift<br>- Làm Lab73-3: Build Dashboard<br>- Làm Lab73-4: Dashboard Improvements<br>- Làm Lab73-5: Create Interactive Dashboard<br>- Phân tích sự khác nhau giữa batch processing, streaming analytics, serverless processing và data warehouse<br>- Hoàn thiện dashboard và dọn dẹp tài nguyên sau khi hoàn thành bài lab | 11/06/2026 | 11/06/2026 | https://000072.awsstudygroup.com/<br><br>https://000073.awsstudygroup.com/ |

### Kết quả đạt được tuần 8:

**Tổng quát:**

Trong tuần 8, tôi đã hoàn thành nội dung học tập và thực hành của **Module 07** về dữ liệu, phân tích dữ liệu và xử lý dữ liệu serverless trên AWS. Nội dung tuần này giúp tôi hiểu rõ hơn cách xây dựng một data pipeline trên AWS, từ bước thu thập dữ liệu, lưu trữ, catalog, làm sạch, chuyển đổi, phân tích đến trực quan hóa dữ liệu.

Ngoài việc thực hiện các bài lab, tôi còn bổ sung thêm phần phân tích kiến trúc dữ liệu, so sánh các dịch vụ xử lý dữ liệu, kiểm tra chi phí, tagging, usage, dashboard và dọn dẹp tài nguyên. Qua đó, tôi có cái nhìn thực tế hơn về cách thiết kế data analytics layer trong một hệ thống cloud.

**Lý thuyết đã học:**

* Hiểu được quy trình cơ bản của một data pipeline trên AWS:

  * Ingest data.
  * Store data.
  * Catalog data.
  * Transform data.
  * Analyze data.
  * Visualize data.
  * Clean up resources.
* Hiểu được vai trò của **Amazon S3** trong lưu trữ dữ liệu đầu vào, dữ liệu trung gian và dữ liệu đầu ra.
* Hiểu được vai trò của **Delivery Stream** trong việc thu thập và chuyển dữ liệu đến nơi lưu trữ hoặc phân tích.
* Hiểu được vai trò của **AWS Glue Crawler** trong việc quét dữ liệu, phát hiện schema và tạo metadata trong Data Catalog.
* Hiểu cách dùng **Amazon Athena** để truy vấn dữ liệu trực tiếp trên S3.
* Hiểu cách dùng **Amazon QuickSight** để trực quan hóa dữ liệu và xây dựng dashboard.
* Nắm được vai trò của **Amazon DynamoDB** trong việc cung cấp NoSQL database được quản lý, có khả năng mở rộng cao và phù hợp với ứng dụng serverless.
* Tìm hiểu các mô hình nâng cao của DynamoDB như advanced design patterns, global serverless application và event-driven architecture.
* Hiểu được vai trò của **tagging** và **cost allocation** trong việc theo dõi chi phí tài nguyên AWS.
* Hiểu được cách sử dụng nhiều công cụ khác nhau để thao tác với AWS:

  * AWS Console.
  * CloudShell.
  * SDK.
  * Cloud9.
* Hiểu được vai trò của **AWS Glue DataBrew** trong profiling, cleaning và transforming dữ liệu.
* Hiểu được vai trò của **AWS Glue** trong quy trình ETL dữ liệu.
* Hiểu được vai trò của **Amazon EMR** trong xử lý dữ liệu lớn bằng các framework phân tán.
* Hiểu được vai trò của **Kinesis Data Analytics** trong phân tích dữ liệu streaming.
* Hiểu được vai trò của **AWS Lambda** trong xử lý dữ liệu theo hướng serverless.
* Hiểu được vai trò của **Amazon Redshift** trong xây dựng data warehouse phục vụ phân tích dữ liệu quy mô lớn.
* Ghi nhận một số best practices:

  * Lưu dữ liệu có tổ chức trên S3 để dễ catalog và query.
  * Kiểm tra schema sau khi Glue Crawler chạy.
  * Theo dõi cost và usage khi xử lý dữ liệu.
  * Sử dụng tag để phân loại tài nguyên và hỗ trợ cost allocation.
  * Dọn dẹp S3, Glue jobs, DynamoDB table, QuickSight dataset, Cloud9 và các tài nguyên liên quan sau lab.

**Thực hành với bài lab:**

* Hoàn thành bài lab về **S3, Delivery Stream, Glue Crawler, Athena và QuickSight**:

  * Tạo S3 Bucket.
  * Tạo Delivery Stream.
  * Tạo sample data.
  * Tạo Glue Crawler.
  * Kiểm tra dữ liệu.
  * Lưu output trên S3.
  * Phân tích dữ liệu với Athena.
  * Trực quan hóa dữ liệu bằng QuickSight.
  * Dọn dẹp tài nguyên.
* Hoàn thành bài lab về **Amazon DynamoDB**:

  * Khám phá DynamoDB Console.
  * Kiểm tra table, item, key và cấu hình cơ bản.
  * Thực hành backup.
  * Tìm hiểu advanced design patterns.
  * Tìm hiểu global serverless application.
  * Tìm hiểu event-driven architecture với DynamoDB.
* Hoàn thành bài lab về **database, cost, tagging và usage**:

  * Chuẩn bị database.
  * Xây dựng database.
  * Kiểm tra dữ liệu trong table.
  * Kiểm tra cost.
  * Cấu hình tagging và cost allocation.
  * Kiểm tra usage.
  * Thực hiện query bổ sung.
* Thực hành sử dụng **CloudShell**, **AWS Console** và **SDK** để thao tác với dịch vụ AWS.
* Hoàn thành bài lab về **Cloud9, dataset, S3 và AWS Glue DataBrew**:

  * Tạo Cloud9 Instance.
  * Download dataset.
  * Upload dataset lên S3.
  * Thiết lập DataBrew.
  * Profiling dữ liệu.
  * Clean và transform data.
* Hoàn thành bài lab về **AWS Glue, EMR, Athena, Kinesis Data Analytics, Lambda và Redshift**:

  * Ingest and Store.
  * Catalog Data.
  * Transform Data bằng Glue interactive sessions.
  * Transform Data bằng Glue GUI.
  * Transform Data bằng Glue DataBrew.
  * Transform Data bằng EMR.
  * Analysis with Athena.
  * Analysis with Kinesis Data Analytics.
  * Visualize in QuickSight.
  * Serve with Lambda.
  * Warehouse on Redshift.
* Hoàn thành bài lab về **dashboard**:

  * Build Dashboard.
  * Dashboard Improvements.
  * Create Interactive Dashboard.
* Phác thảo luồng data analytics trên AWS gồm:

  * Data Source.
  * S3.
  * Delivery Stream.
  * Glue Crawler / Data Catalog.
  * Glue / DataBrew / EMR.
  * Athena / Kinesis Data Analytics.
  * QuickSight Dashboard.
  * Lambda.
  * Redshift.
* Ghi chú các điểm cần kiểm tra khi xử lý dữ liệu:

  * S3 path.
  * Schema sau khi crawler chạy.
  * Quyền truy cập dữ liệu.
  * Trạng thái job.
  * Query result.
  * Dashboard dataset.
  * Cost và usage.
* Dọn dẹp tài nguyên như S3 Bucket, Glue Crawler, DynamoDB table, Cloud9 instance, QuickSight dataset/dashboard, Lambda, Redshift và các tài nguyên liên quan sau khi hoàn thành lab.
