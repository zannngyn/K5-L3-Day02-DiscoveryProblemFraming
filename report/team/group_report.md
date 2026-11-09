# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm:
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Nhân viên content đăng hơn 10 bài sản phẩm/ngày lên nhiều fanpage, mỗi bài mất 13 phút thao tác tay và 15 phút chờ quản lý duyệt, khiến 4–5 bài/tuần lỡ khung giờ đăng.
- Quyết định cuối: **Not Yet** (cần phỏng vấn người ngoài nhóm và bấm giờ 20 bài trước khi pilot)

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Nguyễn Thế Văn | Khi mỗi ngày có hơn 50 sản phẩm mới cần đăng lên các fanpage, tôi muốn biến thông tin sản phẩm thành bài đăng mà không copy qua lại nhiều nơi, để kịp lịch đăng | Nhân viên content fanpage; quản lý duyệt | Chờ quản lý duyệt: 15'/bài (thao tác tay 13'/bài); 4–5 bài/tuần đăng trễ | Bài gửi duyệt bị trả về sửa bao nhiêu % — nghẽn thật là chờ duyệt 15', hay là bước soạn trước đó làm bài phải duyệt lại? (Lê Anh Sơn) |
| 2 | Nguyễn Thế Văn | Khi một bài trên fanpage bị sai giá, tôi muốn biết ai đã đăng và ai đã duyệt, để sửa nhanh và nhắc đúng người | Quản lý fanpage | Hỏi group "ai đăng" và chờ người nhận: 10–15'/lần, 5–10 lần/tháng | Lần gần nhất bài sai giá là khi nào, từ lúc phát hiện đến lúc sửa xong mất bao lâu? (Hoàng Nguyên Long) |
| 3 | Nguyễn Thế Văn | Khi có nhiều bài cần lên trong tuần, tôi muốn thấy bài nào đăng giờ nào trên trang nào, để không trùng hoặc trống lịch | Nhân viên content quản lý hơn 10 trang | Đến giờ vào từng trang đăng tay: >30'/ngày; 10 lần trùng/trống tuần trước | Không có AI, chỉ dùng lên lịch có sẵn của Meta Business Suite thì cắt được bao nhiêu trong >30'/ngày? (Lưu Đăng Tuấn) |
| 4 | Lê Anh Sơn | Khi hoàn thành bài lab trước giờ nộp, tôi muốn đối soát nhanh quy cách file và checklist rubric, để không bị trừ điểm vì lỗi định dạng | Học viên làm lab | Kiểm thủ công từng cell notebook và đề mục markdown: 18/30' | Ngoài bạn còn ai gặp? Số 7/35 bạn bị nhắc lỗi định dạng ở Day 01 lấy từ đâu, có tin nhắn TA hay bảng điểm không? (Nguyễn Thế Văn) |
| 5 | Lê Anh Sơn | Khi bắt đầu buổi lab với 4–5 file hướng dẫn dài, tôi muốn nắm ngay danh sách đầu việc cá nhân và nhóm, để phân bổ 4 tiếng hợp lý | Nhóm trưởng, học viên | Chuyển qua lại giữa các tab tài liệu để ghép checkpoint → file → mục → tiêu chí: 20/35' | Không có AI, một cheat sheet 1 trang do nhóm trưởng làm trong 10' có giảm được nửa 20' không? (Lưu Đăng Tuấn) |
| 6 | Lê Anh Sơn | Khi gọi API của nhà cung cấp LLM với tham số mới, tôi muốn tìm đúng tên tham số hiện hành, để code chạy ngay không bị lỗi 400 | Học viên làm lab tích hợp LLM | Tra tài liệu bị phân mảnh giữa phiên bản cũ và mới: 12/30' | Lần gần nhất bị lỗi 400 vì sai tên tham số là khi nào, mất bao lâu mới chạy được? (Hoàng Nguyên Long) |
| 7 | Lưu Đăng Tuấn | Khi kỳ thi tới gần và phải ôn từ slide, ghi chú, đề cũ, group chat, tôi muốn biết phần nào là trọng tâm, để không ôn tràn lan và không bỏ sót | Sinh viên thi 2–3 môn cùng lúc | Tự tổng hợp nhiều nguồn và suy đoán mức quan trọng từng chủ đề (chưa có số phút) | Lần ôn thi gần nhất là môn nào, bạn mất bao nhiêu phút để tổng hợp nguồn và chốt trọng tâm? (Hoàng Nguyên Long) |
| 8 | Lưu Đăng Tuấn | Khi luyện đề cũ, tôi muốn biết dạng câu hỏi nào hay xuất hiện, để luyện đúng dạng | Sinh viên ôn thi | Đọc và tự phân loại câu hỏi đề cũ theo chương/dạng (chưa có số phút) | Ngoài bạn còn ai luyện đề bằng cách so nhiều đề để tìm dạng lặp, hay mọi người chỉ làm lần lượt từng đề? Có bằng chứng không? (Nguyễn Thế Văn) |
| 9 | Lưu Đăng Tuấn | Khi cần xem lại một câu hỏi và lời giải đã được trả lời trong group chat, tôi muốn tìm lại nhanh và biết nó có đúng không, để không hỏi lại | Sinh viên trong group lớp | Lời giải rải rác trong luồng chat, từ khóa không khớp (chưa có số phút) | Bottleneck là tìm lại tin, hay là bước sau nó — tìm thấy rồi vẫn không biết lời giải có đúng không nên phải hỏi lại? (Lê Anh Sơn) |
| 10 | Hoàng Nguyên Long | Khi mở inbox Zalo OA/fanpage đầu ca, lễ tân muốn tách ngay tin theo loại, để tin triệu chứng được chuyển điều dưỡng sớm | Lễ tân phòng khám nhi (2 người/ca); điều dưỡng trực | Đọc tuần tự 40–60 tin để biết tin nào loại gì: ~25' trong ~45' đầu ca | Bottleneck thật là đọc 25', hay là bước trước — phụ huynh không có lựa chọn phân loại khi nhắn? Bao nhiêu % tin là triệu chứng? (Nguyễn Thế Văn) |
| 11 | Hoàng Nguyên Long | Khi phụ huynh gọi hỏi bé tiêm mũi gì tiếp theo, nhân viên muốn tra đúng mũi theo tuổi và lịch sử tiêm, để trả lời trong 1–2' | Nhân viên tư vấn hotline tiêm chủng | Tìm lịch sử tiêm và đối chiếu bảng lịch theo tuổi: ~6' trong ~10'/cuộc gọi | Ngoài chị bạn còn ai gặp? Số 6'/cuộc gọi là bạn quan sát hay ước đoán từ phía người gọi? (Lê Anh Sơn) |
| 12 | Hoàng Nguyên Long | Khi chuẩn bị đưa bố đi tái khám tiểu đường, tôi muốn có bảng chỉ số 6 tháng theo thời gian, để bác sĩ thấy xu hướng ngay | Người nhà chăm người bệnh mạn tính | Đọc từng tờ kết quả khác mẫu, chép chỉ số và đổi đơn vị: ~15' trong ~40'/lần | Không có AI, mỗi lần nhận kết quả thì điền ngay 1 dòng Google Sheet (~2') có giảm được nửa 40'/tháng không? (Lưu Đăng Tuấn) |

#### Hỏi đáp khi pitch

*Nháp đóng vai do AI soạn từ 4 báo cáo cá nhân. Mỗi người tự sửa câu trả lời của mình cho đúng thực tế; chỗ ghi "chưa đo" đưa vào Assumption Map ở CP4.*

| Card | Người hỏi → người trả lời | Câu trả lời | Hệ quả cho nhóm |
|---:|---|---|---|
| #1 | Sơn → Văn | Chưa đếm tỉ lệ bài bị trả về. Số đã có: chờ duyệt 15'/bài, thao tác tay 13'/bài, 4–5 bài/tuần đăng trễ. Nếu bài bị trả về nhiều thì nghẽn nằm ở bước soạn | Giả định "nghẽn ở chờ duyệt, không phải soạn" cần kiểm chứng trước |
| #2 | Long → Văn | Gặp 5–10 lần/tháng, riêng khâu hỏi group "ai đăng" mất 10–15'/lần; thời gian bài sai còn hiển thị với khách chưa đo | Đo thêm thời gian từ lúc phát hiện đến lúc sửa xong |
| #3 | Tuấn → Văn | Lên lịch có sẵn bỏ được bước canh giờ vào từng trang (3'/bài); team chưa dùng vì chưa có lịch chung. Chưa thử nên chưa có số | Phương án No AI có thể giải phần lớn #3 |
| #4 | Văn → Sơn | 7/35 là số bạn bị nhắc trong lớp Day 01; cần tìm lại tin nhắn TA để làm bằng chứng | Bằng chứng mới ở mức kể lại |
| #5 | Tuấn → Sơn | Có thể: bước nghẽn là chuyển tab để ghép checkpoint → file → mục → tiêu chí (20/35'). Cheat sheet làm 1 lần dùng được cho cả lớp | #5 nghiêng về No AI |
| #6 | Long → Sơn | Bước tra docs mất 12/30'; chưa ghi ngày và số lần gặp lỗi 400 | Thiếu tần suất, khó chấm "Pain có bằng chứng" |
| #7 | Long → Tuấn | Chưa đo. Quy trình hiện tại mới là giả thuyết | Thiếu số phút, chưa đủ để vào shortlist |
| #8 | Văn → Tuấn | Chưa chắc; đây chính là câu cần kiểm chứng trong card: sinh viên có dùng nhiều đề để tìm dạng lặp hay chỉ làm lần lượt | Pain chưa có bằng chứng |
| #9 | Sơn → Tuấn | Đồng ý: bước nghẽn đã ghi trong card là "kiểm tra câu trả lời và ngữ cảnh", không phải tìm từ khóa. Chưa đo số lần hỏi lại | Bottleneck dời sang bước xác minh |
| #10 | Văn → Long | Lễ tân kể 40–60 tin/sáng, 35–45' đọc và phân loại; tuần trước 1 tin bé sốt cao bị trả lời sau 2 tiếng. Tỉ lệ tin triệu chứng chưa đếm; menu bấm sẵn trên Zalo OA giải được phần lớn nhưng nhiều phụ huynh vẫn gõ tự do | Cần đếm tỉ lệ tin gõ tự do và tin triệu chứng |
| #11 | Sơn → Long | Số liệu từ phía người gọi: chị gọi 3 lần/năm, mỗi lần chờ máy 5–10'. 6'/cuộc gọi là ước đoán, chưa quan sát nhân viên | Nhóm không có ai trong domain; lịch tiêm là Rule nên ít chỗ so sánh 4 mức |
| #12 | Tuấn → Long | Có thể: bước nghẽn là chép chỉ số từ các mẫu khác nhau (~15'); điền ngay mỗi lần thì tối trước khám chỉ còn mở sheet. Tần suất thấp: 1 lần/tháng | Impact nhỏ, No AI đủ dùng |

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
OUTCOME: Giảm thời gian từ lúc có sản phẩm mới đến lúc bài đúng thông tin lên fanpage đúng khung giờ, không tăng số bài sai giá
├── Opportunity A: Bài chờ quản lý duyệt ~15'/bài, lâu hơn cả phần thao tác; 4–5 bài/tuần lỡ khung giờ đăng (#1)
├── Opportunity B: Mỗi bài phải copy tay tên, giá, ảnh sản phẩm qua nhiều nơi, ~13'/bài thao tác (#1)
├── Opportunity C: Đến giờ phải vào từng trang trong >10 trang để đăng; tuần trước 10 lần trùng giờ hoặc bỏ trống (#3)
└── Opportunity D: Khi bài sai giá, mất 10–15'/lần hỏi group để biết ai đăng, ai duyệt; 5–10 lần/tháng (#2)
     ✗ "AI tự viết bài từ thông tin sản phẩm"   ← solution, gạch khỏi tầng này
     ✗ "Tool tự đăng lên tất cả các trang"      ← solution, gạch khỏi tầng này
     ✗ "Bot nhắc quản lý duyệt bài"             ← solution, gạch khỏi tầng này
     ✗ "Dashboard theo dõi ai đăng bài nào"     ← solution, gạch khỏi tầng này
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- "Thiếu công cụ AI viết bài": đây là cách giải cho Opportunity B. Câu hỏi của Sơn ở #1 cho thấy nếu nghẽn nằm ở chờ duyệt thì viết nhanh hơn cũng không làm bài lên sớm hơn.
- "Cần tự động đăng lên nhiều trang": là cách giải cho Opportunity C. Pain thật là phải canh giờ và vào từng trang, và Meta Business Suite có thể đã giải được (câu hỏi của Tuấn ở #3).
- "Cần dashboard truy vết bài": là cách giải cho Opportunity D. Pain thật là mất 10–15' để tìm đúng người.

### 2.4. Chấm điểm shortlist (1–5)

Shortlist lấy 1 candidate mạnh nhất từ 3 người có số liệu đo được. Cluster A của Tuấn (#7, #8, #9) không vào shortlist vì chưa có số phút hay tần suất (câu hỏi của Long ở #7, của Văn ở #8).

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| #1 Soạn, duyệt, đăng bài sản phẩm lên fanpage (gộp #2, #3) | 5 | 5 | 4 | 5 | 4 | 5 | 4 | **32** |
| #10 Phân loại inbox đầu ca phòng khám nhi | 5 | 5 | 4 | 4 | 3 | 5 | 2 | 28 |
| #4 Đối soát quy cách file với rubric trước giờ nộp lab | 5 | 5 | 3 | 3 | 5 | 2 | 5 | 28 |

Lý do chấm ở các ô thấp:
- #1 "Vừa sức lab" 4: khối lượng lớn (hơn 10 trang), nhưng thu hẹp được về 1 trang và 1 loại sản phẩm. "Pain có bằng chứng" 4: số liệu do Văn tự trải nghiệm, chưa có người ngoài nhóm xác nhận.
- #10 "Vừa sức lab" 3: không truy cập được inbox thật, và dữ liệu tin nhắn có thông tin sức khỏe của trẻ. "Nhóm hiểu domain" 2: chỉ Long biết bối cảnh, qua lời kể của lễ tân.
- #4 "So sánh 4 mức" 2: Sơn và AI phản biện đều kết luận một script Rule là đủ, nên gần như không có gì để so ở mức Workflow hay Agent. "Pain có bằng chứng" 3: con số 7/35 mới là kể lại, chưa có tin nhắn của TA (câu hỏi của Văn).

**Candidate được chọn:** #1. Khi nhân viên content cần đăng hơn 10 bài sản phẩm mỗi ngày lên nhiều fanpage, bài bị chậm vì phải chờ duyệt và đăng tay từng trang, khiến 4–5 bài/tuần lỡ khung giờ đăng.

**Vì sao chọn:** Điểm cao nhất (32). Quy trình đã có số phút cho từng bước. Ba candidate #1, #2, #3 cùng actor và cùng quy trình nên gom được thành 1 bài có 4 opportunity. Bài cũng có đủ phương án ở cả 4 mức để so sánh ở CP6: No AI (khung giờ duyệt cố định, template), Rule (lên lịch, file sản phẩm chuẩn), Workflow (AI soạn nháp, người duyệt), Agent. Chỗ chưa chắc là nghẽn nằm ở khâu soạn hay khâu chờ duyệt; nhóm chuyển câu này thành giả định cần kiểm chứng trước ở CP4.

**Vì sao loại các candidate còn lại:**
- #10: impact tốt, nhưng dữ liệu y tế nhạy cảm, không lấy được inbox thật trong buổi lab, và chỉ 1 người hiểu domain.
- #4: Rule đã đủ dùng, nên không đáp ứng tiêu chí so sánh 4 mức can thiệp.
- #5, #12: phương án không dùng AI (cheat sheet, Google Sheet) đã giải gần hết. #12 lại chỉ xảy ra 1 lần/tháng.
- #6, #11: thiếu tần suất. Con số 6'/cuộc gọi ở #11 là ước đoán từ phía người gọi.
- #7, #8, #9: chưa có số phút, quy trình mới là giả thuyết.

**Xử lý bất đồng (nếu có):** Long muốn chọn #10 vì tin triệu chứng bị trả lời muộn 2 tiếng là rủi ro thật cho trẻ. Nhóm đồng ý #10 có impact lớn nhất về an toàn, nhưng không kiểm chứng được trong buổi lab và có ranh giới y tế cần người trong ngành. Nhóm ghi #10 vào mục 9 "Hướng tiếp theo" và chọn #1 vì có baseline đo được ngay.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Nhân viên content ở nơi khác cũng mất trên 20 phút/bài cho chuỗi soạn, chờ duyệt và đăng bài (baseline của Văn: 28 phút/bài) | Value | 5 | 1 | Có |
| 2 | Bước tốn thời gian nhất là chờ duyệt (15'), không phải soạn bài (10' gồm copy, AI viết, sửa) | Value | 5 | 2 | Có |
| 3 | Bài sai thông tin xảy ra đủ thường để đáng giải (≥5 lần/tháng) | Value | 4 | 2 | Có |
| 4 | Thông tin sản phẩm đã nằm ở một nguồn có cấu trúc (file, web, phần mềm bán hàng) | Feasibility | 4 | 2 | Có |
| 5 | Quản lý chấp nhận duyệt theo lô ở khung giờ cố định thay vì duyệt từng bài | Viability | 4 | 1 | Hỏi quản lý |
| 6 | Team chưa dùng lên lịch và lịch sử hoạt động có sẵn của Facebook | Feasibility | 3 | 2 | — |

Bằng chứng hiện có chỉ là số liệu Văn tự đo khi làm việc, nên các giả định Value đều ở mức 1–2.

Giả định nhóm kiểm chứng trong buổi này: **#2** (nghẽn ở chờ duyệt hay ở soạn bài), **#1** (người ngoài nhóm có gặp không) và **#5** (quản lý có chấp nhận duyệt theo lô không). Nếu #2 sai thì cả quy trình tương lai ở mục 4 phải vẽ lại.

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn theo The Mom Test, bộ câu hỏi ở [cp4-interview-guide.md](../assets/cp4-interview-guide.md). Mục tiêu: 2–3 người ngoài nhóm có làm content hoặc quản lý fanpage.

> **Chưa thực hiện.** Chưa có buổi phỏng vấn thật nào. Các ô dưới đây để trống, không điền thay. Mỗi buổi ghi vào `report/assets/cp4-interview-snapshot-N.md` theo mẫu trong guide.

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
| Văn tự bấm giờ khi làm việc (trong nhóm) | 1 | 28 phút/bài (13' thao tác + 15' chờ duyệt); 4–5 bài/tuần trễ; 10 lần trùng hoặc trống lịch tuần trước; 5–10 lần/tháng phải tìm người đăng bài sai | Bước 2 đã dùng AI để viết bài, nên "viết bài" không còn là chỗ nghẽn; phần chậm là chờ duyệt và đăng tay |
| Phỏng vấn người ngoài nhóm | 0 / 2–3 | *chưa có* | *chưa có* |

**Nhóm đã sửa problem thế nào sau kiểm chứng:** Phỏng vấn chưa làm, nên dưới đây chỉ là các thay đổi từ phản biện khi pitch và từ research:

- Bỏ hướng "AI viết bài": Văn đã dùng AI ở bước 2. Problem chuyển trọng tâm sang **chờ duyệt** và **đăng tay từng trang**.
- Gộp #2 (ai đăng bài sai) và #3 (trùng lịch) vào cùng problem, vì cả hai đều giải được bằng một file theo dõi bài và tính năng lên lịch có sẵn.
- Problem vẫn phải chờ phỏng vấn để xác nhận giả định #2. Nếu người ngoài nhóm nói khâu soạn mới là chậm nhất, nhóm sẽ sửa lại mục 4–7.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Meta Business Suite — lên lịch bài cho Trang | https://www.facebook.com/business/help/1252240869631062 | Bước đăng: soạn trước, đặt giờ đăng, xem lịch các bài đã lên | Có sẵn, miễn phí cho người quản lý Trang | Không có bước duyệt nhiều cấp; không soạn bài | Giải được bước 4 + 6 (dán lên FB, đăng) và Opportunity C. **Không cần tự xây** phần đăng; bước duyệt phải làm ngoài công cụ |
| Planable — quy trình duyệt bài | https://planable.io/guides/content-approvals-in-planable/ | Bước duyệt + lên lịch: duyệt bắt buộc rồi tự lên lịch khi được duyệt | Duyệt bắt buộc và tự lên lịch khi duyệt | Duyệt bắt buộc cần gói Pro, nhiều cấp cần Enterprise; tốn phí | Mượn **pattern** "duyệt xong mới được lên lịch", nhưng làm bằng file theo dõi + khung giờ duyệt cố định để khỏi tốn phí trong pilot |
| Facebook Page Management History (Social Media Today, 01/2020) | https://www.socialmediatoday.com/news/facebook-adds-new-page-management-history-tab-in-page-tools/570171/ | Bước "biết ai đăng": lịch sử thao tác quản trị của Trang | Có sẵn | Bài từ 2020; tab này ghi thay đổi vai trò và cài đặt, việc đăng bài nằm ở Activity Log; cần tự kiểm giao diện hiện tại | Không dựa vào nó làm nguồn chính cho Opportunity D. Ghi người soạn và người duyệt vào file theo dõi (No AI) |

**Kết luận research:**

```text
Phần đăng và lên lịch đã có công cụ miễn phí. Phần duyệt có công cụ nhưng tốn phí.
Phần soạn bài team đã dùng AI. Không có lý do tự xây công cụ hay agent.
Hướng hợp lý: file sản phẩm chuẩn (Rule) → AI soạn nháp bằng prompt chuẩn → người sửa
→ quản lý duyệt theo lô → lên lịch bằng Meta Business Suite.
```

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text
HIỆN TẠI — 6 bước, 28 phút/bài (13' thao tác + 15' chờ), 6/6 bước thao tác tay

[1 Copy thông tin SP: 3'] → [2 Dán vào AI viết: 2'] → [3 Sửa bài: 5']
→ [4 Dán lên FB: 2'] → [5 Chờ duyệt: 15'] ← BOTTLENECK → [6 Đăng: 1']

Lặp lại >10 bài/ngày/người, trên hơn 10 trang.
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Nhân viên content | Thông tin sản phẩm (tên, giá, mô tả, ảnh) ở nhiều nơi | Thông tin đã copy | 3'/bài | Copy tay, dễ lấy nhầm giá |
| 2 | Nhân viên content + công cụ AI | Thông tin sản phẩm | Bài nháp | 2'/bài | Đã dùng AI; prompt mỗi lần tự gõ |
| 3 | Nhân viên content | Bài nháp | Bài đã sửa | 5'/bài | |
| 4 | Nhân viên content | Bài đã sửa + ảnh | Bài trên Facebook chờ duyệt | 2'/bài | Vào từng trang trong hơn 10 trang |
| 5 | Quản lý | Bài chờ duyệt | Bài được duyệt hoặc trả về | 15'/bài (chờ) | 4–5 bài/tuần lỡ khung giờ đăng |
| 6 | Nhân viên content | Bài được duyệt | Bài đã đăng | 1'/bài | Phải canh giờ; 10 lần trùng hoặc trống lịch tuần trước |

**Bottleneck chính:** Bước 5, chờ quản lý duyệt từng bài (~15'/bài). Bước này lâu hơn toàn bộ phần thao tác (13'/bài) và là nguyên nhân của 4–5 bài/tuần lỡ khung giờ. Chưa được người ngoài nhóm xác nhận (giả định #2).

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text
TƯƠNG LAI — 6 bước, ~7' thao tác/bài, 4/6 bước con người

[1 Nhập SP vào file sản phẩm chuẩn, 1 lần/SP: 1']      ← RULE (Google Sheet có cột cố định)
→ [2 Dán 1 dòng SP vào prompt chuẩn → nháp: 1']        ← AI (công cụ team đang dùng)
   Giá và tên SP KHÔNG do AI viết: chèn từ file vào template
→ [3 Nhân viên sửa nháp + đối chiếu giá với file: 4'] ← CON NGƯỜI (HITL 1)
→ [4 Quản lý duyệt theo lô, 2 khung giờ/ngày: ~1'/bài] ← CON NGƯỜI (HITL 2)
→ [5 Lên lịch trên Meta Business Suite + ghi người soạn, người duyệt vào file: 1'] ← CON NGƯỜI
→ [6 Bài tự đăng đúng giờ: 0']                        ← RULE (lên lịch có sẵn)

BOUNDARY: AI chỉ viết phần mô tả. AI không viết giá, tên, khuyến mãi; không lên lịch; không đăng.
          Bài chưa có dấu "đã duyệt" trong file thì không được lên lịch.
PHƯƠNG ÁN QUAY VỀ: nháp sai hoặc phải sửa quá nhiều → bỏ nháp, dùng template cố định theo loại SP (No AI).
                   Meta Business Suite lỗi → đăng tay như hiện tại.
```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | 6 | 6 | Số bước giữ nguyên; thay đổi nằm ở cách làm từng bước |
| Tổng thời gian | 28'/bài (13' thao tác + 15' chờ) | ~7'/bài thao tác + ~1' duyệt | Chờ duyệt chuyển thành duyệt theo lô; bài lên lịch trước nên không lỡ giờ |
| Số bước thủ công | 6/6 | 4/6 | Bước 1 làm 1 lần/SP, bước 6 tự động |
| Bottleneck chính | Chờ duyệt từng bài | Nhân viên sửa + đối chiếu giá (4') | Chấp nhận được vì là điểm kiểm soát chất lượng |
| Rủi ro mới phát sinh | — | Quản lý bỏ lỡ khung duyệt; file sản phẩm không cập nhật giá mới; AI thêm thông tin không có trong file | Xử lý bằng boundary + tiêu chí đánh giá ở mục 7 |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Nhân viên content phụ trách fanpage bán hàng (mỗi người >10 bài/ngày); quản lý duyệt bài |
| **Quy trình** | Copy thông tin SP → AI viết → sửa bài → dán lên FB → chờ quản lý duyệt → đăng; lặp lại trên hơn 10 trang |
| **Bottleneck** | Chờ quản lý duyệt từng bài, ~15'/bài, lâu hơn toàn bộ phần thao tác |
| **Impact** | 1 người: 100–150 phút/ngày thao tác tay, chưa tính chờ; 4–5 bài/tuần lỡ khung giờ; 10 lần trùng hoặc trống lịch/tuần |
| **Success Metric** (baseline → target, cách đo) | Thời gian từ lúc có sản phẩm đến lúc bài lên: 28 phút/bài → dưới 10 phút/bài. Đo bằng bấm giờ 20 bài trong 1 tuần |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | AI không tự đăng, không thay quản lý duyệt. Mọi bài phải được nhân viên sửa và quản lý duyệt trước khi lên |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

- **AI:** Metric "phút/bài từ lúc có SP đến lúc lên" không hợp với duyệt theo lô, vì bài có thể chờ vài tiếng tới khung duyệt mà vẫn đăng đúng giờ. Thứ khách và team quan tâm là bài lên đúng khung giờ. → **Đồng ý**, v1 đổi sang đo thời gian thao tác và số bài lỡ giờ.
- **AI:** Metric chỉ đo tốc độ, không đo bài sai giá; nhanh hơn mà sai giá nhiều hơn thì không đạt. → **Đồng ý**, thêm metric bài sai giá.
- **AI:** Boundary chưa nói AI có được viết giá không, trong khi sai giá là lỗi đã xảy ra 5–10 lần/tháng. → **Đồng ý**, v1 thêm "AI không viết giá, tên, khuyến mãi".
- **Nhóm (Sơn):** Baseline mới từ 1 người. → **Đồng ý**, chưa sửa được trong buổi này; ghi vào điều kiện của quyết định Not Yet.

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô: **độ mơ hồ thấp–trung bình × độ phức tạp trung bình** → Rule cho phần dữ liệu và lịch, Workflow có AI ở một bước.

Vì sao: Phần quan trọng nhất của bài (tên, giá, ảnh) là dữ liệu có cấu trúc, nên không mơ hồ. Chỉ phần mô tả cần viết linh hoạt, và nhiều cách viết đều chấp nhận được. Độ phức tạp đến từ khối lượng (hơn 10 trang, >10 bài/người/ngày) và bước duyệt, nhưng các bước đều cố định, không rẽ nhánh.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | Khung giờ duyệt cố định 2 lần/ngày; template bài theo loại SP; file theo dõi ghi người soạn, người duyệt | Giải được Opportunity A (chờ duyệt) và D (ai đăng) | Bài viết từ template đơn điệu; vẫn copy tay | **Dùng** cho duyệt và truy vết |
| **Rule** | File sản phẩm chuẩn; chèn giá, tên vào template; lên lịch bằng Meta Business Suite | Giải được Opportunity B (copy tay) và C (đăng tay, trùng lịch) | File không được cập nhật thì sai giá hàng loạt | **Dùng** cho dữ liệu và lịch |
| **Workflow** | Rule lấy dữ liệu → AI soạn phần mô tả bằng prompt chuẩn → người sửa → quản lý duyệt theo lô → lên lịch | Khi cần mô tả khác nhau cho mỗi SP, mỗi trang | AI thêm thông tin không có trong file | **Chọn** (mức tổng thể) |
| **Agent** | AI tự lấy SP mới, tự viết, tự chọn giờ, tự đăng lên các trang | Khi bước tiếp theo không đoán trước được | Bỏ qua bước duyệt; sai giá đến thẳng khách; nhiều quyền truy cập Trang | Không chọn |

**Mức chọn:** Workflow, trong đó phần lớn bước là No AI và Rule.

**Vì sao không chọn mức đơn giản hơn:** Team đã dùng AI để viết bài (bước 2), và bỏ AI thì phần viết sẽ chậm hơn hiện tại. Nhưng phần cải thiện lớn nhất (chờ duyệt 15' và đăng tay) đến từ No AI và Rule, không phải từ AI. Nếu phỏng vấn cho thấy template cố định là đủ cho người đọc fanpage, nhóm sẽ hạ xuống mức Rule.

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | Phần mô tả của bài đăng (2–4 câu + CTA) từ 1 dòng sản phẩm trong file |
| **Judgment** — con người cân nhắc, quyết định gì? | Nhân viên: nháp có đúng và hợp giọng trang không. Quản lý: bài có được đăng không, đăng giờ nào |
| **Action** — hành động cuối cùng là gì, ai làm? | Nhân viên lên lịch bài đã được duyệt trên Meta Business Suite; bài tự đăng |
| **Outcome** — đo kết quả bằng gì? | Thời gian thao tác/bài; số bài lỡ khung giờ/tuần; số bài sai giá/tháng; thời gian nhân viên sửa nháp |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | 1 dòng trong file sản phẩm chuẩn (tên, giá, đặc điểm) + guideline giọng văn của trang. File chuẩn **chưa có**, phải dựng (giả định #4) |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | Phần nhân viên sửa trong nháp; bài quản lý trả về; comment khách báo sai |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng: **Augment.** Hành vi hiện tại của Văn là dùng AI viết nháp rồi tự sửa 5'/bài, và vẫn gửi quản lý duyệt. Chưa có bằng chứng từ người ngoài nhóm; cần hỏi trong phỏng vấn (câu 4, 7 trong guide).
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào: Với bài viết, **đưa thông tin sai** (sai giá, bịa khuyến mãi) tệ hơn **bỏ sót** (thiếu một đặc điểm SP). Thông tin sai đến thẳng khách, và sai giá đã xảy ra 5–10 lần/tháng. Thiết kế xử lý: giá, tên, khuyến mãi chèn bằng Rule từ file; AI chỉ viết mô tả; nhân viên đối chiếu giá ở bước 3; quản lý duyệt ở bước 4.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Nhân viên content phụ trách fanpage bán hàng (mỗi người >10 bài/ngày); quản lý duyệt bài |
| **Quy trình** | Copy thông tin SP → AI viết → sửa bài → dán lên FB → chờ quản lý duyệt → đăng; lặp lại trên hơn 10 trang |
| **Bottleneck** | Chờ quản lý duyệt từng bài (~15'/bài) và đăng tay từng trang đúng giờ |
| **Impact** | 1 người: 100–150 phút/ngày thao tác tay; 4–5 bài/tuần lỡ khung giờ; 10 lần trùng hoặc trống lịch/tuần; 5–10 lần/tháng mất 10–15' tìm người đăng bài sai |
| **Success Metric** (baseline → target, cách đo) | (1) Thời gian thao tác: 13'/bài → ≤7'/bài; (2) bài lỡ khung giờ: 4–5/tuần → ≤1/tuần; (3) bài sai giá do quy trình mới: 0 trong pilot; (4) thời gian tìm người đăng bài sai: 10–15' → <2'. Đo bằng bấm giờ 20 bài/tuần, đếm từ file theo dõi và group chat trong 2 tuần pilot |
| **Boundary** | AI chỉ viết phần mô tả; không viết giá, tên, khuyến mãi; không lên lịch, không đăng. Bài chưa có dấu "đã duyệt" trong file thì không được lên lịch |
| **AI intervention point** | Bước 2: sau khi dữ liệu SP đã nằm trong file chuẩn, trước bước nhân viên sửa |
| **Mức chọn** | Workflow (phần lớn bước là No AI và Rule) |
| **Rủi ro & người kiểm tra** | AI thêm thông tin không có trong file → nhân viên kiểm ở bước 3. Sai giá do file chưa cập nhật → nhân viên đối chiếu giá, quản lý duyệt ở bước 4. Quản lý lỡ khung duyệt → bài không được lên lịch, nhân viên báo trong group |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Bottleneck | Chỉ chờ duyệt | Chờ duyệt + đăng tay từng trang | Gộp #3 vào problem (mục 2.3, Opportunity C) |
| Success Metric | 28 phút/bài từ lúc có SP đến lúc lên → <10' | Thời gian thao tác + số bài lỡ giờ + bài sai giá + thời gian tìm người | Phản biện của AI: duyệt theo lô làm metric "phút/bài" mất ý nghĩa; thiếu metric chất lượng |
| Boundary | AI không tự đăng, không thay quản lý duyệt | Thêm: AI không viết giá, tên, khuyến mãi; chưa duyệt thì không lên lịch | Sai giá là lỗi đã xảy ra 5–10 lần/tháng |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Không bịa thông tin | Mọi đặc điểm SP trong nháp có trong dòng file sản phẩm | Có công dụng, khuyến mãi, số liệu không có trong file |
| 2 | Không đụng vào giá và tên | Phần giá, tên SP giữ nguyên như template chèn từ file | AI viết lại, làm tròn hoặc thêm giá |
| 3 | Đủ phần bắt buộc | Có mô tả, CTA, hashtag theo guideline của trang | Thiếu CTA hoặc hashtag; sai trang |
| 4 | Sửa nhanh | Nhân viên sửa ≤2'/bài | Phải viết lại quá nửa bài |
| 5 | Đúng độ dài | 2–4 câu mô tả, không lan man | Dài quá 6 câu hoặc lặp ý |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | **Cao** | Toàn bộ bằng chứng từ 1 người trong nhóm; chưa phỏng vấn ai ngoài nhóm; giả định #2 (nghẽn ở chờ duyệt) chưa kiểm |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | Thấp | Nhân viên đã dùng AI viết bài và tự sửa; Meta Business Suite có sẵn cho người quản lý Trang |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | Trung bình | Công cụ có sẵn và miễn phí; nhưng file sản phẩm chuẩn chưa có (giả định #4), cần người cập nhật giá thường xuyên |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | Trung bình | Không tốn phí nếu không dùng Planable; chưa biết quản lý có chấp nhận duyệt theo lô không (giả định #5). Người vận hành: nhân viên content giữ file, quản lý giữ khung duyệt |

### 8.2. Kết luận

**Quyết định:** **Not Yet**

**Lý do:** Value đang ở mức Cao vì chưa có bằng chứng ngoài nhóm, và giả định quan trọng nhất (#2) chưa được kiểm. Nếu #2 sai, quy trình tương lai ở mục 4 giải sai chỗ. Phần còn lại (công cụ, chi phí, khả năng dùng) đều ổn, nên chỉ cần kiểm chứng xong là có thể pilot.

**Nếu Go — pilot nhỏ nhất:** (sẵn sàng khi điều kiện bên dưới đạt) 2 tuần, 1 trang, 1 nhân viên. Không xây gì: dựng 1 Google Sheet sản phẩm + file theo dõi, 1 prompt chuẩn, 2 khung duyệt/ngày, lên lịch bằng Meta Business Suite. Nhân viên bấm giờ và chấm nháp theo 5 tiêu chí ở mục 7.

**Nếu Not Yet — cần kiểm chứng gì trước:**

1. Phỏng vấn 2–3 người ngoài nhóm theo [cp4-interview-guide.md](../assets/cp4-interview-guide.md), điền snapshot ở mục 3.2. Đạt khi ≥2/3 người xác nhận chờ duyệt hoặc đăng tay là bước lâu nhất.
2. Văn bấm giờ 20 bài trong 1 tuần để có baseline thật cho từng bước (hiện là số ước lượng).
3. Hỏi quản lý: có chấp nhận duyệt theo lô 2 khung giờ/ngày không (giả định #5).

**Nếu No-Go — nên làm gì thay AI:** Không áp dụng. Nếu phỏng vấn cho thấy template là đủ, nhóm hạ xuống No AI + Rule: khung giờ duyệt cố định, template, file theo dõi, lên lịch có sẵn.

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

- Nếu phỏng vấn mà <2/3 người xác nhận nghẽn ở chờ duyệt hoặc đăng tay → quay về CP3, xem lại candidate #10 hoặc vẽ lại quy trình quanh khâu soạn bài.
- Nếu sau 2 tuần pilot mà bài lỡ khung giờ vẫn >3/tuần → bỏ duyệt theo lô, quay về duyệt từng bài.
- Nếu có 1 bài sai giá lên đến khách do quy trình mới → tắt bước AI, dùng template cố định (No AI).
- Nếu nhân viên sửa nháp trung bình >5'/bài → bỏ AI, dùng template cố định.

---

## 9. Hạn chế và hướng tiếp theo

- Chưa có phỏng vấn người ngoài nhóm; toàn bộ số liệu từ trải nghiệm của 1 thành viên (Văn). Đây là lý do quyết định Not Yet.
- Số phút từng bước là ước lượng; cần bấm giờ 20 bài để có baseline thật.
- Link Social Media Today từ 01/2020; giao diện Activity Log của Facebook có thể đã đổi, cần tự kiểm lại.
- Candidate #10 (phân loại inbox đầu ca phòng khám nhi) có impact lớn về an toàn cho trẻ. Đưa vào vòng sau nếu tiếp cận được lễ tân và có người trong ngành y kiểm boundary.
- Phần hỏi đáp pitch (2.1), cây OST, chấm điểm (2.3–2.4) và phản biện v0 (mục 5) có phần nháp do AI đóng vai; nhóm cần thảo luận và sửa lại theo thực tế.

## 10. Tài liệu tham khảo

- Meta Business Help Center — lên lịch bài cho Trang: https://www.facebook.com/business/help/1252240869631062
- Planable — Content approvals: https://planable.io/guides/content-approvals-in-planable/
- Social Media Today (01/2020) — Facebook Page Management History: https://www.socialmediatoday.com/news/facebook-adds-new-page-management-history-tab-in-page-tools/570171/
- Rob Fitzpatrick, *The Mom Test* — 3 luật phỏng vấn.
- Teresa Torres, *Continuous Discovery Habits* — Opportunity Solution Tree.
- Google PAIR, *People + AI Guidebook* — augment hay automate, báo nhầm hay bỏ sót.
- Tài liệu của lab: [docs/01-worksheet.md](../../docs/01-worksheet.md), [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md), [docs/03-international-frameworks.md](../../docs/03-international-frameworks.md).
