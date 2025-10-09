# Xác suất chốt của Space bán hàng

**Lập trình xác suất cho từng giai đoạn trong space giúp bạn hiểu rõ hơn về doanh thu dự kiến của công ty, từ đó có thể lập ngân sách hiệu quả.**

Theo mặc định, xác suất ở mỗi giai đoạn được đặt là 100%, vì vậy bạn luôn có thể thấy giá trị chính xác được lập trình trong từng giao dịch. Điều này cũng cho phép phần tóm tắt  tổng giá trị giao dịch cho mỗi giai đoạn.

***

## Thiết lập xác suất giai đoạn

Truy cập ứng dụng **LadiWork** -> Chọn **Space** **bán hàng** muốn chỉnh sửa thông tin&#x20;

Sau đó click sang mục **Thiết lập Space** để điều chỉnh thông tin&#x20;

<figure><img src="../../.gitbook/assets/cập nhật space 11 (1).gif" alt=""><figcaption></figcaption></figure>

Trong phần xác suất chốt của giai đoạn, nhập một con số từ 0 đến 100, và bấm **“Cập nhật thay đổi.”**

<figure><img src="../../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
_Lưu ý: Khi một giao dịch tiến triển qua giai đoạn, khả năng nó được đánh dấu là THÀNH CÔNG sẽ tăng lên. Chúng tôi khuyên bạn nên tăng dần xác suất ở mỗi giai đoạn để phản ánh điều này._
{% endhint %}

Sau khi thiết lập xong, hãy bấm **Bật xác suất chốt theo giao dịch** để kích hoạt thống kê theo tỷ lệ đã định

<figure><img src="../../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

{% hint style="danger" %}
Lưu ý :&#x20;

* **Để thiết lập xác suất chốt cho từng giao dịch**, bạn cần **BẬT** tùy chọn _xác suất chốt theo giao dịch_ trong Space
* Trong trường hợp một giao dịch vừa có _xác suất chốt theo giao dịch_, vừa có _xác suất chốt theo giai đoạn_, hệ thống sẽ **ưu tiên tính Giá trị trọng số dựa trên xác suất của giao dịch**.
{% endhint %}

***

## Xác suất chốt hiển thị trong giai đoạn như thế nào?

**Khi xác suất được thiết lập**, phần tóm tắt giao dịch ở từng giai đoạn sẽ hiển thị dưới dạng tỷ lệ phần trăm so với tổng giá trị giao dịch của giai đoạn đó.

1. Trong **chế độ dạng bảng (kanban)**, khi bạn xem thống kê giá trị doanh số của một giai đoạn, hệ thống sẽ tính ra **Giá trị trọng số** theo công thức:\
   **Giá trị trọng số = Tổng (Giá trị từng giao dịch × Xác suất chốt của giao dịch đó).**

<figure><img src="../../.gitbook/assets/image (1462).png" alt=""><figcaption></figcaption></figure>

2. Trong chế độ **forecast** của giao dịch

<figure><img src="../../.gitbook/assets/image (1475).png" alt=""><figcaption></figcaption></figure>

