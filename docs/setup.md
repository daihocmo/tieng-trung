# Hướng dẫn thiết lập môi trường học Tiếng Trung
Đây là một hướng dẫn nhanh cách cài đặt một số phần mềm để hỗ trợ cho việc tiêu thụ nội dung Tiếng Trung và học từ đó.

## Từ điển

### Về việc sử dụng ứng dụng từ điển
Từ điển là một phần rất quan trọng cần có trong quá trình học ngoại ngữ.

Về từ điển, những ứng dụng ở đây đều đạt chỉ tiêu:

1. Hỗ trợ rất nhiều từ điển cùng một lúc. Rất quan trọng vì bạn có thể sử dụng nhiều từ điển.
2. Hoạt động ngoại tuyến: Bạn không cần kết nối mạng để sử dụng, và nó cũng rất gọn nữa

### Những lựa chọn
- Yomitan (Bản kế tiếp từ Yomitan, là một tiện ích trình duyệt Chrome & Firefox để dùng từ điển pop-up bằng cách giữ phím Shift và di chuột vào từ). Mình gợi ý Yomitan vì nó giúp tạo thẻ Anki và dùng trên trình duyệt.
- Goldendict - Một ứng dụng có tuổi đời khá cũ nhưng hỗ trợ rất nhiều định dạng từ điển nên kho từ điển cho Goldendict gần như là vô tận.

Bạn hãy quay lại đọc [các bài hướng dẫn cài đặt](guide.md) được liệt kê ở hướng dẫn tự học và cài đặt xong các công cụ cần thiết trước khi tiếp tục

### Chọn từ điển
#### Yomitan
[Kho từ điển Tiếng Trung cho Yomitan](https://github.com/MarvNC/yomitan-dictionaries?tab=readme-ov-file#mandarin-chinese) để tải, trong kho này sẽ có từ điển Tiếng Trung - Tiếng Anh và từ điển đơn ngữ.

#### Goldendict

[Kho từ điển Trung-Việt trên Freemdict](https://cloud.freemdict.com/index.php/s/pgKcDcbSDTCzXCs?path=%2FCHINESE%2FChi-Vie). Có một kho rất lớn các từ điển bạn có thể tải. 

[Trang Backup](ttps://cloud.freemdict.com/index.php/s/pgKcDcbSDTCzXCs)

## Các phần mềm và tiện ích hỗ trợ khác

### Anki
Đọc [hướng dẫn cài đặt và sử dụng Anki cơ bản](https://daihocmo.github.io/ngoai-ngu/anki/) 

Sau đó, hãy [tải bộ thẻ mẫu bằng cách bấm vào đường dẫn này](assets/template-deck.apkg) rồi **Import** và trong Anki. Mẫu thẻ này làm cho Tiếng Anh nhưng Tiếng Trung dùng cũng được

Giờ chuyển sang Yomitan, sau khi đã cài đặt AnkiConnect như ở trên thì hãy di chuyển đến mục **Anki** trong cài đặt của Yomitan. Cần mở ứng dụng Anki khi bạn sử dụng Yomitan để tạo thẻ. Nếu bạn thành công thì sẽ có dòng **Connection Status: Connected** ở dưới dòng **Enable Anki Integration**.

![alt text](assets/enable-anki.png)

Sau đó, hãy mở **Config Anki card format...**.

Về phần **Deck** và **Model** thì bạn hãy chọn **Model** là **English** (Nếu bạn tải bộ thẻ mình để ở trên), còn **Deck** là bộ thẻ mà bạn sẽ lưu các thẻ học của mình lại, bộ thẻ này thì bạn cần tự tạo bằng cách bấm vào **Create Deck** ở màn hình chính của Anki.

Tiếp theo, hãy sao chép những cài đặt sau vào mẫu thẻ (Nếu bạn sử dụng bộ thẻ mẫu mình đã để ở trên):

| Field | Value |
| --- | --- |
| `Word` | `{expression}` |
| `Sentence` | `{cloze-prefix}<b>{cloze-body}</b>{cloze-suffix}` |
| `Meaning` | `{glossary-first-brief}` |
| `Audio` | `{Audio}` |

Nó sẽ trông như thế này trong phần cài đặt của Yomitan

![alt text](assets/anki-template.png)

Khi bạn tra từ và bấm vào dấu `+` màu xanh lá cây thì nó sẽ tạo thẻ tự động trong Anki và bạn cần bật Anki khi sử dụng Yomitan để tạo thẻ (Nếu bạn chỉ tra từ mà không tạo thẻ thì không cần bật Anki nha).

Đây là một ví dụ mẫu thẻ trên Anki.

![alt text](assets/front-anki.png)

![alt text](assets/back-anki.png)

### Asbplayer

Dùng để tạo thẻ câu (sentence mining) các thứ trên Youtube hay các trang có hỗ trợ phụ đề. Đây là tiện ích trình duyệt chỉ hỗ trợ Chrome và các trình duyệt tương ứng như Edge hay Brave. [Tải tại đây](https://chromewebstore.google.com/detail/asbplayer-language-learni/hkledmpjpaehamkiehglnbelcpdflcab)

[Hướng dẫn học ngoại ngữ thông qua YouTube & Netflix](https://docs.google.com/document/d/1YaHBu5obEmn83kh20NHkWW_eOYXc7_EAPXTJmDHy1y4/edit) - Đây là hướng dẫn cách đào câu (sentence mining) thông qua asbplayer ngay trên trình duyệt (Máy tính).

### RSS Readers - Feed Aggregators

Bạn nên tải một ứng dụng hỗ trợ RSS để đọc báo, tin tức hay quản lý các cập nhật một cách gọn gàng. Bạn có thể tìm RSS của một trang tin tức, báo Tiếng Trung bất kì, cho vào Rss Reader và nó sẽ tự động cập nhật thông tin và bài viết mới cho bạn, mỗi ngày và rất nhanh chóng.

Bạn cũng có thể truy cập [vào trang tổng hợp này](https://rss.feedspot.com/chinese_news_rss_feeds/) để tìm hiểu thêm