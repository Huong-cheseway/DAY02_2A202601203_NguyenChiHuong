# Group Report — Day 02

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm |
|-----|-----------|-------------|--------------------|
| 1   | Nguyễn Chí Hướng | 2A202601203 |         Viết markdown,đề xuất candidate,phân tích candidate           |
| 2   | Nguyễn Tiến Đạt        | 2A202601387 |    đề xuất candidate,phân tích candidate                |
| 3   | Ngô Tuấn Hưng      | 2A202601409 |        đề xuất candidate,phân tích candidate            |
| 4   | Trần Xuân Lộc    | 2A202601671 |         đề xuất candidate,phân tích candidate           |
| 5   | Lại Duy Đông      | 2A202601913 |     Thuyết trình,đề xuất candidate,phân tích candidate               |


|  # | Người đưa ra  | Candidate problem                                                                            | Người gặp vấn đề                         | Điểm nghẽn                                                                                                                             | Cảm nhận nhanh                                                                                                   |
| -: | ------------- | -------------------------------------------------------------------------------------------- | ---------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
|  1 | Nguyễn Tiến Đạt      | Trích xuất ý chính từ tài liệu PDF dài                                                       | Sinh viên, nghiên cứu sinh               | Đọc lướt tìm ý bằng mắt và copy-paste tốn nhiều thời gian                                                                              | Tiết kiệm 70% thời gian; hợp dùng AI Workflow                                                                    |
|  2 | Nguyễn Tiến Đạt      | Sàng lọc CV ứng viên vòng đầu (Screening)                                                    | Nhân viên Tuyển dụng (HR)                | Mở từng file CV, đọc dò mắt tìm kỹ năng theo JD                                                                                        | Tiết kiệm hàng chục giờ việc chân tay; hợp AI Workflow                                                           |
|  3 | Nguyễn Tiến Đạt      | Gỡ băng video & viết lại Content đa nền tảng                                                 | Content Creator, Marketing               | Nghe, gỡ băng thủ công (transcript) video dài                                                                                          | Rút từ 4 tiếng xuống 30 phút/video; hợp AI Workflow                                                              |
|  4 | Ngô Tuấn Hưng | Viết tài liệu đặc tả luồng module để cải tiến (System Logic Mapping)                         | Developer / System Architect / Tech Lead | Đọc code, trace luồng thủ công và vẽ sơ đồ luồng                                                                                       | AI vẽ Mermaid + viết đặc tả ban đầu, Developer review và chỉnh sửa                                               |
|  5 | Ngô Tuấn Hưng | Tìm bug và debug trong code (pytest/runtime error debugging)                                 | Học viên / Python Developer              | Đọc traceback dài và tự suy luận lỗi logic                                                                                             | AI định vị, giải thích nguyên nhân; Developer tự sửa code                                                        |
|  6 | Ngô Tuấn Hưng | Giải quyết Git conflict khi merge code                                                       | Thành viên nhóm phát triển / DevOps      | So sánh code thủ công giữa hai nhánh, trao đổi với đồng đội                                                                            | AI gợi ý phương án merge tối ưu, Developer phê duyệt                                                             |
|  7 | Trần Xuân Lộc | Xử lý bug/ticket lặp lại cùng pattern                                                        | Developer, QA                            | Mất 2–4 giờ/tuần tìm codebase và git log cũ                                                                                            | Pain lặp lại hàng tuần; Workflow rõ ràng; AI có tiềm năng gợi ý solution                                         |
|  8 | Trần Xuân Lộc | Onboarding Developer mới                                                                     | Developer mới, Mentor                    | Mất 2–3 giờ/ngày trong tuần đầu để giải thích quy trình và code                                                                        | Giảm tải cho Mentor; phù hợp AI Agent Chatbot tra cứu tài liệu và code                                           |
|  9 | Trần Xuân Lộc | Tổng hợp thông tin viết báo cáo tuần                                                         | Developer, Team Lead                     | Gom dữ liệu từ Jira, Slack, Docs mất 60–90 phút/tuần                                                                                   | Quy trình lặp lại; dễ tự động hóa bằng AI và tích hợp dữ liệu                                                    |
| 10 | Lại Duy Đông  | Sàng lọc & xếp hạng CV tự động                                                               | Recruiter (HR Department)                | Đọc, đối chiếu CV với JD và chấm điểm thủ công (~10 phút/CV)                                                                           | ROI cao; phù hợp Agent AI; cần bảo mật dữ liệu cá nhân (PII)                                                     |
| 11 | Lại Duy Đông  | Mock data tự động cho Frontend                                                               | Frontend Developer                       | Phải chờ Backend cung cấp API hoặc JSON mẫu để kiểm thử UI                                                                             | Giảm phụ thuộc giữa Frontend và Backend; AI sinh JSON hiệu quả                                                   |
| 12 | Lại Duy Đông  | Giải đáp câu hỏi tự động trên Discord                                                        | Trợ giảng (TA), Học viên                 | Tra cứu tài liệu và trả lời các câu hỏi lặp lại                                                                                        | RAG Bot phù hợp; giảm tải cho TA; tần suất sử dụng cao                                                           |
| 13 | Nguyễn Chí Hướng | Tự động thiết lập môi trường phát triển cho đồ án (Java, Python, Node.js, SQL Server...) | Sinh viên CNTT                      | Mỗi project mới phải cài đặt IDE, SDK, database, package và cấu hình môi trường; mất 30–90 phút, dễ lỗi version hoặc thiếu dependency. | Tần suất lặp lại cao; tiết kiệm nhiều thời gian setup; phù hợp AI Workflow/AI Agent tự động cấu hình môi trường. |
| 14 | Nguyễn Chí Hướng | Quản lý và nhắc nhở deadline học tập thông minh                                          | Sinh viên                            | Phải kiểm tra Messenger, LMS, Email và nhiều nhóm học để biết deadline; dễ bỏ sót hoặc cập nhật muộn.                                  | Giá trị sử dụng hằng ngày; AI có thể tổng hợp và nhắc việc tự động từ nhiều nguồn; giảm nguy cơ quên deadline.   |
| 15 | Nguyễn Chí Hướng | Trợ lý AI tổng hợp và tìm kiếm tài liệu học tập đa nguồn                                 | Sinh viên                           | Một chủ đề phải tìm trên YouTube, GitHub, Documentation, ChatGPT và Google; thông tin phân tán, khó chọn lọc.                          | Phù hợp xây dựng AI Workflow/RAG; giảm thời gian tìm kiếm, tổng hợp tài liệu và tăng hiệu quả học tập.           |


