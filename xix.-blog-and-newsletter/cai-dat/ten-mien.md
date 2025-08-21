---
description: >-
  Cho phép bạn cấu hình tên miền riêng cho trang của bạn. Nếu không thiết lập
  tên miền riêng thì trang sẽ sử dụng với tên miền mặc định của hệ thống
---

# Tên miền

## Sử dụng tên miền miễn phí của hệ thống&#x20;

Truy cập mục **Thiết lập-> Tên miền -> Tên miền miễn phí.**  Mỗi tài khoản blog sẽ được cấp một tên miền miễn phí  với đuôi là ladi.blog để truy cập kiểm tra giao diện blog đã thiết lập.

Bạn có thể thay đổi phần sub của tên miền theo mong muốn của bạn, bằng cách bấm vào mục ![](<../../.gitbook/assets/image (154).png>) rồi bấm lại nút ![](<../../.gitbook/assets/image (155).png>)

<figure><img src="../../.gitbook/assets/image (1363).png" alt=""><figcaption></figcaption></figure>

## Sử dụng tên miền riêng của bạn

Trong trường hợp bạn sử dung gói trả phí của Blog, bạn có thể thêm 1 tên miền riêng để khách hàng truy cập bằng tên miền riêng của bạn

### **Bước 1: Trỏ tên miền về hosting của LadiPage.**

_**Trỏ tên miền chính:**_

Vào phần quản trị tên miền ở nơi bạn mua tên miền và cấu hình **2** bản ghi sau để điều hướng tên miền đó về địa chỉ của LadiPage:

Host record: **www**\
Type (Loại): **CNAME**\
Value (Giá trị): **dns.blog.ladipage.com**

Host record: @\
Type (Loại): URL Redirect\
Value (Giá trị):   http://www.tenmiencuaban.com\
Lưu ý: Thay tenmiencuaban.com thành tên miền bạn đang cấu hình.

_**Trỏ tên miền phụ:**_

Giả sử tên miền chính của bạn là tenmiencuaban.com, và bạn muốn tạo một tên miền phụ là .tenmiencuaban.com thì:\
Chọn tên miền chính bạn muốn cài đặt, sau đó tạo một bản ghi mới và điền các giá trị như sau:\
Host record: **blog**\
Type (Loại): **CNAME**\
Value (Giá trị): **dns.blog.ladipage.com**

### **Bước 2: Thêm tên miền ,xác thực và bật SSL cho tên miền của trang**&#x20;

**Bước 2.1 : Truy cập mục  Blog  -> Thiết lập-> Tên miền -> Tên miền tùy chỉnh**&#x20;

để thêm tên miền riêng cho  của bạn&#x20;

<figure><img src="../../.gitbook/assets/image (1364).png" alt=""><figcaption></figcaption></figure>

Điền tên miền vào mục nhập tên miền và bấm ![](<../../.gitbook/assets/image (157).png>)

**Bước 2.2 : Bấm Xác thực tên miền**&#x20;

<figure><img src="../../.gitbook/assets/image (1365).png" alt=""><figcaption></figcaption></figure>

**Bước 2.3 : Bật SSL cho tên miền**&#x20;

Tên miền sau khi đã xác thực thành công, sẽ cho phép bật SSL để tăng tính bảo mật cho tên miền&#x20;

<figure><img src="../../.gitbook/assets/image (159).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
* **Tên miền chính bắt buộc có www ở đầu, ví dụ: www.tenmiencuaban.com**
* **Tên miền phụ thì không cần nhập www, ví dụ: blog.tenmiencuaban.com**


{% endhint %}

{% hint style="danger" %}
Thời gian xác thực và bật SSL cho tên miền thành công từ 0-2h.
{% endhint %}

{% hint style="danger" %}
Blog có cả tên miền miễn phí và tên miền tùy chỉnh, các nội dung thiết lập của blog sẽ hiển thị theo Tên miền tùy chỉnh&#x20;
{% endhint %}
