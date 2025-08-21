# Trỏ tên miền từ Vietnix

Truy cập trang chủ Vietnix tại [https://vietnix.vn/](https://vietnix.vn/)

**Bước 1:** Sử dụng tài khoản khách hàng của bạn tại Vietnix để đăng nhập.

<figure><img src="https://lh7-us.googleusercontent.com/2OlDUIBas1BBrKYfr1q6EFvqYJFpgvZEao07m5YIZxlnAwyKkUcnU1Hq2AS0tnNvMCwx8Ewl-dmL16-9KX-MSXz9TB7TqxrdlAxfThxWvCVxdcJXk8fYG_tacuFQW96ivbfdZoNQNDKSMxPsUuO4FbI" alt=""><figcaption></figcaption></figure>

**Bước 2:** Tại trang quản trị dịch vụ bạn chọn mục **Quản lý tên miền** sau đó chọn tên miền cần trỏ và chọn **Quản lý.**

<figure><img src="https://lh7-us.googleusercontent.com/W1crEEu-INioY6DDrdwLGRzuUXmQ9VO-VvS0NU6uE6bkmo6VqtOEeiezzzrbRdUS4vZmbU9f0bZ2IXFOeDjCXrLzfApLn3dpa-ploRJXNfMIsXiyWKe1JoCaZlHijCSJkFFkKP_B_JXugo9qG0x4Pz0" alt=""><figcaption></figcaption></figure>

Sau đó chọn **Quản lý DNS** để cập nhật hoặc thêm bản ghi

<figure><img src="https://lh7-us.googleusercontent.com/d95sK5bhFu9VeSjWEKVU2nwbkmDw4_PYu8nzRl2qPHTVxsmIaLRqRJ0kgMC3b4xQYFYOHDZ-act6fiktGTOmy6zD0rQ0Az1vIe3Q7zpntgmjktzbS2RkMjfCK8hYTDmza9tsCVWZlmVVhbFK1Vn4dBA" alt=""><figcaption></figcaption></figure>

**Bước 3: Tạo bản ghi:**

### **A. Trỏ tên miền chính về hosting của LadiPage.**

**Bạn tạo 2 bản ghi sau để trỏ tên miền chính trong Quản lý DNS:**

Type: CNAME\
Name: www\
Content: dns.ladipage.com

Type: URL Redirect\
Name: @\
Content: http://www.tenmiencuaban.com\
Lưu ý: Thay tenmiencuaban.com thành tên miền bạn đang cấu hình.

### B. Trỏ tên miền phụ (Tên miền dạng: sanphama.tenmiencuaban.com).

Để trỏ tên miền phụ về LadiPage bạn thực hiện theo các bước sau:

**1:** Chọn **Tạo mới bản ghi** sau đó chọn **CNAME.**

**2:** Nhập thông tin vào các trường thông tin sau đó bấm nút **Add**.\
1\. **Name:** Nhập tiền tố của tên miền phụ. VD: sanphama.\
2\. **Content:** dns.ladipage.com.

<figure><img src="https://lh7-us.googleusercontent.com/H_fhUJeOqzrh7DKXe6LezGAbv4dolmBCMccCmRgsdfUAR09647TwFVcAKqL6LJ0lZidtI-LdYSbhqUSUyhmL6Vo46MNcbY_p4zZH_pDZy2j96p0fvgKkf7VDK4pwL6rePOBPkKjdDU_lOK_pEHqp7rw" alt=""><figcaption></figcaption></figure>

Sau khi đã tạo thành công bản ghi tên miền về hosting của LadiPage, bạn chờ bản ghi tên miền cập nhật thành công về LadiPage, sau đó bạn cần tiếp tục làm bước tiếp theo: [**tạo và xác thực tên miền trên tài khoản LadiPage**](https://help.ladipage.vn/ten-mien/xac-thuc-ten-mien-tai-ladipage).