| Cluster                                              | Candidates included                                                                                                                                                                                                                                                                            | Pattern chung                                                                                                      | Ghi chú                                                                                   |
| ---------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------- |
| **A. HR & Recruitment Automation**                   | **#2** Sàng lọc CV ứng viên vòng đầu (Nguyễn Tiến Đạt), **#10** Sàng lọc & xếp hạng CV tự động (Lại Duy Đông)                                                                                                                                                                                         | Tự động hóa quy trình tuyển dụng bằng AI (đọc, phân tích, đánh giá và xếp hạng CV theo JD)                         | Hai candidate gần như cùng một bài toán, có thể gộp thành một hướng phát triển.           |
| **B. Developer Productivity & Software Engineering** | **#4** System Logic Mapping, **#5** Debug code, **#6** Git Conflict Resolution (Ngô Tuấn Hưng), **#7** Xử lý bug lặp lại, **#8** Onboarding Developer, **#9** Báo cáo tuần (Trần Xuân Lộc), **#11** Mock Data Frontend (Lại Duy Đông), **#13** Tự động thiết lập môi trường phát triển (Huong) | Giảm thời gian cho các công việc kỹ thuật lặp lại trong vòng đời phát triển phần mềm (SDLC) bằng AI Workflow/Agent | Đây là cluster lớn nhất, tập trung vào tăng năng suất cho Developer và Team kỹ thuật.     |
| **C. Learning & Education Assistant**                | **#1** Trích xuất ý chính PDF (Nguyễn Tiến Đạt), **#12** Discord Q&A Bot (Lại Duy Đông), **#14** Quản lý deadline học tập (Huong), **#15** Tổng hợp tài liệu học tập đa nguồn (Huong)                                                                                                                 | AI hỗ trợ học tập: tổng hợp kiến thức, tra cứu, quản lý học tập và trả lời câu hỏi                                 | Có thể phát triển thành một hệ sinh thái AI Assistant dành cho sinh viên.                 |
| **D. Content & Knowledge Automation**                | **#3** Gỡ băng video & viết Content đa nền tảng (Nguyễn Tiến Đạt)                                                                                                                                                                                                                                     | Chuyển đổi và tái sử dụng nội dung bằng AI (Speech-to-Text, Summarization, Content Generation)                     | Hiện chỉ có một candidate nhưng là bài toán phổ biến trong Marketing và Content Creation. |


