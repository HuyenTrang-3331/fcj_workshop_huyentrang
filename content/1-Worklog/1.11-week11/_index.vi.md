---
title: "Worklog Tuần 11"
date: 2026-06-12
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Mục tiêu tuần 11:

- Tìm hiểu các dịch vụ AWS phục vụ giám sát, ghi log, bảo mật và phát hiện rủi ro trong quá trình vận hành hệ thống.
- Ôn tập vai trò của **Amazon CloudWatch**, **AWS CloudTrail**, **AWS Config**, **Amazon GuardDuty** và **AWS Security Hub**.
- Hiểu cách theo dõi hoạt động hệ thống thông qua **metrics**, **logs**, **alarms** và **dashboards**.
- Tìm hiểu cách phát hiện hành vi bất thường, rủi ro bảo mật và các vấn đề cấu hình trong môi trường AWS.
- Rèn luyện kỹ năng kiểm tra log, đánh giá cảnh báo, phân loại mức độ nghiêm trọng và đề xuất hướng xử lý sự cố.
- Phân tích vai trò của monitoring, logging và security trong một kiến trúc AWS thực tế.
- Tổng hợp kiến thức phục vụ báo cáo tuần và chuẩn bị nội dung trình bày cuối giai đoạn học tập.

### Các nhiệm vụ sẽ được thực hiện trong tuần này:

| Ngày | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| :--- | :--- | :--- | :--- | :--- |
| 1    | - Tìm hiểu Amazon CloudWatch<br>- Ghi chú vai trò của Metrics, Logs, Alarms và Dashboard<br>- Tìm hiểu cách CloudWatch hỗ trợ giám sát tài nguyên AWS<br>- Phân tích cách CloudWatch được dùng để theo dõi EC2, RDS, Lambda và các dịch vụ vận hành trong hệ thống<br>- Ghi chú các tình huống cần tạo alarm để cảnh báo sớm sự cố | 26/06/2026 | 26/06/2026 | https://docs.aws.amazon.com/cloudwatch/ |
| 2    | - Tìm hiểu AWS CloudTrail<br>- Ghi chú vai trò của CloudTrail trong việc theo dõi API calls và hoạt động người dùng<br>- Phân biệt CloudWatch Logs và CloudTrail Logs<br>- Phân tích cách CloudTrail hỗ trợ audit, kiểm tra hành động quản trị và truy vết sự kiện trong tài khoản AWS<br>- Ghi chú các tình huống cần kiểm tra CloudTrail khi phát hiện thay đổi bất thường | 29/06/2026 | 29/06/2026 | https://docs.aws.amazon.com/cloudtrail/ |
| 3    | - Tìm hiểu Amazon GuardDuty và AWS Security Hub<br>- Ghi chú cách các dịch vụ này hỗ trợ phát hiện rủi ro bảo mật<br>- Tìm hiểu khái niệm finding, severity và remediation<br>- Phân tích cách GuardDuty phát hiện hành vi bất thường dựa trên log và threat intelligence<br>- Ghi chú cách Security Hub tổng hợp findings từ nhiều dịch vụ bảo mật khác nhau | 30/06/2026 | 30/06/2026 | https://docs.aws.amazon.com/guardduty/ |
| 4    | - Tìm hiểu AWS Config và kiểm tra compliance của tài nguyên<br>- Ghi chú vai trò của rule, resource inventory và configuration history<br>- Liên hệ với việc quản trị hệ thống cloud trong thực tế<br>- Phân tích cách AWS Config hỗ trợ theo dõi thay đổi cấu hình và phát hiện tài nguyên không tuân thủ<br>- Ghi chú một số ví dụ về compliance rule thường dùng trong quản trị AWS | 01/07/2026 | 01/07/2026 | https://docs.aws.amazon.com/config/ |
| 5    | - Tổng hợp kiến thức monitoring và security trên AWS<br>- Ghi chú quy trình kiểm tra log, cảnh báo và xử lý lỗi cơ bản<br>- Hoàn thiện nội dung báo cáo tuần 11<br>- Xây dựng checklist kiểm tra hệ thống dựa trên log, metric, alarm, finding và compliance<br>- Chuẩn bị nội dung trình bày về monitoring, logging và security trong AWS | 02/07/2026 | 02/07/2026 | https://aws.amazon.com/security/ |

### Kết quả đạt được tuần 11:

**Tổng quát:**

Trong tuần 11, tôi đã tập trung tìm hiểu nhóm dịch vụ hỗ trợ **monitoring**, **logging**, **security** và **risk detection** trên AWS. Nội dung tuần này giúp tôi hiểu rõ hơn cách theo dõi trạng thái hệ thống, ghi nhận hoạt động người dùng, phát hiện hành vi bất thường và kiểm tra mức độ tuân thủ của tài nguyên AWS.

