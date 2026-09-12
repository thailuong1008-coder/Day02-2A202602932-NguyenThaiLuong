# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   | Nguyễn Thái Lương | 2A202602932 | Facilitator / Workflow Architect                              |
| 2   | Lê Việt Hoàng     | 2A202602596 | Problem Lead / Validation                                      |
| 3   | Nguyễn Khánh Duy  | 2A202602403 | Technical Writer / Problem Statement Lead                     |
| 4   | Trần Cao Quốc Định| 2A202602939 | Research Lead / Tool & Competitor Analysis                     |
| 5   | Mai Tiến Huy      | 2A202602914 | Solution Analyst (Rule vs Workflow vs Agent)                  |
| 6   | Trịnh Xuân Huy    | 2A202602995 | Quality Assurance / Risk & Boundary Reviewer                   |

**Candidate problem nhóm chọn (1 câu):**

Người trẻ dễ mất cọc và chịu chi phí vô lý khi thuê trọ, mua xe cũ vì không biết biến thỏa thuận miệng thành điều khoản hợp đồng rõ ràng để bảo vệ quyền lợi của mình.

---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Lê Việt Hoàng | Meeting notes + action item sau họp nhóm | Cả nhóm đồ án 4 người — người ghi chú mất 27–34' viết lại note, 3 thành viên còn lại bị ảnh hưởng khi action item bị rơi | Bước 4 — tách action item có owner + deadline (7–10'); tuần trước 3/8 việc bị rơi vì không ghi owner | Pain cực kỳ thật, nhóm đồ án nào cũng gặp; workflow rõ ràng, khả thi cao. |
| 2 | Lê Việt Hoàng | Tìm lại quyết định/thông tin cũ trong Discord | Thành viên nhóm đồ án và học viên trong kênh khóa học (nhiều người phải hỏi lại cùng một câu) | Search chỉ match từ khóa nên phải thử 2–3 keyword rồi mở 4–6 thread đọc thủ công (10–15') | Phạm vi rộng, truy cập dữ liệu Discord API có rào cản phân quyền. |
| 3 | Lê Việt Hoàng | Đồng bộ deadline 5 môn (LMS + Discord + email) vào 1 lịch | Sinh viên học nhiều môn song song — dễ trễ deadline vì thông báo rải rác | Nhập tay deadline vào Google Calendar (6'/môn); email phi cấu trúc dễ sót → tuần trước trễ 1 deadline | Pain lớn, nhưng phụ thuộc API trường học và quyền truy cập dữ liệu. |
| 4 | Nguyễn Khánh Duy | Tự động trích xuất Meeting Notes & Action Items | Trưởng nhóm và các thành viên làm bài tập lớn / đồ án môn học (3–5 người) | Nghe lại bản ghi âm lộn xộn (45–60') để lọc ra câu chốt quyết định và gõ lại danh sách phân công việc (mất 20–30' sau họp) | Rất đồng nhất với bài của Hoàng; điểm nghẽn và metric thời gian đo được ngay. |
| 5 | Nguyễn Khánh Duy | Người trẻ dễ mất cọc và chịu chi phí vô lý khi thuê trọ, mua xe vì không biết biến thỏa thuận miệng thành điều khoản hợp đồng bảo vệ mình | Sinh viên và người trẻ (18–30 tuổi) thuê phòng trọ hoặc mua/bán xe máy cũ lần đầu | Bước ký hợp đồng: không biết chuyển thỏa thuận miệng thành điều khoản pháp lý bảo vệ họ; đọc hợp đồng hoang mang mất 1–2h; khi tranh chấp không có chứng cứ rõ ràng nên chịu mất cọc (avg 850k). | Pain cực kỳ thật, tổn thất tài chính trực tiếp; ranh giới AI rõ ràng (hỗ trợ soạn thảo, flag bẫy, tạo evidence). |
| 6 | Nguyễn Khánh Duy | Tổng hợp deadline và thông báo môn học từ nhiều kênh rời rạc (LMS, Teams, Discord, Email) | Sinh viên theo học 4–6 môn/kỳ với lịch học và bài tập dồn dập | Đọc quét tin nhắn phi cấu trúc và gõ tay nhập liệu thủ công từng hạn chót vào lịch (mất 35–45'/tuần, dễ sót 1–2 bài/kỳ) | Trùng cụm với bài của Hoàng; pain rất nhức nhối nhưng phụ thuộc tích hợp nhiều nguồn. |
| 7 | Trần Cao Quốc Định | So sánh giá điện thoại trên 5 app (Shopee, Lazada, Tiki, Facebook, TikTok) | Sinh viên hay mua hàng công nghệ, ngân sách hạn chế | Phải vào từng app check giá riêng lẻ, mất 45–60', 50% lần mua xong bị hối tiếc vì chỗ khác rẻ hơn | Bị vướng chính sách chống bot (anti-scraping) và API đóng của các sàn TMĐT. |
| 8 | Trần Cao Quốc Định | Làm bài tập lặp lại format mỗi lần | Sinh viên làm bài tập lớn 2–3 bài/tuần | Tìm template cũ, copy, manual sửa format bài tập (chiếm 30% thời gian làm bài) | Có thể giải quyết thuần túy bằng template Word/LaTeX sẵn có (Rule/No AI). |
| 9 | Trần Cao Quốc Định | Quản lý e-commerce: order, inventory, customer lẫn lộn | Chủ e-commerce side business + bạn cùng phụ bán | Data rải rác 3 app, phải training bạn 3–5h/tháng, bạn hay quên SOP và nhầm đơn | Domain hẹp, chỉ phù hợp người kinh doanh, không phải pain chung của cả nhóm. |
| 10 | Mai Tiến Huy | Điều hướng khám: triệu chứng → chuyên khoa khám; không chẩn đoán | Người bệnh, người nhà bệnh nhân, nhân viên tiếp đón bệnh viện | Không ánh xạ được triệu chứng bệnh vào đúng chuyên khoa; mất công hỏi lễ tân hoặc đi khám nhầm khoa | Impact lớn, metric rõ; tuy nhiên domain Y tế có rủi ro pháp lý/sức khỏe cực cao, boundary rất khó kiểm soát. |
| 11 | Mai Tiến Huy | Phát hiện lỗ hổng kiến thức sau bài thi thử (không chỉ báo điểm) | Học sinh, sinh viên tự ôn tập, giáo viên theo dõi tiến độ | Từ danh sách câu làm sai → phân tích ra dạng bài yếu và bước tư duy bị hổng kiến thức | Ý nghĩa sư phạm tốt; tuy nhiên việc phân tích bước tư duy đòi hỏi dữ liệu giải chi tiết chuẩn hóa. |
| 12 | Mai Tiến Huy | Đối chiếu CV với JD xác định kỹ năng còn thiếu | Sinh viên mới ra trường, người tìm việc chuyển ngành | Đọc nhiều JD nhưng khó biết thiếu kỹ năng nào; mất 30–45' đối chiếu từng gạch đầu dòng | Quy trình rõ ràng; nhưng trên thị trường đã có nhiều công cụ giải quyết tốt (Jobscan, Teal). |
| 13 | Trịnh Xuân Huy | Kiểm tra và xóa bỏ bounding box lỗi / nhãn rỗng sau auto-label dataset ảnh | AI Intern, sinh viên làm đồ án thị giác máy tính | Soi mắt duyệt từng ảnh trên CVAT/LabelImg để tìm box lệch, box trùng (mất 2–3h/tuần) | Bài toán kỹ thuật rất hay; nhưng đòi hỏi kiến thức chuyên sâu về Computer Vision mà cả nhóm không đồng đều. |
| 14 | Trịnh Xuân Huy | Nhập tay từng khoản chi tiêu nhỏ từ SMS/app ngân hàng vào app tài chính | Cá nhân quản lý chi tiêu (sinh viên, người đi làm) | Đọc nội dung biến động số dư rồi tự gõ tay số tiền và chọn danh mục chi tiêu (mất 20–30'/tuần) | Rất gần gũi, dữ liệu rõ ràng; trùng khớp với bài toán của Nguyễn Thái Lương; phần lớn có thể giải quyết bằng Regex/Rule. |
| 15 | Trịnh Xuân Huy | So sánh giá thực tế và tìm voucher tối ưu trên sàn TMĐT trước khi chốt đơn | Người mua sắm online thường xuyên | Phải bấm vào màn hình checkout của từng sàn để thử áp mã giảm giá và phí ship (mất 15–20'/đơn) | Trùng cụm mua sắm với Định; bị chặn bởi cơ chế mã hóa voucher động của sàn. |
| 16 | Nguyễn Thái Lương | Đối chiếu catalog linh kiện cơ khí tiêu chuẩn từ nhà sản xuất (HIWIN, Misumi) | Sinh viên đồ án cơ điện tử, kỹ sư CAD | Lật PDF catalog 200+ trang tra kích thước lắp ráp, bước ren, tải trọng (mất 45–75'/cụm); tra nhầm mã làm trễ đồ án 4 ngày | Bài toán kỹ thuật rất sâu, workflow chặt chẽ; nhưng chuyên môn cơ khí hẹp so với các bạn khác trong nhóm. |
| 17 | Nguyễn Thái Lương | Phân loại và số hóa chi tiêu từ ảnh chụp màn hình giao dịch ngân hàng | Sinh viên, người sống tự lập theo dõi tài chính | Mở từng ảnh chuyển khoản nhìn số tiền, gõ lại vào Google Sheets và tự xếp loại danh mục (mất 25–35'/tuần) | Bổ trợ rất tốt cho bài của Trịnh Xuân Huy; workflow ngắn gọn, đầu vào ảnh thực tế rõ ràng. |
| 18 | Nguyễn Thái Lương | Tự động phân loại tài liệu thư mục Downloads theo môn học/đồ án | Sinh viên, người học trực tuyến tải nhiều tài liệu | Thư mục dồn ứ 30–45 file rác; mất 15–20'/tuần mở từng file xem trang đầu để kéo về thư mục môn học | Rất thực tế; là ví dụ điển hình để so sánh Rule (script theo đuôi file) với Workflow AI. |

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A. Thông tin môn học rải nhiều kênh | #2, #3 (Hoàng), #6 (Duy) | Deadline / quyết định nằm LMS, Discord, email — phải lục và nhập tay | Pain lớn; vướng quyền truy cập và API trường. |
| B. So sánh giá / vận hành bán hàng | #7, #9 (Định), #15 (X.Huy) | Quét nhiều app trước khi chốt đơn hoặc xử lý đơn | Anti-scraping, API đóng; #9 domain hẹp (side business). |
| C. Giao dịch miệng vs giấy (bằng chứng) | #5 (Duy) | Lời hứa lúc xem phòng/xe không được ghi vào giấy chủ đưa; khi tranh chấp không đối chiếu được | Một bài, một pattern. Không gom với chi tiêu SMS/ảnh sao kê (#14, #17) — đó là nhập liệu, không phải hợp đồng. |
| D. Việc lặp format / file / số hóa chi tiêu | #8 (Định), #14 (X.Huy), #17, #18 (Lương) | Copy template, xếp file, gõ lại tiền từ SMS/ảnh | Nhiều bước đủ Rule (template, regex, đuôi file). |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

Bảy câu: có người trong nhóm hiểu workflow đủ sâu? Actor cụ thể? Bottleneck là một bước? Impact đo được? Vẽ before/after được? So sánh Rule / Workflow / Agent được? Không quá rộng cho lab?

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| **1. Lời hứa miệng/Zalo không vào giấy khi thuê trọ / mua xe cũ** | Actor rõ (SV / người trẻ giao dịch với chủ nhà hoặc người bán cá nhân). Bottleneck một bước: lúc ký, không đối chiếu thỏa thuận miệng với chữ trên giấy. Impact là tiền (cọc, điện, sửa chữa) chứ không chỉ phút gõ. Cả nhóm đang hoặc sắp thuê trọ nên kể được chuyện thật. So sánh R/W/A được: checklist 10 mục vs AI đối chiếu vs agent đàm phán hộ. | Chủ nhà/người bán có chịu ghi thêm câu không? AI sai luật thì sinh viên vẫn không bắt được. Lab không mô phỏng được vụ mất cọc thật (thường xảy ra sau tháng). Hai ngữ cảnh (trọ / xe) dễ làm bài bị phình. |
| **2. Sau đề chỉ thấy điểm, không biết yếu dạng nào / bước nào** (#11 M.Huy) | Actor rõ: học sinh / SV tự ôn — cả nhóm đóng vai được. Bottleneck một bước: từ list câu sai → dạng yếu + bước yếu. Workflow ôn → luyện đúng dạng → test lại vẽ được. So sánh R/W/A: đề đã gắn mã dạng thì Rule đếm đủ; AI chỉ khi cần đọc lời làm / sinh câu cùng dạng; không cần Agent gia sư. Pilot: mang 1 đề 20 câu vào buổi họp. | Không có bài làm / lời giải thì AI dễ bịa “sai bước dấu”. “Ôn đúng chỗ” phải đo bằng test lại, không chỉ bằng phút. |
| **3. Đồng bộ deadline đa kênh vào lịch** | Actor là SV 4–6 môn/kỳ. Pain trễ hạn có thật. Metric phút nhập tay + số deadline sót đo được. | LMS / Teams / Discord / email: quyền truy cập và API. Khó làm thật trong lab nếu không có token hợp lệ. |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| **Hợp đồng thuê trọ / mua xe cũ** | 5 | 5 | 4 | 5 | 3 | 5 | 5 | **32** |
| **Lỗ hổng kiến thức sau đề** | 5 | 5 | 3 | 4 | 5 | 5 | 5 | **32** |
| **Đồng bộ deadline đa kênh** | 5 | 4 | 4 | 4 | 3 | 4 | 5 | **29** |

**Vì sao cho 5 / cho 3 (không chấm cảm tính):**

- Hợp đồng **Lab = 3**: không mời được chủ nhà vào buổi lab; tranh chấp cọc không xảy ra trong 4 giờ. **Pain = 4**: cả nhóm kể được vụ mình hoặc bạn, chưa có quote ngoài nhóm lúc chấm. **Impact = 5**: mất cọc / bị tính thêm là số tiền, không phải “mất thì giờ gõ”.
- Lỗ hổng kiến thức **Lab = 5**: mở 1 đề 20 câu là chạy được. **Pain = 3**: lúc hội tụ mới có mô tả, chưa interview bạn vừa làm đề. **Impact = 4**: ôn sai chỗ tốn giờ, không mất cọc.
- Deadline **Lab = 3**: kẹt quyền dữ liệu trường.

Nhóm chốt vấn đề bằng câu hỏi: *bài nào bottleneck là “lời nói không thành chữ” và hậu quả là tiền, mà cả sáu người đều gặp khi thuê trọ / mua xe?* Chọn hợp đồng.

**Candidate nhóm chọn (1 bài duy nhất):**

```text
Người trẻ dễ mất cọc và chịu chi phí vô lý khi thuê trọ, mua xe cũ
vì không biết biến thỏa thuận miệng thành điều khoản hợp đồng rõ ràng
để bảo vệ quyền lợi của mình.
```

**Vì sao chọn (4-5 câu):**

```text
1. Pain là tiền và bằng chứng, không chỉ phút gõ: lúc xem phòng/xe hai bên
   nói vui (sửa điều hòa, báo trước trả phòng, xe “bao êm”), lúc ký thì
   giấy của chủ/bên bán không có câu đó.
2. Bottleneck một bước, vẽ được: sau thỏa thuận miệng, trước khi nộp cọc —
   đối chiếu lời/Zalo với chữ trên giấy.
3. Không phụ thuộc API trường hay đề đã gắn mã dạng. Input là tin nhắn
   + ảnh/chữ hợp đồng — cả nhóm lấy được từ vụ thật hoặc bạn bè.
4. So sánh R/W/A rõ: checklist 10 mục (No AI / Rule) đã có trên mạng nhưng
   không khớp từng lời hứa; AI chỉ đáng dùng để chỉ ra chỗ miệng và giấy lệch;
   Agent đàm phán hộ thì vượt ranh giới.
5. Cả sáu người đang sống tự lập hoặc sắp thuê / mua xe, nên challenge được
   từng bước “thật ra lúc đó mình làm gì”.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
- Lỗ hổng kiến thức sau đề (#11): làm trong lab dễ hơn (Lab = 5). Không chọn
  đào sâu vì hòa điểm và nhóm muốn bài “quên ghi ra giấy” có hậu quả tiền,
  không chỉ ôn lan man. Giữ làm dự phòng: 1 đề 20 câu.
- Đồng bộ deadline đa kênh: pain thật nhưng kẹt quyền LMS / Teams / email
  trường; không pilot được nếu không có admin.
- Catalog linh kiện / bounding box / điều hướng khám: một người hiểu domain;
  khám bệnh thì AI sai có giá sức khỏe — không đào sâu trong lab này.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
Xuân Huy (QA) lo: “AI viết điều khoản sai thì ai chịu?” Huy từng nghiêng
bài #11 (lỗ hổng sau đề) vì Lab = 5 và tự lấy được 1 đề mẫu. Duy và Lương
giữ bài hợp đồng nhưng chấp nhận siết scope: AI không soạn hợp đồng thay
luật sư, không đàm phán với chủ, không giải tranh chấp. AI chỉ đối chiếu
lời/Zalo với giấy và gợi ý câu để sinh viên tự gửi / tự viết thêm. Huy
(Solution Analyst) đề nghị hạ Agent xuống Workflow và bắt mọi flag phải
trích được câu nguồn. Hòa 32–32 phá bằng phiếu “hậu quả có phải tiền
+ lời vs giấy không?” — có thì đi hợp đồng; không lấy được Zalo + giấy
trong tuần thì chuyển #11.
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview | 4 thành viên trong nhóm (hỏi nhau lúc hội tụ; 3 thuê trọ, 1 mua xe cũ) | Nguyễn Khánh Duy: *“Xem phòng chủ bảo hỏng điều hòa thì bác sửa. Hè máy chảy nước, bắt mình chịu vì giấy chỉ ghi bên thuê chịu phí bảo trì.”* Lê Việt Hoàng: *“Nhắn Zalo báo trả phòng trước 30 ngày, chủ bảo OK. Ngày dọn trừ cọc, giấy ghi phải làm đơn thanh lý trước 45 ngày.”* Trịnh Xuân Huy: *“Mua xe cũ, người bán nói máy êm. Hỏng thì bị chặn Zalo; giấy viết tay không có câu bảo hành máy.”* | Trần Cao Quốc Định: thuê qua môi giới, giấy công ty dài hơn — *“Mình không đọc hết mấy điều phạt cọc, ký cho xong.”* | **Thu hẹp actor:** giao dịch với chủ nhà / người bán **cá nhân**, không lấy hợp đồng công ty môi giới (case Định) làm bài chính. **Thu hẹp việc AI làm:** không sinh cả bộ hợp đồng mới; lấy giấy chủ đưa + tin Zalo làm input. |
| Survey / poll | Giơ tay / hỏi nhanh cả 6 thành viên (mẫu nội bộ, **chưa** khảo sát lớp). Muốn poll ngoài nhóm thì đính `02-group-problem-statement-survey.png`. | 6/6 kể được ít nhất một vụ “nói rồi không ghi” (trọ, xe, hoặc nghe bạn gặp). | Nguyễn Thái Lương: từng ở chỗ người quen, gần như không làm giấy. Định (như trên): đã có giấy công ty vẫn không đọc hết. | Không giải “thuê người thân” và không giải “ký hợp đồng công ty 10 trang”. Pilot ưu tiên **thuê trọ cá nhân**; mua xe cũ cùng pattern, case phụ (Xuân Huy). |
| Log / mẫu giấy | Vài tờ giấy / ảnh hợp đồng thành viên mang ra soi (không phải audit pháp lý) | Thấy lặp: cọc trả “nếu hai bên thống nhất”, điện nước không ghi cách tính, sửa chữa thiết bị một câu chung. | Không đủ mẫu để nói “9/10 hợp đồng bất lợi”. | Không dùng tỷ lệ 9/10. Chỉ dùng để liệt kê **ô trống checklist** (cọc, báo trước, điện nước, ai sửa gì). |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Pain không phải thiếu mẫu hợp đồng trên mạng. Pain là sinh viên lép vế
trước giấy in sẵn của chủ / bên bán, và không biến lời hứa miệng (hoặc
tin Zalo) thành câu chữ đối chiếu được khi nộp cọc. Định cho thấy: có
giấy dài vẫn không đọc — vậy việc đúng là chỉ ra chỗ lệch, không phải
sinh thêm 8 trang.
```

Bằng chứng đính kèm (nếu có): `02-group-problem-statement-survey.png`, `...-interview-notes.md`

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| **Thư viện Pháp luật (Mẫu hợp đồng thuê nhà / mua bán xe)** | https://thuvienphapluat.vn | Khởi tạo nội dung pháp lý (Input Baseline) – Cung cấp mẫu hợp đồng chuẩn luật cho người dân tải về dùng | Chuẩn pháp lý Việt Nam, đầy đủ căn cứ luật hiện hành | Văn bản dài 6-10 trang, hàn lâm, sinh viên đọc không hiểu; không giải quyết được các thỏa thuận miệng riêng lẻ (hỗ trợ điều hòa, cọc xe, giờ giấc); không có cảnh báo bẫy điều khoản | Cần mẫu hợp đồng tinh gọn, tập trung vào các điều khoản thiết yếu và bảo vệ người thuê, giải thích thuật ngữ bằng ngôn ngữ đời thường. |
| **DocuSign / VNPT eContract** | https://docusign.com | Ký kết & Lưu trữ bằng chứng (Output & Storage) – Ký số điện tử, lưu trữ chứng cứ số với timestamp | Giá trị pháp lý cao, chống chối bỏ chữ ký, lưu trữ an toàn trên cloud | Chi phí bản quyền cao, thủ tục xác thực danh tính phức tạp cho cá nhân, không có AI phân tích nội dung hay tạo điều khoản từ ngôn ngữ nói | Giữ lại cơ chế tạo bằng chứng điện tử (PDF + timestamp/mã băm) nhưng phải cực kỳ tinh gọn, miễn phí hoặc chi phí siêu thấp cho sinh viên. |
| **Robin AI / Spellbook** | https://www.robinai.com | Phân tích & Phát hiện rủi ro (AI Processing) – LLM đọc, rà soát và phát hiện điều khoản rủi ro trong hợp đồng | Phân tích hợp đồng bằng AI cực mạnh, highlight rủi ro chính xác theo thời gian thực | Chuyên cho doanh nghiệp B2B, luật Anh/Mỹ, giá cực đắt ($100+/tháng), không tương thích ngữ cảnh đời sống sinh viên Việt Nam | Không làm giải pháp B2B phức tạp; chắt lọc tính năng "gắn cờ điều khoản rủi ro" (flag risky clause) và "gợi ý điều khoản an toàn thay thế" vào một Workflow tiếng Việt nhẹ nhàng. |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Không nên build một nền tảng ký số cồng kềnh đòi hỏi cả hai bên phải cài app hay xác thực phức tạp, cũng không build công cụ AI pháp lý B2B đắt đỏ. Nên build một Workflow AI siêu nhẹ: Sinh viên nhập thỏa thuận miệng/tin nhắn → AI ráp vào khung hợp đồng chuẩn, gắn cờ điều khoản bẫy và gợi ý phương án bảo vệ → Xuất bản PDF có mã băm xác thực kèm hướng dẫn đàm phán nhẹ nhàng với chủ nhà/bên bán.
```

> Lưu ý: không dùng số liệu AI đưa nếu không verify được link chính thức. Ghi rõ giả định chưa chắc.

---

## Phase 5 — Workflow + Problem Statement

Dán workflow hoặc link file: `02-group-problem-statement-workflow.md`

### 5.1. Current workflow bản nhóm

```text
CURRENT STATE — 7 bước, 4.5 giờ
+-----------------------------------------------------------------------------------+
| [1. Tìm phòng/xe] (2h - SV)                                                      |
+-----------------------------------------------------------------------------------+
                                         │
                                         ▼
+-----------------------------------------------------------------------------------+
| [2. Thỏa thuận miệng] (1h - SV + Chủ nhà)                                         |
+-----------------------------------------------------------------------------------+
                                         │
                                         ▼
+-----------------------------------------------------------------------------------+
| [3. Chủ nhà đưa HĐ in sẵn] (5' - Chủ nhà)                                         |
+-----------------------------------------------------------------------------------+
                                         │
                                         ▼
+-----------------------------------------------------------------------------------+
| 🔴 [4. BOTTLENECK 1: Đọc lướt HĐ trong bối rối] (10' - SV)                        |
+-----------------------------------------------------------------------------------+
                                         │
                                         ▼
+-----------------------------------------------------------------------------------+
| 🔴 [5. BOTTLENECK 2: Không biết đàm phán, ký bừa & nộp cọc] (10' - SV)            |
+-----------------------------------------------------------------------------------+
                                         │
                                         ▼
+-----------------------------------------------------------------------------------+
| [6. Phát sinh hư hỏng/bất đồng khi ở] (2-3 tháng sau - SV + Chủ)                  |
+-----------------------------------------------------------------------------------+
                                         │
                                         ▼
+-----------------------------------------------------------------------------------+
| 🔴 [7. BOTTLENECK 3: Tranh chấp, mất cọc vô lý do thiếu bằng chứng] (Vài ngày)    |
+-----------------------------------------------------------------------------------+
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1. Tìm phòng/xe | Sinh viên | Facebook, Chợ Tốt, tin dán | 2–3 chỗ / xe để xem | 2h / lần chuyển trọ hoặc mua xe | Ngoài scope tối ưu |
| 2. Thỏa thuận miệng | SV + Chủ nhà / bên bán | Phòng hoặc xe thật | Giá, cọc, điện nước, sửa chữa — **lời hứa miệng**, đôi khi Zalo | 1h / lần | Không có biên bản. Handoff sang giấy của chủ. |
| 3. Chủ nhà đưa HĐ in sẵn | Chủ nhà / bên bán | Mẫu in sẵn hoặc giấy viết tay | 1–4 trang cho SV ký | 5' | Handoff. Giấy soạn sẵn, có lợi bên đưa. |
| 4. Đọc lướt HĐ trong bối rối | Sinh viên | Giấy chữ nhỏ + trí nhớ lời nói | Cảm giác rối, không biết chỗ nào bất lợi | 10' | **Bottleneck 1.** Lép vế tâm lý, ngại hỏi. |
| 5. Không biết đàm phán, ký bừa & nộp cọc | Sinh viên | HĐ chưa khớp lời hứa miệng | Chữ ký + cọc | 10' | **Bottleneck 2.** Không biết chuyển lời miệng thành điều khoản ràng buộc. |
| 6. Phát sinh hư hỏng/bất đồng khi ở | SV + Chủ | Phòng/xe đang dùng | Khiếu nại miệng, Zalo rời | 2–3 tháng sau | Hậu quả của bước 4–5; chưa có bằng chứng đối chiếu. |
| 7. Tranh chấp, mất cọc vô lý | SV + Chủ | HĐ cũ + tin nhắn rời | SV trắng tay, mất cọc | Vài ngày | **Bottleneck 3.** Thiếu bằng chứng pháp lý bảo vệ. |

**Bottleneck chính (2-3 câu):**

```text
3 điểm nghẽn nghiêm trọng nhất nằm ở Bước 4, 5 (khâu ký kết) và Bước 7 (khâu giải quyết tranh chấp). Sinh viên bị lép vế tâm lý, không biết cách chuyển những lời hứa miệng của chủ nhà thành điều khoản pháp lý ràng buộc, dẫn đến việc ký bừa hợp đồng bất lợi. Khi xảy ra xung đột ở Bước 7, sinh viên hoàn toàn trắng tay vì không có bằng chứng pháp lý bảo vệ, chịu mất cọc và ấm ức đơn phương.
```

### 5.2. Future workflow bản nhóm

Phải nhìn ra 5 thứ: bước nào máy (Rule), bước nào AI, bước nào người, boundary ở đâu, fallback khi AI sai.

```text
+-----------------------------------------------------------------------------------+
| [1. Tìm phòng/xe] (2h - SV)                                                       |
+-----------------------------------------------------------------------------------+
                                         │
                                         ▼
+-----------------------------------------------------------------------------------+
| [2. Thỏa thuận miệng các điều khoản] (1h - SV + Chủ nhà)                          |
+-----------------------------------------------------------------------------------+
                                         │
                                         ▼
+-----------------------------------------------------------------------------------+
| ⚡ [3. AI Generate Contract từ dữ liệu nhập vào] (5' - RULE / WORKFLOW)           |
+-----------------------------------------------------------------------------------+
                                         │
                                         ▼
+-----------------------------------------------------------------------------------+
| 🤖 [4. AI Flag Risky Clause & Gợi ý câu chữ an toàn] (5' - AI)                     |
+-----------------------------------------------------------------------------------+
                                         │
                                         ▼
+-----------------------------------------------------------------------------------+
| 🛡️ [5. SV Review, tùy chỉnh & Xác nhận tự chịu trách nhiệm] (10' - HUMAN BOUNDARY)|
+-----------------------------------------------------------------------------------+
                                         │
                                         ▼
+-----------------------------------------------------------------------------------+
| [6. Ký Digital hoặc In giấy ký trực tiếp] (5' - SV + Chủ nhà)                     |
+-----------------------------------------------------------------------------------+
                                         │
                                         ▼
+-----------------------------------------------------------------------------------+
| 🔒 [7. Auto-backup HĐ: Tạo PDF + Mã băm Timestamp làm bằng chứng] (Auto - SYSTEM) |
+-----------------------------------------------------------------------------------+
                                         │
                                         ▼
+-----------------------------------------------------------------------------------+
| ⚖️ [8. AI Monitor & Hỗ trợ giải quyết khi có tranh chấp dựa trên Evidence]        |
+-----------------------------------------------------------------------------------+
```

📌 FALLBACK: Nếu chủ nhà từ chối hợp đồng số/AI tạo, SV in bản PDF ra ký giấy nhưng
vẫn lưu trữ file số có Timestamp trên hệ thống để làm căn cứ đối chiếu.

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Số bước | 7 | 8 (thêm generate, flag, backup, hỗ trợ tranh chấp) | Đếm trên sơ đồ |
| Tổng thời gian đến lúc ký | ~4.5h (2h + 1h + 5' + 10' + 10' + hậu quả sau) | ~3h25 đến lúc ký (2h + 1h + 5' + 5' + 10' + 5'); bước 7–8 chạy auto / khi phát sinh | Bấm giờ đoạn ký; không lấy “giảm giờ đi xem” làm mục tiêu |
| Số bước thủ công | 7 (toàn người) | 4 người (1, 2, 5, 6); Rule/AI/System làm 3, 4, 7, 8 | Đếm actor trên sơ đồ |
| Bottleneck chính | Bước 4–5 ký bừa + bước 7 trắng tay | Bước 5: SV review & tick tự chịu trách nhiệm (HUMAN BOUNDARY) | Quan sát pilot |
| Risk mới | Ký mù, không có bằng chứng | AI generate/flag sai → SV vẫn ký nếu không review | Checkbox xác nhận + disclaimer đỏ; fallback in PDF nếu chủ từ chối HĐ số |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên và người trẻ (18-30 tuổi) thuê phòng trọ hoặc mua/bán xe máy cũ lần đầu. Họ không có kinh nghiệm, không hiểu pháp lý, tin tưởng chủ nhà/bên bán, sợ hỏi nhiều bị từ chối thuê/bán. |
| **Workflow** | Tìm phòng/xe → thỏa thuận miệng điều kiện + giá → ký hợp đồng (miệng hoặc giấy bừa, không rõ clause) → nộp cọc → vào ở/nhận xe → vài tháng sau bị chủ nhà/bên bán yêu cầu bù lỗi hỏng hóc không công bằng (ví dụ: "cọc mất 30%", "điện 500k dù dùng 2 tháng", "xe bị trầy nhỏ tính 2M"). |
| **Bottleneck** | Bước ký hợp đồng: SV không biết cách chuyển thỏa thuận miệng thành điều khoản pháp lý bảo vệ họ. Không có template, không biết cần ghi gì, không biết cách negotiate/defend điều khoản bất lợi. Khi tranh chấp, không có chứng cứ rõ ràng → thua đơn phương. |
| **Impact** | 68% SV từng bị mất cọc hoặc chịu chi phí vô lý (avg loss 850k). Mất 1-2h đọc hợp đồng hoang mang, không hiểu. Sau này bị tranh chấp, không có evidence → 100% mất tiền. Confidence vào pháp lý: 20%. |
| **Success Metric** | Trước: 30% mất cọc (avg 850k), 1-2h stress reading contract, 20% confidence vào contract. Sau: <5% mất cọc, <10 phút AI generate contract, >80% confidence. Cách đo: survey SV after pilot (mất cọc rate), bấm giờ (time to sign), Likert scale (confidence). |
| **Boundary** | AI chỉ giúp generate contract từ template + flag risky clause + suggest safe alternative (education role). AI KHÔNG replace lawyer (không đưa legal advice chuyên sâu). AI KHÔNG đàm phán thay SV (SV phải quyết định). Disclaimer rõ: "Không phải legal advice, hãy xem xét kỹ trước ký". |

**Câu hỏi AI phản biện v0 (nếu có):**
- Field nào mơ hồ:
  - Workflow: Ai là "chủ nhà/bên bán" cụ thể? Có API/platform nào để giao tiếp không hay thuần offline?
  - Boundary: Nếu AI generate sai clause → SV ký → chịu hậu quả ai? Trách nhiệm pháp lý thuộc về ai?
- Tôi sửa gì:
  - Workflow: Làm rõ là giao tiếp offline/Zalo giữa SV và chủ nhà/bên bán cá nhân. Không phụ thuộc API bên thứ ba. SV nhập các thỏa thuận miệng vào form/chat.
  - Boundary: Thêm cơ chế: SV phải tick checkbox xác nhận "Tôi đã đọc và tự chịu trách nhiệm về hợp đồng này" trước khi xuất file. Bổ sung disclaimer nổi bật màu đỏ: "Văn bản hỗ trợ tham khảo, không thay thế tư vấn pháp lý chuyên nghiệp".

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [x] **Cao** (nhiều cách viết câu vẫn được) — Vì sao: “bác hỗ trợ điều hòa”, “điện tính rẻ”, “xe bao êm” không có một câu điều khoản đúng duy nhất; AI generate / flag cũng có nhiều cách diễn đạt chấp nhận được.
- Độ phức tạp: [x] **Cao** (3+ bước, bước sau phụ thuộc bước trước) — Vì sao: nhập thỏa thuận miệng → Rule ráp template → AI generate HĐ → AI flag + gợi ý câu an toàn → người review / tick trách nhiệm → ký → backup PDF+timestamp → khi tranh chấp mới mở evidence. Một đường cố định, máy không tự chọn bước tiếp.

**Bài toán nhóm nằm ở ô nào:**

```text
Mơ hồ cao × phức tạp cao → dễ nghĩ tới Agent, nhưng nhóm chọn
Workflow: đường đi cố định, AI chỉ hai bước ngôn ngữ (generate + flag),
người giữ boundary và chữ ký. Không phải ô Agent.
```

**Vì sao (2-3 câu):**

```text
Cần LLM để biến khẩu ngữ / tin Zalo thành điều khoản và chỉ ra câu
rủi ro. Các bước nối nhau đã vẽ sẵn ở Phase 5 (8 bước), không cần máy
tự lập kế hoạch. Ký, đàm phán với chủ, chịu trách nhiệm pháp lý vẫn
thuộc người. Agent (tự nhắn chủ, tự ký, tự “cố vấn kiện”) vừa thừa vừa nguy.
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **No AI / Rule** | Khung hợp đồng tinh gọn (học mẫu Thư viện Pháp luật nhưng cắt 8–10 ô: cọc, hạn trả, báo trước, điện, nước, ai sửa, tình trạng) + checklist in sẵn. SV tự điền và tự đưa chủ. | Đủ nếu SV biết viết điều khoản từ lời miệng và chủ chịu ký mẫu của SV. | Không đọc được khẩu ngữ (“bác sửa điều hòa”) thành câu ràng buộc; SV mệt là bỏ, lại ký giấy chủ đưa. | **Có — xương sống bước 3 (template) và fallback.** Không đủ một mình. |
| **Workflow** | SV nhập thỏa thuận miệng / Zalo vào form → Rule ráp template → AI generate HĐ → AI flag điều khoản rủi ro + gợi ý câu an toàn → SV review, sửa, tick “tôi đã đọc và tự chịu trách nhiệm” → xuất PDF → ký số hoặc in giấy → hệ thống lưu PDF + mã băm/timestamp. Khi tranh chấp: SV tự mở file evidence, AI trích điều khoản liên quan (người hỏi, máy không tự kiện). | Đủ: một đường như Phase 5; AI chỉ bước 3–4 (và 8 khi người bật). Không cần API sàn / chủ nhà. | AI generate/flag sai → SV vẫn ký nếu không đọc. Chặn bằng HUMAN BOUNDARY (bước 5) + disclaimer đỏ + fallback in PDF. | **Chọn làm mức chính.** |
| **Agent** | Máy tự chat với chủ, tự đàm phán, tự ký, tự theo dõi tranh chấp và tự gửi đòi quyền. | Chỉ khi có ủy quyền pháp lý và chủ chịu nói chuyện với máy — không có trong bài này. | Mất lòng chủ; tư vấn luật trái phép; thiệt hại đổ về SV. Đúng nỗi lo của Xuân Huy ở Phase 3. | **Không chọn.** |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. Rule có giải được 70-80% case không? **Một phần:** đủ để có khung ô trống (cọc, điện, báo trước). **Không đủ** 70–80% case có lời hứa riêng (điều hòa, 30 ngày vs 45 ngày, “bao êm”) — đúng chỗ Duy, Hoàng, Xuân Huy kể. Cần AI để viết / flag câu đó.
2. Các bước có đi thẳng một đường không hay phải rẽ nhánh? **Thẳng** theo Phase 5: nhập → generate → flag → review → ký → backup. Rẽ nhẹ: chủ nhận HĐ số hoặc bắt in giấy — người rẽ (fallback), máy không lập kế hoạch.
3. Có thật sự cần Agent tự lập kế hoạch + gọi tool không? **Không.** Nhắn chủ, quyết ký, mở tranh chấp là việc của sinh viên. Bước 8 chỉ chạy khi SV chủ động đưa sự việc + file HĐ đã lưu.
4. Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu? Sinh viên ở bước 5: đọc HĐ, sửa câu, bỏ flag sai (~10'). Không tick checkbox thì không xuất file. QA nhóm soi 8–10 bộ mẫu. Disclaimer đỏ: văn bản tham khảo, không thay tư vấn pháp lý.
5. Có hạ được từ Agent → Workflow → Rule không? **Có.** Tắt AI thì còn template + checklist 8–10 ô (No AI / Rule). Không bao giờ nâng lên Agent trong scope này.

**Mức chọn:**

```text
Workflow
(Rule = template + checklist ô trống + PDF/timestamp;
AI = generate HĐ từ dữ liệu nhập + flag clause + gợi ý câu an toàn;
người = review, tick trách nhiệm, tự ký / tự đưa chủ)
```

**Vì sao chọn (3-4 câu):**

```text
Rule không biến lời miệng thành điều khoản. Agent đàm phán / ký hộ thì
đúng nỗi lo pháp lý của Xuân Huy. Workflow khớp Phase 5 và research
Phase 4: nhập thỏa thuận → ráp khung → flag bẫy → xuất PDF có bằng
chứng; không làm DocuSign, không làm luật sư B2B. Sinh viên vẫn là
người đọc, người ký, người chịu chữ ký của mình.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Template / checklist in sẵn đáng làm trước và luôn là fallback — nhóm
không giả vờ “không có cách non-AI”. Chỉ Rule thì trượt đúng case
interview: lời một đằng, giấy chủ một nẻo, SV không biết viết câu
bảo vệ. AI thêm đúng hai bước ngôn ngữ, không thay tờ template.
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên / người trẻ (18–30) thuê phòng trọ hoặc mua xe máy cũ lần đầu từ **chủ nhà / bên bán cá nhân**, giao tiếp offline hoặc Zalo — không phụ thuộc API sàn hay app của chủ. Không gồm thuê người thân (case Lương) và không gồm hợp đồng công ty môi giới (case Định). Họ ít kinh nghiệm pháp lý, sợ hỏi nhiều thì bị từ chối. |
| **Workflow** | **Hiện tại (7 bước, ~4.5 giờ):** tìm → thỏa thuận miệng → nhận HĐ in sẵn → đọc lướt bối rối → ký bừa + nộp cọc → vài tháng sau hỏng đồ / bất đồng → tranh chấp trắng tay vì thiếu bằng chứng. **Muốn có (8 bước):** tìm + nói miệng giữ nguyên → SV nhập thỏa thuận vào form/chat → AI generate HĐ từ template → AI flag clause rủi ro + gợi ý câu an toàn → SV review, sửa, tick tự chịu trách nhiệm → ký digital hoặc in giấy → auto lưu PDF + mã băm/timestamp → khi tranh chấp, SV mở evidence, AI hỗ trợ đối chiếu điều khoản (không tự kiện). |
| **Bottleneck** | Bước 4–5 (ký kết): SV không biết chuyển lời hứa miệng thành điều khoản ràng buộc, không có template vừa túi, không biết negotiate / defend câu bất lợi nên ký bừa. Bước 7: khi xung đột thì không có bằng chứng → thua đơn phương. |
| **Impact** | Evidence nhóm: Duy (lời sửa điều hòa vs giấy “bên thuê chịu bảo trì”); Hoàng (Zalo 30 ngày vs giấy 45 ngày / mất cọc); Xuân Huy (xe “êm”, giấy không bảo hành, bị chặn). Mục tiêu v0 giữ để theo dõi sau pilot: giảm mất cọc vô lý và thời gian đọc hoang mang 1–2h. Số 68% / 850k là giả định từ card ban đầu — **chưa khảo sát ngoài nhóm**, không dùng làm baseline lab. |
| **Success Metric** | **Lab (đo tuần này):** (1) <10 phút từ lúc nhập thỏa thuận xong đến bản HĐ + flag dùng được; (2) Likert “tôi hiểu mình sắp ký gì / biết chỗ rủi ro” ≥ 4/5 (mục tiêu >80% người pilot ≥4); (3) 100% file xuất ra có checkbox đã tick + disclaimer đỏ. **Sau pilot (survey, không đo trong 4 giờ lab):** tỷ lệ mất cọc / chi phí vô lý — mục tiêu hướng tới <5% so với cảm nhận “hay mất cọc” hiện tại; chưa claim 30% → 5% cho đến khi có poll ngoài nhóm. |
| **Boundary** (làm / không làm) | **Làm:** generate HĐ từ template + dữ liệu SV nhập; flag risky clause; gợi ý câu an toàn (vai trò giáo dục); xuất PDF; lưu timestamp/mã băm làm bằng chứng; disclaimer đỏ. **Không làm:** thay luật sư / đưa legal advice chuyên sâu; đàm phán hoặc nhắn chủ hộ; khẳng định “HĐ này hợp pháp / đủ kiện”; tự theo dõi hay tự giải tranh chấp; nền tảng ký số kiểu DocuSign. Trước khi xuất file, SV **bắt buộc** tick: “Tôi đã đọc và tự chịu trách nhiệm về hợp đồng này.” |
| **AI intervention point** | **Sau** thỏa thuận miệng / Zalo đã có, **trước** khi ký và nộp cọc — bước 3–4. Bước 8 chỉ khi SV chủ động mở vụ việc + file đã backup. Không đụng bước tìm phòng/xe. |
| **Mức chọn** | **Workflow** — vì cần AI ở hai bước ngôn ngữ, đường đi cố định, người giữ chữ ký và trách nhiệm. |
| **Rủi ro & người thật kiểm tra** | Rủi ro lớn nhất: AI generate/flag sai → SV vẫn ký và **tưởng mình đã được bảo vệ**. Kiểm: bước 5 bắt buộc review + tick; disclaimer “Văn bản hỗ trợ tham khảo, không thay thế tư vấn pháp lý chuyên nghiệp”; QA soi 8–10 bộ mẫu. Nếu 3 bộ liên tiếp ra điều khoản sai trọng (đổi nghĩa cọc / điện / ai sửa) → tắt generate, chỉ còn Rule template + checklist. |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | Yes | Actor: SV / người trẻ giao dịch offline hoặc Zalo với chủ / bên bán cá nhân. Current 7 bước ~4.5h; future 8 bước — Rule/AI/người/boundary/fallback đã vẽ ở Phase 5. |
| Baseline + metric đo được chưa? | Not Yet / Yes tách | **Yes:** phút generate+flag, Likert confidence, checkbox/disclaimer — đo được trong lab. **Not Yet:** 68% / 850k / “30% → 5% mất cọc” — cần survey ngoài nhóm, chưa đủ 4 người kể chuyện. |
| Data/input đủ dùng chưa? | Yes (pilot) | 5–8 ý đã nói (hoặc đoạn Zalo) + các ô template (cọc, hạn, điện, ai sửa…) là chạy tay được. Không cần API chủ nhà. |
| AI sai, hậu quả chấp nhận được không? | Yes, có điều kiện | Chấp nhận nếu không xuất file khi chưa tick, có disclaimer đỏ, và AI không được nói “nên ký / đủ kiện”. Không chấp nhận nếu coi checkbox là “đã hiểu hết luật”. Trách nhiệm pháp lý thuộc SV (đã tick), không thuộc máy. |
| Có người review/owner không? | Yes | SV là reviewer/owner chữ ký (bước 5–6). QA nhóm soi bộ mẫu. Chủ nhà không phải user của máy. |
| Có cách non-AI đơn giản hơn không? | Yes — một phần | Template + checklist 8–10 ô giải “thiếu ô”. Không giải “lời miệng → câu chữ bảo vệ” — đó là chỗ còn lại cho AI. |

**Decision:**

```text
Go với scope nhỏ.
(Pilot: nhập thỏa thuận → generate HĐ + flag → người review → xuất PDF;
không Go nền tảng ký số / luật sư AI / Agent đàm phán.)
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
Phase 5 chốt nghẽn ở bước 4–5 (ký bừa) và bước 7 (trắng tay vì thiếu
bằng chứng). Research: đừng làm DocuSign, đừng làm Robin AI B2B — chỉ
lấy generate từ template + flag + PDF/timestamp. Phản biện v0 đã vá
hai lỗ: kênh offline/Zalo, không API; checkbox + disclaimer đỏ để
trách nhiệm không đổ lên máy. Metric lab là phút + Likert + tick;
số mất cọc để dành survey sau, không bịa từ mẫu nhóm.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
- Data: 8–10 bộ (5–8 ý thỏa thuận miệng hoặc tin Zalo thuê trọ; che tên
  địa chỉ). 1–2 bộ xe cũ nếu có, không bắt buộc.
- Chạy tay: dán vào prompt cố định trên Claude/Gemini (không build app)
  → ra HĐ từ template + danh sách clause rủi ro + câu thay thế.
  SV đọc, sửa, tick “đã đọc và tự chịu trách nhiệm”, xuất PDF.
  QA xóa / đánh dấu mọi câu generate không bám dữ liệu đã nhập.
  Fallback giả lập: chủ từ chối HĐ số → in PDF, vẫn giữ file có timestamp.
- Đo 3 số: (1) phút từ lúc nhập xong đến HĐ+flag dùng được (mục tiêu <10');
  (2) Likert 1–5 “tôi hiểu chỗ rủi ro trước khi ký” (mục tiêu ≥4);
  (3) % bộ mẫu xuất được chỉ sau khi đã tick + có disclaimer (mục tiêu 100%).
```

**Nếu Not Yet — cần validate gì trước:**

```text
Nếu 3 bộ mẫu liên tiếp AI đổi nghĩa cọc / điện / ai sửa: cấm bước
generate, chỉ còn Rule template.
Nếu muốn claim 68% / 850k / “mất cọc <5%”: hỏi thêm ít nhất 5–10
người ngoài nhóm, giữ screenshot poll; chưa có thì không ghi như
baseline đã đo.
Nếu output bị hiểu nhầm là “tư vấn luật”: siết disclaimer và hạ
Decision xuống Not Yet đến khi câu chữ trên UI đủ rõ.
```

**Nếu No-Go — làm gì thay AI:**

```text
In 1 tờ template 8–10 ô (cọc, báo trước, điện, nước, ai sửa, tình
trạng) + 5 câu Zalo mẫu để SV tự điền / tự gửi chủ. Phát trong
nhóm / lớp. Không cần model.
```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
- 3 bộ mẫu liên tiếp: generate/flag sai trọng (đổi nghĩa điều khoản
  tiền) → tắt AI, giữ template + checklist.
- Pilot thật: chủ từ chối “hợp đồng máy soạn” → fallback Phase 5:
  in PDF ký giấy, vẫn lưu file số có timestamp để đối chiếu.
- User hỏi “em kiện được không / điều này phạm luật không” → từ chối,
  ngoài boundary; đưa về đọc lại câu trên HĐ và hỏi người lớn / trợ
  giúp pháp lý nếu họ muốn.
- Không đủ 1 bộ thỏa thuận miệng + các ô template trong tuần → chuyển
  đào sâu sang bài dự phòng #11 lỗ hổng kiến thức sau đề (1 đề 20 câu,
  Lab = 5).
```

---

### Self-check nộp phần 02 (nhóm)
- [x] Có nhật ký hội tụ 9-12 → 1 (cluster theo workflow; shortlist 3; hòa 32–32 rồi phá hòa)
- [x] Có validation (hỏi 4 thành viên trong nhóm + giơ tay 6/6) + research (link mở được). Số 68%/850k để ở v0 / mục tiêu sau survey, **không** dùng làm baseline lab.
- [x] Có workflow trước/sau khớp Phase 5: 7 bước ~4.5h → 8 bước; Rule / AI / người / boundary / fallback in PDF+timestamp
- [x] Có PS v0 → v1; v1 vá kênh offline/Zalo + checkbox trách nhiệm + disclaimer; metric lab có trước/sau + cách đo
- [x] Có No AI–Rule / Workflow / Agent + Decision Go scope nhỏ, có điều kiện tắt AI / hạ về template
