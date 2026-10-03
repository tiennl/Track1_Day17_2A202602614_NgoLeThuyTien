# Chặng 1 — Đặt giả thuyết (Case A)

## 1. Solution — Gỡ solution khỏi hình thức cụ thể

**Case đã chọn:** Case A — AI Tutor: Diagnostic Refresher

**Solution directive:**
Thêm nút “Tôi vẫn chưa hiểu” vào bài học. Khi học viên bấm nút, AI Tutor sử dụng nội dung bài hiện tại, các câu trả lời gần đây và lịch sử học tập để:

1. Đặt 2–3 câu hỏi chẩn đoán ngắn.
2. Chọn một khái niệm nền để học viên ôn lại.
3. Tạo một phần giải thích ngắn.
4. Đưa học viên trở về bài đang học.

**Capability trung tính:**
Khả năng tự động phát hiện, chẩn đoán lỗ hổng kiến thức nền tảng của người học ngay tại thời điểm họ gặp khó khăn và cung cấp kiến thức bổ trợ tương ứng để giúp họ tiếp tục tiếp thu bài học hiện tại.

## 2. Change — Làm lộ chuỗi thay đổi được kỳ vọng

**Chuỗi thay đổi:**
Solution → Người học nhận ra lỗ hổng kiến thức cụ thể của mình → Người học tiếp thu và củng cố khái niệm nền bị thiếu → Outcome (Người học hiểu được nội dung bài đang học và duy trì mạch học).

**Các thay đổi được kỳ vọng:**

1. Người học chuyển từ trạng thái "bế tắc/không hiểu" sang trạng thái chủ động tìm kiếm sự giúp đỡ hoặc báo hiệu khó khăn.
2. Người học nhận diện được lý do tại sao họ không hiểu bài (biết chính xác mình đang thiếu kiến thức nền nào).
3. Người học tự tin tiếp tục hoàn thành bài học thay vì bỏ cuộc hoặc tốn nhiều thời gian tự tìm tài liệu đọc lại một cách mù quáng.

## 3. Actor — Xác định các nhóm người có liên quan

| Actor                    | Họ đang làm gì?                                | Pain hoặc hậu quả có thể có                                                                    | Họ hưởng lợi thế nào?                                                           |
|--------------------------| ---------------------------------------------- | ---------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| **Học viên**             | Đang học bài giảng/đọc tài liệu trên hệ thống. | Không hiểu bài do hổng kiến thức nền, mất thời gian tự tra cứu, dễ nản và bỏ học.              | Tiết kiệm thời gian tự tra cứu, duy trì được mạch học, hiểu bài sâu hơn.        |
| **Lab Coach**            | Hỗ trợ học viên, trả lời câu hỏi thắc mắc.     | Phải trả lời đi trả lời lại các câu hỏi về kiến thức rất cơ bản đáng lẽ học viên phải nắm rồi. | Giảm tải câu hỏi lặp lại, tập trung thời gian hướng dẫn các kiến thức nâng cao. |
| **Người soạn bài giảng** | Xây dựng nội dung khóa học.                    | Khóa học có tỷ lệ drop-out cao ở những bài khó.                                                | Tăng tỷ lệ hoàn thành khóa học, chất lượng đầu ra của học viên tốt hơn.         |

**Actor nhóm chọn để điều tra trước:** Học viên

**Vì sao chọn nhánh này thay vì actor khác:** Vì Học viên là người trực tiếp trải nghiệm sự "không hiểu" (pain chính), và cũng là người trực tiếp tương tác với solution để vượt qua rào cản học tập. Nếu hành vi của Học viên không thay đổi (không tìm cách vượt qua sự không hiểu), thì outcome cuối cùng sẽ không thể đạt được.

## 4. Situation & Job — User đang cố làm gì trong tình huống nào?

**Mô tả Situation & Job:**
Khi đang đọc một khái niệm mới hoặc giải một bài tập khó, Học viên đang cố hiểu trọn vẹn bài học hiện tại bằng cách đọc đi đọc lại hoặc tự loay hoay tra cứu tài liệu cũ một cách mất phương hướng.

**JTBD Hypothesis:**
Khi không thể hiểu một nội dung bài học mới, tôi muốn nhanh chóng xác định được phần kiến thức nền tảng nào tôi đang thiếu hụt, để có thể ôn lại đúng trọng tâm và tiếp tục mạch học mà không bị nản chí hay mất thời gian.

## 5. Pain — Viết các cách giải thích cạnh tranh

**Pain Hypothesis A:**
Khi học bài mới mà không hiểu, Học viên gặp khó khăn trong việc tìm cách vượt qua vì họ **không biết mình đang thiếu hụt kiến thức nền tảng nào (không xác định được lỗ hổng)**, dẫn đến cảm giác chán nản, phải học vẹt hoặc bỏ dở bài học.

