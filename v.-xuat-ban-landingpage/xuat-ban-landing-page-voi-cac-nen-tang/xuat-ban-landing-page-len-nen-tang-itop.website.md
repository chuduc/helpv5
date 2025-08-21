# Xuất bản Landing Page lên nền tảng iTop.website

Để tải Landing Page lên nền tảng iTop.website trước tiên bạn cần phải có tài khoản tại iTop.website. Sau đó bạn có thể thực hiện theo các bước sau đây:

**Bước 1: Tạo bản ghi sau trong phần quản lý DNS của tên miền:**

Bản ghi này chỉ có mục đích xác thực tên miền trong tài khoản LadiPage để bỏ logo LadiPage ở chân trang và không ảnh hưởng tới các bản ghi hiện tại của bạn đang có:\
**Host Record:** ladipageverify\
**Type (Loại):** CNAME\
**Value (Giá trị):** [dns.ladipage.com](http://dns.ladipage.com/)

**Bước 2:** Đăng nhập trang quản trị của bạn tại iTop.website. Chọn mục **Trang Nội Dung** sau đó bấm chọn Lấy mã tích hợp LadiPage.

![](<../../.gitbook/assets/image (826).png>)

**Bước 3:** Lưu lại API URL và API Key.

![](<../../.gitbook/assets/image (485).png>)

**Bước 4:** Tại trang **Landing Page -> Tên miền** bấm chọn **Tạo tên miền mới (lưu ý xác thực email tài khoản đối với tài khoản LadiPage Starter - Miễn phí để tạo được tên miền mới,** [**hướng dẫn chi tiết tại đây**](https://help.ladipage.vn/chinh-sua-thong-tin-tai-khoan#xac-thuc-email-tai-khoan)**).**

\
**Bước 5:** Mục **Nền tảng** chọn **iTop.website** sau đó nhập API URL và API KEY mà bạn lưu lại ở bước 3 và bấm nút **Tạo tên miền** để hoàn tất.

<figure><img src="../../.gitbook/assets/image (1223).png" alt=""><figcaption></figcaption></figure>

**Bước 6: Xác thực tên miền.**

Sau khi thêm tên miền, bạn bấm vào icon ... chọn Xác thực tên miền.

<figure><img src="../../.gitbook/assets/image (1224).png" alt=""><figcaption></figcaption></figure>

**Bước 7: Xuất bản landing page lên Itop.**

1\. Trong trang chỉnh sửa landing page, bấm **Xuất bản.**\
2\. Chọn mục **Tên miền riêng** và chọn **tên miền riêng nền tảng Itop** của bạn.\
3\. Nhập đường dẫn mà bạn muốn.\
4\. Bấm nút **Xuất bản lại** để tải Landing Page lên iTop.website. Sau khi xuất bản xong ngay lập tức bạn có thể truy cập vào đường dẫn vừa được xuất bản thành công.

![](<../../.gitbook/assets/xuất bản với tên miền riêng.png>)

{% hint style="warning" %}
**Lưu ý:**&#x20;

* Tên miền chọn nền tảng Itop sẽ không bật được SSL trong tài khoản LadiPage.
* Các trang landing page xuất bản với nền tảng Itop sẽ không có báo cáo của LadiPage (Người truy cập, chuyển đổi, chuyển đổi duy nhất, tỷ lệ chuyển đổi và doanh thu).
{% endhint %}
