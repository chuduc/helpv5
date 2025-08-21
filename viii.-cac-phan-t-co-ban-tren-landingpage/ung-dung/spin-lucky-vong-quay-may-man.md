# Spin Lucky ( Vòng quay may mắn)

Để thiết lập Vòng quay may mắn, bạn vào phần **Thêm mới->** **Ứng dụng** -> **Spin Lucky** và vào phần **Thuộc Tính** để  chỉnh sửa các nội dung trên vòng quay&#x20;

![](<../../.gitbook/assets/image (604).png>)

{% hint style="info" %}
Sau 24h từ khi bạn hết lượt quay, thì bạn có thể thực hiện thao tác quay tiếp&#x20;
{% endhint %}

## 1. Danh sách kết quả/Kiểu dữ liệu&#x20;

\
\- Mã coupon: mã giảm giá khách hàng nhận được sau khi quay vòng quay\
\- Tên coupon: nội dung sẽ hiển thị ở vòng quay may mắn\
\- %: tỉ lệ quay vào các ô trên vòng quay

Có 2 cách thiết lập Danh sách kết quả : Tự nhập hoặc Dataset

1.1 Tạo nội dung tự nhập : tạo lần lượt thông tin theo mẫu có sẵn với định dạng  Couponcode, CoupontextI,% ( ví dụ COUPON50,Coupon 50k,90%)

![](<../../.gitbook/assets/image (219).png>)

1.2 Tạo nội dung từ Collection&#x20;

Theo dõi chi tiết thao tác hướng dẫn  ở video dưới đây&#x20;

![](<../../.gitbook/assets/vòng quay .gif>)

![Giao diện mẫu phần tạo nội dung vỏng quay từ Collection ](<../../.gitbook/assets/image (1175).png>)

Danh sách các Collecton đã tạo sẽ quản lý trong mục : Thêm mới- Quản lý nội dung&#x20;

## 2.Popup kết quả và Lời nhắn:

Nếu bạn dùng Popup mặc định thì sẽ hiển thị phần nội dung LỜI NHẮN tương ứng ở phía dưới.\
Trong trường hợp muốn dùng Popup tùy chọn, bạn [tạo 1 Popup mới](broken-reference) rồi sử dụng.

## 3.Hình nền

\
Bạn có thể tùy chỉnh lại phần hình nền theo mong muốn sử dụng, kích thước tiêu chuẩn cho ảnh nền là 400\*400px.\
Tham khảo thêm Kho thư viện ảnh nền [tại đây](https://www.facebook.com/groups/LadiPageVietnam/permalink/2458138047783323/).

## Cách hiển thị kết quả vòng quay trên popup kết quả&#x20;

Sau khi khách hàng quay vòng quay may mắn, bạn muốn kết quả vòng quay tự động điền vào POPUP kết quả , ở form trên popup, bạn sử dụng thêm trường : **Mã giảm giá**&#x20;

Trong trường hợp không muốn khách hàng bấm sửa được trường thông tin này, bạn có thể cho ẩn đi trường Mã giảm giá ở form đăng ký, thông tin vẫn gửi đầy đủ về kênh lưu trữ của bạn&#x20;

![](<../../.gitbook/assets/image (299).png>)

![](<../../.gitbook/assets/image (201).png>)

Ngoài ra, trong trường hợp bạn muốn hiển thị mã giảm giá khách hàng đã quay được trên popup , ví dụ chúc mừng bạn đã quay thành công mã giảm giá 15% , bạn thiết lập như sau: Vào phần Thêm mới- Tiêu đề, chỉnh sửa nội dung tiêu đề thành : Chúc mừng bạn đã quay thành công  \{{coupon\_text\}}&#x20;



## Các code tùy chỉnh cho phần vòng quay may mắn

Một số đoạn code nâng cao sau bạn có thể thêm vào phần **Mã tùy chỉnh nâng cao** trong thiết lập Vòng quay may mắn.

* Code hiển thị 1 phần tử, 1 popup hay 1 section sau khi kết thúc vòng quay:

> ladi('HEADLINE50').show();

* Code ẩn vòng quay ngay sau khi kết thúc lượt quay:

> ladi('SPINLUCKY41').hide();

* Code kéo đến một section nào đó khi kết thúc lượt quay:

> ladi('SECTION52').scroll();

> * Thêm lượt Spin Lucky
>
> ladi(SPINLUCKY123').add\_turn();

{% hint style="danger" %}
Lưu ý: thay tên ID tương ứng của các phần tử mà bạn muốn trong dấu ' '
{% endhint %}
