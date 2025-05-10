# MISP
# Task 1: Room Overview
**MISP** *stands for* **Malware Information Sharing Platform**.
# Task 2: MISP Instroction: Feautures & Terminology
**MISP** là một nền tảng mã nguồn mở được thiết kế để chia sẻ thông tin về mối đe dọa và các sự kiện an ninh mạng. Nó cung cấp một loạt các tính năng và thuật ngữ quan trọng giúp người dùng hiểu rõ hơn về cách thức hoạt động của nền tảng này.
**MISP** hữu ích hiệu quả trong những trường hợp cụ thể:
- **Malware Reverse Engineering:** Chia sẻ thông tin về mã độc để hiểu về cách thức hoạt động của nó.
- **Security Investigations:** Hỗ trợ điều tra các sự kiện an ninh mạng.
- **Intelligence Analysis:** Thu thập các thông tin về các nhóm tấn công và khả năng tấn công của chúng.
- **Law Enforcement:** Sử dụng các dấu hiệu hỗ trợ điều tra pháp y.
- **Risk Analysis:** Nghiên cứu về những lỗ hổng mới, khả năng và sự xuất hiện của chúng.
- **Fraud Analysis:** Chia sẻ về các chỉ số để phát hiện gian lận kinh tế.

## What does MISP support? 
- **IOC database:** Cái này cho phép lưu trữ các kỹ thuật và không phải kỹ thuật về các ví dụ mã độc, điều tra, kẻ tấn công, và thông tin.
- **Automatic Correlation:** Xác định mối quan hệ giữa các thuộc tính và chỉ số từ phần mềm độc hại, các chiến dịch tấn công hoặc phân tích.
- **Data Sharing:** Cho phép chia sẻ thông tin bằng các mô hình khác nhau của các tổ chức và giữ MISP.
- **Import & Export Features:** Cho phép nhập và xuất thông tin từ các định dạng khác nhau như NIDS, HIDPS, và OpenIOC.
- **Event Graph:** Hiển thị mối quan hệ giữa các đối tượng và thuộc tính được xác định từ các sự kiện.
- **API Support:** Hỗ trợ tích hợp với các hệ thống riêng để tìm nạp và xuất các sự kiện và thông tin tình báo.

Và bao gồm các thuật ngữ như:
- **Event:** Một sự kiện là một tập hợp các thuộc tính và chỉ số liên quan đến một mối đe dọa cụ thể.
- **Attribute:** Một thuộc tính là một phần của thông tin trong một sự kiện, chẳng hạn như địa chỉ IP, tên miền hoặc hash.
- **Object:** Một đối tượng là một thực thể trong một sự kiện, chẳng hạn như một máy chủ, một địa chỉ IP hoặc một tệp tin.
- **Tag:** Một thẻ là một nhãn được gán cho một sự kiện hoặc thuộc tính để phân loại hoặc nhóm chúng lại với nhau.
- **Object References:** Một tham chiếu đối tượng là một tập hợp các đối tượng và thuộc tính liên quan đến một chủ đề cụ thể, chẳng hạn như một nhóm tấn công hoặc một loại mã độc.
- **Sightings:** Một Sightings là một sự kiện được ghi lại khi một thuộc tính hoặc đối tượng được phát hiện trong môi trường của một tổ chức.
- **Tags:** Một thẻ là một nhãn được gán cho một sự kiện hoặc thuộc tính để phân loại hoặc nhóm chúng lại với nhau.
- **Taxonomies:** Thư viện phân loại được sử dụng để gắn thẻ, phân loại và sắp xếp thông tin.
- **Galaxy:** Các mục cơ sở kiến thức được sử dụng để gắn nhãn sự kiện/thuộc tính.
- **Indicators:** Các mẩu thông tin có thể phát hiện hoạt động mạng đáng ngờ hoặc độc hại.

# Task 3: Using the System
Giao diện **MISP** cho phép các nhà phân tích theo dõi, chia sẻ và đối chiếu các sự kiện và *IOC* (chỉ số xâm phạm). Các chức năng chính bao gồm:

- **Home button:** Đưa bạn về màn hình bắt đầu của ứng dụng, trang danh sách sự kiện hoặc trang được đặt làm trang chủ tùy chỉnh.
- **Event Actions:** Cung cấp tất cả các chức năng liên quan đến việc tạo, sửa đổi, xóa, xuất bản, tìm kiếm và liệt kê các sự kiện và thuộc tính.
- **Dashboard:** Cho phép bạn tạo một bảng điều khiển tùy chỉnh bằng các widget.
- **Galaxies:** Đường dẫn tắt đến danh sách các MISP Galaxies trên phiên bản MISP.
- **Input Filters:** Thay đổi cách người dùng nhập dữ liệu vào phiên bản này. Người dùng có thể xem các quy tắc thay thế và danh sách chặn, trong khi quản trị viên có thể thay đổi chúng.
- **Global Actions:** Truy cập thông tin về MISP và phiên bản này. Bạn có thể xem và chỉnh sửa hồ sơ của mình, xem hướng dẫn sử dụng, đọc tin tức hoặc điều khoản sử dụng, xem danh sách các tổ chức đang hoạt động và biểu đồ đóng góp của họ.
- **MISP:** Liên kết đơn giản đến URL cơ sở của bạn.
- **Name:** Tên (Tự động tạo từ địa chỉ Mail) của người dùng hiện đang đăng nhập.
- **Envelope:** Liên kết đến Bảng điều khiển Người dùng để tham khảo một số thông báo và thay đổi của bạn kể từ lần truy cập cuối cùng.
- **Log out:** Nút Đăng xuất để kết thúc phiên làm việc của bạn ngay lập tức.
1. *How many distribution options does MISP provide to share threat information?*
Answer: **4**
2. *Which user has the role to publish events?*
Answer: **Organisation Admin**
# Task 4: Feeds & Taxonomies
- **Feeds:** Nhập chỉ số đe dọa từ các nguồn bên ngoài để cập nhật thông tin.
- **Taxonomies:** Phân loại thông tin (sự kiện, chỉ số) bằng các thẻ (tag) tiêu chuẩn.
- **Tagging:** Gắn thẻ vào sự kiện/thuộc tính để xác định và chia sẻ thông tin mối đe dọa.
# Task 5: Scenario Event
1. *What event ID has been assigned to the PupyRAT event?*
Answer: **1145**
2. *The event is associated with the adversary gaining ______ into organisations.*
Answer: **Remote Access**
3. *What IP address has been mapped as the PupyRAT C2 Server*
Answer: **89.107.62.39**
4. *From the Intrusion Set Galaxy, what attack group is known to use this form of attack?*
Answer: **Magic Hound**
5. *There is a taxonomy tag set with a Certainty level of 50. Which one is it?*
Answer: **OSINT**