# 11. LadiPage Framework



Bạn có thể sử dụng thêm các code cho vào phần SỰ KIỆN-MÃ TÙY CHỈNH NÂNG CAO của các phần tử để thiết lập thêm tính năng , hiệu ứng cho phần tử đó

![](<../.gitbook/assets/image (318).png>)

Một số nội dung code bạn có thể sử dụng

*   **Hiện LightBox IFrame bất kì, ví dụ như google map**

    lightbox\_iframe(' code iframe muốn sử dụng ');
*   **Hiện LightBox Hình ảnh**&#x20;

    lightbox\_image('[https://w.ladicdn.com/599e5ad132c5e4d618ba0fb7/over-20200608091433.jpg](https://w.ladicdn.com/599e5ad132c5e4d618ba0fb7/over-20200608091433.jpg)');
*   **Hiện LightBox Video theo youtube hoặc link của LadiPage**

    lightbox\_video('[https://www.youtube.com/watch?v=XIOPBQhOjhk](https://www.youtube.com/watch?v=XIOPBQhOjhk)', 'youtube');

    lightbox\_video('[https://s.ladicdn.com/5b8e3a1a8bdb4374b2840137/video-ngan-lam-anh-bia-dep-va-y-nghia-phan-2-20200623034148.mp4](https://s.ladicdn.com/5b8e3a1a8bdb4374b2840137/video-ngan-lam-anh-bia-dep-va-y-nghia-phan-2-20200623034148.mp4)', 'direct');
*   **Mở một đường dẫn '\_blank' = mở trên trang mới; '\_top' = mở trên trang hiện tại**

    ladi('[https://abc.com').open\_url('\_blank](https://abc.com'\).open_url\('_blank)');

    ladi('[https://abc.com').open\_url('\_top](https://abc.com'\).open_url\('_top)');
*   **Gửi form data (bằng với việc bấm nút bấm ở Form)**

    ladi('FORM123').submit();
*   **Cuộn đến section**

    ladi('SECTION123').scroll();
*   **Sửa giá trị của text, text trên form**

    ladi('HEADLINE123').value('LadiPage');

    ladi('PARAGRAPH123').value('LadiPage');

    ladi('FORM\_ITEM123').value('Ladipage');
*   **Hiện section lên trên cùng trang**

    ladi('SECTION123').top();
*   **Tạm dừng video**

    ladi('VIDEO123').pause();
*   **Chạy video**

    ladi('VIDEO123').play();
*   **Prev gallery, carousel**

    ladi('GALLERY123').prev();

    ladi('CAROUSEL123').prev();
*   **Next gallery, carousel**

    ladi('GALLERY123').next();

    ladi('CAROUSEL123').next();
*   **Ẩn phần tử**

    ladi('BUTTON123').hide();
*   **Hiện phần tử**

    ladi('BOX123').show();
*   **Quay spin lucky**

    ladi('SPINLUCKY123').start();
*   **Thêm lượt spin lucky**

    ladi('SPINLUCKY123').add\_turn();
