# Trỏ tên miền từ Tenten

Truy cập trang quản trị tên miền của Tenten và nhập thông tin tài khoản:\
&#x20;[https://domain.tenten.vn/](https://domain.tenten.vn/)

1. **Trỏ tên miền chính:**

**Thêm mới** 2 bản ghi sau:

Host record: www\
Type (Loại): CNAME\
Value (Giá trị): dns.ladipage.com

Host record: @\
Type (Loại): URL Redirect\
Value (Giá trị):   http://www.tenmiencuaban.com\
Lưu ý: Thay tenmiencuaban.com thành tên miền bạn đang cấu hình.

&#x20;  **2. Trỏ tên miền phụ:**&#x20;

Giả sử tên miền chính của bạn là tenmiencuaban.com, và bạn muốn tạo một tên miền phụ là [sanphama.tenmiencuaban.com](http://sanphama.tenmiencuaban.com/) thì:\
Chọn tên miền chính bạn muốn cài đặt, sau đó tạo một bản ghi mới và điền các giá trị như sau:\
Host record: sanphama\
Type (Loại): CNAME\
Value (Giá trị): [dns.ladipage.com](http://dns.ladipage.com/)

![](<../.gitbook/assets/image (1044).png>)

Sau khi đã tạo thành công bản ghi tên miền về hosting của LadiPage, bạn chờ bản ghi tên miền cập nhật thành công về LadiPage, sau đó bạn cần tiếp tục làm bước tiếp theo: [**tạo và xác thực tên miền trên tài khoản LadiPage**](https://help.ladipage.vn/ten-mien/xac-thuc-ten-mien-tai-ladipage)**.**

{% content-ref url="xac-thuc-ten-mien-tai-ladipage.md" %}
[xac-thuc-ten-mien-tai-ladipage.md](xac-thuc-ten-mien-tai-ladipage.md)
{% endcontent-ref %}

{% hint style="danger" %}
**Trong trường hợp bạn sử dụng** [secureweb.vn](http://secureweb.vn/) là host của tenten, sẽ không có cpanel để tạo bản ghi như các host khác, mà sẽ vào phần cài đặt của host, cũng không tạo bản ghi trong tenten đơn thuần, hướng dẫn chi tiết : [https://tenten.vn/help/huong-dan-su-dung-dns-setting-tren-secureweb-hosting/](https://tenten.vn/help/huong-dan-su-dung-dns-setting-tren-secureweb-hosting/)
{% endhint %}
