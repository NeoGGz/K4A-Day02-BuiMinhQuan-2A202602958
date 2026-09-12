# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|---------------------------------------------------------------|
| 1   | Trần Chí Vĩ - 2A202602968 | Facilitator & Technical Lead (Workflow + R/W/A Analysis)     |
| 2   | Trần Đức Quân - 2A202602922   | Validation Lead & Workflow Diagrammer                        |
| 3   | Hoàng Minh Tuấn - 2A202602758   | Research Lead (AI Tools Benchmark)                           |
| 4   | Bùi Minh Quân - 2A202602958   | Quality Reviewer & Document Writer                           |
| 5   | Nguyễn Phi Nhật - 2A202602658   | Challenge Owner (Phản biện rủi ro)                           |
| 6   | Nguyễn Nam Khánh - 2A202602568      | Data Handoff & Boundary Verifier                             |

**Candidate problem nhóm chọn (1 câu):**
Người nghiên cứu/thuyết trình seminar mất trung bình 145 phút để tóm tắt và trích xuất phương pháp luận toán học/triển khai kỹ thuật từ bài báo khoa học 15-20 trang, trong đó bước đọc hiểu chi tiết công thức toán và thông số kỹ thuật là điểm nghẽn lớn nhất gây cạn kiệt trí lực.

---

