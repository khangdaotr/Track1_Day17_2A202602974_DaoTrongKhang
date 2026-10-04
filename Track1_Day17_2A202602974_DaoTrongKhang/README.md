# Track 1 — Day 17

## 1. Thông tin cá nhân và nhóm

| Thông tin | Nội dung |
|---|---|
| Mã học viên | 2A202602974 |
| Họ và tên | Đào Trọng Khang |
| Tên nhóm | ThreeWhites |
| Số thành viên | 3 |
| Thành viên 1 | Đào Trọng Khang — MHV: 2A202602974 |
| Thành viên 2 | Nguyễn Tiến Phát — MHV: 2A202602387 |
| Thành viên 3 | Đỗ Trọng Bình — MHV: 2A202602855 |
| Case đã chọn | Case A — AI Tutor: Diagnostic Refresher |

### Case A — AI Tutor: Diagnostic Refresher

Thêm nút **“Tôi vẫn chưa hiểu”** vào bài học. Khi học viên bấm nút, AI Tutor sử dụng nội dung bài hiện tại, các câu trả lời gần đây và lịch sử học tập để:

1. Đặt 2–3 câu hỏi chẩn đoán ngắn.
2. Chọn một khái niệm nền để học viên ôn lại.
3. Tạo một phần giải thích ngắn.
4. Đưa học viên trở về bài đang học.

---

## 2. Problem Hypothesis Brief

> Các nội dung trong phần này là giả thuyết cần được kiểm chứng, chưa phải fact về người dùng.

### Capability trung tính

Khi người học gặp khó khăn trong một bài học, hệ thống giúp họ xác định lỗ hổng kiến thức có liên quan, tiếp cận phần hỗ trợ phù hợp với nhu cầu và quay lại tiếp tục mục tiêu học tập đang dang dở.

### Chuỗi thay đổi kỳ vọng

**Giải pháp hỗ trợ** → người học chủ động báo hiệu khi chưa hiểu → nguyên nhân gây vướng mắc được nhận diện → người học ôn đúng kiến thức nền còn thiếu → người học hiểu hơn và quay lại bài hiện tại → **người học có khả năng tiếp tục và hoàn thành bài với mức hiểu tốt hơn**.

### Actor được chọn để điều tra trước

**Học viên đang gặp vướng mắc trong lúc học một bài cụ thể.**

Đây là người trực tiếp trải nghiệm tình huống, thực hiện hành vi cần thay đổi và chịu hậu quả đầu tiên nếu không vượt qua được điểm vướng.

### Situation & Job

Khi đang học một bài và gặp nội dung không hiểu dù đã thử xem lại hoặc trả lời, học viên đang cố xác định điểm kiến thức còn thiếu và hiểu đủ để tiếp tục bằng cách tự đọc lại, thử đáp án hoặc tìm trợ giúp từ nguồn khác.

### JTBD Hypothesis

Khi bị mắc ở một nội dung trong bài học, tôi muốn nhanh chóng biết mình đang thiếu hoặc hiểu sai điều gì và được ôn đúng phần đó, để có thể hiểu nội dung hiện tại và tiếp tục học mà không phải bắt đầu lại hoặc bỏ cuộc.

### Hai Pain Hypothesis cạnh tranh

**Pain Hypothesis A — Thiếu kiến thức nền**

Khi gặp một nội dung khó trong bài học, học viên gặp khó khăn trong việc hiểu và tiếp tục bài vì họ thiếu hoặc hiểu sai một khái niệm nền nhưng không xác định được đó là khái niệm nào, dẫn đến thử sai, mất thời gian, giảm tự tin hoặc bỏ dở bài học.

**Pain Hypothesis B — Nội dung hiện tại chưa phù hợp**

Khi gặp một nội dung khó trong bài học, học viên gặp khó khăn trong việc hiểu và tiếp tục bài vì cách giải thích, ví dụ hoặc mức độ phức tạp của nội dung hiện tại không phù hợp với họ, dù họ có thể đã có đủ kiến thức nền, dẫn đến phải tìm một cách diễn đạt khác hoặc rời khỏi bài.

