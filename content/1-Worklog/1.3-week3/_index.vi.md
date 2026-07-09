---
title: "Worklog Tuần 3"
date: 2026-05-01
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Mục tiêu tuần 3:

* Hoàn thành nội dung học tập của **Module 02** về **Amazon Virtual Private Cloud** trong chương trình **First Cloud AI Journey**.
* Hiểu vai trò của Amazon VPC trong việc xây dựng môi trường mạng riêng, cô lập và có khả năng kiểm soát truy cập trên AWS.
* Nắm được các thành phần cốt lõi của AWS Networking như **VPC**, **Subnet**, **Route Table**, **Internet Gateway**, **NAT Gateway**, **Security Group**, **Network ACLs** và **EC2 Instance Connect Endpoint**.
* Thực hành xây dựng mô hình mạng AWS từ cơ bản đến nâng cao, bao gồm Custom VPC, public/private subnet, NAT Gateway, Hybrid DNS, VPC Peering và Transit Gateway.
* Hiểu cách kiểm soát lưu lượng mạng bằng Security Group và Network ACLs theo nguyên tắc chỉ mở quyền cần thiết.
* Tìm hiểu cách thiết kế sơ đồ kiến trúc mạng AWS có tính bảo mật, dễ mở rộng và phù hợp với từng nhu cầu triển khai.
* Rèn luyện kỹ năng kiểm tra kết nối, phân tích lỗi mạng, đọc route table và dọn dẹp tài nguyên sau khi hoàn thành bài lab.

### Các nhiệm vụ sẽ được thực hiện trong tuần này:

| Ngày | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| :--- | :--- | :--- | :--- | :--- |
| 1    | - Học Module 02-01: AWS Virtual Private Cloud<br>- Tìm hiểu khái niệm Amazon VPC và vai trò của VPC trong kiến trúc AWS<br>- Học Module 02-02: VPC Security and Multi-VPC Features<br>- Tìm hiểu các cơ chế bảo mật trong VPC và các mô hình kết nối nhiều VPC<br>- Học Module 02-03: VPN, Direct Connect, Load Balancer và Extra Resources<br>- Ghi chú các khái niệm quan trọng liên quan đến kết nối mạng, bảo mật mạng và cân bằng tải<br>- Phân tích sự khác nhau giữa mạng truyền thống và mạng trong môi trường cloud<br>- Phác thảo sơ đồ tổng quan về network layer trong AWS | 01/05/2026 | 01/05/2026 | https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i |
| 2    | - Làm Lab03-01: Start with Amazon VPC and AWS VPN Site-to-Site Introduction<br>- Làm Lab03-01.1: Subnets<br>- Làm Lab03-01.2: Route Table<br>- Làm Lab03-01.3: Internet Gateway IGW<br>- Làm Lab03-01.4: NAT Gateway<br>- Làm Lab03-02.1: Security Group<br>- Làm Lab03-02.2: Network ACLs<br>- Làm Lab03-02.3: VPC Resource Map<br>- Ghi chú vai trò của từng thành phần trong mô hình VPC<br>- So sánh Security Group và Network ACLs theo phạm vi hoạt động, trạng thái và cách áp dụng rule | 04/05/2026 | 04/05/2026 | https://000003.awsstudygroup.com/ |
| 3    | - Làm Lab03-03.1: Create VPC<br>- Làm Lab03-03.2: Create Subnet<br>- Làm Lab03-03.3: Create an Internet Gateway<br>- Làm Lab03-03.4: Create Route Table for Outbound Internet Routing via Internet Gateway<br>- Làm Lab03-03.5: Create Security Groups<br>- Làm Lab03-04.1: Create EC2 Instances in Subnets<br>- Làm Lab03-04.2: Test Connection<br>- Làm Lab03-04.3: Create NAT Gateway<br>- Làm Lab03-04.5: EC2 Instance Connect Endpoint<br>- Kiểm tra kết nối giữa các EC2 Instance trong public subnet và private subnet<br>- Ghi chú các lỗi thường gặp khi cấu hình routing, security group hoặc NAT Gateway<br>- Bổ sung lưu ý về chi phí khi sử dụng NAT Gateway và tài nguyên EC2 | 05/05/2026 | 05/05/2026 | https://000003.awsstudygroup.com/ |
| 4    | - Làm Lab10-01: Set up Hybrid DNS with Route 53 Resolver Introduction<br>- Làm Lab10-02.1: Generate Key Pair<br>- Làm Lab10-02.2: Initialize CloudFormation Template<br>- Làm Lab10-02.3: Configure Security Group<br>- Làm Lab10-03: Connect to RDGW<br>- Làm Lab10-05: Set up DNS<br>- Làm Lab10-05.1: Create Route 53 Outbound Endpoint<br>- Làm Lab10-05.2: Create Route 53 Resolver Rules<br>- Làm Lab10-05.3: Create Route 53 Inbound Endpoints<br>- Làm Lab10-05.4: Test Results<br>- Làm Lab10-06: Clean up Resources<br>- Tìm hiểu vai trò của Route 53 Resolver trong mô hình Hybrid DNS<br>- Ghi chú cách DNS hỗ trợ kết nối giữa môi trường AWS và môi trường on-premises | 06/05/2026 | 06/05/2026 | https://000010.awsstudygroup.com/ |
| 5    | - Làm Lab19-01: Set up VPC Peering Introduction<br>- Làm Lab19-02.1: Initialize CloudFormation Templates<br>- Làm Lab19-02.2: Create Security Group<br>- Làm Lab19-02.3: Create EC2 Instance<br>- Làm Lab19-03: Update Network ACLs<br>- Làm Lab19-04: Create a Peering Connection<br>- Làm Lab19-05: Configure Route Tables<br>- Làm Lab19-06: Enable Cross-Peer DNS<br>- Làm Lab19-07: Clean up Resources<br>- Làm Lab20-01: Set up AWS Transit Gateway Introduction<br>- Làm Lab20-02: Preparation Steps<br>- Làm Lab20-03: Create Transit Gateway<br>- Làm Lab20-04: Create Transit Gateway Attachments<br>- Làm Lab20-05: Create Transit Gateway Route Tables<br>- Làm Lab20-06: Add Transit Gateway Routes to VPC Route Tables<br>- Làm Lab20-07: Clean up Resources<br>- So sánh VPC Peering và Transit Gateway theo khả năng mở rộng, cách định tuyến và trường hợp sử dụng<br>- Hoàn thiện sơ đồ kiến trúc mạng AWS tổng hợp cho tuần 3<br>- Dọn dẹp tài nguyên để tránh phát sinh chi phí | 07/05/2026 | 07/05/2026 | https://000019.awsstudygroup.com/<br><br>https://000020.awsstudygroup.com/ |

