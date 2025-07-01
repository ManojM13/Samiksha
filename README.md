# Samiksha
The Samiksha is a web application which avoids more manual hours that need to spend in record keeping and calculating votes. Through this the users and the candidates are registered online. Their information is stored in the database the admin can easily access the details of the voters and the candidates. The voters are allowed to vote online they can even vote by sitting at home. Every User allowed to vote
only once so there is no chance of duplicated votes. This application keeps the data in a centralized way which is available to all the users simultaneously. It is very easy to manage statics data in database.
They can easily use the tool that decreases manual hours spending for normal things and hence increases the performance.

<h1>Getting Started</h1>
<p>These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.</p>

<h2>Prerequisites</h2>
<code>python== 3.5 or up and django==2.0 or up</code>

<h2>Installing</h2>
<pre>open terminal and type</pre>
<code>git clone https://github.com/devmahmud/Django-poll-app.git</code><br><br>

<h4>or simply download using the url below</h4>
<code>https://github.com/devmahmud/Django-poll-app.git</code><br>

<h2>To migrate the database open terminal in project directory and type</h2>
<code>python manage.py makemigrations</code><br>
<code>python manage.py migrate</code>

<h2>To use admin panel you need to create superuser using this command </h2>
<code>python manage.py createsuperuser</code>

<h2>To Create some dummy text data for your app follow the step below:</h2>
<code>pip install faker</code>
<code>python manage.py shell</code>
<code>import seeder</code>
<code>seeder.seed_all(30)</code>
<p>Here 30 is a number of entry. You can use it as your own</p>

<h2> To run the program in local server use the following command </h2>
<code>python manage.py runserver</code>

<p>Then go to http://127.0.0.1:8000/home in your browser</p>



<div align="center">
    <h3>========Thank You !!!=========</h3>
</div>

