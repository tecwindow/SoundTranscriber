# Hướng Dẫn Sử Dụng Sound Transcriber

Hướng dẫn người dùng này nhằm cung cấp cho bạn một hiểu biết toàn diện về Sound Transcriber và giúp bạn tận dụng tối đa các tính năng của nó.

Chúng tôi khuyến nghị bạn nên đọc hướng dẫn này để đảm bảo sử dụng chương trình một cách tối ưu.

## Giới thiệu về Sound Transcriber:

"Sound Transcriber" là một chương trình chuyển đổi âm thanh thành văn bản dễ tiếp cận, được thiết kế để phiên âm các tệp âm thanh và video, nó hỗ trợ trích xuất các tệp phụ đề và nhiều hơn nữa.

Được phát triển bởi Mahmoud Atef, Ahmed Bakr và Qais Alrefai từ nhóm TecWindow.

## Tính năng:

Sound Transcriber cung cấp các tính năng sau:

- Chuyển đổi tập tin âm thanh và video thành văn bản bằng nhiều dịch vụ phiên âm khác nhau.
- Lưu kết quả chuyển đổi dưới dạng tập tin .txt và .doc hoặc dưới dạng file phụ đề .SRT.
- Chuyển đổi video từ các nền tảng như YouTube, Facebook và X bằng cách tải xuống tập tin trực tiếp, với tùy chọn lưu tập tin để dễ dàng truy cập và sử dụng trong tương lai.

## Các tính năng dự kiến:

Chúng tôi có một số tính năng dự kiến trong kế hoạch, bao gồm:

- Dịch kết quả chuyển đổi sang nhiều ngôn ngữ.

Chức năng "kiểm tra chính tả" với từ điển.

Chuyển đổi kết quả thành âm thanh bằng cách sử dụng các công cụ chuyển văn bản thành giọng nói.

## Các dịch vụ được hỗ trợ:

Phần mềm hiện chỉ hỗ trợ chuyển đổi trực tuyến bằng cách sử dụng tính năng nhận dạng giọng nói của Google, Whisper của OpenAi và wit.ai của Meta.

## Chú ý quan trọng:

Hãy lưu ý những thông tin quan trọng sau:

- Theo mặc định, chương trình sử dụng dịch vụ của Google. Để sử dụng các dịch vụ khác, bạn cần lấy khóa API từ nhà cung cấp dịch vụ tương ứng.
- Để có kết quả tốt nhất với phiên âm tiếng Ả Rập, chúng tôi khuyên bạn nên sử dụng wit.ai.
- OpenAI's Whisper has been included based on previous experiences, but it may not function as intended or may not work at all. We appreciate your feedback and experiences to help us resolve any issues.

Khác với OpenAI, Wit.ai cung cấp khóa API miễn phí.

- Khi chuyển đổi một tập tin, hãy đảm bảo rằng bạn chọn ngôn ngữ thích hợp trước khi bắt đầu quá trình chuyển đổi. Nếu tập tin đa ngôn ngữ, các từ ở ngôn ngữ khác ngôn ngữ đã chọn có thể không được chuyển đổi chính xác do những hạn chế của dịch vụ.

Trước khi chuyển đổi, các tập tin được chia thành các đoạn có thời lượng tối đa 60 giây, tùy thuộc vào giới hạn của từng dịch vụ. Do đó, một số từ có thể bị mất trong quá trình này.

