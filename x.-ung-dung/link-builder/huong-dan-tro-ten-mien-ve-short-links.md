# Hướng dẫn trỏ tên miền về Short Links

Thông số trỏ tên miền riêng về Hosting Short Links để sử dụng tên miền riêng cho link rút gọn

Trong trường hợp bạn sử dung gói trả phí của Short Links  , bạn có thể thêm 1 tên miền riêng để khách hàng truy cập link trang rút gọn

### **Bước 1: Trỏ tên miền về hosting của** Short Links&#x20;

_**Trỏ tên miền chính:**_

Vào phần quản trị tên miền ở nơi bạn mua tên miền và cấu hình **2** bản ghi sau để điều hướng tên miền đó về địa chỉ của Short Links :

Host record: **www**\
Type (Loại): **CNAME**\
Value (Giá trị): **dns.ladilink.com**

Host record: @\
Type (Loại): URL Redirect\
Value (Giá trị):   http://www.tenmiencuaban.com\
Lưu ý: Thay tenmiencuaban.com thành tên miền bạn đang cấu hình.

_**Trỏ tên miền phụ:**_

Giả sử tên miền chính của bạn là tenmiencuaban.com, và bạn muốn tạo một tên miền phụ là link.tenmiencuaban.com thì:\
Chọn tên miền chính bạn muốn cài đặt, sau đó tạo một bản ghi mới và điền các giá trị như sau:\
Host record: **link**\
Type (Loại): **CNAME**\
Value (Giá trị): **dns.ladilink.com**
