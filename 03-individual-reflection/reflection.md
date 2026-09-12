# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Lê Quang Ngọc
- Mã học viên:2A202602664
- Nhóm: sunset
- Candidate problem nhóm chọn: Mỗi tuần giáo viên mất khoảng 60-180 phút tổng hợp điểm, các ô điểm để trống và ghi chú trong Excel hoặc Google Sheets để báo cáo tình hình học tập của khoảng 60 học sinh.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tôi scan 6 vấn đề trong công việc intern SE và chọn 3 vấn đề có actor, bottleneck và số đo rõ; trong đó tôi pitch mạnh nhất bài tổng hợp báo cáo tiến độ. | Cung cấp một candidate có workflow hằng ngày, baseline khoảng 20 phút/báo cáo và 8-10 câu hỏi bổ sung mỗi tuần. |
| Pitch Problem Card | Tôi trình bày Card tổng hợp báo cáo tiến độ, giải thích current/future workflow và metric thời gian. | Nhóm có thêm một phương án cụ thể để so sánh với các candidate khác. |
| Challenge bài của bạn khác | Tôi đặt câu hỏi về việc dữ liệu đầu vào bị phân mảnh và nguy cơ AI tự suy đoán thông tin khi viết nhận xét. | Nhóm nhận diện sớm rủi ro về chất lượng dữ liệu và hallucination. |
| Gom trùng / cluster | Tôi cùng nhóm phân biệt candidate tổng hợp báo cáo của mình với cluster xử lý dữ liệu phi cấu trúc và hỗ trợ ra quyết định. | Giúp nhóm thấy bài của giáo viên có pain và workflow riêng, không gộp nhầm với các bài khác. |
| Chọn candidate problem | Tôi tham gia chấm và so sánh các candidate theo actor, workflow, evidence, impact và độ phù hợp với lab. | Nhóm chốt bài tổng hợp tình hình học tập vì có baseline 60-180 phút/tuần và phạm vi làm được. |
| Validation / research | Tôi góp ý diễn giải insight từ phỏng vấn giáo viên: pain chính là đối chiếu điểm, ô trống và ghi chú, không chỉ là viết báo cáo. | Problem được sửa để tập trung vào bước đối chiếu và thêm boundary giáo viên phải duyệt nhận xét. |
| Workflow nhóm | Tôi hỗ trợ chuyển workflow thành các bước rõ ràng, đặc biệt là bottleneck ở đối chiếu dữ liệu và bước kiểm tra cuối. | Bản future workflow có Rule tiền xử lý, AI gợi ý và human-in-the-loop. |
| Problem Statement | Với vai trò Writer, tôi góp phần diễn đạt lại v0/v1, metric, boundary, fallback và rủi ro theo cùng một mạch. | Artifact cuối có Problem Statement v1 với mục tiêu dưới 60 phút/tuần và lỗi dữ liệu bằng 0. |
| Rule / Workflow / Agent | Tôi tham gia phân biệt Rule, Workflow và Agent; ủng hộ dùng Rule cho dữ liệu và LLM cho bản nháp nhận xét. | Nhóm chọn Workflow, không chọn Agent tự gửi tin nhắn vì rủi ro cao. |
| Decision | Tôi đồng thuận với quyết định Go và đề xuất pilot trên dữ liệu giả lập của một lớp, có đo thời gian, hallucination và thời gian duyệt. | Quyết định cuối có phạm vi thử nghiệm và điều kiện rollback nếu AI gây thêm công việc. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Tôi để lại dấu tay rõ nhất ở phần diễn đạt Problem Statement v1 và mô tả boundary/fallback. Tôi cũng giúp nối candidate ban đầu của mình về báo cáo tiến độ với cách nhóm nhìn bottleneck đối chiếu dữ liệu và kiểm duyệt nhận xét.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Không dùng AI để tạo danh sách ban đầu; tôi tự xuất phát từ công việc intern SE. | Giúp tôi giữ problem gắn với trải nghiệm và số đo thật. | Nếu chỉ hỏi AI, gợi ý dễ rộng và solution-first. | Tôi tự giữ 6 problem có bằng chứng thời gian/tần suất và bỏ ý chưa quan sát được. |
| Problem Card | Dùng AI để gợi ý câu hỏi phản biện cho card và kiểm tra bottleneck/metric. | AI giúp chỉ ra các điểm cần xác minh như phần báo cáo thiếu thông tin và nguy cơ AI đoán blocker. | AI không biết đầy đủ quy trình thực tế của tôi nên có thể đề xuất metric không có dữ liệu. | Tôi giữ lại các metric đã ghi nhận và tự quyết định card tổng hợp báo cáo là card muốn pitch. |
| Workflow | Dùng AI hỗ trợ diễn đạt workflow trước/sau và kiểm tra fallback. | AI giúp nhìn rõ bước nào nên để Rule, LLM và con người xử lý. | Sơ đồ có thể trông hợp lý dù chưa chứng minh được thời gian thực tế. | Tôi đối chiếu lại từng bước với actor, input, output, thời gian và human boundary. |
| Research | Dùng AI/search để gợi ý các hướng như Google Apps Script và LLM raw. | Giúp nhóm nhanh chóng so sánh công cụ và nhận ra khoảng trống của từng cách. | Link hoặc mô tả tổng quát chưa tự chứng minh hiệu quả trong bối cảnh giáo viên. | Tôi không coi research là bằng chứng thay cho interview và giữ giáo viên là người duyệt cuối. |
| Problem Statement | Dùng AI để phản biện field còn mơ hồ, nhất là boundary và fallback. | AI giúp phát hiện cần nói rõ AI không được tự bịa điểm hoặc tự gửi tin nhắn. | AI có thể viết câu rất trơn tru nhưng làm mờ actor và metric. | Tôi chỉnh lại thành giáo viên dạy Tin, khoảng 60 học sinh, dưới 60 phút/tuần và lỗi dữ liệu bằng 0. |
| Rule / Workflow / Agent | Dùng AI để hỏi ngược về độ phù hợp giữa Rule, Workflow và Agent. | AI giúp nhóm so sánh được ưu/nhược điểm trên cùng một bài toán. | Gợi ý Agent dễ làm bài toán có vẻ hiện đại nhưng vượt boundary và tăng rủi ro. | Tôi ủng hộ Workflow vì Rule xử lý số liệu, LLM viết nháp, giáo viên kiểm duyệt. |
| Decision | Dùng AI để rà lại điều kiện pilot và rollback. | Giúp nhóm bổ sung các số cần đo: thời gian chạy, hallucination và thời gian duyệt. | AI không thể thay nhóm quyết định ngưỡng dừng hoặc chấp nhận rủi ro. | Nhóm tự chốt Go, pilot 1 lớp 30 học sinh và dừng nếu hallucination vượt 20%. |

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
Khi nghe top problems của các bạn, tôi nhận ra một problem tốt không chỉ là việc gây khó chịu mà phải có actor, workflow và số đo cụ thể. Candidate ban đầu của tôi về báo cáo tiến độ intern có workflow rõ, nhưng impact nhỏ hơn bài giáo viên theo dõi khoảng 60 học sinh nên tôi đồng ý để nhóm chọn bài của Thái. Tôi thấy nhóm có lúc dễ bị cuốn vào ý tưởng AI viết nhận xét, nhưng khi challenge về dữ liệu phân mảnh và nguy cơ hallucination, chúng tôi đã quay lại xác định bottleneck là đối chiếu dữ liệu. Điều tôi học được là AI chỉ nên can thiệp sau khi dữ liệu đã được chuẩn hóa và không nên tự gửi kết quả cho phụ huynh. Tôi đóng góp rõ nhất ở việc viết và làm chặt Problem Statement v1, nhất là metric dưới 60 phút/tuần, boundary giáo viên duyệt 100% và fallback dùng dữ liệu gốc. Khó nhất khi viết Problem Statement là giữ cho metric tham vọng nhưng vẫn đo được, vì mục tiêu giảm thời gian không được đánh đổi bằng nhận xét sai. So sánh Rule, Workflow và Agent giúp tôi hiểu rằng bài toán phức tạp không đồng nghĩa với việc cần Agent. Workflow phù hợp hơn vì các bước đi theo luồng cố định, còn trách nhiệm quyết định vẫn thuộc về giáo viên. Nếu làm lại, tôi sẽ challenge sớm hơn về độ tin cậy của quote phỏng vấn và cách đo chất lượng nhận xét thay vì chỉ đo thời gian. Tôi cũng sẽ đề nghị nhóm thử một mẫu dữ liệu nhỏ trước để kiểm tra tỷ lệ nhận xét phải sửa trước khi kết luận Go.
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

