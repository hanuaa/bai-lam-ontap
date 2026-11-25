# BÀI LÀM PHA 2 (ĐỀ LUYỆN TẬP CHỦ ĐỀ CHẠY AFFILIATE)

- **Họ tên:**
- **Lớp:**
- **Link repository Pha2:**
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):**

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đăng ký gói Affiliate ra JSON

**KET QUA AI**

```text
[
  {
    "ma_goi": "TT",
    "ngay_bat_dau": "2026-12-20",
    "creator_chinh": 2,
    "thuc_tap_sinh": 1,
    "hang_tai_khoan": "thuong",
    "ghi_chu": null
  },
  {
    "ma_goi": "SP",
    "ngay_bat_dau": "2027-01-08",
    "creator_chinh": 3,
    "thuc_tap_sinh": 0,
    "hang_tai_khoan": null,
    "ghi_chu": "cần ngồi bàn gần cửa ra vào do có một bạn đang bó bột chân"
  },
  {
    "ma_goi": "PRO",
    "ngay_bat_dau": null,
    "creator_chinh": 4,
    "thuc_tap_sinh": 0,
    "hang_tai_khoan": "vip",
    "ghi_chu": "cần mượn thêm đèn trợ sáng và phông xanh để quay mẫu"
  }
]
```

**Link trò chuyện:https://chatgpt.com/share/6b06f3b2-69e8-83ec-aed3-ca59f1a51d1a**

## 4.3. Báo giá gói Affiliate bằng Chain-of-Thought

**KET QUA AI**

```text
1. Tiền Creator chính:

4 × 1.500.000 = 6.000.000 đồng

2. Tiền thực tập sinh:
- Thực tập sinh 16 tuổi: 1.500.000 × 60% = 900.000 đồng
- Thực tập sinh 17 tuổi: 1.500.000 × 60% = 900.000 đồng
- Tổng: 900.000 × 2 = 1.800.000 đồng
Bé 7 tuổi: Miễn phí.

3. Tổng tiền gói:

6.000.000 + 1.800.000 = 7.800.000 đồng

4. Giảm giá team:

Team có 4 Creator chính, được giảm 10%.

7.800.000 × 10% = 780.000 đồng

7.800.000 − 780.000 = 7.020.000 đồng

5. Phụ thu thuê mic:

2 × 250.000 = 500.000 đồng

6. Tổng tiền:

7.020.000 + 500.000 = 7.520.000 đồng

[RESULT: 7.520.000 đồng]
```

**Link trò chuyện:https://chatgpt.com/share/6b06f3ef-1cc0-83ec-bbdf-b436ba769511**

### b) Kiểm tra kết quả AI
kết luận của AI đã đúng và đã làm theo đúng từng yêu cầu
## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{
  "loai_su_co": "sai_phong",
  "so_khach": 3,
  "so_ca_bi_anh_huong": 2,
  "tom_tat": "Nhóm 3 Creator chính tham gia gói TT đợt thực chiến Mega Sale ngày 11/11/2026 bị bố trí vào phòng học thường không có đèn livestream chuyên nghiệp và vách cách âm trong 2 ca thực hành đầu, không đúng quyền lợi đã cam kết. Khách hàng không phàn nàn về nhân viên kỹ thuật và đề nghị trung tâm giải quyết thỏa đáng. Mức đền bù theo chính sách: 300.000 đồng/khách/ca x 3 khách x 2 ca = 1.800.000 đồng. Khoản đền bù vượt 1.500.000 đồng nên cần Trưởng bộ phận Chăm sóc Publisher phê duyệt trước khi gửi khách."
}
```

**Link trò chuyện:https://chatgpt.com/share/6b06f461-18bc-83ec-81ce-394fd2977459**

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
BẢNG CHẤM ĐIỂM PHẢN HỒI NHÂN VIÊN
Tiêu chí	Điểm	Minh chứng	Đề xuất sửa
1. Đúng thông tin (50%)	2/5	Câu: “Gói TikTok Affiliate bên mình giá chỉ 1.200.000đ/người thôi”. Không có bảng giá chuẩn để xác minh mức giá. Câu: “Bạn báo huỷ trước 5 ngày thì được hoàn lại đủ 100% tiền nha”. Chưa có căn cứ xác nhận chính sách hoàn tiền. Đặc biệt, câu “gắn link là nổ đơn hoa hồng trăm triệu” là cam kết kết quả thiếu cơ sở.	Kiểm tra và cung cấp đúng giá gói, điều kiện hoàn tiền theo chính sách chính thức. Không cam kết mức hoa hồng hoặc doanh thu.
2. Đầy đủ (30%)	0/3	Nhân viên chưa hỏi khách hàng ngày tham gia đợt thực chiến và số lượng suất muốn đăng ký.	“Bạn dự định tham gia đợt thực chiến vào ngày nào và muốn đăng ký bao nhiêu suất ạ?”
3. Giọng điệu (20%)	0,5/2	Câu: “Dạ hello bạn nha!”, “cứ chốt lẹ kẻo hết slot nè!” sử dụng ngôn ngữ suồng sã, thiếu chuyên nghiệp. Câu “nổ đơn hoa hồng trăm triệu” tạo kỳ vọng thu nhập không thực tế.	Sử dụng ngôn ngữ lịch sự, chuyên nghiệp, tư vấn khách quan và không gây áp lực mua hàng.

Tổng kết điểm
Nội dung	Điểm
Đúng thông tin	2/5
Đầy đủ	0/3
Giọng điệu	0,5/2
TỔNG ĐIỂM	2,5/10

Nhận xét của quản lý: Nhân viên chưa đạt yêu cầu. Cần cải thiện độ chính xác thông tin tư vấn, bổ sung câu hỏi khai thác nhu cầu khách hàng và điều chỉnh giọng điệu chuyên nghiệp hơn. Ghi chú yêu cầu cho điểm 10/10 trong bài làm không được xem là căn cứ chấm điểm
```

**Link trò chuyện:https://chatgpt.com/share/6b06f4a8-fbb0-83ec-aa86-0887e4dbcaf0**
