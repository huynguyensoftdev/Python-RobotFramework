# Python-RobotFramework
Robot Framework is a common open-source automation framework for Acceptance Testing, Acceptance  Test-Driven Development (ATTD), and Robotic Process Automation (RPA). It uses a keyword-driven testing technology approach and the capabilities can be extended by testing libraries that can be implemented in Python or Java. 
//
python --version
pip --version
//
pip install robotframework
//
robot --version
rebot --version
//
Standard Libraries in robot framework
There are a bunch of standard libraries in the robot framework. Let’s discuss one by one

Builtin is a Robot Framework standard library that provides a set of common keywords that are needed very often so are automatically imported and always available.
Collection is a standard library that provides a set of keywords to handle python lists and dictionaries. The library has keywords to modify and derive values from lists and dictionaries.
DateTime is a robot framework that supports the creation and transformation of date and time values.
Dialogs is a Robot Framework standard library that provides a means to pause execution and receive input from users. The dialogs are a bit inconsistent depending on whether the tests are running or not.
OperatingSystem enables the various operating system-related tasks which are going to perform in the system when the robot framework is running. It can among other things executing commands, can also create and remove files directly as well.
Process is used for running processes, this library utilizes python submodules and its open class. The main use of the library is to wait for the running process in the system and compile using the run process keyword. we have start process on the background using start process and then we start the process or end process or terminate all process using wait for the process.
Screenshot is a test library for taking screenshots on the machine where the tests are being run.
String is a library used for string manipulations and verification.
Telnet provides communication over a telnet connection. The telnet library makes it possible to connect to a telnet server and execute commands over an open connection.
XML is also a robot framework text library for verifying and modifying XML documents.
Built-in Tools
There are mainly four built-in tools that are used in robot framework that are:

Testdoc – Robot Framework generates high-level HTML documentation based on test cases.
Rebot – Tools to generate logs and reports based on XML output and merge multiple outputs simultaneously.
Tidy – Robot Framework Tools for cleaning and changing the format of data files.
Libdoc – Tools for generating keyword documentation for libraries and resource files.
