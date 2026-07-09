---
title : "Dashboard Access and Validation"
date : 2024-01-01
weight : 7
chapter : false
pre : " <b> 5.4.7. </b> "
---

## Objective

Validate that users can access the dashboard through CloudFront and that browser-side evidence supports the deployment.

The dashboard home screenshot proves that CloudFront can serve the frontend application.

![Dashboard CloudFront home](/fcj_workshop_huyentrang/images/5-Workshop/5.4-Frontend-S3-CloudFront-WAF/w-phu-38-dashboard-cloudfront-home.png)

The HTTP response check confirms that the CloudFront URL returns a successful response.  identifiers in headers are not required for the workshop.

![Curl CloudFront 200](/fcj_workshop_huyentrang/images/5-Workshop/5.4-Frontend-S3-CloudFront-WAF/w-phu-43-curl-cloudfront-200.png)

DevTools static asset evidence confirms that JavaScript and CSS bundles are loading successfully.

![DevTools static assets 200](/fcj_workshop_huyentrang/images/5-Workshop/5.4-Frontend-S3-CloudFront-WAF/w-phu-57-devtools-static-assets-200.png)

The API call evidence is used only to show frontend data-source behavior. If it is mock or replay mode, do not claim live backend telemetry.

![DevTools API call mock or real](/fcj_workshop_huyentrang/images/5-Workshop/5.4-Frontend-S3-CloudFront-WAF/w-phu-58-devtools-api-call-mock-or-real.png)

The console screenshot is useful to confirm there are no critical browser errors after deployment.

![DevTools console warnings](/fcj_workshop_huyentrang/images/5-Workshop/5.4-Frontend-S3-CloudFront-WAF/w-phu-60-devtools-console-warnings.png)

The API and WebSocket CloudFront behavior screenshots are future evidence. Do not claim these paths are production-ready unless the backend and ALB evidence also exist.

![API behavior ](/fcj_workshop_huyentrang/images/5-Workshop/5.4-Frontend-S3-CloudFront-WAF/w-phu-26-api-behavior.png)
![CloudFront origin ALB after config](/fcj_workshop_huyentrang/images/5-Workshop/5.4-Frontend-S3-CloudFront-WAF/w-phu-27-cloudfront-origin-alb-after-config.png)
![CloudFront behavior API after config](/fcj_workshop_huyentrang/images/5-Workshop/5.4-Frontend-S3-CloudFront-WAF/w-phu-28-cloudfront-behavior-api-after-config.png)
![CloudFront behavior WS after config](/fcj_workshop_huyentrang/images/5-Workshop/5.4-Frontend-S3-CloudFront-WAF/w-phu-29-cloudfront-behavior-ws-after-config.png)
![Dashboard header status](/fcj_workshop_huyentrang/images/5-Workshop/5.4-Frontend-S3-CloudFront-WAF/w-phu-39-dashboard-header-status.png)
![Dashboard KPI widgets](/fcj_workshop_huyentrang/images/5-Workshop/5.4-Frontend-S3-CloudFront-WAF/w-phu-40-dashboard-kpi-widgets.png)
![Dashboard alert feed](/fcj_workshop_huyentrang/images/5-Workshop/5.4-Frontend-S3-CloudFront-WAF/w-phu-41-dashboard-alert-feed.png)
![Dashboard event detail modal](/fcj_workshop_huyentrang/images/5-Workshop/5.4-Frontend-S3-CloudFront-WAF/w-phu-42-dashboard-event-detail-modal.png)

