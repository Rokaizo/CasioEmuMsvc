<div align="center">

<img src="./assets/casioemumsvc-male.jpg" width="96" height="96" alt="Biểu tượng CasioEmuMsvc"/>

# CasioEmuMsvc

**Trình mô phỏng và bộ công cụ phát triển dành cho dòng vi điều khiển nX-U8/100 và nX-U16/100.**

</div>

---

## Giới thiệu

CasioEmuMsvc là một dự án tập trung vào việc mô phỏng các dòng vi điều khiển **nX-U8/100** và **nX-U16/100**, đồng thời cung cấp các công cụ hỗ trợ quá trình nghiên cứu, phát triển và kiểm thử.

Dự án hướng tới một môi trường làm việc thuận tiện, kết hợp trình mô phỏng với các công cụ cần thiết để quan sát, phân tích và chỉnh sửa chương trình.

## Tính năng chính

- **Mô phỏng vi điều khiển:** hỗ trợ nX-U8/100 và nX-U16/100.
- **Bộ công cụ phát triển:** gồm trình gỡ lỗi, trình dịch ngược và trình chỉnh sửa HEX.
- **Ảnh chụp và trạng thái:** hỗ trợ lưu trạng thái, tạo nhiều nhánh trạng thái và xem trước màn hình.
- **Hệ thống mở rộng:** hỗ trợ MCP, Python, Cw2tools và các tiện ích mở rộng tùy chỉnh.
- **Nhiều nền tảng:** có các bản xây dựng cho Windows, macOS, Linux và Android.
- **Tùy biến:** hỗ trợ quản lý giao diện, bản địa hóa, Discord Rich Presence và kiểm tra cập nhật.

## Nền tảng

Dự án hiện có cấu hình xây dựng cho:

- **Windows** — hỗ trợ xây dựng bằng MSVC.
- **macOS**
- **Linux** — sử dụng CMake/Ninja.
- **Android** — sử dụng Gradle/NDK.

## Lưu ý khi chạy trên macOS

Bản macOS sử dụng chữ ký tạm thời nên Gatekeeper có thể chặn ứng dụng ở lần chạy đầu tiên và hiển thị thông báo như **“Launch failed”** hoặc **“App is damaged”**.

Sau khi giải nén ứng dụng, mở Terminal và chạy:

```bash
xattr -cr /đường/dẫn/tới/CasioEmuMsvc.app
```

Có thể gõ `xattr -cr ` trong Terminal rồi kéo tệp ứng dụng vào cửa sổ Terminal để điền đường dẫn tự động. Sau khi thực hiện lệnh, có thể mở ứng dụng như bình thường.

## Cộng đồng và hỗ trợ

- **Discord:** https://discord.gg/NM39VPdJTf
- **Email:** telecomadm1919@gmail.com
- **Báo lỗi và đề xuất:** https://github.com/Rokaizo/CasioEmuMsvc/issues

---

**CasioEmuMsvc — một bộ công cụ dành cho việc mô phỏng, nghiên cứu và phát triển trên nền nX-U8/100 và nX-U16/100.**
