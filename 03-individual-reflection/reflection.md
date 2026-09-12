# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Đậu Quang Ý
- Mã học viên: 2A202602661
- Nhóm: Nhóm LAB 02
- Candidate problem nhóm chọn: Khi code bài tập bị lỗi (bug/stack trace), sinh viên phải tìm kiếm nhiều nguồn và thử sai mất 20-40 phút trước khi xác định được nguyên nhân và cách sửa (Debug code bài tập).

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tự quan sát và quét 10 problems bám sát trải nghiệm học CNTT theo 4 lăng kính, có số đo thời gian bấm giờ và tần suất cụ thể | Đóng góp 3 candidate thực tế của sinh viên vào kho ý tưởng chung của nhóm |
| Pitch Problem Card | Trình bày trực tiếp trong 2 phút về Problem Card #1: "Debug code bài tập mất nhiều thời gian", chỉ rõ bottleneck và số đo 20-40 phút/lỗi | Nhóm hiểu rõ tính cấp thiết và đưa bài toán vào danh sách Shortlist tiềm năng nhất |
| Challenge bài của bạn khác | Đặt câu hỏi chất vấn bài "Tin nhắn nhóm từ nhiều nguồn" của bạn Đạt và bài tìm tài liệu của bạn Thắng về tính khả thi của dữ liệu đầu vào và cách đo lường | Giúp nhóm nhận diện nguy cơ bài toán bị quá rộng (scope creep) và khó kiểm soát dữ liệu bên thứ ba |
| Gom trùng / cluster | Cùng nhóm gom 9 candidates thành 3 cụm chủ đề: (A) Hỗ trợ lập trình/debug code, (B) Quản lý trao đổi nhóm, (C) Định dạng văn bản/slide | Nhóm nhìn thấy pattern chung và rút gọn danh sách thảo luận từ 9 ý xuống 3 hướng chính |
| Chọn candidate problem | Tham gia chấm điểm ma trận Score (7 tiêu chí) và giải thích lý do cho điểm 5 ở tính đo lường và tính khả thi trong lab | Nhóm đạt đồng thuận 100% chọn bài toán Debug code làm candidate chính để đào sâu |
| Validation / research | Khảo sát nhanh 3 bạn cùng lớp về thời gian fix bug và tìm hiểu tính năng của GitHub Copilot / Cursor để xem họ đã giải quyết bước nào | Giúp nhóm nhận ra thị trường đã có nhiều công cụ sinh code, nhưng sinh viên vẫn tắc ở khâu "hiểu nguyên nhân gốc rễ" |
| Workflow nhóm | Trực tiếp phác thảo sơ đồ Current Workflow (7 bước lặp thử sai) và Future State (4 bước với điểm can thiệp AI) | Cả nhóm thống nhất được vị trí nút thắt cổ chai nằm ở bước tìm kiếm/lọc thông tin giữa nhiều nguồn |
| Problem Statement | Cùng nhóm hoàn thiện câu PS v1, đặc biệt là đóng góp phần xác định Boundary (ranh giới con người) và Success Metric | Bản Problem Statement của nhóm rất chặt chẽ, có số liệu đo lường rõ ràng (giảm từ 20-40' xuống dưới 10-15') |
| Rule / Workflow / Agent | Phản biện đề xuất xây dựng "Autonomous Agent tự sửa code" của thành viên trong nhóm, bảo vệ quan điểm chọn Workflow | Nhóm đồng thuận hạ mức từ Agent xuống **Workflow**, tránh bẫy solution-first và đảm bảo an toàn cho mục tiêu học tập |
| Decision | Cùng nhóm rà soát 6 câu hỏi checklist đánh giá mức độ sẵn sàng và thống nhất quyết định **Go** | Nhóm chốt được kế hoạch Pilot nhỏ thử nghiệm trên 10 dạng lỗi bài tập phổ biến |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi là việc thuyết phục nhóm chọn bài toán Debug code và kiên quyết hạ mức giải pháp từ "Agent tự động fix code" xuống "Workflow gợi ý nguyên nhân gốc rễ", đồng thời thiết lập ranh giới bắt buộc sinh viên phải tự tay sửa code để giữ vững bản chất học tập.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý thêm góc nhìn phản biện về các khó khăn của sinh viên CNTT | Nhắc nhở thêm khía cạnh về kiểm tra test case và đồng bộ môi trường | Đưa ra các ý chung chung mang tính cảm xúc như "học khó", "áp lực điểm số" | Loại bỏ toàn bộ các ý kiến cảm tính, chỉ giữ lại các vấn đề có số phút và tần suất đo được |
| Problem Card | Đóng vai người phản biện để tìm lỗ hổng trong Problem Card Debug code | Chỉ ra rủi ro sinh viên sẽ ỷ lại nếu AI giải quyết toàn bộ bài tập | Đề xuất giải pháp theo hướng chatbot đa năng không có quy trình cụ thể | Định hình lại giải pháp thành một Workflow 4 bước rõ ràng, giới hạn AI ở khâu phân tích nguyên nhân |
| Workflow | Hỗ trợ chuẩn hóa định dạng văn bản sơ đồ luồng (ASCII text) | Giúp sắp xếp các khối bước và căn lề thời gian trực quan | Tự ý gộp bước "đọc hiểu giải thích" và "tự sửa code" thành một bước do AI làm hộ | Tách riêng bước người học tự đọc hiểu và sửa code thành Human boundary bắt buộc, thêm bước Fallback |
| Research | Tìm kiếm nhanh các công cụ và bài báo liên quan đến hỗ trợ debug cho người mới học | Cung cấp danh sách các công cụ hiện có trên thị trường rất nhanh chóng | Đưa ra các tuyên bố "tiết kiệm 55% thời gian" nhưng không có nguồn kiểm chứng độc lập | Tự tìm lại tài liệu chính thức từ GitHub Copilot Research để kiểm tra tính xác thực, không đưa số liệu ảo vào bài |
| Problem Statement | Kiểm tra xem câu Problem Statement v0 có bị thiếu trường thông tin cốt lõi nào không | Nhắc nhóm cần làm rõ điều kiện biên (Boundary) và đối tượng thụ hưởng | Viết câu văn quá dài dòng, dùng nhiều thuật ngữ đao to búa lớn và lồng sẵn giải pháp vào problem | Rút gọn câu định nghĩa vấn đề về đúng 1 câu duy nhất tập trung vào Actor, Nỗi đau, Điểm nghẽn và Metric |
| Rule / Workflow / Agent | Hỏi phản biện xem bài toán debug này có thể giải quyết bằng Rule-based hay cần Agent | Phân tích rõ ràng giới hạn của Rule-based khi gặp ngôn ngữ tự nhiên và stack trace đa dạng | Luôn cổ vũ nhóm chọn "Agent" vì cho rằng Agent là xu hướng công nghệ tân tiến nhất | Bác bỏ gợi ý Agent của AI, kiên định chọn Workflow vì quy trình xử lý tuyến tính và kiểm soát được rủi ro |
| Decision | Không dùng AI | (Không áp dụng) | (Không áp dụng) | Nhóm tự thảo luận trực tiếp và tự chịu trách nhiệm về quyết định Go dựa trên năng lực thực tế |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

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
Khi lắng nghe top 3 bài toán của bạn Thắng và bạn Đạt, tôi nhận ra mỗi người đều mang đến những góc nhìn rất chân thực nhưng không phải vấn đề nào cũng phù hợp để đưa vào lab: bài toán tin nhắn trôi của Đạt rất nhức nhối nhưng phạm vi quá rộng và phụ thuộc vào nền tảng ngoài, trong khi bài toán debug code của tôi lại có luồng xử lý khép kín và đo lường được rõ ràng hơn. Trong buổi làm việc, nhóm tôi đã có lúc rơi vào cái bẫy solution-first khi một thành viên hào hứng đề xuất xây dựng một "Autonomous Agent" có khả năng tự quét repository, tự viết code sửa và tự commit lên GitHub cho "ngầu". Lúc đó, tôi đã lập tức lên tiếng phản biện rằng mục tiêu cốt lõi của sinh viên là học hiểu bản chất, nếu để Agent làm thay toàn bộ thì người học sẽ hoàn toàn mất khả năng tư duy độc lập và dễ gặp rủi ro ảo giác (hallucination) nghiêm trọng. Sau khi bị nhóm chất vấn ngược lại về việc làm sao ngăn sinh viên copy-paste mù quáng từ AI, bản thân tôi cũng đã thay đổi thiết kế ban đầu: tôi bổ sung thêm ranh giới bắt buộc (Human boundary) là AI chỉ được phép khoanh vùng dòng lỗi và giải thích cơ chế, còn sinh viên bắt buộc phải tự tay gõ lại code sửa. Điều khó nhất với tôi trong suốt quá trình hoàn thiện Problem Statement chính là việc chốt ranh giới (boundary) và tìm ra con số baseline đo lường đáng tin cậy thay vì ước lượng cảm tính. Nếu có cơ hội làm lại từ đầu, tôi sẽ challenge nhóm quyết liệt hơn ngay từ bước gom cụm candidate để tiết kiệm thời gian tranh luận giữa các ý tưởng chưa đủ bằng chứng. Bài học lớn nhất mà tôi tâm đắc sau buổi lab hôm nay là: một bài toán tốt không phải là bài toán nghe có vẻ "AI nhất", mà là bài toán có quy trình đủ chặt, điểm nghẽn đủ rõ và một giải pháp Workflow đơn giản có người kiểm soát luôn giá trị hơn một hệ thống Agent cồng kềnh nhưng thiếu an toàn.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] [Nhóm] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

