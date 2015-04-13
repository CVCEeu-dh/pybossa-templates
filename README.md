# pybossa-templates
A collection of Pybossa templates for various micro crowdsourcing activities. A great tutorial for pybossa beginners is at http://docs.pybossa.com/en/latest/user/tutorial.html




requirements
---
A pybossa server, a pybossa user with an API key. Pybossa-pbs should be installed. Please Cfr the pybossa-pbs documentation.
Bewaare! A `.pybossa.cfg` should be created into your home folder. Otherwise, you should provide pybossa-pbs server and apikey for each request:
 
	pbs --server server --apikey key --help


installation
---
Clone the repo

	$ git clone

Then choose the project template, create a new project via pbs, add tasks. Note that every template folder contains a specific project.example.json file. Rename and edit the project.json file, then:

	$ cd pybossa-templates/date-discovery
	$ pbs add_tasks --tasks-file tasks.csv

You should now see the project 'date-discovery' appearing in your project space along with its tasks list.

Enjoy!

