---
title: Hãy cẩn thận với Wasei-Eigo - tiếng Anh chế của người Nhật
author: Anh Dao To
date: 2021-03-20 23:50:00 +0700
categories: [Japanese]
tags: [wasei-eigo]
---
[![](wasei-eigo.jpeg)](wasei-eigo.jpeg)
Sử dụng tiếng Nhật để làm việc trong ngành IT, chắc hẳn bạn sẽ dễ dàng nhận ra một đặc thù: có rất nhiều từ vựng chuyên ngành là từ Katakana. Hầu hết chúng đều bắt nguồn từ tiếng Anh. Và thông thường thì giữ nguyên tiếng Anh, không cố dịch ra tiếng Việt là lựa chọn khôn ngoan nhất.

Tuy nhiên, khác với Gairaigo (外来語) - những từ ngoại lai được vay mượn trực tiếp từ ngôn ngữ nước ngoài và “may mắn” còn giữ được nguyên ngữ nghĩa của chúng khi “nhập khẩu”, thì người Nhật còn xào nấu tiếng Anh để sáng tạo nên một lớp từ vựng kiểu mới, nhìn thì có vẻ giống tiếng Anh đấy, nhưng thực chất thì nghĩa đã bị thay đổi từ một phần cho đến hoàn toàn so với nghĩa gốc ban đầu - chúng được gọi là Wasei-eigo (和製英語).

Lẽ dĩ nhiên, nếu người Nhật sử dụng y nguyên những từ Wasei-eigo này để giao tiếp với người nói tiếng Anh, thì người nghe cũng không thể nào hiểu được. Và với vai trò là cầu nối giữa hai bên Nhật - Việt, một IT Communicator cần phải chú ý khi gặp những từ vựng kiểu này, để có cách dịch chính xác và tự nhiên nhất. Hôm nay, mình sẽ giới thiệu một số từ Wasei-eigo thường được sử dụng trong ngành IT, và cách diễn đạt chúng trong tiếng Anh/ tiếng Việt nhé.

###バージョンアップ (Version up)・バージョンダウン (Version down)

Khi một từ Wasei-eigo có chữ "up" hay “down” đứng sau, nó có nghĩa là "tăng lên", "cải thiện" hay “làm giảm”, “hạ xuống” thứ gì đó.
Vì vậy, có thể dễ dàng đoán được Version up nghĩa là nâng cấp phần mềm lên phiên bản mới hơn, Version down nghĩa là hạ phần mềm xuống lại phiên bản cũ hơn.   
Có nhiều người vẫn giữ nguyên như vậy khi dịch qua tiếng Anh, tuy nhiên thật sự thì đây là một từ Wasei-eigo, và trong tiếng Anh không tồn tại cách nói như vậy.   
Trong tiếng Anh, khái niệm này được gọi là "Upgrade (version)", "Downgrade (version)".

Ex:   
お使いのブラウザを最新版にバージョンアップしてください。   
Please upgrade your browser to the latest version.

バージョンダウンすることによってレイアウトや見た目が変わる場合があります。   
Có trường hợp layout hay bề ngoài sẽ thay đổi do downgrade

###デグレーション・デグレード・デグレ (Degradation, Degrade)

Việc xuất hiện bug khác do ảnh hưởng khi thay đổi, chỉnh sửa một phần nào đó trong program, khiến chất lượng sản phẩm còn tệ hơn trước đó trong tiếng Nhật được gọi là "デグレード", nói gọn lại là "デグレ" (Degrade).   
Để dễ hiểu hơn, bạn cứ tưởng tượng như thế này: lúc lập trình, xuất hiện tình trạng chức năng rõ ràng đã implement ok rồi mà giờ lại bị mất đi/ không hoạt động được, hay cái bug rõ ràng là đã loại bỏ đi rồi thì giờ lại xuất hiện lại.  
Ngoài ra, việc kiểm thử được thực hiện để đảm bảo xem có xảy ra tình trạng như vậy hay không được gọi là "デグレードテスト" (Degrade test), "ノンデグレードテスト" (Non derade test)...

Tuy nhiên, từ "デグレード" này là một từ Wasei-eigo chỉ có thể hiểu được khi dùng trong ngành IT của Nhật thôi.   
Trong tiếng Anh, hiện tượng như trên được gọi là "Regression", và việc kiểm thử hiện tượng đó được gọi là "Regression testing".

Từ "Degrade" trong tiếng Anh là một động từ mang ý nghĩa làm giảm giá trị, làm giảm chất lượng, nên cách sử dụng trong ngữ cảnh như trên cũng không hợp lý nhỉ.   
Thêm nữa, cũng có khi ta bắt gặp từ "デグレーション", nhưng trong tiếng Anh thì danh từ của "degrade" là "degradation", chứ không hề tồn tại từ "degration".

Ex:   
ソフトウェアの修正を行うたびに、デグレードテストを実施しなければなりません。    
Phải thực hiện regression test mỗi khi chỉnh sửa phần mềm.

