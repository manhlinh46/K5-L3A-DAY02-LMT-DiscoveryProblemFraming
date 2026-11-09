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

|   # | Người đưa ra        | Candidate (Job Story ngắn)                                                                                                                                                                                      | Actor                                  | Bottleneck                                                                                                 | Câu hỏi phản biện nhận được                                                                                                                                                         |     |
| --: | ------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- |
|   1 | Lưu Thanh Mỹ        | Khi chuẩn bị buổi học AI mà chưa có nền tảng code, tôi muốn hiểu được khái niệm và setup tool trong 60 phút                                                                                                     | Sinh viên non-tech học AI              | Không có nguồn giải thích đúng trình độ — phải tự Google hoặc nhờ bạn                                      | Liệu phương pháp đưa ra tổng hợp cho những bạn non-tech đó có những sản phẩm có sẵn trên thị trường chưa                                                                            |     |
|   2 | Lưu Thanh Mỹ        | Khi kết thúc buổi học, tôi muốn tự kiểm tra xem mình hiểu đúng đến đâu từ tài liệu hôm đó                                                                                                                       | Sinh viên mọi lớp                      | Không có cơ chế tự kiểm tra, chỉ đọc lại thụ động                                                          | Sinh viên có chịu dùng thêm 1 tool nữa không?                                                                                                                                       |     |
|   3 | Lưu Thanh Mỹ        | Khi vào đầu buổi thực hành, tôi muốn biết ngay hôm nay làm gì, bấm vào đâu                                                                                                                                      | Sinh viên các lớp thực hành            | Mất 5–10 phút định hướng mỗi buổi                                                                          | Có phải do thiếu tool hay do chưa có thói quen đọc trước?                                                                                                                           |     |
|   4 | Nguyễn Trường Thành | Khi có một file giá mới, tôi muốn biết có mục cập nhật nào, để không phải so sánh từng mục giá với file excel tra cứu                                                                                           | Nhân viên dự toán                      | So sánh với file cũ -> mất 1 tiếng đọc từng bảng giá mới cho các vùng                                      | Có nhưng công cụ nào trên thị trường đang đọc được số từ PDF rồi không?                                                                                                             |     |
|   5 | Nguyễn Trường Thành | Khi đo bóc khối lượng từ bản vẽ, tôi muốn có chiều dài và loại tường được liệt kê ra, để không phải đi cóp nhặt từng dữ liệu từ bản vẽ                                                                          | Nhân viên dự toán                      | tìm và đo từng phần tường mất 10-15 phút mỗi phần                                                          | Để sử dụng AI giải quyết vấn đề này, cần những công nghệ và thông tin có sẵn nào?                                                                                                   |     |
|   6 | Nguyễn Trường Thành | Khi tôi tính cước vận chuyển, tôi muốn biết nhà cung cấp nào là hợp lý nhất, để tối ưu chi phí vận chuyển cho chủ đầu tư                                                                                        | Nhân viên dự toán                      | Việc so sánh còn mất nhiều thời gian, tổng hợp thông tin còn tốn hơn 1 tiếng                               | Thông tin đường xá, vị trí cụ thể đã có sẵn chưa? Khó phỏng vấn, đưa ra metric cụ thể?                                                                                              |     |
|   7 | Bùi Mạnh Linh       | Khi nhận được thông báo đơn hàng sắp được giao trong ngày, tôi muốn hẹn trước khoảng thời gian khung giờ shipper đến, để chủ động sắp xếp lịch trình cá nhân                                                    | Dân văn phòng, shipper có tần suất cao | Cuộc gọi bất ngờ làm gián đoạn luồng công việc; không có cơ chế chốt trước giờ rảnh từ đầu ngày            | Đã có tính năng chọn thời gian giao hàng                                                                                                                                            |     |
|   8 | Bùi Mạnh Linh       | Khi shipper giao tới nơi và yêu cầu thanh toán tiền mặt, tôi muốn mở nhanh app ngân hàng và quét mã QR chính xác số tiền lẻ mà không cần nhập tay hay tìm tiền mặt, để hoàn tất nhận hàng dưới 1 phút           | Người mua hàng COD, Shipper            | Lấy thông tin tài khoản và nhập tay số tiền lẻ, dễ nhập nhầm số hoặc chọn sai ngân hàng, mất khoảng 2 phút | vấn đề này đề xuất giải pháp, nhưng giải pháp đó có thực sử giải quyết được vấn đề gốc? Bottlenect nhập tay số tiền ck mất 2 phút có hợp lý?                                        |     |
|   9 | Bùi Mạnh Linh       | Khi nhận được gói hàng COD lạ không rõ nguồn gốc, tôi muốn đối chiếu ngay thông tin sản phẩm và lịch sử đặt hàng trên các ứng dụng mua sắm, để biết chính xác đây là đơn mình mua thật hay là chiêu trò lừa đảo | Người mua lo ngại lừa đảo, Shipper     | Tra cứu thủ công, lục lọi rải rác trên nhiều app khác nhau bằng trí nhớ mất rất nhiều thời gian            | Để tổng hợp được các thông tin ship hàng từ nhiều bên vận chuyển có khả thi không? Vấn đề này có thể được giải quyết bằng chính sách chống lừa đảo thay vì tổng hợp thông tin ship? |     |
|  10 | *(Thành viên 4)*    | *(Điền theo card)*                                                                                                                                                                                              |                                        |                                                                                                            |                                                                                                                                                                                     |     |
|  11 | *(Thành viên 4)*    | *(Điền theo card)*                                                                                                                                                                                              |                                        |                                                                                                            |                                                                                                                                                                                     |     |
|  12 | *(Thành viên 4)*    | *(Điền theo card)*                                                                                                                                                                                              |                                        |                                                                                                            |                                                                                                                                                                                     |     |

