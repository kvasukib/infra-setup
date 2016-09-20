# Basic Setup

## G++ Upgrade <br/>
Upgrade g++ to g++-5 as our repository uses c++14 <br/>
http://askubuntu.com/questions/618474/how-to-install-the-latest-gcurrently-5-1-in-ubuntucurrently-14-04 <br/>
sudo update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-5 60 --slave /usr/bin/g++ g++ /usr/bin/g++-5 <br/>
Verify if the upgradation is successful or not

## AWS CPP SDK Installation <br/>
Install AWS CPP SDK <br/>
Pre-requisites : Needed CMake <br/>
https://github.com/aws/aws-sdk-cpp <br/>
https://aws.amazon.com/documentation/sdk-for-cpp/ <br/>
Instructions to Install : http://sdk.amazonaws.com/cpp/api/LATEST/index.html <br/>

## Repository Setup
Make a git clone of our repository 
Run ./autogen.sh
Run configure
Run "make all" to verify build succeeds

## Papers :
OpenLambda : 
http://www-di.inf.puc-rio.br/~endler/paperlinks/CLOUD-2010.pdf <br/>
Slides          : https://www.usenix.org/sites/default/files/conference/protected-files/hotcloud16_slides_hendrickson.pdf <br/>
Paper           : https://www.usenix.org/system/files/conference/hotcloud16/hotcloud16_hendrickson.pdf <br/>
Detailed Slides : http://www.open-lambda.org/resources/slides/ol-first-meeting.pdf <br/>

Distributed Video Processing : 
https://www.usenix.org/system/files/conference/hotcloud16/hotcloud16_hendrickson.pdf <br/>

## References:
1. https://github.com/open-lambda/open-lambda <br/>
2. https://open-lambda.org/index.htm <br/>
3. https://github.com/sensorstorm/StormCV <br/>
4. https://github.com/apache/spark <br/>





