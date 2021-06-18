![image](https://user-images.githubusercontent.com/84008107/122566901-b57bdd00-d065-11eb-9561-88ca3fa7a003.png)

Before discusssing Maven lets first understand the purpose of build tool

#### Build Tool
A build tool is a tool that automatesg everything related to building the software project. Building a software project typically includes one or more of these activities:
<ul>
  <li> Generating source code ( Open a Sample project) </li>
  <li> Generating documentation from the source code.</li>
  <li> Compiling source code.</li>
  <li> Packaging compiled code into JAR files or ZIP files. </li>
  <li> Installing the packaged code on a server, in a repository or somewhere else.</li>
 </ul>

#### Maven (Java based build Tool)
Maven’s primary goal is to allow a developer to comprehend the complete state of a development effort in the shortest period of time. In order to attain this goal, Maven deals with several areas of concern:
<ul>
  <li> Making the build process easy</li>
  <li> Providing a uniform build system </li>
  <li>Providing quality project information</li>
  <li> Encouraging better development practices</li>
</ul>

#### Maven Overview - Core Concepts

Maven is centered around the concept of POM files (Project Object Model). A POM file is an XML representation of project resources like source code, test code, dependencies (external JARs used) etc. The POM contains references to all of these resources. The POM file should be located in the root directory of the project it belongs to.

Here is a diagram illustrating how Maven uses the POM file, and what the POM file primarily contains:
 
 ![image](https://user-images.githubusercontent.com/84008107/122586000-bd457c80-d079-11eb-986e-da36d1a788fe.png)

#### Maven Project directory Stucture

![image](https://user-images.githubusercontent.com/84008107/122586947-e3b7e780-d07a-11eb-8272-436d3e51993c.png)

![image](https://user-images.githubusercontent.com/84008107/122587131-195cd080-d07b-11eb-8150-02badc4c8369.png)

![image](https://user-images.githubusercontent.com/84008107/122587194-2a0d4680-d07b-11eb-9ba1-8d06755d4a33.png)


## Maven Build LifeCycle

![image](https://user-images.githubusercontent.com/84008107/122587267-414c3400-d07b-11eb-84b8-39016a90192d.png)

![image](https://user-images.githubusercontent.com/84008107/122587308-4c9f5f80-d07b-11eb-88c6-86f8b7230db3.png)



