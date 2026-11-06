# Báo cáo cá nhân — Day 01: Lọc tin nhắn rác bằng ML, DL, Embedding và LLM

> Đổi tên file này thành `MSSV_HoTen.md` của bạn, ví dụ `2A20260000_NguyenVanAn.md`, rồi điền từng mục. Xoá các dòng hướng dẫn in nghiêng khi xong.

- **MSSV:**2A202604092
- **Họ và tên:**Trần Văn Tuấn
- **SEED** (in ở ô đầu notebook):5906

## 1. Bằng chứng

| Tệp | Có? |
| --- | --- |
| [`day01_lab.ipynb`](day01_lab.ipynb) — notebook đã chạy, còn output | x |
| [`lab1_report.json`](lab1_report.json) — do ô "Báo cáo cuối" sinh ra | x |
| [`hand_calc.jpg`](hand_calc.jpg) — ảnh tính tay có các bước | x |

## 2. Kết quả chính

SEED=5906 · thử thách #0
Bộ kiểm tra: 4/4 đạt
  ✅ 1.1 vectorize
  ✅ 1.2 sigmoid / predict_proba
  ✅ 1.3 train_logreg
  ✅ 1.4 metrics

Dự đoán đã ghi:
  [16:49:38] 0.9: precision cao hơn. Vì các spam thường có các từ như buy, shop, .. nên dùng đánh giá dựa trên các từ có thể đúng
Thiếu dự đoán: ['ml_f1', 'ml_lr', 'dl_curve', 'dl_relu', 'emb_search', 'emb_tricky', 'llm_models', 'llm_fewshot', 'tradeoff', 'hard_eval']

💾 Đã lưu lab1_report.json (chỉ chứa SEED, không chứa MSSV)

## 3. Dự đoán và thực tế

*Chọn 3 dự đoán `predict(...)` lệch nhiều nhất so với kết quả. Mỗi cái: bạn đoán gì, ra gì, vì sao lệch.*

## 4. Phân tích 50 case khó

*Model nào tụt nhiều nhất, ở nhóm case nào? Nêu 2 case cụ thể và cơ chế khiến model sai.*

## 5. Thử thách cá nhân

*Đề theo SEED của bạn, cách làm, kết quả, giải thích.*

## 6. Phương án cho sản phẩm thật

*Với yêu cầu p95 < 50 ms/tin cho 10 triệu SMS/ngày: chọn phương án nào, dẫn số liệu nào, chấp nhận đánh đổi gì.*

## 7. AI log và điều đã học

*Mỗi lần dùng AI: hỏi gì, nhận gì, bạn sửa gì. Sau đó 2–3 câu: điều bạn hiểu ra hôm nay mà trước đó chưa hiểu.*
