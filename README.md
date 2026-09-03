# ExamInsight cho macOS

**Phần mềm thống kê kết quả thi trắc nghiệm** — đọc file kết quả do [ExamScan](https://github.com/viettien117/ExamScan_Windows_updates) chấm ra, tính điểm trung bình, tỷ lệ đạt, phân phối điểm và phân tích xem câu nào cả lớp sai nhiều nhất, rồi xuất báo cáo Excel/PDF.

Repo này host **bản cài đặt macOS** và **kênh cập nhật tự động** cho ExamInsight.

> Dùng Windows? Bản Windows ở [ExamInsight_Windows_updates](https://github.com/viettien117/ExamInsight_Windows_updates).

---

## Tải xuống

1. Vào trang [**Releases**](https://github.com/viettien117/ExamInsight_macOS_updates/releases/latest)
2. Trong mục **Assets**, tải đúng file `.dmg` cho máy của bạn:

| Máy | File |
|---|---|
| Apple Silicon (M1, M2, M3, M4…) | `ExamInsight-x.y.z-osx-arm64.dmg` |
| Intel | `ExamInsight-x.y.z-osx-x64.dmg` |

Không chắc máy mình loại nào? Bấm  → **About This Mac**: dòng **Chip** ghi "Apple M…" là Apple Silicon, ghi "Intel" là Intel.

3. Mở file `.dmg`, kéo **ExamInsight** vào thư mục **Applications**
4. Mở từ Launchpad hoặc thư mục Applications

Ứng dụng **đã được Apple công chứng (notarized)** nên mở được ngay, không hiện cảnh báo "không xác minh được nhà phát triển".

## Yêu cầu hệ thống

- macOS 12 (Monterey) trở lên
- Không cần cài .NET — bản đóng gói đã kèm sẵn

## Cập nhật tự động

Sau khi cài bản đầu tiên, **bạn không cần quay lại trang này nữa**. Ứng dụng tự kiểm tra bản mới khi mở và mỗi 24 giờ, có bản mới thì hỏi bạn rồi tự tải, tự thay thế và tự mở lại.

Kiểm tra thủ công: mở mục **Cập nhật** trong ứng dụng.

> File `.zip` trong mục Assets là **dành cho việc tự cập nhật**, không phải để tải tay. Cài lần đầu thì dùng `.dmg`.

## Bản quyền

Copyright © 2026 RuBi. All rights reserved.
