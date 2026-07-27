| # | Vấn đề quan sát                                                                        | Actor                    | Dấu hiệu thật                                                         |
| - | -------------------------------------------------------------------------------------- | ------------------------ | --------------------------------------------------------------------- |
 1 | Mỗi lần làm đồ án phải cài lại môi trường (Java, Python, Node, SQL Server...) rất lâu. | Sinh viên CNTT           | Mỗi project mới mất 30–90 phút cài đặt, dễ lỗi version.               |
| 2 | Khó theo dõi deadline của nhiều môn học.                                               | Sinh viên                | Thường phải mở nhiều nhóm Messenger, LMS, Email mới biết deadline.    |
| 3 | Tìm tài liệu học nhưng bị phân tán.                                                    | Sinh viên                | Một chủ đề phải tìm YouTube, GitHub, Docs, ChatGPT, Google nhiều nơi. |
| 4 | Đọc log lỗi rất mất thời gian.                                                         | Lập trình viên/sinh viên | Có bug phải đọc hàng trăm dòng log mới xác định nguyên nhân.          |
| 5 | Đặt lịch họp nhóm rất khó.                                                             | Nhóm sinh viên           | Mỗi lần hẹn họp phải nhắn tin nhiều lượt vì lịch mỗi người khác nhau. |
| 6 | Mất nhiều thời gian viết báo cáo sau khi code xong.                                    | Sinh viên                | Code mất 2 giờ nhưng viết báo cáo thêm 1–2 giờ.                       |
| 7 | Khó nhớ kiến thức đã học.                                                              | Sinh viên                | Đã học Spring/Flutter nhưng vài tháng sau phải học lại từ đầu.        |

## Top 3 vấn đề : 
1. Tài liệu học bị phân tán, khó tìm kiếm.
2. Đọc log lỗi mất nhiều thời gian.
3. Mất nhiều thời gian viết báo cáo sau khi code xong.

## Problem Card 1:
# Problem :
  Sinh viên gặp khó khăn trong việc tìm kiếm tài liệu học tập vì các tài liệu bị phân tán trên nhiều nền tảng khác nhau như YouTube, GitHub, Docs, ChatGPT, Google. Điều này dẫn đến việc mất nhiều thời gian và công sức để tìm kiếm thông tin cần thiết cho việc học tập và làm đồ án.

# Actor :
  Sinh viên 

# Current Workflow :
1. Muốn học chủ đề mới
2. Google, YouTube, GitHub, Docs, ChatGPT
3. Tổng hợp lại
4. Lọc những tài liệu hữu ích
5. Bắt đầu học

# Bottleneck
1. Nguồn học quá nhiều.
2. Nội dung trùng lặp.
3. Version khác nhau.
4. Không biết tài liệu nào đáng tin.
5. Mất thời gian chuyển đổi giữa nhiều website,nền tảng.

# Impact
1. Mỗi chủ đề mất khoảng 30–60 phút chỉ để tìm tài liệu.
2. Người mới dễ học sai phiên bản.
3. Kiến thức bị rời rạc.
4. Mất nhiều thời gian để lọc ra các tài liệu hữu ích.

# Success Metric
1. Thời gian tìm tài liệu thật nhanh.
2. Chỉ cần một nơi để bắt đầu học.
3. Ít phải mở nhiều tab.
4. Tài liệu phù hợp ,chính xác, đáng tin cậy.

# Non-AI Alternative
1. Bookmark.
2. Notion.
3. Danh sách Roadmap.
4. Playlist YouTube,Google , GitHub.
5. Nhóm học tập.

# AI Hypothesis

AI sẽ:

1. Hiểu mục tiêu học.
2. Xác định trình độ người học.
3. Gom tài liệu.
4. Loại bỏ tài liệu cũ.
5. Sắp xếp thứ tự học.
6. Sinh kế hoạch học tập.
7. Tạo bài tập, quiz, flashcard.
8. Đề xuất tài liệu học tiếp theo.


---

## Quick Gut

- [ ] No AI
- [ ] Rule
- [x] Workflow
- [ ] Agent
- [ ] Chưa biết

---

# Draft Current Workflow

```text
CURRENT STATE 

[Xác định chủ đề: 2']
        ↓
[Google Search: 15']
        ↓
[Mở nhiều website: 15']
        ↓
[Đọc và đánh giá tài liệu: 40']  
        ↓
[Chọn tài liệu phù hợp: 15']
        ↓
[Bắt đầu học]
```

---

# Draft Future Workflow