| Candidate                                                          | Vì sao vào shortlist                                                                                                                                                                                                                                             | Rủi ro / điều chưa rõ                                                                                                                                       |
| ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **#10 – Sàng lọc & xếp hạng CV tự động**                           | Workflow tuyển dụng rõ ràng (JD → đọc CV → chấm điểm → xếp hạng → HR review). Actor cụ thể (Recruiter/HR). Bottleneck dễ đo (thời gian đọc CV, số CV xử lý/ngày). Dễ vẽ before/after workflow và so sánh Rule-based, AI Workflow, AI Agent. Giá trị kinh tế cao. | Cần dữ liệu CV và JD thực tế; yêu cầu bảo mật thông tin cá nhân (PII); AI có thể đánh giá sai hoặc tạo thiên lệch nếu tiêu chí không tốt.                   |
| **#13 – Tự động thiết lập môi trường phát triển cho đồ án**        | Workflow rõ (chọn project → kiểm tra dependency → cài đặt → cấu hình → kiểm tra). Actor cụ thể (Sinh viên CNTT/Developer). Bottleneck rất phổ biến, thời gian setup có thể đo được. Phù hợp xây dựng AI Agent hỗ trợ cài đặt và xử lý lỗi.                       | Khó hỗ trợ mọi hệ điều hành và mọi stack công nghệ; cần quyền thực thi trên máy người dùng; phạm vi có thể rộng nếu hỗ trợ quá nhiều framework.             |
| **#15 – Trợ lý AI tổng hợp và tìm kiếm tài liệu học tập đa nguồn** | Workflow rõ (nhập chủ đề → tìm kiếm → lọc → tổng hợp → trả kết quả). Actor cụ thể (Sinh viên). Bottleneck là thông tin phân tán, có thể đo bằng thời gian tìm kiếm và độ đầy đủ tài liệu. Dễ mở rộng với RAG và AI Workflow.                                     | Chất lượng phụ thuộc nguồn dữ liệu; cần cơ chế đánh giá độ tin cậy và loại bỏ thông tin lỗi thời hoặc trùng lặp; tích hợp nhiều nguồn có thể mất thời gian. |




| Candidate                                                          | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain |   Tổng |
| ------------------------------------------------------------------ | -------: | ----------: | ---------------: | -------------: | ------------: | -----------------: | ---------------: | -----: |
| **#10 – Sàng lọc & xếp hạng CV tự động**                           |        5 |           5 |                5 |              5 |             4 |                  5 |                4 | **33** |
| **#13 – Tự động thiết lập môi trường phát triển cho đồ án**        |        5 |           5 |                5 |              4 |             4 |                  5 |                5 | **33** |
| **#15 – Trợ lý AI tổng hợp và tìm kiếm tài liệu học tập đa nguồn** |        5 |           4 |                4 |              4 |             5 |                  5 |                5 | **32** |

## Candidate nhóm chọn:

```text
#10 – Sàng lọc & xếp hạng CV tự động (AI Agent hỗ trợ Recruiter)

Problem:
Recruiter phải đọc và đánh giá thủ công hàng trăm CV cho mỗi vị trí tuyển dụng, mất nhiều thời gian, dễ thiếu nhất quán và phản hồi ứng viên chậm.

Actor:
Recruiter (Bộ phận Tuyển dụng của doanh nghiệp).

Giải pháp:
Xây dựng AI Agent tự động đọc CV (PDF/DOCX/ảnh), trích xuất thông tin, đối chiếu với Job Description (JD), chấm điểm, giải thích lý do đánh giá, xếp hạng ứng viên và tạo danh sách Shortlist để Recruiter kiểm duyệt (Human-in-the-Loop).
```

---

## Vì sao chọn:

```text
- Đây là bài toán thực tế mà nhiều doanh nghiệp gặp phải khi tuyển dụng số lượng lớn.
- Actor (Recruiter) và workflow tuyển dụng được xác định rõ ràng.
- Bottleneck tập trung ở bước đọc CV và đối chiếu với JD, rất phù hợp để ứng dụng AI.
- Hiệu quả có thể đo lường bằng thời gian xử lý, tỷ lệ đồng thuận giữa AI và Recruiter và thời gian phản hồi ứng viên.
- Có thể so sánh rõ giữa Rule-based (lọc theo từ khóa), AI Workflow và AI Agent.
- Phạm vi phù hợp với thời gian thực hiện của môn học và có thể xây dựng prototype để demo.
- Đề tài có giá trị ứng dụng thực tế, ROI cao và có tiềm năng mở rộng trong doanh nghiệp.
```

---

## Vì sao không chọn các candidate còn lại:

