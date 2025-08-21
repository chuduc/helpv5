# Lưu data về API

\*LadiPage hiện tại chỉ gửi dữ liệu theo phương thức POST, bạn vui lòng cập nhật thiết lập API nhận data theo phương thức này\*

## **Bước 1: Tạo tài khoản liên kết.**

**Cách 1 : Tạo tài khoản liên kết từ mục Landing Pages -> Cấu hình form**

Truy cập trang [builder.ladipage.com](http://builder.ladipage.com/), chọn menu Landing Pages **-> Cấu hình form-> Tạo cấu hình form -> Form data -> Tạo tài khoản liên kết .**&#x53;au đó lựa chọn Loại tài khoản là **API**

<figure><img src="../../.gitbook/assets/image (1297).png" alt=""><figcaption><p>Chọn Tạo cấu hình form -> Form data </p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (1298).png" alt=""><figcaption><p>Chọn Tạo tài khoản liên kết</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (62).png" alt=""><figcaption></figcaption></figure>

**Cách 2 :** Bạn vào phần **Form đăng ký--> mục Lưu data--> bấm Thêm mới ,--> chọn Tạo liên kết -> Loại tài khoản là API.**

<figure><img src="../../.gitbook/assets/image (27).png" alt=""><figcaption></figcaption></figure>

### **Bước 2: Cấu hình tài khoản liên kết.**

![](<../../.gitbook/assets/image (253).png>)

* **Tên liên kết**: Là tên gợi nhắc cho cấu hình lưu trữ này.
* **API URL:** Là đường dẫn url api mà bạn sẽ ghi nhận dữ liệu từ LadiPage.
* **API content type:** Tương ứng với phương thức nhận dữ liệu của bên API cung cấp. Có 3 hình thức để lựa chọn, bạn chọn 1 phương thức tương ứng.&#x20;
* **Gửi API qua LadiPage**: Trong trường hợp bạn tích chọn sử dụng mục này, thì dữ liệu sẽ có thể kiểm tra ở mục [dữ liệu Backup](https://help.ladipage.vn/quan-ly-landingpage/du-lieu-backup-data-landing-page).
* **API Request Heade**r: Bạn có thể cấu hình Content Type trong trường hợp cần chỉ định rõ kiểu dữ liệu muốn gửi và Authorization (Token, Api Key) nếu như bạn cần xác thực dữ liệu gửi đến.
* **Đồng bộ các trường thông tin:**

Bên tay trái là các trường thông tin bạn đã tạo trên form ở landing page, bạn cần lấy Tên Lấy Dữ Liệu của các trường của form LadiPage như bên dưới:

<figure><img src="../../.gitbook/assets/tên lấy dữ liệu (1).png" alt=""><figcaption></figcaption></figure>

Bên phải là tên lấy dữ liệu của các trường thông tin tương ứng bạn tạo trên API.

{% hint style="warning" %}
**Lưu ý:**

**Bạn chỉ lấy thông tin Tên lấy dữ liệu form của LadiPage trên tài khoản LadiPage, còn các thông tin còn lại bạn lấy tại bên cung cấp API.**
{% endhint %}

Sau khi điền đầy đủ thông tin, bạn bấm lưu lại để lưu tài khoản liên kết API. Bạn có thể chọn **thêm tài khoản liên kết** khác cho Cấu hình này. Mỗi cấu hình được chứa tối đa 3 tài khoản liên kết, tương đương với 3 nguồn lưu trữ thông tin khách hàng đồng thời nhận được từ form đăng ký trên Landing Page.

{% embed url="https://prnt.sc/5YyZIpGyE0y6" %}

## **Bước 3:  Thiết lập Lưu data cho form**

Quay trở lại form trên trang Landing Page, chọn toàn form bạn đang muốn cài đặt và chọn **"Lưu data":**

![](<../../.gitbook/assets/image (696).png>)

## **Bước 4:  Sử dụng cấu hình form**

Chọn cấu hình phù hợp trong danh sách cấu hình form đã được cài đặt ở bước 3, sau đó bấm **Cập nhật** để hoàn thành.

{% hint style="info" %}
Trong trường hợp bạn thay đổi bất kỳ thông tin nào liên quan đến API trong cấu hình form, bạn cần truy cập builder chỉnh sửa, form đăng ký -> chọn làm mới lại danh sách -> chọn lại cấu hình form và xuất bản lại trang&#x20;
{% endhint %}

<figure><img src="../../.gitbook/assets/image (32).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
**Lưu ý:**&#x20;

Ngoài việc gửi các trường dữ liệu ở form đăng ký về API của khách hàng, thì dữ liệu gửi về kênh lưu trữ sẽ có thêm các thông tin sau:&#x20;

* Trường dữ liệu IP, tên gửi dữ liệu "IP". Nếu tích chọn form Gửi API qua LadiPage thì mặc định có trường dữ liệu này, còn gửi trực tiếp qua API thì dựa vào ngôn ngữ API của bạn đang sử dụng, bạn tìm kiếm với từ khóa: get ip address from body thì sẽ tìm được hướng dẫn phù hợp để có thể lấy được IP.
* Trường đường dẫn Landing Page, tên gửi dữ liệu "link".&#x20;
* Các trường thông tin UTM ở đường dẫn. Tên gửi dữ liệu của các trường đó là: utm\_source, utm\_medium, utm\_campaign, utm\_term, utm\_content, variant\_url. Chỉ khi nào có nội dung utm trên link landing page thì dữ liệu này mới có thể được ghi nhận về API Tất cả các trường thông tin được gửi là cùng 1 cấp.
* Trong trường hợp bạn sử dụng OTP trên form, bạn muốn ghi nhận trạng thái xác thực hay chưa xác thực của dữ liệu,  thì tên gửi dữ liệu : " is\_verified " . Còn trong trường hợp muốn ghi nhận mã OTP đã gửi cho khách hàng , thì tên gửi dữ liệu : " otp\_code"&#x20;
* Trong trường hợp bạn muốn lấy ID form mà khách hàng submit dữ liệu, thì tên gửi dữ liệu là : " ladi\_form\_id"&#x20;
* Thời gian hệ thống nhận dữ liệu của khách hàng , thì tên gửi dữ liệu : " message\_time"&#x20;
* Trường hợp bạn muốn lấy các dữ liệu liên quan đến tracking như fbc, fbq, user-agent, event\_id , thì tên gửi dữ liệu lần lượt sẽ là "fbc", "fbq", "user-agent", "event\_id"
* Trong trường hợp bạn sử dụng tài khoản phân quyền có tính năng capture form, bạn có thể thêm ghi chú dữ liệu là capture form. Tên gửi dữ liệu: status\_send, giá trị gửi về: nếu dữ liệu là capture form thì sẽ ghi chú thêm chữ: capture.
{% endhint %}