### Giả thuyết được chọn để điều tra trước

Nhóm chọn **Pain Hypothesis A** vì solution directive đặt trọng tâm vào việc chẩn đoán và ôn một khái niệm nền. Đây là giả định rủi ro nhất cần được kiểm tra sớm. Nếu đa số người học có đủ kiến thức nền và chỉ cần một cách giải thích khác, nhóm phải sửa lại Problem Hypothesis.

### Problem Hypothesis

Khi đang học một bài và gặp nội dung không hiểu, một số học viên khó xác định chính xác kiến thức nền mình còn thiếu hoặc hiểu sai. Vì vậy, họ đọc lại hoặc thử đáp án nhưng vẫn không tiến triển, phải tìm trợ giúp bên ngoài, mất thời gian, giảm tự tin hoặc bỏ dở bài học.

### Điều phải đúng để giả thuyết đứng vững

1. Tình huống không hiểu trong lúc học xảy ra đủ thường xuyên với nhóm học viên mục tiêu.
2. Pain tạo ra hậu quả đáng kể, không chỉ là một bất tiện nhỏ.
3. Trong một tỷ lệ đáng kể các tình huống, nguyên nhân thật sự liên quan đến lỗ hổng kiến thức nền.
4. Học viên hiện không dễ xác định lỗ hổng đó bằng các cách hỗ trợ sẵn có.
5. Ôn đúng khái niệm nền giúp học viên hiểu và tiếp tục bài hiện tại tốt hơn.
6. Học viên sẵn sàng yêu cầu trợ giúp và tham gia một bước chẩn đoán ngắn.

### Điều có thể khiến nhóm sửa hoặc bác bỏ giả thuyết

- Phần lớn học viên vướng do cách trình bày, lỗi nội dung, thiếu động lực hoặc mất tập trung thay vì thiếu kiến thức nền.
- Học viên đã biết rõ mình thiếu gì và có workaround nhanh, hiệu quả.
- Tình huống xảy ra hiếm hoặc không tạo ra hậu quả đáng kể.
- Việc ôn kiến thức nền không cải thiện khả năng trả lời hoặc tiếp tục bài.
- Học viên không chủ động yêu cầu trợ giúp vì không nhận ra mình hiểu sai, ngại thừa nhận hoặc không tin hệ thống.

### Evidence Map tóm tắt

| Cần kiểm tra | Evidence làm nhóm tin hơn | Evidence khiến nhóm xem lại giả thuyết |
|---|---|---|
| Situation có thật | Người học kể được một sự kiện gần đây với bài học, thời điểm và trình tự cụ thể | Chỉ nói chung chung, hiếm gặp hoặc không nhớ được sự kiện |
| Pain có ý nghĩa | Mất nhiều thời gian, thử sai, giảm tự tin, chậm tiến độ hoặc bỏ bài | Tự giải quyết nhanh và không ảnh hưởng tiến độ hay kết quả |
| Workaround tồn tại | Đã đọc/xem lại, tìm kiếm, hỏi người khác, dùng công cụ hoặc thử nhiều đáp án | Không cần tìm cách xử lý hoặc bỏ qua mà không có hậu quả |
| Consequence tồn tại | Không hoàn thành bài, hiểu sai phần sau, điểm giảm hoặc cần người khác hỗ trợ | Vẫn hoàn thành và hiểu các phần sau bình thường |
| Pattern có lặp | Xảy ra ở nhiều bài hoặc nhiều lần gần đây | Chỉ là một sự cố ngoại lệ |
| Nguyên nhân là kiến thức nền | Bộc lộ hiểu sai/không nhớ kiến thức tiên quyết và tiến triển sau khi ôn lại | Nắm chắc kiến thức nền và chỉ cần một cách diễn đạt khác |

### Evidence thu được từ cuộc phỏng vấn