### 2.2. Cluster

| Cluster                                  | Các candidate                               | Pattern chung                                                                                       |
| ---------------------------------------- | ------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| A — Học tập thiếu hướng dẫn phù hợp      | #1, #2, #3 và các card tương tự từ bạn khác | Sinh viên không có nguồn/cơ chế học đúng trình độ, dẫn đến mất thời gian hoặc bỏ cuộc               |
| B — Workflow của việc tính toán còn chậm | #3, #4, #5                                  | một workflow bị chậm vì chưa có một kế hoạch áp dụng công nghệ, AI mới nên còn tốn nhiều thời gian. |
| C — Tiện ích trong việc ship hàng        | #6, #7, #8                                  | Những tiện ích cho người dùng đầu cuối khi sử dụng dịch vụ vận chuyển                               |
| D  —                                     |                                             |                                                                                                     |

### 2.3. Opportunity Solution Tree rút gọn

```text
OUTCOME: Sinh viên non-tech hoàn thành được khoá AI Engineer
  đúng tiến độ, hiểu đúng và làm được bài thực hành độc lập

├── Opportunity A: Thiếu nguồn giải thích khái niệm đúng trình độ
│     (pain: mất 30–90 phút/buổi tự tìm, vẫn mơ hồ)
│
├── Opportunity B: Thiếu cơ chế tự kiểm tra sau buổi học
│     (pain: không biết mình hiểu đúng hay sai cho đến khi thi)
│
└── Opportunity C: Thiếu hướng dẫn setup công cụ cơ bản
      (pain: bị nghẽn trước khi bắt đầu học, phụ thuộc bạn bè)
```

Những ý đã gạch bỏ vì là **solution đội lốt opportunity**:
- "Cần một chatbot giải bài" → là solution, không phải pain
- "Cần một nền tảng học AI" → là solution, không phải pain
- "Thiếu tài liệu tiếng Việt" → là solution trá hình, pain thật là "không hiểu tài liệu hiện có"

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| #1 — Sinh viên non-tech thiếu hướng dẫn đúng trình độ | 5 | 5 | 5 | 4 | 4 | 5 | 5 | **33** |
| #2 — Thiếu cơ chế tự kiểm tra sau buổi học | 4 | 4 | 3 | 4 | 4 | 4 | 4 | **27** |
| #3 — Mất thời gian định hướng đầu buổi | 4 | 4 | 3 | 3 | 5 | 3 | 4 | **26** |

**Candidate được chọn:** #1 — Sinh viên non-tech thiếu nguồn hướng dẫn đúng trình độ khi chuẩn bị buổi học AI

**Vì sao chọn:** Điểm cao nhất trên 7 tiêu chí. Actor rõ, quy trình vẽ được, có bằng chứng thật từ 3 phỏng vấn, impact đo được bằng thời gian, nhóm hiểu domain vì đang sống vấn đề này.

**Vì sao loại các candidate còn lại:**
- #2: Pain ít bằng chứng hơn, giải pháp đơn giản (giảng viên soạn câu hỏi) có thể thay thế hoàn toàn không cần AI
- #3: Impact thấp (5–10 phút/buổi), giải được bằng rule đơn giản (giảng viên gửi checklist), không đủ phức tạp để cần AI

