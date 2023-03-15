## <img src='./logo.jpg' width='40' height='40'>tGoogleAnalyticsUnsampledReports

### Overview
This component managed un-sampled reports for Google Analytics.
It can only be used with a Google Analytics Premium Account.
It is recommended to take care the reports needs to be treated this way because the quotas for un-sampled reports are much lower than for normal reports.
It is a good practice to run the report first as normal reports with tGoogleAnalyticsInput and check the sampling state and decide which reports needs to run as un-sampled reports.
Un-sampled reports are treated in an asynchronous process. Everything whats necessary to do the steps are build-in in this component, except the download of the files. Please us the new component tGoogleDrive to do this.

Please read the linked documentation. The procedure is a bit complex!

In case of questions feel free to contact me: jan.lolling@gmail.com
### Details
* Create an unsampled report
* Check the status of your unsampled reports
* Parse the downloaded report file (to download it use tGoogleDrive component)
* Provide the output as plain rows or as normalized output
### Images
<a href='./screenshots/v_2.9__6.jpg'><img src='./screenshots/v_2.9__6.jpg' ></a>
<a href='./screenshots/v_2.9__5.jpg'><img src='./screenshots/v_2.9__5.jpg' ></a>
<a href='./screenshots/v_2.8__4.jpg'><img src='./screenshots/v_2.8__4.jpg' ></a>
<a href='./screenshots/v_2.8__3.jpg'><img src='./screenshots/v_2.8__3.jpg' ></a>
<a href='./screenshots/v_2.10__2.jpg'><img src='./screenshots/v_2.10__2.jpg' ></a>


### Resources
 * <a href=https://github.com/jlolling/talendcomp_tGoogleAnalyticsUnsampledReports>Source Code on Github</a>
 * <a href=http://jan-lolling.de/talend/components/help/tGoogleAnalyticsUnsampledReports.pdf>Documentation</a>
 * <a href=http://jan-lolling.de/talend/howtos/google_service_account/create-a-google-service-account.html>How to create a Google service account</a>

#### Release Notes

##### 2.8 - 2015-09-16 15:37:18
* Improved error handling, Internal Server Error will cause a retry
##### 2.9 - 2015-09-25 16:17:52
* Fixed bug in list function: list was limited to the first 1000 reports. Google has introduced a paging here in August 2015.
##### 2.10 - 2015-12-18 17:56:50
* updated Google APIs used
### Compatible
 -  5.3 (obsolete)
 -   5.4 (obsolete)
 -   5.5 (obsolete)
 -   5.6 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)
 -   6.3 (obsolete)
 -   6.4 (obsolete)
 -  6.5 (retired)
 -  7.0 (retired)
 -  7.1 (retired)
 - 7.2
 - 7.3