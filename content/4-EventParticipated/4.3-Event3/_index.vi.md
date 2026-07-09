---
title: "Event 3"
date: 2026-06-09
weight: 3
chapter: false
pre: " <b> 4.3. </b> "
---


# Bài Thu Hoạch: "Meetup Event"

### Mục Đích Của Sự Kiện

Sự kiện Meetup ngày 06/06/2026 được tổ chức như một buổi chia sẻ kiến thức dành cho cộng đồng công nghệ. Sự kiện nhằm giúp người tham dự khám phá các chủ đề thực tế trong phát triển phần mềm, điện toán đám mây, an ninh mạng, trí tuệ nhân tạo, hệ thống tri thức dựa trên đồ thị và phát triển nghề nghiệp Cloud/DevOps.

Thông qua các bài trình bày khác nhau, người tham dự đã tìm hiểu cách các công nghệ hiện đại được áp dụng vào các hệ thống thực tế, bao gồm Docker để triển khai ứng dụng, AWS WebSocket để giao tiếp đa người chơi, AWS WAF kết hợp với Machine Learning để phát hiện tấn công mạng, AWS Neptune cho GraphRAG và lộ trình nghề nghiệp từ IT Helpdesk đến Cloud/DevOps.

**Thông tin chung:**

* **Thời gian:** 09:00, ngày 06 tháng 06 năm 2026
* **Địa điểm:** Tầng 26, tòa nhà Bitexco, số 02 đường Hải Triều, phường Sài Gòn, thành phố Hồ Chí Minh
* **Vai trò:** Người tham dự

### Danh Sách Diễn Giả

* **Nguyễn Quốc Bảo** – Multiplayer in the Cloud: Connecting Godot Clients with AWS WebSockets
* **Bảo Huỳnh** – Docker: A Containerization Technology
* **Việt Phát** – AWS Neptune for Building a Graph Knowledge Base for GraphRAG
* **Lê Hoàng Gia Đại** – Combining AWS WAF with Machine Learning for Cyber Attack Detection on AWS
* **Trần Trung Vinh** – From IT Helpdesk to Senior Sysadmin: First Steps Toward Cloud and DevOps

### Nội Dung Nổi Bật

#### Docker – A Containerization Technology

Phiên chia sẻ này giới thiệu về Docker và công nghệ container hóa. Diễn giả đã giải thích sự khác biệt giữa máy ảo truyền thống và container, cho thấy lý do tại sao Docker được sử dụng rộng rãi trong phát triển phần mềm hiện đại.

Docker giúp đóng gói các ứng dụng cùng với các phụ thuộc và môi trường cần thiết để chúng có thể chạy nhất quán trên các hệ thống khác nhau. Các khái niệm chính như Docker Image, Docker Container, Dockerfile, các lớp image, bộ nhớ đệm khi build và các lệnh Docker cơ bản đã được giới thiệu.

Phiên này cũng thảo luận về các trường hợp sử dụng Docker trong đường ống CI/CD, microservices, môi trường phát triển/kiểm thử, ứng dụng cloud-native và hiện đại hóa hệ thống cũ.

#### Multiplayer in the Cloud: Connecting Godot Clients with AWS WebSockets

Phiên này tập trung vào việc xây dựng hệ thống trò chơi đa người chơi dựa trên đám mây bằng cách sử dụng Godot và AWS WebSocket. Diễn giả đã giới thiệu các phương pháp kết nối mạng như UDP/ENet, WebSocket và HTTP Polling.

WebSocket được trình bày như một giải pháp phù hợp cho các trò chơi turn-based, hệ thống sảnh (lobby), tính năng trò chuyện và các trò chơi nhỏ thời gian thực nhẹ nhàng. Kiến trúc bao gồm Godot Client, API Gateway WebSocket, AWS Lambda, DynamoDB và CloudWatch.

DynamoDB được sử dụng để lưu trữ thông tin kết nối và trạng thái người chơi, trong khi Lambda xử lý việc kết nối, ngắt kết nối, ghép trận, lựa chọn trò chơi và kết quả. Bản demo cho thấy hai máy khách kết nối, ghép trận, gửi lựa chọn Kéo-Búa-Bao và nhận kết quả trong thời gian thực.

#### Combining AWS WAF with Machine Learning for Cyber Attack Detection on AWS

