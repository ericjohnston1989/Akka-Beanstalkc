<h4>Akka-Beanstalkc</h4>

<p>Supports Akka version: 2.2.3</p>

<p>This is a very simple project wrapping Beanstalk into an Akka actor. This way we can have one actor handling communication with the beanstalkd job queue, And other parts of our program that need to interact with beanstalk can send a message to its enclosing actor.</p>