```text
FUTURE STATE 

[Nhập chủ đề cần học]
        ↓
[AI phân tích mục tiêu]
        ↓
[AI tổng hợp tài liệu mới nhất]
        ↓
[AI đề xuất lộ trình học]
        ↓
[Sinh viên xem lại và chọn tài liệu]
        ↓
[Bắt đầu học]

```



# Problem Card 2

## Problem 

Sinh viên thường bỏ sót hoặc nộp trễ bài vì phải theo dõi deadline của nhiều môn học trên nhiều nền tảng khác nhau như LMS, Email và Messenger, khiến việc quản lý thời gian trở nên khó khăn.

---

## Actor

Sinh viên đại học đang học nhiều môn trong một học kỳ.

---

## Thời điểm / Bối cảnh

Trong suốt học kỳ, đặc biệt vào các tuần có nhiều bài tập lớn, báo cáo hoặc đồ án, sinh viên phải thường xuyên kiểm tra thông báo từ nhiều nguồn để cập nhật deadline.

---

## Current Workflow

1. Giảng viên đăng thông báo trên LMS hoặc Email.
2. Lớp trao đổi thêm trong nhóm Messenger hoặc Zalo.
3. Sinh viên tự đọc thông báo.
4. Ghi deadline vào sổ tay hoặc ứng dụng ghi chú (nếu nhớ).
5. Khi cần làm bài mới kiểm tra lại deadline.
6. Hoàn thành và nộp bài.

---

## Bottleneck

Bước mất nhiều thời gian và dễ xảy ra sai sót nhất là **kiểm tra và tổng hợp deadline từ nhiều nguồn**.

Thông báo thường được gửi ở nhiều nơi khác nhau, đôi khi có thay đổi hoặc cập nhật mới. Nếu không kiểm tra thường xuyên, sinh viên rất dễ bỏ sót hoặc nhớ nhầm thời gian nộp bài.

---

## Impact

- Phải mở nhiều ứng dụng mỗi ngày để kiểm tra thông báo.
- Dễ bỏ sót deadline hoặc nộp bài trễ.
- Mất thời gian tìm lại thông báo cũ.
- Khó sắp xếp kế hoạch học tập khi có nhiều môn cùng lúc.

---

## Success Metric

- Giảm thời gian kiểm tra deadline xuống dưới **5 phút/ngày**.
- Toàn bộ deadline được hiển thị trên một giao diện duy nhất.
- Không bỏ sót hoặc nộp trễ bài do quên deadline.
- Có thông báo nhắc trước thời hạn nộp bài.

---

## Non-AI Alternative

- Ghi deadline vào Google Calendar.
- Sử dụng Notion hoặc Microsoft To Do.
- Ghi chú bằng sổ tay.
- Đánh dấu thông báo quan trọng trong Email hoặc Messenger.

Các cách này giúp quản lý công việc tốt hơn nhưng vẫn yêu cầu sinh viên tự cập nhật mỗi khi có thông báo mới.

---

## AI Hypothesis

AI có thể:

- Tự động đọc thông báo từ LMS, Email hoặc Messenger.
- Trích xuất ngày nộp bài và thời gian quan trọng.
- Đồng bộ các deadline vào một lịch chung.
- Gửi nhắc nhở dựa trên mức độ ưu tiên và thời gian còn lại.
- Gợi ý kế hoạch học tập phù hợp khi có nhiều deadline gần nhau.

Sinh viên vẫn là người quyết định lịch học và xác nhận các deadline trước khi thực hiện.



# Draft Current Workflow

```text
CURRENT STATE — Khoảng 30 phút/ngày

[Kiểm tra LMS]
        ↓
[Kiểm tra Email]
        ↓
[Đọc Messenger/Zalo]
        ↓
[Tự tổng hợp deadline]  <-- Bottleneck
        ↓
[Ghi vào ghi chú hoặc Calendar]
        ↓
[Làm và nộp bài]
```

---

# Draft Future Workflow

```text
FUTURE STATE — Khoảng 5 phút/ngày

[AI đọc thông báo]
        ↓
[Tự động trích xuất deadline]
        ↓
[Đồng bộ vào Calendar]
        ↓
[Nhắc nhở trước thời hạn]
        ↓
[Sinh viên kiểm tra và xác nhận]
        ↓
[Làm và nộp bài]

Fallback:
Nếu AI không nhận diện được deadline hoặc thông báo bị thiếu, sinh viên vẫn có thể kiểm tra trực tiếp trên LMS hoặc Email.
```


# Problem Card #3

## Problem 

Sinh viên Công nghệ thông tin thường mất nhiều thời gian để đọc và phân tích log lỗi khi lập trình vì log quá dài, chứa nhiều thông tin không liên quan và khó xác định nguyên nhân thực sự của lỗi.

