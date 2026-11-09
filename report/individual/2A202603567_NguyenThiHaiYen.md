# Báo cáo cá nhân — MSSV_HoTen



## 1. Thông tin học viên

- Họ tên: Nguyễn Thị Hải Yến
- MSSV: 2A202603567
- Email trường (không bắt buộc, repo có thể để public): 
- Tên nhóm: LMT
- Link repo nhóm: https://github.com/manhlinh46/K5-L3A-DAY02-LMT-DiscoveryProblemFraming.git

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

|  # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại · Tốn thời gian | Khi đến ngày đóng sổ, tôi muốn nhận đủ dữ liệu từ kho, mua hàng, bán hàng đúng hạn, để không phải đi nhắc từng bộ phận. | Finance Controller, kế toán tổng hợp, các bộ phận cung cấp dữ liệu | ~3,5 giờ/tháng chỉ để nhắc và đòi dữ liệu, 1 lần/tháng, 4–5 bộ phận; đóng sổ hay trễ 1–2 ngày (ước tính) |
| 2 | Cần đọc, tổng hợp nhiều thông tin | Khi tổng hợp báo cáo tháng từ ERP và nhiều file Excel, tôi muốn số liệu tự động cập nhật, để không phải copy-paste và nối file thủ công. | Finance Controller, kế toán tổng hợp | ~4 giờ/tháng, 5–6 file Excel mỗi kỳ, từng có lần nối sai phiên bản (ước tính) |
| 3 | Tốn thời gian | Khi số liệu giữa kho, công nợ và sổ cái không khớp, tôi muốn tìm nhanh nguyên nhân chênh lệch, để đóng sổ đúng hạn. | Kế toán kho, kế toán công nợ, Finance Controller | 2–3 giờ/tháng để tìm một khoản lệch, mỗi tháng thường có 1–2 khoản lệch (ước tính) |
| 4 | Tốn thời gian · Cần đọc, tổng hợp nhiều thông tin | Khi cần theo dõi doanh thu giữa tháng, tôi muốn xem doanh thu thực tế so với kế hoạch ngay, để kịp cảnh báo nếu lệch target thay vì chờ Sales gửi số. | Finance Controller, Sales, Ban Giám đốc | ~3 giờ/lần, 2–4 lần/tháng; số liệu về trễ 2–3 ngày (ước tính) |
| 5 | Lặp lại | Khi nhận hóa đơn nhà cung cấp, tôi muốn đối chiếu tự động với PO và phiếu nhập kho, để không phải kiểm từng tờ bằng mắt và tránh thanh toán sai hoặc trùng. | Kế toán công nợ phải trả, Mua hàng | 5–10 phút/hóa đơn, 100+ hóa đơn/tháng (ước tính) |
| 6 | Pain từ người khác | Khi gửi báo cáo tháng cho BGĐ, tôi muốn có sẵn phần giải thích biến động so với tháng trước và kế hoạch, để không phải viết lại từ đầu và không bị hỏi lại cùng một câu. | Finance Controller, Ban Giám đốc | ~1 giờ viết nhận xét mỗi tháng; BGĐ hỏi lại 2–3 câu cùng loại mỗi kỳ (ước tính) |
| 7 | Lặp lại · Pain từ người khác | Khi các bộ phận hỏi số liệu ad-hoc, tôi muốn họ tự xem được dashboard, để tôi không bị ngắt quãng công việc chính liên tục. | Finance Controller, các bộ phận hỏi số liệu (Sales, Mua hàng, Sản xuất, BGĐ) | ~8 yêu cầu/tuần, ~40 phút/yêu cầu (gồm thời gian lấy lại tập trung), ~5 giờ/tuần (ước tính) |
| 8 | Lặp lại | Khi các bộ phận nộp ngân sách, tôi muốn nhận đúng mẫu và đúng hạn trên một nơi duy nhất, để không phải gom từng file và chỉnh sửa nhiều vòng. | Finance Controller, Trưởng các bộ phận | 5–8 bộ phận, 2–3 vòng sửa mỗi bộ phận, ~10 giờ/kỳ lập ngân sách (ước tính) |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- Dùng AI gợi ý danh sách vấn đề theo mẫu Job Story cho các công việc tốn thời gian của Finance Controller (báo cáo tháng, theo dõi doanh thu, báo cáo tài chính, ngân sách, kiểm tra hóa đơn).

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Thu thập dữ liệu đóng sổ cuối tháng (#1) | [lặp lại mỗi tháng, mất nhiều giờ, ảnh hưởng đến thời hạn đóng sổ] |  chưa đo số giờ thực tế; không chắc nguyên nhân chính là do quy trình hay do thói quen của các bộ phận |
| 2 | Theo dõi doanh thu giữa tháng (#4) | [ quy trình rõ, số giờ lớn, ảnh hưởng đến việc cảnh báo kịp thời] | số của Sales và Kế toán khác định nghĩa; chưa rõ AI có cần thiết hay chỉ cần dashboard|
| 3 | Yêu cầu số liệu ad-hoc từ các bộ phận (#7) |  xảy ra hàng tuần, làm gián đoạn công việc chính, nhiều người liên quan | khó đo chính xác thời gian bị ngắt quãng; người hỏi có chịu tự xem dashboard không] |


### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi đến ngày đóng sổ, tôi muốn nhận đủ dữ liệu từ kho, mua hàng, bán hàng đúng hạn, để không phải đi nhắc từng bộ phận. |
| Actor | Finance Controller (người nhắc và tổng hợp); Kế toán tổng hợp; các bộ phận cung cấp dữ liệu: Kho, Mua hàng, Sales admin |
| Thời điểm / bối cảnh | Những ngày đầu tháng (ngày làm việc 1–3), khi cần đóng sổ tháng trước và hoàn thành báo cáo tháng |
| Quy trình hiện tại (3–7 bước) | Gửi nhắc các bộ phận nộp dữ liệu -> theo dõi ai đã nộp và nhắc lại bộ phận trễ -> nhận và kiểm tra dữ liệu -> xin bổ sung hoặc sửa file sai -> tổng hợp vào file đóng sổ |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước theo dõi và nhắc lại (~60 phút) và bước xin bổ sung, sửa file sai (~60 phút), vì phải chờ qua lại nhiều lần. Tổng cả quy trình ~210 phút/tháng (ước tính) |
| Impact (nếu không giải thì sao) | Đóng sổ trễ 1–2 ngày mỗi tháng, báo cáo đến BGĐ muộn; Finance Controller tốn thời gian nhắc việc thay vì phân tích; dễ sót dữ liệu dẫn đến điều chỉnh bút toán sau khi đóng sổ |
| Success metric (baseline → target) | Thời gian nhắc và đòi dữ liệu: ~3,5 giờ -> dưới 1 giờ/tháng; tỷ lệ bộ phận nộp đúng hạn: ~50% -> trên 90% (ước tính) |
| Phương án không dùng AI | Lập checklist đóng sổ có người phụ trách và deadline cố định; dùng biểu mẫu chuẩn (Google Form/Sheet chung); đặt lịch nhắc tự động |
| Giả thuyết về AI (nếu có) | Công cụ theo dõi bộ phận nào đã nộp và gửi nhắc đúng người, đúng lúc; AI kiểm tra nhanh file nộp về (thiếu cột, sai format) trước khi đến tay Finance Controller |
| Cảm nhận nhanh | Rule |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — ~210 phút / tháng (ước tính)

[1 Gửi nhắc các bộ phận: 20']
→ [2 Theo dõi ai đã nộp, nhắc lại bộ phận trễ: 60']
→ [3 Nhận và kiểm tra dữ liệu: 50']
→ [4 Xin bổ sung / sửa file sai: 60'] ← BOTTLENECK
→ [5 Tổng hợp vào file đóng sổ: 20']
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi cần theo dõi doanh thu giữa tháng, tôi muốn xem doanh thu thực tế so với kế hoạch ngay, để kịp cảnh báo nếu lệch target thay vì chờ Sales gửi số. |
| Actor | Finance Controller (người tổng hợp); Kế toán doanh thu; Sales admin; người nhận: Ban Giám đốc, Trưởng phòng Sales |
| Thời điểm / bối cảnh | Giữa tháng (khoảng ngày 15), trước buổi họp review doanh thu với Sales/BGĐ |
| Quy trình hiện tại (3–7 bước) | Xin Sales số đơn hàng đã chốt -> export doanh thu từ ERP và lấy kế hoạch từ file budget -> đối chiếu đơn hàng, giao hàng, hóa đơn -> tổng hợp thực tế vs kế hoạch -> viết nhận xét và gửi báo cáo |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước xin số từ Sales (~40 phút, do chờ phản hồi) và bước đối chiếu đơn hàng, giao hàng, hóa đơn (~60 phút). Tổng cả quy trình ~180 phút/lần (ước tính) |
| Impact (nếu không giải thì sao) | Số liệu về trễ 2–3 ngày nên cảnh báo lệch target đến muộn, mất cơ hội xử lý trong tháng; tốn 6–12 giờ/tháng; tranh luận số của Sales và Kế toán làm chậm các buổi họp |
| Success metric (baseline → target) | Thời gian ra báo cáo: ~3 giờ -> dưới 30 phút/lần; độ trễ số liệu: 2–3 ngày -> trong ngày (ước tính) |
| Phương án không dùng AI | Thống nhất một định nghĩa "doanh thu" chung giữa Sales và Kế toán; dashboard BI hoặc Excel kết nối thẳng ERP, tự cập nhật thực tế vs kế hoạch; template báo cáo cố định |
| Giả thuyết về AI (nếu có) | AI đọc dữ liệu đã gom, đánh dấu các khoản lệch vượt ngưỡng và soạn nháp nhận xét nguyên nhân; Finance Controller review và sửa trước khi gửi |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — ~180 phút / lần (ước tính)

[1 Xin Sales số đơn hàng đã chốt: 40'] ← BOTTLENECK
→ [2 Export doanh thu từ ERP, lấy kế hoạch từ file budget: 20']
→ [3 Đối chiếu đơn hàng, giao hàng, hóa đơn: 60'] ← BOTTLENECK
→ [4 Tổng hợp thực tế vs kế hoạch: 30']
→ [5 Viết nhận xét và gửi báo cáo: 30']
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi các bộ phận hỏi số liệu ad-hoc, tôi muốn họ tự xem được dashboard, để tôi không bị ngắt quãng công việc chính liên tục. |
| Actor | Finance Controller (người nhận yêu cầu); Kế toán; các bộ phận hỏi số liệu: Sales, Mua hàng, Sản xuất, BGĐ |
| Thời điểm / bối cảnh | Rải rác trong ngày làm việc, tăng mạnh trước các buổi họp và cuối tháng |
| Quy trình hiện tại (3–7 bước) | Nhận yêu cầu qua Zalo/email/trực tiếp -> làm rõ số nào, kỳ nào, định nghĩa ra sao -> tìm và export dữ liệu từ ERP/Excel -> lọc, tính lại theo yêu cầu -> gửi kết quả và trả lời câu hỏi phát sinh |
| Bottleneck (bước nào, mất bao nhiêu phút) | Các bước làm rõ, tìm dữ liệu và tính lại (~20 phút) cộng ~15 phút lấy lại tập trung sau khi bị ngắt quãng. Tổng ~40 phút/yêu cầu, ~8 yêu cầu/tuần (ước tính) |
| Impact (nếu không giải thì sao) | Công việc chính (báo cáo, phân tích) bị ngắt quãng liên tục; cùng một câu hỏi bị trả lời lặp lại; người hỏi phải chờ nên quyết định bị chậm |
| Success metric (baseline → target) | Số yêu cầu ad-hoc/tuần: ~8 -> dưới 3; thời gian xử lý ad-hoc: ~5 giờ/tuần -> dưới 1,5 giờ/tuần (ước tính) |
| Phương án không dùng AI | Xây dashboard self-service cho các chỉ số hay hỏi nhất (doanh thu, chi phí, công nợ, tồn kho); tài liệu định nghĩa chỉ số; khung giờ cố định trong tuần để xử lý yêu cầu ad-hoc |
| Giả thuyết về AI (nếu có) | Trợ lý hỏi đáp trên dữ liệu đã chuẩn hóa: người dùng hỏi bằng ngôn ngữ tự nhiên, hệ thống trả lời và dẫn nguồn; Finance Controller chỉ xử lý các câu hỏi bất thường |
| Cảm nhận nhanh | Rule |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — ~40 phút / yêu cầu (ước tính)

[1 Nhận yêu cầu: 2']
→ [2 Làm rõ số nào, kỳ nào, định nghĩa: 5']
→ [3 Tìm và export dữ liệu: 8'] ← BOTTLENECK
→ [4 Lọc, tính lại theo yêu cầu: 7']
→ [5 Gửi kết quả, trả lời thêm: 3']
+ Lấy lại tập trung sau khi bị ngắt quãng: ~15'
```

### Card muốn pitch nhất

- Card số: 1
- Vì sao: có thể sử dụng AI để tự động hóa công việc nhắc lịch đến hạn cho các bên
- Câu hỏi muốn nhóm phản biện: có thể sử dụng công cụ khác được không ? 

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| [CẦN ĐIỀN] | | |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

> Phần này ghi những gì bạn đã làm thật trong lớp và nhóm, nên bạn tự điền.

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Đóng góp ý kiến đề xuất phần problem của bạn trong nhóm vì nó cũng là nỗi đau của mình cần giải quyết | 
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: không có 
| Nhận phản biện | Câu hỏi tôi nhận được:  | Tôi đã sửa gì: [CẦN ĐIỀN] |
| Gom cluster / cây OST | [CẦN ĐIỀN] | [CẦN ĐIỀN] |
| Chọn candidate problem | [CẦN ĐIỀN] | [CẦN ĐIỀN] |
| Kiểm chứng / research | [CẦN ĐIỀN] | [CẦN ĐIỀN] |
| Quy trình nhóm | [CẦN ĐIỀN] | [CẦN ĐIỀN] |
| Problem Statement | [CẦN ĐIỀN] | [CẦN ĐIỀN] |
| Mức can thiệp AI | [CẦN ĐIỀN] | [CẦN ĐIỀN] |
| Quyết định | [CẦN ĐIỀN] | [CẦN ĐIỀN] |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Nhờ AI gợi ý các vấn đề theo mẫu Job Story cho các công việc tốn thời gian của Finance Controller | [CẦN ĐIỀN] | [CẦN ĐIỀN] |  |
| CP2 Problem Card | Nhờ AI soạn Problem Card theo mẫu từ 3 vấn đề tôi chọn | [CẦN ĐIỀN] | [CẦN ĐIỀN — ví dụ: số phút và tần suất do AI ước tính, chưa phải số đo thật] | [CẦN ĐIỀN] |
| CP4 Research | [CẦN ĐIỀN] | [CẦN ĐIỀN] | [CẦN ĐIỀN] | [CẦN ĐIỀN] |
| CP5 Quy trình | [CẦN ĐIỀN] | [CẦN ĐIỀN] | [CẦN ĐIỀN] | [CẦN ĐIỀN] |
| CP5–6 Problem Statement | [CẦN ĐIỀN] | [CẦN ĐIỀN] | [CẦN ĐIỀN] | [CẦN ĐIỀN] |
| CP6 Mức can thiệp / quyết định | [CẦN ĐIỀN] | [CẦN ĐIỀN] | [CẦN ĐIỀN] | [CẦN ĐIỀN] |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Tôi biết thêm được nhiều vấn đề từ góc nhìn của nhiều người ở các lĩnh vực khác nhau 

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Có , thường có vấn đề là nghĩ đến giải pháp Ai trước khi nghĩ sâu hiểu vấn đề

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Không
**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Không

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Tìm ra điểm nghẽn 

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Phản biện 

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

Nhóm chọn một vấn đề chung từ rất nhiều vấn đề từ những góc nhìn khác nhau sau đó đưa ra quy trình các bước đang làm hiện tại với bottleneck là bước khó nhất, sau đó đưa ra metric đó được cụ thể , sau đó đưa ra giới hạn có thể làm được , mức can thiệp của AI trong quá trình làm , sau đó là người quyết định cuối cùng. 
---

## 7. Tài liệu tham khảo

- công cụ AI đã dùng : Claude 