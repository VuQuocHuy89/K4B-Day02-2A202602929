# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Vũ Quốc Huy
- Mã học viên: 2A202602929
- Nhóm: B1_Ban2
- Candidate problem nhóm chọn: Trả lời câu hỏi tài chính phức tạp bằng nhiều bảng dữ liệu và evidence

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tôi lập 9 problem từ bối cảnh học tập và làm việc nhóm, dùng các lăng kính lặp lại, tốn thời gian, AI có thể hỗ trợ và pain của người khác. | Nhóm có thêm các problem cụ thể, có actor và số liệu quan sát để so sánh. |
| Pitch Problem Card | Tôi trình bày 3 card về tổng hợp ghi chú ôn thi, nhắc task/deadline và viết báo cáo tiến độ; đồng thời mô tả workflow trước/sau. | Nhóm nhìn rõ bottleneck, metric, fallback và mức độ phù hợp của từng card. |
| Challenge bài của bạn khác | Tôi lắng nghe và góp ý một số câu hỏi về actor, evidence và việc có thật sự cần AI hay chỉ cần Rule/template. | Góp phần giúp nhóm xem xét rủi ro solution-first. |
| Gom trùng / cluster | Tôi theo dõi cách nhóm gom candidate và góp ý khi có problem gần với trải nghiệm học tập của mình. | Có thêm góc nhìn để nhóm phân biệt các cụm tổng hợp, automation và truy xuất dữ liệu. |
| Chọn candidate problem | Tôi tham gia thảo luận shortlist và đồng ý với việc chọn candidate #12 của Thành. | Tôi hiểu được lý do bài này có workflow và boundary phù hợp để đào sâu. |
| Validation / research | Tôi xem lại một số nguồn research về SEC EDGAR XBRL APIs, Microsoft Power BI Copilot và FinQA. | Góp ý rằng các claim chưa có dữ liệu nội bộ cần được ghi là giả định, không phải kết quả đã chứng minh. |
| Workflow nhóm | Tôi góp ý ở phần evidence chain và human boundary khi nhóm rà soát workflow. | Bổ sung được điểm kiểm tra nguồn và fallback, còn việc hoàn thiện workflow do cả nhóm phối hợp. |
| Problem Statement | Tôi tập trung góp ý actor, bottleneck, metric, evidence completeness và boundary không tự quyết định tài chính. | Đây là phần tôi có đóng góp rõ nhất trong việc chuyển mô tả chung thành bài toán có thể kiểm thử. |
| Rule / Workflow / Agent | Tôi tham gia nghe và góp ý cho bảng so sánh ba mức, đặc biệt về rủi ro audit của Agent. | Nhóm có thêm cơ sở để chọn Workflow có Rule/calculator và human verification. |
| Decision | Tôi đồng ý với quyết định Not Yet vì nhóm chưa có baseline nội bộ và validation từ người dùng thật. | Quyết định cuối phản ánh đúng giới hạn bằng chứng hiện có. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Đóng góp rõ nhất của tôi là phần Problem Statement cho candidate #12. Tôi tập trung góp
ý để làm rõ actor, bottleneck, evidence chain, success metric và boundary; đồng thời
nhắc nhóm không coi baseline hoặc mức giảm thời gian là số liệu đã được chứng minh khi
chưa có validation nội bộ. Đây là phần tôi tham gia sâu hơn, còn các phần khác chủ yếu
là theo dõi, góp ý và phối hợp cùng các thành viên phụ trách.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý cách mở rộng problem theo nhiều lăng kính và hỏi ngược về actor, pain, metric. | Giúp phát hiện các stakeholder bị ảnh hưởng ngoài bản thân tôi. | AI dễ đưa ra problem chung chung hoặc tự gán số liệu nghe hợp lý. | Tôi chỉ giữ các problem gắn với bối cảnh thật và ghi số liệu quan sát, không dùng số do AI tự bịa. |
| Problem Card | Giúp sắp xếp actor, workflow, bottleneck, metric và fallback cho 3 card. | Làm rõ cấu trúc để tôi pitch ngắn gọn hơn. | Một số gợi ý ban đầu quá rộng và mặc định AI là giải pháp. | Tôi thu hẹp input, thêm nguồn tham chiếu, human review và phương án Rule/no-AI. |
| Workflow | Hỗ trợ chuyển mô tả thành current workflow, future workflow và Mermaid. | Giúp nhìn ra handoff, bước nghẽn và ranh giới giữa AI với con người. | AI có xu hướng tự động hóa quá nhiều bước và coi answer là đúng mặc định. | Tôi giữ calculator/evidence check và analyst approval, thêm fallback về tra cứu thủ công. |
| Research | Hỗ trợ tìm và tổ chức các pattern/tool liên quan đến financial QA và retrieval. | Giúp nhanh chóng lập danh sách nguồn để kiểm tra. | AI có thể trộn nguồn thứ cấp hoặc đưa claim không có link chính thức. | Tôi ưu tiên SEC, Microsoft và ACL Anthology; bỏ các claim chưa kiểm chứng và ghi rõ giới hạn. |
| Problem Statement | Gợi ý cách viết actor, bottleneck, impact và success metric. | Giúp tách metric retrieval, evidence, calculation và answer thay vì chỉ viết “nhanh hơn”. | AI dễ điền baseline, accuracy hoặc mức giảm thời gian dù chưa có dữ liệu. | Tôi chuyển các con số chưa đo thành mục tiêu pilot và chọn Not Yet. |
| Rule / Workflow / Agent | Hỗ trợ lập bảng so sánh ba phương án trên cùng một bài toán. | Làm rõ Rule nên giữ schema/công thức, Workflow điều phối luồng và Agent chỉ là phương án tương lai. | AI thường ưu tiên Agent vì nghe mạnh hơn nhưng chưa xét audit và rủi ro. | Tôi chọn Workflow có Rule/calculator và human verification vì dễ kiểm soát hơn. |
| Decision | Hỗ trợ kiểm tra điều kiện Go/Not Yet/No-Go và đề xuất metric pilot. | Giúp nhóm nêu được dữ liệu cần thu thập trước khi triển khai. | Nếu chỉ nghe AI, nhóm có thể kết luận Go khi chưa có baseline hoặc user validation. | Tôi giữ Not Yet và ghi rõ cần interview, golden set, baseline và tiêu chí rollback. |

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
Qua việc nghe top 3 của các bạn, tôi nhận ra một vấn đề tốt không nhất thiết chỉ ảnh hưởng đến người trực tiếp làm việc mà còn có thể ảnh hưởng đến leader, người kiểm tra và người nhận kết quả. Tôi thay đổi cách nhìn từ “có thể làm AI gì” sang “điểm nghẽn nào có thể đo và kiểm chứng được”. Khi nhóm so sánh các candidate, tôi thấy bài toán tổng hợp báo cáo và phân tích log đều gần với trải nghiệm sinh viên, nhưng candidate tài chính có chuỗi truy xuất và evidence rõ hơn để thiết kế workflow. Điều khó nhất khi viết Problem Statement là không biến một mục tiêu mong muốn thành baseline đã được chứng minh. AI giúp tôi tổ chức các ý tưởng và rà soát các trường còn thiếu, nhưng cũng dễ điền các con số nghe hợp lý dù chưa có dữ liệu thật. Vì vậy tôi góp ý tách thời gian, evidence completeness và calculation correctness thành các metric riêng, đồng thời ghi rõ baseline chưa đo. Tôi cũng nhận ra Agent không tự động là lựa chọn tốt nhất vì bài toán tài chính cần audit, provenance và trách nhiệm của người duyệt. Đóng góp sâu nhất của tôi trong artifact cuối là phần Problem Statement, đặc biệt là actor, bottleneck, metric và boundary. Các phần workflow, research và quyết định là kết quả phối hợp của cả nhóm, trong đó tôi chủ yếu theo dõi và góp ý. Nếu làm lại, tôi sẽ đề xuất nhóm thu thập validation và đo baseline sớm hơn trước khi viết các mục impact và success metric.
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
