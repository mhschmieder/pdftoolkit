# pdftoolkit
Wrapper for PDF export tools to take care of common report-based formatting and page flow

NOTE: This is not yet a functional library in terms of being vetted in production code, due to unforeseen circumstances regarding the PDFjet dependency, which went on hiatus for a few years but now is back in some unknown form.

In order to preserve my officetoolkit as a buildable license-free tool for Excel I/O using Apache POI, I needed to get this PDF code out of that library. I experimented tonight with the latest v7.02 evaluation copy but its API docs are incorrect for what is in the JAR, so that may still be the old v5.75 JAR that doesn't have the essential TextColumn support. TextFrame isn't as controllable so isn't a great substitute.

As time allows, and as current work finally gets to a need for PDF export, I will reviasit this library with a different underlying toolkit altogether, whether the now-free iTextPDF, or a newer one I haven't yet investigated such as PdfPig, PDF Clown or Wicked PDF, or maybe even Apache PdfBox in conjunction with easytable, ph-pdf-layout, pdfbox-layout, or PdfLayoutManager.
