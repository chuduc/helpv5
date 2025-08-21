# Xuất bản Landing Page lên nền tảng Shopify

Để tải Landing Page lên nền tảng Shopify trước tiên bạn cần phải có tài khoản tại Shopify. Sau đó bạn có thể thực hiện theo các bước sau đây:

**Bước 1: Tạo bản ghi sau trong phần quản lý DNS của tên miền:**

**Host Record:** ladipageverify\
**Type (Loại):** CNAME\
**Value (Giá trị):** [dns.ladipage.com](http://dns.ladipage.com/)

**Ghi chú:** Bản ghi này chỉ có mục đích xác thực tên miền trong tài khoản LadiPage để bỏ logo LadiPage ở chân trang và không ảnh hưởng tới các bản ghi hiện tại của bạn đang có.

**Bước 2: Thêm tên miền trong tài khoản LadiPage:**

{% embed url="https://www.loom.com/share/4a1c913d6cbe4e798120f4cf555b4576" %}

{% hint style="danger" %}
Bạn cần dán đường dẫn builder như trong hình tại app shopify của bạn:
{% endhint %}

<figure><img src="../../.gitbook/assets/image (1225).png" alt=""><figcaption></figcaption></figure>

* App URL: [https://](https://webcake.io)builder.ladipage.com/
* Preferences URL: [https://](https://webcake.io)builder.ladipage.com/
* Allowed redirection URL: [https://](https://webcake.io)builder.ladipage.com/auth/shopify.html



<figure><img src="../../.gitbook/assets/image (1109).png" alt=""><figcaption></figcaption></figure>

Truy cập mục Landing Page -> Tên miền, bấm nút Tạo tên miền&#x20;

<figure><img src="../../.gitbook/assets/image (1226).png" alt=""><figcaption></figcaption></figure>

**Bước 3: Xác thực tên miền:**

Sau khi thêm tên miền, bạn bấm vào icon ... chọn Xác thực tên miền.

<figure><img src="../../.gitbook/assets/image (1227).png" alt=""><figcaption></figcaption></figure>

**Bước 4: Xuất bản landing page với tên miền nền tảng Shopify:**

* Trong trang chỉnh sửa landing page, bấm **Xuất bản.**
* Chọn mục **Tên miền riêng** và chọn **tên miền riêng nền tảng Shopify** của bạn.
* Nhập tên thư mục con mà bạn muốn tạo sau dấu "/".
* Bấm nút **Xuất bản lại** để tải Landing Page lên Shopify. Sau khi xuất bản xong ngay lập tức bạn có thể truy cập vào đường dẫn vừa được xuất bản thành công.

![](<../../.gitbook/assets/xuất bản với tên miền riêng (3).png>)

{% hint style="warning" %}
**Lưu ý:**

* Tên miền chọn nền tảng Shopify sẽ không bật được SSL trong tài khoản LadiPage.
* Các trang landing page xuất bản với nền tảng Shopify sẽ nằm trong mục Pages của Shopify, vì vậy trang sẽ mặc định hiển thị có chữ "pages", ví dụ: tenmiencuaban.com/pages/landingpage. Phần này hiển thị theo định dạng của Shopify.
* Các trang landing page xuất bản với nền tảng Shopify sẽ không có báo cáo của LadiPage (Người truy cập, chuyển đổi, chuyển đổi duy nhất, tỷ lệ chuyển đổi và doanh thu).
{% endhint %}
