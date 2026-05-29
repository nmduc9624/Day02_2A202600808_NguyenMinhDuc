# 01 - Individual Problem Scan

## 1. Bảng scan vấn đề cá nhân

| # | Lăng kính | Problem quan sát được | Ai đang đau? | Dấu hiệu thật |
|---|---|---|---|---|
| 1 | Tốn thời gian / Lặp lại | Sinh viên làm lab thường mất nhiều thời gian đọc lại worksheet/rubric để kiểm tra bài nộp có thiếu mục nào không. | Sinh viên làm lab cá nhân/nhóm | Trước khi nộp bài thường phải mở lại README, kiểm từng folder/file, dễ sót các mục nhỏ như reflection, workflow hoặc metric. |
| 2 | Tốn thời gian | Khi làm bài lập trình, sinh viên thường gặp log lỗi dài nhưng khó xác định lỗi chính nằm ở đâu. | Sinh viên học lập trình / làm project | Một lỗi build hoặc runtime có thể mất 20–60 phút để đọc log, tìm nguyên nhân và thử cách sửa. |
| 3 | Lặp lại | Khi làm báo cáo hoặc khóa luận, sinh viên phải nhiều lần chuyển nội dung từ code, sơ đồ, kết quả chạy thử thành đoạn mô tả bằng văn bản. | Sinh viên làm đồ án/khóa luận | Công việc này lặp lại ở nhiều chương, nhiều mục; nếu viết thủ công dễ thiếu ý hoặc không thống nhất thuật ngữ. |
| 4 | Pain từ người khác | Trong nhóm làm bài, thành viên thường hỏi lại deadline, nhiệm vụ của mình, file nào là bản mới nhất. | Nhóm sinh viên làm project/lab | Dễ nhầm phiên bản file, bỏ sót việc hoặc phải nhắn lại nhiều lần trong nhóm. |
| 5 | AI có thể tốt hơn | Sinh viên khó biết nên chọn Rule, Workflow hay Agent cho một bài toán AI Product. | Sinh viên học lab AI Product | Dễ nhảy ngay vào chatbot/agent thay vì bắt đầu từ actor, workflow, bottleneck và metric. |
| 6 | Tốn thời gian / AI có thể tốt hơn | Khi học một notebook AI/ML, sinh viên khó hiểu ý nghĩa từng cell, input/output và kết quả mô hình. | Sinh viên học AI/ML | Cần đọc code, markdown và kết quả chạy; nếu không hiểu từng bước thì khó viết báo cáo hoặc trả lời câu hỏi. |
| 7 | Lặp lại | Khi dùng Git/GitHub, sinh viên hay quên các lệnh cơ bản như add, commit, push, clone, tạo branch hoặc xử lý conflict. | Sinh viên mới dùng Git | Các lỗi/lệnh lặp lại nhiều lần nhưng mỗi lần lại phải tìm lại hoặc hỏi lại. |
| 8 | Tốn thời gian | Khi làm ứng dụng Flutter/Firebase, sinh viên mất nhiều thời gian kiểm tra logic giữa giao diện, backend/cloud và database. | Sinh viên làm project phần mềm | Một thay đổi nhỏ ở UI hoặc database có thể ảnh hưởng nhiều file, khó biết lỗi nằm ở tầng nào. |

---

## 2. Chọn Top 3 problems

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Kiểm tra bài nộp lab theo worksheet/rubric | Actor rõ, workflow rõ, xảy ra thường xuyên trước deadline, có thể đo bằng thời gian kiểm tra và số lỗi thiếu mục. | Cần kiểm chứng thêm xem nhiều sinh viên khác có gặp tình trạng tương tự không. |
| 2 | Đọc log lỗi dài khi lập trình | Pain khá rõ, ảnh hưởng trực tiếp đến thời gian làm bài/project, AI có thể hỗ trợ phân tích và khoanh vùng lỗi. | Cần giới hạn phạm vi vì lỗi lập trình rất rộng, mỗi ngôn ngữ/framework khác nhau. |
| 3 | Chuyển code/sơ đồ/kết quả thành mô tả báo cáo | Gần với trải nghiệm làm đồ án/khóa luận, workflow lặp lại nhiều lần, có thể đo bằng thời gian viết và số lần sửa. | Cần tránh để AI viết thay hoàn toàn, chỉ nên hỗ trợ cấu trúc và kiểm tra thiếu ý. |

