# Track1_Day17_2A202602614_NgoLeThuyTien

> Buổi luyện problem interview theo The Mom Test. Đây là **luyện tập, không phải validation** — không kết luận nào trong repo được coi là "validated".

```
├── README.md                 # 5 phần bắt buộc
└── interview/
    ├── notes.md              # Interview Record – lượt mình làm interviewer
    └── recording-link.md     # Link bản ghi (hoặc file audio recording.m4a/mp3/mp4)
```

---

## 1. Thông tin cá nhân và nhóm

|              |                                                       |
| ------------ | ----------------------------------------------------- |
| MHV          | 2A202602614                                           |
| Họ tên       | Ngô Lê Thuỳ Tiên                                      |
| Tên nhóm     | HKT                                                   |
| Thành viên   | Ngô Lê Thuỷ Tiên, Thân Thị Kim Chi, Nguyễn Khánh Linh |
| Case đã chọn | Case A — AI Tutor: Diagnostic Refresher               |

---

## 2. Problem Hypothesis Brief (kết quả Chặng 1)

| Lớp                            | Kết quả                                                                                                                                                                                                                     |
| ------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Solution directive (tóm tắt)   | Nút "Tôi vẫn chưa hiểu" → AI Tutor đặt 2–3 câu hỏi chẩn đoán → chọn một khái niệm nền để ôn → tạo phần giải thích ngắn → đưa học viên về bài đang học                                                                       |
| Capability trung tính          | Khả năng tự động phát hiện, chẩn đoán lỗ hổng kiến thức nền tảng của người học ngay tại thời điểm họ gặp khó khăn và cung cấp kiến thức bổ trợ tương ứng để giúp họ tiếp tục tiếp thu bài học hiện tại                      |
| Change chain                   | Solution → Người học nhận ra lỗ hổng kiến thức cụ thể của mình → Người học tiếp thu và củng cố khái niệm nền bị thiếu → Outcome: hiểu được nội dung bài đang học và duy trì mạch học                                        |
| Actor chọn điều tra & lý do    | Học viên – người trực tiếp trải nghiệm sự "không hiểu" và trực tiếp tương tác với solution; nếu hành vi của học viên không đổi thì outcome không thể đạt được                                                               |
| Situation & Job                | Khi đang đọc một khái niệm mới hoặc giải một bài tập khó, học viên đang cố hiểu trọn vẹn bài học hiện tại bằng cách đọc đi đọc lại hoặc tự loay hoay tra cứu tài liệu cũ một cách mất phương hướng                          |
| JTBD Hypothesis                | Khi không thể hiểu một nội dung bài học mới, tôi muốn nhanh chóng xác định được phần kiến thức nền tảng nào tôi đang thiếu hụt, để có thể ôn lại đúng trọng tâm và tiếp tục mạch học mà không bị nản chí hay mất thời gian  |
| Pain Hypothesis A              | Khi học bài mới mà không hiểu, học viên gặp khó khăn trong việc tìm cách vượt qua vì không biết mình đang thiếu hụt kiến thức nền tảng nào (không xác định được lỗ hổng), dẫn đến chán nản, phải học vẹt hoặc bỏ dở bài học |
| Pain Hypothesis B (cạnh tranh) | Khi học bài mới mà không hiểu, học viên gặp khó khăn trong việc tra cứu lại kiến thức vì tài liệu cũ quá phân tán hoặc khó tìm lại đúng đoạn cần thiết, dẫn đến tốn quá nhiều công sức tìm kiếm, làm gián đoạn mạch học     |
| Chọn điều tra trước & lý do    | A – "không biết mình không biết cái gì" là rào cản gốc rễ; nếu học viên biết rõ mình quên gì (B) thì vẫn có workaround (tự tra cứu, Google), còn rơi vào A thì thực sự bế tắc                                               |

**Problem Hypothesis mang sang Chặng 2:**

> Học viên trực tuyến thường xuyên gặp bế tắc khi tiếp thu kiến thức mới do bị hổng kiến thức nền tiên quyết, nhưng rào cản lớn nhất là họ lại không thể tự nhận diện được phần kiến thức bị hổng đó là gì. Điều này khiến họ mất nhiều thời gian loay hoay không biết tra cứu từ đâu, dẫn đến dễ nản lòng và bỏ cuộc.