## Phase 3 — Group Convergence: từ 18 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Vĩ | Tóm tắt paper & trích xuất công thức toán cho Seminar | Speaker seminar / Quant Dev | Đọc hiểu Methodology toán (60') | Workflow rõ, bài toán lặp lại hàng tuần, pain rất lớn |
| 2 | Vĩ | Tái hiện reward function từ paper sang code Python | Quant Developer | Debug vector/ma trận numpy (25') | Kỹ thuật sâu nhưng rủi ro AI code sai logic |
| 3 | Vĩ | Tổng hợp note video lecture siêu dài (VIN AI) | Học viên VIN AI | Vừa nghe vừa gõ note thủ công (60') | Pain lớn về thể lực nhưng đã có công cụ Whisper |
| 4 | Đức Quân | Tự động chọn giờ rời nhà theo xe buýt/giao thông | Nhân viên văn phòng | Đoán sai giờ giao thông thực tế (10') | Workflow cá nhân, khó tích hợp API real-time ổn định |
| 5 | Đức Quân | Tóm tắt nhóm chat công việc bị lỡ | Nhân viên văn phòng | Cuộn đọc 50-200 tin nhắn rác (15') | Rất phổ biến, impact cao nhưng vướng bảo mật |
| 6 | Đức Quân | Nhắc trả lời tin nhắn quan trọng bị quên | Người bận rộn | Quên reply vì đang bận việc khác | Dễ giải quyết bằng Rule/Reminder thủ công |
| 7 | Minh Tuấn | Review dữ liệu trực quan quy mô lớn (CV) | ML Engineer | Tắc nghẽn sự chú ý khi xem ảnh | Rất hay, có thể phân định ranh giới Human-AI rõ |
| 8 | Minh Tuấn | Chuyển đổi technical paper thành phương án triển khai | AI Engineer | Lãng phí 70% thời gian đọc văn phong học thuật | **Cực kỳ giống ý số 1 của Vĩ**, bottleneck rất rõ |
| 9 | Minh Tuấn | Quản trị nguồn gốc & phân tích bằng chứng ML | ML Researcher | Đối chiếu log/checkpoint nhiều lần | Scope hơi hẹp, phụ thuộc framework |
| 10 | Minh Quân | Biến yêu cầu bài nộp rời rạc thành checklist | Sinh viên | Bỏ sót field trước deadline | Pain vừa phải, dễ giải quyết bằng template |
| 11 | Minh Quân | Hợp nhất phần việc nhóm thành report | Trưởng nhóm | Ghép nội dung & sửa format (45') | Rủi ro AI làm mất định dạng gốc |
| 12 | Minh Quân | Khôi phục quyết định cũ từ group chat | Team member | Tìm lại message cũ (15') | Rủi ro data access giống ý số 5 |
| 13 | Nhật | Review Code (PR) sơ sài bỏ qua bug logic | Dev / Reviewer | PR quá dài, khó soi kĩ logic | Bài toán kinh điển nhưng vướng bảo mật source code |
| 14 | Nhật | Đọc hiểu mã nguồn cũ không comment | Developer | Phân tích spaghetti code | Khó kiểm soát độ chính xác của AI |
| 15 | Nhật | Nhận Bug Ticket mô tả mơ hồ từ Tester | Dev / Tester | Thiếu log, thiếu steps tái hiện | Cần Process Fix (Rule tạo ticket) hơn là AI |
| 16 | Khánh | Theo dõi bàn giao sự kiện CLB | BTC Sự kiện | Trôi thông tin requirement trên chat | Giống ý số 5/12, cần tool quản lý task hơn AI |
| 17 | Khánh | Quản lý phân công & thay đổi giảng viên | Điều phối viên | Conflict lịch, workload, preference | Rất phức tạp, mang tính tối ưu hóa (Optimization) |
| 18 | Khánh | Điều phối deadline & đặt cơ sở vật chất | Sinh viên | Thông tin phân mảnh nhiều nguồn | Cần Calendar/Hub tập trung thay vì AI |

### 3.2. Gom trùng / cluster (gom 18 ý thành 4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| **A** | 1 (Vĩ), 8 (Tuấn), 3 (Vĩ) | **Trích xuất & Tóm tắt Tri thức Kỹ thuật:** Xử lý tài liệu dài (Paper 15-20 trang, Lecture) thành thông tin cốt lõi (Toán học, Thông số triển khai). | Pain point chung của nhóm kỹ thuật/nghiên cứu. Workflow rất rõ, lặp lại cao, bottleneck là sự cạn kiệt trí lực. |
| **B** | 5, 12, 16, 11, 2, 7, 9, 13, 14, 15 | **Review & Tìm kiếm Dữ liệu Phân mảnh:** Lọc ý chính từ chat, log, code, PR, bug ticket. | Phổ biến nhưng vướng rào cản bảo mật dữ liệu doanh nghiệp cực lớn. |
| **C** | 4, 17, 18 | **Lịch trình & Tối ưu hóa Nguồn lực:** Xếp lịch giảng viên, đặt phòng, chọn giờ đi xe buýt. | Đòi hỏi API thời gian thực hoặc giải thuật Tối ưu hóa (Operations Research) hơn là AI GenAI. |
| **D** | 6, 10 | **Task Management:** Quên reply tin nhắn, lập checklist bài nộp. | Giải quyết hiệu quả bằng Rule/Automation đơn giản. |

### 3.3. Shortlist (giữ 3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| **Tóm tắt Paper & Trích xuất Toán/Kỹ thuật (Gộp #1 & #8)** | - Actor rõ (Người nghiên cứu / Kỹ sư AI / Speaker seminar).<br>- Điểm nghẽn đồng điệu giữa Vĩ (toán) và Tuấn (technical config).<br>- Metric đo lường thời gian cụ thể (145' → 35'). | Khả năng AI bị hallucinate ký hiệu toán học hoặc bỏ qua giả định ngầm (implicit assumptions) của tác giả. |
| **Tóm tắt nhóm chat công việc (#5 & #12)** | - Rất nhiều thành viên gặp (Đức Quân, Minh Quân, Khánh).<br>- Thời gian lãng phí rõ (15-25 phút/lần cuộn chat). | Quyền truy cập API vào Zalo/Slack và vấn đề bảo mật dữ liệu nội bộ. |
| **Review Dữ liệu CV Human-in-the-loop (#7)** | - Workflow phân định rất rõ No-AI (GUI) vs AI (Anomaly Prioritization) vs Human (Phán quyết). | Xác định ngưỡng ranking (top bao nhiêu %) để không gây quá tải cho người review. |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Tóm tắt Paper & Trích xuất (#1 & #8)** | 5 | 5 | 5 | 5 | 4 | 5 | 5 | **34** |
| Review Dữ liệu CV (#7) | 4 | 5 | 4 | 4 | 3 | 5 | 4 | **29** |
| Tóm tắt Group Chat (#5 & #12) | 5 | 4 | 5 | 4 | 2 | 4 | 4 | **28** |

**Candidate nhóm chọn (1 bài duy nhất):**

```text
Actionable Math & Engineering Spec Sheet Extraction for Technical Papers
(Tóm tắt có cấu trúc & Trích xuất Thuật toán / Thông số Kỹ thuật từ Bài báo Khoa học 15–20 trang)
```

**Vì sao chọn (4-5 câu):**
Sự hội tụ ý tưởng giữa Vĩ (tập trung giải mã toán học) và Tuấn (tập trung bóc tách technical implementation) cho thấy đây là nút thắt chung lớn nhất của cả nhóm nghiên cứu AI. Workflow 5 bước hiện tại tiêu tốn trung bình 145 phút/paper, trong đó bước giải mã Methodology toán học (60') và tìm kiếm thông số triển khai rải rác (35') là nguyên nhân chính gây cạn kiệt trí lực. Đề tài tập trung vào việc tạo ra một **bản đặc tả kỹ thuật trung gian (Math & Engineering Spec Sheet)** chuẩn hóa, phục vụ trực tiếp cho cả hai nhu cầu: chuẩn bị thuyết trình seminar và đánh giá tính khả thi triển khai PoC. Bài toán hoàn toàn an toàn về mặt dữ liệu (PDF học thuật công khai) và cho phép thiết lập ranh giới Human Boundary 20 phút rõ ràng.

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**
- *Review Dữ liệu CV:* Có pain evidence rất mạnh (thành viên Tuấn đã tự tay code GUI riêng để giải quyết), nhưng bài toán đòi hỏi dataset hình ảnh, pipeline CV và công cụ visualization chuyên biệt nên ít thành viên trong nhóm có thể cùng tham gia pilot và đánh giá thực tế hơn.
- *Tóm tắt Group Chat:* Dù có tần suất gặp cao nhưng vướng phải rào cản bảo mật dữ liệu nội bộ nghiêm ngặt và khó thiết lập API trích xuất tin nhắn an toàn trong khuôn khổ lab.

**Disagreement (nếu có — ai lo gì, chốt ra sao):**
Nhật và Minh Tuấn lo ngại AI sẽ diễn giải sai lệch các ký hiệu toán học hoặc bỏ sót các giả định ngầm của tác giả. Cả nhóm đã thống nhất giải pháp: Không để AI tự do sinh văn bản, mà ép trích xuất theo Schema 5 trường kỹ thuật + Math Sheet, đồng thời bắt buộc chèn một bước **Human Audit Boundary (20 phút)** để người nghiên cứu đối chiếu 1-1 với số trang PDF gốc.

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (Phỏng vấn thực tế + Khảo sát kỹ sư)

Nhóm đã thực hiện phỏng vấn sâu 2 đối tượng thực tế và làm khảo sát với 12 kỹ sư/sinh viên chuyên ngành AI:

1. **Phỏng vấn bạn T. (AI Research Intern tại Lab thị giác máy tính):**
   > *"Mỗi tuần em phải chuẩn bị 1 buổi thuyết trình seminar và đọc 3–4 paper dài 15–20 trang. Khổ nhất là phần Methodology: tác giả dùng các ký hiệu toán học ma trận và biến số tùy biến rất phức tạp. Em mất tới 60–80 phút chỉ để tra cứu công thức và giải mã logic toán. Nhiều hôm đọc xong cạn kiệt cả trí lực, đến khi chuẩn bị slide seminar thì không còn thời gian để phân tích ưu/nhược điểm thực chiến."*  
   → **Insight:** Điểm nghẽn gây kiệt sức nhất không phải là đọc hiểu tiếng Anh, mà là **nỗ lực giải mã công thức toán học và thông số kỹ thuật bị chôn vùi trong văn phong hàn lâm**.

2. **Phỏng vấn anh D. (Senior Applied AI Engineer & Mentor đồ án):**
   > *"Khi review paper để làm seminar hoặc chuyển giao kỹ thuật, 80% thời gian chết là cố hiểu công thức toán ở phần Methodology và mò mẫm phần phụ lục Appendix để tìm tensor shape, hàm loss và hardware requirement. Chatbot tóm tắt chung chung là vô dụng. Chúng ta cần công cụ bóc tách có cấu trúc (Structured Spec & Math Logic Sheet) kèm trích dẫn số trang chính xác."*  
   → **Insight:** AI không được tóm tắt văn xuôi bay bổng, mà phải hoạt động như một công cụ **Engineering & Math Spec Sheet Extractor**.

3. **Khảo sát nhanh 12 kỹ sư và sinh viên làm đồ án AI / chuẩn bị Seminar:**
   - **100% (12/12):** Mất trung bình từ **120–160 phút** (trung bình 145 phút) cho một paper 15–20 trang.
   - **91.7% (11/12):** Xác nhận bước đọc hiểu chi tiết công thức toán học và thông số kỹ thuật là bước gây mệt mỏi nhận thức (cognitive exhaustion) nặng nề nhất.
   - **100% (12/12):** Đồng ý rằng một bản tóm tắt cấu trúc toán học và bảng 5 thông số kỹ thuật kèm citation sẽ giúp họ giảm tải hơn 70% thời gian chuẩn bị.

### 4.2. Research 2-3 giải pháp có sẵn trên thị trường

| Giải pháp | Cách họ làm | Điểm hay học được | Chỗ còn thiếu / Nhóm KHÔNG làm lại | Link kiểm chứng |
|---|---|---|---|---|
| **Elicit.org / Consensus.app** | Nền tảng AI tìm kiếm và tóm tắt bài báo khoa học dựa trên LLM | Bảng so sánh nhiều paper theo câu hỏi nghiên cứu; trích xuất kết luận chính | Tối ưu cho retrieval và tổng quan nghiên cứu lý thuyết; chưa hỗ trợ bóc tách chi tiết công thức toán hay bảng thông số kỹ thuật triển khai cho kỹ sư | [elicit.com](https://elicit.com) |
| **Papers With Code** | Thư viện cộng đồng liên kết paper với GitHub repo và benchmark | Đính kèm link mã nguồn, bảng benchmark chính thức SOTA | Chỉ có sẵn cho các paper phổ biến; không tự động bóc tách cấu trúc toán học từ file PDF của các paper mới hoặc ngách | [paperswithcode.com](https://paperswithcode.com) |
| **ChatPDF / NotebookLM** | Hỏi đáp tự do với tài liệu PDF bằng LLM RAG | Khả năng đọc hiểu tài liệu dài và trích xuất nguồn trích dẫn | Thiếu Schema kỹ thuật cố định; câu trả lời văn xuôi tự do, dễ gây nhầm lẫn ký hiệu toán học nếu người dùng không biết prompt chuẩn | [notebooklm.google.com](https://notebooklm.google.com) |

**Research takeaway (3 câu chốt):**
- Các công cụ hiện tại (Elicit, Consensus, NotebookLM) đã hỗ trợ rất tốt cho retrieval, tìm kiếm tài liệu, summarization học thuật và document Q&A, nhưng chưa được tối ưu theo workflow kỹ thuật cố định của nhóm.
- Nhóm **KHÔNG** làm lại công cụ tìm kiếm paper hay chatbot hỏi đáp tự do, mà xây dựng **Workflow chuyên biệt: Actionable Math & Engineering Spec Extractor**.
- Chìa khóa thành công là **Schema chuẩn 5 trường thông số kỹ thuật + Math Formulation Sheet** kết hợp cơ chế **Citation linking bắt buộc** trỏ thẳng về trang gốc PDF.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm (Quy trình đọc paper thủ công — 145 phút)

```text
[1. Tải PDF: 5'] 
→ [2. Đọc Abstract & Intro: 15'] 
→ [3. Đọc Methodology & Giải mã công thức toán/ký hiệu: 60'] (BOTTLENECK 1: Cạn kiệt trí lực) 
→ [4. Đọc Implementation Details & Thông số kỹ thuật rải rác: 35'] (BOTTLENECK 2: Thông số phân tán) 
→ [5. Tổng hợp ghi chép, soạn note seminar & đánh giá PoC: 30']
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1. Tìm & tải paper | Người nghiên cứu / Kỹ sư | Chủ đề nghiên cứu trên arXiv/CVPR | File PDF (15–20 trang) | 5 phút (1–2 lần/tuần) | Thao tác tìm kiếm thông thường. |
| 2. Đọc lướt tổng quan | Người nghiên cứu / Kỹ sư | File PDF | Nắm bài toán & kết quả chính | 15 phút | Đọc Abstract, Intro, Conclusion. |
| 3. Đọc sâu Methodology | Người nghiên cứu / Kỹ sư | Section Methodology, Proofs | Hiểu cơ chế thuật toán, công thức toán | **60 phút** (BOTTLENECK 1) | **Tắc nghẽn lớn nhất**: cạn kiệt trí lực do ký hiệu toán ma trận phức tạp và văn phong hàn lâm. |
| 4. Tìm thông số kỹ thuật | Người nghiên cứu / Kỹ sư | Experiments, Appendix | Thông số backbone, loss, GPU | **35 phút** (BOTTLENECK 2) | Thông tin bị giấu rải rác trong phụ lục; mất nhiều thời gian chắp vá. |
| 5. Tổng hợp & Ra quyết định | Người nghiên cứu / Kỹ sư | Kiến thức đã đọc | Spec notes phục vụ seminar / PoC | 30 phút | Tự soạn thủ công; dễ sót các giả định ngầm của tác giả. |

**Bottleneck chính (3 câu):**
Bước 3 (60 phút) và Bước 4 (35 phút) là hai điểm nghẽn nghiêm trọng nhất, tiêu tốn 95 phút căng thẳng trí não. Người đọc phải gồng mình giải mã các ký hiệu toán học trừu tượng và lùng sục thông số kỹ thuật rải rác khắp 15–20 trang paper. Tình trạng cạn kiệt trí lực khiến việc chuẩn bị slide seminar hoặc đánh giá tính khả thi PoC bị đình trệ, gây suy giảm năng suất nghiên cứu rõ rệt.

---

### 5.2. Future workflow bản nhóm (AI-Assisted Spec Extraction — 35 phút)

```text
┌────────────────────────────────────────────────────────────────────────┐
│ BƯỚC 1: RULE-BASED PDF & MATH PARSER (2 phút - MÁY)                    │
│ • Nạp PDF 15-20 trang; tự động bóc tách Section, lọc bỏ References    │
└───────────────────────────────────┬────────────────────────────────────┘
                                    │
                                    ▼
┌────────────────────────────────────────────────────────────────────────┐
│ BƯỚC 2: LLM WORKFLOW STRUCTURED EXTRACTION (3 phút - AI)               │
│ • Trích xuất theo JSON Schema 5 thông số kỹ thuật & giải mã công thức   │
│ • Đính kèm link trích dẫn (Citation) trỏ chính xác về số trang PDF gốc │
│ • Xuất bản Actionable Math & Engineering Spec Sheet                    │
│ • Đánh dấu NOT REPORTED nếu paper không đề cập thông tin               │
└───────────────────────────────────┬────────────────────────────────────┘
                                    │
                                    ▼
┌────────────────────────────────────────────────────────────────────────┐
│ BƯỚC 3: HUMAN AUDIT & REVIEW BOUNDARY (20 phút - NGƯỜI)                │
│ • Người nghiên cứu đối chiếu công thức toán với số trang PDF gốc       │
│ • Rà soát 5 thông số kỹ thuật then chốt, kiểm tra giả định ngầm        │
│ • [Fallback]: Đọc trực tiếp đoạn văn PDF nếu công thức quá dị biệt     │
└───────────────────────────────────┬────────────────────────────────────┘
                                    │
                                    ▼
┌────────────────────────────────────────────────────────────────────────┐
│ BƯỚC 4: DOWNSTREAM APPLICATION (10 phút - NGƯỜI)                       │
│ • Nhánh A (Seminar): Chốt dàn ý bài thuyết trình khoa học              │
│ • Nhánh B (PoC): Đánh giá tính khả thi kỹ thuật & lưu kho tri thức     │
└────────────────────────────────────────────────────────────────────────┘
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|:---:|:---:|---|
| **Thời gian máy trích xuất (Machine-assisted extraction)** | Không có | **~3 phút** | Thời gian chạy tự động của pipeline |
| **Thời gian bóc tách + kiểm chứng (Extraction + verification)** | 95 phút | **~23 phút** | 3 phút trích xuất AI + 20 phút người đối chiếu citation |
| **Tổng thời gian xử lý end-to-end** | **~145 phút** | **~35 phút** | Bấm giờ từ nạp PDF đến khi có Spec Sheet hoàn chỉnh (Giảm 76%) |
| **Số bước thủ công của người** | 5 bước liên tục | **2 bước** (Review spec + Quyết định) | Đếm số bước người phải trực tiếp thao tác |
| **Chốt chặn kiểm soát của con người** | Phải đọc toàn bộ 20 trang | **20 phút đối chiếu 1-1** | Human Boundary kiểm soát triệt để rủi ro ảo giác |
| **Mức độ cạn kiệt trí lực** | Rất cao (Exhausted) | Thấp (Tập trung phản biện và hiểu sâu) | Đánh giá qua khảo sát độ mệt mỏi nhận thức |

---

### 5.3. Problem Statement v0

| Field | Nội dung |
|---|---|
| **Actor** | Người nghiên cứu / Kỹ sư AI trong nhóm đồ án (Trần Chí Vĩ, Đức Quân, Minh Tuấn, Minh Quân, Nhật, Khánh). |
| **Workflow** | Tiếp nhận file PDF bài báo khoa học 15–20 trang → Đọc lướt Abstract → Đọc sâu Methodology giải mã công thức toán → Bóc tách Implementation Details → Tổng hợp tạo Math & Engineering Spec Sheet phục vụ seminar hoặc đánh giá PoC. |
| **Bottleneck** | Mất quá nhiều thời gian (95 phút) và cạn kiệt trí lực khi phải giải mã các ký hiệu toán học trừu tượng và tìm kiếm thông số triển khai kỹ thuật bị phân tán rải rác khắp 15–20 trang. |
| **Impact** | Tiêu tốn khoảng 2.4–4.8 giờ/tuần cho mỗi cá nhân (tương đương 15–30 giờ/tuần cho cả nhóm 6 người); gây kiệt sức trí tuệ trước buổi thuyết trình seminar; làm chậm tiến độ thử nghiệm PoC. |
| **Success Metric** | Giảm tổng thời gian xử lý từ 145 phút xuống dưới 35 phút/paper; Field-level Spec Accuracy ≥90%; Critical unsupported claim rate ≤5%; 100% trường thiếu thông tin được gắn cờ NOT REPORTED. |
| **Boundary** | **LÀM:** Bóc tách thông số kỹ thuật và giải mã công thức toán có cấu trúc theo Schema kèm citation số trang PDF.<br>**KHÔNG LÀM:** Không tự động sinh slide seminar hoàn chỉnh; không tự động viết mã nguồn chạy thử; không thay thế việc thẩm định chuyên môn của con người. |

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (Fit Matrix)

- **Độ mơ hồ:** **Trung bình** — Thuật ngữ toán học và kỹ thuật AI có nền tảng định nghĩa chặt chẽ, nhưng cách hành văn và biểu diễn ký hiệu giữa các tác giả rất đa dạng và phân tán.
- **Độ phức tạp:** **Cao (3+ bước & phụ thuộc ngữ cảnh)** — Tiếp nhận PDF 15–20 trang, bóc tách cấu trúc section, diễn giải công thức toán học ma trận/tích phân, đối chiếu với bối cảnh tài nguyên triển khai thực tế.

**Bài toán nhóm nằm ở ô nào:**
> Nằm ở ô **Complexity Cao — Ambiguity Trung bình** → Miền đất lý tưởng nhất cho **Workflow AI (Chaining + Structured Output)**.

---

### 6.1. So sánh Rule / Workflow / Agent trên cùng bài toán

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | Dùng regex và script Python tìm từ khóa cứng ("loss", "learning rate", "GPU", "$$"). | Chỉ đủ khi paper tuân thủ 100% template cứng và từ khóa chuẩn xác như file cấu hình mã nguồn. | **Không đủ làm giải pháp độc lập**: Văn bản khoa học và ký hiệu toán học có tính phi cấu trúc cao; Rule bất lực trước việc hiểu ngữ nghĩa và liên kết logic. | **Chỉ dùng cho Bước 1** (Tách section PDF, loại bỏ Reference rác). |
| **Workflow** | **Pipeline phối hợp: PDF Parser → LLM trích xuất Schema 5 trường kỹ thuật + Math Sheet → Markdown Spec kèm Citation → Kỹ sư review 20 phút.** | Đủ cho 90% nhu cầu nghiên cứu lý thuyết và chuẩn bị tài liệu kỹ thuật của nhóm. | Rủi ro AI diễn giải sai lệch biến số toán học; kiểm soát triệt để bằng cơ chế bắt buộc đính kèm số trang trích dẫn để người verify. | **CHỌN LÀM GIẢI PHÁP CHÍNH** (Kiểm soát 100% cấu trúc, chi phí thấp, tin cậy cao). |
| **Agent** | Autonomous Agent tự động đọc paper, tự tìm repo GitHub, tự clone code về, tự sửa code và chạy thử nghiệm. | Chỉ phù hợp khi bài toán đã có môi trường sandbox khép kín và mã nguồn mở hoàn chỉnh. | Không chọn Agent vì workflow đã xác định trước, không cần autonomous planning hay tự quyết tool sequence. Agent làm tăng độ phức tạp, quyền truy cập và failure surface mà không tạo thêm giá trị cần thiết. | **KHÔNG CHỌN** (Vi phạm nguyên tắc an toàn kỹ thuật). |

**5 câu hỏi chốt:**
1. *Rule có giải được 70-80% case không?* → **Không**, vì văn bản học thuật và công thức toán là dữ liệu phi cấu trúc phức tạp.
2. *Các bước có đi thẳng một đường không hay phải rẽ nhánh?* → **Đi thẳng một đường có cấu trúc**: Parse PDF → Extract Spec & Math → Human Audit → Downstream Use.
3. *Có thật sự cần Agent tự lập kế hoạch + gọi tool không?* → **Không**, quy trình bóc tách đã được định hình rõ ràng qua Schema cố định, không cần Agent tự trị.
4. *Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu?* → **Người nghiên cứu phát hiện ngay** tại bước Human Boundary (20 phút) nhờ link trích dẫn số trang đi kèm.
5. *Có hạ được từ Agent → Workflow → Rule không?* → **Đã hạ từ Agent xuống Workflow**, và tận dụng Rule ở khâu tiền xử lý tài liệu.

**Mức chọn:** **Workflow (LLM Structured Extraction Pipeline + Human Review Boundary)**.

---

### 6.2. Problem Statement v1 (Bản hoàn chỉnh)

| Field | Nội dung chi tiết |
|---|---|
| **Actor** | Kỹ sư AI và Thành viên nghiên cứu trong nhóm đồ án (Trần Chí Vĩ, Đức Quân, Minh Tuấn, Minh Quân, Nhật, Khánh). |
| **Workflow** | Nạp file PDF bài báo khoa học 15–20 trang → Rule Parser tách section → LLM Workflow trích xuất 5 thông số kỹ thuật cốt lõi và giải mã công thức toán → Người đọc đối chiếu công thức gốc qua citation số trang (20 phút) → Tạo bản Math & Engineering Spec Sheet làm đầu vào cho Seminar hoặc PoC. |
| **Bottleneck** | Tắc nghẽn nhận thức tại khâu đọc sâu Methodology: Mất 95 phút căng thẳng trí não để giải mã các ký hiệu toán trừu tượng và lùng sục thông số triển khai kỹ thuật rải rác khắp 15–20 trang paper. |
| **Impact** | Tiêu tốn khoảng 2.4–4.8 giờ/tuần cho mỗi cá nhân (tương đương 15–30 giờ/tuần cho cả nhóm 6 người); gây cạn kiệt thể lực và trí lực trước buổi thuyết trình seminar; làm chậm tiến độ nghiên cứu PoC. |
| **Success Metric** | - **End-to-end processing time:** Giảm từ 145 phút xuống **dưới 35 phút/paper**.<br>- **Extraction + verification time:** Giảm từ 95 phút xuống **dưới 23 phút** (3' máy + 20' người audit).<br>- **Field-level Spec Accuracy:** Đạt **≥90%** trên tập pilot khi đối chiếu 1-1 với văn bản gốc.<br>- **Critical unsupported claim rate:** Đạt **≤5%** (hạn chế tối đa thông tin suy đoán không căn cứ).<br>- **Quy tắc trích xuất trung thực:** 100% trường dữ liệu không tìm thấy evidence phải được đánh dấu rõ ràng là `NOT REPORTED / UNCERTAIN`, tuyệt đối không suy đoán thành fact. |
| **Boundary (LÀM / KHÔNG LÀM)** | **LÀM:** Trích xuất thông số kỹ thuật có cấu trúc theo Schema cố định; giải mã ký hiệu toán học; tạo link trích dẫn đối chiếu số trang; lưu trữ spec vào kho tri thức chung.<br>**KHÔNG LÀM:** Không tự động sinh slide thuyết trình hoàn chỉnh; không tự động viết mã nguồn chạy thử; không thay thế việc thẩm định chuyên môn của kỹ sư khi triển khai. |
| **AI intervention point** | AI can thiệp **sau khi** PDF được parser phần mềm tách section, và **kết thúc trước khi** người đọc tiến hành rà soát và sử dụng cho seminar / PoC (Chốt chặn Human Boundary bắt buộc 20 phút). |
| **Mức giải pháp lựa chọn** | **Workflow**: Kết hợp Rule (tách file) + LLM Pipeline (trích xuất có cấu trúc) + Chốt chặn Human Boundary 20 phút của người nghiên cứu. |
| **Rủi ro & Chốt chặn kiểm soát** | **Rủi ro lớn nhất:** AI diễn giải sai lệch ký hiệu toán học hoặc bỏ sót giả định ngầm của tác giả (ảo giác).<br>**Cách kiểm soát:** Bắt buộc AI đính kèm số trang và câu trích dẫn gốc; người nghiên cứu dành 20 phút đối chiếu trực tiếp 1-1 với PDF trước khi sử dụng. |

---

### 6.3. Final decision: GO / NOT YET / NO-GO

| Câu hỏi thẩm định | Kết quả | Ghi chú bằng chứng |
|---|:---:|---|
| Actor + workflow rõ chưa? | **Yes** | 6 thành viên trong nhóm, workflow 4 bước rõ ràng từ nạp PDF đến tạo Spec Sheet. |
| Baseline + metric đo được chưa? | **Yes** | Baseline: 145 phút/paper; Kỳ vọng: 35 phút/paper; đo bằng bấm giờ thực tế. |
| Data/input đủ dùng chưa? | **Yes** | File PDF bài báo từ arXiv/CVPR/NeurIPS (15–20 trang) hoàn toàn công khai và sẵn có. |
| AI sai, hậu quả chấp nhận được không? | **Yes** | Chấp nhận được: có link trích dẫn để người đọc verify trong 20 phút, không gây ô nhiễm codebase. |
| Có người review/owner không? | **Yes** | Người nghiên cứu phụ trách bài báo chịu trách nhiệm thẩm định trực tiếp trước khi dùng. |
| Có cách non-AI đơn giản hơn không? | **Yes/No** | Non-AI (Rule/Ctrl+F) chỉ tìm được từ khóa rời rạc, bất lực trong việc giải mã logic toán học. |

**Decision:**
> ### **GO (Tiến hành thử nghiệm Pilot)**

**Lý do (4 câu chốt):**
1. **Nỗi đau thật và có độ phủ 100%:** Cả 6 thành viên đều chịu ảnh hưởng trực tiếp hằng tuần khi vừa học, vừa nghiên cứu và chuẩn bị seminar.
2. **Workflow tinh gọn, đo lường được ngay:** Cắt giảm 76% tổng thời gian (từ 145' xuống 35') và giảm thời gian bóc tách + kiểm chứng từ 95' xuống 23'.
3. **Phù hợp hoàn hảo với nguyên tắc của môn học:** Chọn mức Workflow tối ưu, phân định rạch ròi giữa máy, AI và chốt chặn con người.
4. **Rủi ro thấp và có phương án phòng ngừa chặt chẽ:** Kiểm soát ảo giác bằng trích dẫn đối chiếu trực tiếp qua Human Boundary 20 phút và quy tắc đánh dấu `NOT REPORTED`.

**Kế hoạch Pilot nhỏ nhất (Minimum Viable Pilot):**
- **Dữ liệu thử nghiệm:** 20 bài báo khoa học thực tế dài 15–20 trang từ arXiv/CVPR/NeurIPS.
- **Cách chạy tay:** Nạp PDF vào pipeline trích xuất; ghi nhận bản Spec & Math Sheet sinh ra.
- **3 chỉ số đo lường trong Pilot:**
  1. *Thời gian xử lý trung bình:* Đạt $\le 35$ phút/paper (bao gồm cả thời gian người review 20 phút).
  2. *Field-level Spec Accuracy:* Đạt $\ge 90\%$ trường dữ liệu và ký hiệu toán khớp chính xác với bài báo gốc khi đối chiếu.
  3. *Critical unsupported claim rate:* Đạt $\le 5\%$; 100% trường không có thông tin phải ghi rõ `NOT REPORTED`.

**Exit / Rollback Plan (Khi nào dừng AI, quay về cách cũ):**
- **Ngưỡng kích hoạt dừng khẩn cấp:** Nếu trong quá trình pilot, tỷ lệ sai lệch thông số kỹ thuật hoặc ký hiệu toán học then chốt (**Hallucination / Unsupported Claim Rate**) vượt quá **15%**, hoặc thời gian AI trích xuất lâu hơn **10 phút/paper**, nhóm sẽ lập tức dừng pipeline AI.
- **Phương án dự phòng:** Quay về quy trình đọc chọn lọc thủ công kết hợp bảng Checklist 5 câu hỏi toán học cốt lõi đã được chuẩn hóa.

---

### Self-check nộp phần 02 (nhóm)
- [x] Có nhật ký hội tụ từ 18 candidates về 1 bài toán có ý nghĩa sâu sắc và độ phủ cao nhất (Candidate #1 của Vĩ & #8 của Tuấn).
- [x] Có validation thực tế (phỏng vấn sâu 1 intern, 1 mentor cấp cao + khảo sát 12 kỹ sư AI với baseline 145 phút).
- [x] Có đối chuẩn công nghệ có link kiểm chứng (Elicit, Papers With Code, NotebookLM) và chỉ rõ điểm khác biệt một cách khách quan.
- [x] Có workflow trước/sau chi tiết từng phút, chỉ rõ actor, handoff, bottleneck, human boundary và fallback.
- [x] Có Problem Statement v0 và v1 đầy đủ 9 trường thông tin chuẩn mực kỹ thuật (tập trung vào Math & Engineering Spec Sheet).
- [x] Có so sánh thấu đáo Rule / Workflow / Agent và 5 câu hỏi chốt để chọn Workflow.
- [x] Quyết định GO kèm kế hoạch Pilot định lượng, quy tắc `NOT REPORTED` và kịch bản Rollback rõ ràng.
