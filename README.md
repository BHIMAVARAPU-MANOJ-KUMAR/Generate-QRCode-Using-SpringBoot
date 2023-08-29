# QRCode-Generation-Using-SpringBoot
A QR code generator using Spring Boot and "com.google.zxing" dependency from Maven Central Repository is a web application that can create and display QR codes for various types of data.
QR codes are two-dimensional barcodes that can store large amounts of information in a small space. They can be scanned by smartphones or other devices to access the encoded data.

To create a QR code generator using Spring Boot and com.google.zxing dependency, you will need to follow these steps:

1. Create a Spring Boot project using start.spring.io and add spring-boot-starter-web and com.google.zxing from Maven Repository, dependencies to the pom.xml file.
2. Add com.google.zxing:core and com.google.zxing:javase dependencies to the pom.xml file. These are the libraries that provide the functionality to generate and read QR codes.
3. Create a class named QRCodeGenerator that has two static methods: one to generate a QR code image and save it to a specified path, and another to generate a QR code as a byte array.
4. Create a controller class named MainController that has a method with @GetMapping annotation to handle the requests for generating and displaying QR codes. This method will call the QRCodeGenerator methods and return a file that shows the QR code image or the byte array.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

                                                                          THANK YOU ..... !! 
