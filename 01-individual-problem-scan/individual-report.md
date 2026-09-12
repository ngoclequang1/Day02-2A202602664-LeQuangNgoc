# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Lê Quang Ngọc
- Mã học viên: 2A202602664
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...):intern Software Engineer
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
    + Họp với mentor để nhận task và nghe hướng dẫn
    + Nghiên cứu yêu cầu và hoàn thành task được giao
    + Viết báo cáo tiến độ hàng ngày cho mentor
    + Review code với mentor, nghe feedback và sửa lỗi


---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Tốn thời gian / Pain từ người khác | Sau buổi họp với mentor, intern chưa luôn xác định rõ yêu cầu, phạm vi và tiêu chí hoàn thành của task. | Intern, mentor | Theo dõi 3-5 task: ghi số lần phải hỏi lại ( 2-3 lần/task) và thời gian chờ phản hồi ( ~5 phút/lần). |
| 2 | Tốn thời gian | Intern phải đọc nhiều tài liệu, code cũ và trao đổi trước đây để hiểu đầy đủ context của task. | Intern | Bấm giờ ít nhất 3 task: thời gian tìm hiểu là 20-30 phút/task; ghi số nguồn phải xem là 3+ nguồn/task. |
| 3 | Tốn thời gian / AI có thể tốt hơn | Việc chuyển yêu cầu của mentor thành các bước triển khai cụ thể còn mất thời gian và dễ bỏ sót bước. | Intern, mentor | Trong 3-5 task, ghi số task phải bổ sung hoặc đổi kế hoạch (~3 task) và thời gian lập kế hoạch (20+ phút/task). |
| 4 | Lặp lại / Tốn thời gian | Intern phải viết báo cáo tiến độ hằng ngày theo cùng một format bằng cách nhớ lại và tổng hợp công việc thủ công. | Intern, mentor | Xảy ra 7 ngày/tuần; bấm giờ thời gian viết report là ~15 phút/ngày. |
| 5 | Lặp lại / AI có thể làm tốt hơn | Khi viết báo cáo tiến độ, intern phải kiểm tra lại từng task để tổng hợp việc đã hoàn thành, việc đang làm và khó khăn cần mentor hỗ trợ. Báo cáo còn thiếu thông tin khiến mentor phải hỏi thêm. | Intern, mentor | Theo dõi trong 7 ngày: intern mất khoảng 20 phút/báo cáo để tổng hợp thông tin; mentor phải hỏi bổ sung 8–10 lần/tuần. |
| 6 | Tốn thời gian / Pain từ người khác | Intern mất thời gian phân biệt feedback nào bắt buộc sửa, feedback nào là đề xuất cải thiện hoặc cần hỏi lại mentor. | Intern, mentor/reviewer | Trong 1 lần review, có ~4 comment phải hỏi lại; thời gian phân loại và xác nhận là ~15 phút/PR. |



> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi:
- Ý dùng được:
- Ý bỏ vì không phải pain thật:

**Self-check Phase 1:**
- [X] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [X] Dùng ít nhất 3/4 lăng kính
- [X] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Khi viết báo cáo tiến độ, intern phải kiểm tra lại từng task để tổng hợp việc đã hoàn thành, việc đang làm và khó khăn cần mentor hỗ trợ. Báo cáo còn thiếu thông tin khiến mentor phải hỏi thêm. | Xảy ra hằng ngày, có số đo thời gian và số lần mentor hỏi bổ sung. Workflow ngắn, dễ thử nghiệm bằng template hoặc AI hỗ trợ tổng hợp. | Cần xác nhận báo cáo thiếu thông tin ở phần nào và AI có thể giảm bao nhiêu thời gian mà không làm tăng lỗi. |
| 2 | Sau buổi họp với mentor, intern chưa luôn xác định rõ yêu cầu, phạm vi và tiêu chí hoàn thành của task. | Ảnh hưởng trực tiếp đến việc triển khai; có thể vẽ rõ từ nhận task đến bắt đầu code. Số lần hỏi lại và thời gian chờ phản hồi có thể đo được. | Chưa chắc nguyên nhân chính là yêu cầu chưa rõ, ghi chú cuộc họp chưa đầy đủ hay intern chưa biết cách xác nhận lại. |
| 3 | Intern mất thời gian phân biệt feedback nào bắt buộc sửa, feedback nào là đề xuất cải thiện hoặc cần hỏi lại mentor. | Xảy ra trong code review, có bottleneck rõ ở bước phân loại comment và có số đo thời gian/​​số comment cần hỏi lại. | Cần xác định việc phân loại có thật sự cần AI hay chỉ cần quy ước nhãn và checklist trong code review. |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Tổng hợp báo cáo tiến độ hằng ngày

