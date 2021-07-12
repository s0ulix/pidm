# pidm

This python module help you to download content with multiple parallel threads. So your download speed may increase.

A simple python module developed by me.

Feel free to use it in any of your projects where you have to download some content from your python script. It will make this process faster with the help of multithreading and byte stream downloading.

Just install it with 𝐩𝐢𝐩 𝐢𝐧𝐬𝐭𝐚𝐥𝐥 𝐩𝐢𝐝𝐦

and create an object of Download class with 1 to 4 parameters,
1. url-as per the name the URL of the content.
2. threads- how many threads to run in parallel, need not be defined, the default value is 8.
3. outfile- the name for the file, if not given module will get automatically from the request.
4. flush- True by default no need to change it or pass it. If you choose flush=false it will not delete the temp files created.

You can see how to use it in your project from the picture below.
During downloading some temp files will be created in your folder but will be deleted automatically after the run.

obj.result/bool(obj) will return True or false if the download was successful or not.

It's totally platform-independent .
![image](https://user-images.githubusercontent.com/54552051/125333565-01b9f480-e368-11eb-9a3c-c166e9f03d31.png)

