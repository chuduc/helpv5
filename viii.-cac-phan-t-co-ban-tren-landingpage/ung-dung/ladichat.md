---
description: >-
  LadiChat là công cụ giúp bạn tương tác  trực tiếp với khách hàng của mình 
  trên trang Landing Page,  hỗ trợ , giải đáp , tạo đơn hàng cho khách hàng.
---

# LadiChat

## Cách 1: Tích hợp LadiChat b**ằng API Key của LadiChat**

‌Với cách này tích hợp này, bạn chỉ cần chèn tích hợp chat 1 lần vào tài khoản LadiPage của bạn, rồi ở các landingpage khác trong tài khoản, chọn lại liên kết LadiChat đã tạo là sẽ sử dụng được LadiChat

‌**Bước 1: Tích hợp ứng dụng LadiChat vào tài khoản LadiPage**\
**Cách 1 :** Truy cập trang [builder.ladipage.com](http://builder.ladipage.com/), chọn menu **Tích hợp -> Tài khoản liên kết -> Tạo tài khoản liên kết.** Sau đó lựa chọn Loại tài khoản là **LadiChat**

![](<../../.gitbook/assets/tài khoản liên kết .gif>)

**Cách 2 :** Truy cập builder chỉnh sửa trang landingpage  ở phần **Ứng dụng, LadiChat, bấm tạo Cấu hình LadiChat**&#x20;

![](<../../.gitbook/assets/image (1019).png>)

**Bước 2 :**&#x20;

Điền đầy đủ các thông tin ở tài khoản liên kết:

‌**Tên liên kết:** là tên để phân biệt với các liên kết khác.

‌**API:** api kết nối lấy trong tài khoản của LadiChat&#x20;

![](<../../.gitbook/assets/image (254).png>)

‌

**\*Cách lấy API của LadiChat**

‌Đăng nhập tài khoản LadiChat ở đường dẫn [https://app.ladichat.com](https://app.ladichat.com/), vào phần **Cài đặt** ở thanh công cụ bên tay trái , chọn Tích hợp API, và copy đoạn mã&#x20;

![](<../../.gitbook/assets/image (615).png>)

‌

Kết nối thành công sẽ hiện LadiChat ở tài khoản liên kết:

![](<../../.gitbook/assets/image (591).png>)

‌

**Bước 2: Hiển thị LadiChat đã kết nối trên các landing page của bạn**

‌Truy cập lại builder chỉnh sửa landing page của bạn

Ở thanh công cụ bên trái, vào phần **Ứng dụng** -> chọn **LadiChat**

![](<../../.gitbook/assets/image (934).png>)

‌

**Chọn cấu hình LadiChat của bạn sẽ hiển thị trên trang Landing Page**

## Cách 2: Tích hợp LadiChat bằng code Javascript của LadiChat&#x20;

Với phương pháp tích hợp này, bạn muốn ladiChat hiển thị ở trang landing page nào thì chèn code LadiChat vào trang landing page đó.

Bước  1: Đăng nhập tài khoản LadiChat&#x20;

Đăng nhập tài khoản LadiChat ở đường dẫn [https://app.ladichat.com](https://app.ladichat.com/), vào phần **Cài đặt- Kênh tương tác ,**  ở thanh công cụ bên tay trái  chọn 1  Widget ,copy đoạn mã javascript

![](<../../.gitbook/assets/image (417).png>)

Bước 2 : Truy cập vào Builder chỉnh sửa của Trang Landing Page mà bạn muốn hiển thị code chat&#x20;

Bạn chọn mục Thiết lập (thanh công cụ trên cùng )- Mã Javascript/CSS- Trước thẻ Body, bạn chèn đoạn code chat và bấm Đóng &#x20;

![](<../../.gitbook/assets/image (727).png>)

Xuất bản lại trang Landing Page của bạn, để cập nhật code chat lên trang của bạn

{% hint style="danger" %}
Lưu ý : Trên cùng 1 trang landingpage, chỉ sử dụng 1 trong 2 cách tích hợp LadiChat, sử dụng cả 2 sẽ bị lỗi hiển thị&#x20;
{% endhint %}





\
