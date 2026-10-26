# Draft Bridge

Chuyển project CapCut Desktop giữa Mac ↔ Mac, Windows ↔ Windows và Mac ↔ Windows — không cần CapCut Cloud.

## Cài bằng 1 lệnh

**Windows** — mở **PowerShell** (bấm Start, gõ `PowerShell`) rồi dán:

```powershell
irm https://github.com/locolangson/draft-bridge-releases/releases/latest/download/install.ps1 | iex
```

**macOS** — mở **Terminal** rồi dán:

```bash
curl -fsSL https://github.com/locolangson/draft-bridge-releases/releases/latest/download/install.sh | bash
```

Lệnh tự tải bản mới nhất, cài đặt và mở app. Chạy lại đúng lệnh đó để cập nhật.

## Tải thủ công

Xem mục [Releases](https://github.com/locolangson/draft-bridge-releases/releases/latest):

| Máy | File |
|---|---|
| Windows 10/11 (64-bit) | `DraftBridge-win-x64-Setup.exe` |
| Mac Apple Silicon (M1, M2, M3, M4…) | `DraftBridge-mac-arm64.dmg` |
| Mac Intel | `DraftBridge-mac-x64.dmg` |

App chưa được ký bởi Apple/Microsoft. Khi cài thủ công:
- **Windows**: nếu hiện "Windows protected your PC", bấm **More info → Run anyway**.
- **Mac**: kéo app vào Applications, rồi chạy một lần trong Terminal:
  `xattr -dr com.apple.quarantine "/Applications/Draft Bridge.app"`

Repo này chỉ chứa bộ cài. Mã nguồn ở repo riêng.
