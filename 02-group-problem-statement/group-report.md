# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   | Nguyễn Minh Thắng | 2A202602650 | Facilitator & Document Coordinator (Điều phối thảo luận và thư ký nhóm) |
| 2   | Phạm Thành Đạt   | 2A202602655 | Workflow & Validation Lead (Khảo sát người dùng và thiết kế quy trình) |
| 3   | Đậu Quang Ý      | 2A202602661 | Research & Solution Architect (Nghiên cứu giải pháp và cấu trúc Problem Statement) |

**Candidate problem nhóm chọn (1 câu):**

Khi code bài tập lập trình bị lỗi (bug/stack trace), sinh viên phải tìm kiếm nhiều nguồn (Google, StackOverflow) và thử sai mất 20–40 phút trước khi xác định được nguyên nhân gốc rễ và cách sửa.

---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Nguyễn Minh Thắng | Cấu hình môi trường và thư viện ban đầu cho mỗi bài thực hành mới lặp lại tốn 10-15 phút | Sinh viên CNTT | Cài đặt package xung đột phiên bản, phải gỡ ra cài lại | Phổ biến nhưng giải quyết tốt hơn bằng script Conda/Docker (Rule), chưa cần AI |
| 2 | Nguyễn Minh Thắng | Tìm tài liệu học tập phù hợp mất nhiều thời gian do kết quả trả về không đúng trình độ | Sinh viên tự học | Đọc lướt và đánh giá xem tài liệu có đúng yêu cầu bài tập không (15-25') | Nỗi đau thật, nhưng tiêu chí "phù hợp" mang tính cảm tính, khó đo lường chính xác |
| 3 | Nguyễn Minh Thắng | Khó hiểu các khái niệm thuật toán/toán học AI phức tạp từ tài liệu tiếng Anh | Sinh viên học AI | Đọc nhiều nguồn rồi tự tổng hợp lại thành cách hiểu dễ nhớ (30-60') | Vấn đề quá rộng, mang tính năng lực cá nhân hơn là một quy trình lặp lại |
| 4 | Phạm Thành Đạt | Tin nhắn nhóm từ nhiều nguồn bị trôi, thành viên phải hỏi lại deadline và phân công | Thành viên nhóm | Lục tìm lại tin nhắn ghim, ảnh bài tập trong group chat Zalo/Discord (10-15') | Rất thực tế trong làm việc nhóm; nhưng rào cản truy cập API Zalo và quyền riêng tư |
| 5 | Phạm Thành Đạt | Đồng bộ phiên bản file bài tập nhóm và giải quyết xung đột nội dung trước khi nộp | Nhóm làm bài tập | Soát file thủ công và merge từng phần của các thành viên (20-30') | Phù hợp dùng Git workflow hoặc Google Docs quy định chuẩn hơn là dùng AI |
| 6 | Phạm Thành Đạt | Khi chuẩn bị thuyết trình nhóm, ghép nội dung của nhiều người khiến format và giọng văn lệch nhau | Nhóm thuyết trình | Đọc soát và viết lại câu từ cho đồng nhất văn phong (30-60') | Có pain point nhưng bước đánh giá chất lượng giọng văn khó đặt ra tiêu chí cứng |
| 7 | Đậu Quang Ý | Khi code bài tập bị lỗi (bug/stack trace), phải tìm kiếm Google/GitHub nhiều nguồn mới xác định được nguyên nhân | Sinh viên làm bài code | Mở 5-8 tab tìm kiếm và thử code chắp vá không đúng ngữ cảnh (20-40'/lỗi, 3-5 lỗi/tuần) | Cực kỳ thực tế, ai trong nhóm cũng gặp mỗi ngày; bottleneck rõ; số đo thời gian sắc |
| 8 | Đậu Quang Ý | Khi làm báo cáo/slide, phải nhiều lần chỉnh font, căn lề, tiêu đề, bố cục và kiểm tra lỗi trình bày | Bản thân và nhóm | Căn chỉnh thủ công bảng/ảnh và xuất PDF nhiều vòng (mỗi bài mất 2-3 vòng, 20-30'/vòng) | Workflow lặp lại rất rõ; nhưng nên dùng Template chuẩn + Checklist (No AI) |
| 9 | Đậu Quang Ý | Sau khi hoàn thành bài code phải tự kiểm tra nhiều trường hợp test case đầu vào | Sinh viên nộp bài | Tự nghĩ test case và chạy tay từng case biên để bắt lỗi (10-20'/bài) | Bài toán hay nhưng sinh viên có thể tự viết script Unit Test để kiểm tra tự động |

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A (Hỗ trợ lập trình & xử lý lỗi code) | 1, 7, 9 | Trục trặc kỹ thuật trong quá trình viết và chạy code, mất nhiều thời gian thử sai | Candidate 7 nổi bật nhất vì có workflow rõ ràng và thời gian hao phí lớn nhất |
| B (Giao tiếp & quản lý công việc nhóm) | 4, 5 | Thông tin phân tán trên nhiều kênh chat, tài liệu rời rạc gây chậm tiến độ | Vấn đề phụ thuộc nhiều vào thói quen cá nhân và chính sách bảo mật của các app chat |
| C (Nghiên cứu tài liệu & học tập kiến thức) | 2, 3 | Khó khăn khi tiếp cận tài liệu chuyên sâu, mất công đọc và tự tổng hợp | Dễ rơi vào bẫy "xây chatbot trả lời câu hỏi" chung chung, khó đo lường hiệu quả |
| D (Định dạng văn bản & thuyết trình) | 6, 8 | Mất thời gian căn chỉnh hình thức trình bày sau khi đã hoàn thành nội dung thô | Phần lớn giải quyết triệt để bằng Template chuẩn hóa và quy trình kiểm tra (No AI) |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| Debug code bài tập bị lỗi (Candidate 7) | - Actor cụ thể: Sinh viên CNTT khi làm bài thực hành.<br>- Workflow tuần tự rõ: chạy lỗi → search → thử sửa → test lại.<br>- Bottleneck định lượng được: 20-40 phút/lỗi, tuần gặp 3-5 lần. | Sinh viên có thể bị ỷ lại vào AI mà không hiểu bản chất lỗi; cần thiết kế Human boundary chặt chẽ. |
| Tin nhắn nhóm từ nhiều nguồn bị trôi (Candidate 4) | - Pain point phổ biến trong làm việc nhóm mà ai cũng từng bực bội.<br>- Tần suất lặp lại cao (3-5 lần/tuần). | Quyền truy cập API tin nhắn riêng tư (Zalo/Messenger); phạm vi dễ bị trượt sang hệ thống search quá rộng. |
| Chỉnh format báo cáo/slide (Candidate 8) | - Quy trình lặp lại rất cơ học và tốn thời gian (60-90 phút/bài).<br>- Dễ đo lường số vòng chỉnh sửa. | Bản chất giải quyết được 80% bằng Template chuẩn (No AI); đất diễn cho AI can thiệp không thực sự lớn. |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Debug code bài tập bị lỗi | 5 | 5 | 5 | 5 | 5 | 4 | 5 | 34 |
| Tin nhắn nhóm bị trôi | 4 | 3 | 4 | 3 | 3 | 4 | 4 | 25 |
| Chỉnh format báo cáo/slide | 5 | 5 | 4 | 4 | 4 | 3 | 4 | 29 |

**Candidate nhóm chọn (1 bài duy nhất):**

```text
Khi code bài tập lập trình bị lỗi (bug/stack trace), sinh viên phải tìm kiếm nhiều nguồn (Google, StackOverflow) và thử sai mất 20–40 phút trước khi xác định được nguyên nhân gốc rễ và cách sửa.
```

**Vì sao chọn (4-5 câu):**

```text
1. Đây là bài toán có Actor (sinh viên CNTT) và bối cảnh (làm bài tập thực hành lập trình hàng tuần) vô cùng sắc nét, cả 3 thành viên trong nhóm đều hiểu sâu và đối mặt mỗi ngày.
2. Quy trình hiện tại có điểm nghẽn (bottleneck) cực kỳ rõ ràng: sinh viên bị chìm trong ma trận kết quả tìm kiếm trên Google/StackOverflow và mất 20-40 phút thử copy-paste chắp vá mà không hiểu bản chất.
3. Impact đo lường được trực tiếp bằng số phút xử lý mỗi lỗi và số tab tìm kiếm phải mở, tạo điều kiện thuận lợi để xác lập baseline trước và sau khi có AI can thiệp.
4. Bài toán vừa vặn để thực hiện và kiểm chứng ngay trong buổi lab 4 tiếng bằng cách thử nghiệm trực tiếp trên các đoạn code lỗi thực tế.
5. Rất phù hợp để phân tích và so sánh ranh giới giữa Rule (tra cứu mã lỗi cứng), Workflow (chuỗi phân tích ngữ cảnh) và Agent (tự sửa code), giúp nhóm tránh được bẫy solution-first.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
- Tin nhắn nhóm bị trôi: Vấn đề có pain thật nhưng phụ thuộc vào việc kết nối API dữ liệu chat riêng tư của Zalo/Discord, phạm vi bài toán quá rộng và dễ sa lầy vào việc xây dựng công cụ tìm kiếm dữ liệu lớn vượt quá khuôn khổ buổi lab.
- Chỉnh format báo cáo/slide: Quy trình này rất dễ giải quyết bằng giải pháp phi AI (No AI) như dùng Slide Master hoặc Template Word chuẩn của trường kết hợp Checklist tự kiểm, không đủ lý do thuyết phục để đầu tư giải pháp AI chuyên biệt.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
Bạn Thắng ban đầu lo ngại rằng việc đưa AI vào khâu debug sẽ biến thành công cụ "giải bài tập hộ", khiến sinh viên lười tư duy và trượt môn khi thi thực hành offline. Nhóm đã thảo luận kỹ và chốt giải pháp: không cho AI tự động sinh ra đoạn code hoàn chỉnh để sinh viên copy-paste, mà thiết kế AI chỉ được đóng vai trò "người giải thích nguyên nhân gốc rễ (root cause) và gợi ý checklist kiểm tra", bắt buộc sinh viên phải tự tay sửa code (Human boundary).
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview | 3 sinh viên CNTT năm 3-4 | Cả 3 đều mất từ 25-45 phút mỗi khi gặp lỗi lạ.<br>- Bạn Tuấn (Năm 4): *"Lỗi thư viện Python nhiều khi chỉ 1 dòng mà mở cả chục tab StackOverflow, copy thử tùm lum mất cả tiếng mới chạy được mà chẳng hiểu vì sao."*<br>- Bạn Hoàng (Năm 3): *"Sợ nhất là copy code trên mạng vào sửa xong lại đẻ thêm 2-3 lỗi khác mới toanh."* | Bạn Mai (Năm 3): *"Nếu là lỗi cú pháp cơ bản (SyntaxError) thì VS Code đã gạch đỏ chỉ tận nơi, không cần tra cứu nhiều."* | Thu hẹp bài toán: Loại trừ lỗi cú pháp cơ bản (IDE đã bắt tốt), tập trung vào **lỗi ngoại lệ runtime (Runtime Exceptions), lỗi logic và lỗi xung đột thư viện/môi trường**. |
| Survey / poll | 12 sinh viên lớp K4B | - 10/12 bạn (83.3%) xác nhận mất trên 20 phút cho mỗi lỗi runtime phức tạp.<br>- 9/12 bạn (75%) từng thử ít nhất 3 đoạn code trên mạng trước khi sửa được bài. | 3/12 bạn cho biết đôi khi hỏi bạn cùng bàn hoặc trợ giảng giải thích thì nhanh hơn tự search Google. | Nhóm điều chỉnh mục tiêu: Output của AI không chỉ đưa cách sửa, mà phải đóng vai trò như "người trợ giảng giải thích cơ chế gây lỗi" bằng giọng văn sư phạm dễ hiểu. |
| Log / ticket / review (nếu có) | 15 bug log trong bài tập tuần trước | 11/15 trường hợp lỗi xuất phát từ việc hiểu sai kiểu dữ liệu (TypeError) hoặc gọi sai tên thuộc tính (AttributeError) trong thư viện ngoài. | 4/15 trường hợp là lỗi môi trường chưa kích hoạt virtualenv (cần lệnh terminal, không phải sửa code). | Bổ sung thêm nhánh xử lý nhận diện lỗi môi trường/thiếu thư viện cài đặt. |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Pain point thực sự không phải là thiếu code mẫu trên mạng, mà là sinh viên bị ngập trong ma trận kết quả tìm kiếm không đúng ngữ cảnh và thiếu kiến thức nền để nhận diện nguyên nhân gốc rễ (root cause), dẫn đến vòng lặp thử sai chắp vá và lãng phí thời gian.
```

Bằng chứng đính kèm (nếu có): `02-group-problem-statement-survey.png`, `02-group-problem-statement-interview-notes.md`

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| GitHub Copilot Chat (Fix with Copilot) | https://docs.github.com/en/copilot/using-github-copilot/copilot-chat | Nhận diện lỗi và tự động sinh code sửa trực tiếp trong editor | Tích hợp mượt mà, phản hồi tức thì ngay trong IDE | Thiên về "sửa hộ toàn bộ", sinh viên dễ bấm Accept mà không hiểu bản chất; dễ hallucinate nếu thư viện có phiên bản đặc thù | Phải tách biệt phần giải thích nguyên nhân và không được tự động đè code lên bài làm của sinh viên |
| Phind (AI Search Engine for Developers) | https://www.phind.com | Tìm kiếm kỹ thuật và tổng hợp câu trả lời có trích dẫn | Trả lời thẳng vào câu hỏi code, dẫn link nguồn uy tín (GitHub, Docs) | Không tự động đọc được toàn bộ ngữ cảnh file code và biến số môi trường local của sinh viên | Cần cấu trúc hóa input đầu vào gồm: mã lỗi + đoạn code liên quan + ngữ cảnh bài tập |
| Sentry Error Monitoring | https://docs.sentry.io/product/issues/issue-details/breadcrumbs/ | Bắt stack trace và hiển thị breadcrumbs giá trị biến khi crash | Định vị chính xác vị trí crash và trạng thái dữ liệu | Thiết kế cho production/doanh nghiệp, giao diện phức tạp và không có giải thích mang tính sư phạm cho người học | Cần đầu ra súc tích, giải thích cơ chế lỗi bằng ngôn ngữ giản dị, tập trung vào bài toán giáo dục |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Không nên xây dựng một chatbot hỏi đáp lan man và tuyệt đối không build công cụ tự động ghi đè code sửa hộ. Hướng đi đúng đắn là một Workflow sư phạm: AI phân tích mã lỗi + ngữ cảnh code để chỉ ra nguyên nhân gốc rễ và gợi ý checklist các bước kiểm tra, sau đó dừng lại để sinh viên tự tay thao tác sửa code (Human boundary).
```

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

Dán workflow hoặc link file: `02-group-problem-statement-workflow.png/pdf/md`

```text
CURRENT STATE — 7 bước, tổng cộng 35 phút (sau khi gặp lỗi)

[1 Nhận thông báo lỗi & stack trace: 2' - Sinh viên]
  → [2 Đọc lướt dòng lỗi & đoán nguyên nhân: 3' - Sinh viên]
  → [3 Copy lỗi search Google/GitHub: 5' - Sinh viên]
  → [4 Mở 5-8 tab đọc & lọc bài viết liên quan: 12' - Sinh viên]  <-- bottleneck
  → [5 Copy đoạn code trên mạng vào thử: 8' - Sinh viên]
  → [6 Chạy lại code & kiểm tra kết quả: 3' - Sinh viên]
  → [7 Lặp lại nếu vẫn lỗi / phát sinh lỗi mới: 2' - Sinh viên]
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1 | Sinh viên | Bấm Run chương trình | Thông báo lỗi màu đỏ (Error message / Stack trace) | 2 phút / mỗi lần gặp lỗi | Điểm khởi đầu |
| 2 | Sinh viên | Error message tiếng Anh | Dự đoán sơ bộ dòng gây lỗi | 3 phút / mỗi lỗi | Thường đoán mò vì thuật ngữ khó hiểu |
| 3 | Sinh viên | Dòng lỗi copy vào Google | Danh sách hàng chục link StackOverflow / diễn đàn | 5 phút / mỗi lỗi | Bắt đầu phân tán sự chú ý |
| 4 | Sinh viên | 5-8 tab bài viết trên trình duyệt | Chọn được 1-2 đoạn code mẫu cảm thấy giống bài mình | 12 phút / mỗi lỗi | **BOTTLENECK CHÍNH:** đọc lọc thông tin không đồng nhất, dễ nhầm phiên bản |
| 5 | Sinh viên | Code mẫu trên mạng + code hiện tại | Code được chỉnh sửa chắp vá | 8 phút / mỗi lỗi | Nguy cơ xung đột biến và logic |
| 6 | Sinh viên | Code đã sửa | Kết quả chạy thử (Pass hoặc Fail) | 3 phút / mỗi lỗi | Kiểm tra xem code có chạy qua dòng đó không |
| 7 | Sinh viên | Trạng thái lỗi mới (nếu có) | Quyết định search tiếp hoặc hỏi bạn bè | 2 phút / mỗi lỗi | Nếu fail thì quay lại vòng lặp từ bước 3 |

**Bottleneck chính (2-3 câu):**

```text
Điểm nghẽn nặng nhất nằm ở Bước 4 (mất trung bình 12 phút/lỗi): sinh viên bị quá tải nhận thức khi phải mở nhiều tab, đọc lướt các bài viết từ nhiều năm trước với phiên bản thư viện cũ, dẫn đến việc copy-paste code sửa thử sai một cách may rủi (Bước 5) mà không giải quyết được tận gốc vấn đề.
```

### 5.2. Future workflow bản nhóm

Phải nhìn ra 5 thứ: bước nào máy (Rule), bước nào AI, bước nào người, boundary ở đâu, fallback khi AI sai.

```text
FUTURE STATE — 4 bước, tổng cộng 10 phút

[1 Cung cấp mã lỗi + đoạn code ngữ cảnh: 2' - Người nhập]
  → [2 Rule tiền xử lý lọc cú pháp + AI phân tích root-cause & checklist: 1' - Máy & AI]
  → [3 Sinh viên đọc hiểu nguyên nhân & tự tay sửa code: 5' - Human boundary]
  → [4 Chạy test xác nhận kết quả: 2' - Người kiểm thử]

Fallback: nếu giải thích của AI không rõ hoặc code mẫu lệch thư viện → Mở kho bookmark tài liệu chuẩn của môn học hoặc đặt breakpoint trong VS Code Debugger.
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Tổng thời gian xử lý 1 lỗi | 35 phút | 10 phút (giảm >70%) | Bấm giờ thực tế từ lúc lỗi xuất hiện đến khi chạy pass |
| Số bước quy trình | 7 bước | 4 bước | Đếm số bước thao tác |
| Số bước thủ công mò mẫm | 5 bước (search, lọc, paste, đoán mò, lặp lại) | 1 bước (sinh viên tự sửa code sau khi hiểu bản chất) | Đánh giá qua nhật ký thao tác của người học |
| Bottleneck chính | Lọc thông tin giữa 5-8 tab mạng (12') | Đọc hiểu và tự sửa code (5') | Chuyển từ "mò mẫm thụ động" sang "tư duy chủ động" (Human boundary lành mạnh) |
| Risk mới | Không có AI hallucination, nhưng code chắp vá dễ bug ngầm | AI có thể giải thích nhầm ngữ cảnh bài tập | Kiểm soát bằng Human-in-the-loop + Fallback dùng debugger |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên ngành Công nghệ Thông tin đang học các môn lập trình/AI thực hành, thường xuyên phải tự viết code và chạy thử nghiệm các bài tập hàng tuần. |
| **Workflow** | Khi chạy chương trình bị lỗi, sinh viên đọc stack trace, copy dòng lỗi tra cứu Google/GitHub, mở nhiều bài viết trên mạng để tìm code mẫu chắp vá, sửa thử và lặp lại nếu vẫn lỗi. |
| **Bottleneck** | Bước tìm kiếm và chọn lọc thông tin giữa ma trận kết quả tìm kiếm mất nhiều thời gian nhất (chiếm hơn 35% thời gian xử lý) vì kết quả không khớp phiên bản thư viện hoặc sai ngữ cảnh bài tập. |
| **Impact** | Mỗi lỗi làm mất 20-40 phút, trung bình 60-200 phút/tuần; khiến sinh viên nản lòng, chậm deadline nộp bài và code mang tính chắp vá ăn may mà không hiểu sâu bản chất kỹ thuật. |
| **Success Metric** | Giảm thời gian xử lý một lỗi từ 35 phút xuống dưới 10-15 phút; giảm số nguồn/tab phải mở từ 5-8 trang xuống còn 1 giao diện; 100% người học giải thích được nguyên nhân gây lỗi sau khi sửa. |
| **Boundary** | AI chỉ được phép khoanh vùng dòng lỗi, giải thích cơ chế gây lỗi và đưa ra checklist các bước kiểm tra gợi ý; AI tuyệt đối không tự động sinh toàn bộ code sửa hoặc đè code lên file của người học. |

**Câu hỏi AI phản biện v0 (nếu có):**
- Field nào mơ hồ: Boundary ban đầu chưa nói rõ trường hợp lỗi do môi trường cài đặt (như thiếu package) thì xử lý thế nào.
- Tôi sửa gì: Bổ sung ranh giới: nếu là lỗi thiếu package/môi trường thì AI đưa lệnh cài đặt cụ thể; nếu là lỗi logic thuật toán thì chỉ gợi ý hướng tư duy, không giải bài hộ.

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [x] Thấp (có đúng/sai rõ) / [ ] Cao (nhiều cách trả lời vẫn OK) — Vì sao: Chương trình chạy pass hết test case hay bị crash là kết quả khách quan, stack trace và mã lỗi có cấu trúc chuẩn xác rõ ràng.
- Độ phức tạp: [ ] Thấp (1-2 bước) / [x] Cao (3+ bước/nguồn, phụ thuộc nhau) — Vì sao: Cần phân tích tương quan giữa nhiều dòng code, dòng thông báo lỗi, kiểu dữ liệu truyền vào và phiên bản của các thư viện bên ngoài.

**Bài toán nhóm nằm ở ô nào:**

```text
Độ mơ hồ THẤP — Độ phức tạp CAO (Structured & Complex Problem).
```

**Vì sao (2-3 câu):**

```text
Mặc dù tiêu chí đánh giá đúng/sai của code rất rõ ràng (không mơ hồ), nhưng việc tìm ra nguyên nhân gốc rễ lại đòi hỏi khả năng đọc hiểu ngữ cảnh liên kết giữa nhiều đoạn mã và thông báo ngoại lệ. Do đó, bài toán vượt quá khả năng của các câu lệnh điều kiện Rule-based đơn giản, nhưng lại có tính cấu trúc cao nên cực kỳ phù hợp với một Workflow có AI phân tích ngữ cảnh.
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | Dùng bảng tra cứu tĩnh mã lỗi (Regex mapping): bắt từ khóa như `ModuleNotFoundError` để gợi ý `pip install`, bắt `IndentationError` để nhắc căn lề | Khi gặp các lỗi cú pháp cơ bản và lỗi thiếu package phổ biến (chiếm khoảng 20-25% số lỗi) | Hoàn toàn bất lực trước các lỗi logic thuật toán, lỗi ép sai kiểu dữ liệu phức tạp hoặc lỗi phụ thuộc ngữ cảnh code | **DÙNG PHỤ**: Làm bộ lọc tiền xử lý ở Bước 2 để giải quyết siêu tốc các lỗi cú pháp đơn giản trước khi gọi AI |
| **Workflow** | Chuỗi pipeline tuần tự: Nhận đầu vào (Code + Error) → Tiền xử lý lọc lỗi → AI phân tích root-cause & sinh checklist kiểm tra → Sinh viên tự sửa code → Chạy test | Đủ cho 100% các bài tập lập trình của sinh viên vì các bước xử lý đi theo một luồng tuyến tính cố định | Rủi ro AI bịa hoặc giải thích chung chung nếu sinh viên cung cấp đoạn code quá ngắn hoặc thiếu ngữ cảnh | **CHỌN CHÍNH THỨC**: Là khung giải pháp cốt lõi của cả bài toán |
| **Agent** | Xây dựng Agent tự chủ: tự đọc file, tự mở terminal chạy lệnh test, tự sửa file code và tự commit lên GitHub nếu pass | Chỉ phù hợp với hệ thống auto-healing trong môi trường production của doanh nghiệp lớn | Rất nguy hiểm trong giáo dục vì triệt tiêu tư duy của sinh viên; dễ lặp vô tận (infinite loop) tốn token và có nguy cơ sửa hỏng toàn bộ logic bài tập | **KHÔNG CHỌN**: Quá phức tạp, vi phạm mục tiêu học tập và rủi ro mất kiểm soát cao |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. Rule có giải được 70-80% case không?  
$\rightarrow$ **Không.** Rule chỉ xử lý được khoảng 20-25% các lỗi cú pháp cơ bản; 75-80% lỗi runtime và lỗi logic phức tạp bắt buộc phải có khả năng hiểu ngữ cảnh mã nguồn.
2. Các bước có đi thẳng một đường không hay phải rẽ nhánh?  
$\rightarrow$ **Đi thẳng một đường tuyến tính.** Quy trình xử lý luôn tuần tự: Nhận lỗi $\rightarrow$ Phân tích $\rightarrow$ Người tự sửa $\rightarrow$ Chạy test. Chỉ rẽ nhánh quay lại nếu chạy test vẫn chưa đạt.
3. Có thật sự cần Agent tự lập kế hoạch + gọi tool không?  
$\rightarrow$ **Hoàn toàn không cần.** Quy trình debug bài tập đã được xác định trước các bước rõ ràng; sinh viên là người nắm quyền thực thi và kiểm tra, không cần giao quyền tự chủ cho máy.
4. Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu?  
$\rightarrow$ **Sinh viên phát hiện ngay lập tức** trong vòng 1-2 phút khi bấm chạy lại chương trình và thấy test case không pass.
5. Có hạ được từ Agent → Workflow → Rule không?  
$\rightarrow$ **Đã hạ thành công từ Agent xuống Workflow.** Nhóm giữ Workflow làm khung chính và tích hợp thêm Rule cho các lỗi thiếu package đơn giản để tối ưu chi phí và tốc độ.

**Mức chọn:**

```text
Workflow
```

**Vì sao chọn (3-4 câu):**

```text
Nhóm chọn Workflow vì đây là điểm cân bằng hoàn hảo giữa năng lực phân tích ngữ cảnh của AI và sự kiểm soát của con người. Quy trình debug bài tập là một chuỗi tuyến tính đã được chuẩn hóa (Input → Phân tích → Sửa → Test), hoàn toàn không cần AI phải tự lập kế hoạch đa bước phức tạp. Quan trọng nhất, Workflow cho phép thiết lập ranh giới con người (Human boundary) rõ ràng: AI giải thích và định hướng, sinh viên trực tiếp tư duy và sửa code, giữ vững mục tiêu sư phạm của môn học.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Mức Rule-based quá cứng nhắc và thô sơ, chỉ tra cứu được các từ khóa lỗi bề mặt và không thể hiểu được mối quan hệ logic giữa các biến số trong bài tập. Nếu chỉ dùng Rule, sinh viên vẫn sẽ phải tự mình lặn ngụp tìm kiếm trên Google cho hơn 75% các lỗi runtime còn lại.
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên ngành Công nghệ Thông tin đang thực hành các môn học lập trình và ứng dụng AI (như Python, Data Structures, Machine Learning). |
| **Workflow** | Chạy code bị lỗi $\rightarrow$ cung cấp error message + đoạn code ngữ cảnh vào hệ thống $\rightarrow$ nhận bản giải thích nguyên nhân gốc rễ và checklist gợi ý 3 bước $\rightarrow$ sinh viên tự đọc hiểu và sửa code $\rightarrow$ chạy test kiểm tra lại. |
| **Bottleneck** | Bước tìm kiếm, đọc lướt và lọc thông tin giữa 5-8 tab bài viết không cùng phiên bản trên Google/StackOverflow (chiếm 12-15 phút/lỗi và gây quá tải nhận thức). |
| **Impact** | Mỗi lỗi làm mất 20-40 phút thử sai may rủi, tổng cộng 60-200 phút/tuần; gây nản lòng, chậm tiến độ nộp lab và hình thành thói quen chắp vá code mà không hiểu sâu kỹ thuật. |
| **Success Metric** | Giảm thời gian xử lý một lỗi từ 35 phút xuống dưới 10-15 phút; giảm số nguồn/tab ngoài phải mở về 0 tab; 100% sinh viên giải thích được cơ chế gây lỗi sau khi sửa xong bài. |
| **Boundary** (làm / không làm) | **LÀM:** Khoanh vùng dòng lỗi, giải thích cơ chế gây lỗi bằng ngôn ngữ giản dị, đưa checklist gợi ý kiểm tra, cung cấp lệnh cài đặt nếu thiếu package.<br>**KHÔNG LÀM:** Không tự động sửa file code; không sinh ra đoạn code giải bài tập hoàn chỉnh để copy-paste; không can thiệp vào các bài thi/kiểm tra cấm sử dụng AI. |
| **AI intervention point** (can thiệp sau bước nào, trước bước nào) | Can thiệp ngay **sau** bước nhận thông báo lỗi runtime và **trước** bước sinh viên bắt tay vào thao tác chỉnh sửa mã nguồn. |
| **Mức chọn** (Rule / Workflow / Agent + 1 câu vì sao) | **Workflow** — vì bài toán có các bước xử lý tuần tự rõ ràng, AI đóng vai trò phân tích nhận thức còn sinh viên giữ vai trò thực thi và kiểm duyệt (Human-in-the-loop). |
| **Rủi ro & người thật kiểm tra** (rủi ro lớn nhất + ai kiểm tra bằng cách nào) | Rủi ro lớn nhất là AI giải thích sai ngữ cảnh bài tập hoặc đề xuất thư viện không tương thích $\rightarrow$ **Người kiểm tra:** Chính sinh viên sẽ chạy lại bộ test case thực tế trên máy local để xác minh trong vòng 2 phút. |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | Yes | Actor là sinh viên CNTT làm bài tập và quy trình 4 bước đã được mô tả chi tiết đến từng phút. |
| Baseline + metric đo được chưa? | Yes | Baseline là 35 phút/lỗi (đo qua khảo sát 12 sinh viên), mục tiêu giảm xuống dưới 10-15 phút đo bằng bấm giờ. |
| Data/input đủ dùng chưa? | Yes | Input là mã lỗi stack trace và đoạn code bài tập sẵn có ngay trên màn hình IDE của sinh viên. |
| AI sai, hậu quả chấp nhận được không? | Yes | Nếu AI giải thích chưa đúng, sinh viên chỉ mất thêm 2 phút chạy test và chuyển sang phương án Fallback thông thường. |
| Có người review/owner không? | Yes | Sinh viên chính là người review trực tiếp từng dòng gợi ý trước khi áp dụng vào bài của mình. |
| Có cách non-AI đơn giản hơn không? | Yes (nhưng không đủ) | Cách non-AI là đọc tài liệu chính thức (Docs), nhưng sinh viên mới học không đủ thời gian và kỹ năng để đọc tài liệu tiếng Anh dài hàng chục trang. |

**Decision:**

```text
Go
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
Nhóm đưa ra quyết định Go vì cả 6 tiêu chí đánh giá mức độ sẵn sàng đều đạt trạng thái Yes thuyết phục. Vấn đề có nỗi đau thực tế đã được kiểm chứng bởi 83.3% sinh viên được khảo sát và dữ liệu đầu vào (code + lỗi) luôn sẵn có mà không phụ thuộc vào bên thứ ba. Giải pháp được chốt ở mức Workflow có ranh giới con người rõ ràng, kiểm soát triệt để rủi ro hallucination bằng việc chạy test độc lập. Đây là một bài toán khả thi, có impact đo lường sắc nét và hoàn toàn có thể triển khai thử nghiệm hiệu quả ngay trong khuôn khổ lab.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
- Data thử nghiệm: 10 lỗi runtime thực tế từ bài tập tuần trước của lớp (5 lỗi TypeError/IndexError trong thuật toán xử lý dữ liệu và 5 lỗi cấu hình/gọi hàm trong thư viện PyTorch/Pandas).
- Cách chạy tay (bán tự động): Sinh viên copy mã lỗi và đoạn code dán vào template prompt đã được chuẩn hóa trên giao diện AI, đọc phần phân tích và tự tay sửa code trên VS Code.
- Đo lường 3 số liệu:
  1. Thời gian từ lúc lỗi xuất hiện đến khi chạy pass test case (kỳ vọng: dưới 12 phút).
  2. Số lần phải mở thêm tab tra cứu Google ngoài (kỳ vọng: 0 lần).
  3. Tỷ lệ sinh viên tự tin giải thích lại được cơ chế gây lỗi khi được hỏi nhanh (kỳ vọng: 100%).
```

**Nếu Not Yet — cần validate gì trước:**

```text
(Không áp dụng vì nhóm đã quyết định Go)
```

**Nếu No-Go — làm gì thay AI:**

```text
(Không áp dụng vì nhóm đã quyết định Go)
```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
Nhóm sẽ dừng sử dụng giải pháp và quay về cách debug truyền thống (tra Google / hỏi giảng viên) nếu xảy ra 1 trong 2 điều kiện:
1. AI đưa ra giải thích sai lệch hoặc ảo giác trong 3 lỗi liên tiếp khiến sinh viên tốn hơn 40 phút mà không sửa được bài.
2. Sinh viên có dấu hiệu ỷ lại, chỉ tìm cách copy-paste code mà không đọc hiểu phần giải thích nguyên nhân gốc rễ, làm giảm kết quả bài kiểm tra thực hành độc lập.
```

---

### Self-check nộp phần 02 (nhóm)
- [x] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [x] Có validation (quote thật) + research (link kiểm được)
- [x] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [x] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [x] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do

