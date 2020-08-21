# Nanohttpd_android_app
Android App to transfer Files according to priorities using Nanohttpd and broadcasting in the Post Disaster situatuions.

NanoHttpd is an open-source, web server that is suitable for embedding in embedded device like
raspberry pi , up-squared etc. ,smartphones etc written in the Java programming language. The
source code consists of a single .java file. It can be used as a library component in developing other
software for serving files.

Why NANOHTTPD ?
1. Due to better functionality of HTTP Protocols at application layer in Network Hierarchy, we have
chosen NanoHTTPD server.
2. This serves the files to the client peers .
3. We have implemented a NanoHTTPD Server where a file can be downloaded when the file name is
given in the url.

Our main motive is to a develop a multi server and multi client system, such that after implementation the
files in each node in an common network are balanced.

1. Identifies the nodes in a network.
2. The device shouts its IP address and listens
3. Server is started using Nanohttpd.
4. Prioritize the files in the system.
5. Summary vector exchange.
6. As soon as it receives an IP address, it starts a
thread for downloading the file.
7. Downloading of files using TCP Client.
