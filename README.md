Dear, 

I’ve completed performance test on frequently used API for test site https://reqres.in.

Test executed for the below mentioned scenario in server https://reqres.in. 

10 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 1.333 And Total Concurrent API requested: 80.

50 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 6.667 And Total Concurrent API requested: 400.

100 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 13.3 And Total Concurrent API requested: 800.

While executed 100 concurrent request, found  1 request got connection timeout and error rate is 0.13%.

Summary: Summary: Server can handle almost concurrent 80 API call with almost zero (0) error rate.
![screencapture-file-C-Users-ONTORA-Downloads-Compressed-JMETER-Jmeter-Performance-Testing-reqres-main-reqres-t100-html-reqres-t100-html-2024-03-29-16_11_43](https://github.com/AntaraPaul091/Jmeter_Performance_Testing_reqres-main/assets/66947824/9e316193-8a76-42dd-afec-983b38367169)
