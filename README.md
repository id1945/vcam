# 📱 Hướng Dẫn Root & Cài Đặt Module Android (LSPosed, VCam, Bypass Root)

> ⚠️ **LƯU Ý TRỌNG YẾU BẮT BUỘC:**  
> Hãy cài đặt **TWRP (Team Win Recovery Project)** trước khi thực hiện bất kỳ thao tác nào bên dưới để có thể cứu máy (*unbrick*) khi gặp lỗi treo logo (*bootloop*).  
> **Yêu cầu:** Máy đã được **Root** thành công!

---

## 📋 Danh Sách Các Bước Thực Hiện

```
┌─────────┐     ┌─────────┐     ┌─────────┐     ┌─────────┐
│ Bước 1  │ ──> │ Bước 2  │ ──> │ Bước 3  │ ──> │ Bước 4  │
│ Magisk  │     │ Zygisk  │     │ LSPosed │     │  VCam   │
└─────────┘     └─────────┘     └─────────┘     └─────────┘
```

---

### 🔻 Bước 1: Cài đặt Magisk ⚡
* **Mô tả:** Quản lý quyền Root cho thiết bị Android.
* 🔗 **Link Download:** [Magisk Releases](https://github.com/topjohnwu/Magisk/releases)

---

### 🔻 Bước 2: Cài đặt Zygisk hoặc Riru 🧬
Chọn 1 trong 2 nền tảng phù hợp với thiết bị của bạn:

* 🔗 **ZygiskNext:** [Tải ZygiskNext tại đây](https://github.com/Dr-TSNG/ZygiskNext/releases)  
* 🔗 **Riru:** [Tải Riru tại đây](https://github.com/RikkaApps/Riru/releases)

👉 **Hướng dẫn cài đặt:**
1. Mở ứng dụng **Magisk** trên điện thoại.
2. Chuyển sang mục **Module (Mô đun)**.
3. Nhấn **Chọn từ bộ nhớ** và tìm đến file `.zip` vừa tải về để cài đặt.
4. Truy cập **Cài đặt Magisk** để kích hoạt **Zygisk** (hoặc **Riru**).
5. Khởi động lại thiết bị.

---

### 🔻 Bước 3: Cài đặt LSPosed Framework 🧩
* 🔗 **Link Download:** [LSPosed Releases](https://github.com/LSPosed/LSPosed/releases)

👉 **Hướng dẫn cài đặt:**
1. Mở ứng dụng **Magisk** > Chuyển sang mục **Module (Mô đun)**.
2. Chọn file **LSPosed `.zip`** vừa tải về và tiến hành cài đặt.
3. Khởi động lại máy để hoàn tất.

💡 **Mẹo:** Bạn có thể tham khảo thêm kho lưu trữ các Module LSPosed tại [modules.lsposed.org](https://modules.lsposed.org/).

---

### 🔻 Bước 4: Cài đặt VCam (Virtual Camera) 📹

Danh sách các phiên bản VCam hỗ trợ thay thế camera thực tế bằng video:

* 🚀 **VCAMPro (rhprincess):** [Tải bản Release](https://github.com/rhprincess/VCAMPro/tree/master/app/release)
* 🚀 **VCAMPRO (xiaobutiaoer):** [Tải bản Release](https://github.com/xiaobutiaoer/VCAMPRO/tree/master/app/release)
* 💾 **VCam Full cho Root (Bản ngoại tuyến):** [Tải file 离线版本.apk](https://github.com/id1945/vcam/blob/main/%E7%A6%BB%E7%BA%BF%E7%89%88%E6%9C%AC.apk)
* ❌ **Vcamera (Đã ngưng hoạt động / DIE):** [Link GitHub tham khảo](https://github.com/andvipgroup/VCamera)

---

## 🛡️ Hướng Dẫn Ẩn Root & Vượt Kiểm Tra Security (Bypass Root / SafetyNet)

### 1. 🛡️ Bypass Root / Vượt Check Root
Giúp các ứng dụng ngân hàng hoặc game không phát hiện máy đã Root:
* 🔗 **BypassRootCheckPro:** [Tải bản v1.0](https://github.com/gauravssnl/BypassRootCheckPro/releases/tag/v1.0)

### 2. 🥷 Shamiko (Công cụ ẩn Root nâng cao)
Công cụ ẩn Root phiên bản Pro trên điện thoại Android cực kỳ mạnh mẽ.
* 🔗 **Shamiko v1.2:** [Tải Shamiko Releases](https://github.com/LSPosed/LSPosed.github.io/releases)

### 3. 🔰 SafetyNet Fix (Sửa lỗi Play Integrity / SafetyNet)
Nếu bạn vẫn gặp sự cố khi vượt qua SafetyNet hoặc Play Integrity với mô-đun này, hãy giả mạo hồ sơ của thiết bị đã được chứng nhận bằng cách sao chép các thuộc tính `ro.product`.
* 🔗 **SafetyNet-fix:** [Tải Universal SafetyNet Fix](https://github.com/kdrag0n/safetynet-fix)

---
*Chúc bạn thực hiện thành công! Luôn sao lưu dữ liệu trước khi nâng cấp hoặc cài thêm Module mới.*
