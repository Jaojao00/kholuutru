<div align="center">

![KhoLuuTru Version](https://img.shields.io/badge/KHOLUUTRU-1.0-2ea44f?style=for-the-badge)

# 💎 KhoLuuTru 1.0

*Plugin kho khoáng sản nâng cao cho server Skyblock — phát triển bởi*<br>
***Tài Dev Nguyễn***

---

![Minecraft](https://img.shields.io/badge/Minecraft-1.21%2B-2ea44f?style=flat-square)
![Java](https://img.shields.io/badge/Java-21%2B-orange?style=flat-square)
![Database](https://img.shields.io/badge/Database-SQLite-blue?style=flat-square)
![Economy](https://img.shields.io/badge/Economy-Vault-yellow?style=flat-square)
![API](https://img.shields.io/badge/API-PlaceholderAPI-purple?style=flat-square)

![Type](https://img.shields.io/badge/Type-Skyblock_Storage-ff69b4?style=flat-square)
![Author](https://img.shields.io/badge/Author-Tài_Nguyễn-gray?style=flat-square)
![License](https://img.shields.io/badge/License-Private-red?style=flat-square)

</div>

---

**KhoLuuTru** là một plugin Minecraft đột phá dành cho máy chủ Paper/Folia (phiên bản 1.21+). Plugin này mang đến hệ thống "Kho Ảo" thông minh, giúp người chơi tự động lưu trữ tài nguyên khoáng sản thu thập được mà không lo đầy túi đồ.

---

## 🌟 Tính Năng Nổi Bật

- **Tự Động Thu Thập (Auto-Pickup):** Vật phẩm đào được (đặc biệt là quặng/khoáng sản) sẽ tự động bay thẳng vào Kho Ảo thay vì rớt ra đất hay lấp đầy túi đồ.
- **Tương thích Custom Enchants & MMOItems:** Hệ thống nhận diện thông minh hỗ trợ 100% các loại cúp có bùa Autosmelt hoặc bùa hiệu suất (Efficiency) siêu cao từ các plugin bên thứ ba.
- **Hút luôn Kinh Nghiệm (EXP):** Không chỉ vật phẩm, các điểm kinh nghiệm đào được cũng tự động nạp thẳng vào thanh kinh nghiệm của người chơi.
- **Quản lý Danh sách trắng (Kholist):** Quản trị viên và người chơi (nếu được cấp quyền) có thể dễ dàng quản lý những vật phẩm nào được phép chui vào kho thông qua giao diện GUI thân thiện.
- **Giao dịch Trực tiếp:** Hỗ trợ bán vật phẩm thẳng từ kho để lấy tiền (Tích hợp Vault).
- **Hệ thống Đối tác (Partner):** Chia sẻ quyền truy cập kho với bạn bè một cách an toàn và minh bạch.
- **Hỗ trợ Folia & Paper:** Thiết kế tối ưu đa luồng, hỗ trợ hoàn hảo cho cả Paper và kiến trúc Regionized của Folia.

## 📦 Yêu cầu hệ thống
- **Java:** JDK 21 trở lên.
- **Máy chủ:** Paper, Purpur hoặc Folia (Phiên bản 1.21 trở lên).
- **Plugin phụ thuộc:** Vault (nếu muốn dùng chức năng bán vật phẩm).

## 🚀 Cài Đặt

1. Tải phiên bản mới nhất tại mục [Releases](#).
2. Chép tệp `KhoLuuTru-1.0-SNAPSHOT-all.jar` vào thư mục `plugins` của máy chủ.
3. Khởi động lại máy chủ (hoặc dùng `/reload confirm`).
4. Tùy chỉnh danh sách vật phẩm tự động nhặt tại `plugins/KhoLuuTru/config.yml`.

---
---

## 🎮 Lệnh & Quyền (Permissions)

| Lệnh | Chức năng | Quyền yêu cầu |
| --- | --- | --- |
| `/kho` | Mở giao diện Kho Lưu Trữ chính. | `kho.use` |
| `/kho auto` | Bật/tắt chế độ tự động nhặt cá nhân. | `kho.use` |
| `/kho sell` | Mở giao diện bán vật phẩm. | `kho.use` |
| `/kho partner` | Mở giao diện quản lý Đối tác. | `kho.use` |
| `/kho filter` | Mở giao diện lọc (chặn/nhặt) vật phẩm. | `kho.use` |
| `/kho admin reload` | Tải lại tệp cấu hình config.yml. | `kho.admin` |

*Ghi chú: Lệnh `/kho` có thể thay thế bằng các alias như `/storage`, `/kholuutru`.*

## 📖 Hướng Dẫn Nhanh

- **Thêm đồ vào kho siêu tốc:** Mở `/kho`, sau đó nhấp chuột vào món đồ bạn muốn cất ở nửa dưới màn hình (túi đồ cá nhân). Bấm "Cất" để chuyển đồ.
- **Quản lý danh sách tự động nhặt:** Trong `/kho`, bấm vào biểu tượng Cuốn Sách ở góc dưới để mở danh sách Kholist. Bạn có thể bấm vào đồ trong túi để thêm vào danh sách, hoặc bấm vào đồ trên menu để xóa.

---

## 🎥 Video Hướng Dẫn (Video Tutorial)

[![Video Huong Dan](https://img.youtube.com/vi/YOUR_VIDEO_ID/0.jpg)]([https://www.youtube.com/watch?v=YOUR](https://youtu.be/yqa4h8YieXo)_VIDEO_ID)

*(Nhấn vào hình ảnh phía trên để xem video giới thiệu và hướng dẫn chi tiết cách sử dụng plugin từ tác giả)*

---

## 👨‍💻 Thông tin Tác Giả

**KhoLuuTru** được thiết kế và phát triển bởi:
- **Tác giả:** Tài Dev Nguyễn
- **Email Liên hệ:** [tainguyenhr.dev@gmail.com](mailto:tainguyenhr.dev@gmail.com)

Nếu bạn có bất kì góp ý nào hoặc muốn báo lỗi, xin vui lòng liên hệ qua địa chỉ email trên hoặc tạo một *Issue* trên kho lưu trữ mã nguồn này. Xin cảm ơn vì đã tin dùng sản phẩm!