**Điều phải đúng để giả thuyết đứng vững:** Học viên thực sự có động lực muốn hiểu sâu bài học (chứ không chỉ cần điểm qua môn). Khi gặp khó, họ thực sự cố gắng tìm hiểu chứ không bỏ cuộc ngay lập tức.

**Điều có thể khiến nhóm sửa / bác bỏ:** Học viên thực tế biết rất rõ mình đang quên kiến thức gì, vấn đề chỉ là họ lười tìm lại tài liệu cũ (chuyển sang Giả thuyết B). Hoặc họ hoàn toàn không quan tâm đến việc hiểu sâu, chỉ muốn có mẹo giải bài để pass.

**Solution Parking Lot:**
| # | Hướng | AI / Không AI |
|---|---|---|
| 1 | Chatbot chẩn đoán lỗ hổng và giải thích 1-1 ngay tại chỗ | AI |
| 2 | Bài mini-test đầu mỗi chương để kiểm tra kiến thức cũ, sai thì tự động gợi ý link bài đọc ôn tập | Không AI |
| 3 | Knowledge graph (bản đồ khái niệm) đính kèm mỗi bài, hiển thị các khái niệm tiên quyết để click vào ôn lại | Không AI |
| 4 | Highlight thuật ngữ/khái niệm khó, hiện popup định nghĩa ngắn khi di chuột vào (tooltip) | Không AI |
| 5 | Nút "Trợ giúp" gợi ý hỏi bạn bè/mentor đang online đã master nội dung bài này | Không AI |

---

## 3. Conversation Guide – phiên bản cuối (sau luyện tập)

### Thay đổi so với v1

| Phần / câu                    | v1                                                                             | Bản cuối                                                                                                          | Vì sao sửa (lỗi quan sát được khi luyện – ai, P mấy, câu hỏi số)                                                                                                    |
| ----------------------------- | ------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Neo vào một lần cụ thể        | 3 câu Big 3 hỏi chung "khi không hiểu bài…", không bắt buộc story opener       | Bắt buộc hỏi story opener trước; mỗi câu Big 3 bắt đầu bằng "Lần đó…"                                             | Chi – P1 – câu 1–3 (00:08–01:22): cả 3 câu trả lời đều là thói quen chung ("mình thường xem lại phần lý thuyết…", "Nếu vẫn bí, mình sẽ…"), không có bài gì, hôm nào |
| Big 3 #1                      | "Khi nhận ra mình không hiểu bài, bạn đã làm gì để xác định mình vướng ở đâu?" | "Lần đó, lúc nhận ra mình không hiểu, bạn đã làm gì?"                                                             | Chi – P1 – câu 1 (00:08): câu v1 dẫn dắt – giả định sẵn user đi "xác định chỗ vướng" (đúng Pain A), user trả lời theo đúng khung đó                                 |
| Big 3 #3                      | "Việc loay hoay… đã ảnh hưởng thế nào đến tiến độ và cảm xúc học tập của bạn?" | "Lần đó bạn mất bao lâu mới gỡ được? Sau đó bài/kế hoạch tiếp theo của bạn thế nào?"                              | Chi – P1 – câu 3 (01:22): hỏi cảm xúc nên nhận câu chung "khá áp lực và dễ nản", "đôi khi bị chậm" – không có con số hay hậu quả cụ thể                             |
| Probe bank                    | Không có probe cho "chia nhỏ bài", "hỏi bạn/giảng viên"                        | Thêm: "Lần đó bạn phát hiện vướng ở bước nào?" · "Bạn hỏi ai, họ giúp thế nào?" · "Chậm bao lâu so với kế hoạch?" | Chi – P1 – câu 1–3 (00:08–01:22): user nhắc "chia bài thành từng bước nhỏ", "hỏi bạn bè hoặc giảng viên", "chậm so với kế hoạch" nhưng mình không hỏi tiếp          |
| Big 3 #1 – điều khiến xem lại | Chỉ "tự xác định được chỗ vướng dễ dàng"                                       | Thêm nhánh: vướng do "chưa hiểu cách áp dụng kiến thức mới" chứ không phải hổng kiến thức nền                     | Chi – P1 – câu 1 (00:08): user tự tách "quên kiến thức cũ hay chưa hiểu cách áp dụng kiến thức mới" – nhánh chưa có trong Pain A/B                                  |

### Big 3

