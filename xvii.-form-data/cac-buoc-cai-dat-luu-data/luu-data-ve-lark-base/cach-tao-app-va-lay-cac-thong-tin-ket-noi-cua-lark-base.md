# Cách tạo app và lấy các thông tin kết nối của Lark Base

## Khởi tạo custom app và lấy thông tin app\_id, app\_secret,

1. Truy cập [Lark Developer](https://open.larksuite.com/) và chọn Create Custom App

{% embed url="https://prnt.sc/Mua9Dedjvjsv" %}

<figure><img src="../../../.gitbook/assets/image (1205).png" alt=""><figcaption></figcaption></figure>

2. Nhập Name, Description và Icon cho App sau đó bấm Create để tạo

{% embed url="https://prnt.sc/YaD_NaREpHUW" %}

<figure><img src="../../../.gitbook/assets/image (1206).png" alt=""><figcaption><p>Giao diện sau khi tạo app thành công </p></figcaption></figure>

3. Tại mục Credentials & Basic Info lưu lại thông tin **App ID và App Secret**

<figure><img src="../../../.gitbook/assets/image (1207).png" alt=""><figcaption></figcaption></figure>

{% embed url="https://prnt.sc/EPEK4ddpW9y1" %}

4. Truy cập mục Permissions & Scopes để cấp quyền cho App
5. Tại mục API Scopes / Manage scopes chọn Docs và chọn Scope name:\
   \- View, comment, edit and manage Base (bitable:app)\
   \- View, comment, and export Base (bitable:app:readonly)\
   sau đó bấm chọn **Add in Bulk.**

<figure><img src="../../../.gitbook/assets/image (1208).png" alt=""><figcaption></figcaption></figure>

6. Chọn Confirm and go to create app version để xác nhận và gửi yêu cầu publish app.

{% embed url="https://prnt.sc/jQfgfZS6nlum" %}

7. Nhập thông tin phiên bản app (App version / Update Notes) và bấm Save để gửi yêu cầu review app. Bấm **Submit for release**

{% embed url="https://prnt.sc/-38dw_dEzufn" %}

{% embed url="https://prnt.sc/G2vyYoMonuap" %}

{% embed url="https://prnt.sc/81JuC9MsGp_y" %}

8. Truy cập [Lark Admin](https://www.larksuite.com/admin) và chọn mục Workplace / App Review để tiến hành duyệt app.
9. Chọn App cần duyệt và bấm Approve để duyệt app.

{% embed url="https://prnt.sc/yR232D33CzUt" %}

## Khởi tạo Base và lấy  app token

1. Truy cập Lark Docs và chọn New / Base

{% embed url="https://prnt.sc/8cruWmFpN_75" %}

{% embed url="https://prnt.sc/5_rFgeRMN31K" %}

Lấy **app\_token** từ đường dẫn tới Base (phần app\_token là text từ sau chữ base, đến trước chữ table)

{% embed url="https://prnt.sc/sr5iCmYuGNxx" %}
Ví dụ về 1 đường dẫn&#x20;
{% endembed %}

Để có thể đọc ghi được dữ liệu khi kết nối cần cấp quyền Edit cho thành viên trong tổ chức. Bấm Share và chọn People in the organization with the link can edit

{% embed url="https://prnt.sc/G59nx1NiCMga" %}



{% hint style="info" %}
Trong trường hợp bạn không kết nối được larkbase, bạn kiểm tra phần Bật quyền nâng cao để cấu hình thêm quyền cụ thể hay không. Quyền này phải ở chế độ Tắt thì bạn mới kết nối được ( chế độ như ảnh phía dưới )
{% endhint %}

{% embed url="https://prnt.sc/jWy83Y7mw5wE" %}

{% hint style="info" %}
Trong trường hợp bạn được mời thao tác trên file base, thông qua Invite Collaborators ( Mời cộng tac viên ), để thao tác kết nối với file base được mời này, bạn cần kiểm tra xem email/app của mình được mời đã có quyền Manager chưa.
{% endhint %}

