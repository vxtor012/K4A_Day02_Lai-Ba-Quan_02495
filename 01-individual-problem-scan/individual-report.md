# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Lại Bá Quân
- Mã học viên: 02495
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Sinh viên năm cuối Hệ thống thông tin
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
    - Theo dõi thu chi cá nhân
    - Sản xuất video karaoke cho kênh youtube cá nhân
    - Tổng hợp tài liệu, lên kế hoạch ôn tập cho môn học

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Lặp lại/tốn thời gian | Tách âm thanh bài hát bằng AI, đồng bộ lyrics theo lời bài hát và tinh chỉnh xuất thành video karaoke hoàn chỉnh rồi đăng lên youtube. Viết title và description cho video. | Bản thân (youtube creator) | 2h/video, trung bình 2-3 video/tuần. |
| 2 | AI có thể làm tốt hơn | Tổng hợp tài liệu, tìm hiểu về ngân hàng đề để xem cần ưu tiên học những phần nào, phần này cần những kiến thức nào, lên kế hoạch ôn tập cho môn học. | Bản thân (sinh viên năm cuối) | 3-4h/tuần. |
| 3 | Lặp lại/tốn thời gian/pain từ người khác | Tổng hợp lại lịch làm việc được quản lý trên gg sheets, nhận báo cáo giải ngân từ đối tác để tính lương, thưởng cho nhân sự trong team live. Làm lâu có thể nhầm lẫn các số liệu| Leader live stream | 1h/tuần |
| 4 | Lặp lại/tốn thời gian | Hàng ngày, hàng tuần phải tự ghi chép thu chi, tổng hợp thủ công bằng sheets. Hàng tháng phải tự tạo thêm sheets mới. Khi để lâu, lười ghi luôn hoặc không tiện ghi chép nên dễ quên một số mục thu chi. | Bản thân (sinh viên năm cuối) | 3p/lần ghi. |
| 5 | Pain từ người khác / Lặp lại | Sinh viên khóa học AI in Action liên tục hỏi lại các thông tin về tác vụ, lịch học, vấn đề về hệ thống VLearn, build project dù đã có các tài liệu hướng dẫn và đã được hướng dẫn trực tiếp | Nhiều học viên (50+) | Trung bình 20+ câu hỏi/ngày. |
| 6 | | | | |
| 7 | | | | |
| 8 | | | | |
| 9 | | | | |
| 10 | | | | |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: Tôi cần tìm ra 5+ problem xung quanh mình để nghĩ phương hướng giải quyết. Tôi đã tự scan và nhận ra được 3 problem này, hãy gợi ý cho tôi thêm một số problem phổ biến khác theo cấu trúc của 3 problem tôi nêu dưới đây.
- Ý dùng được: HR hỏi đáp, giải đáp thắc mắc cho nhân viên công ty (liên hệ sang với khóa học AI in Action hiện tại)
- Ý bỏ vì không phải pain thật: Đọc thông số log từ OBS Studio để chẩn đoán nguyên nhân rớt mạng/tụt frame (do encoder hay mạng local) khi đang live.

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Tổng hợp lại lịch làm việc được quản lý trên gg sheets, nhận báo cáo giải ngân từ đối tác để tính lương, thưởng cho nhân sự trong team live. Làm lâu có thể nhầm lẫn các số liệu | - Workflow lặp lại hàng tuần rất rõ ràng, có dữ liệu đầu vào cụ thể.<br>- Điểm nghẽn ở khâu đối chiếu và tính toán thủ công rất tốn thời gian và dễ nhầm lẫn số liệu.<br>- Rất tốt để phân định rõ ràng giữa Rule/Script automation thuần và AI (chứng minh khi nào nên và không nên dùng AI). | Format file báo cáo giải ngân của đối tác có ổn định cấu trúc hay thay đổi liên tục theo từng đợt/đối tác? |
| 2 | Hàng ngày, hàng tuần phải tự ghi chép thu chi, tổng hợp thủ công bằng sheets. Hàng tháng phải tự tạo thêm sheets mới. Khi để lâu, lười ghi luôn hoặc không tiện ghi chép nên dễ quên một số mục thu chi. | - Vấn đề diễn ra hàng ngày, tần suất cao (5-10 lần/ngày), bản thân trải nghiệm sâu sắc.<br>- Nút thắt lớn nhất là ma sát nhập liệu (mở sheet, gõ từng cột) dẫn đến lười và quên.<br>- AI (LLM / NLP) cực kỳ phù hợp để hiểu ngôn ngữ tự nhiên ngắn gọn ("rau 20k", "xăng 50k") và tự động phân loại danh mục. | Khả năng phân loại danh mục chi tiêu có chính xác 100% với các câu chat viết tắt, nhập nhằng hoặc chứa nhiều khoản chi cùng lúc không? |
| 3 | Sinh viên khóa học AI in Action liên tục hỏi lại các thông tin về tác vụ, lịch học, vấn đề về hệ thống VLearn, build project dù đã có các tài liệu hướng dẫn và đã được hướng dẫn trực tiếp | - Impact rộng trong môi trường thực tế (50+ học viên và đội ngũ trợ giảng/mentor).<br>- Tần suất cao (20+ câu hỏi/ngày), phần lớn là các thắc mắc FAQ đã có trong tài liệu.<br>- RAG/AI Assistant có thể giải tỏa ngay lập tức tải công việc cho trợ giảng và giảm thời gian chờ của học viên. | Chất lượng xử lý đối với các lỗi kỹ thuật cá nhân hóa (lỗi môi trường máy học viên) và nguy cơ AI trả lời sai (hallucination) nếu tài liệu chưa kịp cập nhật. |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Tự động hóa đối soát & tính lương thưởng team livestream