---

## Actor

Sinh viên Công nghệ thông tin hoặc lập trình viên mới trong quá trình học và phát triển phần mềm.

---

## Thời điểm / Bối cảnh

Khi làm bài tập, đồ án hoặc project cá nhân, nếu chương trình xảy ra lỗi, sinh viên phải đọc log để tìm nguyên nhân trước khi có thể sửa lỗi.

---

## Current Workflow

1. Chạy chương trình.
2. Chương trình báo lỗi hoặc bị crash.
3. Mở Console hoặc file log.
4. Đọc toàn bộ thông báo lỗi và Stack Trace.
5. Tìm dòng gây lỗi.
6. Tra cứu lỗi trên Google, Stack Overflow hoặc tài liệu.
7. Chỉnh sửa code và chạy lại chương trình.

---

## Bottleneck

Bước mất nhiều thời gian nhất là **đọc và phân tích log lỗi**.

Stack Trace thường rất dài và chứa nhiều thông tin kỹ thuật. Người mới học thường không biết đâu là nguyên nhân chính, phải đọc nhiều lần hoặc tìm kiếm từng dòng lỗi trên Internet mới hiểu được vấn đề.

---

## Impact

- Có những lỗi mất từ **20–40 phút** chỉ để xác định nguyên nhân.
- Người mới dễ hiểu sai thông báo lỗi.
- Mất nhiều thời gian chuyển đổi giữa IDE, Google và Stack Overflow.
- Quá trình sửa lỗi bị gián đoạn và ảnh hưởng đến tiến độ làm bài.

---

## Success Metric

- Giảm thời gian xác định nguyên nhân lỗi xuống dưới **5 phút**.
- Xác định đúng dòng code gây lỗi ngay từ lần phân tích đầu tiên.
- Giảm số lần phải tìm kiếm lỗi trên Google.
- Tăng tốc độ sửa lỗi và hoàn thành bài tập.

---

## Non-AI Alternative

- Đọc tài liệu chính thức của ngôn ngữ hoặc framework.
- Sử dụng Debugger trong IDE.
- Tìm kiếm lỗi trên Google hoặc Stack Overflow.
- Hỏi bạn bè hoặc giảng viên.
- Thêm log để theo dõi chương trình.

Các cách trên giúp tìm được nguyên nhân lỗi nhưng vẫn phụ thuộc nhiều vào kinh nghiệm của người lập trình và thường mất khá nhiều thời gian.

---

## AI Hypothesis

AI có thể:

- Phân tích Stack Trace và log lỗi.
- Xác định dòng log quan trọng nhất.
- Giải thích lỗi bằng ngôn ngữ dễ hiểu.
- Đề xuất nguyên nhân có khả năng cao nhất.
- Gợi ý hướng sửa và ví dụ minh họa.
- Đưa ra liên kết đến tài liệu chính thức nếu cần.

Người lập trình vẫn là người kiểm tra lại nguyên nhân và quyết định cách sửa trước khi thay đổi mã nguồn.

---

## Quick Gut

- [ ] No AI
- [ ] Rule
- [x] Workflow
- [ ] Agent
- [ ] Chưa biết



---

# Draft Current Workflow

```text
CURRENT STATE — Khoảng 30 phút

[Chạy chương trình]
        ↓
[Chương trình báo lỗi]
        ↓
[Mở Console/Log]
        ↓
[Đọc và phân tích Stack Trace: 20']  
        ↓
[Tìm kiếm trên Google]
        ↓
[Sửa code]
        ↓
[Chạy lại chương trình]
```

---

# Draft Future Workflow

```text
FUTURE STATE — Khoảng 8 phút

[Chạy chương trình]
        ↓
[AI phân tích log lỗi]
        ↓
[AI giải thích nguyên nhân]
        ↓
[AI gợi ý hướng sửa]
        ↓
[Lập trình viên kiểm tra]
        ↓
[Sửa code]
        ↓
[Chạy lại chương trình]

Fallback:
Nếu AI phân tích chưa chính xác hoặc không xác định được nguyên nhân, lập trình viên sẽ sử dụng Debugger và tra cứu tài liệu chính thức để kiểm tra lại.
```

# Card tôi muốn pitch nhất

**Problem:** Tài liệu học bị phân tán, khó tìm kiếm.

## Vì sao chọn

- Đây là vấn đề mình gặp trong suốt quá trình học.
- AI phù hợp để hỗ trợ tổng hợp và gợi ý tài liệu, nhưng vẫn cần người học tự quyết định.

---