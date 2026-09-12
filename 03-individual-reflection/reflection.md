# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Nguyễn Thái Lương
- Mã học viên: 2A202602932
- Nhóm: Anh Em Ba Miền
- Candidate problem nhóm chọn: Người trẻ dễ mất cọc và chịu chi phí vô lý khi thuê trọ, mua xe vì không biết biến thỏa thuận miệng thành điều khoản hợp đồng bảo vệ mình.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tự rà soát quy trình học tập, làm đồ án cơ điện tử và sinh hoạt cá nhân; scan 10 bài toán thực tế trên 4 lăng kính với số liệu bấm giờ thật; chuẩn bị 3 Problem Cards chi tiết. | Đóng góp 3 candidate problems (#16 Catalog linh kiện, #17 Chi tiêu ngân hàng, #18 Downloads) vào kho 18 bài toán chung của nhóm. |
| Pitch Problem Card | Trình bày bài toán #16 (Tra cứu catalog linh kiện cơ khí Misumi/HIWIN 200+ trang mất 45–75'/cụm) trong 2 phút với số liệu đo lường cụ thể và sơ đồ workflow rõ ràng. | Nhóm hiểu được một bài toán kỹ thuật chuyên sâu có cấu trúc chặt chẽ, nhưng sau đó nhận ra rào cản domain quá hẹp với các bạn ngoài ngành cơ khí. |
| Challenge bài của bạn khác | Đặt câu hỏi chất vấn bài toán Tìm kiếm Discord của Hoàng và So sánh giá TMĐT của Định về rào cản kỹ thuật (phân quyền truy cập server, cơ chế chống bot và API đóng của các sàn). | Giúp nhóm nhận diện sớm rủi ro phụ thuộc vào nền tảng bên ngoài và loại bỏ các đề tài không khả thi trong môi trường lab. |
| Gom trùng / cluster | Đóng vai trò Facilitator, điều phối nhóm phân loại và gom 18 candidate problems thành 5 cụm (A, B, C, D, E) dựa trên bản chất điểm nghẽn và tính chất dữ liệu. | Giúp nhóm nhìn ra bức tranh tổng thể, dễ dàng nhận diện 2 cụm có nỗi đau thật và dữ liệu mở nhất: Pháp lý đời sống (A) và Quản lý nhóm đồ án (B). |
| Chọn candidate problem | Cùng Duy bảo vệ bài toán Hợp đồng thuê trọ/mua xe trước lo ngại về rủi ro pháp lý; đề xuất thiết lập ranh giới an toàn (Human Boundary) để AI không vi phạm tư vấn luật trái phép. | Thuyết phục cả 6 thành viên đồng thuận 100% chọn bài toán Hợp đồng thuê trọ/mua xe với điểm số cao nhất (34/35 điểm). |
| Validation / research | Trực tiếp thu thập và phân tích 10 bản hợp đồng thuê trọ thực tế của sinh viên; nghiên cứu mô hình Thư viện Pháp luật, DocuSign và đối chiếu tính khả thi cho đối tượng người trẻ. | Cung cấp bằng chứng thực tế cho thấy 9/10 hợp đồng có điều khoản bất lợi nghiêng về chủ nhà; xác định rõ khoảng trống giải pháp mà các công cụ hiện tại chưa đáp ứng được. |
| Workflow nhóm | Đảm nhiệm vai trò Workflow Architect: thiết kế Current State 7 bước (4.5h) và Future State 8 bước (3.5h, xử lý 25') thể hiện đầy đủ 5 thành phần (Rule, AI, Con người, Boundary, Fallback). | Định hình khung xương giải pháp mạch lạc, bóc tách chính xác 3 điểm nghẽn ở khâu ký kết và tranh chấp, chỉ rõ vị trí can thiệp an toàn của AI. |
| Problem Statement | Cùng Duy và nhóm soạn thảo bảng Problem Statement v0 và nâng cấp lên bản v1 với 9 trường chuẩn hóa, siết chặt metric và ranh giới trách nhiệm. | Thiết lập bộ chỉ số đo lường trước/sau rõ ràng (tỷ lệ mất cọc giảm từ 30% xuống <5%) và ranh giới Boundary chặt chẽ, bảo vệ người dùng và hệ thống. |
| Rule / Workflow / Agent | Phân tích ma trận độ mơ hồ và độ phức tạp; dẫn dắt nhóm trả lời 5 câu hỏi chốt để loại bỏ ý tưởng làm Autonomous Agent tự đàm phán hợp đồng. | Nhóm thống nhất hạ mức giải pháp xuống Workflow bán tự động có bước Human Review bắt buộc, tránh rủi ro pháp lý và chi phí vận hành quá lớn. |
| Decision | Đề xuất quyết định Go với pilot nhỏ trên 10–15 trường hợp sinh viên thực tế; xây dựng kịch bản đo lường 3 chỉ số cốt lõi và phương án Rollback nếu bị chủ nhà từ chối. | Nhóm có kế hoạch hành động cụ thể, thực tế và sẵn sàng chuyển giao sang các giai đoạn triển khai kỹ thuật tiếp theo mà không bị mông lung. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi là việc định hình cấu trúc toàn bộ Future Workflow 8 bước và thiết lập ranh giới an toàn (Human Boundary) tại Bước 5: bắt buộc người dùng tick checkbox xác nhận tự chịu trách nhiệm trước khi xuất file PDF có mã băm. Nhờ ranh giới này, nhóm đã hóa giải được nỗi lo vi phạm tư vấn pháp lý và tự tin chọn Go cho giải pháp AI Workflow.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Dùng AI hỏi thêm các góc nhìn lãng phí thời gian trong việc học tập và sinh hoạt của sinh viên ngành kỹ thuật. | Gợi ý thêm các khía cạnh về quản lý hóa đơn, đối chiếu giao dịch ngân hàng và dọn dẹp file tải về. | Gợi ý nhiều ý tưởng chung chung kiểu "học tập không hiệu quả", "quản lý thời gian kém" không có dấu hiệu đo lường cụ thể. | Loại bỏ toàn bộ các ý chung chung, chỉ giữ lại các việc bản thân trực tiếp làm hàng tuần và tự bấm giờ đo đạc số liệu thật (35–55' đọc datasheet, 45–75' tra catalog). |
| Problem Card | Nhờ AI đóng vai người phản biện (Devil's Advocate) để tìm điểm yếu trong Problem Card #2 (Tra cứu catalog cơ khí). | Chỉ ra rủi ro AI đọc sai bảng thông số kỹ thuật (pitch, lead, tải trọng) có thể làm hỏng cụm máy thực tế. | AI gợi ý giải pháp quá đà: đề xuất xây dựng "Multi-agent tự động chọn linh kiện và sinh file CAD 3D" hoàn toàn thiếu thực tế. | Kéo về thực tế: xác định AI chỉ trích xuất đúng hàng thông số từ PDF, việc quyết định chọn mã nào lắp vào cụm máy bắt buộc kỹ sư phải tự kiểm tra. |
| Workflow | Nhờ AI phác thảo nhanh luồng tương tác giữa sinh viên và chủ nhà khi phát sinh giao dịch thuê trọ/mua xe. | Gợi ý logic các điểm có thể xảy ra mâu thuẫn (tiền cọc, khấu trừ hao mòn, thanh lý sớm). | AI tự động vẽ thêm bước "Agent tự gọi điện đàm phán với chủ nhà" và gộp bước AI sinh hợp đồng với bước sinh viên ký tên làm một. | Tách rời bước AI sinh hợp đồng và bước Sinh viên review thành 2 bước riêng biệt; thêm bước Human Boundary 10 phút và bước lưu trữ mã băm làm bằng chứng số. |
| Research | Dùng Perplexity/AI tra cứu nhanh các công cụ rà soát hợp đồng pháp lý hiện có trên thị trường. | Tìm ra các tên tuổi lớn như Robin AI, Spellbook, DocuSign và Thư viện Pháp luật. | AI trích dẫn số liệu quảng cáo kiểu "tiết kiệm 90% chi phí pháp lý" mà không có nguồn kiểm chứng độc lập; đánh giá nhầm rằng Robin AI có hỗ trợ luật nhà trọ Việt Nam. | Tự truy cập website chính thức kiểm tra tính năng, loại bỏ các con số vô căn cứ; ghi rõ Robin AI chỉ dành cho doanh nghiệp lớn nói tiếng Anh và nhóm sẽ học hỏi pattern "gắn cờ rủi ro" thay vì sao chép công cụ. |
| Problem Statement | Nhờ AI phản biện bảng Problem Statement v0 để tìm các trường còn mơ hồ hoặc thiếu khả thi. | Phát hiện ra 2 lỗ hổng lớn: Workflow chưa nói rõ kênh giao tiếp (online hay offline) và Boundary chưa giải quyết câu hỏi "AI sinh sai điều khoản thì ai chịu trách nhiệm?". | AI đề xuất đưa vào điều khoản "miễn trừ mọi trách nhiệm" sơ sài một dòng, không đủ căn cứ bảo vệ hệ thống. | Sửa chặt chẽ: xác nhận giao dịch là trao đổi trực tiếp/Zalo cá nhân, thiết lập cơ chế bắt buộc tick checkbox "Tôi đã đọc và tự chịu trách nhiệm" trước khi xuất file PDF, bổ sung disclaimer màu đỏ cảnh báo không thay thế luật sư. |
| Rule / Workflow / Agent | Nhờ AI phân tích các ca thất bại khi áp dụng Autonomous Agent vào các tác vụ mang tính pháp lý hoặc cam kết tài chính. | Đưa ra các case study về hallucination trong văn bản hợp đồng dẫn đến kiện tụng và việc cơ quan quản lý phạt hành vi tư vấn luật không giấy phép. | AI vẫn có xu hướng khen ngợi phương án Agent là "tiên tiến, đón đầu tương lai" và coi nhẹ rủi ro pháp lý ngoài đời thực. | Dứt khoát bác bỏ phương án Agent; kiên quyết bảo vệ lựa chọn Workflow kết hợp Rule và Con người vì quy trình cần đi thẳng một đường và tính an toàn pháp lý là ưu tiên sống còn. |
| Decision | Dùng AI kiểm tra checklist điều kiện Go / No-Go xem nhóm còn thiếu góc nhìn nào chưa đánh giá. | Nhắc nhở nhóm về rủi ro tâm lý: nếu chủ nhà thấy bản hợp đồng quá lạ hoặc do AI tạo có thể sẽ từ chối cho thuê ngay từ đầu. | AI không đưa ra được phương án xử lý cụ thể khi chủ nhà từ chối mà chỉ bảo "cần nâng cao nhận thức cộng đồng". | Tự bổ sung cơ chế Fallback thực tế: sinh viên xuất file PDF in ra giấy để ký tay truyền thống, đồng thời lập kế hoạch Rollback chuyển sang cẩm nang checklist 10 điều khoản vàng nếu tỷ lệ bị từ chối > 30%. |

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Khi lắng nghe phần trình bày top 3 problems của các bạn trong nhóm, tôi nhận ra bài toán tra cứu catalog cơ khí của mình dù rất sâu về kỹ thuật nhưng lại quá hẹp về phạm vi người dùng, trong khi những vấn đề đời sống như mất cọc thuê trọ của Duy hay trôi việc sau họp của Hoàng mới thực sự là nỗi đau chung nhức nhối. Trong quá trình thảo luận, nhóm chúng tôi cũng từng có thời điểm bị cuốn vào tư duy "solution-first", một số bạn hào hứng đề xuất xây dựng một Autonomous Agent có thể tự động nhảy vào phòng chat Zalo đàm phán hợp đồng với chủ trọ cho "ngầu". Tuy nhiên, với vai trò Workflow Architect, tôi đã kéo nhóm quay lại với thực tế: giao kết dân sự là vấn đề ràng buộc pháp lý và tiền bạc, việc để một con bot tự quyết định là vô cùng liều lĩnh và vi phạm ranh giới an toàn. Đóng góp rõ nét nhất của tôi trong bản báo cáo cuối chính là việc định hình Future Workflow 8 bước và thiết kế cơ chế Human Boundary ở bước 5, buộc sinh viên phải chủ động đọc, tick checkbox xác nhận trách nhiệm trước khi xuất file PDF có mã băm. Với tôi, điều khó nhất khi hoàn thiện Problem Statement không phải là đo đạc thời gian, mà là xác định ranh giới (Boundary) giữa "hỗ trợ soạn thảo giáo dục" và "hành nghề luật sư trái phép". Chúng tôi đã mất rất nhiều thời gian tranh luận để đi đến thỏa thuận rằng AI tuyệt đối không đưa ra lời khuyên pháp lý chuyên sâu mà chỉ đóng vai trò công cụ đối chiếu và gắn cờ điều khoản rủi ro. Nếu được làm lại từ đầu, tôi sẽ challenge nhóm sớm hơn ở khâu khảo sát thực địa để phỏng vấn thêm 2-3 chủ nhà trọ lớn tuổi, nhằm kiểm chứng xem họ có thực sự sẵn lòng ký vào một văn bản do ứng dụng AI gợi ý hay không, thay vì chỉ lắng nghe góc nhìn một chiều từ phía sinh viên.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

