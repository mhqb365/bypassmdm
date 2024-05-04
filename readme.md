# Hướng dẫn bypass MDM MacBook nhanh gọn

## Bước 1. Cài lại MacOS

> Khi cài nhớ format ổ đĩa với tên này để không gặp lỗi ở bước 3: Macintosh HD

## Bước 2. Vào Recovery

> Sau khi cài xong MacOS thì đè nút nguồn cho máy tắt hẳn rồi đưa máy vào Recovery

- Máy xài chip Intel: bấm nút nguồn rồi nhanh tay giữ tổ hợp phím Command + R, khi thấy logo táo và thanh loading thì có thể thả tay
- Máy xài chip M: đè nút nguồn đến khi thấy dòng chữ <b>Loading Startup Options</b> thì thả tay ra, load xong thì chọn Options

## Bước 3. Chạy tools bypass

> Vào được Recovery thì chọn Safari và truy cập địa chỉ: https://mdm.mhqb365.com<br />
> Bạn sẽ gặp lại bài viết này, hãy copy đoạn mã dưới đây:

```sh
curl https://raw.githubusercontent.com/mhqb365/bypassmdm/main/mdm.sh -o mdm.sh && chmod +x ./mdm.sh && ./mdm.sh
```

> Tắt Safari đi, mở Terminal và dán đoạn mã vừa copy vào rồi Enter<br />
> Nhập tên tài khoản + mật khẩu theo hướng dẫn hoặc cứ Enter 3 lần để đặt theo mặt định (tk: MAC / mk: 1234)<br />
> Thấy dòng chữ <b>Chặn host thành công</b> thì khởi động lại hoặc gõ vào từ này rồi enter cho lẹ: reboot

## Bước 4. Setup vào trong như bình thường

> Sau khi setup vào trong thì nên tạo tk Admin mới và xóa tk MAC đi để tránh những thông báo lỗi không quan trọng

### Tận hưởng thành quả thôi, chúc các bạn thành công!

**License: GNU**

*Nguồn: maclife.io*