# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: LMT
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Sinh viên non-tech không có nguồn hướng dẫn đúng trình độ để chuẩn bị cho buổi học AI Engineer, dẫn đến mất 30 phút đến 3 tiếng mỗi buổi mà vẫn bị nghẽn ở bước dùng công cụ cơ bản.
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |
| 7 | | | | | |
| 8 | | | | | |
| 9 | | | | | |
| 10 | | | | | |
| 11 | | | | | |
| 12 | | | | | |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A | | |
| B | | |
| C | | |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: 
├── Opportunity A: 
├── Opportunity B: 
└── Opportunity C: 
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

-

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| | | | | | | | | |
| | | | | | | | | |
| | | | | | | | | |

**Candidate được chọn:**

**Vì sao chọn:**

**Vì sao loại các candidate còn lại:**

**Xử lý bất đồng (nếu có):**

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Sinh viên non-tech thực sự mất nhiều thời gian hơn bạn có nền tảng | Value | 5 | 2 | ✅ Ưu tiên 1 |
| 2 | Bottleneck chính là hiểu lý thuyết, không phải dùng công cụ | Usability | 5 | 1 | ✅ Ưu tiên 1 |
| 3 | Sinh viên sẵn sàng dùng thêm một công cụ mới để học | Usability | 4 | 1 | ✅ Ưu tiên 2 |
| 4 | Có thể cá nhân hoá lộ trình mà không cần chuyên gia duyệt từng bước | Feasibility | 5 | 1 | ✅ Ưu tiên 2 |
| 5 | Giải thích khái niệm đúng level giúp sinh viên làm được bài | Value | 4 | 2 | Ưu tiên 3 |
| 6 | Trường/khoá có đủ tài liệu số để hệ thống đọc và tóm tắt | Feasibility | 3 | 3 | Ưu tiên 3 |

Giả định nhóm kiểm chứng trong buổi này: **Giả định 1 và 2** (quan trọng nhất, ít bằng chứng nhất)

### 3.2. Kiểm chứng

Cách đã dùng: **Phỏng vấn nhanh qua nhắn tin nhóm — 3 người, ngày 09/11/2026**

Interview snapshot chi tiết: xem
- [cp4-interview-snapshot-1.md](../assets/cp4-interview-snapshot-1.md) — Sinh viên non-tech, 30–45 phút/buổi
- [cp4-interview-snapshot-2.md](../assets/cp4-interview-snapshot-2.md) — Sinh viên non-tech, bị nghẽn ở công cụ
- [cp4-interview-snapshot-3.md](../assets/cp4-interview-snapshot-3.md) — Người có kinh nghiệm, 2–3 tiếng/buổi setup

Tổng hợp:

| Nguồn | Số người | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Phỏng vấn nhắn tin | 3 | Pain có thật; thời gian từ 10 phút đến 3 tiếng; đều muốn có hướng dẫn phù hợp trình độ | Khó triển khai, cần chuyên gia giáo dục; không thể auto hoàn toàn |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

Giả định ban đầu sai một phần: Bottleneck **không phải** chỉ là hiểu lý thuyết — mà còn là **không biết dùng công cụ cơ bản** (Colab, VS Code) và **không có người hướng dẫn đúng lúc**. Nhóm cập nhật lại:

- **Trước kiểm chứng:** "Sinh viên mất 3–4h vì phải tự tìm kiếm kiến thức nền"
- **Sau kiểm chứng:** "Sinh viên bị nghẽn vì không có nguồn hướng dẫn đúng trình độ — bao gồm cả lý thuyết lẫn setup công cụ — và phải phụ thuộc vào bạn bè có sẵn hay không"

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào? | Điểm mạnh | Khoảng trống | Bài học cho nhóm |
|---|---|---|---|---|---|
| NotebookLM (Google) | https://notebooklm.google.com | Tóm tắt tài liệu, trả lời câu hỏi từ file upload | Hiểu đúng nội dung tài liệu gốc, trích dẫn chính xác | Không hướng dẫn setup công cụ, không cá nhân hoá theo trình độ | AI đọc tài liệu được — nhưng không dạy được cách thực hành |
| Khanmigo (Khan Academy AI) | https://www.khanacademy.org/khan-labs | Giải thích khái niệm, dẫn dắt từng bước | Cá nhân hoá, hỏi đáp theo Socratic method | Không có nội dung AI Engineering, không dùng tài liệu của trường | Hướng đúng — nhưng cần áp dụng cho domain AI Engineering cụ thể |
| GitHub Copilot Chat | https://github.com/features/copilot | Hỏi về code, giải thích lỗi, hướng dẫn setup | Trả lời đúng context code, hỗ trợ setup VS Code/Colab | Cần biết hỏi gì, không tự dẫn dắt lộ trình; cần có file code trước | Giải được bước công cụ nhưng không giải được bước "tôi cần học gì hôm nay" |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

