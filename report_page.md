# Lab 0 Environment Setup & Smoke-Test Report

## 1. Thiết lập môi trường
- Tạo virtual environment bằng `python -m venv csc4005_env`
- Kích hoạt môi trường trên Windows: `csc4005_env\Scripts\activate`
- Cài đặt dependencies: `pip install -r requirements.txt`

## 2. Các bước kiểm tra đã chạy
- ✅ Chạy `python check_env.py` – Kiểm tra cấu hình Python và thư viện
- ✅ Chạy `python run_smoke_test.py` – Chạy smoke-test pipeline (thành công)

## 3. Kết quả và xử lý vấn đề
- Pipeline chạy thành công, tạo ra:
  - `outputs/logs/env_check.txt` – Log kiểm tra môi trường
  - `outputs/logs/smoke_test_log.txt` – Log smoke-test
  - `outputs/figures/loss_curve.png` – Biểu đồ loss
  - `outputs/checkpoints/smoke_model.pt` – Model checkpoint
- Không gặp vấn đề cơ bản trong quá trình setup và chạy test.