```text
Problem 1 câu: Mỗi ngày intern mất khoảng 20 phút tổng hợp báo cáo tiến độ từ các task đang làm, và mentor vẫn phải hỏi bổ sung khoảng 8-10 lần/tuần.

Actor: Intern Software Engineer; người nhận báo cáo là mentor.

Thời điểm / bối cảnh: Cuối mỗi ngày làm việc, trước khi gửi báo cáo tiến độ cho mentor.

Current workflow 3-7 bước:
1. Mở danh sách task và các ghi chú trong ngày.
2. Nhớ lại hoặc rà lại việc đã hoàn thành, đang làm và đang bị block.
3. Viết nội dung theo format báo cáo.
4. Kiểm tra lại thông tin và gửi cho mentor.
5. Trả lời các câu hỏi bổ sung từ mentor nếu báo cáo thiếu context.

Bottleneck: Bước 2-3 — rà lại nhiều nguồn rồi chuyển thành báo cáo đầy đủ; hiện mất khoảng 20 phút/báo cáo.

Impact: Intern mất khoảng 20 phút mỗi ngày, tương đương khoảng 100 phút/tuần nếu làm 5 ngày. Mentor phải hỏi bổ sung 8-10 lần/tuần, làm chậm việc nắm tiến độ.

Success metric: Giảm thời gian viết báo cáo từ khoảng 20 phút xuống dưới 10 phút/báo cáo; giảm câu hỏi bổ sung của mentor từ 8-10 xuống tối đa 2-3 câu/tuần; không tăng thông tin sai hoặc thiếu.

Non-AI alternative: Dùng template cố định gồm Done/Doing/Blocked/Need help, kèm checklist bắt buộc và cập nhật task ngay sau mỗi phiên làm việc.

AI hypothesis: AI đọc các ghi chú hoặc dữ liệu task do intern cung cấp, đề xuất bản nháp theo template và cảnh báo trường còn thiếu. Intern kiểm tra và gửi bản cuối.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[X] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — khoảng 20 phút

[1 Mở task/ghi chú: 3'] → [2 Rà lại tiến độ: 8'] → [3 Viết report: 7'] → [4 Kiểm tra + gửi: 2']  <-- bottleneck

FUTURE STATE — khoảng 9 phút

[1 Nhập/cập nhật task notes: 2'] → [2 AI tạo draft + cảnh báo thiếu: 1'] → [3 Intern review + gửi: 6']  <-- human boundary

Fallback: nếu AI tóm tắt sai hoặc thiếu context, intern dùng template thủ công và đối chiếu trực tiếp với task tracker trước khi gửi.
```

File đính kèm (nếu vẽ riêng): 

---

#### Problem Card #2 — Làm rõ yêu cầu sau buổi họp với mentor

```text
Problem 1 câu: Sau buổi họp nhận task, intern phải hỏi lại khoảng 2-3 lần/task vì chưa rõ yêu cầu, phạm vi hoặc tiêu chí hoàn thành.

Actor: Intern Software Engineer; mentor là người giao task và xác nhận yêu cầu.

Thời điểm / bối cảnh: Ngay sau buổi họp nhận task và trước khi bắt đầu triển khai.

Current workflow 3-7 bước:
1. Nghe mentor mô tả task và ghi chú.
2. Đọc lại yêu cầu, code liên quan hoặc tài liệu được chỉ dẫn.
3. Tách task thành các bước thực hiện và xác định tiêu chí hoàn thành.
4. Gửi câu hỏi hoặc xác nhận lại các điểm chưa rõ với mentor.
5. Bắt đầu triển khai sau khi nhận phản hồi.

Bottleneck: Bước 3-4 — chuyển hướng dẫn miệng thành phạm vi và acceptance criteria rõ ràng; thường phải hỏi lại 2-3 lần/task.

Impact: Intern mất thời gian chờ và điều chỉnh kế hoạch; mentor bị gián đoạn để giải thích lại. Nếu hiểu sai, task có thể phải sửa hoặc đổi hướng sau khi đã bắt đầu code.

Success metric: Giảm số lần hỏi lại từ 2-3 lần xuống tối đa 1 lần/task; có checklist yêu cầu và acceptance criteria trước khi bắt đầu code; giảm số task phải đổi kế hoạch do hiểu sai.

Non-AI alternative: Dùng mẫu task brief gồm mục tiêu, phạm vi, input/output, acceptance criteria và câu hỏi xác nhận; kết thúc họp bằng việc intern đọc lại task theo cách hiểu của mình.

AI hypothesis: AI chuyển ghi chú cuộc họp và tài liệu liên quan thành task brief có cấu trúc, chỉ ra điểm mơ hồ và sinh danh sách câu hỏi để intern xác nhận với mentor.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[X] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — khoảng 35 phút, chưa tính thời gian chờ mentor

[1 Họp + ghi chú: 15'] → [2 Đọc context: 10'] → [3 Tách bước/tiêu chí: 5'] → [4 Hỏi lại mentor: 5']  <-- bottleneck

FUTURE STATE — khoảng 25 phút, chưa tính thời gian chờ mentor

[1 Nhập ghi chú + context: 5'] → [2 AI tạo task brief/câu hỏi: 5'] → [3 Intern + mentor xác nhận: 15']  <-- human boundary

Fallback: nếu AI diễn giải sai, intern gửi lại ghi chú gốc và dùng task brief thủ công; mentor vẫn là người xác nhận cuối cùng.
```

