# Lưu data về Automation

## **Bước 1: Tạo tài khoản liên kết**

**Cách 1 : Tạo tài khoản liên kết từ mục Cài đặt** \
Truy cập trang [builder.ladipage.com](http://builder.ladipage.com/), chọn menu **Cài đặt -> Tích hợp-> Tài khoản liên kết**. Sau đó lựa chọn Loại tài khoản là **Automation**

<figure><img src="../../.gitbook/assets/image (25).png" alt=""><figcaption></figcaption></figure>

**Cách 2 : Tạo tài khoản liên kết từ mục Landing Pages -> Cấu hình form**

Truy cập trang [builder.ladipage.com](http://builder.ladipage.com/), chọn menu Landing Pages **-> Cấu hình form-> Tạo cấu hình form -> Form data -> Tạo tài khoản liên kết .**&#x53;au đó lựa chọn Loại tài khoản là **Automation**

<figure><img src="../../.gitbook/assets/image (1297).png" alt=""><figcaption><p>Chọn Tạo cấu hình form -> Form data </p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (1298).png" alt=""><figcaption><p>Chọn Tạo tài khoản liên kết</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (26).png" alt=""><figcaption></figcaption></figure>

**Cách 3 :** Truy cập builder chỉnh sửa trang landingpage muốn lưu data về  **Automation**, ở phần **Form đăng ký, mục Lưu data, bấm Thêm mới , chọn Tạo liên kết ->Loại tài khoản là** **Automation**

<figure><img src="../../.gitbook/assets/image (27).png" alt=""><figcaption></figcaption></figure>

## **Bước 2:** Nhập đầy đủ các thông tin:

**Tên Liên kết:** là tên để phân biệt với các liên kết khác.&#x20;

**API KEY** :  lấy từ tài khoản Automation của bạn

Ấn **Thêm tài khoản** để Lưu.

<figure><img src="../../.gitbook/assets/image (28).png" alt=""><figcaption></figcaption></figure>

**\*Cách lấy API KEY của Automation**

Đăng nhập tài khoản builder.ladipage.com -> Cài đặt -> Webhook & API -> API&#x20;

<figure><img src="../../.gitbook/assets/image (57).png" alt=""><figcaption></figcaption></figure>

Bấm ![](<../../.gitbook/assets/image (58).png>) và tích phân quyền **Automation và bấm Tạo API để lưu thành công**&#x20;

<figure><img src="../../.gitbook/assets/image (59).png" alt=""><figcaption></figcaption></figure>

Vào lại phần danh sách API, copy API KEY bạn muốn sử dụng cho phần tích hợp&#x20;

<figure><img src="../../.gitbook/assets/image (60).png" alt=""><figcaption></figcaption></figure>

## Bước 3: **Tạo** cấu hình lưu trữ form&#x20;

Vào lại trang builder.ladipage.com, chọn menu **Tích hợp -> Cấu hình Form -> Tạo cấu hình form.**

<figure><img src="../../.gitbook/assets/cấu hình form (2).gif" alt=""><figcaption></figcaption></figure>

Bấm nút **Chọn** để sử dụng tài khoản liên kết bạn muốn dùng&#x20;

{% embed url="https://prnt.sc/3JcflV7sisVg" %}

{% embed url="https://prnt.sc/SsKP17ENbDtD" %}

Điền các thông tin ở phần thiết lập cấu hình form và bấm Tiếp tục để lưu lại thông tin&#x20;

**Đồng bộ các trường thông tin**

Bạn cần ghép các trường thông tin tương ứng của 2 form với nhau. Bên tay trái là các trường thông tin bạn đã tạo trên form ở landing page, bên phải là các trường thông tin bạn tạo trên **LadiFlow**

Bạn vào builder chỉnh sửa của landing page, Form đăng ký muốn thiết lập lưu trữ, bạn thiết lập đầy đủ trường của form theo ý bạn muốn, ví dụ 4 trường: họ và tên, email, số điện thoại, để lại tin nhắn cho chúng tôi.

Mỗi trường sẽ tương ứng với **1 TÊN LẤY DỮ LIỆU** (như ảnh mô tả )

![](<../../.gitbook/assets/image (283).png>)

**TÊN LẤY DỮ LIỆU** sẽ hiển thị ở cột bên trái trong phần cấu hình tài khoản liên kết

{% embed url="https://prnt.sc/X9ZrXjG90d6w" %}

Nhập **Tên cấu hình** để lưu lại cấu hình form vừa tạo và bấm nút **Hoàn tất**&#x20;

{% embed url="https://prnt.sc/y7WNa3kuJI8o" %}

Bạn có thể chọn **thêm tài khoản liên kết** khác cho Cấu hình này. Mỗi cấu hình được chứa tối đa 3 tài khoản liên kết, tương đương với 3 nguồn lưu trữ thông tin khách hàng đồng thời nhận được từ form đăng ký trên Landing Page.

## **Bước 4: Thiết lập Lưu data cho form**

Quay trở lại form trên trang Landing Page, chọn toàn form bạn đang muốn cài đặt và chọn **"Lưu data":**

![](<../../.gitbook/assets/image (279).png>)

## **Bước 5: Sử dụng cấu hình form**&#x20;

Chọn cấu hình phù hợp trong danh sách cấu hình form đã được cài đặt ở bước 3, sau đó bấm **Cập nhật** để hoàn thành.