```text
- #13 – Tự động thiết lập môi trường phát triển: phù hợp với sinh viên CNTT nhưng phụ thuộc nhiều vào hệ điều hành, ngôn ngữ lập trình và công cụ, khiến phạm vi triển khai khá rộng trong thời gian của môn học.
- #15 – Trợ lý AI tổng hợp và tìm kiếm tài liệu học tập: dễ triển khai nhưng đã có nhiều giải pháp tương tự trên thị trường, tính khác biệt chưa cao và khó chứng minh hiệu quả định lượng hơn so với bài toán tuyển dụng.
- Các candidate khác trong nhóm chủ yếu giải quyết các nhu cầu nội bộ hoặc có phạm vi hẹp, trong khi bài toán sàng lọc CV có giá trị kinh doanh rõ ràng, quy trình chuẩn và dễ chứng minh hiệu quả của AI Agent.
```

---

## Nếu có disagreement, nhóm xử lý thế nào:

```text
Ban đầu nhóm có hai candidate được đánh giá cao là #10 (Sàng lọc & xếp hạng CV tự động) và #13 (Tự động thiết lập môi trường phát triển). Nhóm tiến hành thảo luận dựa trên các tiêu chí đã thống nhất ở bước 3.4 gồm: độ rõ của actor, workflow, bottleneck, khả năng đo lường impact, mức độ phù hợp với AI Agent và phạm vi thực hiện trong lab.

Sau khi chấm điểm và trao đổi, nhóm thống nhất chọn #10 vì có giá trị thực tiễn cao hơn, workflow chuẩn, dễ xây dựng demo và dễ đánh giá hiệu quả bằng các chỉ số cụ thể. Quyết định cuối cùng được thông qua theo sự đồng thuận của toàn bộ thành viên trong nhóm.
```

| Nguồn                     |              Số người / số mẫu | Tín hiệu xác nhận                                                                                                                                                                                        | Tín hiệu phản bác                                                                                             | Nhóm sửa problem thế nào                                                                                                                            |
| ------------------------- | -----------------------------: | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| Interview (Pilot)         |          3 Recruiter (dự kiến) | Recruiter cho biết bước đọc CV và đối chiếu JD chiếm nhiều thời gian nhất; việc đánh giá phụ thuộc kinh nghiệm cá nhân nên đôi khi thiếu nhất quán; mong muốn có công cụ hỗ trợ tạo shortlist nhanh hơn. | Recruiter vẫn muốn tự quyết định ứng viên cuối cùng và không muốn AI tự động loại hồ sơ.                      | Điều chỉnh phạm vi: AI **không thay thế Recruiter**, chỉ hỗ trợ đọc CV, chấm điểm, giải thích và đề xuất shortlist; Recruiter là Human-in-the-Loop. |
| Survey / Poll (Planned)   |         5–10 Recruiter hoặc HR | Kỳ vọng đa số đánh giá việc sàng lọc CV là công việc lặp lại, tốn thời gian và phù hợp để tự động hóa một phần.                                                                                          | Một số doanh nghiệp nhỏ có lượng CV ít nên lợi ích không đáng kể.                                             | Giới hạn đối tượng mục tiêu là doanh nghiệp tuyển dụng số lượng lớn hoặc tuyển dụng thường xuyên.                                                   |
| Log / Review / Case Study | Tài liệu và nghiên cứu hiện có | Nhiều nền tảng tuyển dụng đã bổ sung AI hỗ trợ phân tích và gợi ý ứng viên, nhưng vẫn giữ con người trong vòng phê duyệt cuối cùng. ([Hỗ trợ Greenhouse][1])                                             | AI có nguy cơ tạo thiên lệch (bias) hoặc đánh giá sai nếu dùng làm công cụ quyết định cuối cùng. ([arXiv][2]) | Thiết kế hệ thống theo hướng **AI hỗ trợ ra quyết định**, không tự động từ chối hoặc tuyển dụng ứng viên.                                           |


# Phase 4 — Quick Validation + Research giải pháp 




# Bước 4.1 — Quick validation

Nhóm lựa chọn kết hợp **Quick Interview** và **Research các giải pháp hiện có** để xác nhận vấn đề.

## Option A — Quick interviews

### Đối tượng phỏng vấn

- 03 Recruiter đang hoặc đã tham gia tuyển dụng.
- Hình thức: Trao đổi trực tiếp .


