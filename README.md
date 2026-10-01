# Wedpix Album — bản cài

Kho này chỉ chứa **file tải về** của app Wedpix Album. Mã nguồn không nằm ở đây.

## Tải app

Vào mục [Releases](../../releases) rồi lấy bản mới nhất:

| File | Dành cho |
|---|---|
| `WedpixAlbum-AppleSilicon.zip` | Mac chip Apple (M1, M2, M3…) |
| `WedpixAlbum-Intel.zip` | Mac chip Intel |

Không biết máy mình loại nào: bấm  → **Giới thiệu về máy Mac này**, dòng
**Chip** ghi "Apple M…" thì lấy bản AppleSilicon, ghi "Intel" thì lấy bản Intel.

## Cài

1. Giải nén
2. Kéo **Wedpix Album** vào thư mục **Applications**
3. Mở Terminal, dán dòng này rồi Enter:

```bash
xattr -cr "/Applications/Wedpix Album.app"
```

Bước 3 cần vì app chưa mua chữ ký số của Apple (99 USD/năm). Không chạy thì
macOS báo app bị hỏng.

## Cập nhật

App tự kiểm tra mỗi lần mở. Có bản mới thì hiện dải báo ngay trong app.

---

© 2026 WedPix · wedpix.vn
