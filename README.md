# protobuf-setup
Python script for quick environment setup for using swift protobuf
------
<p>
There are a several tools and libraries that you have to install before using protocol buffers in Swift.
This script will take a while to install, especially when installing Google’s protocol buffer libraries.
</p>

Execution:

After cloning/downloading the project, simple cd into your project directory and executre the 'protoInstallation.sh' script.

$ ./protoInstallation.sh

<i>Note: You may be prompted for admin password. </i>

When the script completes, run it again to ensure you get output similar to the following:

![alt tag](https://github.com/raeidsaqur/protobuf-setup/blob/master/screenshot.png)

Here’s what the script has accomplished:
<ol>
<li>Installed Flask to run the Python Local Server.</li>
<li>Built the Google protocol buffer compiler from Starter/protobuf-3.1.0.</li>
<li>Installed the protocol buffer module for Python so the server can use the Protobuf library.</li>
<li>Moved the Swift Protobuf plugin protoc-gen-swift into /usr/local/bin. This allows the Protobuf compiler to generate Swift structs.</li>
</ol>

**You now have everything you need to start using protocol buffers!**

