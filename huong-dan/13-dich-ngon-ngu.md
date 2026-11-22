# 13. Dịch sang ngôn ngữ khác

[← Mục lục](README.md)

Làm tài liệu một lần bằng tiếng Việt, rồi để AI **dịch cả tài liệu và lời đọc video sang 11 ngôn ngữ**. Ảnh, khung đỏ và thứ tự các bước dùng chung với bản gốc, nên bạn chỉ cần xem lại chữ. Mỗi ngôn ngữ xuất ra **Word, PDF, Markdown và video có giọng đọc** riêng.

## 13.1. Trước khi dịch

- Cần **cài AI** (Claude hoặc Gemini), làm một lần ở **Cài đặt › Cài đặt AI**. Xem [7.1](07-ai.md#71-cài-ai-làm-1-lần). App dịch bằng AI bạn đang chọn ở đó.
- Nên **sửa xong bản tiếng Việt** (tên bước, mô tả từng điểm, lời đọc) rồi mới dịch. Sửa sau vẫn được, xem [13.5](#135-sửa-bản-tiếng-việt-sau-khi-đã-dịch).

Các ngôn ngữ có thể dịch:

| Ngôn ngữ | Giọng đọc video |
|---|---|
| 🇬🇧 English, 🇫🇷 Français, 🇪🇸 Español, 🇩🇪 Deutsch, 🇮🇩 Bahasa Indonesia | Có sẵn trên máy (Windows cần cài thêm, xem [13.7](#137-giọng-đọc-cho-bản-dịch)) |
| 🇨🇳 简体中文 (Trung giản thể), 🇯🇵 日本語 (Nhật), 🇰🇷 한국어 (Hàn), 🇹🇭 ไทย (Thái) | Có trên máy, có thể phải tải thêm giọng |
| 🇱🇦 ລາວ (Lào), 🇰🇭 ខ្មែរ (Khmer) | **Chưa có** giọng đọc trên macOS và Windows: video chỉ có chữ, không có tiếng |

## 13.2. Dịch tài liệu

1. Mở tài liệu ở màn **Biên tập**.
2. Ở **cột trái**, dưới khối **Lời đọc**, mục **Ngôn ngữ**, bấm phần chính của nút **🌐 Dịch sang ngôn ngữ khác** (không phải mũi tên ⌄ bên phải). Hộp thoại dịch mở ra. **Lúc này AI chưa dịch gì.**
3. Chọn trong hộp thoại:

| Phần | Ý nghĩa |
|---|---|
| **Dịch sang** | Tích một hoặc nhiều ngôn ngữ. Ngôn ngữ đã dịch trước đó có nhãn **đã có** |
| **Phạm vi** | **Chỉ câu chưa dịch hoặc câu gốc đã sửa** (giữ nguyên câu bạn đã duyệt, nên dùng), hoặc **Dịch lại toàn bộ** |
| **Ghi chú cho người dịch** | Không bắt buộc nhưng rất nên điền: phần mềm gì, ai đọc, từ nào dịch thế nào. Ví dụ *"Phần mềm quản lý trường học, người đọc là giáo viên. 'Sổ điểm' dịch là Gradebook."* Ghi chú được lưu theo tài liệu cho lần dịch sau |
| **Gửi kèm ảnh màn hình** | AI xem ảnh nên hiểu đúng ngữ cảnh hơn. Ảnh gửi đi **đã làm mờ** chỗ bạn che. **Đừng bật nếu ảnh có dữ liệu thật** |

Dòng cuối cho biết **số câu sẽ dịch** và **AI nào sẽ dịch** (Claude hoặc Gemini).

4. Bấm **Bắt đầu dịch**. Đây là lúc AI bắt đầu dịch.
5. Cạnh mỗi ngôn ngữ hiện trạng thái **chờ**, **đang dịch…**, **xong** hoặc **lỗi**. Các ngôn ngữ được dịch lần lượt.
6. Dịch xong, app ở lại màn Biên tập và **mở luôn bản vừa dịch** để bạn xem lại.

> **Nếu bị lỗi giữa chừng** (mất mạng, hết hạn mức của AI…): các ngôn ngữ đã dịch xong **vẫn được lưu**. Hộp thoại chỉ còn tích các ngôn ngữ chưa xong, bấm **Bắt đầu dịch** lần nữa để dịch tiếp. Khi AI báo đang giới hạn số lần gọi, app tự chờ rồi thử lại vài lần trước khi báo lỗi.

## 13.3. AI dịch thế nào

- AI **đọc hết cả tài liệu trước** rồi mới dịch, nên **dịch theo nghĩa và ngữ cảnh**, không dịch từng chữ. Ví dụ "đơn" được hiểu là đơn hàng, đơn xin hay hoá đơn tuỳ tài liệu.
- Dùng **thuật ngữ chuẩn của tài liệu phần mềm** trong ngôn ngữ đích và **thống nhất** trong cả tài liệu. Câu văn theo cách viết hướng dẫn của từng nước (ví dụ tiếng Nhật dùng thể lịch sự).
- **Tên nút, menu, ô nhập, tab, thông báo và mọi chữ lấy từ giao diện phần mềm được giữ nguyên** đúng như trên màn hình, dù giao diện là tiếng Việt, tiếng Anh hay ngôn ngữ khác. Ảnh chụp không được dịch, nên người xem vẫn tìm đúng nút trên ảnh. Ví dụ: *Bấm nút "Lưu"* → *Click the "Lưu" button*.
- AI dịch cả **chữ trên video** (tiêu đề ngắn, nhãn cạnh ô khoanh, lời đọc) và **mọi chữ của cảnh mở đầu, kết thúc video**, kể cả chữ mặc định bạn chưa sửa như "HƯỚNG DẪN SỬ DỤNG", "HOÀN TẤT", "Chúc bạn thao tác thành công!", lời đọc mở đầu và lời đọc kết. Kiểu *Giới thiệu sản phẩm* thì dịch thêm **câu hỏi mở đầu** và **3 nhãn lợi ích** ở cảnh kết.
- Ô nào bạn **xoá trống để ẩn** ở bản gốc (ví dụ dòng chữ nhỏ trên tiêu đề) thì bản dịch **cũng ẩn**. Địa chỉ trang giữ nguyên.
- AI cũng dịch **chữ cố định của file xuất** ("Mục lục", "Bước 1/5", "Lưu ý"…).

## 13.4. Xem và sửa bản dịch

### Chọn bản để xem

Mục **Ngôn ngữ** ở cột trái là một nút có **mũi tên ⌄**, giống nút **Viết lời đọc bằng AI**:
- Bấm **phần chính** của nút để mở hộp thoại dịch (mục 13.2).
- Bấm **mũi tên ⌄** để mở menu **Xem và sửa bản**: **Tiếng Việt (gốc)** và từng bản dịch, mỗi bản có nhãn **"n cần duyệt"** (màu vàng) hoặc **Xong** (màu xanh). Chọn một bản để chuyển sang bản đó. Cuối menu có **Xem bảng song ngữ** và **Xoá bản …**.
- Dưới nút luôn có dòng **"Đang xem: …"** cho biết bạn đang ở bản nào. Có bao nhiêu ngôn ngữ thì mục này vẫn gọn một chỗ, danh sách bước không bị đẩy xuống.

### Màn Biên tập khi đang ở bản dịch

Màn hình **giữ nguyên bố cục như bản Tiếng Việt**, chỉ khác là mỗi ô chứa **bản dịch** và **câu gốc tiếng Việt hiện nhỏ ngay bên dưới** để đối chiếu.

- Phía trên ảnh hiện dòng **"Đang sửa bản … Ảnh và khung đỏ dùng chung với bản gốc, ở đây chỉ sửa chữ."** Bấm **Về bản Tiếng Việt** để quay lại.
- Danh sách bước bên trái có **số màu vàng**: số câu trong bước (hoặc trong mở đầu, kết thúc video) còn cần xem. Dấu tích xanh là đã duyệt hết.
- **Tab "Nội dung bước"**: Tiêu đề bước (A), Mô tả từng điểm (B, theo số khoanh), Ghi chú thêm. Cuối tab có nút **Duyệt bước này**.
- **Tab "Video"**: Mở đầu bước (Tiêu đề ngắn D, Lời đọc mở đầu bước), Từng điểm (Nhãn cạnh ô C, Lời đọc), Lưu ý (nếu bước có). Bố cục và khung đỏ dùng chung với bản gốc nên không có ở đây.
- **Mở đầu video** và **Kết thúc video** (đầu và cuối danh sách bước): có đủ các ô như bản Tiếng Việt (tiêu đề, cụm từ nhấn, dòng chữ nhỏ, dòng phụ, lời chúc, lời đọc…). Giữa màn hình là **cảnh xem trước bằng chữ đã dịch**, cùng nền, màu và kiểu chữ với bản Tiếng Việt. **Tên tài liệu** (trang bìa, tên file) của bản dịch sửa ở phần Mở đầu video. Mỗi phần có nút **Duyệt phần mở đầu** / **Duyệt phần kết thúc**.
- Câu chưa duyệt có **nền vàng**. **Sửa một câu là câu đó được tính là đã duyệt.**
- Ô mà bản gốc để trống hiện mờ với chữ **"Bản gốc để trống"** (hoặc cho biết video sẽ tự đọc gì).
- Thêm, gộp, di chuyển, xoá bước, khung đỏ, làm mờ, cắt ảnh, kiểu video **chỉ sửa ở bản Tiếng Việt**.

Mỗi câu có một nhãn:

| Nhãn | Nghĩa |
|---|---|
| **Máy dịch · chưa duyệt** | AI đã dịch, bạn chưa xem |
| **Đã duyệt** | Bạn đã xem hoặc đã sửa |
| **Cần dịch lại** | Câu tiếng Việt đã sửa sau khi dịch, bản dịch đã cũ |
| **Chưa dịch** | Chưa có bản dịch. Khi xuất, câu này **giữ tiếng Việt** |

### Bảng song ngữ (duyệt nhanh cả tài liệu)

Bấm mũi tên ⌄ ở mục **Ngôn ngữ**, chọn **Xem bảng song ngữ** (hoặc bấm liên kết **Xem bảng song ngữ** ngay dưới nút). Màn này có:
- Bảng hai cột: câu gốc tiếng Việt và bản dịch, **sửa trực tiếp** trong bảng.
- Bộ lọc **Tất cả**, **Chưa duyệt (n)**, **Cần dịch lại (n)** để chỉ xem những câu cần xem.
- Nút **Duyệt** từng câu và **Duyệt tất cả**.
- Bên phải **xem trước** trang tài liệu hoặc **dựng thử một cảnh video** bằng ngôn ngữ đó.
- Bấm **Xong, quay lại biên tập** khi xong.

## 13.5. Sửa bản tiếng Việt sau khi đã dịch

Cứ sửa bản tiếng Việt như bình thường. Câu nào đổi thì bản dịch của câu đó chuyển sang **Cần dịch lại**. Mở lại hộp thoại dịch, để phạm vi **Chỉ câu chưa dịch hoặc câu gốc đã sửa**, bấm **Bắt đầu dịch**: AI chỉ dịch những câu đó, câu bạn đã duyệt giữ nguyên.

Thêm bước mới thì các câu của bước đó là **Chưa dịch**, cũng dịch tiếp theo cách trên.

## 13.6. Xuất bản dịch

Ở màn **Xuất file** có thêm phần **Ngôn ngữ xuất**:

1. Tích các ngôn ngữ muốn xuất (bản gốc **Tiếng Việt** có nhãn **bản gốc**).
2. Ngôn ngữ còn câu chưa duyệt có nhãn **"n câu chưa duyệt"**. Vẫn xuất được, nhưng nên bấm **Xem trước bản dịch** để xem lại trước.
3. Chọn định dạng như bình thường, bấm **Xuất**. Chọn nhiều ngôn ngữ thì app **hỏi thư mục một lần**, **mỗi ngôn ngữ một file**, tên file có đuôi mã ngôn ngữ: `Huong-dan_vi.docx`, `Huong-dan_en.docx`, `Huong-dan_ja.mp4`…

Ngày tháng trong file theo cách viết của ngôn ngữ đó. Chữ Trung, Nhật, Hàn, Thái, Lào, Khmer dùng **font có sẵn của máy** và được ngắt dòng đúng (các ngôn ngữ này không có dấu cách giữa các từ).

## 13.7. Giọng đọc cho bản dịch

Video bản dịch đọc bằng **giọng có sẵn của máy** cho ngôn ngữ đó, app tự chọn giọng tự nhiên nhất.

- **macOS**: có sẵn giọng cho hầu hết ngôn ngữ (ví dụ Samantha tiếng Anh, Tingting tiếng Trung, Kyoko tiếng Nhật, Yuna tiếng Hàn, Kanya tiếng Thái). Muốn giọng hay hơn hoặc thiếu giọng: vào **Cài đặt hệ thống › Trợ năng › Nội dung được đọc › Giọng hệ thống › Quản lý giọng**, tải giọng của ngôn ngữ đó (nên chọn bản **Nâng cao** hoặc **Cao cấp**).
- **Windows**: vào **Settings › Time & language › Speech › Add voices**, thêm ngôn ngữ cần đọc.
- **Giọng VieNeu chỉ đọc tiếng Việt.** Nếu bạn đang dùng VieNeu, bản tiếng nước ngoài **tự chuyển sang giọng máy** của ngôn ngữ đó.
- **Tiếng Lào và Khmer**: macOS và Windows chưa có giọng đọc. Ở màn Xuất, tắt **Giọng đọc thuyết minh** để xuất video có đủ chữ nhưng không có tiếng.
- **Từ điển phát âm** chỉ áp dụng cho bản tiếng Việt.

## 13.8. Xoá một bản dịch

Mở bản dịch đó (mũi tên ⌄ ở mục **Ngôn ngữ**, chọn ngôn ngữ), bấm mũi tên ⌄ lần nữa, chọn **Xoá bản …** rồi xác nhận. Việc này **không hoàn tác được**. Bản tiếng Việt không bị ảnh hưởng.

## 13.9. Mẹo để bản dịch đúng nghĩa

- Luôn điền **Ghi chú cho người dịch**: nói rõ phần mềm làm gì, ai đọc, và các từ quan trọng nên dịch thế nào.
- Bật **Gửi kèm ảnh màn hình** khi ảnh dùng dữ liệu mẫu: AI nhìn màn hình sẽ hiểu đúng hơn.
- Viết bản tiếng Việt rõ ràng, đủ chủ ngữ, tránh viết tắt.
- Với tài liệu gửi ra ngoài, nên nhờ **người biết ngôn ngữ đó** duyệt trong **Bảng song ngữ** trước khi xuất.
- Chi phí AI tăng theo số ngôn ngữ, và nhiều hơn khi gửi kèm ảnh, vì mỗi ngôn ngữ gửi lại cả tài liệu.

[← Trang trước](12-bao-loi-hoi-dap.md) · [Về mục lục](README.md)
