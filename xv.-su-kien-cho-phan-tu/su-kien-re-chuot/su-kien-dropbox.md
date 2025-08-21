---
description: >-
  Dropbox cũng là 1 dạng hiển thị như popup, rê chuột vào phần tử liên kết đến
  popup thì nội dung sẽ bật ra, nhưng sẽ có 1 số nội dung khác biệt.
---

# Sự kiện Dropbox

1. **Tạo nội dung Dropbox**&#x20;

Để thiết lập sự kiện Dropbox, bạn cần vào mục Dropbox để tạo nội dung của Dropbox trước. Bạn theo dõi cách tạo dropbox [tại đây](https://help.ladipage.vn/cac-phan-t-co-ban-tren-landingpage/dropbox).

Sau khi đã hoàn thiện nội dung của Dropbox, bạn sẽ đi liên kết hiên thị cho phần tử đến Dropbox bạn đã tạo.

**2. Liên kết phần tử đến Dropbox.**

Bạn vào phần Thiết lập của phần tử--> chọn Sự kiện--> Hành động rê chuột --> Mở Dropbox--> Chọn dropdox muốn liên kết.

<figure><img src="../../.gitbook/assets/rê chuột.png" alt=""><figcaption></figcaption></figure>

Ở mục Dropbox, sẽ hiển thị ra danh sách các dropbox bạn đã tạo từ mục 1, bạn chọn Dropbox tương ứng để sử dụng.

Sau khi chọn được Dropbox sẽ hiển thị, bạn chọn thiết lập Vị trí, Khoảng cách (so với phần tử liên kết đến Dropbox) và Hiệu ứng.

<figure><img src="../../.gitbook/assets/rê chuột2.png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
**So sánh Dropbox và Popup.**

* Dropbox chỉ dùng cho phần liên kết phần tử trong mục Sự kiện, KHÔNG hiển thị độc lập trên trang như popup (thoát trang, vào trang, tới 1 section).
* Khi phần tử được thiết lập đến Dropbox, thì khi dropbox hiển thị theo vị trí thiết lập so với phần tử, dựa vào phần Vị trí, khoảng cách bạn thiết lập cho dropbox và phần tử đó.
* Khi phần tử được liên kết sự kiện đến popup thì popup hiển thị theo các vị trí hiển thị cố định của popup được thiết lập, KHÔNG phụ thuộc vào vị trí phần tử liên kết đến popup.
{% endhint %}

{% hint style="danger" %}
**Lưu ý Dropbox.**

* Sau khi đã hiển thị dropbox, khi click ra ngoài phần tử thì phần dropbox mới bị mất đi, còn không thì nội dung sẽ được hiển thị  luôn luôn trên trang.&#x20;
* Không nên cài đặt bên trong dropbox lại mở 1 dropbox khác.
* Khi bạn tạo dropbox, trong đó có chứa nội dung liên kết đến 1 popup, thì khi mở popup sẽ bị đè dưới dropbox, muốn tắt đi dropbox thì bạn cần thiết lập phần ẩn phần tử cho dropbox ở phần tử liên kết đến popup.
{% endhint %}

