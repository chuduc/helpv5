# TikTok Event API

TikTok Event API  hoạt động song song với TikTok Pixel để tối ưu hiệu quả quảng cáo TikTok, cho phép gửi các dữ liệu về hành động (events) mua hàng trong cửa hàng của bạn từ server (máy chủ) lên TikTok. Các server events này được gắn với một Pixel cụ thể. Để thiết lập cơ chế tối ưu này, bạn cần tạo một Access Token tương ứng với Tiktok pixel bạn đã tạo trước đó

**Bước 1: Tạo tài khoản liên kết TikTok Event API**

* Truy cập trang [builder.ladipage.com](http://builder.ladipage.com/), chọn menu Cài đặt ->Tích hợp -> Tài khoản liên kết -> Tạo tài khoản liên kế&#x74;**.** Sau đó lựa chọn Loại tài khoản là TikTok Event API

<figure><img src="../../../.gitbook/assets/image (1423).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (1424).png" alt=""><figcaption></figcaption></figure>

* Bạn nhập đầy đủ các thông tin để tạo tài khoản liên kết TikTok Event API

<figure><img src="../../../.gitbook/assets/image (1425).png" alt=""><figcaption></figcaption></figure>

**Tên gợi nhớ:**  là tên để phân biệt với các liên kết khác.

**Pixel ID**: ID Tiktok pixel mà bạn muốn sử dụng cho việc tracking.

**Token**: là Access Token bạn thiết lập tương ứng với Pixel ID mà bạn sử dụng.

Ấn **Thêm tài khoản** để lưu lại thông tin vừa tạo.

**Bước 2: Cách tạo Event API  trong tài khoản TikTok**

Truy cập tài khoản quảng cáo Tiktok của bạn [https://ads.tiktok.com/](https://ads.tiktok.com/)  mục **Tools -> Events -> Web Events**

<figure><img src="../../../.gitbook/assets/image (353).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (1104).png" alt=""><figcaption></figcaption></figure>

Truy cập mục Pixel -> Settings

<figure><img src="../../../.gitbook/assets/image (334).png" alt=""><figcaption></figcaption></figure>

Truy cập mục **Events API -> Generate Access Token**&#x20;

<figure><img src="../../../.gitbook/assets/image (341).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (742).png" alt=""><figcaption><p>Bạn Copy lại phần Token </p></figcaption></figure>

**Bước 3: Thiết lập TikTok Event API trong landing page.**

Bạn vào trang chỉnh sửa landing page, vào phần Thiết Lập--> Mã chuyển đổi.

<figure><img src="../../../.gitbook/assets/image (335).png" alt=""><figcaption></figcaption></figure>

Tại phần Mã chuyển đổi, TikTok Pixel ID, bạn thiết lập TikTok Event API theo định dạng như phần ảnh mẫu : **TikTok Pixel ID|API**  (thay TikTok Pixel ID bằng ID bạn đã thiết lập trong mục tài khoản liên kết ở bước 2, **ký tự API giữ nguyên là chữ viết hoa, không thay đổi**)

<figure><img src="../../../.gitbook/assets/image (328).png" alt=""><figcaption></figcaption></figure>

Bấm Đóng, xuất bản lại trang Landing Page để cập nhật lại thông tin lên trang của bạn.