```text
Problem 1 câu:
Leader livestream hàng tuần mất hơn 60 phút đối chiếu thủ công giữa lịch ca live trên Google Sheets và file báo cáo giải ngân của đối tác để tính lương, thưởng KPI, dễ nhầm lẫn số liệu và làm chậm trễ chi trả cho nhân sự.

Actor:
Leader livestream (người chịu trách nhiệm quản lý ca live, đối soát doanh thu và thanh toán quyền lợi cho team livestream).

Thời điểm / bối cảnh:
Mỗi tuần hoặc mỗi chu kỳ quyết toán lương/thưởng cho nhân sự livestream (idol, trợ live, kỹ thuật) khi đối tác gửi file giải ngân.

Current workflow 3-7 bước:
1. Tải dữ liệu lịch các ca live thực tế trong tuần từ Google Sheets của team.
2. Tải file sao kê/báo cáo giải ngân doanh thu từ đối tác (file Excel/CSV).
3. Mở song song 2 bảng, dò thủ công mã ca live, ngày giờ và ID nhân sự để khớp dữ liệu.
4. Áp công thức tính lương cứng, % hoa hồng, thưởng vượt KPI và các khoản phạt/phụ cấp cho từng nhân sự.
5. Rà soát lại các dòng dữ liệu bị lệch hoặc thiếu thông tin.
6. Tạo sheet bảng tính lương mới, xuất file tổng hợp và gửi nhân sự đối soát.

Bottleneck:
Bước 3 & 4 (Dò khớp mã ca live với file giải ngân và tính toán thưởng/phạt thủ công) — mất ~45 phút/lần, dễ nhầm dòng, sót ca hoặc sai lệch công thức tính khi số lượng ca live tăng.

Impact:
Mất 1h/tuần cho 1 leader; rủi ro nhầm lẫn tiền bạc dẫn đến khiếu nại, giảm uy tín và mất thời gian đối soát lại; khó mở rộng quy mô khi số lượng nhân sự/ca live tăng gấp đôi.

Success metric:
- Thời gian xử lý bảng tính giảm từ 60 phút xuống dưới 5 phút.
- Tỷ lệ sai sót/nhầm lẫn số liệu trong bảng lương giảm từ ~5% (do thao tác tay) xuống 0%.

Non-AI alternative:
Viết Script tự động hóa chuẩn (Python script với thư viện Pandas hoặc Google Apps Script trên Google Sheets) nhận 2 file đầu vào, tự động merge theo Key (mã ca live/ID nhân sự) và áp logic tính toán có sẵn để sinh ra bảng tính mới. Đây là giải pháp Rule-based tối ưu, chính xác 100% và tiết kiệm chi phí.

AI hypothesis:
Bài toán tính lương đòi hỏi độ chính xác tuyệt đối (zero hallucination). Toàn bộ khâu tính toán và ghép nối dữ liệu phải do Script/Rule xử lý. AI chỉ có thể đóng vai trò phụ trợ nếu format báo cáo của đối tác gửi về dưới dạng phi cấu trúc (ảnh chụp màn hình sao kê, file PDF không chuẩn cột) cần OCR/LLM để chuẩn hóa về bảng dữ liệu có cấu trúc.

Quick gut:
[ ] No AI / process fix
[x] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII):

```text
CURRENT STATE — 60 phút

