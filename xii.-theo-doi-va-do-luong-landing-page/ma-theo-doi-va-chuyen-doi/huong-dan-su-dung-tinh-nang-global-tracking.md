# Hướng dẫn sử dụng tính năng Global tracking

Global Tracking làm một tính năng của LadiPage cho phép bạn lưu các loại Tracking đã gắn ở 1 trang thành 1 cấu hình chung và sử dụng cấu hình đó cho nhiều trang khác.&#x20;

Khi thay đổi thông tin mã ID nào đó trong cấu hình này thì tất cả các trang đang sử dụng cấu hình này đều sẽ được thay đổi theo.&#x20;

Trong phần **Thiết lập- Mã chuyển đổi**, chọn **Thêm mới** đoạn mã **Tracking Global:**

![](<../../.gitbook/assets/image (636).png>)

**Hoặc** bạn có thể vào trực tiếp phần **Tích hợp- Mã Tracking Global**&#x20;

![](<../../.gitbook/assets/image (389).png>)

Tiếp tục nhập các mã tracking trong các ô tương ứng và đặt tên cấu hình sau đó bấm cập nhật:

![](<../../.gitbook/assets/image (391).png>)

{% hint style="danger" %}
Lưu ý: Khi đã điền các mã ID theo dõi trong cấu hình mã tracking global thì không điền các mã ID ở ngoài phần thiết lập của landing page nữa.
{% endhint %}

Sau đó ở trang Landing Page khác, nếu muốn sử dụng lại cấu hình này bạn chỉ cần chọn tên cấu hình trong danh sách là xong: **truy cập mục Thiết lập- Mã chuyển đổi**&#x20;

![](<../../.gitbook/assets/image (412).png>)



![](<../../.gitbook/assets/image (331).png>)

**Phần Thời gian chờ (ms): giúp tối ưu load trang  dù gắn hàng loạt mã js.**

Ngoà**i** LazyLoad Image - Iframe - Video, CDN, Resize, Optimize Image, mục thời gian chờ  "Delay JS" cũng là phần giúp hỗ trợ load trang được nhanh hơn . Hiểu đơn giản là bình thường chúng ta gắn code tracking fb, google analytics, google tag, livechat fb, google ads, tiktok... vô số mã đó khiến Landing Page load bị nặng nề. Chính  vì vậy tất cả các mã trên được  đưa vào  Global Tracking và để Delay JS là 3000ms (tương ứng 3s). Khách hàng khi vào Landing Page chỉ phải load nội dung thôi, nhanh lẹ. Sau 3s hoặc tương tác thì Global Tracking sẽ hoạt động.