### Kết quả

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Hỏi | 3 Recruiter | Recruiter đều cho biết bước đọc CV, đối chiếu JD và chọn shortlist là bước tốn nhiều thời gian nhất. Việc đánh giá còn phụ thuộc kinh nghiệm từng người nên đôi khi thiếu nhất quán. | Recruiter không muốn AI tự động quyết định tuyển hay loại ứng viên. | AI chỉ đóng vai trò hỗ trợ đọc CV, phân tích, chấm điểm và đề xuất shortlist; Recruiter vẫn là người quyết định cuối cùng (Human-in-the-Loop). |
| Hỏi | Dự kiến 5–10 Recruiter hoặc HR | Kỳ vọng đa số đánh giá screening CV là công việc lặp lại, mất nhiều thời gian và phù hợp để tự động hóa một phần. | Doanh nghiệp tuyển ít CV sẽ không thấy nhiều lợi ích. | Giới hạn phạm vi bài toán cho doanh nghiệp tuyển dụng thường xuyên hoặc có số lượng CV lớn. |
| Hỏi | Nghiên cứu tài liệu và sản phẩm thực tế | Nhiều ATS đã tích hợp AI để phân tích CV, gợi ý ứng viên và hỗ trợ Recruiter. | AI có thể tạo bias hoặc đánh giá sai nếu được dùng để tự động ra quyết định. | Thiết kế AI theo hướng Decision Support thay vì Decision Maker. |

---

# Bước 4.2 — Research giải pháp đã có

## Existing solutions

| Nguồn / Tool / Case | Link | Họ giải quyết phần nào? | Điểm mạnh | Khoảng trống / Rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Greenhouse AI | https://www.greenhouse.com | Hỗ trợ đọc CV, matching với JD, đề xuất ứng viên và hỗ trợ Recruiter trong ATS. | Workflow hoàn chỉnh, tích hợp tuyển dụng thực tế. | Không minh bạch hoàn toàn cách AI đánh giá; phụ thuộc dữ liệu doanh nghiệp. | AI nên giải thích lý do chấm điểm để Recruiter dễ kiểm tra. |
| LinkedIn Recruiter AI | https://business.linkedin.com/talent-solutions/recruiter | AI hỗ trợ tìm kiếm, gợi ý và xếp hạng ứng viên từ cơ sở dữ liệu LinkedIn. | Dữ liệu ứng viên lớn, tìm kiếm nhanh, tăng hiệu quả sourcing. | Chủ yếu hỗ trợ ứng viên trong hệ sinh thái LinkedIn; ít hỗ trợ CV ngoài hệ thống. | Có thể học cách AI đề xuất ứng viên nhưng cần hỗ trợ nhiều định dạng CV khác nhau. |
| Workday Recruiting AI | https://www.workday.com | AI hỗ trợ screening, matching kỹ năng, đề xuất ứng viên và hỗ trợ quy trình tuyển dụng. | Tích hợp sâu với HRM và ATS doanh nghiệp. | Triển khai phức tạp; chi phí cao; yêu cầu dữ liệu doanh nghiệp. | Prototype nên tập trung vào workflow cốt lõi thay vì xây dựng toàn bộ ATS. |

---

## Tổng kết nghiên cứu

### Những phần các giải pháp hiện có đã làm tốt

- Đọc CV nhiều định dạng.
- Trích xuất thông tin ứng viên.
- So khớp với Job Description.
- Chấm điểm và xếp hạng ứng viên.
- Tích hợp vào quy trình tuyển dụng.

### Những khoảng trống còn tồn tại

- Khó giải thích vì sao AI đưa ra điểm số.
- Nguy cơ thiên lệch (Bias).
- Thiếu minh bạch trong quá trình đánh giá.
- Không nên để AI tự động từ chối ứng viên.

### Bài học cho nhóm

Prototype của nhóm sẽ tập trung vào:

1. Đọc CV (PDF/DOCX/Image).
2. Trích xuất thông tin quan trọng.
3. Đọc Job Description.
4. Matching kỹ năng giữa JD và CV.
5. Chấm điểm theo tiêu chí rõ ràng.
6. Giải thích lý do chấm điểm (Explainable AI).
7. Xếp hạng ứng viên.
8. Recruiter kiểm duyệt và quyết định cuối cùng (Human-in-the-Loop).

---


# Phase 5 — Workflow + Problem Statement (45')

---

# Bước 5.1 — Current workflow bản nhóm

## Workflow hiện tại

