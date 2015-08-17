#Stale PDF Report

The Stale PDF Report generates a table view of all the PDF files in the CMS, with stale PDFs highlighted in red. PDFs are considered stale when their last modified year is equal to or older than the configured year. For example this past summer, we looked at PDFs that haven’t been updated since 2013.

By default, the PDFs are grouped by subfolder, which, along with the Last Modified By column, offer content ownership insight.

This report is built using an index block and Velocity format by indexing File assets within the application and displaying those that have a .pdf suffix.