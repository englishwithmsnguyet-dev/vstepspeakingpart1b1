# Quy chuẩn biên soạn VSTEP Speaking Part 01 – B1 LEVEL

Khi thêm mới hoặc chỉnh sửa chủ đề trong `script.js` (`practiceTopicsData`), **BẮT BUỘC** tuân thủ:

1. **Văn nói B1 ngắn gọn, tự nhiên:**
   - Bài mẫu dài **18–25 từ**, cấu trúc rõ ràng, dễ nói trôi chảy.
   - Chỉ dùng từ vựng thông dụng A2–B1; ưu tiên cụm từ trong **Bảng Lợi Ích** và **Bảng Hoạt Động**.
   - **Cấm dùng từ C1/C2, từ học thuật hoặc văn chương** (vd: `remarkably, indispensable, effortlessly, seldom, tranquil, serene, pristine, exquisite, wholesome, cultivate, sophisticated, ergonomic, utilizing, immense, perseverance, vitality, pampered, poised, deafening, vividly, downhearted, sorrowful, empathetic, reprocessing, non-intrusive...`).
2. **Đồng bộ đầy đủ 4 thành phần:** `formula`, `vocabGroups`, `samples[].text` và `samples[].formatted`. Không để lệch đại từ (`people ... my mind`) hay lặp từ.
3. **Bắt buộc chạy kiểm tra tự động trước khi commit/push:**
   ```bash
   node check_vocab.js
   ```
   Chỉ commit khi kết quả trả về **PASS (0 lỗi)** và đã nâng version cache `?v=...` cho `script.js` trong `index.html`.
