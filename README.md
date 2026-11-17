# Brave Nine Revival — Launcher

Dự án **cộng đồng, phi thương mại**: chơi lại **Brave Nine** (bản Steam) với private server do cộng đồng tự vận hành.
Repo này **chỉ dùng để phát hành bộ cài launcher** — tải ở mục [**Releases**](../../releases/latest).

*English below.*

## Tuyên bố

- **Không phải sản phẩm chính thức.** Không liên kết, không được bảo trợ bởi Neowiz / Pmang hay bất kỳ nhà phát hành nào.
  Brave Nine và mọi nhân vật, hình ảnh, âm thanh thuộc quyền sở hữu của chủ sở hữu tương ứng.
- **Launcher chỉ cài mod.** Launcher cài BepInEx và plugin của dự án vào **bản Brave Nine trên Steam của chính người chơi**,
  và chỉ bật mod khi chơi từ launcher (mở game từ Steam vẫn là game gốc). Launcher không sửa, không bẻ khoá, không thay
  file game, và không thay thế Steam — vẫn cần Steam và bản game của chính bạn.
- **Không phân phối tài nguyên game.** Bộ cài không chứa file, hình ảnh hay dữ liệu nào trích từ game. Ảnh nhân vật hiển thị
  trong launcher (avatar, đội hình) được đọc từ bản game cài trên máy của chính người chơi, chỉ dùng để hiển thị và
  không gửi đi đâu. Logo launcher lấy từ bộ dev kit mà nhà phát hành để lại để tưởng nhớ game.
- **Không kinh doanh.** Miễn phí hoàn toàn: không bán vật phẩm, tiền tệ, tài khoản hay bất kỳ lợi thế nào trong game.
  Nếu có kênh ủng hộ thì đó là ủng hộ tự nguyện cho chi phí thuê server, không đổi lấy gì trong game.
- **Quyền riêng tư.** Server chỉ lưu những gì cần để chơi: tên người chơi, tên/ID Steam để nhận diện, điểm xếp hạng, đội
  hình phòng thủ, lịch sử trận. Không thu thập mật khẩu hay thông tin thanh toán.
- Nếu bạn là chủ sở hữu quyền và muốn dự án dừng hoặc gỡ nội dung, vui lòng mở một issue — chúng tôi sẽ phản hồi.

## Cài đặt

**Cần có:** Windows 10/11 64-bit · Brave Nine trên Steam (bản của bạn) và Steam đang chạy. Không cần cài .NET: từ bản
2026.11.17.1624 launcher kèm sẵn runtime (bản cũ hơn cần [.NET 10 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/10.0) x64).

1. Tải `BraveNineRevival-Launcher-<phiên bản>.zip` ở [Releases](../../releases/latest), **giải nén cả thư mục** ra một chỗ
   cố định (ví dụ `D:\Game\BraveNineLauncher`).
2. Mở `BraveNineLauncher.exe`. Nếu Windows SmartScreen cảnh báo (exe chưa ký số): **More info → Run anyway**.
3. Launcher tự tìm thư mục game Steam → **Cài mod** → đặt tên → **CHƠI**.

Launcher tự cập nhật: có bản mới thì nút **CHƠI** thành **CẬP NHẬT**. Gặp lỗi: **Nhật ký → Xuất log để gửi** (đã che token
tài khoản và Steam ID) rồi gửi file zip cho người quản lý server. Hướng dẫn chi tiết có trong `HUONG-DAN.txt` của bộ cài.

## Giấy phép thành phần

Bộ cài kèm [BepInEx](https://github.com/BepInEx/BepInEx) (LGPL-2.1) — thư mục `payload\BepInEx-dist`.

---

# Brave Nine Revival — Launcher (English)

A **non-commercial community project** to play **Brave Nine** (Steam version) again on a community-run private server.
This repository **only hosts launcher releases** — download from [**Releases**](../../releases/latest).

## Disclaimer

- **Not official.** Not affiliated with or endorsed by Neowiz / Pmang or any publisher. Brave Nine and all of its characters,
  art and audio belong to their respective owners.
- **The launcher only installs a mod.** It installs BepInEx and the project's plugins into **your own Steam copy** of Brave
  Nine and only enables the mod when you play from the launcher (starting the game from Steam stays vanilla). It does not
  modify, crack or replace game files and does not replace Steam — you still need Steam and your own copy of the game.
- **No game assets are distributed.** The package contains no files, images or data extracted from the game. Character
  images shown in the launcher (avatars, line-ups) are read from the game installed on the player's own PC, for display
  only, and are not uploaded anywhere. The launcher logo comes from the dev kit the publisher released in memory of the game.
- **No commercial activity.** Completely free: nothing is sold — no items, currency, accounts or in-game advantages.
  Any support channel is a voluntary contribution to server costs and gives nothing in the game.
- **Privacy.** The server only stores what is needed to play: player name, Steam name/ID for identification, ratings,
  defense line-ups and match history. No passwords or payment information are collected.
- If you are a rights holder and want the project to stop or content removed, please open an issue and we will respond.

## Install

**Requirements:** Windows 10/11 64-bit · Brave Nine on Steam (your own copy) with Steam running. No .NET install needed:
since 2026.11.17.1624 the launcher ships with its own runtime (older builds need [.NET 10 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/10.0) x64).

1. Download `BraveNineRevival-Launcher-<version>.zip` from [Releases](../../releases/latest) and **extract the whole folder**
   somewhere permanent (e.g. `D:\Game\BraveNineLauncher`).
2. Run `BraveNineLauncher.exe`. If Windows SmartScreen warns (the exe is not code-signed): **More info → Run anyway**.
3. The launcher finds your Steam game folder → **Install mod** → pick a name → **PLAY**.

The launcher updates itself: when an update is available the **PLAY** button becomes **UPDATE**. Problems:
**Log → Export logs** (account token and Steam ID removed) and send the zip to the server admin. See `HUONG-DAN.txt` in
the package for details.

## Third-party licenses

The package includes [BepInEx](https://github.com/BepInEx/BepInEx) (LGPL-2.1) in `payload\BepInEx-dist`.

## Antivirus báo nhầm / Antivirus false positives

Một số phần mềm diệt virus (ví dụ Kaspersky: `PDM:Trojan.Win32.Generic`) có thể chặn launcher vì **hành vi** giống mã độc:
cài `winhttp.dll` (cách BepInEx nạp mod) vào thư mục game, tự tải bản cập nhật và tự thay file của chính nó, và exe chưa
được ký số. Đây là báo nhầm — mã nguồn không chứa gì độc hại. Cách xử lý: khôi phục file khỏi khu cách ly và thêm thư mục
launcher vào danh sách loại trừ. **Đừng** chọn "khử mã độc" (sẽ xoá launcher).

Some antivirus products (e.g. Kaspersky `PDM:Trojan.Win32.Generic`) may block the launcher based on **behavior**: it places
`winhttp.dll` (how BepInEx loads mods) into the game folder, downloads and replaces its own files when updating, and the exe
is not code-signed. This is a false positive. Restore the file from quarantine and add the launcher folder to the exclusions.