Ngoài việc ôn tập lý thuyết, tôi còn bổ sung thêm phần phân tích quy trình vận hành thực tế, bao gồm cách kiểm tra log, đánh giá cảnh báo, phân loại mức độ nghiêm trọng của finding và đề xuất hướng xử lý ban đầu khi có sự cố về hiệu năng hoặc bảo mật.

**Lý thuyết đã học:**

- Hiểu được vai trò của **monitoring** và **logging** trong vận hành hệ thống AWS.
- Nắm được vai trò của **Amazon CloudWatch** trong việc giám sát tài nguyên và ứng dụng.
- Hiểu các thành phần chính của CloudWatch:

  - Metrics.
  - Logs.
  - Alarms.
  - Dashboards.
- Biết cách CloudWatch hỗ trợ theo dõi tình trạng của EC2, RDS, Lambda và các dịch vụ AWS khác.
- Hiểu được vai trò của **AWS CloudTrail** trong việc ghi nhận API calls, hoạt động người dùng và hành động quản trị trên tài khoản AWS.
- Phân biệt được **CloudWatch** và **CloudTrail**:

  - CloudWatch dùng để giám sát hiệu năng, log ứng dụng và cảnh báo hệ thống.
  - CloudTrail dùng để ghi nhận hành động người dùng, API calls và hoạt động quản trị tài khoản.
- Hiểu được vai trò của **Amazon GuardDuty** trong việc phát hiện hành vi bất thường, truy cập đáng ngờ hoặc rủi ro bảo mật.
- Hiểu được vai trò của **AWS Security Hub** trong việc tổng hợp, đánh giá và quản lý findings từ nhiều dịch vụ bảo mật.
- Nắm được các khái niệm cơ bản:

  - Finding.
  - Severity.
  - Remediation.
  - Threat Detection.
  - Compliance.
- Hiểu được vai trò của **AWS Config** trong việc theo dõi cấu hình tài nguyên, kiểm tra compliance và lưu lại lịch sử thay đổi cấu hình.
- Ghi nhận một số best practices:

  - Thiết lập alarm cho các tài nguyên quan trọng.
  - Kiểm tra CloudTrail khi có thay đổi bất thường trong tài khoản.
  - Theo dõi findings từ GuardDuty và Security Hub.
  - Sử dụng AWS Config để kiểm tra tài nguyên có tuân thủ chính sách hay không.
  - Phân loại cảnh báo theo mức độ nghiêm trọng trước khi xử lý.
  - Kết hợp monitoring, logging và security để vận hành hệ thống an toàn hơn.

**Thực hành và tổng hợp:**

- Tổng hợp vai trò của các dịch vụ monitoring và security trên AWS:

  - Amazon CloudWatch.
  - AWS CloudTrail.
  - AWS Config.
  - Amazon GuardDuty.
  - AWS Security Hub.
- Thực hành tư duy kiểm tra hệ thống dựa trên:

  - Metric.
  - Log.
  - Alarm.
  - Finding.
  - Severity.
  - Compliance rule.
- Phân tích quy trình kiểm tra sự cố cơ bản:

  - Xác định dịch vụ bị ảnh hưởng.
  - Kiểm tra CloudWatch metrics và alarms.
  - Xem log liên quan đến ứng dụng hoặc tài nguyên.
  - Kiểm tra CloudTrail để xác định hành động thay đổi cấu hình.
  - Kiểm tra findings từ GuardDuty hoặc Security Hub nếu nghi ngờ rủi ro bảo mật.
  - Đề xuất hướng xử lý hoặc remediation phù hợp.
- Ghi chú các trường hợp cần quan tâm trong thực tế:

  - EC2 CPU tăng cao bất thường.
  - RDS có kết nối hoặc hiệu năng không ổn định.
  - Lambda phát sinh lỗi khi chạy.
  - IAM User hoặc Role có hành động bất thường.
  - Tài nguyên AWS bị cấu hình sai hoặc không tuân thủ policy.
- Xây dựng checklist kiểm tra monitoring và security:

  - CloudWatch Alarm đã được cấu hình chưa?
  - Log có được lưu và dễ truy xuất không?
  - CloudTrail có ghi nhận đầy đủ hoạt động tài khoản không?
  - GuardDuty/Security Hub có phát hiện finding nghiêm trọng không?
  - AWS Config có phát hiện tài nguyên không compliance không?
  - Có hướng xử lý hoặc remediation cho cảnh báo quan trọng không?
- Rèn luyện kỹ năng đọc log, đánh giá cảnh báo và đề xuất hướng xử lý ban đầu khi có sự cố.
- Hoàn thành ghi chú học tập về CloudWatch, CloudTrail, GuardDuty, Security Hub và AWS Config.
