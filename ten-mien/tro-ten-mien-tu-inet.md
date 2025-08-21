# Trỏ tên miền từ iNET

Truy cập trang chủ iNET tại [https://inet.vn/](https://inet.vn/) và chọn **Đăng nhập**. Sau đó nhập thông tin tài khoản khách hàng tại iNET để đăng nhập hệ thống quản trị.

![](<../.gitbook/assets/image (856).png>)

Tại phần quản lý danh sách dịch vụ bạn chọn dịch vụ là **Tên miền** sau đó Chọn tên miền cần trỏ và chọn **Cập nhật bản ghi.**

![](<../.gitbook/assets/image (355).png>)

## Trỏ tên miền chính.

Bạn tạo 02 bản ghi dùng để trỏ tên miền chính về hosting LadiPage như sau:

Host record: www\
Type (Loại): CNAME\
Value (Giá trị): dns.ladipage.com

Host record: @\
Type (Loại): URL Redirect\
Value (Giá trị):   http://www.tenmiencuaban.com\
Lưu ý: Thay tenmiencuaban.com thành tên miền bạn đang cấu hình.

## Trỏ tên miền phụ.&#x20;

Giả sử tên miền chính của bạn là tenmiencuaban.com, và bạn muốn tạo một tên miền phụ là [sanphama.tenmiencuaban.com](http://sanphama.tenmiencuaban.com/) thì:\
Chọn tên miền chính bạn muốn cài đặt, sau đó tạo một bản ghi mới và điền các giá trị như sau:\
Host record: sanphama\
Type (Loại): CNAME\
Value (Giá trị): [dns.ladipage.com](http://dns.ladipage.com/)

Sau khi đã tạo thành công bản ghi tên miền về hosting của LadiPage, bạn chờ bản ghi tên miền cập nhật thành công về LadiPage, sau đó bạn cần tiếp tục làm bước tiếp theo: [**tạo và xác thực tên miền trên tài khoản LadiPage**](https://help.ladipage.vn/ten-mien/xac-thuc-ten-mien-tai-ladipage)**.**

{% content-ref url="xac-thuc-ten-mien-tai-ladipage.md" %}
[xac-thuc-ten-mien-tai-ladipage.md](xac-thuc-ten-mien-tai-ladipage.md)
{% endcontent-ref %}