### Kết quả đạt được tuần 3:

**Tổng quát:**

Trong tuần 3, tôi đã hoàn thành nội dung học tập của **Module 02** về **Amazon Virtual Private Cloud**. Nội dung tuần này giúp tôi hiểu rõ hơn vai trò của VPC trong việc xây dựng một môi trường mạng riêng trên AWS, nơi các tài nguyên có thể được phân tách, kiểm soát truy cập và kết nối theo đúng nhu cầu của hệ thống.

Ngoài việc học module và thực hành lab, tôi còn bổ sung thêm phần phân tích kiến trúc mạng, so sánh các mô hình kết nối, kiểm tra lỗi cấu hình mạng và ghi chú các lưu ý về bảo mật, routing và chi phí. Qua đó, tôi có cái nhìn thực tế hơn về cách thiết kế network layer trong một hệ thống cloud, thay vì chỉ dừng lại ở việc tạo tài nguyên theo từng bước lab.

**Lý thuyết đã học:**

* Hiểu được vai trò của **Amazon VPC** trong việc tạo môi trường mạng riêng, cô lập và có khả năng kiểm soát truy cập trên AWS.
* Nắm được các thành phần quan trọng trong kiến trúc mạng AWS:

  * **VPC**: không gian mạng riêng dùng để triển khai tài nguyên AWS.
  * **Subnet**: chia nhỏ VPC thành các vùng mạng để tổ chức tài nguyên.
  * **Route Table**: điều hướng lưu lượng mạng giữa các subnet, gateway và các kết nối khác.
  * **Internet Gateway**: cho phép tài nguyên trong public subnet truy cập Internet.
  * **NAT Gateway**: cho phép tài nguyên trong private subnet truy cập Internet theo chiều outbound mà không cần public IP.
  * **Security Group**: kiểm soát traffic ở cấp instance hoặc network interface.
  * **Network ACLs**: kiểm soát traffic ở cấp subnet.
  * **EC2 Instance Connect Endpoint**: hỗ trợ kết nối đến EC2 mà không cần mở truy cập public trực tiếp.
  * **VPC Resource Map**: hỗ trợ quan sát trực quan các thành phần mạng trong VPC.
* Phân biệt được **Security Group** và **Network ACLs**:

  * Security Group hoạt động ở cấp instance hoặc elastic network interface.
  * Network ACLs hoạt động ở cấp subnet.
  * Security Group có tính **stateful**.
  * Network ACLs có tính **stateless**.
  * Security Group thường được dùng để kiểm soát truy cập trực tiếp đến tài nguyên.
  * Network ACLs phù hợp để tạo lớp kiểm soát bổ sung ở cấp subnet.
* Hiểu được vai trò của **Route Table** trong việc quyết định đường đi của traffic.
* Hiểu được mô hình **public subnet** và **private subnet**:

  * Public subnet thường chứa tài nguyên cần truy cập từ Internet như bastion host, load balancer hoặc public EC2.
  * Private subnet thường chứa backend server, database hoặc các tài nguyên không nên public trực tiếp ra Internet.