- Để có kết quả tối ưu với các tệp .srt, chúng tôi khuyên bạn nên chọn khoảng thời gian ngắn, chẳng hạn như 5 giây, cho các đoạn.
- Sound Transcriber yêu cầu [Microsoft Visual C++ 2015-2022 Redistributable X64](https://aka.ms/vs/17/release/vc redist.x64.exe) và [Microsoft Visual C++ 2013 Redistributable X64.](https:/ /aka.ms/highdpimfc2013x64enu) Nếu chương trình không hoạt động với bạn, vui lòng sử dụng các liên kết trước đó để tải xuống và cài đặt các tệp cần thiết.
- Hiện tại, Sound Transcriber hỗ trợ các ngôn ngữ sau: Tiếng Ả Rập, Tiếng Anh, Tiếng Tây Ban Nha, Tiếng Pháp, Tiếng Nga, Tiếng Thổ Nhĩ Kỳ và Tiếng Việt.
- Sound Transcriber tương thích với Windows 8 trở lên, nhưng chỉ trên hệ thống 64-bit.

Các định dạng tập tin được hỗ trợ:

Sound Transcriber hỗ trợ các định dạng tập tin sau để chuyển đổi:

.mp3, .wav, .aac, .flac, .oga, .opus, .mp4, .avi, .mkv, .mov, .m4a, .ogg, .ram, .rm, .wma, .wmv, .3gp, .flv.

## Lấy Khóa API:

### Wit.ai:

Nếu chúng tôi bao gồm một khóa API trong chính chương trình, nó có thể sẽ bị chặn sau khi nhiều người dùng sử dụng rộng rãi.

Hơn nữa, "wit.ai" cung cấp các khóa API riêng biệt cho mỗi ngôn ngữ. Điều này có nghĩa là bạn cần tạo một ứng dụng trong ngôn ngữ mong muốn và lấy khóa API tương ứng của nó.

Rất tiếc, việc thu thập khóa API cho tất cả các ngôn ngữ là không khả thi vì chúng khác nhau dựa trên sở thích cá nhân.

Do đó, "chúng tôi" sẽ cung cấp cho bạn hướng dẫn về cách lấy khóa API riêng của bạn.

Mặc dù các bước sau đây có vẻ dài dòng, nhưng chúng rất đơn giản và chỉ cần hoàn thành một lần.

- Mở [trang web wit.ai](https://wit.ai)
- Đăng nhập bằng tài khoản Meta của bạn bằng cách nhấp vào "Continue With Meta."
- Thực hiện các bước tạo tài khoản bình thường hoặc nhấn "Continue with Facebook"
- Đi đến đầu trang, nhấn h hoặc 1 cho người dùng trình đọc màn hình.
- Nhấp vào "New App" và đặt tên cho ứng dụng bằng bất kỳ tên tiếng Anh nào, chẳng hạn như test hoặc my app.
- Bạn sẽ tìm thấy một hộp tùy chọn cho ngôn ngữ của ứng dụng, hãy mở nó và chọn ngôn ngữ phù hợp. Các tệp âm thanh sẽ được chuyển đổi sang ngôn ngữ bạn chọn.

Cuối cùng nhấn "Create".

- Tìm tên của ứng dụng bạn đã tạo, nhấp vào nó, và sau đó điều hướng đến nút "Management".
- Khi bạn đến nút này, nhấn chữ b để tìm một nút gọi là Settings. Nhấn nút này.
- Di chuyển với số 4 hoặc h cho người dùng trình đọc màn hình cho đến khi bạn tìm thấy một tiêu đề có tên Client Access Token, cuộn xuống và bạn sẽ thấy khóa của mình dưới dạng một nút. Bạn có thể chọn văn bản thủ công để sao chép hoặc nhấn nút tương tự để nó được sao chép tự động.
- Trở lại Sound Transcriber và dán khóa API của bạn vào trường được cung cấp.

Bạn có thể lặp lại các bước này và tạo một ứng dụng mới với tên khác để lấy khóa API cho việc phiên âm bằng một ngôn ngữ khác. Nếu bạn muốn sử dụng nhiều ngôn ngữ với wit.ai, chỉ cần lặp lại các bước để lấy khóa API cho mỗi ngôn ngữ.

### Whisper:

Sound Transcriber hỗ trợ phiên âm thông qua việc sử dụng các khóa API Whisper của OpenAI, những khóa này không có sẵn miễn phí.

Giá cả dựa trên số lượng ký tự được phiên âm, và các gói cụ thể không được đề cập ở đây.

Để có thông tin chi tiết về các giới hạn và tùy chọn đăng ký, vui lòng truy cập [trang này/.](https://platform.openai.com/account/billing/overview). Hãy nhớ rằng việc đăng nhập và thêm phương thức thanh toán là do bạn tự chịu rủi ro.

Để lấy khóa API cho Sound Transcriber, hãy truy cập trang [khóa API](https://platform.openai.com/account/api-keys) và nhấp vào "Create new secret key." Sao chép khóa được tạo ra và tiếp tục thêm nó vào cài đặt chương trình như được trình bày sau.

## Giao diện Sound Transcriber:

Khi mở chương trình, bạn sẽ thấy một hộp chỉnh sửa hiển thị kết quả đã được phiên âm. Sử dụng phím tab để điều hướng qua các tùy chọn khác.

Hộp "Ngôn ngữ" cho phép bạn chỉ định ngôn ngữ của tập tin mà bạn muốn phiên âm. Chọn ngôn ngữ phù hợp bằng cách sử dụng các phím mũi tên.

Nhấn nút "Bắt đầu" để bắt đầu quá trình chuyển đổi.

Tiếp theo, bạn sẽ tìm thấy nút "Lưu dưới dạng", cho phép bạn chỉ định các tùy chọn lưu đầu ra.

Dưới đó, có một hộp chỉnh sửa chỉ đọc cho biết đường dẫn hoặc liên kết của tập tin cần được phiên âm.

Sử dụng nút "Duyệt" để tìm và chọn tệp bạn muốn phiên âm.

Ngoài ra, bạn có thể sử dụng các phím tắt, sẽ được giải thích sau.

Xin lưu ý rằng thứ tự các mục trên màn hình có thể khác khi điều hướng bằng phím Tab.

## Các Menu

Chương trình bao gồm một số menu có thể truy cập bằng cách nhấn phím Alt.

### Tập tin:

- Mở: Sử dụng tùy chọn này để duyệt thiết bị của bạn và tìm kiếm tập tin để phiên âm.
- Lưu: Lưu kết quả phiên âm với định dạng đã chỉ định trong cài đặt.
- Lưu dưới dạng: Lưu kết quả với định dạng cụ thể.
- Cài đặt: Truy cập các tùy chọn và tùy chỉnh chương trình.
- Mở Tập tin Nhật kí: cho phép bạn xem tập tin nhật kí của Sound Transcriber.
- Thoát: Thoát chương trình.

### Dịch vụ:

- Nó chứa tên của các dịch vụ có sẵn để chuyển đổi, bạn có thể chọn bất kỳ dịch vụ nào.

### Trợ giúp:

- Hướng dẫn sử dụng: Xem tập tin đang truy cập.
- Có gì mới: Xem nhật ký thay đổi của Sound Transcriber.
- Kiểm tra cập nhật: Tìm kiếm bản cập nhật cho chương trình.
- Liên hệ với chúng tôi: Hiển thị menu với các tùy chọn để liên hệ với nhà phát triển chương trình.
- Quyên góp: ủng hộ các nhà phát triển Sound Transcriber.
- Mở Kho Lưu Trữ: Mở kho lưu trữ của Sound Transcriber trên GitHub, chương trình không phải mã nguồn mở.
- Về: Cung cấp thông tin về Sound Transcriber.

## Cài đặt Sound Transcriber:

- Tương tự như cài đặt trình đọc màn hình NVDA, cài đặt Sound Transcriber được phân loại thành nhiều phần, mỗi phần chứa các tùy chọn khác nhau. Bạn có thể điều hướng giữa các phần bằng cách sử dụng các phím mũi tên lên và xuống. Sử dụng các phím Tab và Shift+Tab để cuộn qua các tùy chọn trong phần đã chọn.

### Tổng quan:

- Phần này bao gồm các tùy chọn khác nhau cho toàn bộ chương trình:
- Ngôn ngữ giao diện: Xác định ngôn ngữ của chương trình.
- Dịch vụ: Xác định dịch vụ được sử dụng để phiên âm tập tin.
- Các tập tin để phiên âm đồng thời: Tính năng này cho phép bạn chỉ định số lượng tập tin cần phiên âm đồng thời. Tính năng này kiểm soát số lượng clip từ cùng một tập tin sẽ được gửi đồng thời sau khi nó được chia nhỏ.
- Tự động phát hiện nếu có tập tin trong khay nhớ tạm: Chương trình kiểm tra khay nhớ tạm của bạn khi khởi động, và nếu tìm thấy tập tin được hỗ trợ, nó sẽ tự động chọn đường dẫn của tập tin đó để chuyển đổi nhanh chóng.
- Hỏi phải làm gì khi phát hiện tập tin trong khay nhớ tạm: Nếu được bật, chương trình sẽ nhắc bạn cách xử lý tập tin được phát hiện.
- Âm thanh: Kích hoạt âm thanh cảnh báo khi quá trình chuyển đổi bắt đầu và kết thúc.
- Nói hành động: Cho phép trình đọc màn hình cung cấp thông tin trạng thái chuyển đổi.
- Kiểm tra cập nhật tự động: Tự động tìm kiếm bản cập nhật chương trình khi khởi động.

Bao gồm các phiên bản beta khi kiểm tra cập nhật: cho phép bạn nhận các bản cập nhật beta cho chương trình. Bạn có thể tìm thêm thông tin trong phần cập nhật beta của hướng dẫn này.

- Bật Ghi Nhật ký: Tính năng này cho phép Sound Transcriber ghi nhật ký các bước trong quá trình phiên âm. Nó đặc biệt hữu ích để khắc phục sự cố. Khi cần, hãy kích hoạt ghi nhật ký và gửi cho chúng tôi tệp được tạo. Nếu ghi nhật ký bị tắt, các nhật ký cũ sẽ bị xóa, nhưng chi tiết của bước cuối cùng sẽ được giữ lại. Điều này đảm bảo rằng chương trình có thể ghi nhật ký các lỗi có thể xảy ra, ngay cả khi bạn không thể chạy chương trình lần đầu tiên và kích hoạt ghi nhật ký.
- Khôi phục cài đặt mặc định: Đặt lại cài đặt về giá trị mặc định.

### Tùy chọn lưu:

- Các tùy chọn trong phần này ảnh hưởng đến chức năng lưu trong trình đơn Tập tin của chương trình.
- Tự động lưu tập tin: Cho phép tự động lưu kết quả chuyển đổi.
- Đường dẫn lưu: Hiển thị đường dẫn hiện tại để lưu tập tin. Sử dụng nút Duyệt để thay đổi nó.
- Lưu dưới dạng .txt: Cho phép tự động lưu tập tin với phần mở rộng .txt.
- Lưu dưới dạng .docx: Lưu tập tin với phần mở rộng .docx.
- Lưu dưới dạng Tập tin phụ đề: Lưu tập tin với phần mở rộng .srt.
- Giữ các tập tin đã tải xuống. Các tập tin tải về từ Internet sẽ được lưu giữ sau khi chuyển đổi. Nếu nó bị tắt, tập tin sẽ được tải xuống, chuyển đổi và sau đó bị xóa.
- Nếu tính năng Lưu tự động bị tắt, tùy chọn "Lưu" trong trình đơn "Tập tin" sẽ thực hiện chức năng tương tự, lưu tệp theo phần mở rộng và đường dẫn đã chỉ định.

### Google:

Phần này yêu cầu bạn nhập khóa API bảo mật vào hộp văn bản được cung cấp có tên "Khóa bí mật". Bạn có thể nhấp vào nút chỉnh sửa để sửa đổi khóa. Ngoài ra, bạn có thể điều chỉnh thời lượng phân đoạn bằng cách chỉ định thời lượng của mỗi phần của tập tin khi sử dụng dịch vụ này.

Lưu ý rằng tập tin cần được chia thành nhiều đoạn để chuyển đổi. Thời lượng tối đa cho mỗi đoạn cho dịch vụ này là một phút.

### OpenAI:

Tương tự như dịch vụ trước, phần này cho phép bạn nhập khóa API. Tuy nhiên, độ dài tối đa cho mỗi tập tin khi sử dụng OpenAI là 30 giây.

### Wit.ai:.

Vì Wit.ai phân tách ngôn ngữ dựa trên khóa API, phần này cho phép bạn kết hợp ngôn ngữ như sau:

Bạn sẽ tìm thấy danh sách các ngôn ngữ hiện được thêm vào.

Mỗi ngôn ngữ đều có một trường chỉnh sửa ẩn tương ứng cho khóa API.

Bạn có thể chỉnh sửa khóa bằng cách xóa khóa cũ, dán khóa mới và sau đó sử dụng nút Chỉnh sửa. Ngoài ra, bạn có thể sử dụng nút Thêm để thêm một khóa mới.

Chọn ngôn ngữ phù hợp với ứng dụng của bạn trong Wit.ai, dán khóa và nhấp vào Thêm.

Lặp lại các bước này cho mỗi ngôn ngữ bạn dự định sử dụng. Sau khi lấy khóa từ trang web Wit.ai, hãy quay lại cửa sổ cài đặt để thêm nó.

Bạn có thể xóa từng khóa riêng lẻ hoặc tất cả các khóa đã lưu liên kết với dịch vụ này bằng cách sử dụng các nút được cung cấp.

Chọn định dạng âm thanh: Để chỉ định phần mở rộng tập tin khi chuyển đổi, hãy chọn ogg hoặc mp3. Nếu kết nối internet của bạn không tốt.

Chọn wav sẽ chia tách tập tin nhanh hơn, nhưng kích thước tập tin sẽ lớn hơn.

Cuối cùng, bạn có thể chỉ định thời lượng của mỗi phân đoạn tập tin, từ 4 đến 20 giây. Chọn thời lượng mang lại kết quả tốt nhất.

Nhấn OK khi bạn đã hoàn tất việc điều chỉnh cài đặt.

## Phím Tắt::

Sound Transcriber cung cấp một số phím tắt để tăng tốc độ và dễ sử dụng.

- Ctrl+O: Mở cửa sổ duyệt tập tin để chọn tập tin cần chuyển đổi.
- Ctrl+V: Dán tập tin từ khay nhớ tạm của bạn để chuyển đổi.
- Ctrl+1: Chuyển sang dịch vụ Google.
- Ctrl+2: Chuyển sang dịch vụ Wit.ai.
- Ctrl+3: Chuyển sang Whisper.
- Ctrl+Enter: Bắt đầu quá trình chuyển đổi.
- P: Hiển thị phần trăm tiến độ chuyển đổi hiện tại.
- Ctrl+S: Mở các tùy chọn lưu.
- Ctrl+Shift+S: Lưu kết quả dưới dạng .srt.
- Ctrl+Shift+T: Lưu kết quả dưới dạng .txt.
- Ctrl+Shift+D: Lưu kết quả dưới dạng .docx.
- Ctrl+U hoặc F3: Kiểm tra các bản cập nhật.
- Alt+S hoặc F8: Mở Cài đặt.
- F1: Mở hướng dẫn sử dụng.
- F2: Xem thông tin bản cập nhật.
- F5: Quyên góp.
- F6: Mở kho lưu trữ.
- F7: Mở tập tin nhật ký.
- F9: Về.
- Ctrl+W hoặc Ctrl+F4: Đóng Sound Transcriber.

## Cách chuyển đổi tập tin:

Để chuyển đổi tập tin, hãy mở Sound Transcriber và duyệt tìm tập tin bằng cách nhấp vào "Duyệt" hoặc sử dụng phím tắt Ctrl+O. Ngoài ra, bạn có thể sao chép tập tin từ thiết bị của mình và dán bằng Ctrl+V.

Bạn cũng có thể sử dụng tùy chọn có sẵn trong menu ngữ cảnh cho các tệp được hỗ trợ, menu Gửi đến trong Windows hoặc đơn giản là kéo và thả.

Bạn cũng có thể sao chép liên kết video từ các trang web như Facebook, Twitter (X), Youtube, SoundCloud và nhiều trang web khác.

Chọn ngôn ngữ và dịch vụ mong muốn bằng cách sử dụng các phím tắt được cung cấp hoặc điều chỉnh chúng trong cài đặt. Nhấn "Bắt đầu" hoặc sử dụng phím tắt Ctrl+Enter để bắt đầu chuyển đổi.

Bạn có biết rằng, bạn có thể mở Sound Transcriber bằng cách nhấn Windows + R để mở hộp thoại Run, sau đó nhập st.

### Lưu ý:

- Trong khi quá trình chuyển đổi đang diễn ra, bạn có thể tạm dừng nó, bất kể là trong quá trình trích xuất văn bản hay tải xuống tập tin. Tuy nhiên, điều quan trọng cần lưu ý là việc khởi động một quy trình mới sẽ dẫn đến việc bỏ qua mọi thứ liên quan đến quy trình trước đó.
- Nếu quá trình bị dừng trong khi chia tách các tập tin, nó không thể được tiếp tục.

## Báo cáo lỗi:

Nếu bạn gặp phải lỗi nào với Sound Transcriber, bạn có thể sử dụng các phương thức liên lạc có sẵn trong menu "Liên hệ với chúng tôi" dưới phần "Trợ giúp". Cung cấp một lời giải thích chi tiết về các hành động dẫn đến lỗi. Chúng tôi khuyên bạn nên chia sẻ tập tin Sound Transcriber.log, điều này sẽ giúp chúng tôi hiểu và giải quyết lỗi hiệu quả hơn.

Vào Cài đặt > Chung và bật ghi nhật ký. Sau đó lặp lại các bước dẫn đến lỗi. Đừng quên tắt ghi nhật ký sau khi gửi tập tin. Lưu ý rằng việc giữ tùy chọn bật có thể dẫn đến tập tin .log có kích thước lớn. Tuy nhiên, bạn có thể chọn giữ nhật ký bật nếu muốn.

Bạn có thể tìm thấy tập tin theo đường dẫn sau:

AppData\Roaming\tecwindow\SoundTranscriber

## Các bản cập nhật Beta:

Sound Transcriber cung cấp một hệ thống cập nhật beta, cho phép bạn thử nghiệm các tính năng mới và hỗ trợ chúng tôi xác định lỗi. Mặc dù việc kích hoạt tính năng này khá đơn giản, nhưng có một số điểm quan trọng cần lưu ý:

- Các bản cập nhật beta có thể không ổn định, và chúng tôi không thể đảm bảo việc phát hành ngay lập tức các bản sửa lỗi cho bất kỳ vấn đề nào bạn gặp phải.
- Trong một số trường hợp, chúng tôi có thể phát hành tối đa ba bản cập nhật trong vòng một tuần.
- Một số tùy chọn có thể không phải lúc nào cũng được dịch sang ngôn ngữ ưa thích của bạn khi sử dụng phiên bản beta.
- Chúng tôi khuyên bạn chỉ nên thử nghiệm beta nếu bạn cảm thấy thoải mái với việc xác định và chia sẻ lỗi.

Để tham gia bản cập nhật beta, hãy vào Cài đặt > Chung, bật tùy chọn "Bao gồm các phiên bản beta khi kiểm tra cập nhật" và sau đó tìm kiếm bản cập nhật.

Nếu bạn muốn trở lại phiên bản ổn định, chỉ cần tắt tùy chọn tương tự, sau đó tải xuống và cài đặt phiên bản ổn định mới nhất.

Chúng tôi gửi lời cảm ơn chân thành đến tất cả những người đã đóng góp vào việc thử nghiệm Sound Transcriber, tìm lỗi và chia sẻ những hiểu biết của họ.

## Cách dịch:

Mặc dù Sound Transcriber hiện chỉ hỗ trợ một số ngôn ngữ giới hạn trong các tùy chọn giao diện và hướng dẫn người dùng, nhưng nó có thể phiên âm giọng nói thành văn bản trong nhiều ngôn ngữ khác nhau.

Tuy nhiên, chúng tôi nhiệt liệt chào đón bất kỳ ai quan tâm đến việc dịch chương trình sang ngôn ngữ mẹ đẻ của họ.

### Dịch giao diện:

Việc dịch các tùy chọn giao diện chủ yếu dựa vào các file .po, có thể được chỉnh sửa bằng chương trình Poedit. Bạn có thể tải xuống Poedit từ trang web chính thức của nó, sau đó điều hướng đến kho lưu trữ Sound Transcriber trên GitHub hoặc tìm thư mục chương trình trên thiết bị của bạn. Tiếp theo, tìm file messages.pot và mở nó trong Poedit. Từ đó, bạn có thể dịch các chuỗi sang ngôn ngữ ưa thích của mình, lưu file (sẽ tạo ra cả file .po và .mo), và chia sẻ những file này với chúng tôi.

### Bản dịch kiểm tra:

Sound Transcriber có thể nhận biết và tiếp nhận các bản dịch mới, cho phép bạn kiểm tra bản dịch của mình trước khi gửi cho chúng tôi. Để làm điều này, hãy điều hướng đến thư mục Languages, tạo một thư mục có mã ngôn ngữ của bạn (hai chữ cái đầu tiên của ngôn ngữ), sau đó tạo một thư mục con có tên LC_MESSAGES và đặt các tệp .po và .mo vào bên trong. Đừng quên đặt tên cho các tệp là SoundTranscriber.po và SoundTranscriber.mo.

### Bản dịch tài liệu:

Mặc dù dịch nhật ký cập nhật và hướng dẫn sử dụng không bắt buộc, bạn có thể dịch chúng sang ngôn ngữ của mình bằng cách sử dụng các tập tin .pot.

Chúng tôi sử dụng các tập tin .md để tạo các tập tin .pot, sau đó chúng tôi gửi tập tin này cho người dịch. Sau đó, chúng tôi chuyển đổi các tập tin .po mà chúng tôi nhận được từ người dịch thành tập tin .md rồi thành tập tin .html để đưa vào chương trình.

Điều này cho phép chúng tôi sửa lỗi bất kỳ phần nào của hướng dẫn và nhật ký thay đổi, đảm bảo chúng được áp dụng nhất quán trên tất cả các ngôn ngữ được hỗ trợ. Nó cũng đảm bảo rằng các tập tin ở các ngôn ngữ khác nhau vẫn giữ nguyên định dạng và cấu trúc.

Để dịch các tập tin, hãy làm theo các bước sau:

- Lấy các tập tin .pot từ kho lưu trữ trên GitHub hoặc từ thư mục Documentation trong thư mục Sound Transcriber.
- Dịch chúng bằng Poedit.
- Bạn có thể thấy một số cụm từ được lặp lại với dấu chấm bổ sung. Chúng tôi sử dụng điều này để phân biệt các cụm từ, đảm bảo chúng ở đúng vị trí. Thêm cùng số lượng dấu chấm, và chúng tôi sẽ xóa chúng khi kết hợp bản dịch.

Lưu ý rằng văn bản có thể không xuất hiện theo thứ tự chính xác nếu bản dịch chưa hoàn chỉnh. Sau khi dịch chính xác, hãy mở lại tập tin để xem chúng theo thứ tự chính xác.

- Cuối cùng, hãy chia sẻ tập tin của bạn với chúng tôi.

### lưu ý:

- Nếu bạn chọn không dịch Hướng dẫn sử dụng và tệp Cập nhật, Sound Transcriber sẽ hiển thị chúng bằng tiếng Anh.
- Dịch thuật phần mềm là một nỗ lực liên tục, và chúng tôi sẽ liên lạc với bạn trước khi phát hành các bản cập nhật mới để bạn có thể dịch bất kỳ nội dung mới nào.

## Trang web Sound Transcriber:

Mặc dù không có trang web chính thức cho Sound Transcriber, bạn có thể truy cập tất cả các tài nguyên cần thiết trong kho lưu trữ Sound Transcriber trên gitHub. Kho lưu trữ này chứa các tệp dịch và phiên bản mới nhất của chương trình.

Lưu ý: Sound Transcriber hiện không phải là mã nguồn mở và kho lưu trữ không chứa mã nguồn của chương trình.

[Liên kết kho lưu trữ.](https://github.com/tecwindow/SoundTranscriber)

## Liên hệ với chúng tôi:

Nếu bạn không thể truy cập danh sách liên hệ của chúng tôi trong Sound Transcriber, bạn có thể liên hệ với chúng tôi qua email bằng các địa chỉ sau:

- Qais Alrefai: ww258148@gmail.com
- Mahmoud Atef: mahmoud.atef.987123@gmail.com
- Ahmed Bakr: AhmedBakr593@gmail.com

## Lời cảm ơn đặc biệt:

- Xin chân thành cảm ơn Riad Assoum vì đã dịch Sound Transcriber sang tiếng Pháp, dịch hướng dẫn sử dụng sang tiếng Anh và hiệu đính chuỗi tiếng Anh và tiếng Ả Rập của chương trình.
- Xin chân thành cảm ơn Georgiana Frincu vì đã dịch Sound Transcriber sang tiếng Tây Ban Nha.
- Cảm ơn Danil rất nhiều vì đã dịch Sound Transcriber sang tiếng Nga.
- Cảm ơn Kadir öz rất nhiều vì đã dịch Sound Transcriber sang tiếng Thổ Nhĩ Kỳ.
- Xin chân thành cảm ơn Nguyễn Anh Đức đã dịch Sound Transcriber sang tiếng Việt.
