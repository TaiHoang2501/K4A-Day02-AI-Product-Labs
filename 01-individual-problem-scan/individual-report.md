# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Hoàng Anh Tài
- Mã học viên: 02612
- Vai trò / bối cảnh: Thực tập sinh tại Trung tâm CNTT của 1 công ty khoảng 20 người. Mình phải viết báo cáo buổi họp hàng tuần đồng thời viết báo cáo vễ dữ liệu, xếp lịch họp hàng tuần

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| **1** | **Tốn thời gian + Lặp lại + AI có thể tốt hơn** | Tìm và hiểu definition của các chỉ tiêu dữ liệu khi làm báo cáo vì tên field/code khác nhau giữa các nguồn | Data Analyst, Intern | Phải tìm nhiều file hoặc hỏi người cũ; một chỉ tiêu có thể có nhiều cách hiểu; mất khoảng **20–30 phút/chỉ tiêu** khi chưa quen |
| **2** | **Pain từ người khác + Tốn thời gian** | Người yêu cầu phân tích mô tả nhu cầu bằng ngôn ngữ nghiệp vụ nhưng Data team phải hỏi lại để xác định chính xác metric, filter và time period | Business User + Data Analyst | Phải trao đổi qua lại nhiều lần trước khi xác định được yêu cầu phân tích cụ thể |
| **4** | **Pain từ người khác + Tốn thời gian** | Người mới vào team phải tự học và tổng hợp kiến thức về hệ thống dữ liệu từ nhiều tài liệu rời rạc | Intern / Nhân viên mới | Cấp trên thường đưa yêu cầu tổng quát và yêu cầu tự tìm hiểu; phải đọc nhiều tài liệu trước khi hiểu được database và workflow |
| **4** | **Tốn thời gian + Lặp lại + AI có thể tốt hơn** | Viết meeting notes sau các buổi cross-team meeting | Member / Người được phân công ghi biên bản | Khoảng **30 phút/buổi** để tổng hợp nội dung, quyết định và action items; phải hỏi lại khi có nội dung chưa rõ |
| **5** | **Tốn thời gian + AI có thể tốt hơn** | Hiểu và xác định các thông tin cần thiết trong một bộ dữ liệu lớn | Member / Data Analyst / Intern | Database có nhiều bảng, field và code; người chưa có kinh nghiệm mất nhiều thời gian để tìm hiểu cấu trúc và ý nghĩa dữ liệu |


> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?


## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| **1** | **Viết meeting minutes sau mỗi buổi họp**           | Workflow rõ, xảy ra thường xuyên, mất thời gian, có thể đo thời gian và độ đầy đủ của biên bản | AI ghi nhận và tổng hợp có đủ chính xác không, đặc biệt với nội dung không rõ hoặc ngoài phạm vi trách nhiệm |
| **2** | **Tìm và hiểu definition của các chỉ tiêu dữ liệu** | Có pain thật, phải tìm thông tin ở nhiều nguồn, AI có thể hỗ trợ search/tóm tắt/giải thích     | **An toàn dữ liệu**, quyền truy cập và độ chính xác của AI khi giải thích definition                         |
| **3** | **Xếp lịch họp/lịch làm việc cho nhiều người**      | Quy trình lặp lại, thường phải trao đổi qua lại, pain dễ quan sát và có metric rõ              | Có cần AI/Agent hay chỉ cần calendar + rule/constraint solving là đủ                                         |


### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

