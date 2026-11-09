# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm:
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu):
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Nguyễn Thế Văn | Khi mỗi ngày có hơn 50 sản phẩm mới cần đăng lên các fanpage, tôi muốn biến thông tin sản phẩm thành bài đăng mà không copy qua lại nhiều nơi, để kịp lịch đăng | Nhân viên content fanpage; quản lý duyệt | Chờ quản lý duyệt: 15'/bài (thao tác tay 13'/bài); 4–5 bài/tuần đăng trễ | [ghi lúc pitch] |
| 2 | Nguyễn Thế Văn | Khi một bài trên fanpage bị sai giá, tôi muốn biết ai đã đăng và ai đã duyệt, để sửa nhanh và nhắc đúng người | Quản lý fanpage | Hỏi group "ai đăng" và chờ người nhận: 10–15'/lần, 5–10 lần/tháng | [ghi lúc pitch] |
| 3 | Nguyễn Thế Văn | Khi có nhiều bài cần lên trong tuần, tôi muốn thấy bài nào đăng giờ nào trên trang nào, để không trùng hoặc trống lịch | Nhân viên content quản lý hơn 10 trang | Đến giờ vào từng trang đăng tay: >30'/ngày; 10 lần trùng/trống tuần trước | [ghi lúc pitch] |
| 4 | Lê Anh Sơn | Khi hoàn thành bài lab trước giờ nộp, tôi muốn đối soát nhanh quy cách file và checklist rubric, để không bị trừ điểm vì lỗi định dạng | Học viên làm lab | Kiểm thủ công từng cell notebook và đề mục markdown: 18/30' | [ghi lúc pitch] |
| 5 | Lê Anh Sơn | Khi bắt đầu buổi lab với 4–5 file hướng dẫn dài, tôi muốn nắm ngay danh sách đầu việc cá nhân và nhóm, để phân bổ 4 tiếng hợp lý | Nhóm trưởng, học viên | Chuyển qua lại giữa các tab tài liệu để ghép checkpoint → file → mục → tiêu chí: 20/35' | [ghi lúc pitch] |
| 6 | Lê Anh Sơn | Khi gọi API của nhà cung cấp LLM với tham số mới, tôi muốn tìm đúng tên tham số hiện hành, để code chạy ngay không bị lỗi 400 | Học viên làm lab tích hợp LLM | Tra tài liệu bị phân mảnh giữa phiên bản cũ và mới: 12/30' | [ghi lúc pitch] |
| 7 | Lưu Đăng Tuấn | Khi kỳ thi tới gần và phải ôn từ slide, ghi chú, đề cũ, group chat, tôi muốn biết phần nào là trọng tâm, để không ôn tràn lan và không bỏ sót | Sinh viên thi 2–3 môn cùng lúc | Tự tổng hợp nhiều nguồn và suy đoán mức quan trọng từng chủ đề (chưa có số phút) | [ghi lúc pitch] |
| 8 | Lưu Đăng Tuấn | Khi luyện đề cũ, tôi muốn biết dạng câu hỏi nào hay xuất hiện, để luyện đúng dạng | Sinh viên ôn thi | Đọc và tự phân loại câu hỏi đề cũ theo chương/dạng (chưa có số phút) | [ghi lúc pitch] |
| 9 | Lưu Đăng Tuấn | Khi cần xem lại một câu hỏi và lời giải đã được trả lời trong group chat, tôi muốn tìm lại nhanh và biết nó có đúng không, để không hỏi lại | Sinh viên trong group lớp | Lời giải rải rác trong luồng chat, từ khóa không khớp (chưa có số phút) | [ghi lúc pitch] |
| 10 | Hoàng Nguyên Long | Khi mở inbox Zalo OA/fanpage đầu ca, lễ tân muốn tách ngay tin theo loại, để tin triệu chứng được chuyển điều dưỡng sớm | Lễ tân phòng khám nhi (2 người/ca); điều dưỡng trực | Đọc tuần tự 40–60 tin để biết tin nào loại gì: ~25' trong ~45' đầu ca | [ghi lúc pitch] |
| 11 | Hoàng Nguyên Long | Khi phụ huynh gọi hỏi bé tiêm mũi gì tiếp theo, nhân viên muốn tra đúng mũi theo tuổi và lịch sử tiêm, để trả lời trong 1–2' | Nhân viên tư vấn hotline tiêm chủng | Tìm lịch sử tiêm và đối chiếu bảng lịch theo tuổi: ~6' trong ~10'/cuộc gọi | [ghi lúc pitch] |
| 12 | Hoàng Nguyên Long | Khi chuẩn bị đưa bố đi tái khám tiểu đường, tôi muốn có bảng chỉ số 6 tháng theo thời gian, để bác sĩ thấy xu hướng ngay | Người nhà chăm người bệnh mạn tính | Đọc từng tờ kết quả khác mẫu, chép chỉ số và đổi đơn vị: ~15' trong ~40'/lần | [ghi lúc pitch] |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A — Tổng hợp nhiều nguồn để biết cái gì quan trọng | #5, #7, #8, #12 | Thông tin nằm ở nhiều tài liệu khác mẫu; người dùng phải tự đọc, gom và suy ra phần quan trọng |
| B — Phân loại và tìm lại tin nhắn | #9, #10 | Tin viết tự do trôi trong luồng chat; khó biết tin nào thuộc loại gì hoặc tìm lại tin cũ |
| C — Đối chiếu với quy tắc hoặc bảng cố định | #2, #4, #6, #11 | Đáp án đã có sẵn ở một bảng, checklist hay log; chậm vì tra cứu tay, không vì cần suy luận |
| D — Sản xuất và phát hành nội dung lặp lại | #1, #3 | Khối lượng bài lớn mỗi ngày; nghẽn ở khâu duyệt và đăng tay trên nhiều trang |

