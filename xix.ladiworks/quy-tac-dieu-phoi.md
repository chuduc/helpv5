# Quy tắc điều phối

Quy tắc điều phối  trong LadiWork giúp tự động phân chia các giao dịch, công việc mới  được cập nhật đến đúng nhân sự phụ trách, dựa trên các điều kiện đã được cấu hình trước đó. Tính năng này đảm bảo quá trình xử lý khách hàng tiềm năng (Leads) diễn ra nhanh chóng, công bằng và không bỏ sót.

Thay vì phụ thuộc vào việc phân công thủ công, hệ thống sẽ tự động xác định người nhận giao dịch, công việc dựa trên các trường dữ liệu như: loại sản phẩm, kênh tiếp cận, khu vực, giai đoạn , hoặc thông tin liên hệ như số điện thoại/email của khách hàng.

Quy tắc điều phối  đặc biệt hữu ích trong môi trường có nhiều nhân viên kinh doanh, đảm bảo tính minh bạch và tối ưu hiệu suất chăm sóc khách hàng.

Chức năng này cho phép quản trị viên cấu hình nhiều quy tắc (Rule) theo độ ưu tiên, đồng thời theo dõi được lịch sử phân chia để đánh giá hiệu quả phân bổ nguồn lực.

Truy cập ứng dụng **LadiWork -> Cài đặt -> Quy tắc điều phối**&#x20;

<figure><img src="../.gitbook/assets/image (1497).png" alt=""><figcaption></figcaption></figure>

## Cách thiết lập quy tắc điều phối tự động&#x20;

_Lưu ý: Bạn có thể thêm tối đa 10 quy tắc điều phối ở trạng thái Kích hoạt_&#x20;

Nhấp vào **“+ Thêm quy tắc mới”** để tạo một quy tắc gán tự động mới.

<figure><img src="../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

Bạn xác định **Trường dữ liệu** muốn làm điều kiện cho phân chia giao dịch công việc&#x20;

<figure><img src="../.gitbook/assets/image (4) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

Khi điều kiện đã được xác định, bạn cần chọn người dùng được gán cụ thể&#x20;

Có 2 loại người được gán để lựa chọn:

*   **Người tạo giao dịch** : là người tạo ra giao dịch đáp ứng với điều kiện phân chia tự động&#x20;

    <figure><img src="../.gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>



* **Người dùng** – Những thành viên đang được kích hoạt quyền ứng dụng LadiWork trong tài khoản&#x20;

<figure><img src="../.gitbook/assets/image (3) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

Sau khi thiết lập các điều kiện và người dùng , bạn nhập Tên cho phần quy tắc và bấm Kích hoạt quy tắc&#x20;

Cuối cùng bấm **Xác nhận** để hoàn thiện việc thiết lập

<figure><img src="../.gitbook/assets/image (5) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>



## Thứ tự phân chia giao dịch, công việc theo phần phân công tự động

* Các quy tắc phải ở trạng thái Kích hoạt&#x20;
* Giao dịch/ Công việc sẽ được phân chia theo quy tắc từ trên xuống dưới, quy tắc nằm phía trên sẽ được ưu tiên chạy trước quy tắc nằm bên dưới.
* Thỏa mãn quy tắc nào thì sẽ dừng lại ở quy tắc đó&#x20;
* Với trường hợp giao dịch/công việc được tạo không khớp với bất kỳ quy tắc  nào thì giao dịch/ công việc sẽ được khởi tạo bình thường theo thông tin tạo.
* Với trường hợp giao dịch/công việc trùng khớp với quy tác phân chia  nhưng tài khoản được chỉ định phân chia giao dịch/ công việc bị xóa, không tồn tại nữa thì deal sẽ được chuyển về cho Người tạo giao dịch/ công việc  hoặc chủ sở hữu ứng dụng&#x20;

## Lịch sử phân công&#x20;

Truy cập ứng dụng **-> Quy tác điều phối -> Lịch sử phân công,** để xem được lịch sử phân chia các giao dịch/ công việc của tài khoản&#x20;

<figure><img src="../.gitbook/assets/image (1498).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (6) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

Trong đó, mỗi dòng lịch sử thể hiện được:&#x20;

* Tên giao dịch
* Quy tắc  trùng khớp được áp dụng (Nếu không khớp bất kỳ quy tắc nào thì sẽ  báo “Không có quy tắc áp dụng”
* Người được phân chia (Người được phân chia  theo quy tác)
* Thời gian
* Trạng thái (Đã phân công/ Chia phân công )
