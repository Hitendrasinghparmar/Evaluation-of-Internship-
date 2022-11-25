# Evaluation-of-Internship-
# Exploit an Android device using payload injected APK

This project describes how to perform exploitation on an android device using tools provided by the Kali Linux operating system such as MSFvenom, Metasploit framework. My intention is to gain access to an android device using the Metasploit framework. To do that we utilizing a payload that we create using MSFvenom. The main issue I faced in this project is, how to send a payload to the victim's phone without letting the victim know that this payload is a malicious payload. To overcome that issue, we are utilizing an original APK and inject a payload to that particular APK with the help of tools such as apktool and keytool.



## In this exploitation I used 5 main commands.

1.	sysinfo to see the system information such as OS

2.	dump_ sms to fetch all the text messages in victim device

3.	dump_callog to fetch all the call logs in victim device

4.	app_list to see all the applications in victim’s device

5.	webcam_stream to exploit the camera of the victim device




## PREVENTION METHODS


These types of attacks can be done to our mobile phones too so as users we have to be alert about these type of attacks there are some prevention steps that we can take to keep our android device safe.



•	Be alert about the malicious links receive to the mobile device.

•	Never trust a unknow 3rd party application. And never turn off the install from unknown sources feature.


•	Do not let any unauthorized user to access the mobile phone physically.

•	Update mobile phone and operating system regularly.

•	Install an antivirus software to mobile devices.

•	Regularly back up mobile devices.




## RESULTS OF EXPLOITATION

Results I received by entering these commands such as call logs, text messages and system information can be considered as the results of this exploitation.

The ability to exploit an android device and find extremely personal information was explained step by step throughout this Report. It is clear that no matter how advanced the android operating system, it is still weak in some points. While this situation is an advantage for white hat hacking, such as identifying criminals, the disadvantages of this situation are relatively large. Therefore, we all need to make sure we are using our mobile phones in a manner of protect our privacy.
