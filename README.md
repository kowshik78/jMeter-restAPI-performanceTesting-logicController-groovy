# jMeter-restAPI-concurrency-logicController-groovy
In this an Apache JMeter template, I use to test the performance of my REST APIs.
The goal is to test concurrency performance of some blockchain APIs using logic controller.
<h3>Two basic controllers- Simple Controller and Module Controller are used very better maintenance</h3>
APIs are kept within simple controller called API
Controller 1 is a module controller to controller the APIs.
<h3>Some operation need UI handling.So, external plugin "Selenium/Webdriver Support" is used. After installation of this plugin, 6 types of driver configs will be found under config ELement. In this project, Chrome Driver Config is used.</h3> 
<h3>For UI aotomation, Webdriver Sampler is taken and groovy is chose for scripting.</h3>
