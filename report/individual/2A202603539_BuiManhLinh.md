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
| 1 | Lặp lại | Khi nhận cuộc gọi từ shipper xác nhận giao hàng, tôi muốn xem lại nhanh mã vận đơn và tên mặt hàng đã đặt mà không cần thoát màn hình cuộc gọi, để xác nhận đúng đơn hàng cần nhận | Người mua bận rộn, shipper | Mất 15–20 giây để mở ứng dụng và kiểm tra đơn; chưa ghi tần suất gặp |
| 2 | Lặp lại | Khi nhận được thông báo đơn hàng sắp được giao trong ngày, tôi muốn hẹn trước khoảng thời gian shipper đến, để chủ động sắp xếp lịch trình cá nhân | Người đi làm, shipper | Ước tính 2–3 lần/tuần shipper đến lúc tôi không có thời gian rảnh |
| 3 | Tốn thời gian | Khi shipper giao tới nơi và yêu cầu thanh toán COD, tôi muốn thanh toán đúng số tiền mà không phải nhập tay hoặc tìm tiền mặt, để hoàn tất nhận hàng dưới 1 phút | Người mua hàng COD, shipper | Mất khoảng 2–3 phút để thanh toán |
| 4 | Tốn thời gian | Khi kiện hàng nhận được có dấu hiệu bị móp vỡ hoặc rách nát, tôi muốn quay video khui hàng kèm mã đơn đúng quy định của sàn, để xử lý khiếu nại hoàn tiền thuận lợi | Người mua hàng giá trị cao, dễ vỡ; bộ phận CSKH | Chưa ghi nhận thời gian hoặc tần suất cụ thể; cần bổ sung số đo từ trải nghiệm |
| 5 | Cần đọc, tổng hợp nhiều thông tin | Khi nhận được gói hàng COD lạ không rõ nguồn gốc, tôi muốn đối chiếu thông tin sản phẩm và lịch sử đặt hàng trên các ứng dụng mua sắm, để biết đây có phải đơn mình đã đặt không | Người mua lo ngại lừa đảo, shipper | Mất khoảng 5–10 phút tra cứu lịch sử mua hàng |
| 6 | Pain từ người khác | Khi người thân hoặc bảo vệ nhận hộ và trả tiền COD giúp tôi, tôi muốn cung cấp đầy đủ thông tin kiện hàng và số tiền chính xác cho họ trước, để họ không phải gọi xác minh lại hoặc trả nhầm tiền | Người thân/bảo vệ nhận hộ, người mua | Khoảng 3 cuộc gọi/tuần từ bảo vệ hoặc người thân |

**Nếu có dùng AI để gợi ý thêm:** AI gợi ý vấn đề nhận đồng thời 3–5 đơn COD từ nhiều sàn và cần phân biệt số tiền từng đơn. Tôi loại ý này vì không sử dụng nhiều sàn cùng lúc và thường nhớ các đơn mình đã đặt; ý tưởng đó không khớp với trải nghiệm của tôi.

--- 

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem Card | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Card #3 — Hẹn trước khung giờ giao hàng | Chạm đúng nỗi đau bị gián đoạn công việc; tần suất được ước tính 2–3 lần/tuần | Một số dịch vụ đã có tính năng chọn thời gian giao hàng; tính năng này có sẵn với đơn hàng và khu vực của tôi không? Shipper/bưu cục có thể đáp ứng khung giờ đã hẹn không? |
| 2 | Card #1 — Thanh toán COD không phải nhập tay | Quy trình tại chỗ rõ, thời gian đo được và ảnh hưởng cả người mua lẫn shipper | Shipper có QR thanh toán chứa đúng số tiền không, hay chỉ cung cấp số tài khoản? Mã vận đơn có chứa dữ liệu cần để tạo QR không? |
| 3 | Card #2 — Xác minh đơn COD lạ | Nếu xác minh sai, người mua có thể trả tiền cho đơn không đặt; hiện mất 5–10 phút tra cứu | Việc tiếp cận lịch sử mua hàng từ nhiều nền tảng có khả thi và được người dùng cho phép không? Có thể phân biệt đơn lạ với lừa đảo chỉ từ dữ liệu đó không? |