| Hạng mục | Evidence trong transcript | Mức độ kết luận |
|---|---|---|
| Situation có thật | Người học kể về lần gần nhất vào “ngày hôm qua”, khi học nội dung mới về Double Diamond và không hiểu cách mô hình hoạt động | Có evidence cho một sự kiện gần đây |
| Hành vi thực tế | Người học chụp màn hình phần chưa hiểu, chuyển sang tab khác, đặt câu hỏi cho AI và mô tả ngữ cảnh bài học | Có evidence trực tiếp về workaround |
| Chi phí của workaround | Phải rời luồng học, chuyển tab, chụp màn hình, viết prompt và giải thích ngữ cảnh; AI có lúc trả lời sai nên phải tìm hiểu lại lâu | Có evidence cho thấy workaround có ma sát và tốn thời gian |
| Hậu quả | Thời gian tìm hiểu kéo dài làm các bài học sau chậm trễ; người học vẫn phải tiếp tục tìm cho đến khi hiểu mới chuyển sang phần khác | Có evidence rằng pain ảnh hưởng tiến độ |
| Kết quả | Người học cho biết cuối cùng hiểu phần đó vì thường tìm hiểu sâu, nhưng phải đánh đổi bằng nhiều thời gian hơn | Workaround có hiệu quả nhưng chi phí cao |
| Tần suất/pattern | Người học nói “thường khi mình tìm hiểu lại một phần kiến thức” nhưng không kể thêm một sự kiện cụ thể khác | Chưa đủ evidence để kết luận pattern lặp lại |
| Nguyên nhân là thiếu kiến thức nền | Transcript không kiểm tra kiến thức tiên quyết và người học không nêu một khái niệm nền cụ thể bị thiếu | Chưa có evidence xác nhận Pain Hypothesis A |
| Nguyên nhân là cách giải thích/nội dung | Người học cần AI giải thích đúng trọng tâm và phải cung cấp nhiều ngữ cảnh | Có tín hiệu ủng hộ Pain Hypothesis B hoặc một pain về việc chuyển ngữ cảnh, nhưng chưa đủ để kết luận |

### Cập nhật Problem Hypothesis sau một cuộc phỏng vấn

Cuộc phỏng vấn **ủng hộ một phần** cho nhận định rằng khi gặp nội dung không hiểu, người học phải dùng workaround bên ngoài luồng học và chịu chi phí thời gian đáng kể. Tuy nhiên, cuộc phỏng vấn **chưa xác nhận** rằng thiếu kiến thức nền là nguyên nhân chính.

Problem Hypothesis tạm thời được điều chỉnh như sau:

> Khi đang học một bài trực tuyến và gặp nội dung không hiểu, một số học viên khó xác định hoặc tiếp cận đúng phần giải thích cần thiết ngay trong ngữ cảnh bài học. Họ phải chuyển sang công cụ bên ngoài, chuyển thông tin và mô tả lại ngữ cảnh; quá trình này có thể mất nhiều thời gian, cho kết quả chưa ổn định và làm chậm tiến độ học.

Đây vẫn chỉ là kết quả từ **một người tham gia**. Cần thêm phỏng vấn trước khi kết luận mức độ phổ biến, nguyên nhân chính hoặc thay đổi hướng sản phẩm.

---

## 3. Conversation Guide phiên bản cuối

> Đây là phiên bản đã rà soát sau buổi phỏng vấn thử. Các câu hỏi dẫn dắt và câu hỏi mời người học đánh giá solution ở cuối buổi đã được loại bỏ.

### Big 3

| Điều cần học | Evidence cần tìm | Điều gì khiến nhóm xem lại giả thuyết? |
|---|---|---|
| 1. Tình huống không hiểu khi đang học có đủ nghiêm trọng và đáng giải quyết không? | Một sự kiện gần đây; thời gian gián đoạn; số lần thử; dấu hiệu bỏ bài, chậm tiến độ, trả lời sai tiếp hoặc giảm tự tin | Người học xử lý rất nhanh, tình huống hiếm, không ảnh hưởng kết quả hoặc dễ dàng bỏ qua |
| 2. Khi bị mắc, người học thực sự làm gì và workaround hiện tại tốn kém hoặc không hiệu quả ra sao? | Các hành động thực tế, thời gian, công sức và kết quả của từng cách đã thử | Workaround hiện tại nhanh, dễ tiếp cận, thường giải quyết được vấn đề và người học hài lòng |
| 3. **Câu hỏi đáng sợ:** nguyên nhân chính có thật sự là thiếu hoặc hiểu sai kiến thức nền không? | Người học không giải thích được kiến thức tiên quyết, nhận ra hiểu nhầm hoặc chỉ tiến triển sau khi ôn phần nền | Người học nắm chắc kiến thức nền nhưng vướng vì câu chữ, ví dụ, giao diện, lỗi nội dung, mất tập trung hoặc thiếu động lực |

