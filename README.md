# Group-Chat-Java

Group based chatting platform in Java

Group chat platform using MulticastSocket class is made. A MulticastSocket is a (UDP) DatagramSocket, with additional capabilities for joining “groups” of other multicast hosts on the internet.

Save the file as GroupChat.java and compile it using javac and then run the program using two command line arguments as specified.
>>javac GroupChat.java
>>java GroupChat 225.0.0.0 8888

A multicast host is specified by a class D IP address and by a standard UDP port number. Class D IP addresses are in the range 224.0.0.0 to 239.255.255.255, inclusive. The address 224.0.0.0 is reserved and should not be used.

We have used the multicast host IP address as 225.0.0.0 and the port number as 8888 (since the port numbers 0 through 1023 are reserved). For leaving the group, any of the user can type in Exit to terminate the session.

Socket programming is meant for distributed programming. The same piece of code snippet when present on different machines which have Java installed can satisfy that requirement. This is just the bare bones service logic.
