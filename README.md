# Toki

An LSPosed module that gives you more control over your TikTok experience.

**English** · [简体中文](README.zh-CN.md)

[Download APK](https://github.com/Xposed-Modules-Repo/io.github.meiyongai.toki/releases/latest) · [Source code](https://github.com/MeiYongAI/Toki) · [Report a problem](https://github.com/MeiYongAI/Toki/issues/new/choose) · [Telegram](https://t.me/toki_lsposed)

This is Toki's module distribution repository for `io.github.meiyongai.toki`.
Source code, development documentation and issue tracking are maintained in
[MeiYongAI/Toki](https://github.com/MeiYongAI/Toki). Releases here distribute the
same signed APK as the source repository.

## Requirements

- Android 9 or newer.
- LSPosed supporting **libxposed API 102**.
- Official TikTok **47.1.4**, **47.0.3** or **46.8.3**.
- Module scope: `com.zhiliaoapp.musically` or `com.ss.android.ugc.trill`.

Third-party modified TikTok clients are not supported. Do not hide Toki from
TikTok with Hide My Applist (HMA).

## Features

Feed filtering, layout cleanup, playback controls and enhanced auto scroll,
media tools, region settings, feature diagnostics and settings import/export.
The Material 3 interface supports 57 languages.

## Install and update

1. Install the APK from [Releases](https://github.com/Xposed-Modules-Repo/io.github.meiyongai.toki/releases/latest).
2. Enable Toki in LSPosed and select your installed TikTok in the module scope.
3. Configure Toki, force-stop TikTok and reopen it. If method discovery runs,
   wait for completion, dismiss the message, then force-stop and reopen TikTok again.

**From 1.0.1 or newer:** install the latest APK over the existing version.

**From 1.0.0:** the signing key changed in 1.0.1. Export Toki settings, uninstall
Toki, install the latest APK and import settings. Recheck activation and scope.
Do not uninstall TikTok.

**From 0.x (`com.seepd.toki`):** the package changed. Disable the previous module
before enabling this one. Configuration does not migrate automatically; preserve
needed settings before uninstalling the old module.

See the [full guide](https://github.com/MeiYongAI/Toki#readme) and
[changelog](https://github.com/MeiYongAI/Toki/blob/main/CHANGELOG.md).

## Project information

This project uses AI-generated code and may contain errors. Toki is independent
of TikTok and ByteDance, and is provided as is. Respect creators' rights and
applicable laws. [License and third-party notices](https://github.com/MeiYongAI/Toki#license).