```text
Recruiter nhận Job Description (JD)
        │
        ▼
Đăng tin tuyển dụng
        │
        ▼
Ứng viên gửi CV (PDF/DOCX)
        │
        ▼
Recruiter mở từng CV
        │
        ▼
Đọc toàn bộ CV
        │
        ▼
Đối chiếu từng kỹ năng với JD
        │
        ▼
Đánh giá kinh nghiệm, học vấn, kỹ năng
        │
        ▼
Chấm điểm thủ công
        │
        ▼
So sánh các ứng viên
        │
        ▼
Lập danh sách Shortlist
        │
        ▼
Mời phỏng vấn
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---|---|---|---|---|---|
| 1 | Recruiter | Job Description | Tiêu chí tuyển dụng | 5–10 phút / vị trí | Xác định yêu cầu tuyển dụng |
| 2 | Recruiter | CV ứng viên | Danh sách CV | Liên tục khi có ứng tuyển | Có thể hàng trăm CV |
| 3 | Recruiter | CV | Thông tin ứng viên | 5–10 phút / CV | Đọc thủ công từng CV |
| 4 | Recruiter | JD + CV | Đánh giá mức độ phù hợp | 3–5 phút / CV | So khớp kỹ năng bằng mắt |
| 5 | Recruiter | Kết quả đánh giá | Danh sách Shortlist | 30–60 phút / đợt tuyển | Xếp hạng và lựa chọn ứng viên |

### Bottleneck chính

```text
- Recruiter phải mở và đọc từng CV thủ công.
- Đối chiếu kỹ năng với JD bằng mắt.
- Chấm điểm phụ thuộc kinh nghiệm cá nhân nên thiếu nhất quán.
- Khi số lượng CV lớn (100–300 CV), thời gian screening kéo dài nhiều giờ hoặc nhiều ngày.
- Ứng viên phải chờ phản hồi lâu.
```

---

# Bước 5.2 — Future workflow bản nhóm

## Workflow sau khi áp dụng AI Agent

```text
Recruiter nhập Job Description
        │
        ▼
Ứng viên nộp CV
        │
        ▼
AI Agent đọc CV
        │
        ▼
AI trích xuất thông tin
        │
        ▼
AI so khớp với JD
        │
        ▼
AI chấm điểm + giải thích lý do
        │
        ▼
AI tạo bảng xếp hạng & Shortlist
        │
        ▼
Recruiter xem kết quả
        │
 ┌──────┴────────┐
 │               │
 ▼               ▼
Đồng ý        Không đồng ý
 │               
 ▼               
Mời PV      
 │               │
 └──────┬────────┘
        ▼
