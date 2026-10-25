# flutter_file_drop_windows

[![Pub package](https://img.shields.io/pub/v/flutter_file_drop_windows.svg)](https://pub.dev/packages/flutter_file_drop_windows)
[![Pub Points](https://img.shields.io/pub/points/flutter_file_drop_windows)](https://pub.dev/packages/flutter_file_drop_windows/score)

Windows native implementation for [`flutter_file_drop`](https://pub.dev/packages/flutter_file_drop).

Use the façade package in applications. It registers this implementation automatically. The plugin uses Windows OLE drag-and-drop and exposes incoming files and supported text formats through the shared platform interface.

File reads use bounded chunks and session-scoped handles. Directory items are rejected. Build with the Windows Flutter toolchain.

BSD-3-Clause. See [LICENSE](LICENSE).
