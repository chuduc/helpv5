# 14.Bảo mật

Các tài khoản trả phí LadiPage, sẽ có tính năng Bảo mật vơi email OTP, để tăng tính bảo mật cho tài khoản khi khách hàng thao tác vào các nội dung tải backup, thay đổi tài khoản liên kết, cấu hình form...

Truy cập  **Cài đặt-> Bảo mật -> Bấm Bật OTP** ở các nội dung thao tác bạn muốn yêu cầu OTP email.

Có 3 tính năng đang cài đặt được email OTP&#x20;

1. Tải backup&#x20;
2. Thay đổi tài khoản liên kết : sửa, xóa tài khoản liên kết&#x20;
3. Thay đổi cấu hình form : thêm, sửa, xóa cấu hình form
4. Tải file .ladipage

## Cơ chế hoạt động

Khi tính năng OTP được bật, mỗi lần thao tác vào các tính năng cài đặt email OTP, người thao tác sẽ nhận được 1 email OTP gửi về **email tài khoản ladipage**, nhập mã OTP để tiếp tục được thao tác đang thực hiện

<figure><img src="../.gitbook/assets/image (1289).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (1290).png" alt=""><figcaption></figcaption></figure>

## Các lưu ý về OTP email

{% hint style="danger" %}
Chỉ có Owner mới có quyền thao tác bật/ tắt  tính năng bảo mật OTP email&#x20;
{% endhint %}

{% hint style="danger" %}
Quyền thao tác với tính năng tải backup, tài khoản liên kết, cấu hình form, tải .ladipage vẫn giữ nguyên theo phần phân quyền của tài khoản ladipage. chi tiết phần quyền [tại đâ](https://docs.google.com/spreadsheets/d/18CMe3T_FDa2ioNVpCmidFS303fx7EZUm-ZwZJd1WQ1w/edit#gid=1085223129)y. Tài khoản không có quyền thao tác tính năng, sẽ không có phần hiển thị nhập OTP
{% endhint %}

{% hint style="danger" %}
Mã OTP có hiệu lực trong 5 phút, chỉ cho phép dùng 1 lần và áp dụng được cho người thao tác tạo mã OTP
{% endhint %}
