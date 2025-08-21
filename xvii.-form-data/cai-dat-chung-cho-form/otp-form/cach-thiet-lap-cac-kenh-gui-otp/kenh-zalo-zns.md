# Kênh Zalo ZNS

Bạn tích hợp  với tài khoản LadiFLow, trong LadiFlow bạn thiết lập Flow gửi tin nhắn ZALO ZNS đến khách hàng đăng ký sdt trên form đăng ký LadiPage.

**Bước 1: Tạo tài khoản liên kết**

&#x20;**Cách 1 :** Truy cập trang [builder.ladipage.com](http://builder.ladipage.com/), chọn menu **Tích hợp -> Tài khoản liên kết -> Tạo tài khoản liên kết.** Sau đó lựa chọn Loại tài khoản là **LadiFLow**

<figure><img src="../../../../.gitbook/assets/tài khoản liên kết  (1).gif" alt=""><figcaption></figcaption></figure>

**Cách 2 :** Truy cập builder chỉnh sửa trang landingpage muốn gửi OTP thông qua Zalo ZNS , ở phần **Form đăng ký, mục Thiết lập của form đăng ký, bật  Form OTP, bấm Tạo cấu hình OTP mới** &#x20;

<figure><img src="../../../../.gitbook/assets/otp 1 (1).gif" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../../.gitbook/assets/image (937).png" alt=""><figcaption></figcaption></figure>

**Bước 2:** Nhập đầy đủ các thông tin:

**Tên liên kết:** là tên để phân biệt với các liên kết khác.&#x20;

**API KEY :** là key kết nối lấy trong tài khoản LadiFlow của bạn&#x20;

Ấn Thêm tài khoản để Lưu.

<figure><img src="../../../../.gitbook/assets/image (755).png" alt=""><figcaption></figcaption></figure>

**\*Cách lấy API  key trong LadiFlow**&#x20;

**Truy cập vào tài khoản** [**app.ladiflow.com** ](https://app.ladiflow.com/settings/api-key) **của bạn, rồi vào mục Cài đặt- Tích hợp API**&#x20;

<figure><img src="../../../../.gitbook/assets/image (924).png" alt=""><figcaption></figcaption></figure>

#### Bước 3: **Tạo** cấu hình lưu trữ form&#x20;

Vào lại trang builder.ladipage.com, chọn menu **Tích hợp -> Cấu hình Form -> chọn OTP ->  Tạo cấu hình form.**

<figure><img src="../../../../.gitbook/assets/image (1015).png" alt=""><figcaption></figcaption></figure>

**Chọn sử dụng tài khoản liên kết Ladiflow đã tạo**&#x20;

<figure><img src="../../../../.gitbook/assets/image (1023).png" alt=""><figcaption></figcaption></figure>

Nhập **Tên cấu hình** để lưu lại cấu hình form vừa tạo và bấm nút **Hoàn tất**&#x20;

<figure><img src="../../../../.gitbook/assets/image (1000).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
Trigger bạn tạo bên Ladiflow phải có phần gửi tin nhắn ZALO ZNS và chứa biến \{{otp\_code\}}
{% endhint %}

**Bước 4:** Quay trở lại form trên trang Landing Page, chọn  form bạn đang muốn cài đặt , mục thiết lập của form&#x20;

<figure><img src="../../../../.gitbook/assets/image (1026).png" alt=""><figcaption></figcaption></figure>