※Thông tin thêm: Có người còn chia デグレード ra hai loại như sau:  
1) "先祖返り" (せんぞがえり)   
   Khi upgrade version, chức năng vốn đã sửa rồi lại quay trở về version trước đó.   
   Nói một cách cụ thể hơn về khái niệm này là: do có sai sót, nhầm lẫn trong việc quản lý version, mà chức năng chắc chắn đã làm thêm rồi giờ bị biến mất, hay cái bug vốn đã fix rồi giờ lại bị lại.
   
2) "エンバグ" (Enbug)   
   Do thay đổi source code để fix bug hay thêm chức năng mà lại tạo ra bug khác trước giờ chưa có được gọi là "エンバグ".  
   Từ "エンバグ" này cũng giống với "デグレード", là một Wasei-eigo, nên đây là cách nói không tồn tại trong tiếng Anh.   
   Vì đây là sai sót khác với "リグレッション (Regression)" mang nghĩa "退行 - Giật lùi, đi ngược trở lại", nên cũng có người phân biệt từ này với "デグレード"

###サービスイン (Service in)

Việc hệ thống mới bắt đầu đi vào hoạt động chính thức được gọi là "サービスイン", nhưng trong tiếng Anh, nếu dùng từ này thì người ta sẽ không hiểu.   
Từ tương ứng với nghĩa này trong tiếng Anh là "go-live". Là danh từ thì có dấu gạch ngang ở giữa. Còn động từ thì có thể dùng "go live".  
Ngoài ra, cũng có thể sử dụng từ "release" hay "launch" với nghĩa tương tự.

Ex:    
このシステムは来月サービスインする予定です。  
This system will go live next month.

###カットオーバー (Cut over)

"カットオーバー" cũng được sử dụng với nghĩa gần như tương tự với từ "サービスイン" phía trên, nên ta có thể sử dụng "go-live", "release", "launch" để thể hiện ý nghĩa này.  
Trong tiếng Anh cũng có từ "cut over", nhưng ý nghĩa hơi khác một chút. Trong khi "カットオーバー" trong tiếng Nhật chỉ thời điểm bắt đầu hoạt động hệ thống mới, thì "cut over" trong tiếng Anh là từ chỉ "giai đoạn chuyển từ hệ thống cũ sang hệ thống mới".   
Trong khi từ "カットオーバー" trong tiếng Nhật thường dùng để chỉ "go-live" trong tiếng Anh, thì "cut over" trong tiếng Anh lại mang ý nghĩa là giai đoạn trước đó, nên khi trao đổi bằng tiếng Anh thì cần phải chú ý.

###システムダウン (System down)

Việc hệ thống bị dừng hoạt động hay tắt bất thường, ngoài mong muốn được gọi là "システムダウン". Trong tiếng Việt, chúng ta dùng cách nói "sập hệ thống", còn trong tiếng Anh thì không có cách diễn đặt bằng danh từ kiểu như "system down" như vậy.   
Trong tiếng Anh, thường sử dụng cách nói "system failure" hay "system crash".

Ex:    
システムダウンによりご不便をおかけして申し訳ございません。   
We apologize for any inconvenience caused by the system failure.

Còn khi sử dụng từ "down", thì sẽ diễn đạt theo kiểu "động từ tobe + down" hay "go down".

昨日から在庫管理システムがダウンしています。    
The inventory management system has been down since yesterday.

停電のため、コンピュータシステムがダウンしました。    
Our computer system went down due to a power outage.

###アンダーバー (Underbar)

Dấu gạch dưới "_" trong tiếng Nhật thường được gọi là "アンダーバー", nhưng trong tiếng Anh thì gọi là "Underscore".

Ex:   
ドメイン名にアンダーバーを使うことはできません。    
You can’t use an underscore in the domain name.

iPadでアンダーバー記号を入力するにはどうすればよいですか？    
How can I type an underscore symbol on iPad?

###チャージ (Charge)

Ở Nhật, người ta dùng khái niệm "チャージ" khi nạp tiền vào thẻ PASMO, SUICA,... Trong tiếng Việt, chúng ta cũng hay dùng cách nói tương tự là "charge tiền" đúng không nào?
Nhưng thật sự thì trong tiếng Anh, họ không dùng từ charge để chỉ việc nạp tiền, tăng số dư trong thẻ đâu. Trong tiếng Anh, khái niệm này được diễn đạt bằng từ "refill" hoặc "top-up".

Ex:    
PASMOカードは何度でも繰り返し入金できます。   
You can refill your PASMO card as many times as desired.

Vẫn còn rất rất nhiều từ Wasei-eigo nữa, mình không thể nào liệt kê hết được (thậm chí, có rất nhiều từ mà người Nhật cũng không biết chúng là Wasei-eigo đâu).   
Mỗi dự án chúng ta làm đều có những từ vựng riêng ứng với chuyên ngành, nghiệp vụ mà hệ thống đó phục vụ. Vì vậy, nếu có bắt gặp những từ vựng mới là Katakana, thì đừng vội vàng dịch chúng ra ngay, mà hãy cẩn thận tìm hiểu, rồi đưa ra cách dịch đúng, phù hợp nhất nhé ^^