**Pain Hypothesis B — cách giải thích cạnh tranh:**
Khi học bài mới mà không hiểu, Học viên gặp khó khăn trong việc tra cứu lại kiến thức vì **tài liệu cũ quá phân tán hoặc khó tìm lại đúng đoạn cần thiết**, dẫn đến việc họ tốn quá nhiều công sức tìm kiếm, làm gián đoạn mạch học.

**Giả thuyết nhóm chọn để điều tra trước:** Giả thuyết A
**Lý do chọn:** Việc "không biết mình không biết cái gì" (không xác định được lỗ hổng) thường là rào cản gốc rễ và lớn nhất. Nếu học viên biết rõ mình quên gì (như Giả thuyết B), họ vẫn có cách tự tra cứu hoặc search Google khá dễ dàng (workaround tồn tại). Nhưng nếu rơi vào Giả thuyết A, họ thực sự bế tắc.

## 6. Evidence — Xác định điều cần tìm trước khi viết câu hỏi

| Cần kiểm tra            | Evidence làm nhóm tin hơn                                                                                | Evidence làm nhóm nghi ngờ hoặc bác bỏ                                                   |
| ----------------------- | -------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| **Situation có thật**   | Học viên kể được ví dụ cụ thể về lần gần nhất họ phải dừng lại giữa chừng vì đọc bài không hiểu.         | Học viên bảo lúc nào học cũng hiểu hết, hoặc không hiểu thì bỏ qua luôn không quan tâm.  |
| **Pain có ý nghĩa**     | Học viên mô tả cảm giác bực bội, chán nản khi không biết hỏi ai, không biết bắt đầu tìm hiểu lại từ đâu. | Học viên cảm thấy việc không hiểu là bình thường, thoải mái với việc học vẹt để qua bài. |
| **Workaround tồn tại**  | Đã từng dùng ChatGPT, ráo riết tra Google, nhắn tin hỏi bạn bè/thầy cô để tìm ra khái niệm bị hổng.      | Chỉ nhún vai rồi đọc tiếp đoạn khác, không có bất kỳ hành động nào để giải quyết vấn đề. |
| **Consequence tồn tại** | Tốn hàng giờ đồng hồ loay hoay, điểm quiz cuối chương thấp, hoặc phải bỏ học tạm thời vì stress.         | Điểm vẫn cao, vẫn qua môn nhẹ nhàng mà không cần hiểu sâu.                               |
| **Pattern có lặp**      | Việc này xảy ra thường xuyên mỗi khi qua chương mới hoặc học môn khó.                                    | Chỉ xảy ra đúng 1 lần do hôm đó mệt hoặc buồn ngủ.                                       |

## Chốt Problem Hypothesis và park solution

**Problem Hypothesis nhóm mang sang Chặng 2:**
Học viên trực tuyến thường xuyên gặp bế tắc khi tiếp thu kiến thức mới do bị hổng kiến thức nền tiên quyết, nhưng rào cản lớn nhất là họ lại không thể tự nhận diện được phần kiến thức bị hổng đó là gì. Điều này khiến họ mất nhiều thời gian loay hoay không biết tra cứu từ đâu, dẫn đến dễ nản lòng và bỏ cuộc.

**Điều gì phải đúng để giả thuyết đứng vững:**
Học viên thực sự có động lực muốn hiểu sâu bài học (chứ không chỉ cần điểm qua môn). Khi gặp khó, họ thực sự cố gắng tìm hiểu chứ không bỏ cuộc ngay lập tức.

**Điều gì có thể khiến nhóm sửa hoặc bác bỏ giả thuyết:**
Học viên thực tế biết rất rõ mình đang quên kiến thức gì, vấn đề chỉ là họ lười tìm lại tài liệu cũ (chuyển sang Giả thuyết B). Hoặc họ hoàn toàn không quan tâm đến việc hiểu sâu, chỉ muốn có mẹo giải bài để pass.

**Solution Parking Lot:**
| Hướng giải quyết có thể có | AI / Không sử dụng AI |
|---|---|
| 1. Chatbot chẩn đoán lỗ hổng và giải thích 1-1 ngay tại chỗ. | AI |
| 2. Bài mini-test đầu mỗi chương học để kiểm tra kiến thức cũ, nếu sai hệ thống sẽ tự động gợi ý link bài đọc ôn tập. | Không sử dụng AI |
| 3. Knowledge graph (bản đồ khái niệm) đính kèm mỗi bài học, hiển thị các khái niệm tiên quyết để học viên click vào ôn lại. | Không sử dụng AI |
| 4. Highlight các thuật ngữ/khái niệm khó, tự động hiện popup định nghĩa ngắn khi di chuột vào (Tooltip). | Không sử dụng AI |
| 5. Nút "SOS" gợi ý hỏi bạn bè/mentor đang online và đã master nội dung của bài học này. | Không sử dụng AI |
