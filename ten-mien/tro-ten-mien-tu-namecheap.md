# Trỏ tên miền từ Namecheap

Truy cập tài khoản của bạn ở [https://ap.www.namecheap.com/](https://ap.www.namecheap.com/), mục **Account --> Domain List.**

Bạn chọn tên miền muốn cập nhật bản ghi, bấm chọn nút ![](<../.gitbook/assets/image (1043).png>)  để truy cập phần quản lý tên miền đó.

![](<../.gitbook/assets/image (1032).png>)

Chọn mục **Advanced DNS**  --> **Add New Record**  ![](<../.gitbook/assets/image (269).png>) để thao tác tạo bản ghi tên miền.

![](<../.gitbook/assets/image (330).png>)

## Trỏ tên miền chính

Tạo 2 bản ghi trỏ tên miền chính về hosting  LadiPag&#x65;**.** Bấm vào mục **Add new record** để thêm bản ghi

![](<../.gitbook/assets/image (829).png>)

Record: Cname\
Host: www\
Target: dns.ladipage.com

Record: A\
Host: @\
Target: 13.229.38.226\


## Trỏ tên miền phụ&#x20;

Giả sử tên miền chính của bạn là tenmiencuaban.com, và bạn muốn tạo một tên miền phụ là [sanphama.tenmiencuaban.com.](http://sanphama.tenmiencuaban.com/)\
Chọn tên miền chính bạn muốn cài đặt, sau đó tạo một bản ghi mới và điền các giá trị như sau:

Record :Cname\
Host : sanphama\
Target: [dns.ladipage.com](http://dns.ladipage.com/)

Bấm vào mục **Add new record** để thêm bản ghi.

![](<../.gitbook/assets/image (1042).png>)

Sau khi đã trỏ thành công tên miền về hosting của LadiPage, bạn cần tiếp tục làm bước tiếp theo, [**tạo và xác thực tên miền trên tài khoản LadiPage**](https://help.ladipage.vn/ten-mien/xac-thuc-ten-mien-tai-ladipage)**:**

{% content-ref url="xac-thuc-ten-mien-tai-ladipage.md" %}
[xac-thuc-ten-mien-tai-ladipage.md](xac-thuc-ten-mien-tai-ladipage.md)
{% endcontent-ref %}
