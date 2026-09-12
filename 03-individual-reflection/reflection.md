# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Bùi Minh Quân
- Mã học viên: 2A202602958
- Nhóm: Nhóm T1 - ZoneA
- Candidate problem nhóm chọn: Chuyển đổi paper và tài liệu kỹ thuật tiếng Anh thành phương án triển khai thực tế.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tôi đưa ra ba problem về checklist bài nộp, gộp report nhóm và tìm quyết định trong group chat. | Nhóm có thêm các candidate gần với bối cảnh học tập và làm việc nhóm để so sánh với problem đọc paper. |
| Pitch Problem Card | Tôi trình bày problem biến yêu cầu bài nộp rời rạc thành checklist có thể kiểm tra, cùng bottleneck và metric thời gian. | Nhóm có một candidate dễ làm bằng template/Rule, giúp so sánh công bằng với các bài cần AI. |
| Challenge bài của bạn khác | Tôi đặt câu hỏi về việc AI có thực sự giảm thời gian hay chỉ chuyển effort sang kiểm tra output, và ai chịu trách nhiệm khi AI sai. | Nhóm chú ý hơn đến human boundary thay vì chỉ tập trung vào việc dùng AI. |
| Gom trùng / cluster | Tôi góp ý gom các ý về đọc paper, trích xuất công thức và thông số kỹ thuật vào cùng một cụm. | Nhóm nhận ra problem của Vĩ và Tuấn có cùng bottleneck, từ đó hội tụ vào một candidate mạnh hơn. |
| Chọn candidate problem | Tôi so sánh các candidate theo actor, workflow, impact, data access và khả năng đo metric. | Nhóm chọn bài toán trích xuất Math & Engineering Spec Sheet với điểm 34/35. |
| Validation / research | Tôi đọc và rà lại các bằng chứng phỏng vấn, khảo sát cùng research về Elicit, Papers With Code và NotebookLM. | Phần research phân biệt được công cụ tóm tắt chung với workflow trích xuất thông số kỹ thuật có schema. |
| Workflow nhóm | Tôi kiểm tra lại các bước trước/sau, tổng thời gian 145 phút xuống 35 phút và vị trí human audit 20 phút. | Workflow thể hiện rõ Rule parser, LLM extraction, người review và fallback khi công thức khó hoặc AI sai. |
| Problem Statement | Tôi rà câu chữ của v0/v1 để actor, bottleneck, metric và boundary không bị trộn lẫn. | Problem Statement được thu hẹp vào trích xuất có citation, không tự sinh slide hay tự viết code triển khai. |
| Rule / Workflow / Agent | Tôi phản biện việc dùng Agent tự trị và ủng hộ Workflow có schema cố định, evidence và human review. | Nhóm chọn được mức Workflow, chỉ dùng Rule ở bước tiền xử lý PDF và không giao cho Agent quyền tự quyết định deploy. |
| Decision | Tôi kiểm tra sự nhất quán giữa baseline, success metric, pilot và rollback threshold. | Quyết định GO có điều kiện pilot, đo accuracy/unsupported claim rate và quay về cách thủ công nếu rủi ro vượt ngưỡng. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Phần có dấu tay rõ nhất của tôi là rà soát và viết lại các phần mô tả workflow, Problem Statement và quyết định cuối. Tôi giúp nhóm giữ đúng ranh giới: AI chỉ trích xuất có cấu trúc và dẫn nguồn, còn kỹ sư vẫn kiểm tra công thức, giả định ngầm và quyết định triển khai.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Tôi dùng AI để gợi ý thêm các problem theo bốn lăng kính sau khi tự scan. | AI giúp mở rộng góc nhìn và gợi ý metric. | Một số ý quá rộng như trợ lý quản lý toàn bộ việc học, không có bottleneck cụ thể. | Tôi bỏ các ý chung chung và giữ các problem có actor, workflow và số đo rõ. |
| Problem Card | Tôi dùng AI để phản biện ba card và tìm điểm yếu. | AI giúp chỉ ra rủi ro AI có thể bỏ sót yêu cầu hoặc làm mất ý. | AI không biết chắc những con số đó có phải số đo thực tế của tôi hay không. | Tôi ghi chúng là baseline quan sát/ước lượng và thêm non-AI alternative, metric và fallback. |
| Workflow | Tôi dùng AI để kiểm tra cách diễn đạt current/future workflow và human boundary. | AI giúp nhìn ra chỗ nên tách Rule, AI và người. | AI dễ làm workflow trông quá tự động và bỏ qua thời gian review. | Tôi giữ bước human audit 20 phút, citation và fallback đọc PDF gốc. |
| Research | Tôi dùng AI để gợi ý các tool/pattern liên quan đến đọc paper và structured extraction. | AI giúp nhóm nhanh chóng lập danh sách công cụ để kiểm tra. | AI có thể mô tả khả năng sản phẩm quá rộng hoặc đưa link chưa đủ chính thức. | Tôi chỉ giữ các link có thể kiểm tra và ghi rõ khoảng trống của Elicit, Papers With Code và NotebookLM. |
| Problem Statement | Tôi dùng AI để phản biện độ rõ của actor, bottleneck, metric và boundary. | AI giúp phát hiện các câu còn mơ hồ và sự không nhất quán giữa v0/v1. | AI không thể tự xác nhận metric 145 phút, 35 phút hay accuracy có đạt được thật hay không. | Tôi đối chiếu lại với workflow, validation và biến metric thành mục tiêu pilot thay vì kết quả đã chứng minh. |
| Rule / Workflow / Agent | Tôi dùng AI để so sánh ba mức Rule, Workflow và Agent. | AI giúp làm rõ Agent là quá mức cần thiết vì quy trình đã định hình. | AI có xu hướng đề xuất Agent vì nghe mạnh hơn, dù không cần autonomous planning. | Tôi chọn Workflow, dùng Rule cho parse section và giới hạn LLM trong schema extraction. |
| Decision | Tôi dùng AI như một người phản biện cho pilot và rollback. | AI giúp gợi ý các failure case như hallucination, thiếu evidence và output chậm. | AI không thể thay nhóm chốt mức rủi ro chấp nhận được. | Nhóm tự chốt GO có điều kiện, pilot 20 paper và rollback khi unsupported claim rate vượt ngưỡng. |

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
Khi nghe top 3 của các bạn, tôi nhận ra không phải problem nào có AI cũng nên làm thành Agent. Các ý về group chat và checklist đều có pain thật, nhưng một phần lớn có thể giải quyết bằng decision log, template hoặc Rule đơn giản. Nhóm chỉ hội tụ vào bài đọc paper sau khi thấy ý của Vĩ và Tuấn cùng gặp một bottleneck: người đọc phải mất rất nhiều thời gian để giải mã Methodology và tìm thông số triển khai rải rác. Tôi thay đổi cách nhìn từ “tóm tắt paper” sang “trích xuất một bản đặc tả kỹ thuật có thể hành động”. Điều khó nhất khi viết Problem Statement là phân biệt kết quả AI tạo ra với quyết định mà con người được phép tin. Vì AI có thể hiểu sai công thức hoặc bỏ qua giả định ngầm, nhóm phải thêm citation, giá trị NOT REPORTED và human audit 20 phút. Tôi đóng góp chủ yếu ở việc rà lại câu chữ, kiểm tra sự nhất quán giữa workflow, metric và boundary, rồi viết các phần đó thành một mạch dễ theo dõi. Tôi cũng nhận ra metric 145 phút xuống 35 phút mới chỉ là kỳ vọng, nên cần pilot và cách đo chứ không thể trình bày như một kết quả đã được chứng minh. Nếu làm lại, tôi sẽ challenge sớm hơn về nguồn gốc của số liệu khảo sát và cách đánh giá “đúng” đối với công thức toán. Tôi sẽ đề nghị nhóm chuẩn bị trước một bộ paper mẫu và một checklist chấm lỗi để đo Field-level Spec Accuracy nhất quán hơn. Bài học lớn nhất của tôi là một workflow AI tốt không nằm ở việc tự động hóa nhiều nhất, mà ở việc phân chia đúng phần máy làm, phần người kiểm tra và điều kiện quay về quy trình cũ.
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

