# Trỏ tên miền từ PA Việt nam

Truy cập trang quản trị tên miền của P.A Việt Nam và nhập thông tin tài khoản:\
&#x20;[https://access.pavietnam.vn/](https://access.pavietnam.vn/login.php)

1. **Trỏ tên miền chính:**

Trong mục **Default/ Cấu hình domain**, bạn Thêm mới 2 bản ghi sau:

Host: www\
Loại: CNAME\
Địa chỉ: dns.ladipage.com

Host: @\
Loại: URL Redirect\
Địa chỉ: http://www.tenmiencuaban.com\
Lưu ý: Thay tenmiencuaban.com thành tên miền bạn đang cấu hình.

**2. Trỏ tên miền phụ:**&#x20;

Giả sử tên miền chính của bạn là tenmiencuaban.com, và bạn muốn tạo một tên miền phụ là [sanphama.tenmiencuaban.com.](http://sanphama.tenmiencuaban.com/)\
Chọn tên miền chính bạn muốn cài đặt, sau đó tạo một bản ghi mới và điền các giá trị như sau:\
Host: sanphama\
Loại: CNAME\
Địa chỉ: [dns.ladipage.com](http://dns.ladipage.com/)

![](<../.gitbook/assets/image (292).png>)

Sau khi đã tạo thành công bản ghi tên miền về hosting của LadiPage, bạn chờ bản ghi tên miền cập nhật thành công về LadiPage, sau đó bạn cần tiếp tục làm bước tiếp theo: [**tạo và xác thực tên miền trên tài khoản LadiPage**](https://help.ladipage.vn/ten-mien/xac-thuc-ten-mien-tai-ladipage)**.**

{% content-ref url="xac-thuc-ten-mien-tai-ladipage.md" %}
[xac-thuc-ten-mien-tai-ladipage.md](xac-thuc-ten-mien-tai-ladipage.md)
{% endcontent-ref %}