[1 Tải lịch live từ Sheets: 3'] 
→ [2 Tải file giải ngân đối tác: 2'] 
→ [3 Dò đối chiếu chéo ca live & doanh thu: 25']  <-- bottleneck
→ [4 Tính lương, KPI, phạt thủ công: 20']  <-- bottleneck
→ [5 Rà soát lệch số liệu: 7'] 
→ [6 Tạo bảng lương mới & gửi đối soát: 3']

FUTURE STATE — 7 phút

[1 Import file giải ngân & lịch ca live: 1'] 
→ [2 Script Automation tự động merge key & tính toán theo Rule chuẩn: 1'] 
→ [3 Leader review bảng lương tự động & xử lý ngoại lệ (human review): 4']  <-- human boundary
→ [4 Bấm xuất bảng tính mới & gửi đối soát nhân sự: 1']

Fallback: Nếu file đối tác bị đổi cấu trúc cột khiến script báo lỗi → Leader dùng template mapping thủ công lại tên cột hoặc quay về quy trình đối chiếu bán tự động trên Sheets.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Chatbot AI ghi chép và tra cứu thu chi cá nhân tức thì

```text
Problem 1 câu:
Bản thân sinh viên mất trung bình 3 phút mỗi lần nhập liệu chi tiêu thủ công vào Google Sheets, thao tác mở sheet cồng kềnh dẫn đến lười ghi chép và bỏ sót 30-40% các khoản chi nhỏ lẻ hàng ngày.

Actor:
Bản thân (sinh viên năm cuối cần theo dõi thu chi cá nhân chặt chẽ).

Thời điểm / bối cảnh:
Diễn ra hàng ngày, ngay sau khi phát sinh các giao dịch mua sắm, ăn uống, đi lại ngoài đường hoặc thanh toán chuyển khoản.

Current workflow 3-7 bước:
1. Phát sinh giao dịch chi tiêu thực tế ngoài đời (VD: mua đồ ăn, đổ xăng).
2. Tự nhớ trong đầu hoặc gõ tạm vào ứng dụng ghi chú điện thoại.
3. Cuối ngày hoặc cuối tuần mở ứng dụng Google Sheets trên điện thoại/máy tính.
4. Hồi tưởng lại các khoản đã chi trong ngày/tuần.
5. Chọn đúng sheet tháng, gõ ngày tháng, chọn danh mục chi tiêu (Ăn uống, Đi lại, Học tập...), gõ số tiền và nội dung ghi chú.
6. Kéo công thức tính tổng và đối chiếu lại số dư tài khoản.

Bottleneck:
Bước 3, 4 & 5 (Mở Google Sheets, nhớ lại khoản chi và nhập liệu thủ công từng ô) — ma sát thao tác quá lớn khi đang di chuyển ngoài đường hoặc đang bận, dẫn đến tâm lý trì hoãn và quên hẳn việc ghi chép.

Impact:
Mất 15-20 phút/ngày nếu ghi đủ; thường xuyên bỏ sót dẫn đến cuối tháng lệch sổ một vài trăm ngàn đồng không rõ nguyên nhân; mất thói quen kỷ luật tài chính cá nhân.

Success metric:
- Thời gian ghi nhận 1 khoản chi giảm từ 3 phút (mở sheet, gõ) xuống dưới 30 giây (chỉ cần nhắn 1 câu chat ngắn gọn).
- Tỷ lệ giao dịch phát sinh được ghi chép đầy đủ tăng từ ~60% lên >95% (không còn bỏ sót các khoản chi lặt vặt).

Non-AI alternative:
Tạo Google Form tạo shortcut trên màn hình điện thoại hoặc dùng app quản lý chi tiêu có sẵn (Money Lover, Spendee). Nhược điểm: Vẫn phải bấm nhiều bước (chọn ví, chọn dropdown danh mục, gõ số), không tự do theo dõi trên Google Sheets cá nhân và không thể chat hỏi đáp linh hoạt.

AI hypothesis:
Sử dụng LLM đóng vai trò NLP Parser tích hợp vào Chatbot (Telegram/Zalo) + Function Calling. Người dùng chỉ cần gõ 1 câu chat tự nhiên ngắn gọn (VD: "mua rau 20k", "đổ xăng 50k", "ăn lẩu với bạn 150k"), AI sẽ tự động trích xuất: Số tiền (Amount), Danh mục (Category), Nội dung (Note), Thời gian (Timestamp) và gọi API ghi thẳng 1 dòng vào Google Sheets. Ngoài ra, AI hỗ trợ hỏi đáp tổng hợp nhanh ("Hôm nay đã tiêu bao nhiêu?", "Tháng này ăn uống hết bao nhiêu?").

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 15p/ngày (cho ~4 lần phát sinh chi tiêu)

[1 Chi tiêu thực tế: 0'] 
→ [2 Ghi nhớ tạm/note nháp: 1'] 
→ [3 Cuối ngày mở Google Sheets: 2'] 
→ [4 Hồi tưởng & nhớ lại khoản chi: 3']  <-- bottleneck
→ [5 Gõ ngày, chọn danh mục, điền tiền & note thủ công: 5']  <-- bottleneck
→ [6 Tính tổng & kiểm tra số dư: 1']

FUTURE STATE — 1p/ngày (cho ~4 lần phát sinh chi tiêu)

[1 Chi tiêu thực tế: 0'] 
→ [2 Nhắn câu chat tự nhiên qua Telegram/Zalo bot (VD: "mua rau 20k"): 5s'] 
→ [3 AI bóc tách số tiền, tự động phân loại danh mục & ghi vào Sheets: 2s'] 
→ [4 Bot phản hồi xác nhận ngắn kèm nút "Sửa/Hủy" nếu sai (human review): 3s']  <-- human boundary

Fallback: Nếu AI không nhận diện được số tiền hoặc không chắc chắn về danh mục → Bot phản hồi hỏi lại: "Mình chưa rõ số tiền/danh mục, bạn bấm chọn nhanh danh mục bên dưới nhé" kèm danh sách nút bấm gợi ý.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Trợ lý AI giải đáp thắc mắc tài liệu và bài tập khóa học AI

```text
Problem 1 câu:
Hơn 50 học viên khóa học AI in Action liên tục hỏi lại các thông tin về quy trình nộp lab, lỗi VLearn và bài tập khiến đội ngũ trợ giảng (TA) mất 2-3 giờ/ngày để tra cứu và trả lời thủ công các câu hỏi lặp lại, trong khi học viên phải chờ đợi phản hồi.

Actor:
Học viên khóa học AI in Action (50+ người) và Đội ngũ Trợ giảng (TA) / Giảng viên hỗ trợ khóa học.

Thời điểm / bối cảnh:
Xuyên suốt khóa học, đặc biệt cao điểm vào các khung giờ trước hạn nộp bài lab, các buổi học trực tiếp và khi triển khai bài tập trên hệ thống VLearn/GitHub.

Current workflow 3-7 bước:
1. Học viên gặp lỗi (lỗi VLearn, cấu hình môi trường, quy định format nộp bài...) hoặc thắc mắc lịch học.
2. Học viên tự tìm kiếm trong tài liệu hướng dẫn (file markdown, docs, slides) hoặc lướt kênh chat Discord/Zalo.
3. Không tìm thấy thông tin ngay hoặc ngại đọc tài liệu dài, học viên tag hoặc nhắn tin hỏi TA trên nhóm chung.
4. TA đọc câu hỏi, xác định vấn đề cần giải đáp.
5. TA lục lại tài liệu, copy link hoặc gõ lại câu trả lời giải thích cho học viên.
6. Học viên đọc câu trả lời và làm theo hướng dẫn.

Bottleneck:
Bước 2 & 5 (Học viên tìm kiếm tài liệu rời rạc mất thời gian; TA phải đọc và soạn lại câu trả lời cho cùng các câu hỏi lặp đi lặp lại 20+ lần/ngày) — tốn 5-10 phút/câu hỏi cho TA và học viên phải chờ đợi từ 15-60 phút.

Impact:
TA mất 2-3 giờ mỗi ngày chỉ để trả lời FAQ lặp lại, giảm thời gian hỗ trợ chuyên sâu các ca khó; học viên bị gián đoạn tiến độ học tập và nộp bài muộn.

Success metric:
- Tỷ lệ câu hỏi thắc mắc phổ biến (FAQ, quy định nộp bài, lỗi hệ thống cơ bản) được giải đáp tự động đạt >= 80%.
- Thời gian chờ câu trả lời của học viên giảm từ trung bình 30 phút xuống dưới 10 giây.
- Thời gian TA phải trực trả lời câu hỏi lặp lại giảm từ 2-3 giờ/ngày xuống dưới 30 phút/ngày.

Non-AI alternative:
Tạo trang FAQ Notion ghim trên Discord, tạo checklist nộp bài, viết bot Slash command cứng (VD: `/faq-vlearn`, `/deadline`). Nhược điểm: Học viên diễn đạt câu hỏi rất đa dạng bằng tiếng Việt ("vlearn bị văng", "không commit được git", "file nộp để ở đâu"), hệ thống tìm kiếm từ khóa cứng không hiểu ngữ cảnh câu hỏi nên học viên vẫn chọn hỏi người thật.

AI hypothesis:
Xây dựng Trợ lý AI (RAG - Retrieval-Augmented Generation) nạp toàn bộ dữ liệu tài liệu khóa học (worksheets, slides, README, quy chế nộp bài, hướng dẫn lỗi VLearn). Khi học viên hỏi bằng ngôn ngữ tự nhiên, AI tự động tìm kiếm đoạn văn bản chuẩn liên quan nhất, tổng hợp câu trả lời súc tích kèm link trích dẫn chính xác. Nếu câu hỏi vượt ngoài dữ liệu hoặc độ tin cậy thấp, hệ thống tự động gắn tag chuyển tiếp cho TA người thật hỗ trợ.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 40 phút (từ lúc hỏi đến khi có giải đáp)

[1 Học viên gặp lỗi/thắc mắc: 0'] 
→ [2 Tự tìm trong docs/chat: 10'] 
→ [3 Nhắn tin hỏi TA lên nhóm: 2'] 
→ [4 Chờ TA online & đọc tin nhắn: 20']  <-- bottleneck
→ [5 TA tìm lại tài liệu & soạn câu trả lời: 5']  <-- bottleneck
→ [6 Học viên nhận câu trả lời & xử lý: 3']

FUTURE STATE — 1 phút

[1 Học viên đặt câu hỏi tự nhiên trên kênh hỏi đáp: 10s'] 
→ [2 Trợ lý AI tra cứu vector database tài liệu khóa học (RAG): 5s'] 
→ [3 AI trả lời ngay lập tức kèm trích dẫn nguồn tài liệu chuẩn: 5s'] 
→ [4 Học viên đọc & bấm reaction đánh giá (Đã giải quyết / Cần TA hỗ trợ) (human review): 40s']  <-- human boundary

Fallback: Nếu câu hỏi ngoài phạm vi tài liệu hoặc câu trả lời không giải quyết được (học viên bấm "Cần TA") → Bot tự động tag TA trực kèm tóm tắt ngữ cảnh câu hỏi để TA trả lời trực tiếp.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #2 — Chatbot AI ghi chép và tra cứu thu chi cá nhân tức thì
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
- Workflow: Thay thế toàn bộ quy trình mở Google Sheets nhập liệu thủ công nhiều bước bằng một thao tác duy nhất là gửi câu chat tự nhiên (VD: "mua rau 20k") qua Telegram/Zalo, AI tự động bóc tách và ghi thẳng vào Sheets.
- Số đo: Giảm thời gian ghi chép từ 3 phút/lần xuống dưới 5 giây/lần; tăng tỷ lệ ghi nhận khoản chi từ 60% lên >95%.
- Impact: Triệt tiêu hoàn toàn rào cản lười ghi chép, giúp cá nhân duy trì kỷ luật tài chính và loại bỏ tình trạng lệch sổ do quên khoản chi vặt.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Liệu bài toán này có thực sự cần đến LLM không, hay chỉ cần dùng Regex / Form mẫu cố định là đủ; chi phí gọi API LLM cho từng câu chat chi tiêu vặt có gây lãng phí không?
2. Khi người dùng nhắn các câu phức tạp chứa nhiều khoản chi hoặc ngôn ngữ địa phương/viết tắt tối nghĩa (VD: "ăn sáng 35k với mua ly cafe 25k, bạn gửi lại 10k"), làm thế nào để đảm bảo AI phân loại đúng 100% mà không ghi sai lệch số dư trên Sheets?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: Nếu chỉ parse số tiền và tên món thì Regex/Rule đơn giản cũng làm được một phần mà không tốn chi phí API; rủi ro ghi sai số tiền vào bảng tính cá nhân có thể gây mất niềm tin của người dùng.
- Tôi sửa gì: 
  + Làm rõ ranh giới AI: Regex chỉ xử lý được cú pháp cứng, còn AI giải quyết bài toán hiểu ngôn ngữ tự nhiên đa dạng ("vừa đổ đầy bình xăng hết 85 nghìn", "bạn trả lại tiền lẩu 120k") và tự động phân loại danh mục (semantic classification) vào đúng cột Sheets mà không bắt người dùng phải nhớ danh mục.
  + Bổ sung cơ chế Human Boundary: Sau khi AI phân tích và ghi tạm, bot gửi phản hồi xác nhận kèm nút bấm "Sửa / Hủy" trong 1 chạm để người dùng kiểm soát 100% tính chính xác.
  + Thêm tính năng hỏi đáp thông minh (truy vấn tổng hợp số liệu thu chi theo yêu cầu) mà Regex/Form thông thường không thể làm được.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