File đính kèm: 

---

#### Problem Card #3 — Phân loại feedback trong code review

```text
Problem 1 câu: Trong mỗi lần code review, intern mất khoảng 15 phút để phân biệt comment bắt buộc sửa, đề xuất cải thiện và vấn đề cần hỏi lại mentor; khoảng 4 comment có thể cần xác nhận.

Actor: Intern Software Engineer; mentor hoặc reviewer là người viết feedback.

Thời điểm / bối cảnh: Sau khi mentor review pull request và trước khi intern bắt đầu sửa code.

Current workflow 3-7 bước:
1. Đọc toàn bộ comment trong pull request.
2. Đối chiếu từng comment với yêu cầu task và code hiện tại.
3. Phân loại comment: bắt buộc sửa, đề xuất hoặc cần hỏi lại.
4. Hỏi mentor về comment chưa rõ và lập danh sách việc cần sửa.
5. Sửa code, chạy kiểm tra và phản hồi từng comment.

Bottleneck: Bước 2-3 — hiểu ngữ cảnh và mức độ ưu tiên của feedback; hiện mất khoảng 15 phút/PR.

Impact: Intern có thể sửa sai ưu tiên hoặc bỏ sót comment, dẫn đến thêm một vòng review và làm mentor phải giải thích lại.

Success metric: Giảm thời gian phân loại từ khoảng 15 phút xuống dưới 8 phút/PR; giảm comment phải hỏi lại từ khoảng 4 xuống tối đa 1-2 comment/PR; không tăng số comment bị bỏ sót.

Non-AI alternative: Thống nhất nhãn trong review như Must fix/Question/Suggestion và dùng checklist xử lý comment trước khi gửi lại PR.

AI hypothesis: AI nhóm và giải thích comment dựa trên yêu cầu task, gợi ý nhãn ưu tiên và tạo checklist sửa. Intern quyết định cuối cùng và hỏi mentor khi confidence thấp.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[X] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — khoảng 15 phút

[1 Đọc comment: 4'] → [2 Đối chiếu context: 6'] → [3 Phân loại + hỏi lại: 5']  <-- bottleneck

FUTURE STATE — khoảng 8 phút

[1 Cung cấp task + diff + comment: 2'] → [2 AI gợi ý nhóm/ưu tiên: 1'] → [3 Intern review + hỏi mentor: 5']  <-- human boundary

Fallback: nếu AI gán nhãn sai, intern bỏ qua gợi ý và dùng nhãn do reviewer quy định; comment chưa rõ phải được mentor xác nhận trước khi sửa.
```

File đính kèm: 

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #1 — Tổng hợp báo cáo tiến độ hằng ngày
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Đây là workflow xảy ra mỗi ngày, có baseline khoảng 20 phút/báo cáo và mentor phải hỏi bổ sung 8-10 lần/tuần. Tôi muốn kiểm tra liệu template hoặc AI có thể giảm thời gian tổng hợp mà vẫn giữ báo cáo đầy đủ, chính xác hay không.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Phần thiếu thông tin trong báo cáo đến từ format chưa đủ rõ hay từ việc intern chưa cập nhật task thường xuyên?
2. Nếu dùng AI tạo draft, cách nào đảm bảo AI không tự suy đoán tiến độ hoặc blocker?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra:
- Tôi sửa gì:

### Self-check nộp phần 01
- [X] Có 5+ problems + top 3 Cards đủ field
- [X] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [X] Đã chọn 1 card pitch + câu hỏi challenge