**Xử lý bất đồng (nếu có):** Không có bất đồng lớn. Nhóm đồng thuận chọn #1 sau khi thảo luận về impact và khả năng kiểm chứng.

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
| **Quy trình** | Nhận tài liệu trước buổi học → Đọc lướt → Cố gắng hiểu các khái niệm nền → Setup công cụ thực hành (Colab/VS Code) → Sẵn sàng làm bài |
| **Bottleneck** | Nút thắt nằm ở bước hiểu khái niệm và setup công cụ: do không có nguồn tài liệu giải thích phù hợp với trình độ người mới, sinh viên phải tự tra cứu Google một cách phân mảnh hoặc chật vật nhờ vả bạn bè, ngốn mất 30–90 phút mỗi buổi chỉ để bắt đầu.|
| **Impact** | Sinh viên mang tâm lý tự ti, cảm thấy bị tụt lại so với các bạn có nền tảng IT trong lớp; việc học bị thụ động do phụ thuộc vào thời gian rảnh của người khác. Lâu dần dẫn đến mất động lực, chuyển sang học vẹt chống đối hoặc bỏ cuộc giữa chừng. |
| **Success Metric** | Baseline: 60–150 phút/buổi để hoàn tất khâu chuẩn bị.  Target: Giảm xuống dưới 30 phút/buổi. Cách đo: Sinh viên tự ghi nhận và báo cáo thời gian chuẩn bị sau 4 buổi học pilot có sử dụng hệ thống. |
| **Boundary** | AI chỉ làm nhiệm vụ biên dịch khái niệm và tạo checklist setup dựa trên nội dung tài liệu gốc của giảng viên. AI tuyệt đối không giải bài tập thay sinh viên, không tự quyết định lộ trình dài hạn khi chưa có chuyên gia duyệt. Bắt buộc có Human-in-the-loop (HITL): Sinh viên phải đọc, đối chiếu và tự xác nhận đã hiểu trước khi vào bài.|

Phản biện nhận được (từ AI đóng vai PM hoài nghi):
- *"Nếu chỉ hiểu đủ để bắt đầu mà không hiểu sâu, sinh viên có thực sự học được gì không?"* → Đồng ý một phần. Việc rút ngắn thời gian chuẩn bị có rủi ro làm giảm độ sâu của kiến thức. Nhóm sẽ cập nhật ở v1: cần thêm tiêu chí đánh giá chất lượng lĩnh hội (ví dụ: làm đúng bài test khái niệm nhỏ đầu giờ) chứ không chỉ chăm chăm giảm metric thời gian.
- *"Giải pháp buddy system (nhờ bạn) đang hoạt động — tại sao cần build thêm?"* → Không đồng ý. Giải pháp buddy system không có khả năng mở rộng (scale) và thiếu tính bền vững. Nó phụ thuộc hoàn toàn vào lòng nhiệt tình và thời gian rảnh của bạn cùng lớp. Người hỏi thường mang tâm lý ngại phiền hà, dẫn đến việc giấu dốt, trong khi người hướng dẫn cũng bị mất thời gian cá nhân. Công cụ AI giúp sinh viên lấy lại sự chủ động.

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô: **Độ mơ hồ cao × Độ phức tạp trung bình**

Vì sao: Mỗi sinh viên có trình độ, background và câu hỏi khác nhau → không có quy trình cố định. Nhưng các bước (đọc tài liệu → giải thích → hướng dẫn setup) là có thể xác định trước → không phức tạp đến mức cần Agent tự quyết.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** | Giảng viên soạn glossary + checklist setup cho từng buổi | Nếu tài liệu ít thay đổi, giảng viên có thời gian | Tốn công giảng viên mỗi buổi, không cá nhân hoá được | ❌ |
| **Rule** | If sinh viên hỏi khái niệm X → trả về định nghĩa cố định | Nếu số lượng khái niệm hữu hạn và không thay đổi | Không đủ linh hoạt, không giải thích theo context bài hôm đó | ❌ |
| **Workflow** | AI đọc tài liệu buổi học → tóm tắt điểm chính → giải thích khái niệm → hướng dẫn setup → sinh viên xác nhận | Phù hợp — bước AI rõ ràng, con người vẫn kiểm tra | AI giải thích sai, sinh viên tin mù | ✅ **Chọn** |
| **Agent** | AI tự quyết lộ trình học dài hạn, tự chọn tài liệu, tự đánh giá tiến độ | Khi cần cá nhân hoá toàn diện nhiều buổi liên tục | Quá phức tạp, thiếu dữ liệu, cần chuyên gia duyệt — rủi ro cao | ❌ |