### Tiêu chí tuyển người

Nói chuyện với học viên đã gặp ít nhất một nội dung hoặc câu hỏi không hiểu khi học một bài trực tuyến và đã phải dừng lại, thử xử lý hoặc tìm trợ giúp trong vòng **14 ngày gần đây**.

### Recruitment check

> Trong 14 ngày vừa qua, bạn có lần nào đang học một bài trực tuyến thì gặp một nội dung hoặc câu hỏi không hiểu, khiến bạn phải dừng lại, thử làm lại hoặc tìm cách xử lý không? Đó là bài nào và xảy ra khoảng ngày nào?

Câu hỏi này chỉ dùng để tuyển đúng người, không được tính là evidence chính.

### Lời mở đầu

> Cảm ơn bạn đã dành thời gian. Bọn mình đang tìm hiểu cách người học xử lý những lúc gặp khó khăn trong quá trình học trực tuyến. Không có câu trả lời đúng hay sai và đây không phải bài kiểm tra kiến thức. Mình muốn nghe về những việc đã thực sự xảy ra, nên thỉnh thoảng sẽ hỏi kỹ về trình tự, hành động và kết quả. Những chia sẻ của bạn chỉ được dùng cho mục đích nghiên cứu. Buổi trò chuyện dự kiến kéo dài khoảng 15–20 phút. Với sự đồng ý của bạn, mình xin ghi chép/ghi âm để không bỏ sót thông tin. Bạn có thể bỏ qua bất kỳ câu hỏi nào hoặc dừng bất cứ lúc nào.

### Story opener

> Kể mình nghe về **lần gần nhất** bạn đang học một bài trực tuyến thì gặp một nội dung hoặc câu hỏi không hiểu và phải dừng lại hoặc tìm cách xử lý. Hãy bắt đầu từ lúc bạn nhận ra mình đang bị mắc.

### Big 3 Questions

| Điều cần học | Câu hỏi sẽ dùng |
|---|---|
| Mức độ nghiêm trọng và hậu quả | Trong lần đó, việc không hiểu đã ảnh hưởng thế nào đến quá trình học của bạn? Sau đó bạn có tiếp tục và hoàn thành được phần đang học không? |
| Hành vi và workaround thực tế | Từ lúc nhận ra mình không hiểu cho đến khi tiếp tục hoặc dừng lại, bạn đã làm những gì? Hãy kể theo đúng thứ tự, kết quả của từng cách và những thông tin bạn phải cung cấp lại khi chuyển sang một nguồn hoặc công cụ khác. |
| Nguyên nhân thực tế của điểm vướng | Trước khi bị mắc, bạn nghĩ mình đã biết những gì cần thiết để hiểu phần đó? Điều gì đã giúp bạn hiểu ra, hoặc đến cuối cùng bạn vẫn chưa hiểu điều gì? |

### Probe bank

- “Lúc đó chuyện gì xảy ra tiếp theo?”
- “Bạn đã làm gì?”
- “Vì sao bạn chọn cách đó?”
- “Phần nào khó nhất?”
- “Bạn đã thử cách nào khác chưa?”
- “Mỗi cách mất khoảng bao lâu?”
- “Kết quả sau khi thử cách đó là gì?”
- “Bạn đã tìm hoặc hỏi ai? Vì sao chọn nguồn đó?”
- “Điều gì khiến bạn quyết định tiếp tục hoặc dừng lại?”
- “Việc đó kéo theo hậu quả gì?”
- “Bạn nhận ra nguyên nhân khiến mình bị mắc vào lúc nào?”
- “Lần gần nhất trước đó là khi nào?”