```text
Nhận thông báo buổi học / link tài liệu
           ↓
Mở tài liệu — đọc lần đầu (10–30 phút)
           ↓
Gặp thuật ngữ / tool chưa biết  ← BOTTLENECK CHÍNH
           ↓
Tự Google / hỏi AI / xem YouTube (~30–90 phút)
           ↓
Vẫn chưa rõ → nhờ bạn hỗ trợ trực tiếp (~30 phút, nếu có bạn)
           ↓
Mở tool (Colab / VS Code) — không biết setup → hỏi bạn thêm
           ↓
Bắt đầu buổi học — vẫn còn mơ hồ hoặc trễ tiến độ
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Sinh viên | Thông báo buổi học | Mở tài liệu | 5 phút | Mỗi buổi |
| 2 | Sinh viên | Slide / repo | Danh sách điểm chưa hiểu | 10–30 phút | Mỗi buổi |
| 3 | Sinh viên | Thuật ngữ lạ | Giải thích | 30–90 phút | **BOTTLENECK** — không có nguồn đúng level |
| 4 | Sinh viên + bạn | Câu hỏi cụ thể | Hướng dẫn setup | 30 phút | Phụ thuộc bạn có rảnh không |
| 5 | Sinh viên | Tool đã setup | Bắt đầu làm bài | 10 phút | Thường bị trễ so với bạn có nền tảng |

**Bottleneck chính:** Bước 3 — không có nguồn giải thích đúng trình độ cho từng người, dẫn đến mất 30–90 phút tìm kiếm không hiệu quả và/hoặc phụ thuộc bạn bè.

### 4.2. Quy trình tương lai

```text
Nhận thông báo buổi học
           ↓
[AI - Workflow] Đọc tài liệu → tóm tắt 5 điểm cần biết hôm nay,
  giải thích thuật ngữ theo trình độ người dùng,
  hướng dẫn setup tool từng bước
           ↓
Sinh viên đọc tóm tắt + hỏi câu hỏi cụ thể (~15–20 phút)
           ↓
[Con người kiểm tra] Sinh viên tự xác nhận đã hiểu trước khi vào bài
           ↓
Bắt đầu buổi học — đúng giờ, đủ nền tảng
           ↓
[Phương án quay về] Nếu AI giải thích sai hoặc không đủ → sinh viên
  hỏi thêm bạn/giảng viên như bình thường
```

**Boundary:** AI chỉ giải thích và tóm tắt — không làm bài thay sinh viên, không tự quyết định lộ trình dài hạn mà không có chuyên gia duyệt.

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---|---|---|
| Số bước | 5 bước | 4 bước | Gộp bước tìm kiếm vào AI |
| Tổng thời gian | 60–150 phút | 20–30 phút | Mục tiêu giảm 70% |
| Số bước thủ công | 5 | 2 | Bước 3–4 được AI hỗ trợ |
| Bottleneck chính | Tìm kiếm không đúng level | Sinh viên tự xác nhận hiểu | Con người vẫn kiểm tra |
| Rủi ro mới phát sinh | — | AI giải thích sai; sinh viên tin mù | Cần HITL ở bước xác nhận |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Sinh viên non-tech đang học khoá AI Engineer (K5), chưa có nền tảng lập trình |
| **Quy trình** | Chuẩn bị trước mỗi buổi học: đọc tài liệu → hiểu khái niệm nền → setup công cụ → sẵn sàng làm bài |
| **Bottleneck** | Bước hiểu khái niệm + setup công cụ: không có nguồn giải thích đúng trình độ, phải tự Google hoặc nhờ bạn, mất 30–90 phút mỗi buổi |
| **Impact** | Sinh viên bị tụt lại so với bạn có nền tảng; phụ thuộc vào việc bạn có rảnh không; dần mất động lực, học vẹt hoặc bỏ cuộc |
| **Success Metric** | Baseline: 60–150 phút/buổi để sẵn sàng. Target: dưới 30 phút. Đo bằng: sinh viên tự báo cáo thời gian chuẩn bị sau 4 buổi dùng hệ thống |
| **Boundary** | AI chỉ giải thích khái niệm và hướng dẫn setup dựa trên tài liệu có sẵn. AI **không** làm bài thay, không tự quyết lộ trình dài hạn không có chuyên gia duyệt. Sinh viên phải tự xác nhận hiểu trước khi vào bài (HITL). |

Phản biện nhận được (từ AI đóng vai PM hoài nghi):
- *"Nếu chỉ hiểu đủ để bắt đầu mà không hiểu sâu, sinh viên có thực sự học được gì không?"* → Nhóm đồng ý một phần — cần thêm tiêu chí đánh giá "hiểu" không chỉ là "có thể bắt đầu"
- *"Giải pháp buddy system (nhờ bạn) đang hoạt động — tại sao cần build thêm?"* → Nhóm không đồng ý: buddy system phụ thuộc vào bạn có rảnh, không scale được

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | | | | |
| **Rule** | | | | |
| **Workflow** | | | | |
| **Agent** | | | | |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | |
| **Judgment** — con người cân nhắc, quyết định gì? | |
| **Action** — hành động cuối cùng là gì, ai làm? | |
| **Outcome** — đo kết quả bằng gì? | |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** | |
| **AI intervention point** | |
| **Mức chọn** | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra** | |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| | | | |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | | |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | | |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | | |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | | |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go

**Lý do:**

**Nếu Go — pilot nhỏ nhất:**

**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-
