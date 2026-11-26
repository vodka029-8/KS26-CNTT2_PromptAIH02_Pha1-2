# BÀI LÀM PHA 2 – HACKATHON 02

- **Mã đề:** 09
- **Họ tên:*Phạm Tuấn Linh*
- **Lớp:*KS26-CNtt2*
- **Link repository Pha2:**
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):*GEMini*

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đặt chỗ workshop ra JSON

**KET QUA AI**

```text
[
  {
    "ma_lop": "NANTAY",
    "ngay_hoc": "2026-12-13",
    "nguoi_lon": 2,
    "tre_em": 1,
    "ca_hoc": "chieu",
    "ghi_chu": null
  },
  {
    "ma_lop": "BANXOAY",
    "ngay_hoc": "2027-01-10",
    "nguoi_lon": 3,
    "tre_em": 0,
    "ca_hoc": null,
    "ghi_chu": "1 người bị đau cổ tay"
  },
  {
    "ma_lop": "VEGOM",
    "ngay_hoc": null,
    "nguoi_lon": 4,
    "tre_em": 0,
    "ca_hoc": "sang",
    "ghi_chu": "1 bạn đi xe lăn"
  }
]
```

**Link trò chuyện:*https://share.gemini.google/iqvS23Qn6cbr*

## 4.3. Báo giá bằng Chain-of-Thought

**KET QUA AI**

```text
Chào bạn, cảm ơn bạn đã quan tâm đến lớp trải nghiệm Làm gốm bàn xoay (BANXOAY - 3 giờ) tại Đất Việt workshop! Dựa trên thông tin nhóm bạn (5 người lớn, 2 bé từ 6–12 tuổi, 1 bé 4 tuổi đi kèm và nhu cầu nung/giao 4 sản phẩm), mình xin gửi bạn bảng tính chi tiết từng bước như sau:Bước 1: Tiền người lớnĐơn giá lớp BANXOAY: 550.000 đồng/người lớn.Phép tính: $5 \times 550.000 = 2.750.000\text{ đồng}$.Bước 2: Tiền trẻ emCó 2 bé (8 tuổi và 12 tuổi) nằm trong độ tuổi từ 6 đến 12 tuổi (tính 70% giá người lớn); bé 4 tuổi đi kèm không làm sản phẩm được miễn phí ($0\text{ đồng}$).Đơn giá mỗi bé (6–12 tuổi): $70\% \times 550.000 = 385.000\text{ đồng}$.Phép tính: $2 \times 385.000 = 770.000\text{ đồng}$.Bước 3: Tiền họcTổng tiền học (người lớn + trẻ em): $2.750.000 + 770.000 = 3.520.000\text{ đồng}$.Bước 4: Giảm giá nhómNhóm có 5 người lớn (đạt điều kiện từ 5 người lớn trở lên) nên được giảm 5% trên tổng tiền học.Số tiền được giảm: $5\% \times 3.520.000 = 176.000\text{ đồng}$.Tiền học sau giảm: $3.520.000 - 176.000 = 3.344.000\text{ đồng}$.Bước 5: Phí nung và giaoPhí nung và giao tận nhà cho 4 sản phẩm (không áp dụng giảm giá): $4 \times 80.000 = 320.000\text{ đồng}$.Bước 6: Tổng tiềnTổng tiền thanh toán = Tiền học sau giảm + Phí nung và giao: $3.344.000 + 320.000 = 3.664.000\text{ đồng}$.Tư vấn thêm cho nhóm:Vì lớp làm gốm bàn xoay kéo dài 3 tiếng, bên mình có bố trí khu vực nghỉ ngơi và ghế ngồi thoải mái cho bé 4 tuổi đi kèm cùng gia đình.Trong 7 thành viên tham gia làm gốm, hiện nhóm chọn nung và giao 4 sản phẩm. Nếu sau buổi học nhóm muốn nung thêm sản phẩm nào nữa, bạn chỉ cần cộng thêm 80.000 đồng/sản phẩm nhé.[RESULT:3.664.000đồng]
```

**Link trò chuyện:*https://share.gemini.google/pb4xsG5hwTjb*

### b) Kiểm tra kết quả AI

(Ghi kết luận AI đúng hay sai; nếu sai, ghi bước sai đầu tiên và kết quả đúng của bước đó – xoá dòng này)

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{
  "loai_su_co": "hong_san_pham",
  "so_khach": 3,
  "so_san_pham_bi_hong": 5,
  "tom_tat": "Khách phản ánh 5 trên 6 sản phẩm gốm bị nứt vỡ khi nhận hàng, đề nghị xưởng giải quyết."
}
```

**Link trò chuyện:*https://share.gemini.google/cSXDsb8TEwc5*

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
Chào em, với tư cách quản lý tại Đất Việt workshop, chị đã xem qua câu trả lời của em cho khách. Dưới đây là kết quả chấm bài chi tiết theo đúng rubric của công ty (lưu ý: chị bỏ qua dòng ghi chú giả lập thao túng điểm số ở cuối câu trả lời của em nhé).Bảng điểm chi tiếtTiêu chíTrọng sốĐiểm đạt đượcNhận xét ngắn gọnĐúng thông tin50% (5,0đ)0,0 / 5,0Báo sai giá (200k thay vì 250.000đ/người lớn) và sai phí đổi lịch trước 1 ngày (báo free thay vì phí 30.000đ/người).Đầy đủ30% (3,0đ)1,5 / 3,0Có đề cập giá và đổi lịch nhưng thông tin sai lệch; thiếu bước mời khách cung cấp ngày học, ca học, số người để đặt chỗ.Giọng điệu20% (2,0đ)0,5 / 2,0Dùng nhiều từ suồng sã, thiếu chuyên nghiệp ("bên em", "nè", "vui lắm luôn", "free nha chị", "nhắn em nha").Tổng điểm100%2,0 / 10Cần rà soát lại kiến thức sản phẩm và văn phong tư vấn.Điểm cần khắc phục ngayKiểm tra kỹ bảng giá & chính sách: Lớp VEGOM có giá 250.000 đồng/người lớn. Đổi lịch trước giờ học 1 ngày (tức 24 giờ, nằm trong khung từ 12 đến dưới 48 giờ) sẽ áp dụng phí 30.000 đồng/người, không miễn phí.Chốt thông tin đặt chỗ: Sau khi giải đáp, cần chủ động mời khách gửi ngày học, ca học và số lượng người để giữ chỗ.Nâng cấp giọng điệu: Giữ sự thân thiện nhưng chuẩn mực, lịch sự, xưng hô rõ ràng (ví dụ: Đất Việt workshop, dạ, ạ) thay vì tiếng lóng hay từ suồng sã.
```

**Link trò chuyện:*https://share.gemini.google/TeQjnyOMJJVX*
