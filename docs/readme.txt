WebRTC
“WebRTC is a free, open project that enables web browsers with Real-Time Communications (RTC) capabilities via simple Javascript APIs. The WebRTC components have been optimized to best serve this purpose.” webrtc.org
The WebRTC project will look at and deliver the following.
Documentation to explain WebRTC:
What is WebRTC
Who is driving WebRTC
Why do we need WebRTC
When and where will it be seen
Future benefits and possibilities
The project will review the commercial possibilities of adding functionality to the existing WebRTC product such as:
Screen sharing
File sharing
How best to design,code and implement this additional functionality
Present the findings to interested parties
Bring to market


Repository Structure
Following the initial suggestions of http://java.sun.com/blueprints/code/projectconventions.html#25692, here is the repository structure and an explanation of its parts.
├── README
├── apps
│ └── skeleton
│ ├── README
│ ├── bin
│ ├── build.xml
│ ├── conf
│ └── src
│ ├── main
│ └── test
├── components
├── docs
└── lib


Global Repository
The global repository is presented as follows when pulled from the repository.
Directory Name 
Directory Contents 
apps/ 
Contains all the apps of the project. Apps are self standing programs. 
components/ 
Contains components used in apps. 
docs/ 
Contains all the documentation of the project 
lib/ 
Global libraries used in the project. Ideally, all dependencies should be handled by the build system. 
README 
Details of the contents and how to use them 


Apps
Each app should contain at least the following directories.
Directory Name 
Directory Contents 
bin/ 
Shell scripts or batch files needed to run the app on a given platform 
conf/ 
Template configuration files needed by the app. 
src/ 
Source for the app. 
README 
Details of the contents and how to use them 
build.xml 
Build tasks for the app. This should gather all dependencies and build the application such that it can be used or tested. 