┌────────────────────────────────────────────────────┐
│ PROBLEM CARD #1                                    │
│                                                    │
│ Problem 1 câu:                                     │
│ Phải viết Meeting Minutes sau mỗi buổi họp,       │
│ trong khi người ghi biên bản phải vừa nghe họp,  │
│ vừa ghi chú và sau đó tổng hợp lại nội dung.     │
│                                                    │
│ Ai chịu ảnh hưởng?                                 │
│ Người được phân công ghi biên bản                  │
│                                                    │
│ Workflow hiện tại:                                 │
│ 1. Tham gia họp                                    │
│ → 2. Ghi chú trong khi họp                         │
│ → 3. Hỏi lại nội dung chưa rõ                      │
│ → 4. Tổng hợp nội dung                             │
│ → 5. Viết Meeting Minutes                          │
│ → 6. Gửi các thành viên xác nhận                   │
│                                                    │
│ Bước nghẽn nhất:                                   │
│ Ghi chú + tổng hợp lại nội dung sau cuộc họp       │
│                                                    │
│ Impact:                                             │
│ Khoảng 1 giờ/tuần                                  │
│                                                    │
│ Đo thành công bằng gì?                             │
│ Giảm thời gian viết biên bản từ ~60 phút           │
│ xuống ≤15 phút/buổi họp                            │
│ + Meeting Minutes vẫn đầy đủ các action items     │
│                                                    │
│ Quick gut:                                         │
│ □ No AI    □ Rule    ☑ Workflow    ☑ Agent        │
└────────────────────────────────────────────────────┘

┌────────────────────────────────────────────────────┐
│ PROBLEM CARD #2                                    │
│                                                    │
│ Problem 1 câu:                                     │
│ Data Analyst mất thời gian tìm và hiểu definition │
│ của các chỉ tiêu dữ liệu trước khi sử dụng chúng │
│ trong phân tích/báo cáo.                           │
│                                                    │
│ Ai chịu ảnh hưởng?                                 │
│ Data Analyst / Data Intern                         │
│                                                    │
│ Workflow hiện tại:                                 │
│ 1. Nhận yêu cầu                                    │
│ → 2. Xác định KPI cần dùng                         │
│ → 3. Tìm definition                                │
│ → 4. Tìm source/table/field                        │
│ → 5. Đọc tài liệu                                  │
│ → 6. Hỏi người có kinh nghiệm nếu chưa rõ         │
│                                                    │
│ Bước nghẽn nhất:                                   │
│ Tìm kiếm + đối chiếu definition từ nhiều nguồn    │
│                                                    │
│ Impact:                                             │
│ ~20-30 phút/chỉ tiêu chưa quen                     │
│                                                    │
│ Đo thành công bằng gì?                             │
│ Giảm thời gian tìm hiểu từ 20-30 phút              │
│ xuống ≤5 phút                                      │
│                                                    │
│ Quick gut:                                         │
│ □ No AI    □ Rule    ☑ Workflow    ☑ Agent        │
└────────────────────────────────────────────────────┘


┌────────────────────────────────────────────────────┐
│ PROBLEM CARD #3                                    │
│                                                    │
│ Problem 1 câu:                                     │
│ Mất nhiều thời gian để tìm thời gian họp phù hợp  │
│ khi phải đồng thời đáp ứng lịch trống của nhiều   │
│ người và các constraint khác nhau.                 │
│                                                    │
│ Ai chịu ảnh hưởng?                                 │
│ Người tổ chức cuộc họp + các thành viên            │
│                                                    │
│ Workflow hiện tại:                                 │
│ 1. Xác định người cần tham gia                      │
│ → 2. Kiểm tra lịch từng người                       │
│ → 3. Tìm khoảng thời gian phù hợp                  │
│ → 4. Đề xuất thời gian                             │
│ → 5. Trao đổi nếu có người không phù hợp           │
│ → 6. Chốt lịch                                     │
│                                                    │
│ Bước nghẽn nhất:                                   │
│ Tìm khoảng thời gian thỏa mãn nhiều constraint     │
│                                                    │
│ Impact:                                             │
│ 10-20 phút/lần + nhiều tin nhắn trao đổi            │
│                                                    │
│ Đo thành công bằng gì?                             │
│ Giảm thời gian xếp lịch từ 15 phút                 │
│ xuống ≤3 phút                                      │
│                                                    │
│ Quick gut:                                         │
│ □ No AI    ☑ Rule    ☑ Workflow    □ Agent        │
└────────────────────────────────────────────────────┘
---

#### Problem Card #1 — Viết meeting minutes sau mỗi buổi họp

Problem 1 câu:

Phải viết Meeting Minutes sau mỗi buổi họp, trong khi
người ghi biên bản phải vừa nghe họp, vừa ghi chú và
sau đó tổng hợp lại nội dung.


Actor:

Người được phân công ghi biên bản.


Thời điểm / bối cảnh:

Sau mỗi buổi họp, thường xuyên hàng tuần.


Current workflow 3-7 bước:

1. Tham gia buổi họp
2. Ghi chép nội dung trong buổi họp
3. Hỏi lại những nội dung chưa rõ
4. Tổng hợp các nội dung đã ghi chú
5. Viết lại thành Meeting Minutes
6. Gửi cho các thành viên xác nhận/chỉnh sửa


Bottleneck:

Ghi chép và tổng hợp nội dung trong khi/ngay sau cuộc họp.
Người ghi biên bản có thể không hiểu một số nội dung,
hoặc phải lọc những nội dung không liên quan đến mình.


Impact:

Khoảng 1 giờ/tuần cho việc ghi chú, tổng hợp và hoàn thiện
Meeting Minutes.


Success metric:

- Giảm thời gian hoàn thiện Meeting Minutes từ ~60 phút
  xuống ≤15 phút/buổi.
- 100% action items quan trọng được ghi nhận.
- Giảm số lần phải hỏi lại nội dung sau cuộc họp.


Non-AI alternative:

Sử dụng template Meeting Minutes cố định + checklist
các nội dung bắt buộc + phân công rõ người ghi biên bản.


AI hypothesis:

AI có thể ghi nhận nội dung cuộc họp, tự động phân loại
thành:
- Nội dung chính
- Quyết định
- Action items
- Người phụ trách
- Deadline
- Nội dung cần làm rõ

Sau đó tạo Meeting Minutes draft để người phụ trách
review trước khi gửi.


Quick gut:

[ ] No AI / process fix
[ ] Rule
[x] Workflow
[x] Agent
[ ] Chưa biết


#### Problem Card #2 — Tìm và hiểu definition của các chỉ tiêu dữ liệu
Problem 1 câu:

Data Analyst mất thời gian tìm và hiểu definition của
các chỉ tiêu dữ liệu trước khi sử dụng chúng trong
phân tích hoặc báo cáo.


Actor:

Data Analyst / Data Intern.


Thời điểm / bối cảnh:

Khi nhận một yêu cầu phân tích mới hoặc làm việc với
dataset/chỉ tiêu chưa quen thuộc.


Current workflow 3-7 bước:

1. Nhận yêu cầu phân tích
2. Xác định chỉ tiêu/KPI cần sử dụng
3. Tìm definition trong Data Dictionary/tài liệu
4. Tìm source table và field tương ứng
5. Đọc và đối chiếu các tài liệu liên quan
6. Hỏi người có kinh nghiệm nếu definition chưa rõ
7. Xác nhận chỉ tiêu trước khi sử dụng


Bottleneck:

Tìm kiếm và đối chiếu thông tin definition từ nhiều
nguồn khác nhau.


Impact:

Khoảng 20-30 phút cho mỗi chỉ tiêu chưa quen thuộc.
Nếu phải tìm nhiều chỉ tiêu, thời gian discovery tăng đáng kể.


Success metric:

- Giảm thời gian tìm hiểu một chỉ tiêu từ 20-30 phút
  xuống ≤5 phút.
- Definition retrieval accuracy ≥90%.
- Giảm số lần phải hỏi người khác để xác nhận definition.


Non-AI alternative:

Xây dựng Data Dictionary tập trung với:
- Business Definition
- Technical Definition
- Source Table
- Source Field
- Formula
- Data Owner
- Example


AI hypothesis:

AI có thể tìm kiếm và tổng hợp definition từ Data
Dictionary, tài liệu nghiệp vụ và metadata.

Khi người dùng hỏi về một KPI, AI trả về:
- Definition
- Công thức
- Source table/field
- Ý nghĩa nghiệp vụ
- Ví dụ
- Citation/source


Quick gut:

[ ] No AI / process fix
[ ] Rule
[x] Workflow
[x] Agent
[ ] Chưa biết

