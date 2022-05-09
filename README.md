<!--
 Copyright 2022 iamgabc
 
 Licensed under the Apache License, Version 2.0 (the "License");
 you may not use this file except in compliance with the License.
 You may obtain a copy of the License at
 
     http://www.apache.org/licenses/LICENSE-2.0
 
 Unless required by applicable law or agreed to in writing, software
 distributed under the License is distributed on an "AS IS" BASIS,
 WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 See the License for the specific language governing permissions and
 limitations under the License.
-->

<h1> Backend Basic With Spring </h1>
<p>powered by Gabriel Carvalho</p>

<div>
    <h2>Languages and Tools</h2>
    <code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/java/java.png" alt='Java'></code>
    <code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/maven/maven.png" alt='Maven'></code>
    <code><img height="30" src="https://www.seekpng.com/png/full/8-80775_spring-logo-png-transparent-spring-java.png" alt='Spring'></code>
    <code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/postgresql/postgresql.png" alt='Postgresql'></code>
</div>

<h2> How to run? </h2>

<p>
    1   - Download the .zip code from this project <br>
    2   - Unzip the package <br>
    3   - Open your IDE/code editor (I'm using eclipse) <br>
    4   - Import it as a java project and will run <br>
    Obs: may you need to install some dependencies like java <br>
    and maven in VSCODE. IDE will probably indentify the pom.xml file <br>
    5   - Create a database to the project <br>
    6   - Go to main file and run it, if you forgot some step or there is <br>
    some error, spring will warn you. 
</p>

<h2>Configure properties file</h2>
<h3>Use hibernate</h3>
<code>
    spring.jpa.properties.hibernate.jdbc.lob.non_contextual_creation=true
</code>

<h3>Set local database</h3>
<p>Pattern <'jdbc:postgresql://local_you_are_running:port/database_name'></p>
<code>
    spring.datasource.url= jdbc:postgresql://localhost:5432/YOUR_DATABASE_NAME
</code>

<h3>Set database username and password</h3>
<code>
    spring.datasource.username= YOUR USERNAME
    spring.datasource.password= YOUR PASSWORD
</code>

<h3>Active auto update</h3>
<code>
    spring.jpa.hibernate.ddl-auto=update
</code>

<h4> Nice hacking! </h4>