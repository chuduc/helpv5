# Lưu trữ , khôi phục giao dịch lưu trữ

Khi dữ liệu bán hàng của bạn ngày càng nhiều, việc giữ cho không gian làm việc gọn gàng và hiệu quả trở nên quan trọng hơn.

**Lưu trữ** cho phép bạn loại bỏ các giao dịch không còn hoạt động khỏi chế độ xem hiện tại mà không làm mất dữ liệu lịch sử. Điều này giúp bạn tập trung hơn, cải thiện hiệu suất hệ thống và không vượt quá giới hạn số lượng của giao dịch ( nếu có)

***

## Khi nào nên lưu trữ giao dịch

Bạn có thể lưu trữ bất kỳ giao dịchnào không còn được quản lý tích cực. Một số trường hợp phổ biến:

**1. Không hoạt động trong thời gian dài**

* Không có hoạt động hoặc cập nhật trong 6–12 tháng qua
* Không có nhiệm vụ sắp tới hoặc theo dõi dự kiến

**2. Đã đóng hoặc không còn tiềm năng**

* giao dịch thua&#x20;
* Giao dịch thắng đã được giao và hoàn tất

**3. Ưu tiên thấp hoặc giá trị thấp**

* Giao dịch từ các chiến dịch cũ, thử nghiệm, hoặc công việc thăm dò
* Không phù hợp với mục tiêu kinh doanh hiện tại

**4. Lưu trữ hồ sơ**

* Các mục được giữ lại để tuân thủ, kiểm toán hoặc báo cáo mà không cần hiển thị trong workspace chính

***

## Cách lưu trữ Giao dịch&#x20;

### Chế độ xem dạng bảng (kanban)&#x20;

* Trong giao diện chi tiết của giao dịch bấm **Lưu trữ** từ menu “...”&#x20;

<figure><img src="../../../.gitbook/assets/image (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

### **Chế độ xem dạng lưới**&#x20;

* Trong chế độ xem danh sách giao dịch  dạng lưới, click vào dấu ... ỏ ngoài cùng bên phải và bấm **Lưu trữ**

<figure><img src="../../../.gitbook/assets/image (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

***

## Khi đã lưu trữ

* Giao dịch giữ nguyên trạng thái trước đó (Mở,  Thành Công hoặc Thất bại)
* Automations và webhook phụ thuộc vào thay đổi bản ghi có thể được kích hoạt

***

***

## Xem các giao dịch đã lưu trữ

Ở phần chế độ xem, chọn mục **Lưu trữ** để xem lại danh sách các giao dịch đã được bấm Lưu trữ&#x20;

<figure><img src="../../../.gitbook/assets/image (2) (1) (1).png" alt=""><figcaption></figcaption></figure>

***

## Khôi phục các giao dịch đã lưu trữ&#x20;

Ở phần chế độ xem, chọn mục **Lưu trữ** để xem lại danh sách các giao dịch đã được bấm Lưu trữ&#x20;

Ở mục ... ở từng giao dịch, bấm **Khôi phục** lại giao dịch để đưa lại giao dịch về trạng thái Mở

<figure><img src="../../../.gitbook/assets/image (4) (1).png" alt=""><figcaption></figcaption></figure>

***

## Hành động bị hạn chế với giao dịch đã lưu trữ

* **Chỉnh sửa:** không thể thay đổi tiêu đề, giá trị, giai đoạn, người sở hữu hoặc trường tùy chỉnh, bất kỳ nội dung nào trong giao dịch&#x20;

***

## Hành động vẫn cho phép với giao dịch đã lưu trữ

* **Xuất dữ liệu** từ list view
* **Tạo bản sao** từ giao dịch lưu trữ
* Hiển thị trong **kết quả tìm kiếm**