*Nháp do AI gom từ 4 file cá nhân. Nhóm thảo luận và sửa lại khi làm CP3.*

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: 
├── Opportunity A: 
├── Opportunity B: 
└── Opportunity C: 
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

-

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| | | | | | | | | |
| | | | | | | | | |
| | | | | | | | | |

**Candidate được chọn:**

**Vì sao chọn:**

**Vì sao loại các candidate còn lại:**

**Xử lý bất đồng (nếu có):**

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Nhân viên content ở nơi khác cũng mất trên [__] phút/bài cho chuỗi soạn và đăng bài | Value | 5 | 1 | Có |
| 2 | Bước tốn thời gian nhất là soạn bài, không phải chờ duyệt | Value | 5 | 1 | Có |
| 3 | Bài sai thông tin xảy ra đủ thường để đáng giải (≥[__] lần/tháng) | Value | 4 | 2 | Có |
| 4 | Thông tin sản phẩm đã nằm ở một nguồn có cấu trúc (file, web, phần mềm bán hàng) | Feasibility | 4 | 2 | Có |
| 5 | Quản lý chấp nhận bài do AI soạn nháp nếu vẫn có bước duyệt | Viability | 4 | 1 | Hỏi quản lý |
| 6 | Team chưa dùng lên lịch và lịch sử hoạt động có sẵn của Facebook | Feasibility | 3 | 2 | — |

*Nháp cho candidate "đăng bài fanpage". Nhóm chốt candidate ở CP3 rồi sửa lại; cột điểm do nhóm tự chấm.*

Giả định nhóm kiểm chứng trong buổi này:

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | |
| Câu nói đáng nhớ nhất (nguyên văn) | |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | |
| Hiện đang xử lý bằng cách nào (workaround)? | |
| Mất bao lâu, bao lần? | |
| Insight / opportunity rút ra | |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| | | | |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Meta Business Suite — lên lịch bài cho Trang | https://www.facebook.com/business/help/1252240869631062 | Bước đăng: soạn trước, đặt giờ đăng, xem lịch các bài đã lên | Có sẵn, miễn phí cho người quản lý Trang | Không có bước duyệt nhiều cấp; không soạn bài | [nhóm điền] |
| Planable — quy trình duyệt bài | https://planable.io/guides/content-approvals-in-planable/ | Bước duyệt + lên lịch: duyệt bắt buộc rồi tự lên lịch khi được duyệt | Duyệt bắt buộc và tự lên lịch khi duyệt | Duyệt bắt buộc cần gói Pro, nhiều cấp cần Enterprise; tốn phí | [nhóm điền] |
| Facebook Page Management History (Social Media Today, 01/2020) | https://www.socialmediatoday.com/news/facebook-adds-new-page-management-history-tab-in-page-tools/570171/ | Bước "biết ai đăng": lịch sử thao tác quản trị của Trang | Có sẵn | Bài từ 2020; tab này ghi thay đổi vai trò và cài đặt, việc đăng bài nằm ở Activity Log; cần tự kiểm giao diện hiện tại | [nhóm điền] |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

**Bottleneck chính:**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | | | |
| Tổng thời gian | | | |
| Số bước thủ công | | | |
| Bottleneck chính | | | |
| Rủi ro mới phát sinh | | | |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

-

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | | | | |
| **Rule** | | | | |
| **Workflow** | | | | |
| **Agent** | | | | |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | |
| **Judgment** — con người cân nhắc, quyết định gì? | |
| **Action** — hành động cuối cùng là gì, ai làm? | |
| **Outcome** — đo kết quả bằng gì? | |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** | |
| **AI intervention point** | |
| **Mức chọn** | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra** | |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| | | | |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | | |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | | |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | | |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | | |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go

**Lý do:**

**Nếu Go — pilot nhỏ nhất:**

**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-
