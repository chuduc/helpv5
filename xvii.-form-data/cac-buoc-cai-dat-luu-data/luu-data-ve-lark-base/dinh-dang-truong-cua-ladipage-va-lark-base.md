# Định dạng trường của LadiPage và Lark Base

Hiện tại khi đồng bộ dữ liệu , bên Lark yêu cầu thiết lập theo các định dạng trường của form , tương ứng với các trường  dữ liệu bên Larkbase, để data có thể về được kênh lưu trữ

Việc chọn các định dạng trường bên Lark base và form LadiPage, sẽ thao tác tại phần thiết lập Cấu hình form bên LadiPage&#x20;

{% embed url="https://prnt.sc/ON3ekWGamLlg" %}

{% embed url="https://prnt.sc/RHYp31O7IP7M" %}
Danh sách các trường bên LadiPage&#x20;
{% endembed %}

{% embed url="https://prnt.sc/LoIdmcX-tFVv" %}
Danh sách các trường bên Lark Base&#x20;
{% endembed %}

Bảng mô tả các định dạng trường bên Ladipage và bên Lark Base yêu cầu&#x20;

<table><thead><tr><th width="91">STT</th><th>Trường dữ liệu bên LadiPage </th><th>Trường dữ liệu bên Lark Base </th></tr></thead><tbody><tr><td>1</td><td>Họ và tên</td><td>Văn bản (1: Multiline)</td></tr><tr><td>2</td><td>Lời nhắn</td><td>Văn bản (1: Multiline)</td></tr><tr><td>3</td><td>Địa chỉ</td><td>Văn bản (1: Multiline)</td></tr><tr><td>4</td><td>Nhập chữ</td><td>Văn bản (1: Multiline)</td></tr><tr><td>5</td><td>Nhập đoạn văn</td><td>Văn bản (1: Multiline)</td></tr><tr><td>6</td><td>Nhập mật khẩu</td><td>Văn bản (1: Multiline)</td></tr><tr><td>7</td><td>Mã giảm giá</td><td>Văn bản (1: Multiline)</td></tr><tr><td>8</td><td>Zipcode</td><td>Văn bản (1: Multiline)</td></tr><tr><td>9</td><td>Số điện thoại</td><td>Số điện thoại</td></tr><tr><td>10</td><td>Địa chỉ email</td><td>Email</td></tr><tr><td>11</td><td>Nhập số</td><td><p>Số</p><p>(2: Number)</p></td></tr><tr><td>12</td><td>Số lượng</td><td><p>Số</p><p>(2: Number)</p></td></tr><tr><td>13</td><td>Hộp chọn giá trị (Combobox)</td><td><p>Một lựa chọn</p><p>(3: Single option)</p></td></tr><tr><td>14</td><td>Lựa chọn hình ảnh</td><td><p>Một lựa chọn</p><p>(3: Single option)</p></td></tr><tr><td>15</td><td>Chọn một giá trị (Radio)</td><td><p>Một lựa chọn</p><p>(3: Single option)</p></td></tr><tr><td>16</td><td>Sản phẩm</td><td><p>Một lựa chọn</p><p>(3: Single option)</p></td></tr><tr><td>17</td><td>Tỉnh thành </td><td><p>Một lựa chọn</p><p>(3: Single option)</p></td></tr><tr><td>18</td><td>Quận Huyện </td><td><p>Một lựa chọn</p><p>(3: Single option)</p></td></tr><tr><td>19</td><td> Phường xã </td><td><p>Một lựa chọn</p><p>(3: Single option)</p></td></tr><tr><td>20</td><td>Chọn nhiều giá trị  (Checkbox)</td><td>Nhiều lựa chọn (4: Multiple options)</td></tr><tr><td>21</td><td><p>Ngày tháng,</p><p>Nhập ngày tháng</p></td><td><p>Ngày</p><p>(5: Date)</p></td></tr><tr><td>22</td><td>Tôi đồng ý với chính sách điều khoản</td><td><p>Hộp kiểm</p><p>(7: Checkbox)</p></td></tr><tr><td>23</td><td>Chọn file</td><td><p>Liên kết</p><p>(15: Link)</p></td></tr><tr><td>24</td><td>url_page</td><td>Văn bản (1: Multiline)</td></tr><tr><td>25</td><td>utm_source</td><td>Văn bản (1: Multiline)</td></tr><tr><td>26</td><td>utm_medium</td><td>Văn bản (1: Multiline)</td></tr><tr><td>27</td><td>utm_campaign</td><td>Văn bản (1: Multiline)</td></tr><tr><td>28</td><td>utm_term</td><td>Văn bản (1: Multiline)</td></tr><tr><td>29</td><td>utm_content</td><td>Văn bản (1: Multiline)</td></tr><tr><td>30</td><td>variant_url</td><td>Văn bản (1: Multiline)</td></tr><tr><td>31</td><td>variant_content</td><td>Văn bản (1: Multiline)</td></tr><tr><td>32</td><td>ref</td><td>Văn bản (1: Multiline)</td></tr><tr><td>33</td><td>fbc</td><td>Văn bản (1: Multiline)</td></tr><tr><td>34</td><td>fbp</td><td>Văn bản (1: Multiline)</td></tr><tr><td>35</td><td>event_id</td><td>Văn bản (1: Multiline)</td></tr><tr><td>36</td><td>user_agent</td><td>Văn bản (1: Multiline)</td></tr><tr><td>37</td><td>ip</td><td>Văn bản (1: Multiline)</td></tr></tbody></table>

{% hint style="info" %}
* Trong trường hợp bạn sử dụng tài khoản Enterprise/Premium/Business có tính năng capture form, bạn có thể thêm ghi chú dữ liệu là capture form. Trong phần bảng ở larkbase, bạn tạo 1 trường dữ liệu tên là : status\_send loại định dạng trường Văn bản .Nếu dữ liệu là capture form thì sẽ tự động trả về nội dung : capture.
{% endhint %}
