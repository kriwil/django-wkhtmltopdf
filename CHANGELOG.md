Changelog for django-wkhtmltopdf
================================


0.3
---

* Fix a bug where temporary files were removed before the PDF was generated
  when using the header & footer options.
* Only set the `Content-Disposition` header in the response if `filename` is set.
* Added a Makefile for deployments.
* Added 2.6 requirement to the README.


0.2.2
-----

* Create a request context if one hasn't been passed into the view.


0.2.1
-----

* Use `get_template_names()` for extra extensibility.
* Be clear with `template_to_temp_file`'s arguments.


0.2
---

* Added option for orientation. Defaults to 'portrait', can be 'landscape'.
* Deprecated PdfTemplateView in preference of PDFTemplateView.
* Deprecated PdfResponse in preference of PDFResponse.
* Made PDFResponse more extensible.


0.1.1
-----
