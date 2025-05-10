# TheHive Project

# Task 1: Room Outline
# Task 2: Introduction
Dự án TheHive vận hành dưới 3 tính năng chính:
- **Collaborate**: Nhiều nhà phân tích từ một tổ chức có thể làm việc cùng nhau trong cùng một trường hợp. Thông qua khả năng phát trực tiếp của nó, mọi người đều có thể theo dõi các trường hợp trong thời gian thực.
- **Elaborate**: Điều tra tương ứng với các trường hợp. Chi tiết của từng trường hợp có thể được chia thành các tác vụ liên quan, có thể được tạo từ đầu hoặc thông qua công cụ mẫu. Ngoài ra, các nhà phân tích có thể ghi lại tiến trình của họ, đính kèm các bằng chứng giả và phân công nhiệm vụ một cách dễ dàng.
- **Act**: Quá trình phân loại nhanh có thể được hỗ trợ bằng cách cho phép các nhà phân tích thêm các vật thể quan sát được vào trường hợp của họ, tận dụng thẻ, gắn cờ IOC và xác định các vật thể quan sát được nhìn thấy trước đó để cung cấp thông tin về mối đe dọa của họ.

# Task 3: TheHive Features & Integrations
The features include:
- **Case/Task Management**: Mọi cuộc điều tra đều nhằm mục đích tương ứng với một vụ án đã được tạo ra. Mỗi trường hợp có thể được chia thành một hoặc nhiều nhiệm vụ để tăng thêm chi tiết và thậm chí được chuyển thành các mẫu để quản lý dễ dàng hơn. Ngoài ra, các nhà phân tích có thể ghi lại tiến trình của họ, đính kèm các mảnh bằng chứng hoặc các tệp đáng chú ý, thêm thẻ và các kho lưu trữ khác vào các trường hợp.
- **Alert Triage**: Các trường hợp có thể được nhập từ cảnh báo SIEM, báo cáo email và các nguồn sự kiện bảo mật khác. Tính năng này cho phép nhà phân tích xem qua các cảnh báo đã nhập và quyết định xem chúng có được chuyển sang điều tra hoặc ứng phó sự cố hay không.
- **Observable Enrichment with Cortex**: Một trong những tích hợp tính năng chính mà TheHive hỗ trợ là Cortex, một công cụ phân tích và phản hồi tích cực có thể quan sát được. Cortex cho phép các nhà phân tích thu thập thêm thông tin từ các chỉ số mối đe dọa bằng cách thực hiện phân tích tương quan và phát triển các mô hình từ các trường hợp. Thông tin thêm về Cortex.
- **Active Response**: TheHive cho phép các nhà phân tích sử dụng Người phản hồi và thực hiện các hành động tích cực để liên lạc, chia sẻ thông tin về sự cố và ngăn chặn hoặc ngăn chặn mối đe dọa.
- **Custom Dashboards**: **Thống kê** về các trường hợp, nhiệm vụ, **có thể quan sát được**, số liệu, v.v. có thể được biên soạn và phân phối trên bảng điều khiển có thể được sử dụng để tạo KPI hữu ích trong tổ chức.
- **Built-in MISP Integration**: Một sự tích hợp hữu ích khác là với **MISP**, một nền tảng thông tin về mối đe dọa để chia sẻ, lưu trữ và tương quan các Chỉ số Thỏa hiệp của các cuộc tấn công có chủ đích và các mối đe dọa khác. Sự tích hợp này cho phép các nhà phân tích tạo các trường hợp từ các sự kiện MISP, nhập IOC hoặc xuất các chỉ số được xác định của riêng họ sang cộng đồng MISP của họ.

# Task 4: User Profiles & Permissions
**TheHive** cung cấp cho quản trị viên khả năng tạo một nhóm tổ chức để xác định các nhà phân tích và phân công các vai trò khác nhau dựa trên danh sách hồ sơ người dùng được cấu hình sẵn.
Các hồ sơ người dùng được cấu hình sẵn là:
- **admin**: Quản trị vị có đầy đủ các quyền hạn trên hệ thống. Không thể quản lý bất kỳ Trường hợp hoặc dữ liệu nào khác liên quan đến điều tra;
- **org-admin**: quản lý người dùng và tất cả cấu hình cấp tổ chức, có thể tạo và chỉnh sửa **Trường hợp**, **Nhiệm vụ**, **Thiết bị quan sát** và **chạy Trình phân tích** và **Trình phản hồi**;
- **analyst**: có thể tạo và chỉnh sửa Case, Tasks, **Observables** và chạy **Analysers** & **Responders**;
- **Read-only**: Chỉ có thể đọc, Trường hợp, Nhiệm vụ và Chi tiết quan sát được;
## Answer the questions
1. *Which pre-configured account cannot manage any cases?*
Answer: **Admin**
2. *Which permission allows a user to create, update or delete observables?*
Answer: **manageObservable**
3. *Which permission allows a user to execute actions?*
Answer: **manageAction**
# Task 5: Analyst Interface Navigation
1. *Where are the TTPs imported from?*
Answer: **MITRE ATT&CK**
1. *According to the Framework, what type of Detection "Data source" would our investigation be classified under?*
Answer: **Network Traffic**
Solution: **Để tìm được đáp án, bạn phải vào trang web của MITRE ATT&CK, chọn mục `Defenses` rồi vào `Data Sources`. File đầu bài cho là file `pcap`. Nên sử dụng tìm kiếm tìm từ `pcap`**