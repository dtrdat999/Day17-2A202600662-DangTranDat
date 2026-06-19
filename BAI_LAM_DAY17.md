# Lab Assignment Day 17 – Chủ đề bất động sản

**Học viên:** Đặng Trần Đạt<br>
**Mã học viên:** 2A202600662

## 1. Hypothesis quan trọng

**Đối tượng:** Người mua căn hộ lần đầu tại TP.HCM, ngân sách 2–5 tỷ đồng.

**Hypothesis:**

> Người mua căn hộ lần đầu sẽ sẵn sàng để lại thông tin liên hệ và tiêu chí tìm nhà nếu họ được hứa nhận một shortlist 5 căn phù hợp, có giải thích rõ lý do, trong vòng 30 phút.

### Tiêu chí để xác nhận hypothesis

- Ít nhất **20%** người truy cập landing page hoàn tất form nhận shortlist.
- Ít nhất **60%** người nhận shortlist đánh giá kết quả từ **4/5 điểm**.
- Ít nhất **30%** lead yêu cầu tư vấn thêm hoặc đặt lịch xem một căn.

## 2. Cách team đã/đang định làm

Phương án dự kiến ban đầu là xây một website/app tương đối hoàn chỉnh:

- Thu thập và chuẩn hóa nhiều tin đăng bất động sản.
- Xây bộ lọc tìm kiếm, tài khoản người dùng và hệ thống gợi ý bằng AI.
- Tích hợp bản đồ, CRM, chatbot và chức năng đặt lịch xem nhà.
- Sau khi hoàn thiện mới chạy quảng cáo để thu hút người dùng.

Phương án này tốn nhiều thời gian và chi phí trong khi team chưa biết chắc khách hàng có thực sự muốn nhận shortlist cá nhân hóa hay không.

## 3. Ba cách rẻ hơn để test cùng hypothesis

### Cách 1 – Smoke test bằng landing page

- Tạo một landing page với thông điệp: “Nhận 5 căn hộ phù hợp trong 30 phút”.
- Chạy một chiến dịch quảng cáo nhỏ hoặc chia sẻ vào các cộng đồng tìm nhà.
- Yêu cầu khách nhập ngân sách, khu vực và số điện thoại.
- Chỉ số chính: tỷ lệ hoàn tất form.
- Thời gian: 1–2 ngày.
- Ngân sách gợi ý: 500.000–1.000.000 đồng.

### Cách 2 – Concierge MVP

- Nhận tiêu chí của khách qua form hoặc Zalo.
- Thành viên trong team tự tìm tin đăng từ các nguồn hiện có.
- Chọn 5 căn phù hợp, viết lý do lựa chọn và gửi trong vòng 30 phút.
- Sau khi gửi, hỏi khách chấm điểm và chọn căn họ muốn xem.
- Chỉ số chính: điểm hài lòng và tỷ lệ yêu cầu xem nhà.
- Thời gian: 3–5 ngày.

### Cách 3 – Wizard-of-Oz

- Tạo giao diện “AI phân tích độ phù hợp của căn hộ”.
- Khách chọn một căn và đặt câu hỏi như “Vì sao phù hợp?”, “Rủi ro là gì?”.
- Giao diện trông như sản phẩm thật, nhưng team chuẩn bị hoặc trả lời thủ công phía sau.
- Chỉ số chính: điểm tin tưởng, số câu hỏi được gửi và tỷ lệ khách bấm “Muốn xem căn này”.
- Thời gian: 1–2 ngày.

## 4. Prototype

Mở file `index.html` bằng trình duyệt. Trang gồm:

1. Landing page để mô phỏng việc thu lead.
2. Concierge MVP để mô phỏng quy trình gửi shortlist thủ công.
3. Wizard-of-Oz để mô phỏng tính năng AI phân tích bất động sản.

## 5. Cách kết luận sau khi test

- **Đạt cả ba ngưỡng:** tiếp tục xây MVP đơn giản.
- **Có nhiều lead nhưng ít người muốn xem nhà:** cải thiện chất lượng shortlist hoặc thay đổi lời hứa giá trị.
- **Ít người để lại thông tin:** hypothesis chưa đủ mạnh; phỏng vấn lại khách hàng trước khi xây sản phẩm.
- **Khách thích kết quả nhưng không tin phần “AI”:** tập trung vào dữ liệu, nguồn dẫn chứng và chuyên gia thay vì quảng bá công nghệ.

## Kịch bản present ngắn

“Hypothesis quan trọng nhất của nhóm là người mua căn hộ lần đầu sẵn sàng để lại thông tin nếu được nhận một shortlist 5 căn phù hợp trong 30 phút. Ban đầu nhóm định xây một nền tảng có dữ liệu, bộ lọc và AI recommendation hoàn chỉnh. Tuy nhiên, cách đó tốn kém và chưa trực tiếp kiểm chứng nhu cầu. Vì vậy nhóm đề xuất ba test rẻ hơn: landing page để đo nhu cầu, concierge MVP để đo giá trị thực của shortlist, và Wizard-of-Oz để đo mức độ tin tưởng cũng như ý định xem nhà. Nếu conversion đạt 20%, 60% khách chấm từ 4/5 và 30% yêu cầu tư vấn hoặc xem nhà, nhóm mới tiếp tục đầu tư xây MVP.”
