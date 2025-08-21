---
description: >-
  Dưới đây là cách bạn có thể thiết lập cá nhân hóa trang cảm ơn riêng cho Form
  Checkout để hiển thị các thông tin trên trang cảm ơn theo nhu cầu của riêng
  bạn.
---

# 3. Thiết lập cá nhân hóa trang cảm ơn riêng

Trang cảm ơn sẽ hiển thị trong các trường hợp sau : trang áp dụng phương thức thanh toán của các cổng thanh toán như Vnpay, VnPT epay .. hoặc phương thanh thanh toán Bank mà tự động xác nhận được đơn hàng&#x20;

Bạn có thể tự thiết kế một trang cảm ơn riêng từ kho giao diện mẫu của LadiPage hoặc tải về **mẫu trang cảm ơn được thiết kế riêng cho Form Checkout dưới dạng file .ladipage** tại: [http://s.ldplink.me/dl-checkout-confirm](http://s.ldplink.me/dl-checkout-confirm)

1.  Tạo Landing Page mới từ thư viện mẫu hoặc tải lên file **checkout-confirmation-example-page.ladipage** đã tải về.\


    <figure><img src="../.gitbook/assets/image (108).png" alt="" width="563"><figcaption></figcaption></figure>

    Đặt tên cho Landing Page vừa tải lên sau đó bấm nút **Tạo Landing Page**\


    <figure><img src="../.gitbook/assets/image (109).png" alt=""><figcaption></figcaption></figure>


2.  Tùy biến nội dung và thiết kế của trang cảm ơn theo nhu cầu của bạn sau đó xuất bản Landing Page.\


    <figure><img src="../.gitbook/assets/image (110).png" alt="" width="563"><figcaption></figcaption></figure>


3. Sử dụng các biến các nhân hóa để hiển thị thông tin đơn hàng trong quá trình thiết kế trang cảm ơn.

| Biến thông tin      | Mô tả                        |
| ------------------- | ---------------------------- |
| \{{name\}}          | Họ tên khách hàng            |
| \{{email\}}         | Địa chỉ email khách hàng     |
| \{{phone\}}         | Số điện thoại                |
| \{{reference\_no\}} | Mã đơn hàng                  |
| \{{order\_date\}}   | Ngày đặt hàng                |
| \{{product\_name\}} | Tên sản phẩm, dịch vụ đã mua |
| \{{amount\_fm\}}    | Tổng tiền                    |

4.  Xuất bản Landing Page và nhập đường dẫn xuất bản của Landing Page vừa thiết kế vào URL Cảm ơn ở phần **Cấu hình thanh toán -> Trang cảm ơn khác**\


    <figure><img src="../.gitbook/assets/image (112).png" alt="" width="563"><figcaption></figcaption></figure>

    <figure><img src="../.gitbook/assets/image (115).png" alt="" width="563"><figcaption></figcaption></figure>


5. Bấm hoàn tất và xuất bản lại Landing Page bán hàng của bạn.