### Khi cuộc trò chuyện lệch khỏi evidence

| Người học đưa ra | Phản xạ | Cách quay lại evidence |
|---|---|---|
| Lời khen | **Deflect** | Cảm ơn ngắn rồi hỏi họ đã làm gì đầu tiên trong sự kiện vừa kể |
| Câu chung chung hoặc lời hứa tương lai | **Anchor** | Hỏi lần gần nhất chuyện đó thực sự xảy ra và hành động cụ thể khi ấy |
| Ý tưởng hoặc feature request | **Dig** | Hỏi ý tưởng đó giúp hoàn thành việc gì và hiện tại họ xử lý nhu cầu ấy ra sao |

### Câu kết thúc

> Trong câu chuyện vừa rồi, còn chi tiết hoặc hành động nào bạn thấy quan trọng mà mình chưa hỏi tới không?

### Nguyên tắc phỏng vấn

- Không nhắc đến nút “Tôi vẫn chưa hiểu”, AI Tutor hoặc quy trình ôn tập dự kiến.
- Không hỏi người học có thích, có dùng hoặc thấy một tính năng giả định hữu ích hay không.
- Ưu tiên sự kiện và hành vi đã xảy ra, không dùng dự đoán tương lai làm evidence.
- Không đưa sẵn các nguyên nhân để người học lựa chọn khi chưa nghe câu chuyện của họ.
- Không coi câu trả lời ở recruitment check là evidence chính.
- Không kết luận thay cho người học bằng câu hỏi dạng “Bạn đang cần một công cụ... đúng không?”.
- Dừng ở việc tìm hiểu problem; không mô tả một nút hoặc công cụ giả định rồi hỏi nó có hữu ích hay không.

### Những chỉnh sửa sau buổi luyện/phỏng vấn thử

1. Loại câu hỏi dẫn dắt: “Bạn đang cần công cụ có thể giúp bạn hiểu nhanh... đúng không?”.
2. Loại câu hỏi concept: “Nếu có một công cụ hình thành một nút... thì có hữu ích không?”. Câu trả lời tích cực cho câu hỏi này không được dùng làm evidence về pain.
3. Giữ story opener về “lần gần nhất” vì câu hỏi này đã tạo ra một sự kiện cụ thể: học Double Diamond vào ngày hôm trước.
4. Giữ các câu hỏi về hành động và hậu quả vì chúng đã làm rõ workaround, chi phí chuyển ngữ cảnh và ảnh hưởng tới tiến độ.
5. Bổ sung probe về kiến thức tiên quyết để kiểm tra trực tiếp Pain Hypothesis A; buổi thử chưa khai thác được điểm này.
6. Bổ sung probe về thông tin phải chuyển sang công cụ khác vì đây là ma sát nổi bật trong câu chuyện.

---

## 4. Practice Reflection


### Câu trả lời 1 — Điều đã làm được

Buổi phỏng vấn đã bắt đầu bằng mục đích học hỏi, xin phép ghi âm và nhấn mạnh đây không phải bài kiểm tra. Story opener neo vào “lần gần nhất” đã giúp người tham gia kể một sự kiện cụ thể xảy ra ngày hôm trước khi học Double Diamond. Các câu hỏi tiếp theo thu được hành vi thực tế: chụp màn hình, chuyển tab, hỏi AI, mô tả lại ngữ cảnh và tiếp tục tìm hiểu cho tới khi hiểu. Buổi phỏng vấn cũng làm rõ hậu quả là mất thời gian và làm chậm các bài học sau.

### Câu trả lời 2 — Điều chưa làm tốt

Đoạn cuối đã chuyển từ tìm evidence sang xác nhận solution. Hai câu hỏi về việc người học “đang cần công cụ” và giả định có “một nút” đều dẫn dắt, làm lộ hướng giải pháp và mời người tham gia đánh giá một tính năng chưa tồn tại. Vì vậy, câu trả lời “hữu ích” sau đó không phải evidence đáng tin về hành vi. Buổi phỏng vấn cũng chưa hỏi đủ sâu về kiến thức tiên quyết nên không thể xác nhận giả thuyết rằng nguyên nhân là thiếu kiến thức nền. Ngoài ra, câu hỏi về mức độ “phức tạp và tốn thời gian” đã gợi sẵn câu trả lời thay vì để người học tự mô tả chi phí.

