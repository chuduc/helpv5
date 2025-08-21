# 9. Place Autocomplete

Tính năng này cho phép bạn tìm kiếm phần địa chỉ thực tế và tự động điền vào trường địa chỉ trên form đăng ký của bạn&#x20;

<figure><img src="../.gitbook/assets/map.gif" alt=""><figcaption></figcaption></figure>

**Bước 1 :   Tích hợp Google Place Autocomplete**&#x20;

**Cách 1**   Truy cập trang [builder.ladipage.com](http://builder.ladipage.com/), chọn menu **Tích hợp -> Tài khoản liên kết -> Tạo tài khoản liên kết.** Sau đó lựa chọn Loại tài khoản là  **Place Autocomplete**

<figure><img src="../.gitbook/assets/image (939).png" alt=""><figcaption></figcaption></figure>



**Cách 2  : Bạn vào phần Thêm mới -> Ứng dụng --> Place Autocomplete**

<figure><img src="../.gitbook/assets/image (931).png" alt=""><figcaption></figcaption></figure>

## Bước 2: Tạo cấu hình Place Autocomplete

Bấm tạo cấu hình Place Autocomplete bằng cách nhập các thông tin&#x20;

‌**Tên liên kết:** là tên để phân biệt với các liên kết khác.

‌ **API KEY :** bạn tạo trên tài khoản google&#x20;

<figure><img src="../.gitbook/assets/image (922).png" alt=""><figcaption></figcaption></figure>

\***Cách tạo API KEY của Place Autocomplete**

* Truy cập vào link đăng ký [API Key Google Map](https://console.cloud.google.com/project/_/apiui/credential)
* Nhấn tạo 1 Project mới, sau đó điền đầy đủ các thông tin theo các bước mà popup hiện lên

<figure><img src="../.gitbook/assets/image (1014).png" alt=""><figcaption></figcaption></figure>

* Nhấn tạo 1 API Key: Sau khi tạo xong 1 project mới bạn hãy chọn dự án mới tạo. vd: mình đã tạo dự án **“My Project”**

<figure><img src="../.gitbook/assets/image (1017).png" alt=""><figcaption></figcaption></figure>

**Bước 3: Hiển thị Google Place  trên các form đăng ký của bạn**

Tại mục Ứng dụng --> Place Autocomplete, bạn bật sử dụng ứng dụng và chọn cấu hình Place autocomplete mới tạo

&#x20;

<figure><img src="../.gitbook/assets/image (1016).png" alt=""><figcaption></figcaption></figure>

Sau khi tích hợp thành công , trên trường địa chỉ của form sẽ hiển thị như ảnh&#x20;

<figure><img src="../.gitbook/assets/image (1024).png" alt=""><figcaption></figcaption></figure>

{% hint style="danger" %}
1. Phần địa chỉ gợi ý sẽ chỉ được điền vào trường Địa chỉ của form, không tự động điền vào  trường dữ liệu tỉnh/thành, quận/huyện,phường/xã của form&#x20;
2. &#x20;Số lượt sử dụng của  key google place autocomplete bị giới hạn, nên bạn phải request với google để tăng số lượt sử dụng theo hướng dẫn [http://ldp.to/1mQIB](http://ldp.to/1mQIB)


{% endhint %}