| #    | Điều cần học                                                                 | Evidence cần tìm                                              | Điều gì khiến nhóm xem lại giả thuyết?                                                                                    |
| ---- | ---------------------------------------------------------------------------- | ------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| 1    | Lần gần nhất bị bế tắc, họ đã làm gì và có tự xác định được chỗ vướng không? | Bài gì, đoạn nào; các bước đã làm; vướng ở bước nào           | Tự xác định được chỗ vướng (→ làm yếu Pain A); vướng do chưa biết áp dụng kiến thức mới chứ không phải hổng kiến thức nền |
| 2    | Họ đã thử những cách nào để vượt qua, tốn bao nhiêu công?                    | Công cụ/người đã dùng, thời gian, kết quả                     | Gỡ nhanh bằng Google/ChatGPT/bạn bè; hoặc khó chủ yếu ở việc tìm lại tài liệu cũ (→ Pain B)                               |
| 3 ⚠️ | Lần đó gây hậu quả gì?                                                       | Mất bao lâu, chậm bao nhiêu so với kế hoạch, bỏ dở, điểm thấp | Không kể được hậu quả cụ thể nào                                                                                          |

### Guide

- **Tiêu chí tuyển:** Người đã gặp một phần bài học không hiểu và phải tìm cách xử lý, trong vòng 7 ngày gần đây.
- **Recruitment check:** "Trong 7 ngày vừa rồi, có lúc nào bạn học mà gặp một đoạn không hiểu không?"
- **Xin phép ghi âm:** "Mình xin phép ghi âm để nghe lại cho bài lab, chỉ dùng trong lớp, không chia sẻ công khai. Bạn đồng ý không?"
- **Lời mở đầu:** "Mình đang tìm hiểu cách mọi người xử lý khi học gặp chỗ khó. Không có đúng sai, mình chỉ muốn nghe chuyện thật của bạn."
- **Story opener (bắt buộc, hỏi trước Big 3):** "Kể mình nghe về lần gần nhất bạn học mà gặp một đoạn không hiểu? Hôm đó bạn đang học gì, đoạn nào?"

| #   | Điều cần học             | Câu hỏi sẽ dùng                                                                               |
| --- | ------------------------ | --------------------------------------------------------------------------------------------- |
| 1   | Hành động & chỗ vướng    | "Lần đó, lúc nhận ra mình không hiểu, bạn đã làm gì?" → "Rồi bạn phát hiện mình vướng ở đâu?" |
| 2   | Cách vượt qua & công sức | "Lần đó bạn đã thử những cách nào?" → "Mỗi cách mất bao lâu? Cách nào giúp được?"             |
| 3   | Hậu quả                  | "Lần đó bạn mất bao lâu mới gỡ được? Sau đó bài/kế hoạch tiếp theo của bạn thế nào?"          |

**Probe bank:** "Lúc đó chuyện gì xảy ra tiếp theo?" · "Vì sao bạn chọn cách đó?" · "Lần đó bạn phát hiện vướng ở bước nào?" · "Bạn hỏi ai, họ giúp thế nào?" · "Bạn tìm lại tài liệu cũ ở đâu, mất bao lâu?" · "Chậm bao lâu so với kế hoạch?" · "Lần gần nhất trước đó là khi nào?"

**Ba phản xạ:**
| User đưa ra | Phản xạ | Cách quay lại evidence |
|---|---|---|
| Lời khen | Deflect | Cảm ơn ngắn rồi quay lại việc họ đang làm hiện tại |
| Câu chung chung ("mình thường…") / lời hứa tương lai | Anchor | "Lần gần nhất chuyện đó xảy ra là khi nào? Lần đó bạn làm gì?" |
| Ý tưởng / feature request | Dig | "Điều đó giúp bạn làm được gì? Hiện tại bạn xử lý ra sao?" |

**Kết thúc:** "Có điều gì về chuyện này mà mình nên hỏi nhưng chưa hỏi không?"

---

## 4. Practice Reflection

> Dẫn chứng theo số câu hỏi trong [interview/notes.md](interview/notes.md).

**1. Câu hỏi nào đã giúp user kể một tình huống cụ thể?**
Trong suốt buổi phỏng vấn, user chưa thực sự kể được một tình huống cụ thể nào mà chỉ chia sẻ thói quen chung chung ("xảy ra thường xuyên hàng ngày", "mỗi lần kiểu em học xong"). Câu hỏi "Nói cách đó ra thì bạn có thử cách gì khác không?" (01:33) là câu mở ra nhiều hành vi nhất, giúp user nhắc đến việc dùng công cụ để tổng hợp lại kiến thức, tuy nhiên nó vẫn chưa được neo vào một lần cụ thể.

