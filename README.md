# K5-L3B-Day05-Track3-VietnamBamboo

**Bài nộp LAB5 · Track T3 Du lịch:** trợ lý đổi chuyến khi chuyến bay bị huỷ.

**Lớp:** L3B · **Track:** T3 · **Tên nhóm:** VietnamBamboo

## Thành viên và phân công

| Họ và Tên | Mã Học Viên | Role | Việc đã làm |
|---|---|---|---|
| Bùi Đình Quý Anh | 2A202603969 | Role 1 · Kịch bản & phạm vi | spec §1 (lát cắt, 3 việc không làm), §2 (15 kịch bản, chọn 2 ca đắt nhất) · nói phần mở đầu khi demo |
| Nguyễn Thanh Tùng | 2A202603957 | Role 2 · Khi AI sai | spec §3 (câu AI nguyên văn, khách thấy gì, ai được báo, loại lỗi, nguyên tắc HAX) · demo Ca A |
| Trịnh Ngọc Ninh | 2A202603996 | Role 3 · Mức tự chủ | spec §4 (mức cho từng tool, tool khó xếp nhất, luật thêm, thử trên 3 kịch bản), §6 · demo Ca B |
| Giang Thái Sơn | 2A202603964 | Role 4 · Tổng hợp | prototype, ảnh đánh số, spec §5, ghép bài, repo · demo chỉ số ①–⑦ và trả lời ca lạ |
	
## Bài làm tóm tắt

- **Lát cắt:** khách vừa nhận tin chuyến BM 213 bị huỷ do bão nhắn hỏi; AI đề xuất và giữ chỗ, hỏi lại, đổi vé, hay chuyển nhân viên.
- **2 ca đắt nhất:**
  - "Đổi giúp mình chuyến sớm nhất": BM 217 chỉ còn 1 chỗ, mà vé có 2 người, một bé 5 tuổi.
  - "Thôi huỷ hết đi, hoàn tiền": yêu cầu hoàn gửi rồi không huỷ được.
- **Mức tự chủ chính:**
  - giữ chỗ: tự làm;
  - đổi vé: khách xác nhận, có tên từng hành khách;
  - hoàn vé: tách "soạn" (tự làm) khỏi "gửi" (khách xác nhận, chọn từng người);
  - cấm tách trẻ khỏi người lớn, cấm đổi lần hai, cấm hứa bồi thường.

## Cấu trúc repo

```
K5-L3B-Day05-Track3-VietnamBamboo/
├── README.md        ← file này
├── spec.md          ← bài nộp chính (§1–§7)
└── prototype/
    ├── index.html   ← prototype bấm được, mở bằng trình duyệt
    ├── README.md    ← cách bấm, chú thích ảnh
    └── anh-1.png · anh-2.png · anh-3.png   ← ảnh đánh số ①–⑦
```

## Checklist nộp (trước 23:59 ngày lab)

- [ ] Repo **công khai**, mở được bằng cửa sổ ẩn danh
- [ ] Mỗi người đọc lại phần có tên mình và giải thích được
- [ ] Sau buổi demo, điền ca lạ vào spec §7

> Dữ liệu trong bài là dựng; hãng "Bay Mẫu" là hãng dựng. Khoá học không liên kết với Traveloka hay hãng bay nào. Không có dữ liệu thật của người thật, không có API key.
