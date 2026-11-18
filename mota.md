Ý tưởng của nhóm có hướng đi hay, nhưng bỏ hẳn P2 và P3 là điểm yếu lớn nhất. Tôi nghĩ bạn có thể giữ tinh thần "tự do" mà không cần xây lại cả hai phần đó.

## Ưu điểm

- **Liên tưởng do người học tự tạo thường nhớ lâu hơn liên tưởng có sẵn.** Tự chọn vật, tự chọn chỗ đặt là phần thú vị nhất của app gốc, và bạn đang giữ đúng phần đó.
- **Phạm vi gọn.** Bỏ quiz và lịch ôn giúp 3 người làm kịp, và có thời gian làm phần đặt vật thật mượt. Với VR, cảm giác cầm và đặt vật tốt là yếu tố quyết định.
- **Dễ demo và dễ gây ấn tượng.** Người xem thấy ngay "ngôi nhà từ vựng" do chính họ dựng.
- **Không phải thiết kế vị trí đặt cố định cho từng phòng.**

## Nhược điểm

1. **Không có bước tự nhớ lại thì không biết người học có nhớ hay không.** Nghiên cứu về học tập khá nhất quán rằng việc tự gợi nhớ (không nhìn đáp án) hiệu quả hơn nhiều so với xem lại. Nếu chỉ đặt rồi thôi, app dễ trở thành "bày đồ chơi trong nhà ảo". Về sản phẩm, người dùng cũng không có lý do để quay lại ngày hôm sau.
2. **Không chứng minh được MVP có tác dụng.** Không quiz thì không có số liệu, và đây là thứ nhóm cần để thuyết phục người khác.
3. **Đặt tuỳ ý làm mất sức mạnh của phương pháp loci.** Phương pháp này hiệu quả nhờ các vị trí có thứ tự, dễ phân biệt và đã quen thuộc. Đặt lung tung, chồng chéo hoặc ở chỗ khuất thì người học dễ quên chính chỗ mình đặt.
4. **Nhà ảo là nơi lạ.** Người học chưa thuộc không gian đó thì khó dùng nó làm điểm tựa trí nhớ.
5. **Người mới không biết nên liên tưởng thế nào** nếu không có hướng dẫn, và vừa học từ vừa điều khiển VR cũng là tải khá nặng.
6. **Cần kính VR**, nên nhóm người thử sẽ hẹp.

## Hướng để có MVP "ngon"

**Giữ đặt tự do, nhưng thêm một cơ chế tự nhớ lại rất nhẹ thay cho P2 và P3.** Tôi gọi nó là **chế độ che**:

- Khi vào lại căn nhà, từ và nghĩa trên các vật **bị ẩn**, chỉ còn vật thể hiện ra.
- Người học nhìn vật, tự nhớ từ rồi **chạm để lật** xem đáp án. Có thể thêm hai nút "nhớ" và "quên" để ghi lại.

Phần này chỉ tốn thêm một công tắc ẩn/hiện và một nút lật, ít hơn nhiều so với quiz đầy đủ, mà vẫn đem lại lợi ích của việc tự nhớ lại. Đây cũng là lý do để người dùng quay lại căn nhà.

Các điểm còn lại:

1. **Cho phép đặt tự do nhưng có hỗ trợ.** Vật tự bám vào mặt bàn, kệ, tường hoặc sàn để không lơ lửng. Nhà nhỏ (1–2 phòng) với nhiều đồ nội thất dễ nhận ra sẽ làm điểm neo tốt. Cho người dùng đi một vòng làm quen trước khi bắt đầu.
2. **Gợi ý liên tưởng ngay khi đặt.** Một câu hỏi ngắn như "Vật này gợi bạn nhớ gì về nghĩa của từ?" và có thể ghi chú bằng giọng nói. Đây là cách rẻ nhất để biến việc đặt vật thành việc ghi nhớ thật.
3. **Số lượng nhỏ.** Phiên đầu chỉ nên 5–8 từ, mỗi từ có nghĩa, ví dụ và audio. Đừng làm 30 từ ngay.
4. **Đo ngoài app.** Không cần xây quiz trong app: hôm sau cho người thử làm bài kiểm tra ngắn bằng Google Form hoặc giấy. Nhóm vẫn có số liệu mà không tốn công lập trình. Nếu được, so với một nhóm học bằng flashcard.
5. **Lưu bố cục nhà** để lần sau vào lại thấy đúng những gì mình đã dựng.

## Gợi ý chia việc cho 3 người

| Vai | Phụ trách |
|---|---|
| Lập trình VR | Chạy repo gốc, đặt/cầm/bám vật, lưu bố cục, chế độ che |
| Nội dung và học tập | Bộ từ, audio, gợi ý liên tưởng, bài kiểm tra 24h, khảo sát |
| UX và 3D | Thẻ từ dễ đọc trong VR, bộ vật thể, hướng dẫn mở đầu, tổ chức buổi thử |

## So sánh ba phương án

| | A: Đặt tự do thuần | **B: Tự do + chế độ che (đề xuất)** | C: Bản đầy đủ như file trước |
|---|---|---|---|
| Công sức | Thấp | Thấp–vừa | Cao |
| Có tự nhớ lại | Không | Có | Có |
| Chứng minh được hiệu quả | Khó | Được (qua bài kiểm tra ngoài app) | Được |
| Lý do quay lại | Yếu | Khá | Mạnh |
| Hợp với nhóm 3 người | Có | Có | Dễ quá tải |

Tôi khuyên chọn **B**. Nếu muốn, tôi sẽ cập nhật file `.md` theo phương án này, gồm luồng người dùng, dữ liệu, kế hoạch tuần và phân công.
