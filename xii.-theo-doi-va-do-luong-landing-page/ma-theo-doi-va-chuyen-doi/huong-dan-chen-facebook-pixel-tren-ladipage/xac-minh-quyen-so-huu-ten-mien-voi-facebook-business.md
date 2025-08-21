# Xác minh quyền sở hữu tên miền với Facebook Business

## Xác minh miền là gì?

&#x20;Xác minh tên miền là cách để bạn xác nhận quyền sở hữu tên miền của mình trong [Trình quản lý doanh nghiệp](https://business.facebook.com/). Quyền sở hữu này cho phép bạn kiểm soát các đặc quyền chỉnh sửa liên kết và nội dung khác để ngăn chặn việc lạm dụng tên miền, đồng thời ngăn các phần tử xấu truyền bá thông tin sai lệch.

## Khi nào nên xác minh tên miền?

Xác minh tên miền là cách tốt nhất để xử lý quyền sở hữu nếu:

* Bạn có nhiều Trang khó duy trì thủ công qua thẻ Open Graph.
* Bạn có kinh nghiệm sử dụng Trình quản lý doanh nghiệp để quản lý tài sản của mình.
* Bạn có khả năng tải tệp HTML lên thư mục gốc website hoặc khả năng chỉnh sửa bản ghi DNS TXT.
* Bạn có thể chỉnh sửa Bài viết có liên kết trên Trang đến nội dung mình sở hữu – cuối cùng, quyền sở hữu sẽ trở thành biện pháp xác định ai có quyền chỉnh sửa liên kết.
* Bạn muốn kiểm soát những người có thể chỉnh sửa nội dung mô tả liên kết trên các quảng cáo hướng đến miền của mình.

{% hint style="danger" %}
**Lưu ý:**&#x20;

Bạn chỉ cần xác thực với tên miền chính (không www) thì tên miền phụ và subfolder cũng sẽ tự động được xác thực.
{% endhint %}

## **Hướng dẫn xác minh tên miền**

&#x20;Tại [**Trình quản lý doanh nghiệp**](http://business.facebook.com/) **→** **More Tools** (**Công cụ khác)** **→Business settings (Cài đặt cho doanh nghiệp).**

![](<../../../.gitbook/assets/image (1176).png>)

&#x20;**Cài đặt cho doanh nghiệp → Brand Safety(Sự an toàn của thương hiệu) → Domain(Miền).**

![](<../../../.gitbook/assets/image (640).png>)

&#x20;Nhấp vào nút **Add(Thêm)**, sau đó hãy nhập tên miền của bạn vào và nhấn **Add domain**( **Thêm miền)** như ảnh bên dưới.

![](<../../../.gitbook/assets/image (194).png>)

Như vậy là bạn đã hoàn tất quá trình thêm tên miền vào trình quản lý doanh nghiệp tại facebook, cuối cùng bạn cần xác nhận quyền sở hưu tên miền nữa hoàn tất 100%.

## Xác nhận quyền sở hữu tên miền

* Sau khi thêm tên miền thành công, bạn cần bấm phím F5 để tải lại trang để thấy giao diện xác minh tên miền (nếu tên miền đã xác minh thì sẽ không xuất hiện giao diện này).
* Nếu bạn có nhiều hơn một tên miền được thêm vào, hãy chọn tên miền mà bạn muốn xác nhận quyền sở hữu.
*   Chọn 1 trong 2 phương pháp sau để xác minh tên miền:

    * Thêm thẻ meta \<head> vào phần website của bạn.
    * Thêm giá trị TXT vào bản ghi DNS tên miền của bạn.

    ### **Phương pháp 1: Thêm thẻ meta vào phần \<head> landing page của bạn.**

![](<../../../.gitbook/assets/image (630).png>)



**Xác minh thẻ meta** tên miền vào trang chủ tên miền của bạn theo các bước sau:

* **Bước 1:** Thêm thẻ meta vào phần `<head> landing page` của bạn: Bạn vào trang chỉnh sửa landing page-->**Thiết lập- Mã Javascript/Css)**
* **Bước 2:** Nhấp vào nút **Xác minh** để tiến hành xác minh quyền sở hữu tên miền.

<figure><img src="../../../.gitbook/assets/thẻ head (1).png" alt=""><figcaption></figcaption></figure>

### **Phương pháp 2: Thêm giá trị TXT vào bản ghi DNS tên miền của bạn**

![](<../../../.gitbook/assets/image (1138).png>)

Bạn cần cấu hình thêm vào bản ghi TXT vào tên miền của bạn như sau:

* **Bước 1:** Truy cập **vào trang quản lý tên miền của bạn→** **Tên miền** **→ Chọn tên miền →** **Quản lý DNS**
* **Bước 2:** **Thêm bản ghi** tên miền như sau:

**Host** : **@**

**Loại** : **TXT**

**Giá trị** : facebook-domain-verification=0gcnmflzona4gulerep3sdr5b1s5l8 ( giá trị demo )

Giá trị bảng ghi TXT là riêng biệt, do đó bạn cần sao chép giá trị từ facebook cung cấp. Nếu bạn không biết thao tác tạo bản ghi này, vui lòng liên hệ với bên cung cấp tên miền để được hỗ trợ.

## Hướng dẫn liên kết tên miền với Fanpage (Trang)

Việc thêm tên miền vào Trình quản lý doanh nghiệp cho phép bạn dễ dàng quản lý nội dung trong danh sách Fanpage (Trang), bạn thực hiện theo hướng dẫn sau:

* **Bước 1:** Truy cập **Cài đặt cho doanh nghiệp** **→** Brand Safety(**Sự an toàn của thương hiệu)** **→** Domains (**Miền)** **→Domain(** **tên miền)** **→** Add Assets(**Thêm** **tài sản)** như ảnh bên dưới.

![](<../../../.gitbook/assets/image (619).png>)



* **Bước 2:** Chọn bất kỳ Trang nào của bạn cần muốn thêm vào tên miền và nhấp vào **Add( Thêm).**
* **Bước 3:** Bây giờ bạn sẽ thấy danh sách Trang đã được thêm vào tab **Add Assets( Tài sản đã kết nối)** của tên miền.

Như vậy, chúng ta đã hoàn thành xác minh tên miền với Trình quản lý doanh nghiệp và liên kết với các Fanpage (Trang) thành công.

