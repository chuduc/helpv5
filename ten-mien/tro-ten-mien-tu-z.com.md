# Trỏ tên miền từ Z.com

Truy cập trang quản trị tên miền của Z.com và nhập thông tin tài khoản:\
[https://domain.z.com/vn/](https://domain.z.com/vn/)

\[1] Từ trình đơn phía trên, click vào \[DNS].

![](<../.gitbook/assets/image (484).png>)

\[2] Chọn tên miền mà bạn muốn thiết lập bản ghi CNAME và click vào biểu tượng \[Chỉnh sửa].

![](<../.gitbook/assets/image (466).png>)

\[3] Click vào biểu tượng \[+].

![](<../.gitbook/assets/image (288).png>)

**TRỎ TÊN MIỀN CHÍNH**

**Thêm mới** 2 bản ghi sau:

Host record (Tên): www\
Type (Loại): CNAME\
Value (Giá trị): dns.ladipage.com

Host record: @\
Type (Loại): URL Redirect\
Value (Giá trị): http://www.tenmiencuaban.com\
Lưu ý: Thay tenmiencuaban.com thành tên miền bạn đang cấu hình.

Nhập từng mục, sau đó click \[Lưu].

**TRỎ TÊN MIỀN PHỤ**

Giả sử tên miền chính của bạn là tenmiencuaban.com, và bạn muốn tạo một tên miền phụ là [sanphama.tenmiencuaban.com](http://sanphama.tenmiencuaban.com/) thì:\
Chọn tên miền chính bạn muốn cài đặt, sau đó tạo một bản ghi mới và điền các giá trị như sau:\
Host record (Tên): sanphama\
Type (Loại): CNAME\
Value (Giá trị): [dns.ladipage.com](http://dns.ladipage.com/)

Sau khi đã tạo thành công bản ghi tên miền về hosting của LadiPage, bạn chờ bản ghi tên miền cập nhật thành công về LadiPage, sau đó bạn cần tiếp tục làm bước tiếp theo: [**tạo và xác thực tên miền trên tài khoản LadiPage**](https://help.ladipage.vn/ten-mien/xac-thuc-ten-mien-tai-ladipage)**.**

{% content-ref url="xac-thuc-ten-mien-tai-ladipage.md" %}
[xac-thuc-ten-mien-tai-ladipage.md](xac-thuc-ten-mien-tai-ladipage.md)
{% endcontent-ref %}
