# Có gì mới trong Sound Transcriber?

## Phiên bản 1.4.5:

- Một số cải tiến.

## Phiên bản 1.4.4:

- Đã thêm bản dịch tiếng Việt, xin chân thành cảm ơn Nguyễn Anh Đức.
- Đã chuyển sang hệ thống mới để dịch nhật ký thay đổi và Hướng dẫn Sử dụng Sound Transcriber. Bạn có thể tìm thêm thông tin trong Hướng dẫn Sử dụng.
- Đã sửa lỗi khiến Sound Transcriber không thể tải xuống video YouTube thành công.
- Đã sửa lỗi ngăn chặn Sound Transcriber dừng tải xuống đúng cách khi tùy chọn "Giữ Tập Tin Đã Tải Xuống "được bật".
- Đã sửa lỗi khiến Sound Transcriber ghi nhật ký lỗi trả về từ dịch vụ không chính xác.
- Hướng dẫn sử dụng Sound Transcriber được cải tiến.
- Nâng cấp lên wxPython 4.2.2 và Python 3.12.7.

## Phiên bản 1.4.3:

- Một số cải tiến.

## Phiên bản 1.4.2:

- Đã thêm bản dịch tiếng Thổ Nhĩ Kì. Cảm ơn Kadir öz.
- đã sửa lỗi liên quan đến việc tải xuống từ YouTube.
- Một số cải tiến.

## Phiên bản 1.4.1:

- Một số cải tiến nhỏ.

## Phiên bản 1.4.0:

- Đã thêm hệ thống cập nhật Beta. Bạn có thể kích hoạt tùy chọn này trong cài đặt để nhận các bản cập nhật beta. Xin lưu ý rằng các bản cập nhật beta có thể chứa các lỗi nghiêm trọng. Bạn có thể tắt tùy chọn này và quay lại phiên bản ổn định mới nhất bất kỳ lúc nào.
- Đã thêm tùy chọn để chỉ định số lượng tệp sẽ được chuyển đổi đồng thời.
- Sound Transcriber sẽ không còn tạo nhật ký sự kiện theo mặc định. Bạn có thể kích hoạt nó từ cài đặt khi gặp lỗi và sau đó lặp lại các bước. Theo mặc định, nhật ký sẽ giữ chi tiết của bước cuối cùng và chi tiết các thao tác trước đó sẽ bị xóa khi bị vô hiệu.
- Nhật ký bây giờ hiển thị nhiều thông tin hơn.
- Chức năng của nút sao chép đã được nâng cao. Do đó, nút sao chép sẽ vẫn khả dụng miễn là trường kết quả chứa văn bản được phiên âm.
- Đã thêm tùy chọn quyên góp cho nhà phát triển.
- Đã cố gắng giảm thiểu các lỗi do dịch vụ Google trả về.
- Đã sửa một số lỗi, đặc biệt là các lỗi liên quan đến việc tạm dừng và tiếp tục quá trình phiên âm.
- Đã cập nhật hướng dẫn sử dụng để bao gồm chi tiết bản dịch, bản cập nhật beta và các thông tin quan trọng khác. Chúng tôi thực sự khuyên bạn nên xem lại nó để biết thông tin mới nhất.
- Đã cập nhật phiên bản Python được sử dụng lên Python 3.12.
- Một số cải tiến nhỏ.

## Phiên bản 1.3.3:

- Đã thêm bản dịch tiếng Nga, cảm ơn Danil rất nhiều.
- thực hiện các cải tiến về mã giúp tăng tốc độ phản hồi và giảm kích thước.
- Đã thay thế Accessible Output 2 bằng PythonUniversalSpeech.
- Sound Transcriber sẽ không còn sử dụng Sapi5 để đọc lời nhắc hành động khi được sử dụng mà không có trình đọc màn hình.
- Cập nhật phiên bản Python được sử dụng lên Python 3.11.7.
- Một số cải tiến nhỏ.

## Phiên bản 1.3.2:

- Bây giờ bạn có thể thêm tập tin bằng cách kéo và thả.
- Đã sửa một lỗi nghiêm trọng khiến văn bản được trích xuất xuất hiện theo thứ tự sai khi chuyển đổi các tệp dài.
- Đã sửa lỗi khiến tùy chọn lưu bị vô hiệu nếu quá trình chuyển đổi bị hủy trước khi hoàn tất.
- Một số cải tiến cho bản dịch tiếng Ả Rập. Xin cảm ơn Zeinab Bahaa rất nhiều.
- Nhiều cải tiến nhỏ khác nhau.

## Phiên bản 1.3.1:

Một số sửa lỗi và cải tiến.

## Phiên bản 1.3.0:

- Đã thêm bản dịch tiếng Pháp. Cảm ơn Riad Assoum rất nhiều.
- Giờ bạn có thể mở tập tin trong Sound Transcriber để phiên âm chúng từ menu ngữ cảnh của các loại tập tin được hỗ trợ.
- Giờ đây, bạn có thể truy cập Sound Transcriber nhanh chóng bằng cách chỉ cần nhập 'st' trong hộp thoại Run.
- Sound Transcriber giờ đây có thể tự động nhận dạng bản dịch giao diện và tích hợp các tệp trợ giúp mới. Để đóng góp, hãy dịch tệp messages.pot bằng Poedit và lưu các tệp theo cùng thứ tự với các tệp ngôn ngữ hiện có.
- Khi tùy chọn giữ tệp đã tải xuống bị tắt, Sound Transcriber sẽ giữ chúng cho đến khi chương trình được đóng. Điều này đặc biệt hữu ích nếu bạn muốn lặp lại quá trình chuyển đổi với các tùy chọn khác nhau.
- Một số lỗi liên quan đến tính năng dán từ khay nhớ tạm đã được sửa. Như bỏ qua một số đường dẫn, không bắt đầu chuyển đổi từ thông báo phát hiện, dán liên kết bất kỳ lúc nào và hơn thế nữa. Cảm ơn rất nhiều Dawlat Hassan vì ghi chú đã giúp phát hiện ra nhiều lỗi liên quan đến tính năng này.
- Đã sửa lỗi đôi khi khiến Sound Transcriber bắt đầu bằng một ngôn ngữ khác sau lần cập nhật cuối cùng.
- Bạn không thể mở hai phiên bản Sound Transcriber cùng một lúc nữa.
- Thực hiện các thay đổi đối với phương pháp dừng chuyển đổi.
- Những cải tiến nhỏ khác nhau.

## Phiên bản 1.2.0:

Quan trọng, bắt đầu từ phiên bản này, Sound Transcriber sẽ chỉ hỗ trợ phiên bản Windows 64 bit.

- Đã thêm bản dịch tiếng Tây Ban Nha. Cảm ơn Georgiana Frincu rất nhiều.
- Bây giờ bạn có thể chuyển đổi video từ Youtube, Facebook, Twitter (X) và các dịch vụ khác thành văn bản để Sound Transcriber tải video xuống rồi chuyển đổi.
- Bạn có thể chọn giữ lại tập tin gốc sau khi chuyển đổi hoặc xóa nó khỏi cài đặt.
- Tính năng tạm dừng và tiếp tục đã được thêm vào quá trình phiên âm.
- Bây giờ bạn có thể dán đường dẫn tập tin cần chuyển đổi.
- Bạn có thể chỉ định phần mở rộng tập tin được gửi tới wit.ai để chuyển đổi từ cài đặt.
- Sound Transcriber sẽ cố gắng xử lý các tập tin có tên chứa biểu tượng cảm xúc.
- Sound Transcriber sẽ không còn dừng lại trong quá trình chuyển đổi. Nếu điều này xảy ra, bạn vẫn có thể tiếp tục quá trình.
- Những cải tiến nhỏ chỗ này chỗ kia.

### Ghi chú

- Hỗ trợ tạm dừng trong quá trình trích xuất văn bản nhưng không hỗ trợ trong quá trình chia nhỏ tập tin.
- Nếu bạn tạm dừng một quy trình và sau đó bắt đầu một quy trình chuyển đổi mới, bạn sẽ mất mọi thứ liên quan đến quy trình trước đó; Do đó, nên lưu kết quả hiện tại trước khi bắt đầu quá trình chuyển đổi mới.
- Việc chọn định dạng wav trong cài đặt wit.ai sẽ tăng tốc độ chia nhỏ tệp nhưng dẫn đến chuyển đổi chậm hơn và tăng mức sử dụng dữ liệu. Hãy cân nhắc dùng thử định dạng .ogg và chia sẻ phản hồi của bạn về kết quả.

