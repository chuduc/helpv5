# Trường chọn file

Trường dữ liệu này cho phép người sử dụng tải file dữ liệu lên form của bạn và gửi về kênh lưu trữ đã được thiết lập của form đó.

<figure><img src="../../.gitbook/assets/tải file.png" alt=""><figcaption></figcaption></figure>

Khi xuất bản sẽ có định dạng như sau:

![](<../../.gitbook/assets/image (317).png>)



### **Các lưu ý về trường chọn file**

* Các định dạng file cho phép được tải lên: 'jpg', 'jpeg', 'png', 'gif', 'svg', 'ico', 'mp3', 'mp4', 'ttf', 'otf', 'woff2', 'txt', 'doc', 'docx', 'xls', 'xlsx', 'pdf' , ' avif ' , 'webp'
* Ở 1 trường chọn file, bạn được phép tải lên **tối đa 5 file cùng 1 lúc**, với tổng dung lượng tối đa cho 1 lần tải là **25 Mb**, nếu tải lần lượt từng file lên thì chỉ lưu lại file ở thao tác tải lên cuối cùng.
* Bạn được tạo tối đa 5 trường chọn file cho 1 form điền thông tin.
* Dữ liệu của trường chọn file, chỉ gửi về các kênh lưu trữ: **Email, Google Sheet, SMTP, Slack, Telegram, Custome API (tích chọn gửi qua LadiPage).** Trong mục **Backup dữ liệu-** trường file ghi nhận như dạng text nên sẽ không tải được file từ mục backup.

{% hint style="warning" %}
**Lưu ý:**&#x20;

Các Link File chỉ truy cập được <mark style="color:red;">**trong vòng 30 ngày và tối đa 1000 lượt truy cập**</mark> từ thời điểm ghi nhận thông tin về kênh lưu trữ.
{% endhint %}
