---
layout: post
title: "Migrating Django Database Using south"
description: ""
category: 
tags: [django]
---
{% include JB/setup %}

		
	 pip install south

	

	
 In settings.py  add 'south' to INSTALLED_APPS
	

	
	  ./manage.py 
	
  		you can see all the extra functionalites of south 


	
	 ./manage.py schemamigration Mymodel --initial
	
 		to build your migration history


 and now makes changes to your Models and run
		 
		./manage.py schemamigration --auto
		
   	to auto detect changes in models


 now you can apply migration with following commands
 
		
 	./manage.py migrate Mymodel
		

to rollback the back to changes you've made
		 
	./manage.py migrate Mymodel 002(migration number)
		











