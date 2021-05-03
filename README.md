# Load a PDF document from memory or bytes in Flutter PDF Viewer

The [SfPdfViewer.network](https://pub.dev/documentation/syncfusion_flutter_pdfviewer/latest/pdfviewer/SfPdfViewer/SfPdfViewer.network.html) creates a widget that displays the PDF document obtained from a URL. The following code example explains the same.

{% tabs %}
{% highlight Dart %}

@override
Widget build(BuildContext context) {
  return Scaffold(
      body: Container(
          child: SfPdfViewer.network(
              'http://ebooks.syncfusion.com/downloads/flutter-succinctly/flutter-succinctly.pdf')));
}

{% endhighlight %}
{% endtabs %}

To learn more about [SfPdfViewer](https://pub.dev/documentation/syncfusion_flutter_pdfviewer/latest/pdfviewer/SfPdfViewer-class.html) widget and its features, refer to this [documentation](https://help.syncfusion.com/flutter/pdf-viewer/overview) 