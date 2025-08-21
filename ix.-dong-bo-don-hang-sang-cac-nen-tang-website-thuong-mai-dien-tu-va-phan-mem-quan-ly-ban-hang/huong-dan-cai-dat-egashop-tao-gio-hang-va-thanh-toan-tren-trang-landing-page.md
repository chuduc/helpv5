# 5. Hướng dẫn cài đặt EgaShop- Tạo Giỏ hàng và Thanh toán trên trang Landing Page

Ở bài viết này, LadiPage giới thiệu tới người dùng ứng dụng Egashop - một ứng dụng độc lập từ bên thứ ba giúp bạn tạo trải nghiệm giỏ hàng và thanh toán ngay trên trang Landing Page.\
Egashop cung cấp 2 hình thức:

* Nhúng danh sách sản phẩm từ website Sapo/Haravan lên Landing Page của LadiPage và chuyển tiếp về trang thanh toán của Sapo/Haravan.
* Tự động tạo giao diện danh sách sản phẩm trên Landing Page từ file excel có sẵn và tạo trải nghiệm giỏ hàng trong khi đơn hàng vẫn đẩy về Google Sheet.

## Hình thức 1 : Để nhúng sản phẩm/nhóm sản phẩm từ Haravan/Sapo vào trang Landing Page, anh/chị thực hiện theo các bước sau:

{% hint style="info" %}
Lưu ý: Anh/chị đăng ký tạo tài khoản tại Egashop để thực hiện được việc cài đặt ứng dụng. thông tin chi tiết [tại đây](https://egany.com/blogs/ega-cross-platform/huong-dan-cai-dat-egashop?fbclid=IwAR1SOO_a2-HVbBz5vQnhHYyLxRoWB5WJ9LZUgdDYMi5bOHyws3PTM_h6edU)
{% endhint %}

1. Truy cập egaShop --> vào "Thiết lập ứng dụng"

![](<../.gitbook/assets/image (834).png>)

2\. Chọn Nền tảng --> Nhập domain (hoặc file excel) --> Thêm nhóm sản phẩm (Nếu sử dụng bản trademark thì mặc định sẽ chọn collection all)

![](<../.gitbook/assets/image (435).png>)

3\. Ấn Lưu thay đổi

![](<../.gitbook/assets/image (416).png>)

4\. Chọn "Lấy mã thực thi" và copy đoạn mã

![](<../.gitbook/assets/image (999).png>)

\
5\. Vào thiết lập của Ladipage đã khai báo, chọn Thiết lập --> Mã Javascript/CSS --> Dán đoạn mã thực thi vừa copy vào "Trước thẻ \</body>"

![](<../.gitbook/assets/image (531).png>)

![](<../.gitbook/assets/image (1080).png>)

6\. Quay lại dashboard egaShop, chọn "Lấy mã nhúng" của nhóm sản phẩm và copy đoạn mã

\


![](<../.gitbook/assets/image (1150).png>)

7\. Vào lại Ladipage, chọn thêm mới "Mã HTML" (chọn vị trí muốn trình bày sản phẩm) --> Dán mã nhúng vừa lấy được vào và Cập nhật

![](<../.gitbook/assets/image (174).png>)



Sau khi hoàn thành các bước trên, ấn xuất bản Ladipage. Và như vậy anh/chị đã có cho mình giỏ hàng cùng sản phẩm hiển thị trên Ladipage.

![](https://file.hstatic.net/1000181505/file/step-13_1c3b1709c4c84be9ba75173a0191162f.png)

_Sản phẩm và giỏ hàng được thêm vào Ladipage_

{% hint style="info" %}
Nếu còn thắc mắc, anh/chị vui lòng liên hệ support@egany.com hoặc fanpage EGANY.\
Truy cập group [EGANY - Tối ưu chuyển đổi & trải nghiệm người dùng chuyên sâu](https://www.facebook.com/groups/egany/) để cập nhật được nhiều thông tin hữu ích hơn.
{% endhint %}

