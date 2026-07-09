---
title : "Dashboard Access và Validation"
date : 2024-01-01
weight : 7
chapter : false
pre : " <b> 5.4.7. </b> "
---

## Mục tiêu

Validate người dùng có thể truy cập dashboard qua CloudFront và browser-side evidence đủ chứng minh deployment hoạt động.

Dashboard home screenshot chứng minh CloudFront phục vụ được frontend application.

![Dashboard CloudFront home](/fcj_workshop_huyentrang/images/5-Workshop/5.4-Frontend-S3-CloudFront-WAF/w-phu-38-dashboard-cloudfront-home.png)

HTTP response check xác nhận CloudFront URL trả về response thành công. Các identifier trong header đã redact không cần hiển thị trong workshop.

![Curl CloudFront 200](/fcj_workshop_huyentrang/images/5-Workshop/5.4-Frontend-S3-CloudFront-WAF/w-phu-43-curl-cloudfront-200.png)

DevTools static asset evidence xác nhận JavaScript và CSS bundle load thành công.

![DevTools static assets 200](/fcj_workshop_huyentrang/images/5-Workshop/5.4-Frontend-S3-CloudFront-WAF/w-phu-57-devtools-static-assets-200.png)

API call evidence chỉ dùng để mô tả data-source behavior của frontend. Nếu ảnh là mock hoặc replay mode, không claim live backend telemetry.

![DevTools API call mock or real](/fcj_workshop_huyentrang/images/5-Workshop/5.4-Frontend-S3-CloudFront-WAF/w-phu-58-devtools-api-call-mock-or-real.png)

Console screenshot giúp xác nhận không có lỗi browser nghiêm trọng sau khi deploy.

![DevTools console warnings](/fcj_workshop_huyentrang/images/5-Workshop/5.4-Frontend-S3-CloudFront-WAF/w-phu-60-devtools-console-warnings.png)

Các screenshot API và WebSocket CloudFront behavior là future evidence. Không claim các path này production-ready nếu chưa có backend và ALB evidence tương ứng.

![API behavior ](/fcj_workshop_huyentrang/images/5-Workshop/5.4-Frontend-S3-CloudFront-WAF/w-phu-26-api-behavior.png)
![CloudFront origin ALB sau khi config](/fcj_workshop_huyentrang/images/5-Workshop/5.4-Frontend-S3-CloudFront-WAF/w-phu-27-cloudfront-origin-alb-after-config.png)
![CloudFront behavior API sau khi config](/fcj_workshop_huyentrang/images/5-Workshop/5.4-Frontend-S3-CloudFront-WAF/w-phu-28-cloudfront-behavior-api-after-config.png)
![CloudFront behavior WS sau khi config](/fcj_workshop_huyentrang/images/5-Workshop/5.4-Frontend-S3-CloudFront-WAF/w-phu-29-cloudfront-behavior-ws-after-config.png)
![Dashboard header status](/fcj_workshop_huyentrang/images/5-Workshop/5.4-Frontend-S3-CloudFront-WAF/w-phu-39-dashboard-header-status.png)
![Dashboard KPI widgets](/fcj_workshop_huyentrang/images/5-Workshop/5.4-Frontend-S3-CloudFront-WAF/w-phu-40-dashboard-kpi-widgets.png)
![Dashboard alert feed](/fcj_workshop_huyentrang/images/5-Workshop/5.4-Frontend-S3-CloudFront-WAF/w-phu-41-dashboard-alert-feed.png)
![Dashboard event detail modal](/fcj_workshop_huyentrang/images/5-Workshop/5.4-Frontend-S3-CloudFront-WAF/w-phu-42-dashboard-event-detail-modal.png)

