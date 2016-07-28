# JDK-on-Ubuntu
How to install JDK on Ubuntu (Linux)?



How to install "Open JDK" (Java developement kit) in Ubuntu (Linux)?

    Open Applicaction -> Accessories -> Terminal

    Type commandline as below...

    sudo apt-get install openjdk-7-jdk

    Type commandline as below...

    apt-cache search jdk

    (Note: openjdk-7-jdk is symbolically used here. You can choose the JDK version as per your requirement.)

    For "JAVA_HOME" (Environment Variable) type command as shown below, in "Terminal" using your installation path...

    export JAVA_HOME=/usr/lib/jvm/java-7-openjdk

    (Note: "/usr/lib/jvm/java-7-openjdk" is symbolically used here just for demostration.
    
    You should use your path as per your installation.)

    For "PATH" (Environment Variable) type command as shown below, in "Terminal" using your installation path...

    export PATH=$PATH:/usr/lib/jvm/java-7-openjdk/bin

    (Note: "/usr/lib/jvm/java-7-openjdk" is symbolically used here just for demostration. 
    You should use your path as per your installation.)

    Check for "open jdk" installation, just type command in "Terminal" as shown below

    javac -version


