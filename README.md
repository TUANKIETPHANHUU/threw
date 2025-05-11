# ĐỀ TÀI: DỰ ĐOÁN MỨC ĐỘ BỆNH TIM

**Môn học**: Khai Phá Dữ Liệu  
**Giảng viên hướng dẫn**: TS. Nguyễn Ngọc Thủy(1990)

---

## Giới thiệu

Đây là một dự án học tập trong môn *Khai Phá Dữ Liệu*, nhằm xây dựng một hệ thống dự đoán **mức độ bệnh tim** dựa trên dữ liệu đầu vào từ người dùng. Mô hình sử dụng các thuật toán học máy hiện đại để phân loại tình trạng tim mạch thành 4 cấp độ, từ không có bệnh đến mức độ nặng.

---

##  Mục tiêu

- Phân tích dữ liệu y tế có sẵn để phát hiện các yếu tố ảnh hưởng đến bệnh tim.
- Xây dựng mô hình học máy có thể dự đoán mức độ bệnh tim.
- Triển khai một ứng dụng web đơn giản để người dùng nhập dữ liệu và xem kết quả dự đoán trực tiếp.

---

##  Mức độ bệnh tim được chia thành 4 cấp:

- `0`: Không có bệnh
- `1`: Mức độ nhẹ
- `2`: Mức độ trung bình
- `3`: Mức độ nặng

---

## 🛠️ Công nghệ & Thư viện

- **Python**
- **TensorFlow / Keras** – Xây dựng và huấn luyện mô hình học sâu.
- **Streamlit** – Giao diện người dùng web.
- **Pandas, NumPy** – Xử lý dữ liệu.
- **Scikit-learn** – Tiền xử lý và đánh giá mô hình.

---

## ⚙️ Cách chạy dự án

### 1. Cài đặt thư viện

```bash
pip install -r requirements.txt