Phiên này trình bày cách kết hợp AWS WAF với Machine Learning để phát hiện các hành vi tấn công mạng. AWS WAF bảo vệ các ứng dụng web khỏi các cuộc tấn công phổ biến bằng các cơ chế dựa trên quy tắc (rule-based) và chữ ký (signature-based).

Tuy nhiên, các quy tắc cố định có thể không phát hiện được các mẫu tấn công mới hoặc phức tạp. Do đó, Machine Learning có thể được sử dụng để hỗ trợ phát hiện bất thường và cải thiện giám sát an ninh. Diễn giả đã giới thiệu mô hình Hệ thống Phát hiện Xâm nhập Mạng (NIDS) sử dụng bộ dữ liệu CSE-CIC-IDS2018.

Phiên này cũng đề cập đến các công cụ và dịch vụ như Python, scikit-learn, pandas, AWS WAF, Amazon S3, AWS Lambda, Kinesis Data Firehose, GuardDuty, Security Hub và CloudWatch. Các chủ đề quan trọng bao gồm bảng điều khiển thời gian thực, trực quan hóa cảnh báo, mất cân bằng lớp dữ liệu, dương tính giả và tối ưu hóa mô hình.

#### AWS Neptune for Building a Graph Knowledge Base for GraphRAG

Phiên này giới thiệu về GraphRAG và việc sử dụng AWS Neptune để xây dựng cơ sở tri thức đồ thị. Diễn giả trước tiên giải thích về Retrieval-Augmented Generation (RAG), giúp các mô hình ngôn ngữ lớn truy xuất kiến thức bên ngoài trước khi tạo câu trả lời.

RAG truyền thống hữu ích nhưng có thể bị hạn chế khi các câu hỏi yêu cầu hiểu mối quan hệ giữa nhiều thực thể. GraphRAG cải thiện điều này bằng cách sử dụng đồ thị để lưu trữ các thực thể và mối quan hệ, hỗ trợ suy luận nhiều bước tốt hơn.

Diễn giả đã trình bày hai phương pháp triển khai: sử dụng Amazon Bedrock Knowledge Bases với Neptune Analytics, hoặc xây dựng một đường ống tùy chỉnh với các công cụ như LlamaIndex và lưu trữ đồ thị trong Amazon Neptune.

#### From IT Helpdesk to Senior Sysadmin: First Steps Toward Cloud and DevOps

Phiên này chia sẻ về hành trình nghề nghiệp thực tế từ IT Helpdesk đến Senior Sysadmin và sau đó hướng tới Cloud/DevOps. Diễn giả giải thích rằng Helpdesk là một nền tảng quan trọng để học cách khắc phục sự cố, giao tiếp với người dùng, xử lý sự cố và vận hành hệ thống IT.

Khi các chuyên gia chuyển sang vai trò Quản trị viên hệ thống (System Administrator), họ cần các kỹ năng mạnh mẽ hơn về quản lý máy chủ, mạng, giám sát, vá lỗi bảo mật, sao lưu và tự động hóa.

Đối với Cloud/DevOps, diễn giả nhấn mạnh vào tư duy đám mây, AWS, khả năng mở rộng đàn hồi, mô hình trả tiền theo mức sử dụng, các dịch vụ được quản lý, Cơ sở hạ tầng dưới dạng mã (IaC) với Terraform, kiểm soát phiên bản, CI/CD, Docker, giám sát và văn hóa DevOps. Phiên chia sẻ cũng nhấn mạnh tầm quan trọng của các dự án thực tế, portfolio và thực hành thực tế.

### Những Gì Học Được

Thông qua sự kiện, tôi đã rút ra được một số bài học quan trọng:

* **Docker và tính nhất quán khi triển khai:** Docker giúp các ứng dụng chạy nhất quán trên các môi trường khác nhau và hỗ trợ các quy trình triển khai hiện đại.
* **Kiến trúc đám mây thời gian thực:** AWS WebSocket, Lambda và DynamoDB có thể được sử dụng để xây dựng các ứng dụng đa người chơi hoặc thời gian thực đơn giản.
* **Tư duy bảo mật phân lớp:** AWS WAF có thể chặn các mối đe dọa đã biết, trong khi Machine Learning có thể giúp phát hiện các hành vi bất thường.
* **Giá trị của GraphRAG:** GraphRAG hữu ích cho các hệ thống cần hiểu mối quan hệ giữa các thực thể, không chỉ là truy xuất văn bản tương tự.
* **Lộ trình sự nghiệp Cloud/DevOps:** Nền tảng vững chắc về khắc phục sự cố, mạng, máy chủ, Docker và tự động hóa là quan trọng trước khi đi sâu vào Cloud và DevOps.

