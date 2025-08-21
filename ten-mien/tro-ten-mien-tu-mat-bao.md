# Trỏ tên miền từ Mắt Bão

Truy cập trang quản trị tên miền của Mắt Bão và nhập thông tin tài khoản:\
[https://id.matbao.net/users/login/](https://id.matbao.net/users/login/).

Sau đó bạn chọn lần lượt:

* Mục **Tên Miền.**
* Click vào tên miền cần trỏ.
* Vào mục **Quản lý DNS.**

**Mắt bão hiện tại có 2 giao diện cấu hình trỏ DNS, bạn xem mình đang sử dụng giao diện nào thì sử dụng theo hướng dẫn của giao diện đó.**

## **Giao diện cũ của Mắt Bão.**

**Bạn truy cập tài khoản Mắt bão--> chọn Tên miền --> Quản lý DNS để tạo bản ghi tên miền.**

1. **Trỏ tên miền chính:**

Bạn thêm mới 2 bản ghi sau:

Host record: www\
Loại: CNAME\
Giá trị: dns.ladipage.com

Host record: @\
Loại: URL Redirect\
Giá trị): http://www.tenmiencuaban.com\
Lưu ý: Thay tenmiencuaban.com thành tên miền bạn đang cấu hình.

![](<../.gitbook/assets/image (734).png>)

Sau khi tạo xong, phần danh sách bản ghi hiển thị đủ 2 bản ghi trên là bạn đã tạo đúng.

**2. Trỏ tên miền phụ:**&#x20;

Giả sử tên miền chính của bạn là tenmiencuaban.com, và bạn muốn tạo một tên miền phụ là [sanphama.tenmiencuaban.com.](http://sanphama.tenmiencuaban.com/)\
Chọn tên miền chính bạn muốn cài đặt, sau đó tạo một bản ghi mới và điền các giá trị như sau:\
Host record: sanphama\
Type (Loại): CNAME\
Value (Giá trị): [dns.ladipage.com](http://dns.ladipage.com/)

![](<../.gitbook/assets/image (697).png>)

## Giao diện mới của Mắt bão

Bạn vào mục Tên miền --> Quản lý Tên miền --> Chọn cấu hình DNS nâng cao--> Chọn tab tạo bản ghi để tạo bản ghi.

<figure><img src="../.gitbook/assets/mắt bão 2.png" alt=""><figcaption></figcaption></figure>

1. **Trỏ tên miền chính:**

Bạn thêm mới 2 bản ghi sau:

Host record: www\
Type (Loại): CNAME\
Value (Giá trị): dns.ladipage.com

Host record: @\
Loại: URL Redirect\
Giá trị): http://www.tenmiencuaban.com\
Lưu ý: Thay tenmiencuaban.com thành tên miền bạn đang cấu hình.

![](<../.gitbook/assets/image (1059).png>)

<figure><img src="../.gitbook/assets/mắt bão.png" alt=""><figcaption></figcaption></figure>

Sau khi tạo xong, phần danh sách bản ghi hiển thị đủ 2 bản ghi trên là bạn đã tạo đúng.

**2. Trỏ tên miền phụ:**&#x20;

Giả sử tên miền chính của bạn là tenmiencuaban.com, và bạn muốn tạo một tên miền phụ là [sanphama.tenmiencuaban.com.](http://sanphama.tenmiencuaban.com/)\
Chọn tên miền chính bạn muốn cài đặt, sau đó tạo một bản ghi mới và điền các giá trị như sau:\
Host record: sanphama\
Type (Loại): CNAME\
Value (Giá trị): [dns.ladipage.com](http://dns.ladipage.com/)

![](<../.gitbook/assets/image (350).png>)

Sau khi đã tạo thành công bản ghi tên miền về hosting của LadiPage, bạn chờ bản ghi tên miền cập nhật thành công về LadiPage, sau đó bạn cần tiếp tục làm bước tiếp theo: [**tạo và xác thực tên miền trên tài khoản LadiPage**](https://help.ladipage.vn/ten-mien/xac-thuc-ten-mien-tai-ladipage)**.**

{% content-ref url="xac-thuc-ten-mien-tai-ladipage.md" %}
[xac-thuc-ten-mien-tai-ladipage.md](xac-thuc-ten-mien-tai-ladipage.md)
{% endcontent-ref %}



