# 2.Các thiết lập của Smart Form

Các thiết lập của Smart Form cũng tương tự như các form thông thường trên trang, nhưng sẽ có thêm phần thiết lập **ĐIỀU KIỆN FORM**

Truy cập vào mục **Lưu data**, để thực hiện các cấu hình form, điều kiện hiển thị và thiết lập tracking&#x20;

{% embed url="https://prnt.sc/eyGvMrTkkx6a" %}

## 1.Cấu hình form :&#x20;

Thiết lập tương tự như các form thông thường, bạn sẽ thiết lập thông tin về các kênh lưu trữ mình mong muốn&#x20;

{% embed url="https://prnt.sc/_u_I_aG2FISu" %}

Tham khảo hướng dẫn thiết lập Lưu data:

{% content-ref url="../../xvii.-form-data/cac-buoc-cai-dat-luu-data/" %}
[cac-buoc-cai-dat-luu-data](../../xvii.-form-data/cac-buoc-cai-dat-luu-data/)
{% endcontent-ref %}

## 2.Điều kiện form&#x20;

Cho phép bạn thiết lập khi khách hàng submit form ( nhập thông tin vào form và gửi ) và thỏa mãn các điều kiện,nhóm điều kiện ,đã cài đặt thì thực hiện các hành động tương ứng ( hiển thị popup, trang cảm ơn, thiết lập cookie...)

{% embed url="https://prnt.sc/x0HKH-CzLHGx" %}

<mark style="color:red;">**Chi tiết về phần mô tả các loại điều kiện và hành động**</mark>&#x20;

{% content-ref url="dieu-kien-form.md" %}
[dieu-kien-form.md](dieu-kien-form.md)
{% endcontent-ref %}

## 3. Mã sự kiện chuyển đổi&#x20;

Cho phép bạn cài đặt các tracking cho form của mình&#x20;

{% embed url="https://prnt.sc/xElsrFIjJao9" %}

{% hint style="danger" %}
Lưu ý : Trong trường hợp bạn thiết lập nhiều hành động khác nhau trên form, ví dụ như  điều kiện 1 đáp ứng là mở popup hoặc điều kiện 2 đáp ứng mở sang 1 trang cảm ơn khác, để việc tracking được chính xác, bạn  nên :&#x20;

* Cài đặt ID tracking ( facebook, google analytics, tiktok, google ads ,GTM..) ở trang landingpage gốc tại mục **Thiết lập -> Mã chuyển đổi**&#x20;
* Thiết lập các mã sự kiện ở trên popup/ trang thực hiện hành động
{% endhint %}
