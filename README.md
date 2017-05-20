# reddragon
To install this package
**npm i reddragon**

How to use and start your api in debug mode
DEBUG=true node src/server

To debug
debug excepts two parameters, one for the title and one for status
now the status aspect should be pass or fail

**reddragon.debug('title', 'status');**

Now the status can be one of three things, success means it was a successful, warn means that the log may have potential errors, and fail means that there is an error
