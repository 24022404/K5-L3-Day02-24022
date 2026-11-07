# K5 · L3 · Day 02 — Discovery & Problem Framing

> **Loại bài: Cá nhân + Nhóm.** Một phần làm cá nhân, một phần làm theo nhóm 3–4 người. **Mỗi học viên tự nộp một repo riêng**, trong đó có cả phần cá nhân và bản sao phần nhóm. Xem [SUBMISSION.md](SUBMISSION.md).

Hôm nay bạn chưa xây AI. Hôm nay bạn **tìm đúng bài toán**: đi từ một vấn đề thật quanh mình, vẽ workflow, viết Problem Statement đủ chặt, kiểm chứng với người thật, rồi mới quyết định có nên dùng AI không. Nếu dùng thì ở mức nào: Rule, Workflow hay Agent. Cuối cùng là kết luận **Go / Not Yet / No-Go**.

Lab này đi theo **nửa đầu của mô hình Double Diamond** (Design Council, UK):

```text
     DISCOVER (mở rộng)              DEFINE (thu hẹp)
   ◇ cá nhân scan rộng  ──────▶  ◇ nhóm hội tụ về 1 Problem Statement
   CP1 → CP2                       CP3 → CP4 → CP5 → CP6
```

Đầu ra cuối cùng là **một Problem Statement đã kiểm chứng và một quyết định có lý do**, chưa phải một sản phẩm. Kết luận "không cần AI" vẫn là một kết luận tốt nếu lập luận chặt.

## Mục tiêu học tập

Sau buổi này, bạn làm được:

1. Mô tả một vấn đề theo **actor, workflow, bottleneck, metric**, không bắt đầu từ giải pháp (Job Story, Opportunity Solution Tree).
2. Kiểm chứng một vấn đề bằng **bằng chứng về hành vi đã xảy ra**, không dựa vào ý kiến hay lời khen (The Mom Test).
3. Viết **Problem Statement** có success metric đo được, boundary rõ và tiêu chí đánh giá AI (Lean UX, Google PAIR).
4. Chọn đúng mức can thiệp **No AI / Rule / Workflow / Agent** và ra quyết định theo **4 rủi ro** Value, Usability, Feasibility, Viability (Anthropic, Marty Cagan).

## Thông tin chung

| Mục | Nội dung |
|---|---|
| Khóa / level | K5 · Level 3 (dùng chung, không chia lớp A/B) |
| Ngày học | Day 02 |
| Thời lượng | 4 tiếng (240 phút, gồm 2 lần nghỉ 10 phút) |
| Nhóm | 3–4 người |
| Chuẩn bị | Tài khoản GitHub; một công cụ vẽ workflow (giấy, Mermaid, Excalidraw hoặc FigJam); một trợ lý AI (ví dụ ChatGPT hoặc Gemini) |
| Code | Không có code. Toàn bộ bài làm là file Markdown và hình ảnh |
| Deadline | Lab sáng: 23h59 GMT+7 ngày lab. Lab chiều/tối: 11h59 GMT+7 ngày hôm sau. Chi tiết trong [SUBMISSION.md](SUBMISSION.md) |

## Bắt đầu

1. Bấm **Use this template** để tạo repo cá nhân, đặt tên:

   ```text
   K5-L3-DAY02-HoVaTen-MSSV-DiscoveryProblemFraming
   ```

   Ví dụ: `K5-L3-DAY02-NguyenVanAn-20241234-DiscoveryProblemFraming`.

2. Đổi tên file báo cáo cá nhân `report/individual/MSSV_HoTen.md` thành MSSV và tên của bạn, ví dụ `report/individual/20241234_NguyenVanAn.md`.
3. Đọc tài liệu theo thứ tự dưới đây, rồi làm lần lượt từ CP0 đến CP7.

## Thứ tự đọc

| # | File | Đọc để biết |
|---|---|---|
| 1 | [RULES.md](RULES.md) | Được và không được dùng AI ở đâu, quy định nhóm và nộp muộn |
| 2 | [CHECKPOINTS.md](CHECKPOINTS.md) | 8 checkpoint: làm gì, nộp gì, tự kiểm thế nào |
| 3 | [docs/01-worksheet.md](docs/01-worksheet.md) | Hướng dẫn chi tiết, template và prompt mẫu cho từng checkpoint |
| 4 | [docs/02-deliverable-example.md](docs/02-deliverable-example.md) | Một bài làm mẫu hoàn chỉnh |
| 5 | [RUBRIC.md](RUBRIC.md) | Cách chấm 100 điểm và bonus |
| 6 | [SUBMISSION.md](SUBMISSION.md) | Tên repo, cấu trúc, deadline, checklist trước khi nộp |
| — | [docs/03-international-frameworks.md](docs/03-international-frameworks.md) | Các framework quốc tế mà lab sử dụng, kèm nguồn gốc (đọc thêm) |

## Cấu trúc repo

```text
K5-L3-DAY02-HoVaTen-MSSV-DiscoveryProblemFraming/
├── README.md
├── RULES.md
├── CHECKPOINTS.md
├── RUBRIC.md
├── SUBMISSION.md
├── TEAM.md                          ← nhóm điền chung, mỗi người copy vào repo mình
├── docs/                            ← worksheet, bài mẫu, framework (chỉ đọc)
├── report/
│   ├── individual/MSSV_HoTen.md     ← phần CÁ NHÂN: CP1, CP2, CP7
│   ├── team/group_report.md         ← phần NHÓM: CP3 → CP6 (bản chung của nhóm)
│   └── assets/                      ← ảnh workflow, Mermaid, ảnh survey, ghi chú phỏng vấn
└── src/                             ← lab này không có code (xem src/README.md)
```

## Lịch buổi lab

| Thời gian | Checkpoint | Làm | Giai đoạn |
|---:|---|---|---|
| 15' | CP0 | Đọc bài mẫu | — |
| 25' | CP1 | Cá nhân scan 5+ problems | Discover |
| 35' | CP2 | Top 3 Problem Cards + draft workflow | Discover |
| 10' | — | Nghỉ | |
| 30' | CP3 | Nhóm hội tụ về 1 candidate | Define |
| 30' | CP4 | Kiểm chứng + research giải pháp đã có | Define |
| 45' | CP5 | Workflow trước/sau + Problem Statement v0 | Define |
| 10' | — | Nghỉ | |
| 25' | CP6 | Rule / Workflow / Agent + Problem Statement v1 + quyết định | Define |
| 15' | CP7 | Reflection cá nhân | — |
