# computer_system_security_project
I wrote a program in Bash on Linux to perform the following tasks:
# identifying all network interfaces and testing all available IP addresses in an IP class
The program should be able to take an IP class as input, and it focuses on that class. It's worth mentioning that this program is executed at one or more specific points in the network.
# finding open port numbers and saving them in a CSV file
To achieve this, I tried to familiarize myself with Linux commands in this area and use them.
# connecting to discovered devices and testing a list of common usernames and passwords
I read this list from a CSV file located next to the program.
# gaining information
Once connected to the victim device, I attempted to place the second Bash script on it. For simplicity, I assumed that I have root access.
The second program on the victim device retrieves various information, such as system information, memory information, and CPU model, at specified intervals and sends it to the server.
# displaying information
On the server, I also wrote a program to display the received information in a web-based application. For this task, I created a simple backend and frontend.
