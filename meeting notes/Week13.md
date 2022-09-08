---
title: Week 13
author: Rohit Pandey
author_url: https://github.com/rohitpandey49
---

# GSoC Week 13

## Updates

- On issue [#2214](https://github.com/fossology/fossology/issues/2214) - Detecting licenses declared in LICENSE file and LICENSES folder:
    - Added `SearchHelperDao.php` in lib/php/dao and made changes in `src/www/ui/api/Controllers/SearchController.php`, `src/www/ui/ajax-notice-files.php` and `src/www/ui/search.php` files that uses function of this file.
    - To detect the LICENSES directory, I created `DetectLicensesFolder.php` in src/lib/php/BusinessRules. The getDeclearedLicense() function returns an array with license Ids declared in LICENSES directory.
    - To compare the license findings, I created `ReuseReportProcessor.php` in src/lib/php/BusinessRules. GetReuseSummary() function compares the cleared licenses and declared licenses.
    - `src/www/ui/async/AjaxReuseReport.php` handle AJAX request and return reuse summary report as JSON response.
- Solve requested changes on existing PR.
- Cleared doubts regarding the AJAX call.

## Conclusions and further plans

- Implement AJAX call and add reuse summary report table in License Browse page.
- Write a blog on medium describing the journey of Google Summer of Code with Fossology and contributions made during the tenure.