**2. Chỗ nào mình cần làm tốt hơn ở lần phỏng vấn thật?**

- **Không neo được vào "lần gần nhất":** Khi hỏi câu mở đầu (00:04), user kể lể quá nhiều vấn đề, lẽ ra ở phút 00:27 thay vì hỏi "thời điểm nào", mình nên áp dụng kỹ năng Anchor mạnh hơn (ví dụ: "Cụ thể hôm qua hoặc hôm kia, khi học môn X, bạn gặp bế tắc ở bài nào?").
- **Bỏ lỡ tín hiệu (Missed probe):** Ở phút 01:37, user có nhắc đến việc "sử dụng [công cụ] để có thể tổng hợp lại những kiến thức". Đây là một cách giải quyết (Workaround) rất quan trọng, nhưng mình đã bỏ lỡ và chuyển sang hỏi về tiến độ/cảm xúc (02:19) thay vì đào sâu ("Bạn dùng công cụ gì? Mất bao lâu? Kết quả có giúp bạn gỡ bế tắc không?").

**3. Sau khi luyện, nhóm đã sửa Conversation Guide ở đâu và vì sao?**

- Bắt buộc story opener và thêm "Lần đó…" vào đầu mỗi câu Big 3, vì interviewee chỉ trả lời bằng thói quen chung.
- Đổi Big 3 #1 thành "Lần đó, lúc nhận ra mình không hiểu, bạn đã làm gì?" để bỏ phần dẫn dắt.
- Đổi Big 3 #3 từ hỏi cảm xúc sang hỏi thời gian và hậu quả cụ thể, vì câu cũ chỉ nhận được câu trả lời chung chung "ảnh hưởng rất lớn đến cảm xúc".
- Thêm probe về công cụ đã dùng và cách vượt qua cụ thể vào Guide. Chi tiết ở bảng "Thay đổi so với v1" (mục 3).

---

## 5. AI Support Log

| Chặng | Công cụ     | AI đã giúp gì                                                                                                                                                             | Điểm sai / hời hợt của AI                                                                                                                               | Mình đã tự sửa thế nào                                                                                |
| ----- | ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| Setup | Claude Code | Tạo khung repo, template trống theo đề                                                                                                                                    | —                                                                                                                                                       | Nội dung điền do mình/nhóm                                                                            |
| 1     | Claude Code | Phân tích 3 case; gợi ý bản nháp 6 lớp cho Case A (capability, change, actor, JTBD, Pain A/B, evidence, parking lot)                                                      | Giả thuyết hoàn toàn suy đoán từ solution directive, chưa dựa trên evidence; Pain A gần như lặp lại giả định của solution                               | Không dùng bản nháp AI: nội dung mục 2 là kết quả Chặng 1 do nhóm tự thảo luận và thống nhất          |
| 2     | Claude Code | Gợi ý Big 3 và câu hỏi cho guide v1; liệt kê câu cần tránh                                                                                                                | Bản gợi ý chưa khớp Pain B mới của nhóm (vẫn hỏi về "cách giải thích, ngại hỏi")                                                                        | Nhóm dùng 3 câu Big 3 do nhóm tự soạn theo giả thuyết Chặng 1; so sánh chi tiết ở bảng thay đổi mục 3 |
| 3     | Claude Code | Xếp câu trả lời mình ghi lại vào bảng Interview Record (giữ nguyên văn); gợi ý bảng Diễn giải và Tự soát kỹ năng dựa trên đúng lời P1                                     | AI không nghe được bản ghi nên không có timestamp, không biết giọng điệu/chỗ ngập ngừng                                                                 | Lời user do mình tự ghi; quote gắn theo số câu hỏi thay vì timestamp                                  |
| 4     | AI Assistant | Format và trích xuất nguyên văn đoạn transcript để đưa vào notes, giúp phân tích các lỗi phỏng vấn (không neo lần cụ thể, bỏ lỡ tín hiệu) dựa trên dữ liệu thật | AI chỉ dựa vào text transcript do mình cung cấp nên có thể bị lỗi nhận diện giọng nói ban đầu, cần kiểm tra lại | Mình đối chiếu lại đoạn text, review các lỗi do AI phân tích và tự quyết định đưa vào bài |

Cam kết: không dùng AI để tạo interview data, bịa quote, suy diễn chi tiết user chưa nói, hoặc viết reflection thay cho việc tự nghe lại.

