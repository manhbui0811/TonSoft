# TonDaisy — Phần mềm quản lý tiệm cho thuê & bán trang phục

**Từ lúc khách đặt váy đến lúc trả đồ, hoàn cọc, chốt lãi lỗ: một phần mềm lo hết.**

Dành cho tiệm **váy cưới, áo dài, vest, trang phục biểu diễn, phụ kiện cho thuê**. Cài 1 file, dùng offline trên Windows, dữ liệu nằm trên máy của bạn.

---

## 1. Cho thuê: trái tim của phần mềm

### Lập đơn thuê nhanh
- Chọn món, chọn **ngày nhận – ngày trả** (nút nhanh +1 / +2 / +3 ngày), hệ thống tự tính tiền = giá thuê/ngày × số ngày × số lượng.
- Cho nhập ngày quá khứ hoặc tương lai, phù hợp khách đặt trước hoặc nhập bù.
- **Sửa giá thuê từng dòng**, giảm giá từng món hoặc cả đơn.
- Thuê nhiều món, nhiều số lượng trong một đơn; đơn đã giao đồ vẫn **thêm / sửa / xóa món** (chỉ khóa món đã trả).
- Tìm theo tên, mã sản phẩm, SKU hoặc **quét mã vạch**; phím tắt **F2** (tìm) và **F9** (thanh toán).

### Lịch thuê trực quan, không lo trùng
- Lưới **ngày × sản phẩm** xem theo tuần, tô màu theo trạng thái: **Đặt trước · Đang thuê · Đã trả · Quá hạn · Đã bán**.
- Rê chuột ra danh sách đơn trong ngày, bấm vào xem chi tiết từng dòng thuê.
- Hiện **tất cả sản phẩm cho thuê** kể cả chưa có lịch, kèm số lượng sở hữu.
- **Cảnh báo thiếu hàng / trùng ngày** ngay lúc lập đơn (chỉ cảnh báo, bạn vẫn quyết định được).
- **Ngày đệm giặt / ủi** tự chừa sau mỗi lượt thuê.

### Theo dõi đồ đang ở ngoài
- Danh sách **Đang thuê & quá hạn**: món quá hạn xếp đầu, tô đỏ «Quá N ngày», món sắp đến hạn được đánh dấu.
- Có thể **gia hạn** dòng thuê.

### Nhận trả đồ & quyết toán cọc trong một hộp
- Trả **đủ hoặc trả một phần**, ghi chú tình trạng lúc trả.
- **Tự gợi ý phí trễ hạn** = số ngày trễ × phí trễ/ngày × số lượng; thêm **phí hư hỏng / mất** nếu cần.
- Tự tính: đã thanh toán – tiền đơn – phí phát sinh = **hoàn lại khách** hoặc **khách trả thêm**.
- Khách trả thêm: hiện luôn **mã QR chuyển khoản**; hoàn cọc: chọn tiền mặt hoặc chuyển khoản.
- Lưu **giấy tờ giữ lại** (CCCD, bằng lái…) của khách.

### Cọc rõ ràng, không nhầm tiền
- Nhận cọc **nhiều lần**; cọc cấn vào tiền đơn, phần dư hoàn khách.
- Xem từng khoản **đã thu / hoàn**; **hủy khoản nhập nhầm** (bắt buộc ghi lý do).
- Hủy đơn đã thu cọc đi đúng quy trình hoàn / giữ cọc, không thất thoát.

### Vừa thuê vừa bán
- **«Mua luôn»**: khách đang thuê muốn mua, chọn số lượng, giá bán và % trừ tiền thuê đã tính; xem trước số phải trả.
- **Thanh lý** món cũ ngay ở POS; mua một phần thì tự tách dòng thuê.
- Bán **phụ kiện** (hoa cài áo, kẹp tóc, găng tay…) có kho, bán kèm **dịch vụ** (giặt ủi, giao nhận…).

---

## 2. Bán hàng & thanh toán (POS)

