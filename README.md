# How to enable WebAssembly (WASM) support in Flutter DataTable (SfDataGrid)?.

In this article, we will show you how to enable WebAssembly (WASM) support in [Flutter DataTable](https://www.syncfusion.com/flutter-widgets/flutter-datagrid).

Flutter Web with WebAssembly (WASM) leverages multi-threading to render applications faster and with minimal lag. The compact and optimized nature of WASM modules ensures efficient execution, significantly reducing the initial load time of web applications.

## Step 1: Switch to the latest version of Flutter : 

Switch to Flutter version 3.24 or higher to run and compile Flutter applications to WebAssembly. To ensure you are running the latest version, run flutter upgrade. For more details on WebAssembly support in Flutter, refer to the provided [link](https://docs.flutter.dev/platform-integration/web/wasm).

## Step 2: Building a Web Application with WASM :

Initialize the [SfDataGrid](https://pub.dev/documentation/syncfusion_flutter_datagrid/latest/datagrid/SfDataGrid-class.html) widget by configuring all the necessary properties. The WASM enhancement empowers SfDataGrid to achieve performance comparable to native speeds in web browsers.

To Building a Web Application with WASM: Use the following commands:

 - flutter build web --wasm
 - flutter run -d chrome --wasm

You can download this example on [GitHub](https://github.com/SyncfusionExamples/How-to-enable-WebAssembly-WASM-support-in-Flutter-DataTable).