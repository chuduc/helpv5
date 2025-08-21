# Facebook Conversion API

Facebook Conversion API hoạt động song song với Facebook Pixel để tối ưu hiệu quả quảng cáo Facebook, cho phép gửi các dữ liệu về hành động (events) mua hàng trong cửa hàng của bạn từ server (máy chủ) lên Facebook. Các server events này được gắn với một Pixel cụ thể. Để thiết lập cơ chế tối ưu này, bạn cần tạo một Access Token tương ứng với Pixel bạn đã tạo trước đó

{% hint style="danger" %}
Để tạo và sử dụng được phần Conversion API, bạn cần xác minh quyền sở hữu tên miền với Facebook Business. Chi tiết hướng dẫn theo dõi [tại đây](https://help.ladipage.vn/theo-doi-va-do-luong-landing-page/ma-theo-doi-va-chuyen-doi/huong-dan-chen-facebook-pixel-tren-ladipage/xac-minh-quyen-so-huu-ten-mien-voi-facebook-business).
{% endhint %}

{% embed url="https://www.youtube.com/watch?v=CnN5Kby4ah0" %}

**Bước 1: Tạo tài khoản liên kết Facebook Conversion API**

* Truy cập trang [builder.ladipage.com](http://builder.ladipage.com/), chọn menu  Cài đặt -> Tích hợp-> Tài khoản liên kết -> Tạo tài khoản liên kế&#x74;**.** Sau đó lựa chọn Loại tài khoản là **Facebook Conversion API**

<figure><img src="../../../.gitbook/assets/image (1419).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (1420).png" alt=""><figcaption></figcaption></figure>

* Bạn nhập đầy đủ các thông tin để tạo tài khoản liên kết Facebook Conversion API

<figure><img src="../../../.gitbook/assets/image (1426).png" alt=""><figcaption></figcaption></figure>

**Tên gợi nhớ:**  là tên để phân biệt với các liên kết khác.

**Pixel ID**: ID Facebook pixel mà bạn muốn sử dụng cho việc tracking.

**Token**: là Conversions API bạn thiết lập tương ứng với Pixel ID mà bạn sử dụng.

Ấn **Thêm tài khoản** để lưu lại thông tin vừa tạo.

**Bước 2: Cách tạo Conversion API trong tài khoản facebook pixel.**

Để tạo Access Token, bạn cần có quyền truy cập vào Quản lý Doanh nghiệp (Business Manager) của Facebook.

<figure><img src="../../../.gitbook/assets/image (884).png" alt=""><figcaption></figcaption></figure>

* Chọn pixel để thiết lập Conversions API tương ứng -> Mở trong trình quản lý sự kiện
* Chọn Cài đặt (Settings).

<figure><img src="../../../.gitbook/assets/image (662).png" alt=""><figcaption></figcaption></figure>

**Bước 3: Thiết lập conversion API trong landing page.**

Bạn vào trang chỉnh sửa landing page, vào phần Thiết Lập--> Mã chuyển đổi.

<figure><img src="../../../.gitbook/assets/image (474).png" alt=""><figcaption></figcaption></figure>

Tại phần Mã chuyển đổi, Facebook Pixel ID, bạn thiết lập Conversion API theo định dạng như phần ảnh mẫu : **ID FB Pixel|API**  (thay ID FB Pixel bằng ID bạn đã thiết lập trong mục tài khoản liên kết ở bước 2, **ký tự API giữ nguyên là chữ viết hoa, không thay đổi**)

![](<../../../.gitbook/assets/image (690).png>)

Bấm Đóng, xuất bản lại trang Landing Page để cập nhật lại thông tin lên trang của bạn.

Bạn xem kết quả liên quan đến Conversion API tại phần hoạt động của pixel của bạn&#x20;

![](<../../../.gitbook/assets/image (933).png>)

Trong trường hợp bạn sử dụng code đo lường sự kiện tùy chỉnh (không sử dụng phần tracking LadiPage thiết lập trên form) thì sẽ sử dụng theo các mẫu sau.

```
ladi_fbq('track', 'PageView');
Nếu có data về giá tiền, currency...: ladi_fbq('track', 'Purchase', {value: 50000, currency: 'VND'});
```
