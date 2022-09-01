# NanoHTTPD – a tiny web server in Java (LaunchDarkly fork)

[![Circle CI](https://circleci.com/gh/launchdarkly-labs/nanohttpd.svg?style=shield)](https://circleci.com/gh/launchdarkly-labs/nanohttpd)
[![Javadocs](http://javadoc.io/badge/com.launchdarkly.labs/nanohttpd.svg)](http://javadoc.io/doc/com.launchdarkly.labs/nanohttpd)

*NanoHTTPD* is a light-weight HTTP server designed for embedding in other applications, released under a Modified BSD licence.

This is a fork of the original NanoHTTPD project (https://github.com/NanoHttpd/nanohttpd) which is maintained by LaunchDarkly for the specific purpose of testing LaunchDarkly Java-based open-source components, including both server-side Java and Android code, where a lightweight embeddable HTTP server is desirable. Modifications from the upstream implementation will generally be limited to adding new capabilities that are required for this purpose, and fixing bugs.

LaunchDarkly cannot provide support for use of this library in any other context.
