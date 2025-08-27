# 7. Đồng bộ đơn hàng từ Landing Page sang Shopify

## **Bước 1 : Tạo tài khoản liên kết.**

**Cách 1 : Tạo tài khoản liên kết từ mục Cài đặt** \
Truy cập trang [builder.ladipage.com](http://builder.ladipage.com/), chọn menu **Cài đặt -> Tích hợp-> Tài khoản liên kết**. Sau đó lựa chọn Loại tài khoản là **Shopify**

<figure><img src="../.gitbook/assets/image (1320).png" alt=""><figcaption></figcaption></figure>

**Cách 2 : Tạo tài khoản liên kết từ mục Landing Pages -> Cấu hình form**

Truy cập trang [builder.ladipage.com](http://builder.ladipage.com/), chọn menu Landing Pages **-> Cấu hình form-> Tạo cấu hình form -> Form data -> Tạo tài khoản liên kết .**&#x53;au đó lựa chọn Loại tài khoản là **Shopify.**

<figure><img src="../.gitbook/assets/image (1297).png" alt=""><figcaption><p>Chọn Tạo cấu hình form -> Form data </p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (1298).png" alt=""><figcaption><p>Chọn Tạo tài khoản liên kết</p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (1322).png" alt=""><figcaption></figcaption></figure>

## **Bước 2:** Nhập đầy đủ các thông tin:

**Tên Liên kết:** là tên để phân biệt với các liên kết khác.

<figure><img src="../.gitbook/assets/image (1323).png" alt=""><figcaption></figcaption></figure>

**Cách lấy các thông tin của bên Shopify**&#x20;

{% embed url="https://www.loom.com/share/94c12e4153e546b0a88cf027d9e923fe" %}

{% hint style="danger" %}
Bạn cần dán đường dẫn builder như trong hình tại app shopify của bạn:
{% endhint %}

<figure><img src="../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

* App URL: https://app.ladipage.com/
* Preferences URL: https://app.ladipage.com/
* Allowed redirection URL: https://app.ladipage.com/auth/shopify.html

<figure><img src="../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

![Cách lấy API URL ](<../.gitbook/assets/image (988).png>)

## Bước 3: **Tạo** cấu hình lưu trữ form.

Vào lại trang builder.ladipage.com, chọn menu **Landing Pages -> Cấu hình form-> Tạo cấu hình form -> Form Data** **.** Bạn bấm nút **Chọn** để sử dụng tài khoản liên kết bạn muốn dùn&#x67;**.**

<figure><img src="../.gitbook/assets/image (1300).png" alt=""><figcaption></figcaption></figure>

Bấm nút **Chọn** để sử dụng tài khoản liên kết **Shopify** bạn muốn dùng.

![](<../.gitbook/assets/image (982).png>)

Nhập **Tên cấu hình** để lưu lại cấu hình form vừa tạo và bấm nút **Hoàn tất.**

![](<../.gitbook/assets/image (513).png>)

Bạn có thể chọn **thêm tài khoản liên kết** khác cho Cấu hình này. Mỗi cấu hình được chứa tối đa 3 tài khoản liên kết, tương đương với 3 nguồn lưu trữ thông tin khách hàng đồng thời nhận được từ form đăng ký trên Landing Page.

## **Bước 4: thiết lập trên form đăng ký** &#x20;

Quay trở lại form trên trang Landing Page, chọn toàn form bạn đang muốn cài đặt và chọn **"Lưu data":**

![](<../.gitbook/assets/image (279).png>)

## **Bước 5 : thiết lập sản phẩm**

&#x20;Sau khi chọn cấu hình form, bạn cần phải vào form dăng ký của bạn, chọn SẢN PHẨM trên Shopify sẽ hiển thị trên form của bạn theo [chi tiết hướng dẫn tại đây](https://help.ladipage.vn/dong-bo-don-hang-sang-cac-nen-tang-website-thuong-mai-dien-tu-va-phan-mem-quan-ly-ban-hang/tao-form-dang-ky-lien-ket-voi-cac-website-thuong-mai-dien-tu-phan-mem-quan-ly-ban-hang).

Vậy là bạn đã hoàn thành việc đồng bộ đơn hàng từ Landing Page sang mục **Orders trên Shopify.**

![](<../.gitbook/assets/image (379).png>)

![](<../.gitbook/assets/image (236).png>)

![](<../.gitbook/assets/image (741).png>)

**Lưu ý: Đối với trường thông tin giao hàng (shipping address) thì phần First Name và Last Name sẽ bị lặp lại trùng nhau, và thông tin địa chỉ sẽ chỉ thêm được vào mục Address và City.**
