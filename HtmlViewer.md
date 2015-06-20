# Introduction #

The HtmlViewer component set consists of the THtmlViewer, TFrameViewer,
and TFrameBrowser components. All three are HTML document display components:

# Details #

THtmlViewer
  * The basic component.
  * THtmlViewer displays single (non-frame) documents.
  * It also forms the basis for the other two components.

TFrameViewer (deprecated)
  * Displays both frame and single HTML documents.
  * TFrameViewer is oriented more for local file system use.

TFrameBrowser
  * Also displays frame and single HTML documents.
  * TFrameBrower is oriented for use with local file systems and toward Internet style protocols and URL usage.
  * Additional code and/or components are generally required to get data from other sources than the local file system.

These components support most of the HTML 3.2 specifications with many
additional popular HTML 4 and 5 enhancements.
Many Cascading Style Sheet properties are also supported.

For a more detailed list and demonstration of features download and start "FrameDem.exe".