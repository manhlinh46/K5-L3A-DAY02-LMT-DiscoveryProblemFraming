# Báo cáo cá nhân — 2A202603539_BuiManhLinh

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Bùi Mạnh Linh
- MSSV: 2A202603539
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: LMT
- Link repo nhóm: https://github.com/manhlinh46/-K5-L3A-DAY02-LMT-DiscoveryProblemFraming.git

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 |Lặp lại|Khi nhận cuộc gọi từ shipper xác nhận giao hàng, tôi muốn xem lại nhanh mã vận đơn và tên mặt hàng đã đặt mà không cần thoát màn hình cuộc gọi, để xác nhận đúng đơn hàng cần nhận|Người mua bận rộn, Shipper|15–20 giây để mở app và check lại xem có đúng đơn không|
| 2 |Lặp lại|Khi nhận được thông báo đơn hàng sắp được giao trong ngày, tôi muốn hẹn trước khoảng thời gian khung giờ shipper đến, để chủ động sắp xếp lịch trình cá nhân|Người đi làm, shipper|2–3 lần/tuần shipper tới nhưng không có thời gian rảnh |
| 3 |Tốn thời gian|Khi shipper giao tới nơi và yêu cầu thanh toán tiền mặt, tôi muốn mở nhanh app ngân hàng và quét mã QR chính xác số tiền lẻ mà không cần nhập tay hay tìm tiền mặt, để hoàn tất nhận hàng dưới 1 phút |Người mua hàng COD, Shipper|Mất 2–3 phút để thanh toán số tiền|
| 4 |Tốn thời gian|Khi kiện hàng nhận được có dấu hiệu bị móp vỡ hoặc rách nát, tôi muốn quay video khui hàng kèm mã đơn đúng chuẩn quy định của sàn, để không mất thời gian xử lý khi khiếu nại hoàn tiền|Người mua nhận hàng giá trị cao, dễ vỡ, Bộ phận CSKH|Tìm quy định khui hàng và nhắn tin qua lại với shop/sàn để khiếu nại|
| 5 |Cần đọc, tổng hợp nhiều thông tin|Khi nhận được gói hàng COD lạ không rõ nguồn gốc, tôi muốn đối chiếu ngay thông tin sản phẩm và lịch sử đặt hàng trên các ứng dụng mua sắm, để biết chính xác đây là đơn mình mua thật hay là chiêu trò lừa đảo|Người mua lo ngại lừa đảo, Shipper|5–10 phút tra cứu lịch sử mua hàng|
| 6 |Pain từ người khác|Khi người thân hoặc bảo vệ nhận hộ và trả tiền COD giúp tôi, tôi muốn cung cấp đầy đủ thông tin kiện hàng và số tiền chính xác cho họ trước, để người nhận hộ không phải gọi điện xác minh lại hay trả nhầm tiền|Người thân / Bảo vệ nhận hộ, Người mua|3 cuộc gọi/tuần từ bảo vệ/người thân gọi|

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

"Khi cùng lúc giao 3–5 đơn hàng COD từ các sàn khác nhau trong ngày, tôi muốn biết rõ shipper đang giao gói hàng nào và số tiền chính xác cần trả cho từng gói, để không bị thu nhầm tiền hoặc trả tiền cho đơn rác". tôi bỏ ý này vì tôi không sử dụng quá nhiều sàn và có ghi nhớ thông tin đơn hàng mình đặt

