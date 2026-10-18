# BÀI THỰC HÀNH 2: TỔ CHỨC SPRINT RETROSPECTIVE CHO NỀN TẢNG RIKKAIRETECH

> 👤 **Học viên:** Đỗ Hoàng Sơn | **Mã SV:** PTIT-HCM-066
> 🏫 **Môn học:** IT206-K25-Agile-va-Scrum

---

## Nhiệm vụ 1: Chọn kỹ thuật và xếp thẻ ý kiến

Sprint này vấn đề đã khá rõ ràng qua nhật ký thực tế, thời gian buổi họp chỉ có hạn là 45 phút và cả nhóm đều muốn đi thẳng vào việc đưa ra hành động cải tiến ngay. Do đó, tôi chọn kỹ thuật 4Ls cho buổi Sprint Retrospective này.

- Kỹ thuật chọn và lý do: Chọn kỹ thuật 4Ls (Liked, Learned, Lacked, Longed For). Lý do: Kỹ thuật này giúp phân loại rõ ràng các khía cạnh từ tốt đến thiếu sót, giúp nhóm tiết kiệm thời gian tranh luận lan man và nhanh chóng định hình vấn đề để đi đến hành động trong thời lượng 45 phút.

| Thẻ | Nội dung thẻ | Xếp vào cột nào, lý do ngắn |
| --- | --- | --- |
| T1 | Review chéo giúp sửa lỗi trước khi kiểm thử. | Liked (hoặc Continue): Cách làm này hiệu quả, nên giữ. |
| T2 | Kiểm thử dồn đến ngày 9 mới bắt đầu. | Lacked: Phản ánh sự thiếu hụt quy trình kiểm thử cuốn chiếu trong Sprint. |
| T3 | Hải báo lỗi muộn khiến cả nhóm phải sửa gấp. | Đã viết lại: Chuyển thành 'Quy trình báo cáo và xử lý lỗi cần được cập nhật để thông báo sớm hơn'. Xếp vào cột Lacked vì đây là điểm thiếu sót trong phối hợp. |
| T4 | Bộ lọc giá chưa hợp nhu cầu của người mua. | Liked / Learned: Phản ánh thông tin phản hồi từ thị trường, xếp vào Learned để rút kinh nghiệm cho việc phân tích Product Backlog Item. |
| T5 | Definition of Done (DoD) chưa ghi việc kiểm thử trên điện thoại. | Lacked: Định nghĩa hoàn thành chưa chuẩn xác, thiếu hạng mục kiểm thử thiết bị thực tế. |

## Nhiệm vụ 2: Từ Data đến Improvement

Dựa vào sự việc DT-01 trong nhật ký Sprint (Ngày 9 mới bắt đầu kiểm thử chức năng đặt giữ máy, lỗi phát hiện quá muộn nên chức năng chưa Done), tôi tiến hành phân tích nguyên nhân và đưa ra hành động cải tiến theo chuẩn SMART.

| Data đã chọn | Khía cạnh | Insight (vì sao xảy ra) |
| --- | --- | --- |
| DT-01 | Quy trình | Developers đợi code xong toàn bộ tính năng rồi mới chuyển sang Tester kiểm thử một lần vào cuối Sprint, không áp dụng kiểm thử cuốn chiếu (Continuous Testing) hay viết Unit Test song song. |

## Bảng kế hoạch hành động cải tiến (Improvement Plan)

Kế hoạch chi tiết để khắc phục sự việc DT-01, đảm bảo tính đo lường được và có thời gian kiểm tra rõ ràng ngay trong Sprint tiếp theo:

| Hành động cụ thể | Người/nhóm theo dõi | Khi kiểm tra lại | Bằng chứng |
| --- | --- | --- | --- |
| Áp dụng quy tắc kiểm thử cuốn chiếu: Task code nào hoàn thành thì Developers phải gửi Tester kiểm thử ngay trong vòng 24 giờ, không chờ đến cuối Sprint. | Scrum Master Duy và đại diện Developers (Hải) | Giữa Sprint 3 (Ngày thứ 5 của Sprint) | Lịch sử cập nhật trạng thái trên bảng Jira/Trello cho thấy các PBI được kiểm thử rải đều từ ngày 2 đến ngày 8. |

## Nhiệm vụ 3: Sắp xếp và mở đầu buổi Retrospective

Để đảm bảo buổi họp 45 phút diễn ra an toàn, không lặp lại tình trạng chỉ trích cá nhân như Sprint trước, tôi sắp xếp lại trình tự các hoạt động cho hợp lý và chuẩn bị lời mở đầu mang tính xây dựng.

- Thứ tự 5 bước: H3 -> H2 -> H5 -> H1 -> H6
- Hoạt động bị loại và lý do: Loại hoạt động H4 ('Scrum Master chọn sẵn giải pháp và giao cho nhóm làm theo'). Lý do: Vi phạm nguyên tắc tự tổ chức (Self-organizing) của Scrum Team, Scrum Master không được áp đặt giải pháp mà phải để nhóm tự thảo luận và quyết định.

## Lời mở đầu buổi họp của Scrum Master Duy

Chào mọi người, cảm ơn anh chị em đã tham gia buổi Sprint Retrospective hôm nay. Sprint 2 vừa qua chúng ta đã rất nỗ lực nhưng cũng gặp một số điểm nghẽn kỹ thuật cần tháo gỡ. Hôm nay, chúng ta họp với tinh thần nhìn nhận sự việc để cải tiến quy trình chứ tuyệt đối không đổ lỗi cá nhân, ai làm sai ở đâu chúng ta cùng tìm nguyên nhân và sửa đổi để Sprint 3 chạy mượt mà hơn nhé. Bây giờ chúng ta bắt đầu vào bước đầu tiên.

---

## 📁 Danh sách tệp tin nộp bài trong Repository
- 📝 `bt2.docx`: Báo cáo tài liệu phân tích nghiệp vụ hoàn chỉnh.
