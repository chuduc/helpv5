# 1. Tạo Form đăng ký liên kết với các website thương mại điện tử, phần mềm quản lý bán hàng

_**Lưu ý**_: **Phần Form tại Landing Page chứa rất nhiều trường thông tin, nhưng tại 4 website thương mại điện tử (Haravan, Sapo, Shopify và Wordpress) và 3 nền tảng quản lý bán hàng (LadiSales, Nhanh.vn, KiotViet), gọi tắt 7 nền tảng - chỉ nhận một số trường thông tin gửi sang từ Landing Page.**&#x20;

Để tạo form, bạn vào phần **Thêm mới- Phần tử** ở thanh công cụ - và chọn Form:

![](<../.gitbook/assets/image (692).png>)

## Thêm trường dữ liệu cho form&#x20;

Một form đăng ký gồm nhiều trường thông tin và bạn có thể thêm bớt các trường thông tin này trong thiết lập của form. Khi bắt đầu thêm, form đăng ký mẫu hiện ra những trường cơ bản hay được sử dụng. Bạn có thể chọn **Thêm Trường** để chọn các trường khác mà phía 7 nền tảng nhận dữ liệu.

![](<../.gitbook/assets/image (452).png>)

**Số lượng trường dữ liệu tối đa có thể gửi về các nền tảng là 8 trường**, nhưng không phải lúc nào form đăng ký của bạn cũng đủ 8 trường thông tin đó. Mỗi nền tảng sẽ quy định những trường dữ liệu bắt buộc phải có thông tin thì đơn hàng mới về kênh lưu trữ. Thông tin chi tiết liệt kê ở bảng dưới đây.

![](<../.gitbook/assets/image (429).png>)

**LadiSales**: chỉ yêu cầu có trường **EMAIL** hoặc **SỐ ĐIỆN THOẠI** là dữ liệu sẽ gửi về được LadiSales.

**Các nền tảng khác yêu cầu form có trường Sản phẩm.**

<figure><img src="../.gitbook/assets/sán phẩm.png" alt=""><figcaption></figcaption></figure>

Sau khi chọn Thêm trường Sản phẩm, bạn cần vào trường đó để cài đặt sao cho cấu hình phần sản phẩm đồng bộ giữa các nền tảng và form của LadiPage.&#x20;

<figure><img src="../.gitbook/assets/image (1291).png" alt=""><figcaption></figcaption></figure>

Bạn chọn lần lượt các thông số liên quan đến mục sản phẩm như sau: &#x20;

1. _**Tài khoản liên kết**_**:** Bạn vào mục Cài đặt của form -> Thiết kế -> Chọn cấu hình tài khoản liên kết bạn muốn đồng bộ sản phẩm lên form

<figure><img src="../.gitbook/assets/image (1293).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (122).png" alt=""><figcaption></figcaption></figure>

2. _**Sản phẩm**_**:** Sản phẩm bạn muốn hiển thị trên form đăng ký của khách hàng. Phần danh sách sản phẩm hiển thị toàn bộ biến thể của sản phẩm trên website của bạn. Để lựa chọn biến thể muốn hiển thị, bạn gõ tìm kiếm theo tên sản phẩm.&#x20;

<figure><img src="../.gitbook/assets/image (119).png" alt=""><figcaption></figcaption></figure>

Bấm chọn vào mục **Danh sách sản phẩm và bấm nút** ![](<../.gitbook/assets/image (121).png>)

<figure><img src="../.gitbook/assets/image (120).png" alt=""><figcaption></figcaption></figure>

Bạn tìm kiếm sản phẩm từ mục Sản phẩm và chọn danh sách các sản phẩm muốn hiển thị trên form

{% embed url="https://prnt.sc/SlCjYKHVFnqS" %}

**Tiêu đề và giá trị:** Phần định dạng sản phẩm  ở mục giá trị có 2 phần: kí tự dãy số | tên biến thể. Phần tiêu đề là phần hiển thị trên form của bạn, bạn có thể đặt tên theo nhu cầu hiển thị của mình

<figure><img src="../.gitbook/assets/image (123).png" alt=""><figcaption></figcaption></figure>

&#x20;

<figure><img src="../.gitbook/assets/image (124).png" alt=""><figcaption></figcaption></figure>

Ví dụ trong danh sách giá trị trên: 150360:1:100:0:g|sản phẩm 1- l là giá trị gửi về kênh lưu trữ, còn tên hiển thị trên form là Sản phẩm ưu đãi

Sau khi hoàn thiện các trường trên form, bạn bấm **Lưu** và thiết lập phần **Lưu data** cho form đăng ký (xem hướng dẫn [tại đây](https://help.ladipage.vn/form-data/cac-buoc-cai-dat-luu-data)).

{% hint style="danger" %}
Trong trường hợp bạn sử dụng các trường dữ liệu khác ngoài danh sách liệt kê phía trên, trường thông tin đó không lưu về đơn hàng của các website nhưng vẫn về các kênh lưu trữ khác (Email, Google Sheet...) như bình thường.
{% endhint %}

