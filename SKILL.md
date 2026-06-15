---
name: flashcard-luat-dan-su
description: >
  Tạo bộ flashcard học Bộ luật Dân sự 2015 từ Obsidian vault tại
  github.com/datng3823/tom-tat-luat-dan-su. Dùng skill này bất cứ khi
  nào người dùng yêu cầu "làm flashcard", "tạo thẻ học", "soạn câu
  hỏi ôn tập" từ các file trong vault, hoặc chỉ định một chủ đề/điều
  luật cụ thể cần ôn (ví dụ: "làm flashcard về thừa kế", "tạo thẻ
  học điều 117-133"). Cũng dùng khi người dùng muốn export flashcard
  ra file .md để import vào Anki hoặc dùng plugin Obsidian Spaced
  Repetition.
---

# Skill: Làm Flashcard Luật Dân Sự 2015

## Mục tiêu

Tạo bộ flashcard chất lượng cao, đúng luật, tối ưu cho việc ghi nhớ lâu dài (spaced repetition). Mỗi thẻ phải kiểm tra được **một ý duy nhất**, rõ ràng, không mơ hồ.

---

## Bước 1 — Đọc file nguồn

Trước khi tạo flashcard, **bắt buộc đọc file liên quan** trong vault. Ưu tiên theo thứ tự:

| Ưu tiên | File | Chủ đề |
|---------|------|--------|
| ⭐⭐⭐ | `07 - Giao dich dan su - Dieu 117-133.md` | Giao dịch dân sự |
| ⭐⭐⭐ | `08 - Thua ke - Dieu 609-662.md` | Thừa kế |
| ⭐⭐⭐ | `09 - Quyen so huu - Dieu 158-273.md` | Quyền sở hữu |
| ⭐⭐ | `11 - Bieu thuong ngoai hop dong - Dieu 584-608.md` | Bồi thường ngoài HĐ |
| ⭐⭐ | `12 - Hop dong thong dung - Dieu 430-578.md` | Hợp đồng thông dụng |
| ⭐ | `10 - Nang luc hanh vi - Dieu 16-24.md` | Năng lực hành vi |
| ⭐ | `13 - Dai dien - Dieu 134-143.md` | Đại diện |
| ⭐ | `14 - Thoi han thoi hieu - Dieu 144-157.md` | Thời hạn, thời hiệu |
| ⭐ | `15 - Phap nhan - Dieu 74-96.md` | Pháp nhân |
| ⭐ | `16 - Quyen nhan than - Dieu 25-39.md` | Quyền nhân thân |

Luôn đọc thêm `24 - Canh bao sai so dieu.md` để tránh nhầm số điều.

---

## Bước 2 — Phân loại thẻ

Vault có nhiều loại nội dung → mỗi loại sinh ra kiểu thẻ khác nhau. Nhận diện loại nội dung rồi áp đúng template.

### Loại A — Định nghĩa / Khái niệm
> Khi gặp: định nghĩa, giải thích thuật ngữ, "là gì?"

```
Q: [Khái niệm] là gì? (Điều X BLDS 2015)
A: [Định nghĩa ngắn gọn, dùng ngôn ngữ của mình, không chép nguyên văn điều luật]
   → Cơ sở pháp lý: Điều X
```

**Ví dụ:**
```
Q: Giao dịch dân sự là gì? (Điều 116 BLDS 2015)
A: Hợp đồng hoặc hành vi pháp lý đơn phương làm phát sinh, thay đổi
   hoặc chấm dứt quyền, nghĩa vụ dân sự.
   → Cơ sở: Điều 116
```

---

### Loại B — Điều kiện / Yêu cầu
> Khi gặp: điều kiện có hiệu lực, điều kiện áp dụng, các yếu tố cấu thành

Mỗi điều kiện = **một thẻ riêng** (không gộp nhiều điều kiện vào một thẻ).

```
Q: Điều kiện [thứ N] để [X] có hiệu lực là gì? (Điều Y)
A: [Điều kiện cụ thể]
   → Cơ sở: Điều Y khoản Z
```

**Ví dụ:**
```
Q: Điều kiện về chủ thể để giao dịch dân sự có hiệu lực là gì? (Điều 117)
A: Chủ thể có năng lực pháp luật dân sự, năng lực hành vi dân sự
   phù hợp với giao dịch được xác lập.
   → Cơ sở: Điều 117 khoản 1 điểm a

Q: Điều kiện về ý chí để giao dịch dân sự có hiệu lực là gì? (Điều 117)
A: Chủ thể tham gia giao dịch hoàn toàn tự nguyện.
   → Cơ sở: Điều 117 khoản 1 điểm b
```

---

### Loại C — Con số / Thời hạn
> Khi gặp: số năm, số tháng, tỷ lệ phần trăm, tuổi, số lượng hàng thừa kế, v.v.

Con số trong luật rất quan trọng và dễ nhầm → tạo thẻ riêng cho mỗi con số.

```
Q: [Con số/thời hạn] của [quy định X] là bao nhiêu? (Điều Y)
A: [Số cụ thể + đơn vị]
   → Cơ sở: Điều Y
   ⚠️ [Ghi chú nếu có ngoại lệ hoặc dễ nhầm]
```

**Ví dụ:**
```
Q: Thời hiệu khởi kiện tranh chấp hợp đồng dân sự là bao lâu? (Điều 429)
A: 3 năm, kể từ ngày người có quyền yêu cầu biết hoặc phải biết
   quyền, lợi ích hợp pháp của mình bị xâm phạm.
   → Cơ sở: Điều 429
   ⚠️ Trừ trường hợp pháp luật có quy định khác

Q: Người từ đủ mấy tuổi có thể lập di chúc miệng? (Điều 630)
A: Không có quy định về di chúc miệng theo độ tuổi riêng — điều kiện là
   người lập di chúc ở tình trạng không thể lập di chúc bằng văn bản.
   → Cơ sở: Điều 629 khoản 1
```

---

### Loại D — So sánh / Phân biệt
> Khi gặp bảng so sánh trong `19 - Bang so sanh.md`, hoặc hai khái niệm có thể nhầm lẫn

```
Q: Phân biệt [X] và [Y]: điểm khác nhau về [tiêu chí Z]?
A: [X]: ...
   [Y]: ...
   → Xem thêm: Điều A (X), Điều B (Y)
```

**Ví dụ:**
```
Q: Phân biệt di chúc viết tay và di chúc có người làm chứng:
   yêu cầu về hình thức?
A: Di chúc viết tay: người lập tự tay viết và ký toàn bộ nội dung,
   không cần người làm chứng.
   Di chúc có người làm chứng: người lập đọc trước người làm chứng,
   cùng ký/điểm chỉ, cần ít nhất 2 người làm chứng.
   → Cơ sở: Điều 633 (viết tay), Điều 634 (có người làm chứng)
```

---

### Loại E — Hậu quả pháp lý
> Khi gặp: "bị vô hiệu", "không có hiệu lực", "phải bồi thường", "xử lý như thế nào"

```
Q: Hậu quả pháp lý khi [X xảy ra]? (Điều Y)
A: [Hậu quả 1]
   [Hậu quả 2 nếu có]
   → Cơ sở: Điều Y
```

**Ví dụ:**
```
Q: Hậu quả pháp lý của giao dịch dân sự vô hiệu toàn phần? (Điều 131)
A: 1. Không làm phát sinh, thay đổi, chấm dứt quyền và nghĩa vụ từ thời
      điểm giao dịch được xác lập.
   2. Các bên khôi phục lại tình trạng ban đầu, hoàn trả cho nhau những
      gì đã nhận.
   3. Bên ngay tình được bảo vệ trong một số trường hợp (Điều 133).
   → Cơ sở: Điều 131
```

---

### Loại F — Nhận định Đúng/Sai
> Nguồn: `21 - Cau hoi nhan dinh Dung-Sai.md` hoặc tự soạn từ các "bẫy" trong vault

```
Q: Nhận định sau đúng hay sai?
   "[Phát biểu cần kiểm tra]"
A: [ĐÚNG / SAI]
   Lý do: [Giải thích ngắn gọn]
   → Cơ sở: Điều Y
```

**Ví dụ:**
```
Q: Nhận định sau đúng hay sai?
   "Người từ đủ 6 tuổi đến chưa đủ 15 tuổi khi xác lập giao dịch dân sự
   phải có sự đồng ý của người đại diện theo pháp luật."
A: SAI.
   Lý do: Người từ đủ 6 tuổi đến chưa đủ 15 tuổi (không phải 18) phải có
   sự đồng ý — nhưng con số chính xác là chưa đủ 15 tuổi theo Điều 21 khoản 3.
   Tuy nhiên giao dịch phục vụ nhu cầu sinh hoạt hàng ngày phù hợp
   với lứa tuổi thì không cần.
   → Cơ sở: Điều 21 khoản 3
```

---

### Loại G — Tình huống (Cloze / Scenario)
> Nguồn: `20 - Bai tap tinh huong mau.md` hoặc tự soạn

```
Q: [Mô tả tình huống ngắn gọn, 2-4 câu]. Hỏi: [câu hỏi pháp lý]?
A: [Kết luận pháp lý]
   Phân tích: [1-3 bước lý luận ngắn]
   → Cơ sở: Điều A, Điều B
```

---

## Bước 3 — Quy tắc viết thẻ

### ✅ BẮT BUỘC

1. **Một thẻ, một ý** — Không nhồi nhiều kiến thức vào cùng một thẻ.
2. **Luôn có số điều** — Mỗi thẻ phải ghi rõ `(Điều X BLDS 2015)` ở câu hỏi hoặc phần cơ sở pháp lý ở câu trả lời.
3. **Câu hỏi chủ động** — Hỏi "là gì?", "bao nhiêu?", "khi nào?", "hậu quả gì?", "đúng/sai?" — không dùng "hãy trình bày..."
4. **Câu trả lời ngắn** — Tối đa 4-5 dòng. Nếu dài hơn → tách thành nhiều thẻ.
5. **Kiểm tra số điều với `24 - Canh bao sai so dieu.md`** trước khi viết thẻ bất kỳ có con số điều luật.

### ❌ TRÁNH

- Tránh chép nguyên văn điều luật dài vào câu trả lời — diễn giải bằng ngôn ngữ dễ hiểu.
- Tránh câu hỏi mơ hồ kiểu "Nêu các quy định về thừa kế?" (quá rộng).
- Tránh gộp danh sách dài vào một thẻ (3+ mục → tách thẻ hoặc dùng cloze).
- Tránh dùng "v.v.", "..." trong câu trả lời — phải đầy đủ hoặc ghi rõ "xem thêm Điều X".

### ⚠️ BẪY SỐ ĐIỀU HAY GẶP

Luôn kiểm tra các số điều sau vì dễ nhầm giữa BLDS 2005 và BLDS 2015:

| Chủ đề | Số điều BLDS 2015 | Ghi chú |
|--------|-------------------|---------|
| Quyền lợi người thứ 3 ngay tình | Điều 133 | ≠ Điều 133 BLDS 2005 |
| Thời hiệu khởi kiện chung | Điều 429 (HĐ), Điều 588 (BTTH) | Khác nhau theo loại |
| Thế vị trong thừa kế | Điều 652 | Chỉ áp dụng cho con, cháu |
| Di chúc miệng | Điều 629 | Điều kiện đặc biệt |
| Năng lực hành vi từng mức | Điều 21, 22, 23, 24 | Phân biệt theo độ tuổi |

---

## Bước 4 — Format output

### Định dạng mặc định (Obsidian Spaced Repetition plugin)

```markdown
#flashcard

Q: [câu hỏi]
?
[câu trả lời]
→ Cơ sở: Điều X BLDS 2015
```

Mỗi thẻ cách nhau một dòng trống. Ví dụ file hoàn chỉnh:

```markdown
---
tags: [flashcard, luat-dan-su, giao-dich-dan-su]
---

#flashcard

Q: Giao dịch dân sự là gì? (Điều 116)
?
Hợp đồng hoặc hành vi pháp lý đơn phương làm phát sinh, thay đổi
hoặc chấm dứt quyền, nghĩa vụ dân sự.
→ Cơ sở: Điều 116 BLDS 2015

Q: Có mấy điều kiện để giao dịch dân sự có hiệu lực? (Điều 117)
?
3 điều kiện:
1. Chủ thể có năng lực pháp luật, năng lực hành vi phù hợp.
2. Chủ thể tham gia hoàn toàn tự nguyện.
3. Mục đích và nội dung không vi phạm điều cấm, không trái đạo đức xã hội.
→ Cơ sở: Điều 117 khoản 1 BLDS 2015
```

### Nếu người dùng yêu cầu format Anki (TSV)

```
[Câu hỏi]	[Câu trả lời + số điều]
```

Dùng tab (`\t`) làm dấu phân cách, mỗi thẻ một dòng.

## Nếu người dùng yêu cầu format Quizlet
**Quizlet / .md format **
```
[Câu hỏi] /#*#/ [Câu trả lời + số điều]
\#
[Câu hỏi] /#*#/ [Câu trả lời + số điều]
\#
```

**Lưu ý:** File Quizlet chỉ chứa nội dung thẻ, KHÔNG thêm YAML metadata đầu file.

---

## Bước 5 — Đặt tên file output

Đặt tên theo quy tắc: `FC-[số thứ tự chủ đề]-[tên chủ đề]-Dieu[phạm vi].md`

Ví dụ:
- `FC-07-Giao-dich-dan-su-Dieu117-133.md`
- `FC-08-Thua-ke-Dieu609-662.md`
- `FC-ALL-Tong-hop-uu-tien.md` (nếu tổng hợp nhiều chủ đề)

Lưu vào thư mục `Flashcards/` trong vault.

---

## Bước 6 — Kiểm tra chất lượng trước khi xuất

Trước khi hoàn thành, tự kiểm tra theo checklist:

- [ ] Mỗi thẻ có đúng một ý duy nhất không?
- [ ] Tất cả số điều đã đối chiếu với `24 - Canh bao sai so dieu.md`?
- [ ] Câu hỏi có thể trả lời được mà không cần đọc lại tài liệu gốc không?
- [ ] Câu trả lời có đủ ngắn để đọc trong vòng 10 giây không?
- [ ] Các thẻ Loại C (con số) có ghi rõ ngoại lệ không?
- [ ] File có YAML metadata đầy đủ không?

---

## Quy trình khi người dùng yêu cầu

1. **Hỏi** (nếu chưa rõ): Chủ đề nào? Số lượng thẻ mong muốn? Format (Obsidian/Anki)?
2. **Đọc file nguồn** tương ứng trong vault.
3. **Phân tích nội dung**: Xác định các điểm quan trọng cần thẻ (ưu tiên theo mức ⭐).
4. **Tạo thẻ** theo đúng loại template (A→G).
5. **Kiểm tra checklist** Bước 6.
6. **Xuất file** theo format và tên đúng quy tắc.
7. **Báo cáo**: Nêu số lượng thẻ, phân bố theo loại, những điểm cần lưu ý khi học.
