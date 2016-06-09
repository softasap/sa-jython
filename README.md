sa-jython
=========

[![Build Status](https://travis-ci.org/softasap/sa-jython.svg?branch=master)](https://travis-ci.org/softasap/sa-jython)


optionally installs oracle java 6-7-8 controlled by java_version variable


Usage example:

Simple:

<pre>

     - {
         role: "sa-jython",
         jython_version: "2.7.0"
       }

</pre>


Advanced:
<pre>

     - {
         role: "sa-jython",
         jython_version: "2.7.0",
         option_install_java: true,
         java_version: 7
       }

</pre>
