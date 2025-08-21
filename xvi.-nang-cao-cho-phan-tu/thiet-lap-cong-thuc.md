# 7. Thiết lập công thức

Phần này cho phép bạn nối nhiều dữ liệu với nhau (text hoặc số) hoặc cộng/trừ/nhân/chia  các dữ liệu dạng số thành 1 giá trị cụ thể

Bạn truy cập mục Thiết lập của phần tử -> Nâng Cao -> Thiết lập công thức, chọn trạng thái là Bật để kích hoạt sử dụng&#x20;

<figure><img src="../.gitbook/assets/image (493).png" alt=""><figcaption></figcaption></figure>

Ví dụ về việc sử dụng thiết lập công thức&#x20;

<figure><img src="../.gitbook/assets/công thức.gif" alt=""><figcaption><p>Ví dụ phần ghép các chứ với nhau </p></figcaption></figure>

<figure><img src="../.gitbook/assets/công thức số .gif" alt=""><figcaption><p>Ví dụ về công thức cộng số </p></figcaption></figure>

{% hint style="info" %}
Các lưu ý về việc thiết lập công thức&#x20;

*   Trường hợp bạn muốn các giá trị là nối tiếp nhau, có dấu cách thì trong công thức bạn sử dụng thêm kí tự :  " ...." ( dấu ... bạn có thể thay thế tùy ý ) , ví dụ bạn muốn giá trị của text sau khi ghép hiển thị là Ladi\_Page thì công thức bạn thao tác&#x20;

    ```
    {{FORM_ITEM9}} + "_ " + {{FORM_ITEM10}}
    ```
* Trường hợp bạn muốn thêm trường dữ liệu form  tỉnh thành. quận huyện, phường xã thì bạn phải lấy lần lượt các giá trị tỉnh , thành, quận huyện, phường xã, ví dụ về việc tạo công thức cho phần trường tỉnh thành  ( quận/huyện- phường/xã thay đổi giá trị  state trong công thức thành district/ ward tương ứng)
*   ```
    {{FORM_ITEM1.state}} : lấy giá  trị là mã tỉnh thành 
    ```

    ```
    {{FORM_ITEM1.state.value}} : lấy giá trị là mã tỉnh thành
    ```

    ```
    {{FORM_ITEM1.state.label}} : lấy giá trị tên tỉnh
    ```
* Trường hợp bạn muốn cộng các giá trị số lại với nhau ví dụ form item 1 và form item 2 thì bạn thiết lập \{{FORM\_ITEM1\}}+\{{FORM\_ITEM2\}}

Lưu ý : các giá trị FORM\_ITEM1 bạn phải thay thế tương ứng với giá trị thực tế trên form của bạn . Cách lấy giá trị FORM\_ITEM bạn lấy như ảnh mẫu hướng dẫn&#x20;

```
```
{% endhint %}

<figure><img src="../.gitbook/assets/image (1183).png" alt=""><figcaption></figcaption></figure>

