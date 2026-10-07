# 📝 Soạn 500 Câu Hỏi Trắc Nghiệm – Sinh Tế Bào & Vi Sinh

App 1 file duy nhất `index.html` — soạn, lưu, thi thử, xuất file để nộp/đẩy GitHub.

Nội dung bao phủ:
- **P1:** Tế bào nhân sơ/nhân thực + Màng tế bào (khảm lỏng)
- **P2:** Trao đổi chất, ATP, hô hấp, lên men, quang hợp
- **P3:** Dinh dưỡng VSV, sinh trưởng, sản phẩm chuyển hóa
- **P4:** Phân loại 2→3→4→5 giới→3 vực + Truyền tin tế bào

## 🚀 Cách dán lên GitHub (2 phút)

### Cách 1: Up file trực tiếp (nhanh nhất)
1. Tạo repo mới trên github.com → `New repository` → đặt tên `500-cau-hoi-sinh` → Public → Create
2. Bấm `uploading an existing file` → kéo thả 2 file `index.html` + `questions.json` vào → `Commit changes`
3. Xong! Ai cũng xem được code.

### Cách 2: Bật web làm bài online (GitHub Pages – khuyên dùng)
1. Sau khi up file, vào repo → `Settings` → `Pages`
2. `Branch`: chọn `main` + `/ (root)` → `Save`
3. Đợi 1-2 phút → mở link `https://ten-cua-ban.github.io/500-cau-hoi-sinh/`
4. Gửi link này cho bạn bè cùng soạn / thi thử.

### Cách 3: Dùng git trên máy
```bash
git clone https://github.com/ten-cua-ban/500-cau-hoi-sinh.git
# copy index.html + questions.json vào thư mục
git add index.html questions.json
git commit -m "them app soan 500 cau hoi"
git push
```

## 📋 Quy trình soạn đủ 500 câu

1. Mở `index.html` (double-click) hoặc mở link GitHub Pages
2. Bấm **📥 Nạp 30 câu mẫu** (tab Ngân hàng) → đã có sẵn 30 câu chuẩn theo đề cương của bạn
3. Sang tab **✏️ Soạn** → nhập tiếp cho đủ 500. Thanh tiến độ trên đầu báo `n / 500`
   - Chia chỉ tiêu: P1 ~120 câu, P2 ~130 câu, P3 ~130 câu, P4 ~120 câu
4. Tab **💾 Import/Export** → **Xuất questions.json** → commit file mới lên GitHub để lưu trữ
5. Cần file word/đề cương → **Xuất 500_cau_hoi.md**

## 📦 Định dạng 1 câu hỏi (JSON)

```json
{
  "part": "P1-C1: Tế bào nhân sơ & nhân thực",
  "level": "Trung bình",
  "question": "Nội dung câu hỏi?",
  "A": "Đáp án A",
  "B": "Đáp án B",
  "C": "Đáp án C",
  "D": "Đáp án D",
  "correct": "A",
  "explain": "Giải thích"
}
```

Mã phần dùng trong app:
- `P1-C1: Tế bào nhân sơ & nhân thực`
- `P1-CĐ: Màng tế bào`
- `P2-C2: Trao đổi chất & Năng lượng`
- `P2-CĐ: Quang hợp`
- `P3-C3.1: Dinh dưỡng & Sinh trưởng VSV`
- `P3-C3.2: Sản phẩm chuyển hóa VSV`
- `P4-C4: Đa dạng & Phân loại`
- `P4-CĐ: Truyền tin tế bào`

## 👥 Soạn nhóm
Mỗi người soạn 50-100 câu → mỗi người Xuất `questions.json` → gộp bằng cách vào app → Import file của nhau → Xuất file tổng → đẩy lên GitHub.
