# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Nguyễn Thái Lương
- Mã học viên: 2A202602932
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Sinh viên năm 4 ngành Kỹ thuật Cơ điện tử / Robot & Hệ thống nhúng (đang làm đồ án tốt nghiệp thiết kế cơ khí và lập trình phần cứng).
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
  - Tra cứu tài liệu kỹ thuật, datasheet và catalog linh kiện cơ khí - điện tử tiêu chuẩn từ các nhà sản xuất (Misumi, HIWIN, THK) để chọn mã và dựng mô hình lắp ráp 3D trên CAD (SolidWorks/Inventor).
  - Lập trình firmware điều khiển ngoại vi (I2C, SPI, UART, Timer, PWM) trên vi điều khiển STM32/ESP32 bằng C/C++ và debug các lỗi biên dịch hoặc lỗi treo vi điều khiển (HardFault).
  - Họp nhóm đồ án tốt nghiệp hằng tuần, phân chia khối lượng công việc, rà soát tiến độ và tổng hợp báo cáo tuần gửi giảng viên hướng dẫn.
  - Tự học thêm ngoại ngữ (tiếng Anh kỹ thuật), đọc các bài báo nghiên cứu (IEEE/ScienceDirect) và tạo thẻ Flashcard để ôn tập thuật ngữ chuyên ngành.
  - Quản lý chi tiêu sinh hoạt cá nhân qua tài khoản ngân hàng và định kỳ dọn dẹp, sắp xếp tài liệu học tập, bài giảng trong thư mục Downloads trên máy tính cá nhân.

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Lặp lại | Đọc datasheet (40–80 trang) để dò cấu hình thanh ghi, địa chỉ giao tiếp I2C/SPI và tính toán bitmask | Lập trình viên firmware nhúng, sinh viên làm đồ án phần cứng/robotics | Bấm giờ 3 lần gần nhất mất 35–55 phút/IC; đồ án có 4 cảm biến mất gần 3 tiếng lật PDF dò từng thanh ghi; từng nhầm 1 bit cấu hình I2C thanh ghi `0x0B` trên cảm biến MPU6050 làm mất thêm 4 tiếng đo xung bằng Logic Analyzer để tìm lỗi. |
| 2 | Tốn thời gian | Tìm kiếm và đối chiếu linh kiện cơ khí tiêu chuẩn (vít me bi, ray trượt, khớp nối) từ catalog PDF của nhà sản xuất | Sinh viên thiết kế đồ án cơ điện tử, kỹ sư thiết kế CAD máy | Bấm giờ tra cứu vít me bi HIWIN mất 45–75 phút/cụm; lật tài liệu catalog 200+ trang đối chiếu bước ren, tải trọng động C0 và khoảng cách tâm lỗ; từng đặt mua nhầm mã phụ tùng lệch bước ren 5mm sang 10mm làm chậm tiến độ lắp ráp 4 ngày chờ đổi trả. |
| 3 | AI có thể tốt hơn | Chẩn đoán lỗi biên dịch tầng thấp và xung đột tài nguyên bộ nhớ (linker script, register conflict, runtime HardFault) | Người lập trình C/C++/Assembly trên hệ thống nhúng (STM32, ARM Cortex-M) | Gặp 2–3 lần/tuần; trình biên dịch (GCC/Keil) chỉ báo thông điệp vắn tắt `region 'RAM' overflowed by 248 bytes` hoặc rơi vào ngắt `HardFault_Handler`; mất 25–45 phút mở file `.map` và tra Google/ST Community để tìm hàm gây tràn bộ nhớ stack. |
| 4 | Lặp lại | Phân loại biên lai hóa đơn và sao kê giao dịch ngân hàng để ghi chép chi tiêu sinh hoạt cá nhân | Sinh viên, người sống tự lập cần quản lý tài chính | Bấm giờ tối Chủ nhật mất 25–35 phút/tuần; phải mở 15–20 ảnh chụp màn hình giao dịch chuyển khoản (Vietcombank, MBBank) để gõ lại số tiền, ngày tháng, nội dung vào Google Sheets; thường bị nản lòng và bỏ dở sau 2 tuần ghi chép. |
| 5 | Pain từ người khác | Thành viên mới trong nhóm đồ án liên tục hỏi lại cùng một quy trình cài đặt toolchain và thiết lập môi trường build | Trưởng nhóm kỹ thuật, thành viên mới tham gia dự án | Bị hỏi lặp lại 3–4 lần/học kỳ từ 2 thành viên mới; mỗi lần mất 15–20 phút mở Discord/TeamViewer hướng dẫn lại cách clone repo Git, cài đặt toolchain ARM-GCC và cấu hình biến môi trường PATH trên Ubuntu/WSL. |
| 6 | Tốn thời gian | Tự trích xuất từ vựng chuyên ngành và tạo bộ thẻ Flashcard ngữ cảnh từ tài liệu nghiên cứu tiếng Anh | Sinh viên tự học tiếng Anh kỹ thuật, người ôn thi chứng chỉ TOEIC/IELTS | Bấm giờ mỗi cuối tuần mất 50–65 phút; khi đọc 1 bài báo IEEE có khoảng 20 thuật ngữ mới; phải copy từng từ sang từ điển tra cứu, copy câu văn ngữ cảnh gốc và dán mặt trước/sau vào phần mềm Anki, làm đứt gãy mạch đọc hiểu tài liệu. |
| 7 | AI có thể tốt hơn | Thiếu phản hồi chi tiết về độ chính xác của phụ âm cuối và ngữ điệu câu khi tự luyện phát âm tiếng Anh | Người tự luyện kỹ năng nói tiếng Anh kỹ thuật để thuyết trình đồ án | Luyện nói 30 phút/ngày; ghi âm trên điện thoại nghe lại nhưng không tự nhận biết được sai ở phụ âm cuối (`/s/`, `/t/`, `/ed/`) hay trọng âm từ; phải chờ đến buổi học phụ đạo với trợ giảng (1 lần/tuần) mới được sửa lỗi. |
| 8 | Lặp lại | Dọn dẹp thư mục Downloads bị dồn ứ và phân loại thủ công các tệp tài liệu môn học | Sinh viên, người học trực tuyến thường xuyên tải tài liệu từ mạng | Cuối mỗi tuần thư mục Downloads tích tụ 30–45 tệp tin hỗn độn (`document_final_1.pdf`, `slide_c3.pptx`, file nén zip); mất 15–20 phút bấm mở từng file để xem nội dung trang đầu rồi mới kéo thả vào đúng thư mục môn học tương ứng. |
| 9 | Pain từ người khác | Bàn giao (handoff) bản vẽ CAD 2D sang xưởng gia công cơ khí bị thiếu kích thước dung sai hoặc không phù hợp quy chuẩn chế tạo | Người thiết kế CAD, thợ tiện/phay tại xưởng gia công | Xưởng gia công gọi điện hoặc nhắn tin hỏi lại 2–3 lần/bản vẽ vì thiếu dung sai lắp ghép trục-lỗ (H7/g6) hoặc thiếu chỉ dẫn độ nhám bề mặt (Ra); phát sinh thêm 30–60 phút mở mô hình CAD sửa lại và làm chậm tiến độ giao nhận chi tiết máy 1–2 ngày. |
| 10 | Tốn thời gian | Tổng hợp báo cáo tiến độ đồ án tuần từ commit log trên Git, tin nhắn nhóm và nhật ký thử nghiệm phần cứng | Trưởng nhóm đồ án môn học / đồ án tốt nghiệp | Mất 50–70 phút mỗi tối thứ Bảy; phải lục lại 10–15 commit trên GitHub, tin nhắn trao đổi trên nhóm Zalo và ảnh chụp kết quả đo kiểm mạch điện để viết báo cáo tiến độ 2 trang nộp cho giảng viên hướng dẫn. |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: "Tôi là sinh viên năm cuối ngành Kỹ thuật Cơ điện tử và Hệ thống nhúng. Công việc hằng tuần gồm thiết kế mô hình CAD 3D, tra cứu catalog linh kiện, lập trình vi điều khiển STM32, họp nhóm đồ án và tự học ngoại ngữ. Hãy gợi ý thêm các bài toán thực tế theo 4 lăng kính: Lặp lại, Tốn thời gian, AI có thể tốt hơn, Pain từ người khác. Với mỗi bài toán, yêu cầu ghi rõ actor cụ thể, workflow sơ bộ và dấu hiệu đo lường bằng số liệu thật, không đưa ý tưởng viển vông."
- Ý dùng được: AI gợi ý thêm góc nhìn sâu về sự lãng phí thời gian khi đối chiếu chéo các bảng thông số catalog linh kiện cơ khí chuẩn (Problem #2) và việc chẩn đoán log lỗi compiler/hardfault nhúng (Problem #3) – đây là những điểm nghẽn thực tế gây ức chế nhất trong tuần làm việc kỹ thuật.
- Ý bỏ vì không phải pain thật: AI đề xuất "tự động hóa toàn bộ việc dựng khung máy CAD từ text prompt" và "tự động sinh toàn bộ code firmware nhúng từ mô tả". Tôi đã loại bỏ ngay vì đây là các đề xuất phi thực tế, thiếu tính khả thi kỹ thuật, bỏ qua các ràng buộc vật lý và không có quy trình kiểm soát sai số cụ thể.

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể (đã scan đủ 10 dòng có số liệu thật)
- [x] Dùng ít nhất 3/4 lăng kính (bao phủ đủ cả 4/4 lăng kính)
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian" (mọi dòng đều có thời gian bấm giờ, tần suất và hậu quả cụ thể)

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | **#2 — Đối chiếu catalog linh kiện cơ khí tiêu chuẩn từ nhà sản xuất** | Tác động trực tiếp đến tiến độ đồ án cơ điện tử/CAD; tốn nhiều giờ lật bảng tra thông số ma trận dày đặc; ranh giới đối chiếu kiểm chứng (human boundary) rất rõ ràng trước khi đưa vào bản vẽ. | Khả năng mô hình AI đọc hiểu đúng bảng dung sai ma trận, bản vẽ kích thước và các ký hiệu mã biến thể (suffix/prefix) phức tạp trong catalog PDF. |
| 2 | **#4 — Phân loại và số hóa chi tiêu từ ảnh chụp giao dịch** | Dữ liệu đầu vào rất rõ ràng (ảnh chụp màn hình biên lai chuyển khoản ngân hàng); workflow ngắn gọn; impact đo được ngay bằng thời gian tiết kiệm thực tế (từ 30' xuống < 5'). | Độ chính xác của OCR/Vision AI khi gặp ảnh chất lượng thấp, ảnh bị mờ hoặc các ngân hàng thay đổi giao diện ứng dụng. |
| 3 | **#8 — Tự động phân loại tài liệu thư mục Downloads** | Vấn đề xảy ra hàng tuần với tần suất lặp lại cao; dữ liệu đầu vào đa dạng (PDF, zip, docx, ảnh); là bài toán tiêu biểu để so sánh rõ nét giữa việc dùng Rule (script lọc đuôi file) và AI (phân loại theo ngữ cảnh môn học/đồ án). | Khả năng phân loại sai nếu tài liệu có tiêu đề hoặc nội dung trang đầu quá sơ sài, hoặc nguy cơ di chuyển nhầm các tệp tin cá nhân nhạy cảm. |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Đối chiếu catalog linh kiện cơ khí tiêu chuẩn (Ý tưởng #2)

```text
Problem 1 câu:
Người thiết kế đồ án cơ điện tử mất 40–90 phút cho mỗi cụm lắp ráp để lật catalog PDF hàng trăm trang nhằm tra cứu kích thước lắp ghép, bước ren và tải trọng của linh kiện tiêu chuẩn.

Actor:
Sinh viên làm đồ án tốt nghiệp cơ điện tử / kỹ sư thiết kế máy (CAD engineer).

Thời điểm / bối cảnh:
Giai đoạn tính toán chọn linh kiện tiêu chuẩn (vít me bi, ray trượt, khớp nối, động cơ bước) để đưa thông số vào mô hình lắp ráp 3D trên CAD.

Current workflow 3-7 bước:
1. Xác định yêu cầu kỹ thuật sơ bộ (hành trình, tải trọng làm việc, không gian bao).
2. Mở file PDF catalog của hãng sản xuất (HIWIN, Misumi, THK) dài 200–400 trang.
3. Lật từng trang tra cứu bảng dữ liệu kích thước hình học và bảng tải trọng tương ứng.
4. Đối chiếu chéo giữa các thông số lắp đặt (đường kính trục, bước ren, khoảng cách lỗ bắt ốc) với không gian kết cấu máy.
5. Chốt mã định danh chi tiết (part number đầy đủ kèm suffix) và nhập kích thước vào mô hình CAD 3D.

Bottleneck:
Bước 3 và 4 (mất 30–45 phút) — việc tra cứu thủ công qua các bảng dữ liệu ma trận dày đặc rất dễ hoa mắt, nhầm lẫn giữa các dòng mã hiệu tương đương.

Impact:
Mất khoảng 60–90 phút cho mỗi linh kiện; nếu tra nhầm mã hoặc thông số (ví dụ nhầm bước ren 5mm thành 10mm), chi tiết mua về sẽ không lắp vừa khung máy, phát sinh chi phí gia công lại và làm chậm tiến độ dự án 3–5 ngày.

Success metric:
Giảm thời gian tìm và đối chiếu thông số từ 60 phút xuống dưới 12 phút/cụm; độ chính xác về mã định danh và thông số lắp ghép đạt 100% sau bước kiểm tra lại.

Non-AI alternative:
Dùng công cụ lọc trực tuyến của nhà sản xuất (Configurator) hoặc file Excel tổng hợp sẵn (nhược điểm: nhiều catalog nội địa hoặc file PDF cũ không có bộ lọc web tương tác; web configurator yêu cầu nhập quá nhiều trường phân cấp rời rạc).

AI hypothesis:
Mô hình tiếp nhận yêu cầu ràng buộc kỹ thuật dạng văn bản, tra cứu trên cấu trúc bảng dữ liệu của catalog PDF và trích xuất bảng đối chiếu, đề xuất 2–3 mã linh kiện phù hợp nhất kèm trích dẫn số trang gốc để kỹ sư quyết định.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 60 phút

[1 Xác định tải & hành trình: 10']
→ [2 Mở PDF catalog 200+ trang: 5']
→ [3 Dò tìm bảng kích thước: 25']  <-- bottleneck
→ [4 Đối chiếu chéo thông số: 15']  <-- bottleneck
→ [5 Chốt mã & nhập vào CAD: 5']

FUTURE STATE — 12 phút

[1 Nhập ràng buộc thông số vào hệ thống: 2']
→ [2 Workflow AI quét bảng catalog & gợi ý 2-3 mã phù hợp: 1']
→ [3 Kỹ sư đối chiếu lại thông số với bản vẽ gốc & trang PDF: 7']  <-- human boundary
→ [4 Chốt mã & tải file CAD: 2']

Fallback: AI trích xuất sai dòng biến thể → Kỹ sư dùng lại số trang PDF mà hệ thống đính kèm để mở trực tiếp trang catalog gốc kiểm tra.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Phân loại & số hóa chi tiêu từ ảnh chụp giao dịch (Ý tưởng #4)

```text
Problem 1 câu:
Người quản lý tài chính cá nhân mất 20–30 phút mỗi tuần mở từng ảnh chụp màn hình xác nhận giao dịch ngân hàng để nhập liệu thủ công và phân loại vào sổ theo dõi chi tiêu.

Actor:
Sinh viên, người sống tự lập cần kiểm soát chi tiêu định kỳ.

Thời điểm / bối cảnh:
Tối Chủ nhật hàng tuần khi ngồi rà soát lại biến động số dư và ngân sách sinh hoạt trong tuần.

Current workflow 3-7 bước:
1. Gom toàn bộ ảnh chụp giao dịch, biên lai chuyển tiền trong tuần vào một album ảnh.
2. Mở bảng tính quản lý chi tiêu (Google Sheets / Excel).
3. Mở từng ảnh để đọc các trường: số tiền, người nhận, thời gian và nội dung chuyển khoản.
4. Nhập thủ công từng trường thông tin vào đúng các cột trên bảng tính.
5. Đọc nội dung giao dịch để suy nghĩ và gán nhãn danh mục (Ăn uống, Tiền trọ, Mua sắm linh kiện, Học tập).

Bottleneck:
Bước 4 và 5 (mất 15–20 phút) — việc nhìn qua lại giữa màn hình ảnh và bảng tính để gõ số gây mỏi mắt, dễ nản lòng và thường bị bỏ dở giữa chừng.

Impact:
Tốn khoảng 30 phút/tuần; việc ngại nhập liệu dẫn đến tình trạng dồn ứ dữ liệu cả tháng, thất thoát ghi chép và mất kiểm soát tài chính cá nhân.

Success metric:
Giảm thời gian tổng hợp chi tiêu từ 30 phút xuống dưới 5 phút mỗi tuần; dữ liệu được cập nhật đều đặn 100% không bỏ sót giao dịch.

Non-AI alternative:
Dùng ứng dụng ghi chép chi tiêu sẵn có trên điện thoại yêu cầu nhập tay ngay lúc vừa chi tiêu (nhược điểm: lúc mua hàng bận rộn thường quên mở app ra gõ; sao kê ngân hàng cuối tháng không có ghi chú rõ từng khoản).

AI hypothesis:
Mô hình OCR kết hợp Vision LLM tự động trích xuất các trường thông tin (Số tiền, Ngày, Nội dung, Đơn vị thụ hưởng) từ ảnh và dựa vào nội dung giao dịch để tự động phân loại danh mục, xuất thẳng ra dòng dữ liệu có cấu trúc.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 30 phút

[1 Gom ảnh chụp màn hình: 3']
→ [2 Mở file bảng tính: 2']
→ [3 Mở từng ảnh để đọc: 5']
→ [4 Nhập tay từng số tiền, ngày tháng: 10']  <-- bottleneck
→ [5 Suy nghĩ phân loại danh mục: 10']        <-- bottleneck

FUTURE STATE — 4 phút

[1 Tải hàng loạt ảnh giao dịch vào luồng: 1']
→ [2 OCR trích xuất số & LLM tự động phân loại danh mục: 1']
→ [3 Người dùng rà soát nhanh bảng dữ liệu đã cấu trúc: 2']  <-- human boundary

Fallback: Ảnh chụp chất lượng kém không đọc được → Hệ thống gắn cờ để người dùng tự gõ tay bổ sung giao dịch đó.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Tự động phân loại tài liệu thư mục Downloads (Ý tưởng #8)

```text
Problem 1 câu:
Người dùng máy tính để thư mục Downloads dồn ứ hàng chục tệp tin không tên hoặc đặt tên mặc định, mất 15–20 phút mỗi tuần mở từng file để xem nội dung rồi phân loại về đúng folder môn học/đồ án.

Actor:
Sinh viên, người làm việc nhiều với tài liệu học tập và đồ án trực tuyến.

Thời điểm / bối cảnh:
Định kỳ cuối tuần hoặc khi chuẩn bị nộp bài tập mà không tìm thấy tệp tài liệu vừa tải về từ web/LMS.

Current workflow 3-7 bước:
1. Mở thư mục Downloads chứa 30–50 tệp tin hỗn độn (PDF, zip, ảnh, docx, code).
2. Bấm mở từng tệp để đọc nhanh trang đầu tiên nhằm xác định nội dung là gì.
3. Xác định tài liệu này thuộc môn học, đề tài nghiên cứu hoặc mục đích cá nhân nào.
4. Đổi tên tệp cho dễ hiểu (nếu tên tệp ban đầu là chuỗi ký tự ngẫu nhiên như document_final_123.pdf).
5. Cắt và dán file vào đúng thư mục lưu trữ chuyên môn tương ứng.

Bottleneck:
Bước 2 và 3 (mất 10–15 phút) — phải mở từng file để đọc nội dung vì tên file tải về từ web/email thường bị mã hóa hoặc đặt tên chung chung.

Impact:
Mất 15–20 phút mỗi lần dọn dẹp; các file quan trọng dễ bị thất lạc hoặc vô tình bị bấm xóa nhầm khi dọn dẹp vội vã.

Success metric:
Giảm thời gian dọn dẹp phân loại từ 15 phút xuống dưới 2 phút; không còn file tài liệu vô danh trôi nổi trong thư mục tạm sau 7 ngày.

Non-AI alternative:
Viết kịch bản tự động hóa (Script Python/PowerShell) phân loại theo đuôi file (ví dụ: dồn tất cả .pdf vào một folder, .zip vào một folder) — nhược điểm: hoàn toàn không phân loại được theo ngữ cảnh môn học/dự án.

AI hypothesis:
Script hệ thống quét tệp tin, trích xuất text 1-2 trang đầu, mô hình ngôn ngữ nhỏ (small LLM) đọc lướt để suy luận ngữ cảnh môn học theo danh mục định sẵn và đề xuất tên mới; script tự động di chuyển file sau khi người dùng bấm xác nhận.

Quick gut:
[ ] No AI / process fix
[x] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 15 phút

[1 Mở thư mục Downloads: 1']
→ [2 Mở từng file xem nội dung: 8']  <-- bottleneck
→ [3 Nhớ lại tài liệu thuộc môn/dự án nào: 3']  <-- bottleneck
→ [4 Đổi tên file cho rõ nghĩa: 2']
→ [5 Kéo thả file về thư mục lưu: 1']

FUTURE STATE — 2 phút

[1 Chạy script quét thư mục Downloads: 10 giây]
→ [2 Script đọc metadata & AI trích xuất text đề xuất tên + thư mục đích: 20 giây]
→ [3 Người dùng xác nhận danh sách chuyển file trên bảng xem trước: 1']  <-- human boundary
→ [4 Hệ thống tự động đổi tên và di chuyển file: 10 giây]

Fallback: File nhạy cảm hoặc không nhận diện được nội dung → Giữ nguyên vị trí tại thư mục Downloads và gắn nhãn hỏi lại người dùng.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #1 — Đối chiếu catalog linh kiện cơ khí tiêu chuẩn từ nhà sản xuất (Ý tưởng #2).
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Workflow tra cứu thông số kỹ thuật từ catalog PDF để chọn mã part number vào bản vẽ CAD 3D là điểm nghẽn nặng nề và lặp lại liên tục trong mọi đồ án cơ điện tử. Số đo rõ ràng từ 60 phút giảm xuống dưới 12 phút/cụm linh kiện và đảm bảo độ chính xác 100% sau bước đối chiếu. Giải quyết bài toán này mang lại tác động rất lớn: loại bỏ hoàn toàn rủi ro mua sai linh kiện không lắp vừa khung máy, tránh lãng phí kinh phí gia công lại và không làm trễ tiến độ đồ án tốt nghiệp 3-5 ngày.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Liệu việc bóc tách bảng thông số kỹ thuật từ catalog PDF có thể giải quyết hoàn toàn bằng các bộ parser bóc tách bảng cố định (Rule-based PDF table parser) mà không cần đến AI hay không?
2. Nếu mô hình AI gợi ý sai một thông số lắp ghép cốt lõi (như bước ren vít me hoặc khoảng cách tâm lỗ bắt ốc), cơ chế kiểm soát của con người (human boundary) cần can thiệp ở bước nào để kỹ sư phát hiện ra ngay mà không làm hỏng cả bản vẽ thiết kế 3D?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: AI nhận xét rằng catalog của các hãng khác nhau (HIWIN, Misumi, THK) có cấu trúc bảng biểu, quy ước mã hóa linh kiện (naming convention) và các ký hiệu biến thể (suffix) rất khác nhau; nếu kỳ vọng AI tự động chọn mã rồi nhập thẳng vào file CAD 3D mà không có bước kỹ sư kiểm tra bản vẽ gốc thì rủi ro sai lệch kích thước lắp ráp là rất cao.
- Tôi sửa gì: Tôi đã điều chỉnh ranh giới giải pháp (boundary): AI chỉ dừng lại ở vai trò trợ lý trích xuất bảng thông số và gợi ý 2–3 mã tiềm năng kèm số trang PDF gốc; bước kiểm tra đối chiếu kích thước lắp ghép và chốt mã vào mô hình CAD bắt buộc phải là "Human boundary" do kỹ sư trực tiếp thực hiện.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