#### Problem Card #3 — Xếp lịch họp/lịch làm việc cho nhiều người
Problem 1 câu:

Mất nhiều thời gian để tìm thời gian họp phù hợp khi
phải đồng thời đáp ứng lịch trống của nhiều người và
các constraint khác nhau.


Actor:

Người tổ chức cuộc họp và các thành viên tham gia.


Thời điểm / bối cảnh:

Khi cần tổ chức cuộc họp có từ 3 người trở lên.


Current workflow 3-7 bước:

1. Xác định những người cần tham gia
2. Kiểm tra lịch của từng người
3. Tìm các khoảng thời gian mọi người cùng rảnh
4. Đề xuất một hoặc một số thời gian
5. Trao đổi lại nếu có người không phù hợp
6. Điều chỉnh thời gian
7. Chốt và gửi lịch họp


Bottleneck:

Tìm khoảng thời gian đáp ứng đồng thời nhiều constraint,
ví dụ:
- Tất cả thành viên phải rảnh
- Không trùng cuộc họp khác
- Trong giờ làm việc
- Ưu tiên một số khung giờ
- Người quan trọng phải tham gia


Impact:

Khoảng 10-20 phút cho mỗi lần xếp lịch và có thể phát sinh
nhiều lượt trao đổi qua chat/email.


Success metric:

- Giảm thời gian xếp lịch từ 10-20 phút xuống ≤3 phút.
- Giảm số lượt trao đổi để chốt lịch.
- Tỷ lệ lịch được chấp nhận ngay từ đề xuất đầu tiên.


Non-AI alternative:

Calendar + rule-based scheduling/constraint solver.

Ví dụ:
- Tìm intersection giữa lịch trống.
- Loại bỏ ngoài giờ làm việc.
- Ưu tiên slot có nhiều người rảnh nhất.


AI hypothesis:

AI có thể nhận yêu cầu bằng ngôn ngữ tự nhiên:

"Xếp một cuộc họp 60 phút với A, B và C trong tuần
sau, ưu tiên buổi chiều và tránh thứ Hai."

AI chuyển yêu cầu thành các constraint, kiểm tra lịch
và đề xuất các slot phù hợp.


Quick gut:

[ ] No AI / process fix
[x] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```Problem #2 – Tìm và hiểu definition của các chỉ tiêu dữ liệu

```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```Khi nhận một yêu cầu phân tích, Data Analyst thường phải tìm definition, công thức và source field của các chỉ tiêu từ nhiều tài liệu hoặc hỏi người có kinh nghiệm. Workflow này mất khoảng 20–30 phút cho mỗi chỉ tiêu chưa quen thuộc và có thể dẫn đến việc hiểu sai hoặc chọn sai field. Tôi muốn thử nghiệm AI/RAG để rút ngắn thời gian tìm hiểu xuống khoảng ≤5 phút, đồng thời cung cấp definition và nguồn tham chiếu để analyst kiểm tra.

```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```Problem này có thực sự cần AI/RAG không, hay chỉ cần xây dựng một Data Dictionary/Metadata Catalog tốt hơn?


```Làm thế nào để đảm bảo AI trả lời đúng definition và không tạo ra thông tin sai về chỉ tiêu?

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: AI có thể không cần thiết nếu vấn đề chủ yếu nằm ở việc tài liệu và Data Dictionary đang được tổ chức kém. Ngoài ra, nếu AI trả lời sai definition hoặc công thức KPI thì có thể dẫn đến quyết định phân tích sai.
- Tôi sửa gì:Thu hẹp scope từ “AI giải đáp mọi câu hỏi về dữ liệu” thành “AI hỗ trợ tìm kiếm và tổng hợp definition từ các nguồn dữ liệu đã được xác thực”. AI phải cung cấp citation/source để analyst kiểm tra trước khi sử dụng.

### Self-check nộp phần 01
- [ ] Có 5+ problems + top 3 Cards đủ field
- [ ] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [ ] Đã chọn 1 card pitch + câu hỏi challenge
