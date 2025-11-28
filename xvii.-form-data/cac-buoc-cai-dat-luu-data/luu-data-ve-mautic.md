# Lưu data về Mautic

## **Bước 1: Tạo tài khoản liên kết**

**Cách 1 : Tạo tài khoản liên kết từ mục Cài đặt** \
Truy cập trang [builder.ladipage.com](http://builder.ladipage.com/), chọn menu **Cài đặt -> Tích hợp-> Tài khoản liên kết**. Sau đó lựa chọn Loại tài khoản là **Mautic**

<figure><img src="../../.gitbook/assets/image (1413).png" alt=""><figcaption></figcaption></figure>

**Cách 2 : Tạo tài khoản liên kết từ mục Landing Pages -> Cấu hình form**

Truy cập trang [builder.ladipage.com](http://builder.ladipage.com/), chọn menu **Landing Pages -> Cấu hình form-> Tạo cấu hình form -> Form data -> Tạo tài khoản liên kết .**&#x53;au đó lựa chọn Loại tài khoản là **Mautic**

<figure><img src="../../.gitbook/assets/image (1297).png" alt=""><figcaption><p>Chọn Tạo cấu hình form -> Form data </p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (1298).png" alt=""><figcaption><p>Chọn Tạo tài khoản liên kết</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (1412).png" alt=""><figcaption></figcaption></figure>

**Cách 3 :** Truy cập builder chỉnh sửa trang landingpage muốn lưu data về **Mautic**, ở phần **Form đăng ký, mục Lưu data, bấm Thêm mới , chọn Tạo liên kết ->Loại tài khoản là Mautic**<br>

<figure><img src="../../.gitbook/assets/image (27).png" alt=""><figcaption></figcaption></figure>

![](<../../.gitbook/assets/image (576).png>)

**Bước 2:** Nhập đầy đủ các thông tin:

**Tên liên kết:** là tên để phân biệt với các liên kết khác.&#x20;

**API URL:**  copy đường dẫn url trên link admin của bạn

![](<../../.gitbook/assets/image (260).png>)

&#x20;**Public Key, Secret Key** là  key kết nối lấy trong tài khoản Mautic



![](<../../.gitbook/assets/image (579).png>)

**\*Cách lấy Public Key, Secret Key**&#x20;

Đăng nhập tài khoản Mautic-> API Credentials tạo Public Key, Secret Key

Authorization Protocol : bạn phải chọn là OAuth 2

Name: tên gọi nhớ cho API key của bạn

Redirect URL : [https://builder.ladipage.com/auth/mautic.html ](https://builder.ladipage.com/auth/mautic.html) đây là đường dẫn BẮT BUỘC phải sử dụng khi thiết lập API, KHÔNG được thay đổi&#x20;

![](<../../.gitbook/assets/image (1008).png>)

![](<../../.gitbook/assets/image (646).png>)

## Bước 3: **Tạo** cấu hình lưu trữ form&#x20;

Vào lại trang builder.ladipage.com, chọn menu **Landing Pages-> Cấu hình Form -> Tạo cấu hình form.**

<figure><img src="../../.gitbook/assets/cấu hình form (2).gif" alt=""><figcaption></figcaption></figure>

Bấm nút **Chọn** để sử dụng tài khoản liên kết bạn muốn dùng&#x20;

![](<../../.gitbook/assets/image (589).png>)

![](<../../.gitbook/assets/image (942).png>)

**Đồng bộ các trường thông tin**

Bạn cần ghép các trường thông tin tương ứng của 2 form với nhau. Bên tay trái là các trường thông tin bạn đã tạo trên form ở landing page, bên phải là các trường thông tin bạn tạo trên **Mautic**

Bạn vào builder chỉnh sửa của landing page, Form đăng ký muốn thiết lập lưu trữ, bạn thiết lập đầy đủ trường của form theo ý bạn muốn, ví dụ 4 trường: họ và tên, email, số điện thoại, để lại tin nhắn cho chúng tôi.

Mỗi trường sẽ tương ứng với **1 TÊN LẤY DỮ LIỆU** (như ảnh mô tả )

![](<../../.gitbook/assets/image (283).png>)

**TÊN LẤY DỮ LIỆU** sẽ hiển thị ở cột bên trái trong phần cấu hình tài khoản liên kết

Bạn có thể chọn **thêm tài khoản liên kết** khác cho Cấu hình này. Mỗi cấu hình được chứa tối đa 3 tài khoản liên kết, tương đương với 3 nguồn lưu trữ thông tin khách hàng đồng thời nhận được từ form đăng ký trên Landing Page.

![](<../../.gitbook/assets/image (588).png>)

## **Bước 4: Thiết lập Lưu data cho form**

&#x20;Quay trở lại form trên trang Landing Page, chọn toàn form bạn đang muốn cài đặt và chọn **"Lưu data":**

![](<../../.gitbook/assets/image (279).png>)

## **Bước 5: Sử dụng cấu hình form**

Chọn cấu hình phù hợp trong danh sách cấu hình form đã được cài đặt ở bước 3, sau đó bấm **Cập nhật** để hoàn thành.

