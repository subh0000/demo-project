# Demo-Project
The Demo project is built in the test environment to detail out system, application, databases related metrics and events collection, correlation,alerting and predictive analysis purpose.
<h1>Architecture Diagram</h1>
The following image represents high-level architecture.
<img src="https://github.com/subh0000/demo-project/blob/master/images/architecture.JPG">
The above architectural diagram shows end to end data flow and the components are used in this demo project as follows:<br/>
- Telegraf Agent.<br/>
- Influx DB.<br/>
- Kapacitor.<br/>
- Grafana.<br/>
- Apache Kafka.<br/>
- Ansible.<br/>
- Jenkins.<br/>

<h2> Setup and Configurations </h2><br/>
<h3> Ansible Setup and Configurations </h3><br/>
For Ansible setup and configurations, download the document from the following link:<br/>
https://github.com/subh0000/demo-project/blob/master/docs/Ansible_Setup_Configurations.docx <br/>
<B>Note</B>: the yaml files are uploaded in the config directory to install and configure the following using Ansible automation </br>
1. Telegraf Agent.</br>
2. Influx DB.</br>
3. Kapacitor.</br>
4. Grafana. </br>
<h3> Kafka Setup and Configurations </h3><br/>
For Kafka setup and configurations, download the document from the following link:<br/>
https://github.com/subh0000/demo-project/blob/master/docs/Kafka_Setup_Configurations.docx </br>
<h3> Enabling CI/CD Pipeline using Jenkins and Ansible </h3><br/>
For CI/CD Pipeline using Jenkins and Ansible, download the document from the following link:<br/>
https://github.com/subh0000/demo-project/blob/master/docs/Jenkins-Ansible-CI-CD%20Pipeline.docx </br>

<h2> Test Artifacts </h2><br/>
The test artifacts capture the Grafana Dashboard visualization metrics. Download the document from the following link:</br>
https://github.com/subh0000/demo-project/blob/master/docs/Grafana%20Dashboard.docx</br>

<h2> About Telegraf agent, Kapacitor and InfluxDB </h2></br>
Telegraf is a plugin-driven server agent for collecting and sending metrics and events from databases, systems, and IoT sensors. Telegraf is written in Go and compiles into a single binary with no external dependencies, and requires a very minimal memory footprint.</br>

<h4>Collect and send all kinds of data:</h4></br>
<b>Database</b>: Connect to datasources like MongoDB, MySQL, Redis, and others to collect and send metrics.</br>
<b>Systems</b>: Collect metrics from your modern stack of cloud platforms, containers, and orchestrators.</br>
<b>IoT sensors</b>: Collect critical stateful data (pressure levels, temp levels, etc.) from IoT sensors and devices.</br>
<b>Agent</b>: Telegraf can collect metrics from a wide array of inputs and write them into a wide array of outputs. It is plugin-driven for both collection and output of data so it is easily extendable. It is written in Go, which means that it is a compiled and standalone binary that can be executed on any system with no need for external dependencies, no npm, pip, gem, or other package management tools required.</br>

<b>Coverage</b>: With 200+ plugins already written by subject matter experts on the data in the community, it is easy to start collecting metrics from your end-points. Even better, the ease of plugin development means you can build your own plugin to fit with your monitoring needs. You can even use Telegraf to parse the input data formats into metrics. These include: InfluxDB Line Protocol, JSON, Graphite, Value, Nagios, and Collectd.</br>

<b>Flexible</b>: The Telegraf plugin architecture supports your processes and does not force you to change your workflows to work with the technology. Whether you need it to sit on the edge, or in a centralized manner, it just fits with your architecture instead of the other way around. Telegraf’s flexibility makes it an easy decision to implement.</br>

<img src="https://github.com/subh0000/demo-project/blob/master/images/Influx-1.0-Diagram.jpg">
