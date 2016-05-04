# Amazon S3 Services API documentation version 2006-03-01
https://s3.amazonaws.com/

### Headline
Amazon S3 is cloud storage for the Internet. It is designed to make web-scale computing easier for developers. Amazon S3 provides a simple web-services interface that can be used to store and retrieve any amount of data, at any time, from anywhere on the web. It gives any developer access to the same highly scalable, reliable, secure, fast, inexpensive infrastructure that Amazon uses to run its own global network of web sites. The service aims to maximize benefits of scale and to pass those benefits on to developers.

---

## GET Service
This is base resource type described common request and response headers and error response codes

### /

* **get**: This implementation of the GET operation returns a list of all buckets owned by the authenticated sender of the request.
To authenticate a request, you must use a valid AWS Access Key ID that is registered with Amazon S3.
Anonymous requests cannot list buckets, and you cannot list buckets that you did not create.
Syntax
------
GET / HTTP/1.1
Host: s3.amazonaws.com
Date: date
Region: us-east-1
Authorization: signatureValue