## Phiên bản 1.1.2:

- Đã sửa lỗi khiến việc chuyển đổi các tập tin .mp4 không đúng cách.
- Đã sửa lỗi khiến định dạng tập tin được lưu giữ lại phần mở rộng của tập tin gốc với các tập tin đầu ra và đôi khi lưu các tập tin đầu ra với cùng phần mở rộng với tập tin gốc khi mở tập tin qua khay nhớ tạm.
- Bạn không thể chuyển đổi giữa các dịch vụ và mở cài đặt của Sound Transcriber trong quá trình chuyển đổi nữa.
- Sound Transcriber bây giờ sẽ cố gắng cảnh báo bạn khi chuyển đổi sử dụng khóa API wit.ai không chính xác.
- Đã sửa lỗi khiến nút "Chỉnh sửa" hiển thị hai lần sau khi thêm khóa wit.ai.
- Đã sửa lỗi khiến các nút Cập nhật và Hủy xuất hiện bằng tiếng Anh khi sử dụng Sound Transcriber bằng tiếng Ả Rập.
- Một số lỗi khác đã được sửa.

## Phiên bản 1.1.1:

- Đã sửa lỗi khiến vị trí con trỏ di chuyển về đầu văn bản liên tục với trình đọc màn hình trong khi trích xuất văn bản.
- Đã sửa lỗi khiến tùy chọn lưu không hoạt động sau khi quá trình trích xuất văn bản hoàn tất.
- Đã sửa một số lỗi khác.

## Phiên bản 1.1:

Phiên bản này bao gồm một số sửa lỗi và một số tính năng mới.

- Đã hỗ trợ thêm nhiều định dạng tập tin âm thanh và video khác nhau.
- Các tập tin Word hiện được lưu dưới dạng .docx thay vì .doc.
- Sound Transcriber sẽ hiển thị cảnh báo khi đóng trong quá trình chuyển đổi tập tin.
- Nếu tự động lưu bị tắt và văn bản được trích xuất không được lưu trong bất kỳ tập tin nào, Sound Transcriber sẽ nhắc bạn về việc cần làm khi đóng. Nếu bạn chọn lưu, tập tin sẽ được lưu theo các tùy chọn được chỉ định trong phần Tùy chọn Lưu trong cài đặt.
- Sound Transcriber bây giờ sẽ ghi nhớ ngôn ngữ đã chọn để chuyển đổi tập tin cho mỗi dịch vụ.
- Văn bản được trích xuất giờ đây sẽ được hiển thị trong quá trình trích xuất. Nói cách khác, nếu quá trình trích xuất dừng lại vì bất kỳ lý do nào, bạn sẽ không bị mất văn bản đã trích xuất. Văn bản mới sẽ được thêm vào khi quá trình tiếp tục.
- Bây giờ bạn có thể kiểm tra tiến trình trích xuất bằng cách nhấn P.
- Đã sửa lỗi khiến nút "Duyệt" đường dẫn tự động lưu không hoạt động.
- Đã sửa lỗi ngăn không cho thay đổi khóa API cho các ngôn ngữ khác ngoài ngôn ngữ chính trong danh sách ngôn ngữ của wit.ai.
- Đã sửa lỗi khiến việc chuyển đổi tệp bằng Wit.ai không hoạt động với các ngôn ngữ khác ngoài ngôn ngữ chính.
- Đã sửa lỗi khiến việc khôi phục cài đặt mặc định không hoạt động.
- Điều chỉnh bố cục của hộp thoại cài đặt để hiển thị các mục chính xác.
- Đã thực hiện một số cải tiến đối với bản dịch tiếng Ả Rập.
- Sửa một số lỗi nhỏ chỗ này chỗ kia.

## Phiên bản 1.0:

Bản phát hành đầu tiên.