---

# Problem Card #1

## Problem 1 câu

Sinh viên làm lab thường mất nhiều thời gian kiểm tra bài nộp theo worksheet/rubric nhưng vẫn dễ sót yêu cầu nhỏ trước khi nộp.

## Actor

Sinh viên làm lab cá nhân hoặc lab nhóm.

## Thời điểm / bối cảnh

Trước deadline nộp lab, sau khi đã hoàn thành phần nội dung chính và chuẩn bị đẩy bài lên GitHub.

## Current workflow

1. Mở lại README hoặc worksheet của lab.
2. Đọc từng yêu cầu trong phần output/deliverable.
3. Mở repo bài làm để kiểm tra folder/file.
4. So sánh từng yêu cầu với nội dung đã làm.
5. Phát hiện phần còn thiếu hoặc chưa đúng format.
6. Sửa lại file/folder.
7. Kiểm tra lại lần cuối và nộp.

## Bottleneck

Bước đối chiếu thủ công giữa rubric/worksheet và repo bài làm mất nhiều thời gian, thường khoảng 20–30 phút/lần, nhưng vẫn có khả năng sót các mục nhỏ.

## Impact

Nếu thiếu folder, thiếu reflection, thiếu workflow hoặc thiếu metric, sinh viên có thể bị trừ điểm dù phần chính đã làm. Ngoài ra, việc kiểm tra thủ công làm tăng áp lực trước deadline.

## Success metric

- Giảm thời gian tự kiểm tra bài nộp từ khoảng 25 phút xuống dưới 10 phút.
- Giảm số lỗi thiếu mục/folder/file khi nộp.
- Sinh viên biết rõ mục nào đã đủ, mục nào thiếu, mục nào chưa chắc.

## Non-AI alternative

Tạo checklist thủ công theo từng lab và tự tick từng mục trước khi nộp.

## AI hypothesis

AI có thể đọc worksheet/rubric, tách thành checklist, sau đó đối chiếu với cấu trúc repo hoặc nội dung bài làm để báo mục đủ, mục thiếu và mục chưa rõ. Sinh viên vẫn là người tự sửa và tự quyết định nộp.

## Quick gut

- [ ] No AI / process fix
- [ ] Rule
- [x] Workflow
- [ ] Agent
- [ ] Chưa biết

## Draft workflow

### Current state

```text
CURRENT STATE — khoảng 25 phút

[Đọc lại worksheet/rubric]
→ [Mở repo bài làm]
→ [Kiểm tra từng folder/file]
→ [So từng yêu cầu với bài đã làm]
→ [Tự ghi nhớ phần thiếu]
→ [Sửa bài]
→ [Kiểm tra lại]
→ [Nộp bài]

Bottleneck:
So yêu cầu với bài làm thủ công, dễ sót mục nhỏ.
```

### Future state

```text
FUTURE STATE — khoảng 8–10 phút

[Dán/upload worksheet]
→ [AI tách yêu cầu thành checklist]
→ [AI đối chiếu với repo/nội dung bài]
→ [AI báo: đủ / thiếu / chưa rõ]
→ [Sinh viên tự sửa]
→ [Sinh viên kiểm lại và nộp]

Human boundary:
AI không làm bài thay, không tự nộp bài, không quyết định điểm. AI chỉ hỗ trợ kiểm tra thiếu/đủ.
```

---

# Problem Card #2

## Problem 1 câu

Sinh viên lập trình thường mất nhiều thời gian đọc log lỗi dài để xác định nguyên nhân chính và cách sửa phù hợp.

## Actor

Sinh viên học lập trình hoặc làm project phần mềm.

## Thời điểm / bối cảnh

Khi chạy chương trình, build project, cài thư viện hoặc kết nối các thành phần như frontend, backend, database, Firebase, Flutter, Node.js.

## Current workflow

1. Chạy chương trình hoặc build project.
2. Gặp lỗi trên terminal/console.
3. Đọc log lỗi dài.
4. Copy một phần lỗi để tìm kiếm Google/Stack Overflow.
5. Thử nhiều cách sửa khác nhau.
6. Chạy lại chương trình.
7. Nếu vẫn lỗi thì tiếp tục lặp lại.

