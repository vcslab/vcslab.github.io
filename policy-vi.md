---
layout: page
permalink: /policy
title: VCS Vulnerability Disclosure Policy
version: 1.0
update: 2021-09-09
---
[Read English version](/policy)

Công ty An ninh mạng Viettel được thành lập từ năm 2011 với trách nhiệm đảm bảo an toàn thông tin cho Tập đoàn Công nghiệp - Viễn thông Quân đội, song song với đó là cung cấp dịch vụ an toàn thông tin cho các tổ chức, doanh nghiệp khác. Với phương châm coi trọng việc nghiên cứu chuyên sâu, nhóm security research của chúng tôi được thành lập từ những ngày đầu tiên. Mục tiêu của nhóm là thực hiện nghiên cứu lỗ hổng, các kỹ thuật khai thác và nguy cơ an toàn thông tin mới, nhằm cảnh báo và ngăn chặn sự ảnh hưởng tới cộng đồng. Năm 2021, nhóm bắt đầu được định danh là VCSLab với định hướng tìm, công bố lỗ hổng chuyên nghiệp, đồng thời hướng tới giá trị cộng đồng.

### 1.  Định nghĩa khái niệm
**Chương trình công bố lỗ hổng** của Công ty An ninh mạng Viettel tuân thủ theo hình thức “Responsible Disclosure” (Link tham chiếu 1). Điều đó có nghĩa rằng các lỗ hổng trong chương trình sẽ được cảnh bảo đến đơn vị chủ quản, vendor ngay khi lỗ hổng được phát hiện. Song song với đó, thông tin mô tả về lỗ hổng, cách thức khắc phục sẽ được cảnh báo cho cộng đồng dưới dạng advisory sau 90 ngày. Cách làm này được chúng tôi tham khảo theo Nhóm nghiên cứu của Google – Project Zero (https://www.google.com/about/appsecurity/)  
**Advisory** là các cảnh báo lỗ hổng của Chương trình đến cộng đồng nhằm đảm bảo rằng lỗ hổng được nhận thức đúng đắn về mức độ nghiêm trọng, đồng thời đảm bảo lỗ hổng được khắc phục rộng rãi. Các advisory được đăng tải trên website lab.viettelcybersecurity.com 
**Báo cáo lỗ hổng** là các mô tả lỗ hổng được gửi riêng cho đơn vị chủ quản và vendor. Có 3 nhóm báo cáo như sau:
+ **Báo cáo phi lợi nhuận (Community report):** là các báo cáo gửi đến các đơn vị chủ quản, vendor theo một chương trình nghiên cứu hoặc vì mục đích cộng đồng.
+ **Báo cáo phi lợi nhuận tại Việt Nam (VN Community report):** vì một số vấn đề pháp lý nên các báo cáo lỗ hổng tại Việt Nam sẽ được thực hiện thông qua sự chấp thuận của đơn vị chủ quản hoặc thông qua các cơ quan quản lý nhà nước.
+ **Báo cáo lỗ hổng Bugbounty:** là các báo cáo theo 1 chương trình Bugbounty, các báo cáo này sẽ tuân theo chính sách disclosure của chương trình.
### 2.  Nguyên tắc
Chính sách công bố lỗ hổng được tuân theo một số nguyên tắc sau:
-   **Tôn trọng lỗ hổng** là tôn chỉ và định hướng xuyên suốt của chương trình. Lỗ hổng cần được nhìn nhận đúng và khắc phục đầy đủ nhất có thể.
-   **Tôn trọng luật lệ:** Tất cả chương trình tìm lỗ hổng đều hướng tới môi trường mạng an toàn hơn, chúng tôi cam kết việc tìm lỗ hổng đều nằm trong khuôn khổ cho phép, tuân thủ theo pháp luật.
-   **Tôn trọng sản phẩm:** Chúng tôi hiểu rằng giá trị cốt lõi của sản phẩm nằm trong chức năng mà sản phẩm đó cung cấp. Security là giá trị tăng thêm cho sản phẩm. Các công bố lỗ hổng luôn hướng tới giá trị của sản phẩm, không làm ảnh hưởng đến uy tín và hình ảnh của sản phẩm.

### 3.  Thời hạn khắc phục
**Các trạng thái và thời hạn chung:** Mỗi lỗ hổng phát hiện trong chương trình được đánh mã VCSA và được thay đổi các trạng thái tương ứng cho đến khi được công bố. Cụ thể có các trạng thái sau:
-   **New:** Lỗ hổng mới phát hiện và đã được gửi cho đơn vị chủ quản. VCSA của lỗ hổng ở trạng thái này không được hiển thị trên [lab.viettelcybsecurity.com](https://lab.viettelcybsecurity.com)
-   **Not-Responsed:** Sau 3 lần báo cáo được gửi và remind, mỗi lần cách nhau 7 ngày làm việc, nếu đơn vị chủ quản không phản hồi thì advisory được chuyển sang trạng thái Not-Responsed và hiển ở mục Upcomming trên trang chủ [lab.viettelcybsecurity.com](https://lab.viettelcybsecurity.com)
-   **Accepted:** Các lỗ hổng đã được đơn vị chủ quản xác nhận sẽ được hiển thị ở mục Upcomming cho đến khi hết thời hạn khắc phục.
-   **Fixed:** Các lỗ hổng đã được đơn vị chủ quản khắc phục và đã có cách thức khắc phục.
-   **Upcomming:** Là 1 mục trong advisory, liệt kê các advisory đã được chuyển trạng thái Not-Responsed, Accepted hoặc Fixed.
-   **Published:** Sau thời hạn khắc phục (90 ngày), các advisory sẽ công bố thông tin chi tiết và hiện trong mục Published trên [lab.viettelcybsecurity.com](https://lab.viettelcybsecurity.com)
Trong một số trường hợp, thời hạn khắc phục 90 ngày có thể thay đổi, cụ thể như sau:
Nếu thời hạn khắc phục rơi vào cuối tuần hoặc ngày nghỉ lễ tại Việt Nam, thời hạn sẽ được rời vào ngày làm việc tiếp theo.
-   Trước thời hạn khắc phục, nếu đơn vị chủ quản cung cấp lịch khắc phục chính thức rơi vào trong 14 ngày sau thời hạn, chúng tôi sẽ rời lịch công bố advisory cho đến khi việc khắc phục được thực hiện.
-   Trong trường hợp chúng tôi xác định một lỗ hổng đang bị khai thác một cách tích cực trong thực tế (0 day in the wild), chúng tôi tin rằng cần có những hành động khẩn cấp hơn – thời hạn 7 ngày là phù hợp. Bảy ngày là cột mốc quan trọng, có thể là ngắn để một số nhà cung cấp cập nhật sản phẩm của họ, nhưng đủ thời gian để đưa ra một số biện pháp giảm thiểu rủi ro như tạm thời vô hiệu hóa một dịch vụ, hạn chế quyền truy cập hoặc liên hệ với nhà cung cấp để biết thêm thông tin. Do đó, sau thời hạn 7 ngày, nếu đơn vị chủ quản không có bất cứ hành động bản vá hoặc khuyến nghị nào, chúng tôi sẽ cung cấp thông tin chi tiết để người dùng có thể thực hiện các bước để tự bảo vệ mình.
### 4.  Tài liệu tham chiếu
-   [https://cheatsheetseries.owasp.org/cheatsheets/Vulnerability_Disclosure_Cheat_Sheet.html](https://cheatsheetseries.owasp.org/cheatsheets/Vulnerability_Disclosure_Cheat_Sheet.html)
-   [https://www.google.com/about/appsecurity/](https://www.google.com/about/appsecurity/)
