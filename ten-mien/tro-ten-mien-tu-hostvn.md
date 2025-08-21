# Trỏ tên miền từ HOSTVN

Truy cập trang quản trị tên miền của HOSTVN tại [https://dns.hostvn.net/](https://dns.hostvn.net/).

**Bước 1:** Sử dụng tài khoản khách hàng của bạn tại HOSTVN để đăng nhập.

![](<../.gitbook/assets/image (719).png>)



**Bước 2:** Chọn **Quản lý DNS** tại tên miền cần trỏ về LadiPage.

![](<../.gitbook/assets/image (450).png>)

**Bước 3: Tạo bản ghi:**

### **A. Trỏ tên miền chính về hosting của LadiPage.**

**Bạn tạo 2 bản ghi sau để trỏ tên miền chính trong Quản lý DNS:**

Kiểu: CNAME\
Tên: www\
Nội dung: dns.ladipage.com

Kiểu: URL Redirect\
Tên: @\
Nội dung: http://www.tenmiencuaban.com\
Lưu ý: Thay tenmiencuaban.com thành tên miền bạn đang cấu hình.

### B. Trỏ tên miền phụ (Tên miền dạng: sanpham.tenmiencuaban.com).

Để trỏ tên miền phụ về LadiPage bạn thực hiện theo các bước sau:

**1:** Chọn **Tạo mới bản ghi** sau đó chọn **CNAME.**

**2:** Nhập thông tin vào các trường thông tin sau đó bấm nút **Thêm mới**.\
1\. **Host**: Nhập tiền tố của tên miền phụ. VD: sanpham.\
2\. **Host name:** dns.ladipage.com.

![](<../.gitbook/assets/image (1035).png>)

![](<../.gitbook/assets/image (497).png>)

Sau khi đã tạo thành công bản ghi tên miền về hosting của LadiPage, bạn chờ bản ghi tên miền cập nhật thành công về LadiPage, sau đó bạn cần tiếp tục làm bước tiếp theo: [**tạo và xác thực tên miền trên tài khoản LadiPage**](https://help.ladipage.vn/ten-mien/xac-thuc-ten-mien-tai-ladipage).
