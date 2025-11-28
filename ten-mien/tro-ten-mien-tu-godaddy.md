# Trỏ tên miền từ GoDaddy

Truy cập trang quản trị tên miền của GoDaddy và nhập thông tin tài khoản.\
Trong phần **Domain Manager (Quản lý tên miền),** click vào tên miền bạn đang muốn trỏ.\
Kéo xuống phần **Additional Setting (Thiết lập bổ sung)** và chọn **Manage DNS:**

![](<../.gitbook/assets/image (276).png>)



1. **Trỏ tên miền chính:**

Thêm mới 2 bản ghi sau:

Host record: www\
Type (Loại): CNAME\
Points to: dns.ladipage.com

Type: A\
Name: @\
Points to: 13.229.38.226<br>

**2. Trỏ tên miền phụ:**&#x20;

Giả sử tên miền chính của bạn là tenmiencuaban.com, và bạn muốn tạo một tên miền phụ là [sanphama.tenmiencuaban.com.](http://sanphama.tenmiencuaban.com/)\
Chọn tên miền chính bạn muốn cài đặt, sau đó tạo một bản ghi mới và điền các giá trị như sau:\
Host record: sanphama\
Type (Loại): CNAME\
Points to: [dns.ladipage.com](http://dns.ladipage.com/)

![](<../.gitbook/assets/image (282).png>)

Sau khi đã trỏ thành công tên miền về hosting của LadiPage, bạn cần tiếp tục làm bước tiếp theo, [**tạo và xác thực tên miền trên tài khoản LadiPage**](https://help.ladipage.vn/ten-mien/xac-thuc-ten-mien-tai-ladipage)**:**

{% content-ref url="xac-thuc-ten-mien-tai-ladipage.md" %}
[xac-thuc-ten-mien-tai-ladipage.md](xac-thuc-ten-mien-tai-ladipage.md)
{% endcontent-ref %}

