# Hello-Kitty-Cafe
We LIVE LIFE To The FULLEST

If anyone here needs to see Malware patterns in any .exe file you can use this program I made in python

I worked with chatgpt to code my exe malware sniffer/dumper basically it scans any exe file for virus type files without extracting the exe file so it wouldn't cause most type of infection to your machine

Instructions: Click on Browse Application to select an executable file. This will allow the Cyber Capture to scan the exe file directory path. Then Click on the Cyber Capture Directory button this will allow you to select the path where you want the Cyber Capture to be created in. Then Click on Start Cyber Capture button this will prompt the software to scan the selected exe file for these types of files:

virus_patterns = { r'.exe', r'.dll', r'.vbs', r'.ps1', r'.bat', r'.doc', r'.docx', r'.pdf', r'.html', r'.htm', r'.php', r'.js', r'.css', r'.jar', r'.zip', r'.rar', r'.inj', }

Note that some exe files may contain Malicious content that can bypass the software and may cause infection to your machine! Once the cyber Capture is finished doing it's job.

It will write 4 files: possible malicious script dir.txt possible malicious binary scripting.txt malicious pattern.txt binary target.txt

Additional Upcoming features Include: -Dumping the actual code and the actual files from any exe -Cleaning exe files with either advanced features including choosing what files to delete or cleaning exe files automatically -Adding advanced file targeting and advanced silent targeting features

![276786094-b84b9750-2dc7-49a0-8e40-ed9395970318](https://github.com/user-attachments/assets/03e6b6cf-9a0c-4e56-be13-2abb2d8b010f)