Hoàn thành Screening
```

## Boundary giữa AI và Con người

### Rule-based

- Kiểm tra định dạng file.
- Kiểm tra CV có đọc được hay không.
- Kiểm tra trường thông tin bắt buộc.

### AI Agent

- Đọc CV (PDF/DOCX/Image).
- Trích xuất thông tin.
- Matching JD và CV.
- Chấm điểm ứng viên.
- Giải thích lý do chấm điểm.
- Xếp hạng ứng viên.
- Đề xuất Shortlist.

### Con người

- Kiểm tra kết quả AI.
- Điều chỉnh nếu cần.
- Quyết định ứng viên được phỏng vấn.
- Đưa ra quyết định tuyển dụng cuối cùng.

### Fallback nếu AI sai

- Recruiter bỏ qua điểm AI.
- Recruiter tự đánh giá lại CV.
- Có thể chỉnh trọng số tiêu chí hoặc chấm điểm thủ công.

---

## Before / After Impact

| Metric | Trước | Sau kỳ vọng | Ghi chú |
|---|---:|---:|---|
| Số bước | 10 | 8 | Giảm các bước đọc và đối chiếu thủ công |
| Tổng thời gian | 6–10 giờ / 100 CV | 1–2 giờ / 100 CV | AI xử lý phần lớn việc screening |
| Số bước thủ công | 6 | 2 | Recruiter chỉ review và quyết định |
| Bottleneck chính | Đọc CV & đối chiếu JD | Review kết quả AI | Chuyển bottleneck sang bước kiểm duyệt |
| Risk mới | Ít | AI có thể đánh giá sai hoặc bias | Cần Human-in-the-Loop |

---

# Bước 5.3 — Problem Statement v0

| Field | Nội dung |
|---|---|
| **Actor** | Recruiter (Bộ phận Tuyển dụng của doanh nghiệp). |
| **Workflow** | Recruiter nhận JD → nhận CV → đọc từng CV → đối chiếu JD → đánh giá → chấm điểm → xếp hạng → tạo Shortlist → mời phỏng vấn. |
| **Bottleneck** | Việc đọc và đánh giá thủ công từng CV tốn nhiều thời gian, dễ thiếu nhất quán và làm chậm quá trình tuyển dụng. |
| **Impact** | Recruiter mất nhiều giờ cho mỗi đợt tuyển dụng, thời gian phản hồi ứng viên kéo dài và hiệu quả tuyển dụng giảm khi số lượng CV lớn. |
| **Success Metric** | Giảm ≥70% thời gian screening CV; AI tạo được bảng xếp hạng và giải thích kết quả; Recruiter đồng thuận với đề xuất AI ở mức cao; giảm thời gian phản hồi ứng viên. |
| **Boundary** | AI chỉ hỗ trợ đọc CV, phân tích, chấm điểm và đề xuất Shortlist. Quyết định cuối cùng luôn thuộc về Recruiter (Human-in-the-Loop). |

# Phase 6 — Rule / Workflow / Agent + Decision (25')

---

# Bước 6.0 — Ma trận độ phù hợp với AI để suy nghĩ nhanh

## Bài toán của nhóm nằm ở ô nào?

```text
Độ phức tạp cao + Độ mơ hồ cao
→ Agent phù hợp, nhưng cần Human-in-the-Loop và boundary rõ ràng.
```

## Vì sao?

```text
- Workflow tuyển dụng gồm nhiều bước liên tiếp: nhận JD → nhận CV → đọc CV → trích xuất thông tin → so khớp JD → chấm điểm → giải thích → xếp hạng → Recruiter review.
- Hệ thống phải xử lý nhiều nguồn dữ liệu (JD, CV PDF/DOCX/Image, tiêu chí tuyển dụng).
- Việc đánh giá mức độ phù hợp giữa CV và JD không có một đáp án đúng tuyệt đối; hai Recruiter khác nhau có thể đưa ra đánh giá khác nhau nhưng đều hợp lý.
- AI cần lựa chọn công cụ phù hợp (đọc PDF, OCR nếu là ảnh, trích xuất thông tin, LLM đánh giá) và phối hợp nhiều bước để tạo kết quả cuối cùng.
- Tuy nhiên, AI không được phép tự quyết định tuyển hoặc loại ứng viên; Recruiter luôn là người phê duyệt cuối cùng.
```

---

# Bước 6.1 — So sánh Rule / Workflow / Agent

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? |
|---|---|---|---|---|
| **Rule** | Lọc CV theo từ khóa (Java, Python, IELTS...), số năm kinh nghiệm, bằng cấp | Chỉ phù hợp khi tiêu chí tuyển dụng rất đơn giản và cố định | Không hiểu ngữ cảnh, bỏ sót ứng viên tốt hoặc đánh giá sai | Không |
| **Workflow** | Chuỗi bước cố định: đọc CV → trích xuất → so khớp JD → chấm điểm → xuất kết quả | Đủ khi dữ liệu đồng nhất và không cần thay đổi cách xử lý | Khó mở rộng, khó thích ứng với nhiều loại CV hoặc tiêu chí tuyển dụng khác nhau | Có thể |
| **Agent** | AI Agent tự lựa chọn công cụ (PDF Parser, OCR, LLM), phân tích CV, matching với JD, giải thích kết quả và đề xuất Shortlist | Phù hợp với quy trình tuyển dụng thực tế có nhiều bước và nhiều loại dữ liệu | Có thể đánh giá sai hoặc tạo bias nếu không có Recruiter kiểm tra | Có |

## Hỏi kỹ

### Rule có giải được 70–80% case không?

Không. Rule-based chỉ lọc được theo từ khóa hoặc điều kiện cố định, không hiểu ngữ cảnh và khó đánh giá năng lực thực tế của ứng viên.

### Workflow có đủ vì các bước khá rõ không?

Workflow có thể giải quyết phần lớn quy trình, nhưng khó xử lý linh hoạt khi CV có nhiều định dạng khác nhau hoặc tiêu chí tuyển dụng thay đổi. Ngoài ra, Workflow không tự quyết định nên dùng công cụ nào để xử lý từng loại dữ liệu.

### Có thật sự cần Agent tự lập kế hoạch/gọi công cụ/đổi bước tiếp theo không?

Có.

Ví dụ:

- Nếu CV là PDF → dùng PDF Parser.
- Nếu CV là ảnh → dùng OCR.
- Sau khi trích xuất → dùng LLM để phân tích.
- Nếu thông tin chưa đủ → yêu cầu Recruiter bổ sung hoặc đánh dấu cần review.

### Nếu AI sai, ai phát hiện và sửa?

Recruiter sẽ:

- kiểm tra bảng điểm,
- xem giải thích của AI,
- chỉnh sửa hoặc bỏ qua đề xuất nếu cần,
- quyết định shortlist cuối cùng.

### Có thể hạ mức từ Agent về Workflow hoặc từ Workflow về Rule không?

Có.

Nếu phạm vi prototype nhỏ hơn, nhóm có thể chỉ xây dựng AI Workflow (chuỗi bước cố định). Tuy nhiên, với mục tiêu của đề tài là AI Agent hỗ trợ Recruiter, Agent phù hợp hơn.

---

## Mức chọn

```text
Agent
```

## Vì sao chọn

```text
- Quy trình tuyển dụng gồm nhiều bước liên tiếp và nhiều nguồn dữ liệu.
- AI cần phối hợp nhiều công cụ (PDF Parser, OCR, LLM) để hoàn thành nhiệm vụ.
- AI phải tự lựa chọn cách xử lý phù hợp với từng loại CV.
- AI cần giải thích kết quả để Recruiter dễ kiểm tra.
- Recruiter luôn giữ quyền quyết định cuối cùng (Human-in-the-Loop).
```

## Vì sao không chọn mức đơn giản hơn

```text
Rule-based chỉ phù hợp với việc lọc theo từ khóa nên không đáp ứng yêu cầu đánh giá toàn diện.

