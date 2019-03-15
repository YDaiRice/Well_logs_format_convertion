# Well_logs_format_convertion
This is a conversion program to convert external .las file to internal .las file for well logs.
External .las file is usually from clients and has been interpreated by geologists before handling over to geophysists. It is very informative and normally contains a lot of information than geophysists need. So, I wrote this conversion is plugin to only select the information usable in external .las file and output to a new .las with our own format, which can be used directly as input to internal plot software. 
I also included the code "LAS File Reader"created by Warren Weckesser in the repository for reference. I used some of its classes. 