### Ứng Dụng Vào Công Việc

Kiến thức từ buổi Meetup này có thể được áp dụng vào việc học tập, các dự án cá nhân và phát triển nghề nghiệp của tôi.

Tôi có thể sử dụng Docker để container hóa các ứng dụng web, API và cơ sở dữ liệu để các dự án dễ dàng chạy và chia sẻ với các thành viên trong nhóm. Phiên AWS WebSocket mang lại cho tôi ý tưởng xây dựng các tính năng trò chuyện, hệ thống sảnh hoặc các trò chơi nhỏ đa người chơi đơn giản bằng các dịch vụ đám mây không máy chủ (serverless).

Phiên AWS WAF và Machine Learning giúp tôi cải thiện tư duy bảo mật khi thiết kế các ứng dụng web. Tôi nên xem xét việc lọc yêu cầu, ghi nhật ký, giám sát và phát hiện bất thường thay vì chỉ tập trung vào các tính năng của ứng dụng.

Phiên AWS Neptune và GraphRAG mang lại cho tôi hướng đi để xây dựng các hệ thống dựa trên tri thức, chatbot nội bộ, hệ thống trả lời câu hỏi trên tài liệu hoặc các công cụ phân tích mối quan hệ dữ liệu.

Phiên nghề nghiệp Cloud/DevOps giúp tôi lập kế hoạch lộ trình học tập rõ ràng hơn bằng cách tập trung vào Linux, mạng, Git, Docker, kiến thức cơ bản về AWS, CI/CD, giám sát và Cơ sở hạ tầng dưới dạng mã.

### Trải Nghiệm Trong Sự Kiện

Tham gia buổi Meetup ngày 06/06/2026 là một trải nghiệm quý giá vì nó giúp tôi mở rộng tầm nhìn về các công nghệ hiện đại và các ứng dụng thực tế của chúng.

#### Học hỏi từ các diễn giả

Tôi đã chủ động lắng nghe các bài thuyết trình, ghi chép các khái niệm quan trọng và tóm tắt các ý chính sau sự kiện. Các diễn giả đã chia sẻ kiến thức thực tế về triển khai phần mềm, kiến trúc đám mây, an ninh mạng, hệ thống tri thức AI và phát triển nghề nghiệp IT.

#### Tiếp cận các công nghệ đa dạng

Sự kiện bao gồm nhiều chủ đề quan trọng, bao gồm Docker, AWS WebSocket, AWS WAF, Machine Learning, AWS Neptune, GraphRAG và DevOps. Điều này giúp tôi hiểu rằng các hệ thống hiện đại thường đòi hỏi nhiều công nghệ hoạt động cùng nhau.

#### Tư duy hệ thống thực tế

Các phiên chia sẻ cho thấy một hệ thống tốt không chỉ chạy thành công mà còn phải ổn định, bảo mật, có khả năng mở rộng, dễ bảo trì và phù hợp với nhu cầu thực tế. Điều này giúp tôi cải thiện tư duy về thiết kế và triển khai hệ thống.

#### Định hướng nghề nghiệp rõ ràng

Phiên chia sẻ về lộ trình từ IT Helpdesk đến Cloud/DevOps giúp tôi hiểu rằng sự phát triển nghề nghiệp đòi hỏi nền tảng vững chắc, các dự án thực tế, kinh nghiệm thực hành và học hỏi không ngừng.


> Nhìn chung, Meetup 06/06/2026 là một sự kiện thực tế và ý nghĩa. Nó cung cấp kiến thức hữu ích về triển khai phần mềm, kiến trúc đám mây, an ninh mạng, GraphRAG và phát triển nghề nghiệp Cloud/DevOps. Sau sự kiện, tôi cảm thấy có động lực hơn để tiếp tục học tập, xây dựng các dự án cá nhân và xác định lộ trình nghề nghiệp rõ ràng hơn trong lĩnh vực công nghệ thông tin.
