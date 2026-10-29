Warehouse Operations Dashboard — Improved

Unzip this folder, then open index.html in Chrome or Edge.
Import Excel workbooks (.xlsx or .xls) using the Requested SO and Requested TR selectors. Weekly OpsActivityLog is optional.
Internet is required to load the Excel parsing library.
Imported data stays in this browser profile. Export saved data regularly and retain your original reports. Opening this version at a different location may use separate browser storage; keep the original dashboard and its data backup.

Updates: refreshed responsive layout, Excel-only imports, clearer import counts and errors, turnaround breakdown chart, contextual empty states, full dates in daily reports, accessible focus and status indicators.

Navigation: use the Reports dropdown for overview, daily/trends, carriers, product lines, rollover, and OpsActivityLog. Use Weekly Performance → Pickers or Packers for separate names, SO/TR and total packed orders, and available packed-line totals for the selected Monday–Sunday week. Import the Excel OpsActivityLog first. Lines require an explicit per-order Packed Lines, Lines Packed, Packed Line Count, or Number of Packed Lines column; missing counts show Unavailable or partial. No picker percentages are shown. Repeated order rows use the largest reported line total in that import.

Picker names are read from Picker / Picked By / First Picked By columns; packer names are read separately from Packer / Packed By / First Packed By columns. Missing roles show Unassigned. Re-upload older Excel activity logs to populate separate role names; existing order history is retained. No percentages appear in either weekly team report.

Appearance: MSI-inspired black header, white report panels, dark text, blue controls, and green, amber and coral performance accents, and an MSI text wordmark. Report calculations and browser storage are unchanged by this visual update.

Manual backorders: in the overview, enter the number of backordered orders and click Save count. Requested excluding backorders shows the original requested count minus that entry (for example, 3,055 minus 300 = 2,755). The original total remains visible. Counts are saved in this browser separately for each exact date range and SO/TR selection, included in Export saved data, and removed by Clear saved data. They are excluded from the overview unpacked count and Packed / Adjusted requested percentage. They do not identify specific orders, change timed packing percentages, or modify detailed tables. A backorder count cannot exceed the unpacked count; update it if later imports reduce that count.