**Mức chọn:** **Workflow**

**Vì sao không chọn mức đơn giản hơn:**
- No AI: không scale, tốn công giảng viên mỗi buổi, không cá nhân hoá theo trình độ từng sinh viên
- Rule: quá cứng, không hiểu context tài liệu buổi hôm đó, không giải thích theo câu hỏi cụ thể

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | Giải thích khái niệm trong tài liệu theo trình độ sinh viên; hướng dẫn setup công cụ từng bước; tóm tắt 5 điểm cần biết buổi hôm nay |
| **Judgment** — con người cân nhắc, quyết định gì? | Sinh viên tự xác nhận đã hiểu hay chưa trước khi vào bài; giảng viên duyệt tóm tắt nếu cần |
| **Action** — hành động cuối cùng là gì, ai làm? | Sinh viên bắt đầu buổi học / mở tool và làm bài thực hành |
| **Outcome** — đo kết quả bằng gì? | Thời gian chuẩn bị giảm từ 60–150 phút xuống dưới 30 phút; sinh viên tự báo cáo sau 4 buổi |
| **Input** — AI cần gì mỗi lần chạy? | Tài liệu / slide buổi học (PDF, Markdown); trình độ sinh viên (lần đầu tự khai) |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | Sinh viên đánh giá giải thích đúng/sai ngay sau khi đọc; giảng viên ghi nhận câu hỏi lặp lại nhiều |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)**. Bằng chứng: *"Rất muốn có người hướng dẫn"* — không phải giao hẳn việc, vẫn muốn tự hiểu và tự làm bài; buddy system hiện tại là augment bằng người, không phải automate.
- AI sai kiểu **bỏ sót** (không giải thích đủ, thiếu bước setup) **tệ hơn báo nhầm**. Vì sao: nếu AI giải thích thiếu, sinh viên vào buổi học vẫn bị nghẽn y như cũ. Nếu AI giải thích sai một điểm nhỏ, sinh viên có thể phát hiện khi thực hành. Thiết kế xử lý: thêm bước sinh viên tự xác nhận hiểu và phương án quay về hỏi bạn/giảng viên.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Sinh viên non-tech đang học khoá AI Engineer (K5), chưa có nền tảng lập trình |
| **Quy trình** | Chuẩn bị trước mỗi buổi học: đọc tài liệu → hiểu khái niệm nền → setup công cụ → sẵn sàng làm bài |
| **Bottleneck** | Không có nguồn giải thích đúng trình độ — phải tự Google hoặc nhờ bạn, mất 30–90 phút mỗi buổi, phụ thuộc bạn có rảnh không |
| **Impact** | Sinh viên tụt lại, học vẹt hoặc bỏ cuộc; chênh lệch ngày càng lớn so với bạn có nền tảng |
| **Success Metric** | Baseline: 60–150 phút/buổi. Target: dưới 30 phút. Đo bằng: sinh viên tự báo cáo thời gian chuẩn bị sau 4 buổi; tỉ lệ bắt đầu làm bài đúng giờ tăng |
| **Boundary** | AI chỉ giải thích khái niệm và hướng dẫn setup dựa trên tài liệu buổi học. AI **không** làm bài thay, không tự quyết lộ trình dài hạn không có chuyên gia duyệt |
| **AI intervention point** | Bước 3 trong quy trình: sau khi sinh viên đọc lần đầu và liệt kê điểm chưa hiểu → AI giải thích và hướng dẫn setup |
| **Mức chọn** | **Workflow** |
| **Rủi ro & người kiểm tra** | Rủi ro: AI giải thích sai hoặc thiếu. Người kiểm tra: sinh viên tự xác nhận hiểu (HITL) trước khi vào bài; giảng viên theo dõi câu hỏi lặp lại |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Bottleneck | "Mất 3–4h vì phải tự tìm kiếm" | "Không có nguồn đúng trình độ — bao gồm cả khái niệm lẫn setup công cụ" | Phỏng vấn cho thấy bottleneck thật là setup tool và thiếu người hướng dẫn, không chỉ là lý thuyết |
| AI intervention point | Chưa có | Bước 3 cụ thể sau khi sinh viên liệt kê điểm chưa hiểu | Thêm sau khi vẽ quy trình tương lai rõ hơn |
| Mức chọn | Chưa có | Workflow | Thêm sau CP6 |

