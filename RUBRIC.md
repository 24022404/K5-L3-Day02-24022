# Rubric

Tổng điểm chính: **100** (cá nhân 40 + nhóm 60). Bonus ghi riêng, tối đa **10**.

Phần nhóm: cả nhóm nhận cùng một điểm, trừ thành viên không có đóng góp thực tế trong `TEAM.md` (xem quy tắc bên dưới).

## Phần cá nhân — 40 điểm

Người chấm xem file `report/individual/MSSV_HoTen.md`.

| Tiêu chí | CP | Điểm | Bằng chứng | Điều kiện được điểm / bị trừ |
|---|---|---:|---|---|
| C1 — Scan problem | CP1 | 8 | Mục 2: bảng scan | Đủ 5 problem dạng Job Story, mỗi dòng có dấu hiệu thật đo được: 8. Thiếu dấu hiệu thật ở quá nửa số dòng: tối đa 4. Problem là solution trá hình ("cần chatbot…"): trừ 1/dòng. Dưới 5 problem: tối đa 3 |
| C2 — Top 3 Problem Cards + draft workflow | CP2 | 10 | Mục 3: 3 card + 3 workflow | Mỗi card đủ field và workflow có số phút, bottleneck: 3 điểm/card. Có ghi lại phản biện của AI và đã sửa gì: +1. Bottleneck mơ hồ ("quy trình chậm"): trừ 1/card |
| C3 — Nhật ký phản biện | CP3 | 6 | Mục 4: bảng tham gia, dòng "Pitch" và "Phản biện" | Ghi được câu hỏi mình đã đặt cho người khác và câu hỏi mình nhận được, kèm thay đổi cụ thể sau đó: 6. Chỉ ghi chung chung "đã góp ý": tối đa 2 |
| C4 — Reflection | CP7 | 10 | Mục 4–6 | Nêu rõ vai trò, có ví dụ đổi ý cụ thể, bảng dùng AI chỉ ra được chỗ AI sai và cách sửa, nói được nếu làm lại sẽ đổi gì: 10. Dưới 200 từ hoặc chung chung: tối đa 4. Có dấu hiệu AI viết thay: 0 |
| C5 — Hiểu bài | CP7 | 6 | Mục 6, câu cuối; coach có thể hỏi trực tiếp | Tự giải thích đúng chuỗi problem → workflow → metric → boundary → mức can thiệp → quyết định cho bài của nhóm: 6. Giải thích sai hoặc thiếu mắt xích: 0–3 |
| **Cộng phần cá nhân** | | **40** | | |

## Phần nhóm — 60 điểm

Người chấm xem file `report/team/group_report.md` (giống nhau trong repo của mọi thành viên).

| Tiêu chí | CP | Điểm | Bằng chứng | Điều kiện được điểm / bị trừ |
|---|---|---:|---|---|
| C6 — Hội tụ có lập luận | CP3 | 8 | Mục 2: cluster, cây OST, bảng chấm điểm, lý do chọn/loại | Có cây OST tách đúng opportunity và solution, bảng chấm điểm có lý do, giải thích vì sao loại ít nhất 2 candidate: 8. Chỉ bỏ phiếu không lý do: tối đa 3 |
| C7 — Kiểm chứng + research | CP4 | 10 | Mục 3: assumption map, snapshot/survey, bảng research | Kiểm chứng đúng cách (hỏi hành vi đã xảy ra, không hỏi giả định), có tín hiệu phản bác, research có 2–3 nguồn với link mở được, problem được sửa sau kiểm chứng: 10. Câu hỏi dạng "Bạn có muốn…": trừ 3. Link chết hoặc số liệu không nguồn: trừ 2 |
| C8 — Workflow trước/sau | CP5 | 12 | Mục 4 + `report/assets/` | Workflow hiện tại có actor/input/output/thời gian, bottleneck rõ; workflow tương lai có bước con người kiểm tra, boundary, phương án quay về; có bảng before/after: 12. Thiếu phương án quay về: trừ 3. Thiếu thời gian từng bước: trừ 2 |
| C9 — Problem Statement v0 → v1 | CP5, CP6 | 15 | Mục 5 + mục 7 | Đủ trường; success metric có baseline, target, cách đo; boundary ghi rõ AI không được làm gì; có 3–5 tiêu chí eval; v1 khác v0 và có lý do: 15. Metric không đo được: trừ 5. Không có tiêu chí eval: trừ 3 |
| C10 — Mức can thiệp AI | CP6 | 8 | Mục 6: ma trận, bảng No AI/Rule/Workflow/Agent, AI Canvas, câu hỏi PAIR | Lập luận rõ vì sao không chọn mức đơn giản hơn, AI Canvas chỉ ra đúng dữ liệu cần có: 8. Chọn Agent mà không giải thích vì sao Workflow không đủ: tối đa 3 |
| C11 — Quyết định | CP6 | 7 | Mục 8: 4 rủi ro + quyết định + ngưỡng dừng | Đánh giá đủ 4 rủi ro có lý do, quyết định nhất quán với rủi ro, có ngưỡng dừng đo được và bước tiếp theo cụ thể: 7. Không có ngưỡng dừng: trừ 2 |
| **Cộng phần nhóm** | | **60** | | |

**Tổng điểm chính: 40 + 60 = 100.**

## Bonus — tối đa 10 điểm (ghi riêng)

Bonus là điểm cộng cho **chất lượng bài lab**, không phải điểm phát biểu, giơ tay hay pitching.

| Bonus | Điểm | Bằng chứng |
|---|---:|---|
| B1 — Scan rộng mà vẫn cụ thể: từ 10 problem trở lên, trải đủ 4 lăng kính, mỗi dòng có dấu hiệu thật | +3 | Báo cáo cá nhân mục 2 |
| B2 — Kiểm chứng vượt yêu cầu: từ 5 interview snapshot trở lên hoặc survey từ 20 người trở lên, **và** kết quả làm nhóm sửa problem, metric hoặc quyết định | +4 | Báo cáo nhóm mục 3, phần "Nhóm đã sửa gì" |
| B3 — Bộ eval mẫu: 10 cặp input/đầu ra mong đợi cho bước AI, mỗi cặp chấm theo tiêu chí eval của nhóm | +3 | Báo cáo nhóm mục 7 hoặc file trong `report/assets/` |

## Quy tắc chấm

- Điểm chính tối đa 100. Bonus không tự cộng vào điểm chính và tối đa 10.
- Chấm theo commit cuối cùng trước deadline.
- **Sai tên repo hoặc sai tên file báo cáo** (không theo `MSSV_HoTen.md`): trừ 5 điểm.
- **Thiếu phần nhóm trong repo cá nhân** (không copy `group_report.md` hoặc `TEAM.md`): phần nhóm của người đó bị 0.
- **Không có đóng góp trong `TEAM.md`** hoặc các thành viên khác xác nhận không tham gia: phần nhóm của người đó bị 0.
- **Bịa kết quả phỏng vấn/survey**: C7 bị 0 cho cả nhóm.
- **Báo cáo cá nhân trùng lặp đáng kể với người khác** hoặc do AI viết thay: phần cá nhân bị 0.
- Commit API key, password hoặc thông tin cá nhân của người được phỏng vấn: trừ 5 điểm.
