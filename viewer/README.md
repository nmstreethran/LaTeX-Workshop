The pdf viewer is based on [pdf.js](https://mozilla.github.io/pdf.js/) by Mozilla Foundation. Files are from the [prebuilt download version](https://mozilla.github.io/pdf.js/getting_started/#download). The reason we do not use `web/pdf_viewer.js` from `pdfjs-dist` package is that `pdf_viewer.js` does not provide features we need. `pdf_viewer.js` is much simpler than `viewer.js`. See [link](https://github.com/mozilla/pdf.js/issues/9318).

Mozilla [asks](https://mozilla.github.io/pdf.js/getting_started/) web developers to reskin `viewer.html` because Firefox users would think bugs of the viewer on the web site are ones of Firefox and would report them to the pdf.js team. See [link](https://github.com/mozilla/pdf.js/issues/5609). Our usage does not cause such a problem.