Workflow xử lý được chuỗi bước cố định nhưng thiếu khả năng thích ứng với nhiều loại dữ liệu và khó mở rộng khi quy trình tuyển dụng thay đổi.

AI Agent giúp tăng tính linh hoạt, khả năng mở rộng và phù hợp hơn với quy trình tuyển dụng thực tế.
```

---

# Bước 6.2 — Problem Statement v1

| Field | Nội dung |
|---|---|
| **Actor** | Recruiter (Bộ phận Tuyển dụng của doanh nghiệp) |
| **Workflow** | Recruiter nhập JD → Ứng viên nộp CV → AI Agent đọc CV → Trích xuất thông tin → So khớp JD → Chấm điểm → Giải thích → Xếp hạng → Recruiter review → Tạo Shortlist |
| **Bottleneck** | Recruiter phải đọc và đánh giá thủ công số lượng lớn CV, mất nhiều thời gian và dễ thiếu nhất quán. |
| **Impact** | Giảm thời gian screening, tăng tính nhất quán khi đánh giá và rút ngắn thời gian phản hồi ứng viên. |
| **Success Metric** | Giảm ≥70% thời gian screening; AI tạo được bảng xếp hạng và giải thích kết quả; Recruiter đồng thuận với đề xuất AI ở mức cao; giảm thời gian phản hồi ứng viên. |
| **Boundary** | AI chỉ hỗ trợ phân tích, chấm điểm và đề xuất Shortlist. Recruiter quyết định cuối cùng. |
| **AI intervention point** | Đọc CV, trích xuất thông tin, matching JD, chấm điểm, giải thích và xếp hạng ứng viên. |
| **Mức chọn** | **Agent** |
| **Rủi ro & người thật kiểm tra** | AI có thể đánh giá sai hoặc tạo bias; Recruiter luôn kiểm tra, chỉnh sửa và phê duyệt kết quả trước khi sử dụng. |

---

# Bước 6.3 — Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú |
|---|---|---|
| Actor và workflow đã rõ chưa? |  Yes | Recruiter và quy trình tuyển dụng đã được xác định rõ. |
| Baseline và success metric đã đo được chưa? |  Yes | Có thể đo thời gian screening, số CV xử lý và thời gian phản hồi ứng viên. |
| Có data/input đủ dùng chưa? | Not Yet | Cần thu thập thêm JD và CV mẫu để huấn luyện và kiểm thử prototype. |
| Nếu AI sai, hậu quả có chấp nhận được không? |  Yes | AI chỉ hỗ trợ, Recruiter vẫn quyết định cuối cùng. |
| Có người review/owner vận hành không? |  Yes | Recruiter đóng vai trò kiểm duyệt và vận hành hệ thống. |
| Có cách non-AI đơn giản hơn không? |  Yes | Rule-based hoặc Workflow có thể áp dụng nhưng hiệu quả và khả năng mở rộng thấp hơn. |

## Decision

```text
Go
```

## Lý do

```text
Bài toán có actor rõ ràng, workflow cụ thể, pain point phổ biến và dễ đo lường. AI Agent phù hợp để hỗ trợ Recruiter trong các bước lặp lại như đọc CV, matching với JD và chấm điểm. Human-in-the-Loop giúp giảm rủi ro khi AI đánh giá sai và đảm bảo quyết định cuối cùng vẫn thuộc về Recruiter.
```

## Nếu Go, pilot nhỏ nhất là

```text
Prototype cho phép:

- Recruiter nhập 01 Job Description.
- Upload 10–20 CV (PDF/DOCX).
- AI Agent trích xuất thông tin.
- So khớp với JD.
- Chấm điểm.
- Giải thích lý do.
- Xuất bảng xếp hạng và đề xuất Shortlist để Recruiter kiểm duyệt.
```

## Nếu Not Yet, cần validate gì trước

```text
- Thu thập thêm CV và JD thực tế.
- Kiểm tra chất lượng kết quả AI trên nhiều vị trí tuyển dụng.
- Đánh giá mức độ đồng thuận giữa AI và Recruiter.
```

## Nếu No-Go, nên làm gì thay AI

```text
Áp dụng Rule-based filtering hoặc Workflow tự động để lọc CV theo từ khóa và tiêu chí cố định trước khi Recruiter thực hiện đánh giá thủ công.
```

