# ReCAPTCHA

## 1. Google reCaptcha V2 checkbox&#x20;

Khi sử dụng google reCaptcha V2 check box thì trên phần form đăng ký của bạn, sẽ có 1 phần Có phải robot hay không

![](<../../.gitbook/assets/image (944).png>)

**Bước 1: Tạo tài khoản liên kết**

**Cách 1 :** Truy cập trang builder.ladipage.com, chọn menu **Tích hợp -> Tài khoản liên kết -> Tạo tài khoản liên kết.** Sau đó lựa chọn Loại tài khoản là **Google reCaptcha- Chọn loại Captcha là v2**&#x20;

![](<../../.gitbook/assets/image (301).png>)

![](<../../.gitbook/assets/image (327).png>)

**Cách 2 :** Truy cập builder chỉnh sửa trang landingpage muốn sử dụng reCaptcha,  mục **Thêm mới- Ứng dụng- Google reCaptcha - chọn loại là v2**&#x20;

![](<../../.gitbook/assets/image (309).png>)

**Bước 2:** Nhập đầy đủ các thông tin:

**Tên Gợi Nhớ:** là tên để phân biệt với các liên kết khác.&#x20;

**Site Key,Secret Key**: là api key kết nối lấy trong tài khoản Google reCaptcha&#x20;

Ấn **Thêm tài khoản** để Lưu.

![](<../../.gitbook/assets/image (991).png>)

**Cách lấy Site Key,Secret Key**&#x20;

Đăng nhập tài khoản Google reCaptcha của bạn bằng đường dẫn : [http://ldp.to/4HuPI](http://ldp.to/4HuPI) rồi thiết lập lần lượt các thông tin để tạo Site Key và Secret Key

**Lưu ý** : ReCaptcha Type: chọn là **V2**

Tên miền : bạn muốn sử dụng phần Google Captcha ở trang nào thì phần tên miền phải thiết lập ở phần Areas&#x20;

![](<../../.gitbook/assets/image (246).png>)

**Bước 3: Sử dụng google reCaptcha cho trang landingpage**

Truy cập vào builder của trang landingpage mà bạn muốn bật tính năng Google recaptcha,  thanh công trên cùng , mục **Thêm mới**-> **Ứng dụng** -> **Google Recaptcha .** Bạn **Bật sử dụng ứng dụng** và  **Chọn cấu hình tài khoản liên kết** bạn đã tạo&#x20;

![](<../../.gitbook/assets/capcha 2 (1).gif>)

Sau khi tích chọn sử dụng google reCaptcha V2, các form trên trang landingpage của bạn sẽ có phần giao diện hiển thị : I am not robot ( Tôi không phải robot ) , bạn sẽ vào phần Form đăng ký, chọn căn chỉnh lại vị trí hiển thị và kéo chuyển vị trí các phần tử của form cho phù hợp với giao diện hiển thị của google captcha V2

Vị trí hiển thị đó sẽ căn chỉnh theo vị trí của nút bấm submit của Form&#x20;

![](<../../.gitbook/assets/image (1151).png>)

## 2. Google reCaptcha bản v3

**Bước 1: Tạo tài khoản liên kết**

Cách 1 : Truy cập trang builder.ladipage.com, chọn menu **Tích hợp -> Tài khoản liên kết -> Tạo tài khoản liên kết.** Sau đó lựa chọn Loại tài khoản là **Google reCaptcha - chọn loại Captcha là v3**

![](<../../.gitbook/assets/image (238).png>)



![](<../../.gitbook/assets/image (202).png>)

**Cách 2 :** Truy cập builder chỉnh sửa trang landingpage muốn sử dụng reCaptcha,  mục **Thêm mới- Ứng dụng- Google reCaptcha - chọn Captcha là v3**

![](<../../.gitbook/assets/image (180).png>)

**Bước 2:** Nhập đầy đủ các thông tin:

**Tên Gợi Nhớ:** là tên để phân biệt với các liên kết khác.&#x20;

**Site Key,Secret Key**: là api key kết nối lấy trong tài khoản Google reCaptcha&#x20;

Ấn **Thêm tài khoản**  để Lưu.

![](<../../.gitbook/assets/image (220).png>)

**Cách lấy Site Key,Secret Key**&#x20;

Đăng nhập tài khoản Google reCaptcha của bạn bằng đường dẫn : [http://ldp.to/4HuPI](http://ldp.to/4HuPI) rồi thiết lập lần lượt các thông tin để tạo Site Key và Secret Key

**Lưu ý** : ReCaptcha Type: chọn là **V3**

Tên miền : bạn muốn sử dụng phần Google Captcha ở trang nào thì phần tên miền phải thiết lập ở phần Areas&#x20;

![](<../../.gitbook/assets/image (1169).png>)

**Bước 3: Sử dụng google reCaptcha cho trang landingpage**

Truy cập vào builder của trang landingpage mà bạn muốn bật tính năng Google recaptcha,  thanh công trên cùng , mục **Thêm mới**-> **Ứng dụng** -> **Google Recaptcha .** Bạn **Bật sử dụng ứng dụng** và  **Chọn cấu hình tài khoản liên kết** bạn đã tạo&#x20;

![](<../../.gitbook/assets/capcha 2.gif>)

{% hint style="danger" %}
Bạn cần xuất bản landingpage tương ứng với tên miền đã được thêm vào mục Areas trong phần thiết lập tạo Site Key và Secret Key của Google reCaptcha&#x20;
{% endhint %}

{% hint style="danger" %}
Bạn muốn ẩn đi Logo của Google reCaptcha hiển thị trên trang của bạn, bạn thêm dòng code vào phần Thiết lập - Mã Java/Css- Thẻ Header trong builder trang landingpage của bạn&#x20;
{% endhint %}

```
<style>
 .grecaptcha-badge{
    visibility: collapse !important;
}
</style>
```

{% hint style="danger" %}
Google reCaptcha V2 thì phần dữ liệu Capture Form của Form ( đối với các tài khoản có tính năng này ) sẽ không áp dụng được&#x20;
{% endhint %}

{% hint style="danger" %}
Nếu chọn sử dụng cả Google reCaptcha Enterprise và V2 hoặc V3 thì sẽ ưu tiên hiển thị  Google reCaptcha Enterprise  ở trang xuất bản và  trong builder chỉnh sửa sẽ không có hiển thị phần căn chỉnh hiển thị vi trí Google recaptcha V2 checkbox trên form&#x20;
{% endhint %}