## Bottleneck

Log lỗi thường dài, có nhiều warning hoặc dòng không quan trọng. Sinh viên mới khó biết dòng nào là nguyên nhân chính. Việc thử sai có thể mất 20–60 phút cho một lỗi.

## Impact

Làm chậm tiến độ học tập/project, dễ sửa sai chỗ, đôi khi tạo thêm lỗi mới. Với sinh viên mới học, điều này cũng làm giảm động lực vì không hiểu lỗi thật sự đến từ đâu.

## Success metric

- Giảm thời gian xác định nguyên nhân lỗi từ khoảng 30 phút xuống dưới 10–15 phút.
- Tăng tỷ lệ lần sửa đầu tiên đúng hướng.
- Tóm tắt được lỗi chính, file liên quan và bước kiểm tra tiếp theo.

## Non-AI alternative

Viết tài liệu lỗi thường gặp, checklist debug theo từng framework, hoặc dùng search engine truyền thống.

## AI hypothesis

AI có thể đọc log, tách warning khỏi error chính, chỉ ra nguyên nhân có khả năng cao, gợi ý thứ tự kiểm tra và giải thích bằng ngôn ngữ dễ hiểu. Người dùng vẫn phải tự kiểm tra code và không chạy lệnh nguy hiểm nếu chưa hiểu.

## Quick gut

- [ ] No AI / process fix
- [ ] Rule
- [x] Workflow
- [ ] Agent
- [ ] Chưa biết

## Draft workflow

### Current state

```text
CURRENT STATE — khoảng 30–60 phút

[Chạy chương trình]
→ [Terminal báo lỗi]
→ [Đọc log dài]
→ [Không rõ dòng lỗi chính]
→ [Tìm Google/Stack Overflow]
→ [Thử nhiều cách sửa]
→ [Chạy lại]
→ [Nếu vẫn lỗi thì lặp lại]

Bottleneck:
Không xác định nhanh được nguyên nhân chính trong log.
```

### Future state

```text
FUTURE STATE — khoảng 10–15 phút

[Chạy chương trình]
→ [Copy log lỗi]
→ [AI tóm tắt lỗi chính]
→ [AI chỉ ra file/dòng/thành phần có khả năng liên quan]
→ [AI gợi ý checklist kiểm tra]
→ [Sinh viên tự sửa và chạy lại]

Human boundary:
AI không tự sửa toàn bộ project nếu chưa được kiểm tra. Sinh viên phải đọc lại gợi ý, hiểu nguyên nhân và chỉ áp dụng thay đổi phù hợp.
```

---

# Problem Card #3

## Problem 1 câu

Sinh viên làm báo cáo/khóa luận thường mất nhiều thời gian chuyển code, sơ đồ và kết quả thực nghiệm thành đoạn mô tả đầy đủ, mạch lạc.

## Actor

Sinh viên làm đồ án, khóa luận hoặc báo cáo project kỹ thuật.

## Thời điểm / bối cảnh

Sau khi đã có mã nguồn, sơ đồ hệ thống, ảnh thực nghiệm, bảng kết quả hoặc log chạy thử, sinh viên cần viết lại thành nội dung báo cáo.

## Current workflow

1. Mở code, sơ đồ hoặc kết quả thực nghiệm.
2. Đọc lại từng phần để hiểu chức năng.
3. Tự viết mô tả bằng văn bản.
4. Kiểm tra xem có thiếu thành phần nào không.
5. Chỉnh lại thuật ngữ cho thống nhất.
6. Chèn bảng/hình vào báo cáo.
7. Sửa lại theo góp ý của giảng viên.

## Bottleneck

Bước chuyển nội dung kỹ thuật thành đoạn văn báo cáo mất nhiều thời gian và dễ thiếu ý. Một sơ đồ hoặc đoạn code có thể có nhiều chức năng nhỏ nhưng khi viết báo cáo dễ bỏ sót.

## Impact

Báo cáo có thể dài nhưng vẫn thiếu nội dung quan trọng, hoặc mô tả không khớp với hệ thống thực tế. Việc chỉnh sửa nhiều lần làm tốn thời gian, đặc biệt ở giai đoạn gần hạn nộp.

