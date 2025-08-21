---
description: >-
  Cho phép bạn thiết lập tracking đo lường quảng cáo facebook, google... cho
  phần form checkout,
---

# 4. Thiết lập tracking cho form checkout

## Sử dụng trang cảm ơn mặc định&#x20;

{% embed url="https://prnt.sc/wvvX3cr39eNo" %}

Bạn thực hiện các thao tác cài đặt tracking như sau :&#x20;

* Truy cập mục **Thiết lập** của Trang LandingPage chứa form checkout  -> **Mã chuyển đổi** . Chèn ID các tài khoản quảng cáo bạn muốn sử dụng&#x20;

{% embed url="https://prnt.sc/m8zdxrj-yqLM" %}

Tại form checkout, truy cập mục **Tracking**&#x20;

{% embed url="https://prnt.sc/bUFtFZYmoKfV" %}

Tại phần mã sự kiện chuyển đổi, bạn chọn cài đặt các mã chuyển đổi mong muốn sử dụng rồi bấm Cập nhật và Xuất bản lại trang&#x20;

{% embed url="https://prnt.sc/A8I8dcFoNYpj" %}

* Truy cập thiết lập của tài khoản LadiSales, mục  Thiết lập -> Mã chuyển đổi, bạn cài đặt các Mã chuyển đổi theo các mã đã thiết lập ở cho trang landingpage ở thao tác phía trên&#x20;

{% embed url="https://prnt.sc/YElfOVqZRNE2" %}



{% hint style="info" %}
Form checkout hiện tại có 2 mã tracking sự kiện: Purchase và CompletePayment cho bạn lựa chọn. Trong trường hợp bạn muốn sử dụng 1 mã khác, vui lòng thêm mã tùy chỉnh vào mục Mã tùy chỉnh nâng cao
{% endhint %}

{% hint style="info" %}
1. Trong trường hợp form checkout bạn cài đặt mã sự kiện là **Không chọn**, thì khi chuyển sang trang cảm ơn mặc định  , sẽ ghi nhận mã sự kiện là **Purchase**.
2. Trong trường hợp form checkout của bạn cài đặt mã sự kiện **KHÁC với Purchase**, thì khi chuyển sang trang cảm ơn mặc định, sẽ ghi nhận mã đã cài đặt trên form checkout.
3. Trong trường hợp form checkout của bạn cài đặt mã sự kiện là **Purchase**, thì khi chuyển sang trang cảm ơn mặc định, sẽ ghi nhận mã là **Purchase.**
{% endhint %}

Tham khảo thêm về cài đặt tracking trên trang landingpage tại đấy:

{% content-ref url="../xii.-theo-doi-va-do-luong-landing-page/ma-theo-doi-va-chuyen-doi/" %}
[ma-theo-doi-va-chuyen-doi](../xii.-theo-doi-va-do-luong-landing-page/ma-theo-doi-va-chuyen-doi/)
{% endcontent-ref %}

## Sử dụng trang cảm ơn riêng&#x20;

{% embed url="https://prnt.sc/sZMJFOA01LOj" %}

Trong trường hợp bạn sử dụng Trang cảm ơn khác để điều hướng sau khi hoàn thành form checkout, bạn cần

* Trang chứa form checkout : gắn các ID tài khoản quảng cáo vào trang chính, trong mục lưu Tracking của form đăng ký, không chọn sự kiện cho GA.

{% embed url="https://prnt.sc/skh9tra41Bk5" %}
Mục Thiết lập -> Mã chuyển đổi của trang chứa form checkout
{% endembed %}

{% embed url="https://prnt.sc/9WVQV0vV73qU" %}
Mục Form checkout không cài đặt tracking&#x20;
{% endembed %}

* Trang cảm ơn:  gắn các ID tài khoản quảng cáo vào trang và sự kiện chuyển đổi trên trang cảm ơn&#x20;

Trường hợp bạn sử dụng trang cảm ơn riêng tạo từ landingpage, bạn truy cập mục Thiết lập -> Mã chuyển đổi, điền ID vào các mục Facebook, Google ...&#x20;

Tại mục Trang cảm ơn ( Thank You Page) bấm nút Bật, và setup chọn các sự kiện tương ứng với mong muốn sử dụng&#x20;

{% embed url="https://prnt.sc/pWp10Cdsmpx8" %}
