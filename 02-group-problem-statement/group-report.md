# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   | Nguyễn Khánh Linh | 2A202602409 | Workflow Modeling & Technical Writer                          |
| 2   | [Thành viên 2]   | [Mã HV]     | User Research & Validation                                    |
| 3   | [Thành viên 3]   | [Mã HV]     | Facilitator & Problem Framing                                 |
| 4   | [Thành viên 4]   | [Mã HV]     | Solution Research & Feasibility Evaluation                    |

**Candidate problem nhóm chọn (1 câu):**
Kỹ thuật viên và Nghiên cứu viên vi sinh vật mất 10–15 phút/đĩa để chấm đếm khuẩn lạc thủ công bằng mắt và nhập liệu tay vào Excel, dẫn đến mỏi mắt, dễ đếm sót/trùng khi mật độ cao (>100 CFU) và tiềm ẩn nguy cơ sai lệch số liệu thí nghiệm.

---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Khánh Linh | Tổng hợp meeting notes & trích xuất task, owner, deadline sau họp nhóm đồ án | Leader, thành viên nhóm | Lọc bản ghi chép/transcript để bóc tách việc cụ thể | Workflow rõ, phổ biến nhưng domain làm việc nhóm khá quen thuộc |
| 2 | Khánh Linh | Tìm kiếm tài liệu, quy định nộp bài môn học rải rác đa kênh (Discord, LMS, Mail) | Sinh viên | Mù vị trí lưu trữ, thông tin trôi trên chat | Pain point thật, nhưng liên quan nhiều đến phân quyền dữ liệu trường |
| 3 | Khánh Linh | Mất thời gian chọn món ăn mỗi ngày (cân đối ngân sách, khẩu vị, dinh dưỡng) | Sinh viên ở trọ | Đắn đo giữa hàng chục quán trên app giao đồ ăn | Lặp lại hàng ngày nhưng mang tính tiện ích cá nhân hơn là bài toán chuyên sâu |
| 4 | Thành viên 2 | Đếm khuẩn lạc (Colony Counting) thủ công trên đĩa Petri trong phòng thí nghiệm | Kỹ thuật viên (KTV), nghiên cứu viên (NCV) vi sinh | Chấm đếm từng chấm bằng mắt thường khi đĩa >100 CFU và nhập tay vào Excel | **Rất đau, tốn thời gian (10-15'/đĩa), mỏi mắt, dễ sai số, tác động lớn đến nghiên cứu** |
| 5 | Thành viên 2 | Ghi chép nhật ký vận hành và nhiệt độ tủ ấm vi sinh hàng ngày | KTV phòng lab | Đi từng tủ đọc đồng hồ và ghi sổ giấy | Dễ giải quyết bằng cảm biến IoT / Rule đơn giản, chưa cần AI |
| 6 | Thành viên 2 | Phân loại chủng vi khuẩn qua ảnh nhuộm Gram dưới kính hiển vi | NCV vi sinh | So sánh hình thái tế bào vi khuẩn (hình que, hình cầu) | Thú vị nhưng độ mơ hồ cao, cần chuyên gia giải phẫu bệnh/vi sinh thẩm định |
| 7 | Thành viên 3 | Theo dõi lịch khử trùng và hạn sử dụng hóa chất thí nghiệm | Quản lý phòng lab | Kiểm tra từng nhãn chai hóa chất trên kệ | Bài toán quản lý kho (Inventory), dùng barcode/database là đủ |
| 8 | Thành viên 3 | Tổng hợp số liệu và vẽ biểu đồ tăng trưởng vi sinh vật từ dữ liệu đo OD | NCV, sinh viên lab | Copy số đo mật độ quang học OD600 vào Excel rồi fit đường cong | Có thể dùng script Python/Excel template, không cần AI |
| 9 | Thành viên 3 | Tóm tắt các bài báo khoa học (paper) chuyên ngành công nghệ sinh học | Sinh viên nghiên cứu | Đọc 20–30 trang tiếng Anh chuyên ngành | Giống các bài toán LLM tóm tắt thông thường, chưa thấy workflow riêng biệt |
| 10 | Thành viên 4 | Kiểm tra lỗi cú pháp và format báo cáo thực hành thí nghiệm theo mẫu chuẩn | Trợ giảng (TA), KTV | Soát từng lỗi căn lề, mục lục, bảng biểu bài nộp sinh viên | Rule-based hoặc linter thông thường có thể xử lý phần lớn |
| 11 | Thành viên 4 | Dự đoán nguy cơ nhiễm tạp (contamination) trong mẻ nuôi cấy tế bào | NCV nuôi cấy | Quan sát vệt đục bất thường trên môi trường lỏng | Rất khó thu thập tập dữ liệu lỗi để huấn luyện, scope quá lớn |
| 12 | Thành viên 4 | Số hóa và trích xuất dữ liệu từ sổ tay ghi chép thí nghiệm viết tay | KTV phòng lab | Đọc chữ viết tay bác sĩ/NCV để gõ vào máy tính | OCR chữ viết tay tiếng Việt trong lab rất nhiễu, rủi ro sai lệch cao |

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| **A: Tự động hóa xử lý ảnh & đo lường phòng lab** | #4 (Đếm khuẩn lạc Petri), #6 (Phân loại ảnh nhuộm Gram), #11 (Phát hiện nhiễm tạp) | Sử dụng thị giác máy tính (Computer Vision) để giảm tải các thao tác quan sát bằng mắt lặp đi lặp lại của nghiên cứu viên. | Cụm có tính ứng dụng chuyên môn cao, giải quyết điểm đau vật lý thực sự. |
| **B: Số hóa dữ liệu & ghi chép thí nghiệm** | #5 (Log tủ ấm), #7 (Quản lý hóa chất), #8 (Xử lý số đo OD), #12 (Số hóa sổ tay lab) | Chuyển đổi dữ liệu từ dạng vật lý/sổ sách sang bảng tính kỹ thuật số. | Nhiều bài toán chỉ cần Rule / Database / IoT, chưa cần AI can thiệp. |
| **C: Hỗ trợ học tập & làm việc nhóm** | #1 (Meeting notes), #2 (Tra cứu tài liệu khóa học), #10 (Format báo cáo) | Tối ưu hóa giao tiếp, sắp xếp thông tin và tài liệu học tập/dự án của sinh viên. | Dễ hiểu, dễ tiếp cận nhưng thiếu tính đột phá kỹ thuật trong môi trường lab. |
| **D: Đời sống & sinh hoạt cá nhân** | #3 (Gợi ý món ăn hàng ngày) | Bài toán gợi ý quyết định cá nhân hóa hàng ngày. | Phạm vi cá nhân, khó nhân rộng thành quy trình nghiệp vụ rõ ràng. |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| **Candidate #4: Đếm khuẩn lạc (Colony Counting) trên đĩa Petri** | - Actor cực kỳ rõ ràng: Kỹ thuật viên / Nghiên cứu viên phòng lab vi sinh.<br>- Workflow chuẩn mực: Chụp ảnh → Phát hiện khuẩn lạc → Đếm số lượng → Xuất báo cáo.<br>- Bottleneck định lượng rất rõ: 10–15 phút/đĩa, mật độ >100 CFU dễ đếm sót/trùng.<br>- Có thể so sánh rõ ràng Rule vs Workflow vs Agent. | Xử lý các cụm khuẩn lạc dính chùm, chồng lấn lên nhau (overlapping colonies) và bọt khí trên mặt thạch. |
| **Candidate #1: Tổng hợp meeting notes & trích xuất Action Items sau họp** | - Workflow rõ ràng (5 bước), nhóm đều hiểu domain.<br>- Impact đo lường được bằng số phút tiết kiệm (từ 25' xuống 5').<br>- Có thể thử nghiệm ngay trong các buổi làm việc nhóm. | Phụ thuộc vào chất lượng transcript/ghi chú; tính độc đáo không cao bằng bài toán lab. |
| **Candidate #6: Phân loại chủng vi khuẩn qua ảnh kính hiển vi** | - Bài toán AI Vision chuyên sâu, giá trị nghiên cứu cao.<br>- Giảm tải công sức đối chiếu atlas vi sinh học của chuyên gia. | Cần dữ liệu kính hiển vi độ phân giải cao; độ mơ hồ lớn; rủi ro nhận diện sai chủng gây hậu quả nghiêm trọng. |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| **Đếm khuẩn lạc trên đĩa Petri** | 5 | 5 | 5 | 5 | 5 | 5 | 4 | **34** |
| **Tổng hợp meeting notes** | 5 | 5 | 4 | 4 | 5 | 4 | 5 | **32** |
| **Phân loại ảnh vi khuẩn qua kính hiển vi** | 4 | 3 | 4 | 4 | 2 | 4 | 3 | **24** |

**Candidate nhóm chọn (1 bài duy nhất):**

```text
Hệ thống AI Workflow hỗ trợ đếm khuẩn lạc (Colony Counting) trên đĩa Petri và tự động xuất báo cáo Excel cho phòng thí nghiệm vi sinh.
```

**Vì sao chọn (4-5 câu):**

```text
1. Vấn đề có actor và bối cảnh nghiệp vụ cực kỳ sắc nét: kỹ thuật viên vi sinh vật phải ngồi đếm thủ công hàng chục đĩa Petri mỗi ngày sau thời gian nuôi cấy.
2. Điểm nghẽn (bottleneck) được định lượng chính xác: mất 10–15 phút/đĩa, gây mỏi mắt nghiêm trọng và tỷ lệ đếm sót/trùng tăng vọt khi mật độ đĩa vượt quá 100 CFU.
3. Bài toán phù hợp hoàn hảo với mô hình AI Workflow có sự tham gia của con người (Human-in-the-loop): AI hỗ trợ bước phát hiện/đếm nặng nhất, con người giữ quyền kiểm soát và hiệu chỉnh (Click ±1) trước khi xuất file Excel.
4. Metric cải tiến mang tính đột phá: giảm thời gian từ 10–15 phút xuống dưới 2 phút/đĩa, loại bỏ hoàn toàn thao tác nhập liệu tay và đảm bảo độ chính xác ≥ 93% so với chuyên gia.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
- Tổng hợp meeting notes: Dù workflow rõ ràng và nhóm hiểu sâu, nhưng đây là bài toán xử lý văn bản (NLP) khá thông dụng, không khai thác được thế mạnh xử lý hình ảnh thị giác máy tính và chưa tạo ra tác động vật lý lớn như việc giải phóng sức lao động trong phòng thí nghiệm.
- Phân loại vi khuẩn qua kính hiển vi: Yêu cầu nguồn ảnh hiển vi chuyên dụng phức tạp, dữ liệu phân loại vi sinh vật đòi hỏi chuyên gia giải phẫu tế bào đánh giá nhãn, độ rủi ro khi nhận diện sai rất cao, không khả thi để làm pilot và đo lường trọn vẹn trong khuôn khổ bài lab.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
- Thành viên lo lắng: Liệu nhóm có đủ chuyên môn sâu về vi sinh vật để hiểu hết các loại hình thái khuẩn lạc không? Nếu khuẩn lạc mọc loang (swarming) hoặc thạch bị nứt thì AI có đếm sai không?
- Cách nhóm chốt: Thiết kế quy trình chặt chẽ với Human Boundary — AI không tự động ra quyết định tuyệt đối. Sau khi AI phát hiện, hệ thống sẽ phủ lớp chấm màu (Overlay mask) trên màn hình để kỹ thuật viên kiểm tra bằng mắt trong 30 giây và click ±1 sửa lỗi trực tiếp trước khi nhấn Export kết quả.
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| **Interview** (KTV & sinh viên làm việc tại Lab Vi sinh UET / Viện Vi sinh vật) | 3 người | *"Mỗi đợt làm thí nghiệm pha loãng nồng độ phải đếm cả series 20–30 đĩa Petri. Đĩa nào thưa thì đếm nhanh, chứ đĩa mật độ trên 100 CFU khuẩn lạc dính chùm vào nhau, vừa đếm vừa lấy bút lông chấm đáy đĩa hoa cả mắt. Đếm xong lại phải gõ từng số vào Excel, rất sợ gõ nhầm dòng làm lệch kết quả cả mẻ nuôi cấy."* | Với những đĩa quá thưa (<30 CFU), kỹ thuật viên đếm bằng mắt chỉ mất 1–2 phút nên không cần thiết phải đưa vào máy quét. | Thu hẹp trọng tâm: Tối ưu hóa thuật toán tách vùng (Watershed) cho các đĩa có mật độ từ 100–300 CFU và khuẩn lạc mọc dính chùm. |
| **Survey / Poll nhanh** (Nhóm sinh viên nghiên cứu Sinh học / CNSH) | 8 người | 7/8 người xác nhận thao tác đếm khuẩn lạc bằng mắt gây mỏi mắt, nhức đầu sau 30 phút làm việc liên tục; 6/8 người từng bị nhầm số khi gõ kết quả từ sổ tay vào máy tính. | 2 người lo ngại chụp ảnh bằng điện thoại trong điều kiện ánh sáng phòng lab bình thường sẽ bị lóa nắp đĩa Petri. | Bổ sung bước 1: Chuẩn hóa điều kiện chụp ảnh đầu vào (sử dụng hộp chụp cố định góc chụp, ánh sáng đèn LED nền đen chống phản quang). |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Điểm đau thực sự không chỉ là việc "đếm số", mà nằm ở sự kết hợp giữa: (1) mỏi mắt và sai sót khi phải phân tách các cụm khuẩn lạc dính chùm có mật độ cao (>100 CFU), và (2) sự phiền toái, dễ nhầm lẫn khi phải nhập thủ công từng con số vào bảng Excel.
```

Bằng chứng đính kèm: `02-group-problem-statement-workflow.jpg` (Infographic tổng quan dự án do nhóm xây dựng).

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| **OpenCFU** (Mã nguồn mở C++) | http://opencfu.sourceforge.net/ | Tự động nhận diện và đếm khuẩn lạc từ ảnh kỹ thuật số bằng thuật toán lọc ngưỡng và Watershed truyền thống. | Miễn phí, tốc độ xử lý nhanh trên máy tính cá nhân, có khả năng lọc tạp chất theo kích thước và màu sắc. | Thuật toán xử lý ảnh cổ điển dễ thất bại khi khuẩn dính chùm phức tạp hoặc ánh sáng không đồng đều; giao diện cũ, không có tính năng click ±1 trực quan trên ảnh; không tự động xuất báo cáo Excel chuẩn hóa. | Rule/Computer Vision truyền thống cần kết hợp thêm Deep Learning và giao diện tương tác Human-in-the-loop để người dùng sửa nhanh. |
| **Scan 1200 / Scan 4000 (Interscience)** | https://www.interscience.com/en/products/automatic-colony-counters/scan-1200 | Hệ thống phần cứng buồng chụp chuyên dụng tích hợp camera HD và phần mềm đếm tự động đạt chuẩn dược điển (CFR 21). | Độ chính xác rất cao, tự động phân tách khuẩn lạc dính nhau, tự xuất file báo cáo truy xuất nguồn gốc. | Chi phí phần cứng cực kỳ đắt đỏ ($10.000 – $30.000 USD/máy), cồng kềnh, không thể trang bị rộng rãi cho các lab trường học hay nghiên cứu vừa và nhỏ. | Không cạnh tranh bằng phần cứng đắt tiền; tập trung vào giải pháp phần mềm linh hoạt (chạy trên ảnh chụp điện thoại/webcam chuẩn hóa). |
| **Roboflow Colony Counter / YOLOv8 Vision** | https://roboflow.com/model/colony-counter | Ứng dụng mô hình Deep Learning (Object Detection / Segmentation) để phát hiện tọa độ từng khuẩn lạc trên ảnh đĩa Petri. | Nhận diện vượt trội đối với các khuẩn lạc đa dạng hình thái, màu sắc và ít bị ảnh hưởng bởi vết lóa ánh sáng hơn so với filter cổ điển. | Chỉ là API nhận diện đối tượng thuần túy, chưa đóng gói thành quy trình nghiệp vụ lab (thiếu bước overlay mask kiểm tra và export Excel). | Áp dụng mô hình AI Vision hiện đại làm lõi xử lý, nhưng phải xây dựng thành một Workflow hoàn chỉnh phục vụ đúng thói quen của KTV. |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Nhóm không nên tự chế tạo phần cứng đắt tiền hay cố gắng xây dựng một AI Agent tự trị hoàn toàn. Hướng đi đúng đắn nhất là xây dựng một AI Workflow tinh gọn: chuẩn hóa khâu chụp ảnh đầu vào, dùng Watershed + AI Vision để tự động nhận diện và khoanh vùng khuẩn lạc, cung cấp giao diện Overlay mask cho phép KTV click ±1 sửa lỗi tức thì, và tự động xuất dữ liệu ra file Excel chuẩn phòng lab.
```

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

Dán workflow hoặc link file: `02-group-problem-statement-workflow.jpg`

```text
[1 Lấy đĩa Petri ra khỏi tủ ấm: 1'] 
→ [2 Đặt đĩa lên bàn soi đèn: 1'] 
→ [3 Dùng bút lông chấm đáy đĩa & đếm nhẩm bằng mắt: 10-15']  <-- BOTTLENECK CHÍNH (mỏi mắt, sót/trùng)
→ [4 Ghi số CFU tạm thời ra sổ tay giấy: 1'] 
→ [5 Mở máy tính, gõ thủ công số liệu vào file Excel: 3-5']   <-- BOTTLENECK PHỤ (dễ gõ nhầm dòng)
→ [6 Kiểm tra & lưu báo cáo: 1']
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1 | Kỹ thuật viên | Đĩa Petri trong tủ ấm sau nuôi cấy 24–48h | Đĩa Petri sẵn sàng trên bàn thao tác | 1 phút / đĩa | Thao tác vật lý thông thường. |
| 2 | Kỹ thuật viên | Đĩa Petri | Đĩa đặt trên bàn soi đèn nền đen | 1 phút / đĩa | Chuẩn bị vị trí quan sát. |
| 3 | Kỹ thuật viên | Đĩa Petri có khuẩn lạc mọc trên mặt thạch | Số lượng đếm được trong đầu; các chấm mực bút lông dưới đáy đĩa | **10–15 phút / đĩa** | **BOTTLENECK CHÍNH**: Căng mắt quan sát từng chấm li ti; mật độ >100 CFU khuẩn dính nhau rất dễ đếm trùng/sót; gây mỏi mắt và đau đầu sau 3–5 đĩa liên tục. |
| 4 | Kỹ thuật viên | Số lượng đếm được | Số liệu ghi chép trên sổ tay nháp | 1 phút / đĩa | Handoff từ trí nhớ sang sổ giấy. |
| 5 | Kỹ thuật viên | Số liệu trên sổ tay nháp | Dòng dữ liệu được gõ vào bảng tính Excel | **3–5 phút / đĩa** | **BOTTLENECK PHỤ**: Phải đối chiếu mã mẫu và gõ tay từng số; dễ nhầm lẫn hàng/cột khi làm việc trong tình trạng mệt mỏi. |
| 6 | Nghiên cứu viên | Bảng tính Excel | Báo cáo thí nghiệm hoàn chỉnh | 1 phút / đĩa | Lưu trữ và đối soát cuối cùng. |

**Bottleneck chính (2-3 câu):**

```text
Điểm nghẽn nghiêm trọng nhất nằm ở bước 3 (đếm thủ công bằng mắt mất 10–15 phút/đĩa) và bước 5 (nhập tay vào Excel mất 3–5 phút). Khi mật độ vi sinh vật vượt quá 100 CFU, các khuẩn lạc chồng lấn lên nhau khiến con người không thể phân biệt chính xác bằng mắt thường, gây mỏi mắt quá tải và làm sai lệch kết quả thí nghiệm khi gõ lại số liệu.
```

### 5.2. Future workflow bản nhóm

```text
[1 Chụp ảnh đĩa Petri chuẩn hóa: 1' - KTV làm] 
→ [2 Watershed + AI Vision nhận diện & đếm: 5-10s - Máy/AI Workflow]  <-- AI Intervention Point
→ [3 Overlay mask chấm màu hiển thị trên màn hình: 30s - KTV quan sát]
→ [4 Click ±1 hiệu chỉnh nếu đếm sót/trùng: 30-45s - KTV làm]        <-- Human Boundary
→ [5 Tự động xuất kết quả và metadata vào Excel: 5s - Rule/Script]
```

**Fallback:** Nếu ảnh chụp bị mờ, lóa sáng nắp đĩa hoặc khuẩn lạc mọc loang (swarming) vượt quá khả năng nhận diện của AI → Kỹ thuật viên bấm nút "Hủy và chụp lại" hoặc chuyển sang phương thức đếm thủ công truyền thống như trước.

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| **Tổng thời gian** | 15–23 phút / đĩa | **< 2 phút / đĩa** (giảm >85%) | Bấm giờ từ lúc có đĩa đến khi dữ liệu nằm trên file Excel. |
| **Số bước thao tác** | 6 bước | 5 bước | So sánh sơ đồ quy trình làm việc. |
| **Số bước thủ công** | 6 / 6 bước (100% người làm) | 2 / 5 bước (KTV chỉ chụp ảnh và review click ±1) | Đếm số bước con người phải trực tiếp thao tác. |
| **Độ chính xác** | 88–92% (giảm mạnh khi >100 CFU do mỏi mắt) | **≥ 93%** so với chuyên gia đếm chuẩn | So sánh số CFU AI đếm với số đếm của 2 chuyên gia độc lập. |
| **Bottleneck chính** | Đếm nhẩm bằng mắt và gõ Excel | Chuyển thành bước Review kiểm tra overlay mask | Đổi từ điểm nghẽn "lao động chân tay mệt mỏi" thành "điểm kiểm soát chất lượng". |
| **Risk mới** | Không có AI hallucination | AI có thể đếm nhầm cặn thạch/bọt khí hoặc bỏ sót khuẩn dính chùm | Triệt tiêu hoàn toàn nhờ bước kiểm tra và click ±1 của KTV. |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | Kỹ thuật viên (KTV) xét nghiệm vi sinh và Nghiên cứu viên (NCV) tại các phòng thí nghiệm sinh học, công nghệ sinh học và kiểm nghiệm thực phẩm/dược phẩm. |
| **Workflow** | Sau khi nuôi cấy, KTV lấy đĩa Petri ra bàn soi đèn, dùng bút lông chấm từng khuẩn lạc dưới đáy đĩa để đếm nhẩm bằng mắt, ghi kết quả ra giấy rồi gõ lại từng số liệu vào file Excel báo cáo. |
| **Bottleneck** | Thao tác đếm bằng mắt lặp đi lặp lại tốn 10–15 phút/đĩa, gây mỏi mắt căng thẳng; khi đĩa có mật độ cao (>100 CFU) các khuẩn dính chùm rất dễ đếm sót/trùng; bước nhập liệu thủ công vào Excel tốn thêm 3–5 phút và dễ nhầm dòng. |
| **Impact** | Một buổi làm việc đếm 20–30 đĩa tiêu tốn 4–6 tiếng của nhân sự có chuyên môn cao; nguy cơ sai lệch kết quả kiểm nghiệm vi sinh dẫn đến đánh giá sai chất lượng mẫu hoặc phải làm lại toàn bộ mẻ nuôi cấy tốn kém. |
| **Success Metric** | Giảm tổng thời gian xử lý từ 10–15 phút xuống dưới 2 phút/đĩa; độ chính xác đạt ≥ 93% so với chuyên gia; loại bỏ 100% sai sót do nhập liệu tay vào Excel. |
| **Boundary** | AI chỉ hỗ trợ phát hiện và đếm số lượng khuẩn lạc từ ảnh chụp; AI không tự ý lưu hay xuất báo cáo nếu chưa có xác nhận của KTV; AI không thay thế con người phân loại chủng vi khuẩn gây bệnh trong giai đoạn này. |

**Câu hỏi AI phản biện v0 (nếu có):**
- **Field nào mơ hồ:** Metric độ chính xác ≥ 93% tính trên tổng số khuẩn lạc hay tính trên từng đĩa? Nếu đĩa có 500 khuẩn lạc thì sai số 7% là 35 con, liệu lab có chấp nhận được không?
- **Tôi sửa gì:** Bổ sung cơ chế: Độ chính xác ≥ 93% là kết quả sau bước AI nhận diện tự động; sau đó con người có quyền click ±1 để đưa độ chính xác cuối cùng của file Excel về xấp xỉ 98–100%.

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- **Độ mơ hồ: [x] Thấp** (có đúng/sai rõ) / [ ] Cao — Vì sao: Khuẩn lạc là thực thể vật lý hữu hình trên đĩa thạch, số lượng CFU có đáp án đúng/sai tuyệt đối (ground truth) xác định được bằng chuyên gia.
- **Độ phức tạp: [ ] Thấp / [x] Cao** (3+ bước/nguồn, phụ thuộc nhau) — Vì sao: Quy trình đòi hỏi kết hợp nhiều bước nối tiếp: Chuẩn hóa ảnh đầu vào → Tiền xử lý tách đĩa → Thuật toán Watershed/Deep Learning phát hiện đối tượng → Render giao diện Overlay mask tương tác → Export tự động ra bảng tính Excel.

**Bài toán nhóm nằm ở ô nào:**

```text
Ô "Độ mơ hồ thấp — Độ phức tạp cao": Phù hợp nhất với Workflow có AI hỗ trợ ở khâu nhận diện cốt lõi, không cần Agent tự trị.
```

**Vì sao (2-3 câu):**

```text
Bài toán có mục tiêu và quy tắc xác định rõ ràng (đếm chính xác số lượng khuẩn lạc), nhưng các bước xử lý hình ảnh và dữ liệu cần xâu chuỗi tuần tự và có sự kiểm soát chặt chẽ. Mô hình Workflow cho phép tự động hóa tối đa khâu nặng nhọc nhất nhưng vẫn giữ được tính minh bạch và có điểm dừng an toàn cho con người kiểm chứng.
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | Dùng ngưỡng màu tĩnh (Color Thresholding) hoặc bộ lọc hình thái học cố định để tách đốm sáng/tối. | Chỉ đủ khi đĩa cực kỳ sạch, thạch trong suốt, khuẩn lạc tròn xoe, đứng tách rời nhau hoàn toàn và ánh sáng đồng đều 100%. | Hoàn toàn thất bại khi khuẩn dính chùm, màu thạch biến thiên hoặc đĩa có bọt khí/vết nứt xước. | **Không chọn làm giải pháp chính**. Chỉ dùng Rule đơn giản cho bước xuất dữ liệu sang file Excel (Export). |
| **Workflow** | Quy trình tuyến tính: Chụp ảnh chuẩn hóa → Watershed + AI Vision đếm → Overlay mask chấm màu → KTV click ±1 hiệu chỉnh → Export Excel. | **Phù hợp nhất**: Quy trình công việc rõ ràng, AI xử lý tác vụ thị giác nặng nhất, con người kiểm soát chất lượng ở khâu review trước khi chốt kết quả. | AI có thể đếm nhầm cặn lắng hoặc bỏ sót khuẩn dính chùm, nhưng rủi ro này được triệt tiêu nhờ bước click ±1 của KTV. | **CHỌN LÀM GIẢI PHÁP TOÀN BỘ**. |
| **Agent** | Xây dựng AI Agent tự điều khiển camera, tự xoay góc đĩa, tự quyết định phương pháp đếm và tự gửi báo cáo không cần người. | Chỉ cần khi hệ thống tự động hóa hoàn toàn trong nhà máy dược phẩm lớn với robot tự gắp đĩa và buồng nuôi cấy tự động. | Chi phí phát triển cực kỳ đắt đỏ, phức tạp không cần thiết; nguy cơ Agent tự quyết định sai lầm mà không có cơ chế giải thích rõ ràng. | **Chưa cần thiết**. Vượt quá nhu cầu và năng lực triển khai thực tế của phòng thí nghiệm. |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. **Rule có giải được 70-80% case không?** → Không, Rule chỉ giải được khoảng 30–40% các đĩa thưa và lý tưởng; với các đĩa nuôi cấy thực tế có khuẩn dính chùm hoặc nền thạch đục, Rule thất bại hoàn toàn.
2. **Các bước có đi thẳng một đường không hay phải rẽ nhánh?** → Quy trình đi thẳng một đường tuần tự: Chụp ảnh → Phân tích AI → Hiển thị Overlay → Người duyệt/sửa → Xuất Excel; chỉ có nhánh rẽ khi ảnh quá mờ phải chụp lại.
3. **Có thật sự cần Agent tự lập kế hoạch + gọi tool không?** → Hoàn toàn không cần, vì thứ tự các bước đã được chuẩn hóa cố định theo quy chuẩn phòng lab, không cần AI phải tự suy nghĩ bước tiếp theo.
4. **Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu?** → Kỹ thuật viên phát hiện ngay lập tức trên màn hình Overlay mask trong vòng 5–10 giây và dùng chuột click ±1 sửa lỗi trong vòng 30 giây.
5. **Có hạ được từ Agent → Workflow → Rule không?** → Nhóm chủ động chọn ngay mức Workflow, loại bỏ mức Agent vì quá phức tạp và không chọn mức Rule vì độ chính xác không đáp ứng được yêu cầu lab.

**Mức chọn:**

```text
Workflow (Human-in-the-loop AI Workflow).
```

**Vì sao chọn (3-4 câu):**

```text
1. Quy trình đếm khuẩn lạc có các bước nghiệp vụ tuyến tính và tiêu chuẩn đầu vào/đầu ra cực kỳ rõ ràng.
2. AI đóng vai trò công cụ đòn bẩy ở đúng bước nghẽn nhất: thay thế con người căng mắt chấm từng điểm trên đĩa.
3. Thiết kế giữ con người ở trung tâm (Human-in-the-loop) với giao diện Overlay mask chấm màu và công cụ Click ±1 giúp đảm bảo độ tin cậy tuyệt đối trước khi dữ liệu được ghi nhận chính thức vào Excel.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Phương pháp Rule thuần túy (như OpenCFU hay bộ lọc ảnh tĩnh) không đủ khả năng phân tách các cụm khuẩn lạc chồng lấn khi mật độ >100 CFU và rất nhạy cảm với vết nứt thạch hay ánh sáng phản chiếu. Nếu chỉ dùng Rule, kỹ thuật viên vẫn phải tự làm lại bằng tay tới hơn 60% trường hợp, không giải quyết triệt để điểm nghẽn.
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | Kỹ thuật viên (KTV) xét nghiệm và Nghiên cứu viên (NCV) tại các phòng thí nghiệm vi sinh học, kiểm nghiệm an toàn thực phẩm và dược phẩm. |
| **Workflow** | Chụp ảnh đĩa Petri chuẩn hóa → AI tự động tách vùng và đếm khuẩn lạc → Hiển thị Overlay mask chấm màu trên màn hình → KTV kiểm tra nhanh và click ±1 nếu cần → Tự động xuất số lượng và metadata vào file Excel. |
| **Bottleneck** | Thao tác chấm đếm thủ công bằng mắt tốn 10–15 phút/đĩa, dễ hoa mắt mệt mỏi và nhầm lẫn khi đĩa có mật độ cao (>100 CFU); khâu gõ số liệu tay vào Excel tốn thêm 3–5 phút và dễ lệch hàng. |
| **Impact** | Tiêu tốn 4–6 giờ lao động mỗi ngày của nhân sự chuyên môn cao; nguy cơ sai lệch số liệu kiểm nghiệm dẫn đến đánh giá sai độ an toàn vi sinh của mẫu nghiên cứu. |
| **Success Metric** | Giảm tổng thời gian xử lý xuống < 2 phút/đĩa (giảm >85%); độ chính xác mô hình AI ban đầu đạt ≥ 93% và đạt 99–100% sau bước KTV click ±1; loại bỏ hoàn toàn việc gõ Excel thủ công. |
| **Boundary (làm / không làm)** | **LÀM**: Nhận diện, khoanh vùng, đếm số lượng CFU, hiển thị overlay chấm màu trực quan và xuất file Excel.<br>**KHÔNG LÀM**: Không tự ý ghi đè số liệu nếu chưa có người bấm duyệt; không tự phân loại chủng vi khuẩn gây bệnh; không tự xử lý các đĩa bị mốc loang toàn phần (swarming). |
| **AI intervention point** | Can thiệp ngay sau bước chụp ảnh chuẩn hóa đĩa Petri và trước bước hiển thị kết quả cho KTV kiểm tra (Bước 2 trong quy trình). |
| **Mức chọn** | **Workflow**: Ứng dụng Watershed kết hợp Computer Vision / Deep Learning để xử lý hình ảnh, kết hợp cơ chế kiểm soát của con người qua tương tác Click ±1. |
| **Rủi ro & người thật kiểm tra** | **Rủi ro**: AI có thể bỏ sót khuẩn lạc dính chùm hoặc đếm nhầm cặn thạch/bọt khí.<br>**Kiểm soát**: Kỹ thuật viên bắt buộc phải quan sát Overlay mask trên màn hình và click chuột thêm/bớt điểm trước khi ấn nút "Xác nhận & Xuất Excel". |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | **Yes** | Actor là KTV/NCV vi sinh, workflow 5 bước từ chụp ảnh đến xuất Excel đã được chuẩn hóa chi tiết. |
| Baseline + metric đo được chưa? | **Yes** | Baseline đếm tay là 10–15 phút/đĩa; mục tiêu đo được chính xác là < 2 phút/đĩa và độ chính xác ≥ 93%. |
| Data/input đủ dùng chưa? | **Yes** | Có thể thu thập ngay tập dữ liệu ảnh đĩa Petri trong phòng lab trường hoặc dùng bộ dữ liệu công khai (AGAR dataset). |
| AI sai, hậu quả chấp nhận được không? | **Yes** | Hoàn toàn chấp nhận được vì có bước đệm Human Boundary (click ±1) sửa lỗi trực tiếp trước khi xuất báo cáo. |
| Có người review/owner không? | **Yes** | Kỹ thuật viên trực tiếp vận hành là người review và ký duyệt dữ liệu trên hệ thống. |
| Có cách non-AI đơn giản hơn không? | **Yes nhưng không đủ** | Đếm tay thủ công quá tốn thời gian; đếm bằng Rule ảnh cổ điển sai số rất cao khi đĩa có mật độ dày. |

**Decision:**

```text
GO với scope nhỏ (Pilot trong phòng thí nghiệm vi sinh).
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
1. Vấn đề thực tế có điểm đau vô cùng lớn và đo lường được bằng thời gian lao động cụ thể (tiết kiệm hơn 85% thời gian cho nhân sự lab).
2. Mô hình Workflow được thiết kế chặt chẽ với cơ chế Human-in-the-loop đảm bảo an toàn tuyệt đối, không có rủi ro nghiêm trọng khi AI đưa ra kết quả chưa hoàn hảo.
3. Giải pháp khả thi cao về mặt kỹ thuật khi kết hợp các thuật toán thị giác máy tính đã được chứng minh (Watershed + Object Detection) thay vì phụ thuộc vào các công nghệ viển vông.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
- Tập dữ liệu pilot: 50 đĩa Petri nuôi cấy vi khuẩn chuẩn (như E. coli, S. aureus) có mật độ từ 30 đến 300 CFU, đã được 2 chuyên gia đếm thủ công độc lập để làm nhãn chuẩn (Ground Truth).
- Quy trình chạy pilot: KTV dùng điện thoại chụp ảnh đĩa qua hộp chụp cố định, đưa vào phần mềm để AI chạy nhận diện và overlay mask, KTV đo thời gian kiểm tra và hiệu chỉnh click ±1 rồi xuất file Excel.
- Đo 3 con số cốt lõi:
  1. Thời gian trung bình hoàn thành 1 đĩa (Mục tiêu: < 2 phút/đĩa).
  2. Độ chính xác nhận diện tự động của AI so với chuyên gia (Mục tiêu: ≥ 93%).
  3. Số lần click ±1 trung bình KTV phải thao tác trên mỗi đĩa (Mục tiêu: < 5 click/đĩa).
```

**Nếu Not Yet — cần validate gì trước:**

```text
(Không áp dụng vì nhóm đã chọn GO). Tuy nhiên trong giai đoạn chuẩn bị pilot, nhóm sẽ validate thêm khả năng chống lóa sáng của hộp chụp thủ công làm bằng bìa carton và đèn LED.
```

**Nếu No-Go — làm gì thay AI:**

```text
(Không áp dụng). Nếu không dùng AI, lab chỉ có thể duy trì bút đếm khuẩn lạc thủ công có tiếng bíp (Colony Counter pen) và bắt buộc 2 người cùng đối soát độc lập.
```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
- Dừng pilot và quay về đếm tay truyền thống nếu:
  1. Sau 50 đĩa thử nghiệm, độ chính xác nhận diện tự động của AI thấp hơn 80% hoặc số lần click sửa lỗi vượt quá 15 click/đĩa (làm thời gian review lâu hơn đếm tay).
  2. Hệ thống liên tục nhận diện nhầm bọt khí và vết xước thạch thành khuẩn lạc trên nhiều chủng loại môi trường khác nhau mà không thể tinh chỉnh được ngưỡng lọc.
```

---

### Self-check nộp phần 02 (nhóm)
- [x] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score chi tiết)
- [x] Có validation (quote phỏng vấn thật) + research (link kiểm được của OpenCFU, Interscience Scan, Roboflow)
- [x] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [x] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm rõ ràng
- [x] Có so sánh Rule/Workflow/Agent + Decision Go với kế hoạch pilot 3 số đo và điều kiện exit/rollback