- **Nhiều đơn mở cùng lúc**: tạm cất đơn này, mở đơn khác, tìm lại đơn đang mở theo SĐT, tên, mã đơn.
- **Gắn khách** (hoặc để khách vãng lai), tạo khách mới ngay trong đơn.
- **Giao hàng**: người nhận, SĐT, địa chỉ, phí giao. **Hẹn ngày giờ nhận**.
- Thanh toán **tiền mặt**, **chuyển khoản bằng mã VietQR** hiện ngay trên màn hình, hoặc **thẻ trả trước** của khách; dùng **điểm tích lũy** để trừ tiền.
- **Thu thiếu = đặt cọc đơn**, thu nhiều lần, thu nốt rồi hoàn thành.
- Thu vượt thì **hoàn phần thu vượt**; hủy khoản nhập nhầm có lý do.
- Nhận tại quầy, thu đủ: **đơn tự hoàn thành**. Đơn cọc / hẹn / giao hàng: bấm **Hoàn thành** có xác nhận.
- **Khuyến mại tự áp** vào đơn, hiển thị rõ số tiền giảm, bỏ được cho từng đơn.
- **Cảnh báo thiếu hàng** dạng banner, không chặn bán.
- Hủy đơn (chưa thu: hủy nhẹ; đã thu: hoàn hoặc giữ cọc kèm lý do), **mở lại đơn** đã hoàn thành.

---

## 3. Lịch sử đơn & hủy / hoàn hàng

- Tra cứu đơn đã hoàn thành / đã hủy theo mã đơn, SĐT, tên khách, khoảng ngày, ngày nhận; có **thanh tổng hợp** và phân trang.
- Xem chi tiết đơn, các khoản thanh toán, khuyến mại và điểm đã dùng, **in lại phiếu**.
- **Hủy / hoàn từng dòng** bằng phiếu hoàn: chọn số lượng, ghi lại kho, lý do, phương thức hoàn, số tiền giữ lại; xem trước trước khi lập, hủy phiếu có lý do.
- Hủy / hoàn **tự hoàn điểm** đã tích.

---

## 4. Khách hàng & chăm sóc khách quen

- Hồ sơ khách: tên, SĐT, ngày sinh, địa chỉ, ghi chú; tìm theo SĐT / tên; ẩn / hiện / xóa.
- Xem **lịch sử đơn** của từng khách.
- **Tích điểm – đổi điểm**: cấu hình số tiền/điểm, giá trị điểm, điểm tối thiểu để dùng, tối đa % đơn được trả bằng điểm; xem **lịch sử điểm**; cộng / trừ điểm tay.
- **Ví trả trước**: nạp, trả lại, điều chỉnh, hủy lần nạp, xem lịch sử; khách dùng ví để thanh toán.
- **Khuyến mại tự động**: giảm %, giảm tiền, tặng sản phẩm, miễn phí giao hàng; áp theo cả đơn, danh mục, mẫu hoặc sản phẩm; đặt đơn tối thiểu, thời gian chạy, độ ưu tiên; mỗi đơn tự chọn chương trình lợi nhất.

---

## 5. Sản phẩm, kho & nhập hàng

### Sản phẩm / dịch vụ
- Sản phẩm **nhiều phân loại** (màu, size…) với nhãn tự do như «Đen / 38»; mỗi phân loại có SKU, giá và cảnh báo riêng.
- Phân biệt **Bán** và **Cho thuê**: món thuê có **giá thuê/ngày** (riêng từng phân loại), **cọc gợi ý**, **phí trễ/ngày**, **giá bán lại**.
- **Dịch vụ** không cần kho, cho sửa giá trên đơn.
- Quản lý **danh mục**, ẩn / hiện, lọc theo danh mục, trạng thái, loại.
- **Nhập sản phẩm hàng loạt từ Excel**: có file mẫu, xem trước từng dòng (thêm mới / cập nhật / lỗi), nhập lại không bị nhân đôi.
- **Danh mục và sản phẩm mẫu ngành cho thuê** nạp sẵn lần đầu: váy cưới, áo dài, vest, đồ biểu diễn, phụ kiện thuê, phụ kiện bán, phí dịch vụ.

### Kho
- Xem **Tồn · Giữ · Còn bán / sẵn sàng**; cảnh báo **sắp hết / hết / tồn âm** bằng màu.
- **Nhập kho, xuất dùng, hao hụt**, **kiểm kho** (xem chênh lệch trước khi ghi), **sổ cái** mọi biến động.
- Quản lý **vật tư** (túi đựng đồ, móc áo, giấy lót, nước giặt, tem…).
- Món thuê tính theo **số lượng**: còn trống = tồn − số đang giữ chỗ chồng ngày.

### Nhập hàng
- Phiếu nhập: nháp → nhận hàng (tự cộng kho, tự ghi chi) → hủy có lý do.
- **Nhập dòng hàng từ Excel**; quản lý **nhà cung cấp**.
- **In phiếu nhập hàng**.