### Problem Card #1 — Thanh toán COD không phải nhập tay (Rank 2)

| Trường | Nội dung |
|---|---|
| Job Story | Khi shipper giao tới nơi và yêu cầu thanh toán tiền mặt, tôi muốn mở nhanh app ngân hàng và quét mã QR chính xác số tiền lẻ mà không cần nhập tay, để hoàn tất nhận hàng dưới 1 phút. |
| Actor | Người mua hàng online thường xuyên chọn thanh toán COD|
| Thời điểm / bối cảnh |Đứng ở cửa nhà/sảnh chung cư|
| Quy trình hiện tại (3–7 bước) |1. Nhận hàng từ shipper · 2. Hỏi số tiền · 3. Mở app ngân hàng · 4. Xin số tài khoản/ngân hàng của shipper · 5. Nhập tay số tiền lẻ và nội dung · 6. Bấm chuyển khoản · 7. Đợi shipper chụp màn hình xác nhận|
| Bottleneck (bước nào, mất bao nhiêu phút) |Bước 4–5: lấy thông tin tài khoản và nhập số tiền; mất khoảng 2 phút và có nguy cơ nhập sai|
| Impact (nếu không giải thì sao) |Mất 2–3 phút/đơn; người mua dễ thao tác sai; shipper bị chậm tiến độ|
| Success metric (baseline → target) |Baseline: khoảng 2–3 phút/đơn theo ước tính ban đầu. Target thử nghiệm: dưới 30 giây và không có sai lệch số tiền. Cách đo: bấm giờ các lần thanh toán COD trong một pilot và đối chiếu số tiền chuyển với số tiền thu hộ; số lần đo cần chốt trước pilot.|
| Phương án không dùng AI |Yêu cầu shop cho thanh toán thẻ từ trước; hoặc người mua chuẩn bị sẵn phong bì tiền lẻ ở nhà|
| Giả thuyết về AI (nếu có) |Chưa có căn cứ rằng mã vận đơn chứa tài khoản và số tiền COD. Giả thuyết đơn giản hơn là shipper/bưu cục cung cấp QR chuẩn có sẵn số tiền; bước này có thể không cần AI. Cần xác minh khả năng tạo và sử dụng QR trước khi đề xuất AI.|
| Cảm nhận nhanh | Rule hoặc không cần AI nếu hệ thống vận chuyển cung cấp QR chuẩn |

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

