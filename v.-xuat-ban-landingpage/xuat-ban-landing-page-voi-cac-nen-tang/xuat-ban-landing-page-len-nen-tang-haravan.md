# Xuất bản Landing Page lên nền tảng Haravan

Để tải Landing Page lên nền tảng Haravan trước tiên bạn cần phải có tài khoản tại Haravan. Sau đó bạn có thể thực hiện theo các bước sau đây:

**Bước 1: Tạo bản ghi xác thực tên miền:**

* Bạn cần vào phần quản lý tên miền chính của mình.
* Tạo bản ghi sau trong phần quản lý DNS của tên miền:\
  **Host Record:** ladipageverify\
  **Type (Loại):** CNAME\
  **Value (Giá trị):** [dns.ladipage.com](http://dns.ladipage.com/)

**Ghi chú:** Bản ghi này chỉ có mục đích xác thực tên miền của bạn trong tài khoản LadiPage để bỏ logo LadiPage ở chân trang và không ảnh hưởng tới các bản ghi hiện tại của bạn đang có. Tài khoản LadiPage starter- miễn phí mặc định có logo LadiPage dưới chân tran&#x67;**.**

**Bước 2: Thêm tên miền trong tài khoản LadiPage:**

* Đăng nhập tài khoản LadiPage, chọn mục  **LandingPage ->Tên miền** bấm chọn **Tạo tên miền mới (lưu ý xác thực email tài khoản đối với tài khoản LadiPage Starter - Miễn phí để tạo được tên miền mới,** [**hướng dẫn chi tiết tại đây)**](../../vii.-quan-ly-landingpage/chinh-sua-thong-tin-tai-khoan.md)**.**&#x20;
* Chọn **Nền tảng** - **Haravan** sau đó nhập **Tên miền của bạn** (điền đúng định dạng tên miền của bạn tại nền tảng Haravan) và nhập **đường dẫn trang quản lý Haravan (như hình dưới) vào ô API URL:**

<figure><img src="../../.gitbook/assets/image (1219).png" alt=""><figcaption></figcaption></figure>

![](<../../.gitbook/assets/image (503).png>)

* Chọn **Tạo tên miền** và Đăng nhập tài khoản Haravan của bạn (Nếu đã đăng nhập rồi có thể bỏ qua bước này).

![](<../../.gitbook/assets/image (368).png>)

**Bước 3: Xác thực tên miền:**

Sau khi thêm tên miền, bạn bấm vào icon ... chọn Xác thực tên miền.

<figure><img src="../../.gitbook/assets/image (1220).png" alt=""><figcaption></figcaption></figure>

**Bước 4: Xuất bản landing page với tên miền nền tảng Haravan:**

* Trong trang chỉnh sửa landing page, bấm **Xuất bản.**
* Chọn mục **Tên miền riêng** và chọn **tên miền riêng nền tảng Haravan** của bạn.
* Nhập tên thư mục con mà bạn muốn tạo sau dấu "/".
* Bấm nút **Xuất bản lại** để tải Landing Page lên Haravan. Sau khi xuất bản xong ngay lập tức bạn có thể truy cập vào đường dẫn vừa được xuất bản thành công.

![](<../../.gitbook/assets/xuất bản với tên miền riêng (2).png>)

{% hint style="warning" %}
**Lưu ý:**&#x20;

* Tên miền chọn nền tảng Haravan sẽ không bật được SSL trong tài khoản LadiPage.
* Các trang landing page xuất bản với nền tảng Haravan sẽ nằm trong mục Trang Nội Dung của Haravan, vì vậy trang sẽ mặc định hiển thị có chữ "pages", ví dụ: tenmiencuaban.com/pages/landingpage. Phần này hiển thị theo định dạng của Haravan.
* Các trang landing page xuất bản với nền tảng Haravan sẽ không có báo cáo LadiPage (Người truy cập, chuyển đổi, chuyển đổi duy nhất, tỷ lệ chuyển đổi và doanh thu).
{% endhint %}