**Tiêu chí đánh giá đầu ra của AI (5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Giải thích đúng khái niệm | Sinh viên đọc xong hiểu được định nghĩa và ví dụ liên quan bài hôm đó | Sinh viên vẫn không hiểu hoặc giải thích mâu thuẫn với tài liệu gốc |
| 2 | Độ phù hợp trình độ | Dùng ngôn ngữ không có jargon kỹ thuật cao hơn tài liệu buổi học | Dùng thuật ngữ phức tạp hơn, sinh viên phải Google thêm để hiểu phần giải thích |
| 3 | Hướng dẫn setup đủ bước | Sinh viên làm theo được từng bước và tool chạy được | Thiếu bước, sinh viên bị lỗi mà không có hướng dẫn xử lý |
| 4 | Tóm tắt đúng trọng tâm | 5 điểm tóm tắt bao phủ nội dung chính của tài liệu, không bỏ sót phần thực hành | Tóm tắt quá chung chung hoặc bỏ sót bước thực hành quan trọng |
| 5 | Không làm bài thay | Chỉ giải thích khái niệm và setup, không viết code hoàn chỉnh cho bài tập | Cung cấp đáp án bài tập, sinh viên copy mà không hiểu |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | **Thấp** (an toàn) | 3/3 người phỏng vấn xác nhận pain có thật; 1 người nói rõ "rất muốn có người hướng dẫn" — đây là cam kết hành vi |
| **Usability** | Người dùng có dùng được, hiểu và sửa được đầu ra của AI không? | **Trung bình** | Sinh viên non-tech có thể khó nhận ra khi AI giải thích thiếu; cần thiết kế bước xác nhận hiểu (HITL) rõ ràng |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | **Trung bình** | Tài liệu buổi học có sẵn (PDF, Markdown, repo). Công cụ: NotebookLM hoặc API LLM đã có. Thách thức: cá nhân hoá theo trình độ cần dữ liệu ban đầu từ sinh viên |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? | **Thấp** (an toàn) | Chi phí API ở mức pilot rất nhỏ. Không có vấn đề pháp lý (tài liệu là của trường/khoá). Cần trường hoặc khoá chấp thuận tích hợp |

### 8.2. Kết luận

**Quyết định:** **Not Yet**

**Lý do:** Pain có thật và được kiểm chứng. Nhưng còn 2 giả định chưa được kiểm chứng đủ: (1) sinh viên có chịu dùng thêm 1 tool mới không, (2) AI giải thích đúng trình độ có thực sự giúp họ bắt đầu làm bài được không — hay vẫn cần người hướng dẫn thực hành trực tiếp.

**Nếu Not Yet — cần kiểm chứng gì trước:**
1. Thử nghiệm nhỏ: dùng NotebookLM với tài liệu 1 buổi thật, cho 3–5 sinh viên non-tech thử chuẩn bị, đo thời gian và hỏi họ có cần hỗ trợ thêm không
2. Kiểm chứng giả định "cá nhân hoá theo trình độ": hỏi sinh viên về trình độ xuất phát và xem AI có giải thích khác nhau đủ để có ích không

**Ngưỡng dừng:** Nếu sau 2 buổi thử nghiệm mà hơn 50% sinh viên vẫn cần hỏi thêm bạn/giảng viên sau khi dùng công cụ → quay về giải pháp No AI (giảng viên soạn checklist + glossary có cấu trúc).

---

## 9. Hạn chế và hướng tiếp theo

- Chỉ phỏng vấn 3 người — cần mở rộng survey để có số liệu đại diện hơn
- Chưa kiểm chứng được giả định "AI giải thích đúng trình độ" trong thực tế
- Scope hiện tại chỉ giải quyết bước chuẩn bị, chưa giải quyết bước thực hành trong buổi học
- Hướng tiếp theo: thử pilot với NotebookLM + 1 buổi lab thật, đo thời gian và chất lượng hiểu

## 10. Tài liệu tham khảo

- NotebookLM — Google: https://notebooklm.google.com
- Khanmigo — Khan Academy AI tutor: https://www.khanacademy.org/khan-labs
- GitHub Copilot Chat: https://github.com/features/copilot
- The Mom Test — Rob Fitzpatrick (phương pháp phỏng vấn)
- Google PAIR Guidebook: https://pair.withgoogle.com/guidebook
