<h1>RabbitMQ Publisher-Consumer Node.js App</h1>

<p>This is a Node.js application that demonstrates the use of RabbitMQ for message publishing and consumption. It provides a simple example of how to create a publisher that sends messages to a RabbitMQ queue and a consumer that processes those messages.</p>

<h2>Getting Started</h2>

<h3>Prerequisites</h3>
<p>Before you begin, ensure you have the following installed:</p>
<ul>
    <li>Node.js (v14 or higher)</li>
    <li>RabbitMQ Server</li>
</ul>

<h3>Installation</h3>
<ol>
    <li>Clone the repository to your local machine:</li>
</ol>
<code>git clone https://github.com/pro-shubham-jain/rabbitmq-publisher-consumer.git</code>
<ol start="2">
    <li>Navigate to the project directory:</li>
</ol>
<code>cd rabbitmq-publisher-consumer</code>
<ol start="3">
    <li>Install the project dependencies:</li>
</ol>
<code>npm install</code>

<h2>Usage</h2>
<p>This project consists of two main components:</p>

<h3>Publisher</h3>
<p>The publisher sends messages to a RabbitMQ queue. To use it, follow these steps:</p>
<ol>
    <li>Edit the configuration file to specify your RabbitMQ server details (config.json).</li>
    <li>Run the publisher:</li>
</ol>
<code>node publisher.js</code>

<h3>Consumer</h3>
<p>The consumer processes messages from the RabbitMQ queue. To use it, follow these steps:</p>
<ol>
    <li>Edit the configuration file to specify your RabbitMQ server details (config.json).</li>
    <li>Run the consumer:</li>
</ol>
<code>node consumer.js</code>

<h2>Customization</h2>
<p>You can customize the publisher and consumer logic to fit your specific use case. Feel free to modify the code and configurations as needed.</p>
