# Survey

Tính năng cho phép tạo các câu khảo sát, lựa chọn để khách hàng lựa chọn và gửi thông tin về các kênh lưu trữ của bạn

{% embed url="https://youtu.be/O7Yqr2M-8Oo" %}

Truy cập mục Thêm mới- Phần tử- Survey để sử dụng tính năng&#x20;

![](<../../.gitbook/assets/image (984).png>)

### Thiết kế nội dung hiển thị của Survey&#x20;

Bấm vào Thuộc tính, chọn mục Thiết kế để tạo nội dung của Survey&#x20;

![](<../../.gitbook/assets/image (996).png>)

#### Mục 1 : Kiểu hiển thị&#x20;

Bạn chọn xem survey của mình sẽ hiển thị với nội dung : Chữ, Ảnh hay kiểu Chữ và Ảnh&#x20;

#### Mục 2 : Chọn nhiều Option&#x20;

Cho phép khách hàng được chọn 1 hay nhiều lựa chọn trên survey của bạn&#x20;

Trong trường hợp bạn thiết lập Chọn nhiều Option là Có và ở mục Sự kiện, bạn có thiết lập Sự kiện cho Survey thì sẽ hiển thị thêm nút bấm : Chữ nút bấm tiếp theo&#x20;

![](<../../.gitbook/assets/image (1078).png>)

Bạn có đổi tên cho nút bấm , còn chưa thiết lập thay đổi về hiển thị hình dáng, màu sắc nút bấm&#x20;

#### Mục 3: Danh sách Option&#x20;

Thiết lập nội dung hiển thị về ảnh, tiêu đề,giá trị cho nội dung Survey của bạn . Tùy theo nội dung bạn chọn ở mục 1, bạn sẽ có các trường thiết lập nội dung tương ứng

**Tiêu đề** : nội dung text hiển thị trên survey để khách hàng lựa chọn&#x20;

**Gía trị** ( trường giá trị bắt buộc của survey) **:** thông tin này sẽ hiển thị trên form đăng ký trong trường hợp bạn đồng bộ dữ liệu của survey với form của bạn&#x20;

Phần Chọn mặc định có 2 tác dụng : Option này sẽ luôn được sử dụng hiệu ứng lựa chọn trên phần hiển thị của Survey và phần Giá trị sẽ hiển thị trên trường form mà bạn đồng bộ dữ liệu&#x20;

Hình ảnh : nội dung hình ảnh hiển thị trên survey của bạn&#x20;

Bấm vào **Thêm mới** để thêm nội dung lựa chọn của Survey&#x20;

![](<../../.gitbook/assets/image (784).png>)

### Thiết lập hiệu ứng hiển thị  Survey&#x20;

Bấm vào Thuộc tính thiết lập, chọn mục HIệu ứng, thiết lập các hiệu ứng cho Survey&#x20;

![](<../../.gitbook/assets/image (1171).png>)

**Hiệu ứng lựa chọn**: phần hiển thị hiệu ứng khi bạn lựa chọn 1 nội dung trên survey&#x20;

### Sự kiện của Survey

![](<../../.gitbook/assets/image (977).png>)

![](<../../.gitbook/assets/image (1068).png>)

#### Mục 1 :Liên kết đến Form &#x20;

Bạn đồng bộ giá trị survey mà khách hàng lựa chọn vào phần form đăng ký trên trang của bạn&#x20;

Các thao tác thác thực hiện

1.Tích chọn vào form bạn muốn liên kết dữ liệu của survey&#x20;

2\. Trên form bạn vừa tích chọn đồng bộ dữ liệu, bạn thêm mới 1 trường dữ liệu Nhập chữ ( Input Text )- và thiết lập Tên lấy dữ liệu của trường dữ liệu là Tên lấy dữ liệu của Survey bạn muốn đồng bộ&#x20;

![](<../../.gitbook/assets/image (1159).png>)

#### Mục 2 : Danh sách hành động Hoàn tất

Sau khi khách hàng lựa chọn nội dung trên survey, bạn có thể thực hiện hành động chuyển tiếp đến 1 section khác hoặc mở tiếp 1 popup khác&#x20;

Liên kết đến Section : có 1 lưu ý nếu bạn liên kết đến 1 section bị ẩn đi, thì khi liên kết đến section này sẽ hiển thị ra&#x20;

Liên kết đến POPUP :&#x20;

Liên kết đến Tab : chi tiết hướng dẫn[ tại đây](../../xv.-su-kien-cho-phan-tu/su-kien-re-chuot/chuyen-tab.md)

Liên kết ẩn hiện phần tử : chi tiết hướng dẫn [tại đây ](../../xv.-su-kien-cho-phan-tu/su-kien-re-chuot/an-hien-phan-tu.md)

Chọn tương ứng hành động bạn muốn thực hiện, chọn ID section/popup, chuyển Tab tương ứng trên trang của bạn&#x20;

