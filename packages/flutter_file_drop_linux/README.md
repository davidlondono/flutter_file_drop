# flutter_file_drop_linux

[![Pub package](https://img.shields.io/pub/v/flutter_file_drop_linux.svg)](https://pub.dev/packages/flutter_file_drop_linux)
[![Pub Points](https://img.shields.io/pub/points/flutter_file_drop_linux)](https://pub.dev/packages/flutter_file_drop_linux/score)

Linux native implementation for [`flutter_file_drop`](https://pub.dev/packages/flutter_file_drop).

Use the façade package in applications. It registers this implementation automatically. The plugin uses GTK drag-and-drop signals and local file handles to expose incoming files and supported text formats through the shared platform interface.

File reads use bounded chunks and session-scoped handles. Directory items are rejected. Build with GTK 3 development libraries installed.

BSD-3-Clause. See [LICENSE](LICENSE).