### Tem mã vạch
- In **Code128** theo SKU, chọn khổ tem (tem cuộn hoặc nhiều tem trên A4), in tên / giá / phân loại, xem trước, nhập số tem theo tồn.

---

## 6. In ấn

Mỗi loại phiếu tự cấu hình **tên phiếu, đầu phiếu, cuối phiếu, khổ giấy (K80 / A5), số liên**, xem trước khi gõ; chọn máy in qua hộp thoại Windows.

| Phiếu | Điểm nổi bật |
|---|---|
| Phiếu thuê | Món × số lượng, ngày nhận / trả, giấy tờ giữ, tiền thuê, cọc; **điều khoản thuê tự soạn**; tự in khi giao đồ |
| Phiếu trả đồ | Món đã trả, ngày trễ, quyết toán cọc; tự in khi nhận trả đồ |
| Hóa đơn / tạm tính / in lại | Tổng cộng, đặt cọc, còn lại hoặc trả lại khách, điểm tích lũy; tự in khi hoàn thành; in kèm QR |
| Chuẩn bị đơn | Cho khâu chuẩn bị, địa chỉ giao, tiền còn phải thu |
| Phiếu hoàn / hủy | Lý do, tiền hoàn / giữ lại |
| Phiếu nhập hàng | Nhà cung cấp, giá nhập, thanh toán |

Nút **In** ở mỗi đơn: bấm 1 lần là in đúng loại phiếu bạn chọn.

---

## 7. Thu chi & báo cáo

- **Sổ thu chi**: ghi khoản thu / chi ngoài đơn (điện nước, mặt bằng, marketing, góp vốn, thanh lý…); bán hàng và nhập hàng **tự ghi sổ**; không xóa, chỉ **hủy kèm lý do**; danh mục thu chi tự quản lý.
- **Dashboard**:
  - *Cho thuê:* đang thuê, đến hạn, quá hạn, cọc đang giữ; doanh thu **thuê vs bán**, top 5 sản phẩm, **tỉ lệ lấp đầy**.
  - *Tổng quan:* doanh thu thực tế / dự kiến / còn lại, biểu đồ theo ngày, thu theo hình thức, dòng tiền, đơn còn thiếu tiền, **ghi chú cuối ngày**.
  - *Kho & bán chạy:* tồn hiện tại, bán chạy theo sản phẩm và phân loại, hàng tồn chậm.
  - *Thu chi & lợi nhuận:* thu / chi theo danh mục, **lợi nhuận theo kỳ** (chỉ chủ quán xem).
- **Xuất báo cáo ra Excel** (theo kỳ và theo ngày).

---

## 8. Quản trị, bảo mật, tiện ích

- **Đăng nhập & phân quyền**: chủ quán (toàn quyền) và nhân viên; tạo vai trò riêng, tick từng quyền; nhân viên không thấy lợi nhuận, thu chi nếu bạn không cho.
- Mật khẩu **băm an toàn**, tự khóa tạm khi nhập sai nhiều lần, phiên tự hết hạn.
- **Sao lưu, khôi phục, đổi vị trí dữ liệu** chỉ vài cú bấm, luôn có hộp xác nhận.
- **VietQR**: chọn ngân hàng + số tài khoản, QR sinh ngay trên máy, không cần mạng, không nhập mật khẩu ngân hàng.
- Đặt **tên hiển thị** quán ở menu; **giao diện sáng / tối**; giao diện tiếng Việt toàn bộ.
- Không xóa mất dữ liệu: hủy kèm lý do hoặc ẩn đi, truy vết được ai làm gì.
- **Kích hoạt bản quyền**, kiểm tra trạng thái, xuất / nhập mã kích hoạt.
- Dùng **offline**, không mở cổng ra ngoài, dữ liệu không rời khỏi máy bạn.

---

## Gói chào bán gợi ý

> **TonDaisy — quản lý tiệm cho thuê trang phục trọn gói**
> Thuê · bán · cọc · lịch · kho · khách quen · in phiếu · thu chi · báo cáo.
> Cài 1 file, dùng offline, chạy trên Windows 10/11.
> 🎁 Dùng thử miễn phí (chưa kích hoạt: tối đa 200 đơn hoàn thành mỗi tháng).

**Lưu ý khi chào bán:** phiếu in là phiếu nội bộ, chưa phải hóa đơn điện tử theo quy định thuế. Phần mềm chạy trên Windows, chưa có bản điện thoại / web. Giá, gói bản quyền, hỗ trợ sau bán bạn tự bổ sung.
