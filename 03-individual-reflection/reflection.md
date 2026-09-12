# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Lại Bá Quân
- Mã học viên: 02495
- Nhóm: Nhóm 5 thành viên (Nguyễn Trọng Minh, Lê Mạnh Cường, Lại Bá Quân, Trần Quốc Khánh, Nguyễn Trần Nhựt Nam)
- Candidate problem nhóm chọn: Vinhomes Resident Amenity Booking Bot / Script Exploit & Slot Scalping

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Brainstorm 5 problems, chọn ra 3 problems để làm card và đưa ra được một 1 problem tâm đắc để team pitch | Có thêm những problem mới, chưa trùng lặp với team |
| Pitch Problem Card | Đưa ra 1 problem tâm đắc cho anh em pitch và bổ sung thêm một problem nữa để đa dạng lựa chọn | Giúp team có thêm lựa chọn trong việc chọn candidate problem |
| Challenge bài của bạn khác | Đặt câu hỏi về tính thực tiễn, problem có xuất phát từ pain point của bản thân không hay chỉ tìm trên mạng. Giải pháp được đưa ra là bổ sung các bước booking phức tạp thêm thì đã nghĩ đến trải nghiệm người dùng chưa | làm rõ được pain point và cân nhắc kỹ đến giải pháp |
| Gom trùng / cluster | Đọc bài của các bạn và đưa ra ý kiến để gom các bài có đề tài gần tương tự | Giúp team dễ lọc problem |
| Chọn candidate problem | tra cứu thêm thông tin về problem mà anh em trong nhóm đưa ra, phản biện loại bỏ những vấn đề chưa phù hợp và chốt 1 problem duy nhất | chốt lại problem có sự đồng thuận cao trong team |
| Validation / research | Tra cứu thêm review của cư dân trên App Store và tìm hiểu các tài liệu kỹ thuật về giải pháp chống bot / rate limiting (AWS WAF, Google Play Integrity) | Cung cấp tài liệu tham khảo kỹ thuật để nhóm thấy rằng Rule/Rate limiting là lớp phòng thủ nền tảng quan trọng trước AI |
| Workflow nhóm | Thảo luận cùng nhóm về các bước trong luồng booking hiện tại và góp ý cho luồng tương lai có cơ chế phòng thủ phân tầng | Đưa ra ý kiến giữ luồng đơn giản, không làm phiền cư dân thông thường bằng quá nhiều bước xác thực phức tạp |
| Problem Statement | Đọc lại bản thảo do bạn writer soạn, rà soát lại tính thực tế và xác nhận phần Boundary (phạm vi làm / không làm) | Giúp bài toán có ranh giới rõ ràng, không bị phình to sang việc thay đổi chính sách hay thiết kế lại toàn bộ app |
| Rule / Workflow / Agent | Tham gia biểu quyết, đồng thuận với nhóm chọn mức Workflow kết hợp Rule-based thay vì chọn Agent | Tránh việc nhóm chọn Agent theo cảm tính hoặc chọn giải pháp quá phức tạp không cần thiết |
| Decision | Cùng nhóm thảo luận và thống nhất quyết định "Not Yet" để pilot log-based trước khi quyết định deploy AI | Giúp nhóm đưa ra quyết định thực tế dựa trên dữ liệu, tránh vội vàng "Go" khi chưa có server log |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Kiên quyết đặt câu hỏi về trải nghiệm người dùng thực tế và nhấn mạnh ranh giới phòng thủ: ưu tiên Rule/Rate limiting để chặn 70-80% hành vi lạm dụng rõ ràng, chỉ dùng AI để chấm điểm rủi ro cho các ca mơ hồ và tuyệt đối không để AI can thiệp trực tiếp vào việc khóa/hủy slot của cư dân.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý thêm các problem phổ biến từ bối cảnh sinh viên/công việc theo 4 lăng kính | Giúp mở rộng góc nhìn sang các vấn đề CSKH và hỗ trợ hỏi đáp | Đưa ra một số ý tưởng quá nặng kỹ thuật và không phải pain thật của bản thân (như chẩn đoán log OBS Studio khi live) | Lọc bỏ các ý kiến xa vời, chỉ giữ lại những việc bản thân thực sự làm và gặp khó khăn (tính lương team live, ghi thu chi cá nhân, thắc mắc bài tập) |
| Problem Card | Đóng vai skeptical PM phản biện điểm yếu của Card và gợi ý khung câu hỏi challenge | Chỉ ra rủi ro bài toán thu chi có thể giải quyết bằng Regex/Form thay vì cần LLM | Ước lượng thời gian và các con số metric rất cảm tính, chung chung | Tự bấm giờ và đưa số liệu thật từ thói quen ghi chép của bản thân (15 phút/ngày, giảm xuống 1 phút) |
| Workflow | Gợi ý các bước phân rã quy trình booking hiện tại và các lớp kiểm soát trong hệ thống phân tầng | Liệt kê nhanh các khái niệm kỹ thuật chuẩn (Rate limit, Nonce, Integrity, Behavioral Risk Scoring) | Đề xuất luồng quá cồng kềnh với nhiều bước challenge khiến trải nghiệm người dùng bình thường bị ảnh hưởng nặng | Cùng nhóm tinh gọn lại flow, chỉ giữ Rule chặn ở đầu, luồng bình thường đi thẳng (low-risk), chỉ ca nghi ngờ mới đưa vào tính điểm rủi ro |
| Research | Tìm kiếm các pattern/tool công nghệ chuẩn trong ngành chuyên phòng thủ bot và quản lý tài nguyên khan hiếm | Gợi ý đúng các công cụ tiêu chuẩn như AWS WAF Bot Control và Google Play Integrity API | Trả lời mang tính lý thuyết chung chung, không có link kiểm chứng và vội vã khẳng định "bot là nguyên nhân chắc chắn" | Tự tra cứu trực tiếp tài liệu chính thức của AWS và Google Developer để lấy link kiểm chứng; đồng thời hạ mức khẳng định xuống "giả thuyết cần xác minh bằng log" |
| Problem Statement | Không dùng | Không áp dụng vì tôi chỉ đọc bản thảo của nhóm và góp ý trực tiếp | Không áp dụng | Đọc trực tiếp bản thảo của bạn writer và góp ý làm chặt phần Boundary |
| Rule / Workflow / Agent | Không dùng | Không áp dụng | Không áp dụng | Cả nhóm tự dựa vào 5 câu hỏi chốt trong worksheet để thảo luận và chốt hạ chọn Workflow kết hợp Rule |
| Decision | Không dùng | Không áp dụng | Không áp dụng | Cả nhóm tự biểu quyết chọn Not Yet dựa trên thực tế chưa có log server xác minh root cause |

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
Khi lắng nghe top 3 problems của các bạn trong nhóm, tôi nhận ra bài toán cá nhân của mình tuy rất thật nhưng quy mô còn hẹp. Ngược lại, bài toán về việc bot chiếm slot tiện ích Vinhomes chạm đúng vào vấn đề nhức nhối về tính công bằng trong việc tiếp cận tài nguyên khan hiếm. Trong quá trình thảo luận ban đầu, nhóm suýt bị cuốn vào cái bẫy solution-first khi có ý kiến muốn xây dựng ngay một AI Agent thông minh để tự động truy vết và chặn bot. Tuy nhiên, qua quá trình bóc tách workflow và tra cứu tài liệu giải pháp, nhóm nhận thấy phần lớn các hành vi lạm dụng hoàn toàn có thể xử lý triệt để bằng các quy tắc kỹ thuật (Rule) như Rate limiting hay kiểm tra tính toàn vẹn của thiết bị. Dấu tay rõ nhất của tôi trong artifact cuối là việc kiên quyết bảo vệ trải nghiệm của cư dân thật và đề xuất mô hình phòng thủ phân tầng: Rule chặn trước, AI chỉ chấm điểm rủi ro cho các ca nghi ngờ. Tôi cũng nhấn mạnh ranh giới kỹ thuật rằng AI không được phép trực tiếp can thiệp vào việc khóa hay hủy slot booking của người dùng. Khi tham gia xây dựng Problem Statement, tôi thấy việc xác định Boundary là khâu khó nhất vì nhóm phải kiên quyết loại bỏ những mong muốn can thiệp quá sâu vào chính sách nội bộ của ban quản lý. Quyết định cuối cùng chọn "Not Yet" thay vì vội vàng "Go" là một trải nghiệm rất giá trị đối với tôi trong buổi lab. Nó giúp tôi hiểu rằng một kỹ sư giỏi không phải là người cố nhồi nhét AI vào mọi bài toán, mà là người biết khi nào cần dừng lại để kiểm chứng bằng dữ liệu thật. Nếu được làm lại, tôi sẽ chủ động đề xuất nhóm thực hiện phỏng vấn nhanh một vài cư dân ngay trong buổi sáng để có thêm bằng chứng thực tế củng cố cho bài toán.
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


