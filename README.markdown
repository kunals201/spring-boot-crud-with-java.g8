A [Giter8][g8] template for Spring Boot Crud With Java!

# How to use
---
You can import the template using
`sbt new `

You will need to install Cassandra on your local machine for using this template. For information on how to install Cassandra, please refer to [http://cassandra.apache.org/download/]). After Downloading it, you need to run cassandra on port no. 9042 and Cassandra by default runs on same port which is 9042.

Then all you will have to do is run the project, you can use the following command for doing so -

`mvn spring-boot:run`

After strating this application you have to create table in cassandra you can create the table through the cqlsh. you can copy the create table command from below:
`create table student(id text, name text, marks text, PRIMARY KEY(id));`

The application will -
- Create a connection to the cassandra using the host and port provided in application.properties.

This application contains five endpoint which you can see in controller file.
The application will start on localhost:9091.
Hope this template comes in handy and you find it useful. Please reach out to me at - **kunal.sethi@knoldus.in** in case of any queries.

# Template license
----------------
Written in 2019 by [Knoldus Inc.](http://www.knoldus.com)

To the extent possible under law, the author(s) have dedicated all copyright and related
and neighboring rights to this template to the public domain worldwide.
This template is distributed without any warranty. See <http://creativecommons.org/publicdomain/zero/1.0/>.

[g8]: http://www.foundweekends.org/giter8/