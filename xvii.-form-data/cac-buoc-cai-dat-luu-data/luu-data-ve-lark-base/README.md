# Lưu data về Lark Base

## **Bước 1: Tạo tài khoản liên kết.**

**Cách 1 : Tạo tài khoản liên kết từ mục Cài đặt** \
Truy cập trang [builder.ladipage.com](http://builder.ladipage.com/), chọn menu **Cài đặt -> Tích hợp-> Tài khoản liên kết**. Sau đó lựa chọn Loại tài khoản là **Lark Base**

<figure><img src="../../../.gitbook/assets/image (1414).png" alt=""><figcaption></figcaption></figure>

**Cách 2 : Tạo tài khoản liên kết từ mục Landing Pages -> Cấu hình form**

Truy cập trang [builder.ladipage.com](http://builder.ladipage.com/), chọn menu **Landing Pages -> Cấu hình form-> Tạo cấu hình form -> Form data -> Tạo tài khoản liên kết .**&#x53;au đó lựa chọn Loại tài khoản là **Lark Base**

<figure><img src="../../../.gitbook/assets/image (1297).png" alt=""><figcaption><p>Chọn Tạo cấu hình form -> Form data </p></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (1298).png" alt=""><figcaption><p>Chọn Tạo tài khoản liên kết</p></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (1415).png" alt=""><figcaption></figcaption></figure>

**Cách 3 :** Truy cập builder chỉnh sửa trang landingpage muốn lưu data về **Lark Base**, ở phần **Form đăng ký --> mục Lưu data--> bấm Thêm mới ---> chọn Tạo liên kết ->Loại tài khoản là Lark Base**

<figure><img src="../../../.gitbook/assets/image (27).png" alt=""><figcaption></figcaption></figure>

## **Bước 2:** Nhập đầy đủ các thông tin:

**Tên Liên kết:** là tên để phân biệt với các liên kết khác.&#x20;

**App ID, App Secret.** là các thông tin kết nối láy trong tài khoản Larkbase

Ấn **Thêm tài khoản** để Lưu.

{% embed url="https://prnt.sc/VNcNH7-BEOw5" %}

**\*Cách lấy các thông tin kết nối bên** [**Lark Base** ](cach-tao-app-va-lay-cac-thong-tin-ket-noi-cua-lark-base.md)

{% content-ref url="cach-tao-app-va-lay-cac-thong-tin-ket-noi-cua-lark-base.md" %}
[cach-tao-app-va-lay-cac-thong-tin-ket-noi-cua-lark-base.md](cach-tao-app-va-lay-cac-thong-tin-ket-noi-cua-lark-base.md)
{% endcontent-ref %}

## Bước 3: **Tạo** cấu hình lưu trữ form.

Vào lại trang builder.ladipage.com, chọn menu **Landing Pages -> Cấu hình Form -> Tạo cấu hình form.** Bấm nút **Chọn** để sử dụng tài khoản liên kết bạn muốn dùng

<figure><img src="../../../.gitbook/assets/cấu hình form (2).gif" alt=""><figcaption></figcaption></figure>

**Kết nối các thông tin:**

**Nhập thông tin App Token** lấy trong tài khoản Larkbase và bấm **Kết nối**&#x20;

{% embed url="https://prnt.sc/ArGfVqIHYeyq" %}

**Chọn Table (Bảng dữ liệu) muốn dữ liệu đồng bộ sang bên Lark Base**

{% embed url="https://prnt.sc/XqCDKriRnniV" %}

* **Tên lưu trữ**: là tên gợi nhắc cho cấu hình form này.
* **Table:** Bạn chọn bảng tính bạn muốn lưu trữ dữ liệu về bên Lark Base

{% hint style="info" %}
Bạn cần tạo sẵn các Table ( Bảng dữ liệu) từ bên Lark Base ,  trong mục Cấu hình Form sẽ không có phần tạo Table mới
{% endhint %}

* **Đồng bộ các trường thông tin:**&#x20;

Bên tay trái là các trường thông tin bạn đã tạo trên form ở landing page, bạn cần lấy Tên Lấy Dữ Liệu của các trường của LadiPage như bên dưới:

<figure><img src="../../../.gitbook/assets/tên lấy dữ liệu (2).png" alt=""><figcaption></figcaption></figure>

Bên phải là các trường thông tin bạn tạo trên **Lark Base**

{% embed url="https://prnt.sc/dIDzdg9Np_NE" %}

Bạn có thể chọn **thêm tài khoản liên kết** khác cho Cấu hình này. Mỗi cấu hình được chứa tối đa 3 tài khoản liên kết, tương đương với 3 nguồn lưu trữ thông tin khách hàng đồng thời nhận được từ form đăng ký trên Landing Page.

## **Bước 4: Thiết lập Lưu data cho form**

Quay trở lại form trên trang Landing Page, chọn toàn form bạn đang muốn cài đặt và chọn **"Lưu data":**

![](<../../../.gitbook/assets/image (279).png>)

## **Bước 5: Sử dụng cấu hình form**

&#x20;Chọn cấu hình phù hợp trong danh sách cấu hình form đã được cài đặt ở bước 3, sau đó bấm **Cập nhật** để hoàn thành.

{% hint style="danger" %}
Khi cấu hình lưu trữ dữ liệu về Lark Base, bạn muốn lấy các thông số của URL : URL truy cập, các thông số UTM tracking- utm source, utm medium..., bạn cần tạo các tạo các trường đó ở mục liên kết trường dữ liệu ở form LadiPage và Lark Base ở mục Cấu hình form&#x20;
{% endhint %}