### Problem Card #2 — Xác minh đơn COD lạ (Rank 3; card muốn pitch)

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận được gói hàng COD lạ không rõ nguồn gốc, tôi muốn đối chiếu ngay thông tin sản phẩm và lịch sử đặt hàng trên các app, để biết chính xác đây là đơn mình mua thật hay chiêu trò lừa đảo. |
| Actor |Người mua hàng online, người nhà/bảo vệ thường xuyên nhận hộ hàng|
| Thời điểm / bối cảnh |Shipper gọi giao một đơn có thu tiền (COD) nhưng người mua không nhớ rõ đã đặt gì|
| Quy trình hiện tại (3–7 bước) |1. Cầm gói hàng xem thông tin · 2. Thấy lạ, sinh nghi · 3. Mở Shopee tìm lịch sử · 4. Mở Tiktok Shop tìm lịch sử · 5. Mở Lazada tìm lịch sử · 6. Đối chiếu mã vận đơn/tên hàng · 7. Ra quyết định nhận/hoàn|
| Bottleneck (bước nào, mất bao nhiêu phút) |Bước 3–5: tra cứu thủ công từng ứng dụng và đối chiếu bằng trí nhớ; theo ước tính ban đầu mất 5–10 phút|
| Impact (nếu không giải thì sao) |Mất 5–10 phút tra cứu, khiến shipper phải chờ; nếu xác minh nhầm, người mua có thể trả tiền cho đơn không đặt|
| Success metric (baseline → target) |Baseline: khoảng 5–10 phút/đơn lạ theo ước tính ban đầu. Target thử nghiệm: dưới 30 giây để đưa ra kết quả đối chiếu ban đầu. Cách đo: bấm giờ từ lúc cầm kiện hàng đến lúc có đủ thông tin để tự quyết định nhận hay từ chối; ghi riêng trường hợp không đủ dữ liệu.|
| Phương án không dùng AI |Chỉ nhận đơn khi tự tay tra được trạng thái "Đang giao hàng" trên app. Dặn người nhà tuyệt đối không nhận hộ bất kỳ đơn COD nào nếu không dặn trước.|
| Giả thuyết về AI (nếu có) |Nếu người dùng tự cung cấp ảnh mã vận đơn và dữ liệu đơn hàng mà họ có quyền truy cập, AI có thể trích xuất mã và tìm thông tin trùng khớp. Chỉ hiển thị thông tin đối chiếu hoặc "chưa đủ dữ liệu"; không tự kết luận đơn là lừa đảo hay thay người dùng quyết định thanh toán. Khả năng truy cập dữ liệu là giả định chưa được kiểm chứng.|
| Cảm nhận nhanh | Workflow có người dùng kiểm tra; chưa đủ căn cứ chọn Agent |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — khoảng 7-10 phút