* Nắm được các mô hình kết nối mở rộng trong AWS:

  * **VPN Site-to-Site**: kết nối mạng on-premises với AWS thông qua VPN.
  * **AWS Direct Connect**: kết nối riêng từ hệ thống bên ngoài vào AWS với độ ổn định cao hơn.
  * **VPC Peering**: kết nối trực tiếp giữa hai VPC để tài nguyên giao tiếp bằng private IP.
  * **Transit Gateway**: mô hình trung tâm giúp kết nối nhiều VPC và hệ thống mạng khác nhau dễ quản lý hơn.
  * **Hybrid DNS**: hỗ trợ phân giải tên miền giữa AWS và hệ thống on-premises.
* Hiểu được vai trò của **Route 53 Resolver** trong mô hình Hybrid DNS.
* So sánh được **VPC Peering** và **Transit Gateway**:

  * VPC Peering phù hợp khi số lượng VPC ít và mô hình kết nối đơn giản.
  * Transit Gateway phù hợp khi có nhiều VPC, nhiều kết nối và cần mô hình mạng trung tâm dễ mở rộng.
* Nắm được một số best practices khi thiết kế network layer:

  * Không public tài nguyên không cần thiết.
  * Chỉ mở port cần dùng trong Security Group.
  * Tách public subnet và private subnet rõ ràng.
  * Kiểm tra route table khi gặp lỗi kết nối.
  * Dọn dẹp NAT Gateway, EC2 và các tài nguyên mạng sau khi thực hành để tránh phát sinh chi phí.

**Thực hành với bài lab:**

* Hoàn thành các bài lab nền tảng về Amazon VPC:

  * **Lab03-01:** Start with Amazon VPC and AWS VPN Site-to-Site Introduction.
  * **Lab03-01.1:** Subnets.
  * **Lab03-01.2:** Route Table.
  * **Lab03-01.3:** Internet Gateway.
  * **Lab03-01.4:** NAT Gateway.
  * **Lab03-02.1:** Security Group.
  * **Lab03-02.2:** Network ACLs.
  * **Lab03-02.3:** VPC Resource Map.
* Thực hành tạo và cấu hình các thành phần mạng cơ bản trong AWS:

  * Create VPC.
  * Create Subnet.
  * Create an Internet Gateway.
  * Create Route Table for Outbound Internet Routing via Internet Gateway.
  * Create Security Groups.
  * Create EC2 Instances in Subnets.
  * Test Connection.
  * Create NAT Gateway.
  * EC2 Instance Connect Endpoint.
* Thực hành kiểm tra kết nối giữa các tài nguyên:

  * Kiểm tra kết nối từ public subnet ra Internet.
  * Kiểm tra kết nối từ private subnet thông qua NAT Gateway.
  * Kiểm tra kết nối đến EC2 Instance.
  * Kiểm tra route table khi traffic không đi đúng hướng.
  * Kiểm tra Security Group và Network ACLs khi kết nối bị chặn.
* Thực hành cấu hình **Hybrid DNS với Route 53 Resolver**:

  * Generate Key Pair.
  * Initialize CloudFormation Template.
  * Configure Security Group.
  * Connect to RDGW.
  * Set up DNS.
  * Create Route 53 Outbound Endpoint.
  * Create Route 53 Resolver Rules.
  * Create Route 53 Inbound Endpoints.
  * Test Results.
  * Clean up Resources.
* Thực hành cấu hình **VPC Peering**:

  * Initialize CloudFormation Templates.
  * Create Security Group.
  * Create EC2 Instance.
  * Update Network ACLs.
  * Create a Peering Connection.
  * Configure Route Tables.
  * Enable Cross-Peer DNS.
  * Clean up Resources.
* Thực hành cấu hình **AWS Transit Gateway**:

  * Preparation Steps.
  * Create Transit Gateway.
  * Create Transit Gateway Attachments.
  * Create Transit Gateway Route Tables.
  * Add Transit Gateway Routes to VPC Route Tables.
  * Clean up Resources.
* Bổ sung kỹ năng phân tích và vận hành sau khi làm lab:

  * Đọc yêu cầu bài lab trước khi cấu hình.
  * Thực hiện từng bước trên AWS Console.
  * Ghi chú vai trò của từng tài nguyên được tạo.
  * Quan sát kết quả sau mỗi bước cấu hình.
  * Ghi nhận lỗi phát sinh nếu có.
  * So sánh mô hình VPC Peering và Transit Gateway.
  * Phác thảo sơ đồ kiến trúc mạng sau khi hoàn thành lab.
  * Dọn dẹp tài nguyên như EC2, NAT Gateway, Route 53 Resolver Endpoint, VPC Peering, Transit Gateway và các tài nguyên liên quan để tránh phát sinh chi phí.