## Success metric

- Giảm thời gian viết bản nháp mô tả kỹ thuật.
- Giảm số lần phải sửa vì thiếu thành phần chính.
- Nội dung cuối cùng vẫn do sinh viên kiểm tra và chỉnh theo hệ thống thật.

## Non-AI alternative

Tạo template báo cáo cố định, checklist các ý cần mô tả cho từng loại phần: code, sơ đồ, bảng kết quả, giao diện.

## AI hypothesis

AI có thể hỗ trợ tóm tắt code/sơ đồ/kết quả thành dàn ý, nhắc các ý còn thiếu, đề xuất cách diễn đạt rõ hơn. Tuy nhiên AI không nên viết thay toàn bộ hoặc bịa kết quả không có thật.

## Quick gut

- [ ] No AI / process fix
- [ ] Rule
- [x] Workflow
- [ ] Agent
- [ ] Chưa biết

## Draft workflow

### Current state

```text
CURRENT STATE — khoảng 45–90 phút cho một phần

[Mở code/sơ đồ/kết quả]
→ [Đọc lại từng thành phần]
→ [Tự xác định ý cần viết]
→ [Viết đoạn mô tả]
→ [Kiểm tra thiếu ý]
→ [Chỉnh thuật ngữ]
→ [Đưa vào báo cáo]

Bottleneck:
Chuyển thông tin kỹ thuật rời rạc thành đoạn văn đầy đủ và thống nhất.
```

### Future state

```text
FUTURE STATE — khoảng 25–40 phút cho một phần

[Cung cấp code/sơ đồ/kết quả]
→ [AI tạo dàn ý mô tả]
→ [AI liệt kê thành phần cần nhắc đến]
→ [Sinh viên chọn ý đúng với hệ thống]
→ [Sinh viên viết/chỉnh thành đoạn báo cáo]
→ [Kiểm tra lại với hệ thống thật]

Human boundary:
AI chỉ hỗ trợ tạo dàn ý, kiểm tra thiếu ý và gợi ý cách diễn đạt. Sinh viên phải xác nhận nội dung kỹ thuật và không dùng số liệu AI tự bịa.
```

---

## 3. Card muốn pitch nhất

Card tôi muốn pitch nhất:

```text
Problem Card #1: Kiểm tra bài nộp lab theo worksheet/rubric.
```

## Vì sao chọn card này

Tôi chọn problem này vì đây là vấn đề khá cụ thể, actor rõ ràng và workflow hiện tại có thể mô tả được. Bài toán không quá rộng, phù hợp với phạm vi lab trong một buổi học. Ngoài ra, bottleneck có thể đo bằng thời gian kiểm tra bài nộp và số lỗi thiếu mục trước khi nộp.

Problem này cũng phù hợp với nguyên tắc “Problem first, not AI first”. Trước khi nghĩ đến AI, có thể thấy non-AI solution là checklist thủ công. Tuy nhiên, AI có thể hữu ích hơn ở bước đọc worksheet/rubric và chuyển nó thành checklist rõ ràng, sau đó hỗ trợ đối chiếu với bài làm.

## Câu hỏi muốn nhóm challenge

```text
1. Problem này có đủ đau không hay chỉ là vấn đề nhỏ trước khi nộp bài?
2. Checklist thủ công đã đủ giải quyết chưa, hay thật sự cần AI workflow?
3. Success metric “giảm thời gian kiểm tra xuống dưới 10 phút” có hợp lý không?
4. AI nên chỉ kiểm tra cấu trúc folder/file hay cả nội dung bên trong README?
5. Boundary cần đặt thế nào để AI không biến thành công cụ làm bài thay sinh viên?
```

---

## 4. Ghi chú về việc dùng AI

Tôi dùng AI để hỗ trợ hệ thống hóa ý tưởng, gợi ý cách trình bày Problem Card và phản biện xem problem có đủ actor, workflow, bottleneck, metric hay chưa. Các problem được chọn dựa trên trải nghiệm học tập, làm lab, làm project và làm báo cáo của bản thân. Tôi không dùng AI để tự động quyết định problem cuối cùng thay mình.
