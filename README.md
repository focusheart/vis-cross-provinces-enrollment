# vis-cross-provinces-enrollment

Visualization for analyzing cross provinces enrollment in XJTUDLC.

The old version of this program using MySQL to query students' raw data 
which was stored in a local MySQL database which is not suitable to migrated to internet. 
I exported some PII-free data from raw data and using **AlaSQL** to handle the query on web page.
Therefore, this visualization can be used without accessing raw database.

## Usage

Since there is not server-sied query needed, any web server like Apache, Nginx is fine.
Or a simple python http server:

    python -m SimpleHTTPServer

and see this vis on `localhost:8888`

## Thanks

The China map visualization is powered by `ECharts` from Baidu (http://echarts.baidu.com/).
