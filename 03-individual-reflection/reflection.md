# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Nguyễn Khánh Linh
- Mã học viên: 2A202602409
- Nhóm: EQ200
- Candidate problem nhóm chọn: Đếm số lượng/mật độ khuẩn lạc trên đĩa Petri trong phòng thí nghiệm vi sinh.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tôi scan 9 vấn đề từ trải nghiệm học tập và sinh hoạt, sau đó chọn 3 Problem Cards để phân tích sâu. | Tạo được ba candidate có actor, workflow, bottleneck và metric để mang vào vòng thảo luận nhóm. |
| Pitch Problem Card | Tôi trình bày ba bài toán cá nhân, trong đó ưu tiên bài toán phân rã đầu việc lớn thành task, dependency, owner và deadline sau cuộc họp nhóm. | Nhóm có thêm một candidate workflow rõ ràng để so sánh với bài toán đếm khuẩn lạc và các đề xuất khác. |
| Challenge bài của bạn khác | Với bài đếm khuẩn lạc, tôi đặt vấn đề liệu có cần dùng model AI ngay hay nên thử rule-based image processing trước; tôi cũng đặt câu hỏi ai sẽ kiểm tra nếu hệ thống đếm sai. | Nhóm làm rõ được human boundary, fallback và lý do chỉ nâng lên model khi các trường hợp chồng lấn hoặc ảnh phức tạp vượt khả năng của rule-based. |
| Gom trùng / cluster | Tôi cùng nhóm đối chiếu các candidate theo actor, loại dữ liệu và workflow để tách nhóm xử lý ảnh phòng lab khỏi các bài quản lý dữ liệu hoặc hỗ trợ học tập. | Phạm vi thảo luận được thu hẹp, giúp nhóm so sánh các bài trên cùng tiêu chí thay vì chọn theo cảm giác. |
| Chọn candidate problem | Tôi tham gia phân tích pain, khả năng đo lường và tính phù hợp của bài toán đếm khuẩn lạc. | Nhóm chọn được candidate có bottleneck rõ: đếm thủ công tốn thời gian, gây mỏi mắt và khó xử lý khuẩn lạc sát hoặc chồng nhau. |
| Validation / research | Tôi góp ý cần dùng ảnh đĩa nuôi cấy thật, đo thời gian đếm thủ công và so kết quả giữa nhiều người để tạo ground truth. | Nhóm xác định được cách xây baseline và các số cần đo trong pilot thay vì chỉ đặt target theo giả định. |
| Workflow nhóm | Tôi cùng nhóm xây dựng workflow trước/sau, xác định điểm Computer Vision can thiệp, bước người dùng review và fallback khi ảnh hoặc kết quả không đủ tin cậy. | Workflow giữ được người dùng trong vòng kiểm soát và không tự động xuất kết quả chưa được xác nhận. |
| Problem Statement | Tôi tham gia làm rõ actor, bottleneck, impact, boundary và các metric gồm thời gian/đĩa, sai lệch so với ground truth và tỷ lệ cần chỉnh tay. | Problem Statement chuyển từ mô tả chung “AI đếm khuẩn lạc” thành một bài toán có thể kiểm thử và đánh giá. |
| Rule / Workflow / Agent | Tôi đề xuất thử rule-based image processing trước, chỉ dùng model khi khuẩn lạc chồng lấn hoặc ảnh phức tạp không xử lý tốt; tôi không ủng hộ Agent tự động toàn bộ. | Nhóm chọn hướng Workflow có human-in-the-loop và tránh mở rộng giải pháp quá sớm. |
| Decision | Tôi ủng hộ pilot phạm vi nhỏ, so rule-based với model trên dữ liệu thật và yêu cầu người dùng xác nhận kết quả cuối. | Quyết định Go có điều kiện đo lường và đường lui rõ nếu độ chính xác hoặc thời gian chỉnh tay không đạt yêu cầu. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Đóng góp rõ nhất của tôi là giúp biến ý tưởng “AI đếm khuẩn lạc” thành một workflow có metric, human boundary và fallback cụ thể. Tôi cũng giúp nhóm giữ phương án rule-based như baseline trước khi quyết định có cần dùng model AI hay không.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Dùng AI phản biện danh sách problem sau khi tôi tự scan từ trải nghiệm thật. | AI gợi ý cách bổ sung tần suất, thời gian và dấu hiệu quan sát được cho từng problem. | Một số gợi ý quá rộng, như AI tự làm đồ án hoặc quản lý toàn bộ cuộc sống, không phản ánh pain thật của tôi. | Tôi bỏ các ý không có trải nghiệm hoặc bằng chứng và chỉ giữ 9 problem có actor, tần suất và số đo cụ thể. |
| Problem Card | Dùng AI đóng vai skeptical product manager để challenge Problem Card về công việc sau họp nhóm. | AI chỉ ra metric “100% task có owner/deadline” chưa đo chất lượng và transcript có thể không chứa đủ bối cảnh. | Ban đầu AI tập trung nhiều vào trích xuất Action Items, chưa phản ánh đúng pain là phân rã đầu việc lớn thành kế hoạch thực thi. | Tôi giải thích lại ví dụ “làm chatbot” và sửa card theo hướng WBS gồm component, task, dependency, definition of done, owner và deadline. |
| Workflow | Không dùng AI để quyết định workflow nhóm; tôi cùng nhóm tự xác định các bước từ ảnh đầu vào đến review và xuất kết quả. | AI chỉ hỗ trợ tôi kiểm tra cách trình bày workflow trong tài liệu cá nhân. | AI không thể tự biết điều kiện thực tế của ảnh đĩa Petri hoặc mức sai số phòng lab chấp nhận. | Tôi giữ bước kỹ thuật viên review, xác nhận và fallback về đếm thủ công khi hệ thống không chắc chắn. |
| Research | Không dùng AI để thay việc kiểm chứng; nguồn và kết quả validation cần được kiểm tra bằng dữ liệu, ảnh hoặc người dùng thật. | AI giúp gợi ý các câu hỏi cần kiểm chứng như thời gian đếm, ground truth và mức độ chồng lấn. | Các con số do AI gợi ý không thể được coi là bằng chứng thực tế. | Tôi đề xuất lấy ảnh thật, bấm giờ và so kết quả giữa nhiều người trước khi chốt baseline hoặc target. |
| Problem Statement | Không dùng AI để viết thay; tôi tham gia cùng nhóm xác định actor, bottleneck, impact, metric và boundary. | AI hữu ích như công cụ soi xem metric có đo được và boundary có giữ người thật trong quy trình hay không. | AI dễ làm Problem Statement nghiêng sang mô tả giải pháp thay vì mô tả vấn đề. | Tôi giữ trọng tâm ở pain đếm thủ công và tách phần Computer Vision sang workflow tương lai. |
| Rule / Workflow / Agent | Dùng câu hỏi phản biện về việc có cần AI hay có thể dùng rule/process đơn giản hơn. | Cách so sánh giúp tôi nhận ra chưa cần Agent và nên có rule-based baseline. | AI có xu hướng đề xuất model Computer Vision sớm nếu chỉ nhìn vào bài toán nhận diện ảnh. | Tôi chọn thử rule-based trước, chỉ nâng lên model cho trường hợp chồng lấn hoặc ảnh phức tạp, và luôn giữ human review. |
| Decision | Không dùng AI để chốt thay nhóm; AI chỉ hỗ trợ liệt kê rủi ro và điều kiện đo. | AI giúp làm rõ các điều kiện Go/rollback như độ chính xác và số lần chỉnh tay. | AI không thể quyết định ngưỡng chấp nhận nếu chưa có baseline và ý kiến người dùng lab. | Tôi ủng hộ pilot nhỏ và chốt metric sau khi đo dữ liệu thật thay vì mặc định tin vào target ban đầu. |

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
Khi bắt đầu thảo luận, tôi nghĩ có thể dùng AI hoặc Computer Vision ngay để nhận diện và đếm khuẩn lạc thay cho người dùng. Sau khi cùng nhóm phân tích kỹ hơn, tôi nhận ra pain thật không chỉ là đếm chậm mà còn là mỏi mắt, khó phân biệt các khuẩn lạc sát hoặc chồng nhau và kết quả thiếu nhất quán giữa các lần đếm. Tôi đã tham gia làm rõ actor, bottleneck, workflow hiện tại và các metric có thể dùng để đánh giá giải pháp. Phần có dấu tay rõ nhất của tôi là workflow trước/sau, human boundary và fallback khi hệ thống không đủ chắc chắn. Tôi cũng thay đổi quan điểm rằng không nhất thiết phải bắt đầu bằng một model AI phức tạp. Với ảnh sạch và khuẩn lạc tách rời, rule-based image processing có thể là baseline rẻ và dễ kiểm soát hơn. Chỉ khi các trường hợp chồng lấn hoặc ảnh phức tạp vượt khả năng của rule-based thì nhóm mới có đủ lý do để thử model Computer Vision. Vì vậy, tôi nhìn giải pháp là công cụ hỗ trợ đếm chứ không phải hệ thống thay thế hoàn toàn kỹ thuật viên. Người dùng vẫn phải review, chỉnh sửa và xác nhận kết quả trước khi xuất dữ liệu. Nếu làm lại, tôi sẽ validate sớm hơn bằng ảnh thật, bấm giờ quá trình đếm thủ công và so kết quả giữa nhiều người để có ground truth rõ ràng. Tôi cũng sẽ chốt target sau khi có baseline và challenge mạnh hơn mỗi khi nhóm muốn đưa AI vào trước khi chứng minh rule hoặc process đơn giản là chưa đủ.
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
