# Load a PDF document from URL in Flutter PDF Viewer

The [SfPdfViewer.network](https://pub.dev/documentation/syncfusion_flutter_pdfviewer/latest/pdfviewer/SfPdfViewer/SfPdfViewer.network.html) creates a widget that displays the PDF document obtained from a URL. The following code example explains the same.

``` dart
@override
Widget build(BuildContext context) {
  return Scaffold(
      body: SfPdfViewer.network(
              'http://ebooks.syncfusion.com/downloads/flutter-succinctly/flutter-succinctly.pdf'));
}
```

## System requirements

https://help.syncfusion.com/flutter/system-requirements

## Clone the repository

* To clone the sample repository locally, open the command prompt in the desired location and execute the following command.

```sh

git clone https://github.com/SyncfusionExamples/load-a-pdf-from-URL-in-flutter-pdf-viewer.git

```

* Navigate to the project directory:

```sh
cd load-a-pdf-from-URL-in-flutter-pdf-viewer
```

## Installing Packages

Install the required packages by running the following command:

```sh
flutter pub get
```

## Run the application

To run the application, use the following command:

```sh
flutter run
```

To learn more about [SfPdfViewer](https://pub.dev/documentation/syncfusion_flutter_pdfviewer/latest/pdfviewer/SfPdfViewer-class.html) widget and its features, refer to this [documentation](https://help.syncfusion.com/flutter/pdf-viewer/overview) 