[1 Xem thông tin kiện hàng: 30s] 
→ [2 Mở Shopee dò tìm: 2'] ← BOTTLENECK 
→ [3 Mở Tiktok dò: 2'] ← BOTTLENECK 
→ [4 Mở Lazada dò: 2'] ← BOTTLENECK 
→ [5 So sánh mã & Quyết định nhận/từ chối: 1']
```

### Problem Card #3 — Hẹn trước khung giờ giao hàng (Rank 1)

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận được thông báo đơn hàng sắp được giao trong ngày, tôi muốn hẹn trước khung giờ shipper đến, để chủ động sắp xếp lịch trình cá nhân. |
| Actor |Nhân viên văn phòng, hay phải họp hoặc di chuyển|
| Thời điểm / bối cảnh |"Đơn hàng đang trên đường giao" nhưng không có giờ cụ thể; shipper gọi bất ngờ lúc đang họp|
| Quy trình hiện tại (3–7 bước) |1. Nhận tin báo giao hàng chung chung · 2. Chờ đợi thụ động · 3. Shipper gọi lúc đang bận họp · 4. Cáo lỗi ngắt ngang cuộc họp nghe máy · 5. Hẹn lại giờ khác hoặc nhờ người nhận hộ · 6. Shipper vòng lại sau|
| Bottleneck (bước nào, mất bao nhiêu phút) |Bước 3–5: shipper gọi vào lúc người nhận đang bận, khiến phải ngắt việc hoặc hẹn lại. Thời lượng chờ có thể vài tiếng; thời gian gián đoạn chưa được đo riêng.|
| Impact (nếu không giải thì sao) |Ước tính 2–3 lần/tuần bị ảnh hưởng lịch; shipper có thể phải giao lại và kiện hàng có thể bị lưu kho thêm 1 ngày. Cần xác nhận lại tần suất này.|
| Success metric (baseline → target) |Baseline: chưa có số cuộc gọi nhỡ hoặc lần giao lại được ghi nhận; ghi chú hiện tại ước tính 2–3 lần/tuần bị ảnh hưởng lịch. Target thử nghiệm: không có cuộc gọi giao hàng làm gián đoạn cuộc họp trong thời gian pilot. Cách đo: ghi số cuộc gọi nhỡ, lần gián đoạn cuộc họp và lần giao lại trong 2 tuần; không xem yêu cầu hẹn giờ là bằng chứng shipper đã đáp ứng.|
| Phương án không dùng AI |Ghi chú thời gian giao hàng, chuyển địa chỉ sang địa chỉ công ty|
| Giả thuyết về AI (nếu có) |Trước tiên cần kiểm tra tính năng hẹn giờ sẵn có của đơn vị vận chuyển. Nếu người dùng chủ động cho phép chia sẻ lịch, hệ thống có thể đề xuất một khung giờ rảnh để người dùng xác nhận; chưa có căn cứ cho việc AI tự đọc lịch hoặc bưu cục có thể nhận yêu cầu tự động.|
| Cảm nhận nhanh | Rule/Workflow; không đủ căn cứ chọn Agent |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — Ngắt quãng luồng công việc

[1 Nhận báo giao hàng: 0']
→ [2 Chờ đợi thụ động: vài tiếng]
→ [3 Shipper gọi lúc đang bận: khoảng 1'] ← BOTTLENECK
→ [4 Xin lỗi/Ra ngoài nghe máy: khoảng 2']
→ [5 Hẹn lại: khoảng 1']
```

### Card muốn pitch nhất

- Card số: 2
- Vì sao: Card này liên quan đến dữ liệu đơn hàng cá nhân trên các nền tảng; chưa rõ nền tảng có cho phép truy cập và người dùng có muốn chia sẻ dữ liệu đó không.
- Câu hỏi muốn nhóm phản biện: Có thể xác minh đơn lạ mà không truy cập trực tiếp dữ liệu riêng tư của các sàn không? Dữ liệu nào đủ để cảnh báo mà không kết luận nhầm đơn hàng là lừa đảo?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Card đang giả định có thể lấy lịch sử mua hàng từ Shopee, TikTok Shop hoặc email; chưa có bằng chứng về quyền truy cập hay sự đồng ý của người dùng. | Đồng ý | Ghi khả năng truy cập dữ liệu là giả định cần kiểm chứng; giới hạn giả thuyết ở dữ liệu người dùng tự cung cấp và có quyền chia sẻ. |
| Kết quả "đơn hợp lệ/cảnh báo lừa đảo" có thể khiến người dùng tin vào kết luận khi dữ liệu đối chiếu thiếu hoặc sai. | Đồng ý | Đổi đầu ra giả thuyết thành thông tin trùng khớp hoặc "chưa đủ dữ liệu"; người dùng tự quyết định nhận hay từ chối. |
| Target dưới 30 giây chưa được đo và có thể không khả thi khi phải tìm thông tin ở nhiều ứng dụng. | Đồng ý | Ghi đây là target thử nghiệm; bổ sung cách bấm giờ và ghi nhận trường hợp không đủ dữ liệu, không trình bày target như kết quả đã đạt. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Trình bày ba vấn đề về giao nhận: hẹn giờ giao, thanh toán COD và xác minh đơn COD lạ (các dòng 7–9 trong bảng pitch nhóm). | Nhóm ghi nhận ba ý trong cluster C — tiện ích giao hàng. Nhóm chọn candidate về hướng dẫn sinh viên non-tech thay vì các ý giao nhận. |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: chưa được ghi lại trong tài liệu hiện có. | Bổ sung câu hỏi cụ thể nếu còn nhớ; không suy đoán câu hỏi đã đặt. |
| Nhận phản biện | Tôi nhận được câu hỏi liệu dịch vụ đã có tính năng hẹn giờ giao hàng chưa; liệu đề xuất QR có giải quyết pain gốc hay chỉ là giải pháp; và việc tổng hợp dữ liệu đơn từ nhiều sàn có khả thi không, có thể giải bằng chính sách chống lừa đảo không. | Các câu hỏi được ghi trong bảng pitch nhóm. Tài liệu hiện có chưa ghi rõ câu trả lời hoặc điều chỉnh tôi đã thực hiện sau buổi pitch; các điểm này được giữ thành giả định cần kiểm chứng trong bản card hiện tại. |
| Gom cluster / cây OST | Theo phân công, tôi ghi chép và điền bảng pitch + cluster. | Ba candidate giao hàng được xếp vào cluster C; nhóm chọn nhánh cơ hội về vấn đề học tập của sinh viên non-tech. |
| Chọn candidate problem | Tham gia thảo luận ba candidate của mình; phần lựa chọn cuối được ghi trong báo cáo nhóm. | Candidate của nhóm là thiếu nguồn hướng dẫn đúng trình độ cho sinh viên non-tech, không phải vấn đề giao hàng của tôi. |
| Kiểm chứng / research | Theo TEAM.md, tôi có hỗ trợ kiểm chứng lại thông tin thu thập được; tài liệu hiện có chưa ghi rõ câu hỏi, người tham gia hay kết quả do cá nhân tôi thu thập. | Không gán kết quả phỏng vấn/research của thành viên khác cho phần đóng góp cá nhân của tôi. |
| Quy trình nhóm | Chưa có đóng góp cá nhân cụ thể được ghi trong tài liệu hiện có. | Phần quy trình chung do người phụ trách CP5 tổng hợp trong báo cáo nhóm. |
| Problem Statement | Chưa có đóng góp cá nhân cụ thể được ghi trong tài liệu hiện có. | TEAM.md ghi người phụ trách chính phần Problem Statement là Lưu Thanh Mỹ. |
| Mức can thiệp AI | Chưa có đóng góp cá nhân cụ thể được ghi trong tài liệu hiện có. | TEAM.md ghi người phụ trách chính CP6 là Lưu Thanh Mỹ. |
| Quyết định | Chưa có đóng góp cá nhân cụ thể được ghi trong tài liệu hiện có. | Quyết định Not Yet và lý do được ghi trong báo cáo nhóm; không nhận là phần việc cá nhân nếu chưa bổ sung bằng chứng. |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Gợi ý thêm ý tưởng về đơn COD lạ; nội dung trong file cho biết tôi đã loại ý tưởng về nhiều đơn từ nhiều sàn vì không đúng thói quen của mình. | Gợi ý giúp mở rộng danh sách để tôi cân nhắc. | Ý tưởng nhiều đơn từ nhiều sàn không phù hợp với trải nghiệm của tôi. | Loại ý đó vì tôi không sử dụng nhiều sàn và thường nhớ các đơn đã đặt. |
| CP2 Problem Card | Nhờ AI đóng vai PM hoài nghi để rà soát card muốn pitch. | Giúp chỉ ra giả định về quyền truy cập dữ liệu, nguy cơ kết luận sai và metric chưa có cách đo. | Target dưới 30 giây chưa có dữ liệu chứng minh; việc truy cập lịch sử đơn hàng từ các nền tảng cũng chưa được xác nhận. | Ghi các điểm này thành giả định cần kiểm chứng; giới hạn đầu ra ở thông tin đối chiếu hoặc "chưa đủ dữ liệu", để người dùng quyết định. |
---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
Các bạn có nhiều góc nhìn khác nhau về các vấn đề. Mỗi người luôn có ý của riêng mình và rất hay. Tôi có thêm những nhận định về cuộc sống hơn vế các vấn đề đó

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
Kết quả không quá bất ngờ dù tôi mong sẽ hơi khác 1 chút

**6.5. Điều khó nhất khi viết Problem Statement là gì?**
Không chắc về Boundary và Success Metric

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
Tôi sẽ không đổi gì vì tôi nghĩ cả nhóm đang làm khá ổn. Tôi mong cả nhóm sẽ trao đổi nhiều hơn

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.
Vấn đề là sinh viên không có khi chuẩn bị buổi học AI, mất 1-2 tiếng chỉ để setup. Quy trình gồm 7 bước từ nhận tài liệu đến vào buổi học, trong đó bottleneck nằm ở bước 2–3 khi sinh viên tự mò khái niệm và setup công cụ mà không có người hỗ trợ đúng lúc. Success Metric là giảm thời gian chuẩn bị. Boundary: không làm hệ thống ôn tập. Mức can thiệp AI chọn là Workflow . Quyết định là Not Yet.

---

## 7. Tài liệu tham khảo