--- 

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 |Khi nhận được thông báo đơn hàng sắp được giao trong ngày, tôi muốn hẹn trước khoảng thời gian khung giờ shipper đến, để chủ động sắp xếp lịch trình cá nhân|Chạm đúng nỗi đau lỡ việc của dân văn phòng, tần suất cao|Shipper có chịu đọc tin nhắn hẹn giờ không hay theo lộ trình cố định của bưu cục?|
| 2 |Khi shipper giao tới nơi và yêu cầu thanh toán tiền mặt, tôi muốn mở nhanh app ngân hàng và quét mã QR chính xác số tiền lẻ mà không cần nhập tay hay tìm tiền mặt, để hoàn tất nhận hàng dưới 1 phút|Quy trình thanh toán tại chỗ rất rõ ràng, thời gian đo được, nỗi đau (pain) xuất hiện liên tục mỗi lần nhận hàng|Shipper có sẵn QR code không hay chỉ đọc số tài khoản?|
| 3 |Khi nhận được gói hàng COD lạ không rõ nguồn gốc, tôi muốn đối chiếu ngay thông tin sản phẩm và lịch sử đặt hàng trên các ứng dụng mua sắm, để biết chính xác đây là đơn mình mua thật hay là chiêu trò lừa đảo|Impact rất lớn (bảo vệ người dùng khỏi mất tiền oan), đánh đúng tâm lý bất an hiện nay|Việc lấy dữ liệu lịch sử đặt hàng từ nhiều nền tảng đóng (Shopee, TikTok) có khả thi về mặt kỹ thuật không?|

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi shipper giao tới nơi và yêu cầu thanh toán tiền mặt, tôi muốn mở nhanh app ngân hàng và quét mã QR chính xác số tiền lẻ mà không cần nhập tay, để hoàn tất nhận hàng dưới 1 phút. |
| Actor | Người mua hàng online thường xuyên chọn thanh toán COD|
| Thời điểm / bối cảnh |Đứng ở cửa nhà/sảnh chung cư|
| Quy trình hiện tại (3–7 bước) |1. Nhận hàng từ shipper · 2. Hỏi số tiền · 3. Mở app ngân hàng · 4. Xin số tài khoản/ngân hàng của shipper · 5. Nhập tay số tiền lẻ và nội dung · 6. Bấm chuyển khoản · 7. Đợi shipper chụp màn hình xác nhận|
| Bottleneck (bước nào, mất bao nhiêu phút) |Bước 4 & 5: Lấy thông tin tài khoản và nhập tay số tiền lẻ, dễ nhập nhầm số hoặc chọn sai ngân hàng, mất khoảng 2 phút|
| Impact (nếu không giải thì sao) |Mất 2–3 phút/đơn; người mua bối rối, dễ thao tác sai; shipper bị chậm tiến độ|
| Success metric (baseline → target) |Thời gian từ lúc mở app đến lúc chuyển xong giảm từ 3 phút xuống dưới 30 giây; 0% sai lệch số tiền|
| Phương án không dùng AI |Yêu cầu shop cho thanh toán thẻ từ trước; hoặc người mua chuẩn bị sẵn phong bì tiền lẻ ở nhà|
| Giả thuyết về AI (nếu có) |Ứng dụng dùng AI/Rule quét trực tiếp mã vận đơn trên hộp hàng để tự sinh mã QR thanh toán có sẵn thông tin tài khoản bưu cục và số tiền chính xác|
| Cảm nhận nhanh | Workflow / Rule |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — khoảng 3 phút

[1 Nhận hàng: 10s] 
→ [2 Hỏi tiền: 10s] 
→ [3 Mở app: 10s] 
→ [4 Xin thông tin TK: 40s] ← BOTTLENECK
→ [5 Nhập số tiền lẻ + nội dung: 60s] ← BOTTLENECK
→ [6 Chuyển khoản: 20s] 
→ [7 Xác nhận: 20s]
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận được gói hàng COD lạ không rõ nguồn gốc, tôi muốn đối chiếu ngay thông tin sản phẩm và lịch sử đặt hàng trên các app, để biết chính xác đây là đơn mình mua thật hay chiêu trò lừa đảo. |
| Actor |Người mua hàng online, người nhà/bảo vệ thường xuyên nhận hộ hàng|
| Thời điểm / bối cảnh |Shipper gọi giao một đơn có thu tiền (COD) nhưng người mua không nhớ rõ đã đặt gì|
| Quy trình hiện tại (3–7 bước) |1. Cầm gói hàng xem thông tin · 2. Thấy lạ, sinh nghi · 3. Mở Shopee tìm lịch sử · 4. Mở Tiktok Shop tìm lịch sử · 5. Mở Lazada tìm lịch sử · 6. Đối chiếu mã vận đơn/tên hàng · 7. Ra quyết định nhận/hoàn|
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3, 4, 5: Tra cứu thủ công, lục lọi rải rác trên nhiều app khác nhau bằng trí nhớ mất rất nhiều thời gian|
| Impact (nếu không giải thì sao) |Tốn 5–10 phút tra cứu khiến shipper phải chờ đợi;|
| Success metric (baseline → target) |Thời gian xác minh một đơn hàng lạ giảm từ 10 phút xuống dưới 30 giây|
| Phương án không dùng AI |Chỉ nhận đơn khi tự tay tra được trạng thái "Đang giao hàng" trên app. Dặn người nhà tuyệt đối không nhận hộ bất kỳ đơn COD nào nếu không dặn trước.|
| Giả thuyết về AI (nếu có) |Người mua chụp ảnh mã vận đơn trên kiện hàng gửi cho AI; AI trích xuất chữ (OCR) và tự động đối chiếu với email xác nhận đơn hàng/lịch sử mua sắm để báo ngay "Đơn hợp lệ" hoặc "Cảnh báo lừa đảo"|
| Cảm nhận nhanh | Workflow / Agent |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — khoảng 7-10 phút

