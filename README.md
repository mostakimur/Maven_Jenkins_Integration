# Maven_Jenkins_Integration
Maven &amp; Jenkins Integration with Selenium: Complete Tutorial

What is Jenkins?
Jenkins is the leading open-source continuous integration tool developed by Hudson lab. It is cross-platform and can be used on Windows, Linux, Mac OS and Solaris environments. Jenkins is written in Java. Jenkin's chief usage is to monitor any job which can be SVN checkout, cron or any application states. It fires pre-configured actions when a particular step occurs in jobs.

<ul> <li><a href="#1">Important Features of Jenkins</a></li> <li><a href="#2">Why Jenkins and Selenium?</a></li> <li><a href="#8">What is Maven?</a></li> <li><a href="#3">Steps to install Maven and use it with TestNG Selenium</a></li> <li><a href="#4">Steps to Install Jenkins and configure it to Run Maven with TestNg Selenium</a></li> <li><a href="#5">Scheduling Jenkins for automatic execution.</a></li> <li><a href="#6">Jenkins with TestNg</a></li> <li><a href="#7">Benefits of Jenkins</a></li> </ul>

<h2><a id="1"></a>Important Features of Jenkins</h2>

<ul> <li>Change Support: Jenkins generates the list of all changes done in repositories like SVN.</li> <li>Permanent links: Jenkins provides direct links to the latest build or failed build that can be used for easy communication</li> <li>Installation: Jenkins is easy to install either using direct installation file (exe) or war file to deploy using application server.</li> <li>Email integration: Jenkins can be configured to email the content of the status of the build.</li> <li>Easy Configuration: To configure various tasks on Jenkins is easy.</li> <li>TestNG test: Jenkins can be configured to run the automation test build on<a href="/all-about-testng-and-selenium.html" onclick="ga('send', 'event', 'internal_linking', 'Maven &amp; Jenkins with Selenium: Complete Tutorial', 'Maven &amp; Jenkins with Selenium: Complete Tutorial');"> Testng </a>after each build of SVN.</li> <li>Multiple VMs: Jenkins can be configured to distribute the build on multiple machines.</li> <li>Project build: Jenkins documents the details of jar, version of jar and mapping of build and jar numbers.</li> <li>Plugins: 3<sup>rd</sup> party plugin can be configured in Jenkins to use features and additional functionality.</li> </ul>

<h2><a id="2"></a>Why Jenkins and Selenium?</h2>
<ul> <li>Running Selenium tests in Jenkins allows you to run your tests every time your software changes and deploy the software to a new environment when the tests pass.</li> <li>Jenkins can schedule your tests to run at specific time.</li> <li>You can save the execution history and Test Reports.</li> <li>Jenkins supports Maven for building and<a href="/software-testing.html" onclick="ga('send', 'event', 'internal_linking', 'Maven &amp; Jenkins with Selenium: Complete Tutorial', 'Maven &amp; Jenkins with Selenium: Complete Tutorial');"> Testing </a>a project in continuous integration.</li> </ul>

<h2><a id="8"></a>What is Maven?</h2>
Maven is a powerful project / build management tool, based on the concept of a POM (Project Object Model) that includes project information and configuration information for Maven such as construction directory, source directory, dependency, test source directory, Goals, plugins, etc. 

<h2>Why Maven &amp; Jenkins</h2>
<p>Selenium WebDriver is great for browser automation. But, when using it for testing and building a test framework, it feels underpowered. Integrating Maven with Selenium provides following benefits<strong><br></strong>Apache Maven provides support for managing the full lifecycle of a test project.</p>
<ul> <li>Maven is used to define project structure, dependencies, build, and test management.</li> <li>Using pom.xml(Maven) you can configure dependencies needed for building testing and running code.</li> <li>Maven automatically downloads the necessary files from the repository while building the project.</li> </ul>
