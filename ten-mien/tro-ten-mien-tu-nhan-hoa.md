# Trỏ tên miền từ Nhân Hòa

Truy cập trang quản trị tên miền của Nhân Hòa và nhập thông tin tài khoản: [https://zonedns.vn/](https://zonedns.vn/)

1. **Trỏ tên miền chính:**

Bạn thêm mới 2 bản ghi sau:

Tên record: www\
Loại record: CNAME\
Giá trị record: dns.ladipage.com

Tên record: @\
Loại record: URL Redirect\
Giá trị record:   http://www.tenmiencuaban.com\
Lưu ý: Thay tenmiencuaban.com thành tên miền bạn đang cấu hình.

![](<../.gitbook/assets/image (489).png>)

**2. Trỏ tên miền phụ:**&#x20;

![](<../.gitbook/assets/image (851).png>)

Giả sử tên miền chính của bạn là tenmiencuaban.com, và bạn muốn tạo một tên miền phụ là [sanphama.tenmiencuaban.com](http://sanphama.tenmiencuaban.com/) thì:\
Chọn tên miền chính bạn muốn cài đặt, sau đó tạo một bản ghi mới và điền các giá trị như sau:\
Tên record: sanphama\
Loại record: CNAME\
Giá trị record: [dns.ladipage.com](http://dns.ladipage.com/)

Sau khi đã tạo thành công bản ghi tên miền về hosting của LadiPage, bạn chờ bản ghi tên miền cập nhật thành công về LadiPage, sau đó bạn cần tiếp tục làm bước tiếp theo: [**tạo và xác thực tên miền trên tài khoản LadiPage**](https://help.ladipage.vn/ten-mien/xac-thuc-ten-mien-tai-ladipage)**.**

{% content-ref url="xac-thuc-ten-mien-tai-ladipage.md" %}
[xac-thuc-ten-mien-tai-ladipage.md](xac-thuc-ten-mien-tai-ladipage.md)
{% endcontent-ref %}
