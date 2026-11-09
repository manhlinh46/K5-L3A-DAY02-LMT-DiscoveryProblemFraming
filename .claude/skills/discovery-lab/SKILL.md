---
name: discovery-lab
description: >
  Hướng dẫn cá nhân hoá cho bài lab Discovery & Problem Framing (VinUni AI Engineering K5).
  Dùng khi sinh viên cần làm CP1, CP2, CP7, chuẩn bị pitch cho nhóm, viết Problem Card,
  Job Story, reflection, hoặc hỏi "tôi cần làm gì tiếp theo", "nhóm làm gì", "cách đẩy lên git".
  Luôn kích hoạt khi người dùng nhắc đến: CP1, CP2, CP3, CP4, CP5, CP6, CP7,
  Problem Card, Job Story, Problem Statement, Double Diamond, Discovery lab,
  bài lab VinUni, nhóm lab, phần cá nhân, reflection, pitch vấn đề.
---

# Discovery & Problem Framing — Skill hướng dẫn cá nhân hoá

Bài lab này đi theo mô hình Double Diamond:
- **Cá nhân (CP1, CP2, CP7):** scan vấn đề → chọn top 3 → reflection
- **Nhóm (CP3–CP6):** hội tụ → kiểm chứng → quy trình → Problem Statement → quyết định

---

## Khi sinh viên hỏi "tôi cần làm gì"

Hỏi ngay:
1. Họ đang ở checkpoint nào?
2. Họ đã có file `MSSV_HoTen.md` chưa?
3. Nhóm đã chốt vấn đề chưa?

Từ đó dẫn đúng bước tiếp theo, không giải thích thừa.

---

## CP1 — Scan 5+ vấn đề

Giúp sinh viên viết Job Story từ trải nghiệm thật:

> *Khi [tình huống], tôi muốn [động cơ], để [kết quả]*

**Luật cứng:**
- Không được có chữ "AI", "chatbot", "agent" trong cột Job Story
- Mỗi dòng phải có ít nhất 1 con số đo được (phút, lần/tuần, số người)
- Phải từ trải nghiệm thật, không bịa

**Cách giúp sinh viên scan:**
Hỏi họ 4 câu này:
- "Việc gì bạn hay lặp lại nhất mỗi tuần?"
- "Việc gì tốn thời gian nhất mà cảm thấy không xứng?"
- "Việc gì cần đọc, tổng hợp nhiều thứ trước khi làm được?"
- "Bạn thấy bạn bè hoặc đồng nghiệp hay than về vấn đề gì?"

**Bonus B1 (+3đ):** Viết từ 10 vấn đề trở lên, trải đủ 4 lăng kính.

---

## CP2 — Top 3 Problem Cards

Mỗi card cần đủ 9 trường:

| Trường | Lưu ý |
|---|---|
| Job Story | Dạng Khi…muốn…để… |
| Actor | Người cụ thể, không phải "mọi người" |
| Bottleneck | Một bước cụ thể, không phải "quy trình chậm" |
| Impact | Nếu không giải thì hậu quả gì đo được |
| Success metric | Phải có baseline → target → cách đo |
| Phương án không dùng AI | Bắt buộc |

**Quy trình nháp:** 3–7 bước, có số phút từng bước, đánh dấu bottleneck bằng `← BOTTLENECK`.

**Sau khi viết xong:** Cho AI đóng vai "PM hoài nghi" phản biện, ghi lại điểm đã sửa. Bắt buộc để đạt điểm tối đa C2.

---

## CP3 — Pitch & Hội tụ nhóm

Mỗi người pitch 3 card, 1–2 phút mỗi card. Người nghe ghi câu hỏi phản biện.

**Cấu trúc pitch 90 giây:**
1. Ai gặp vấn đề này?
2. Pain thật là gì, số đo bao nhiêu?
3. Bước nào bị nghẽn?
4. Muốn cải thiện đến đâu?

**Nhóm chốt 1 candidate bằng bảng chấm điểm 7 tiêu chí**, không bỏ phiếu ngay.

---

## CP4 — Kiểm chứng

**3 luật The Mom Test:**
1. Hỏi về cuộc sống của họ, không hỏi về ý tưởng
2. Hỏi hành vi đã xảy ra, không hỏi giả định
3. Nói ít hơn người được hỏi

**Câu hỏi đúng:** "Lần gần nhất bạn gặp vấn đề X, chuyện gì xảy ra?"
**Câu hỏi sai:** "Bạn có muốn dùng tool này không?"

**Bonus B2 (+4đ):** 5+ interview hoặc 20+ survey, và kết quả làm nhóm sửa vấn đề/metric.

---

## CP5 — Quy trình + Problem Statement v0

**Success metric phải có:**
- Baseline (hiện tại là bao nhiêu)
- Target (muốn đạt bao nhiêu)
- Cách đo (đo bằng gì, ai đo, khi nào đo)

**Boundary phải ghi rõ:**
- AI KHÔNG được làm gì
- Khi nào cần con người kiểm tra (HITL)

---

## CP6 — Mức can thiệp AI

Thứ tự so sánh từ đơn giản đến phức tạp:

| Mức | Khi nào chọn |
|---|---|
| No AI | Giải được bằng quy trình/checklist |
| Rule | Điều kiện if-then cố định |
| Workflow | Nhiều bước, AI làm 1 phần, con người kiểm tra |
| Agent | AI tự quyết bước tiếp theo — rất hiếm cần |

**Chọn mức đơn giản nhất đủ dùng.** Phải giải thích rõ vì sao không chọn mức đơn giản hơn.

**Bonus B3 (+3đ):** Viết 10 cặp input/output mẫu cho bước AI, chấm theo tiêu chí đánh giá.

---

## CP7 — Reflection

**Bắt buộc tự viết, không dùng AI.**

Checklist trước khi nộp:
- [ ] Mục 6.1–6.6 tối thiểu 200 từ
- [ ] Có ít nhất 1 lần đổi ý sau khi bị phản biện (cụ thể)
- [ ] Có ít nhất 1 chỗ AI sai và bạn đã sửa gì
- [ ] Mục 6.7 giải thích được chuỗi không nhìn tài liệu

---

## Git workflow cá nhân

```bash
# Tạo branch riêng
git checkout -b TenMình

# Sau khi điền xong file
git add report/individual/MSSV_HoTen.md
git commit -m "Add individual report MSSV"
git push -u origin TenMình
```

Báo nhóm trưởng merge vào `main` trước deadline.

---

## Checklist điểm cộng

| Bonus | Điểm | Làm gì |
|---|---|---|
| B1 | +3 | 10+ vấn đề, đủ 4 lăng kính, có số đo |
| B2 | +4 | 5+ phỏng vấn hoặc 20+ survey, nhóm sửa bài vì kết quả |
| B3 | +3 | 10 cặp input/output mẫu cho bước AI |

---

## Lỗi phổ biến cần tránh

- Solution trá hình: "cần chatbot X" trong cột Job Story → trừ điểm
- Metric không đo được: "nhanh hơn, tiện hơn" → trừ 5 điểm
- Reflection do AI viết → C4 = 0
- Bịa kết quả phỏng vấn → C7 = 0 cả nhóm
- Giữ nguyên tên file `MSSV_HoTen.md` chưa đổi → trừ 5 điểm
