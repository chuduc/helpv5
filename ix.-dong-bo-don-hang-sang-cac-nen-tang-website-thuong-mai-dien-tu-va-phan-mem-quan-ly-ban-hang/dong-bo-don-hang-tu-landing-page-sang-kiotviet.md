# 8. Đồng bộ đơn hàng từ Landing Page sang KiotViet

Để đồng bộ đơn hàng từ LadiPage lên KiotViet, trước tiên bạn cần phải có tài khoản tại **KiotViet** và tạo các sản phẩm ở mục Hàng Hóa-Danh Mục của KiotViet.

Sau đó bạn có thể thực hiện theo các bước sau đây:

## **Bước 1 : Tạo tài khoản liên kết.**

**Cách 1 : Tạo tài khoản liên kết từ mục Cài đặt** \
Truy cập trang [builder.ladipage.com](http://builder.ladipage.com/), chọn menu **Cài đặt -> Tích hợp-> Tài khoản liên kết**. Sau đó lựa chọn Loại tài khoản là **KiotViet.**

<figure><img src="../.gitbook/assets/image (1326).png" alt=""><figcaption></figcaption></figure>

**Cách 2 : Tạo tài khoản liên kết từ mục Landing Pages -> Cấu hình form**

Truy cập trang [builder.ladipage.com](http://builder.ladipage.com/), chọn menu Landing Pages **-> Cấu hình form-> Tạo cấu hình form -> Form data -> Tạo tài khoản liên kết .**&#x53;au đó lựa chọn Loại tài khoản là **KiotViet**

<figure><img src="../.gitbook/assets/image (1297).png" alt=""><figcaption><p>Chọn Tạo cấu hình form -> Form data </p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (1298).png" alt=""><figcaption><p>Chọn Tạo tài khoản liên kết</p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (1329).png" alt=""><figcaption></figcaption></figure>

## **Bước 2:** Nhập đầy đủ các thông tin:

**Tên Liên kết:** là tên để phân biệt với các liên kết khác.&#x20;

**Client ID, Mã bảo mật**: lấy từ tài khoản KiotViet của bạn.

<figure><img src="../.gitbook/assets/image (1330).png" alt=""><figcaption></figcaption></figure>

**Cách lấy các thông số kết nối trong KiotViet.**

![](<../.gitbook/assets/image (1161).png>)

{% hint style="danger" %}
**Lưu ý: phần TÊN KẾT NỐI phải Trùng với phần tên trong link đăng nhập kiotviet của bạn, ví dụ như trong hướng dẫn, tên kết nối là check1111, giống với tên trong đường dẫn đăng nhập tài khoản.**&#x20;
{% endhint %}

#### ![](<../.gitbook/assets/image (1070).png>)

## Bước 3: **Tạo** cấu hình lưu trữ form.

Vào lại trang builder.ladipage.com, chọn menu **Landing Pages -> Cấu hình form-> Tạo cấu hình form -> Form Data** **.** Bạn bấm nút **Chọn** để sử dụng tài khoản liên kết bạn muốn dùn&#x67;**.**

<figure><img src="../.gitbook/assets/image (1300).png" alt=""><figcaption></figcaption></figure>

Bấm nút **Chọn** để sử dụng tài khoản liên kết bạn muốn dùn&#x67;**.**

![](<../.gitbook/assets/image (1099).png>)

Nhập **Tên cấu hình** để lưu lại cấu hình form vừa tạo và bấm nút **Hoàn tất.**&#x20;

![](<../.gitbook/assets/image (1149).png>)

Bạn có thể chọn **thêm tài khoản liên kết** khác cho Cấu hình này. Mỗi cấu hình được chứa tối đa 3 tài khoản liên kết, tương đương với 3 nguồn lưu trữ thông tin khách hàng đồng thời nhận được từ form đăng ký trên Landing Page.

## **Bước 4: thiết lập trên form đăng ký**&#x20;

&#x20;Quay trở lại form trên trang Landing Page, chọn toàn form bạn đang muốn cài đặt và chọn **"Lưu data":**

![](<../.gitbook/assets/image (279).png>)

## **Bước 5 : thiết lập sản phẩm**

Sau khi chọn cấu hình form, bạn cần phải vào form dăng ký của bạn, chọn SẢN PHẨM trên KiotViet sẽ hiển thị trên form của bạn theo [chi tiết hướng dẫn tại đây](https://help.ladipage.vn/dong-bo-don-hang-sang-cac-nen-tang-website-thuong-mai-dien-tu-va-phan-mem-quan-ly-ban-hang/tao-form-dang-ky-lien-ket-voi-cac-website-thuong-mai-dien-tu-phan-mem-quan-ly-ban-hang).

{% hint style="danger" %}
**`Lưu ý:`**

`Bạn muốn chọn sản phẩm từ KiotViet để hiển thị trên form của LadiPage,thì KHÔNG tìm kiếm theo tên sản phẩm mà tìm kiếm bằng`**`MÃ HÀNG`**`ở bên KiotViet.`
{% endhint %}

![](<../.gitbook/assets/image (1060).png>)

Vậy là bạn đã hoàn thành việc đồng bộ đơn hàng từ Landing Page sang mục **Giao dịch, đặt hàng của KiotViet.**

![](<../.gitbook/assets/image (243).png>)

![Thông tin đơn hàng trong KiotViet](<../.gitbook/assets/image (980).png>)

![Chi tiết phần thông tin khách hàng trong KiotViet](<../.gitbook/assets/image (985).png>)

{% hint style="danger" %}
**Lưu ý:** Ở KiotViet, nếu bạn không cho phép đặt hàng khi hết hàng, thì đơn hàng sẽ không về phần quản lý của KiotViet khi khách hàng đặt hàng quá số lượng tồn kho của sản phẩm đó. Thông tin cài đặt này bạn có thể kiểm tra ở mục như ảnh hướng dẫn (Thiết lập, Giao dịch, Đặt hàng).
{% endhint %}

<figure><img src="../.gitbook/assets/image (259).png" alt=""><figcaption></figcaption></figure>