### Câu trả lời 3 — Điều sẽ thay đổi ở lần sau

Ở lần sau, người phỏng vấn sẽ dừng ở câu chuyện quá khứ và không giới thiệu solution. Thay vì hỏi công cụ giả định có hữu ích không, người phỏng vấn sẽ hỏi người học đã phải cung cấp lại ngữ cảnh gì, mất khoảng bao lâu, AI sai ở điểm nào và họ kiểm tra câu trả lời bằng cách nào. Để kiểm tra câu hỏi “đáng sợ”, người phỏng vấn sẽ hỏi người học đã biết gì trước khi gặp vướng mắc, kiến thức tiên quyết nào còn thiếu và điều cụ thể nào cuối cùng giúp họ hiểu. Nếu người học nói chung chung, người phỏng vấn sẽ neo lại vào sự kiện gần nhất thay vì chấp nhận dự đoán hoặc nhận xét chung.

---

## 5. AI Support Log

### AI đã hỗ trợ những gì?

- Giúp chuyển solution directive của Case A thành capability trung tính.
- Giúp triển khai chuỗi **Solution → Change → Actor → Situation & Job → Pain → Evidence**.
- Đề xuất hai Pain Hypothesis cạnh tranh và chỉ ra giả định rủi ro cần kiểm chứng trước.
- Hỗ trợ xây dựng Evidence Map với evidence ủng hộ và evidence có thể bác bỏ giả thuyết.
- Giúp chuyển Evidence Map thành Big 3 và Conversation Guide tập trung vào hành vi quá khứ.
- Hỗ trợ rà soát để câu hỏi không làm lộ solution hoặc mời người học đánh giá tính năng.
- Hỗ trợ trình bày và hệ thống hóa nội dung trong các tệp Markdown.

### Điểm AI có thể sai hoặc hời hợt

- Ở bản đầu, AI suy luận hoàn toàn từ đề bài và chưa có transcript nên không thể xác nhận Problem Hypothesis là đúng.
- Các actor, pain, consequence và workaround được nêu là giả thuyết hợp lý nhưng chưa phải evidence.
- Mốc tuyển người trong 14 ngày là lựa chọn phục vụ khả năng nhớ lại sự kiện, chưa được kiểm chứng là khoảng thời gian phù hợp nhất.
- Sau khi có transcript, AI chỉ có dữ liệu từ một người tham gia nên không thể khái quát cho toàn bộ học viên.
- AI chưa biết tên nhóm và chưa có nguyên văn ba câu hỏi Reflection ở Chặng 4.

### Tôi đã tự kiểm tra và sửa như thế nào?

- Giữ nhãn “giả thuyết” cho các nhận định chưa được xác thực, không trình bày chúng như fact về người dùng.
- Giữ trống tên nhóm khi chưa được cung cấp; sử dụng đúng thông tin ba thành viên hiện có trong README.
- Giữ cả Pain Hypothesis A và B để tránh mặc định rằng thiếu kiến thức nền là nguyên nhân duy nhất.
- Bổ sung câu hỏi “đáng sợ” để evidence có khả năng làm nhóm thay đổi hướng.
- Loại các câu hỏi xin ý kiến về solution; thay bằng câu hỏi về lần gần nhất, hành động, workaround và hậu quả đã xảy ra.
- Đối chiếu transcript để tách phát biểu có evidence khỏi câu trả lời bị tạo bởi câu hỏi dẫn dắt.
- Không dùng lời khen solution ở cuối cuộc phỏng vấn làm bằng chứng rằng solution cần được xây dựng.
- Điều chỉnh Problem Hypothesis theo evidence thực tế: pain được quan sát rõ nhất là chi phí chuyển ngữ cảnh và tìm đúng phần giải thích; giả thuyết thiếu kiến thức nền vẫn chưa được xác nhận.