[1 Xem thông tin kiện hàng: 30s] 
→ [2 Mở Shopee dò tìm: 2'] ← BOTTLENECK 
→ [3 Mở Tiktok dò: 2'] ← BOTTLENECK 
→ [4 Mở Lazada dò: 2'] ← BOTTLENECK 
→ [5 So sánh mã & Quyết định nhận/từ chối: 1']
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận được thông báo đơn hàng sắp được giao trong ngày, tôi muốn hẹn trước khung giờ shipper đến, để chủ động sắp xếp lịch trình cá nhân. |
| Actor |Nhân viên văn phòng, hay phải họp hoặc di chuyển|
| Thời điểm / bối cảnh |"Đơn hàng đang trên đường giao" nhưng không có giờ cụ thể; shipper gọi bất ngờ lúc đang họp|
| Quy trình hiện tại (3–7 bước) |1. Nhận tin báo giao hàng chung chung · 2. Chờ đợi thụ động · 3. Shipper gọi lúc đang bận họp · 4. Cáo lỗi ngắt ngang cuộc họp nghe máy · 5. Hẹn lại giờ khác hoặc nhờ người nhận hộ · 6. Shipper vòng lại sau|
| Bottleneck (bước nào, mất bao nhiêu phút) |Bước 3 & 4: Cuộc gọi bất ngờ làm gián đoạn luồng công việc; không có cơ chế chốt trước giờ rảnh từ đầu ngày|
| Impact (nếu không giải thì sao) |2–3 cuộc họp/tuần; shipper bực mình vì khách không nghe máy; hàng bị lưu kho giao lại mất thêm 1 ngày|
| Success metric (baseline → target) |Số cuộc gọi nhỡ từ shipper = 0; số lần phải chạy ra nhận hàng lúc đang họp giảm về 0|
| Phương án không dùng AI |Ghi chú thời gian giao hàng, chuyển địa chỉ sang địa chỉ công ty|
| Giả thuyết về AI (nếu có) |AI đọc lịch Google Calendar của người mua, tự động phân tích khoảng thời gian trống trong ngày và nhắn lại cho hệ thống bưu cục/shipper: "Khách rảnh từ 12h-13h, vui lòng giao khung giờ này"|
| Cảm nhận nhanh | Agent |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — Ngắt quãng luồng công việc

[1 Nhận báo giao hàng: 0'] 
→ [2 Chờ đợi thụ động: vài tiếng] 
→ [3 Shipper gọi lúc đang bận: 1'] ← BOTTLENECK 
→ [4 Xin lỗi/Ra ngoài nghe máy: 2'] 
→ [5 Hẹn lại: 1'][cite: 1]
```

### Card muốn pitch nhất

- Card số: 2
- Vì sao: vì có thông tin của khách hàng và app, có thể app sẽ không đồng ý chia sẽ dữ liệu người dùng
- Câu hỏi muốn nhóm phản biện: 

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| | | |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | | | | |
| CP2 Problem Card | | | | |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
