# Hướng dẫn kích hoạt tài khoản JetBrains (FREE)

## Bước 1: Cài đặt IntelliJ IDEA
- Tải và cài đặt IntelliJ IDEA từ trang chủ của JetBrains.

## Bước 2: Clone repository công cụ hỗ trợ kích hoạt
- Mở terminal tại nơi muốn lưu trữ file support(thường lưu ở nơi ít làm việc để được bảo toàn) và chạy lệnh sau để clone repo hỗ trợ kích hoạt:
    ```bash
    git clone https://github.com/hieumai1905/tool-crack-jetbrains.git
    ```

## Bước 3: Chỉnh sửa Custom VM Options
- [WINDOWN] Truy cập vào file `idea64.exe.vmoptions` theo đường dẫn sau:
    ```bash
    C:\Users\{user}\AppData\Roaming\JetBrains\IntelliJIdeaVersion\idea64.exe.vmoptions
    ```
- [MAC] Truy cập vào file `idea.vmoptions` theo đường dẫn sau:
    ```bash
    /Users/{user}/Library/Application Support/JetBrains/IntelliJIdeaVersion/idea.vmoptions
    ```
- Thêm 3 dòng code sau vào cuối file:
    ```bash
    --add-opens=java.base/jdk.internal.org.objectweb.asm=ALL-UNNAMED
    --add-opens=java.base/jdk.internal.org.objectweb.asm.tree=ALL-UNNAMED
    -javaagent:{path}\tool-crack-jetbrains\ja-netfilter.jar=jetbrains
    ```
    **path**: ở đây là đường dẫn folder chứa repo đã clone về

## Bước 4: Khởi động lại ứng dụng
- Sau khi chỉnh sửa, khởi động lại IntelliJ IDEA.

## Bước 5: Lấy Activation Code
- Truy cập vào đường dẫn sau để lấy mã kích hoạt: https://3.jetbra.in/
- Chọn 1 server bất kỳ:
    ![alt text](readme/image-1.png)
- Chọn IDE cần activate và copy code:
    ![alt text](readme/image-3.png)

## Bước 6: Active License
- Trong IntelliJ, chọn `Paid License`, sau đó chọn `Activation code`.
- Paste đoạn mã Activation Code đã copy vào và nhấn "Activate".
    ![alt text](readme/image-4.png)

## HOÀN THÀNH
- Bạn đã kích hoạt thành công! Bây giờ có thể tận hưởng toàn bộ tính năng của JetBrains IDE.
![alt text](readme/image-5.png)
