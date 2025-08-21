# Trỏ tên miền từ AZDIGI

Để thực hiện trỏ DNS bạn cần đăng nhập vào quản trị dịch vụ tại [my.azdigi.com](https://my.azdigi.com/clientarea.php) và đăng nhập bằng thông tin của mình đã tạo trước đó.

{% embed url="https://prnt.sc/Vvmf2AYhWipS" %}

**Bước 1: Đăng nhập vào quản trị tên miền**

Trên thanh Menu bạn chọn **Domain** => **DNS Manager**

{% embed url="https://prnt.sc/pfcR0y_7OUcP" %}

**Bước 2: Truy cập vào quản trị DNS**

Tại đây bạn chọn domain cần chỉnh sửa DNS. Bạn lưu ý giúp mình như sau. Nếu ở mục **Zones:1/50** thì có nghĩa domain bạn đã có Zone rồi và bạn chỉ việc thêm bản ghi DNS thôi.

Nếu chổ **Zone: 0/50** thì domain bạn chưa có Zone và bắt buộc bạn phải tạo 1 Zone mới. Hãy tạo theo [hướng dẫn sau nhé.](https://dotrungquan.info/huong-dan-cau-hinh-dns-domain-va-tao-record-domain-tai-azdigi/)

{% embed url="https://prnt.sc/rrY2gQ94nRrU" %}

**Bước 3: Tạo Record trỏ về LadiPage**

Ở đây mình sẽ bắt đầu tạo record trỏ về LadiPage, nhưng sẽ thực hiện trong 2 trường hợp đó là domain chính và subdomain.

**1. Trỏ tên miền chính.**

Bạn click chọn Add Record để tạo record (bản ghi mới.) Và bạn thực hiện tạo 2 record như sau.

**Thứ nhất: Record A**

* Name: Nhập vào tên miền của bạn
* Type: A
* TTL (Time to live): Bạn để mặc định
* RDATA: Nhập vào IP là 13.229.38.226

Giống như ảnh bên dưới.

{% embed url="https://prnt.sc/w5WL1PTVKZE3" %}

**Thứ 2: Record CNAME**

* Name: www
* Type: CNAME
* TTL (Time to live): Bạn để mặc định
* RDATA: dns.ladipage.com

{% embed url="https://prnt.sc/697yV6QnVc_Y" %}

Và bên dưới là 2 bản record trỏ về ladipage hoàn tất.

{% embed url="https://prnt.sc/TzXkV1GtMOBe" %}

**2. Trỏ tên miền phụ (Subdomain)**

Giả sử tên miền chính của bạn là tenmiencuaban.com, và bạn muốn tạo một tên miền phụ là sanpham.tenmiencuaban.com thì:

Chọn tên miền chính bạn muốn cài đặt, sau đó tạo một bản ghi mới và điền các giá trị như sau: Host record: sanpham Type (Loại): CNAME Value (Giá trị): dns.ladipage.com

Sau đây là ảnh minh họa, trong đó:

* Name: Tên miền phụ (Subdomain)
* Type: CNAME
* TTL (Time to live): Bạn để mặc định
* RDATA: dns.ladipage.com

{% embed url="https://prnt.sc/tiPPOd6OjxY7" %}

Sau khi đã tạo thành công bản ghi tên miền về hosting của LadiPage, bạn chờ bản ghi tên miền cập nhật thành công về LadiPage, sau đó bạn cần tiếp tục làm bước tiếp theo: [**tạo và xác thực tên miền trên tài khoản LadiPage**](https://help.ladipage.vn/ten-mien/xac-thuc-ten-mien-tai-ladipage)**.**

{% content-ref url="xac-thuc-ten-mien-tai-ladipage.md" %}
[xac-thuc-ten-mien-tai-ladipage.md](xac-thuc-ten-mien-tai-ladipage.md)
{% endcontent-ref %}
