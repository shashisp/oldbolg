---
layout: post
title: "Migrating Django Database Using south"
description: ""
category: 
tags: [django]
---
{% include JB/setup %}

Migrating your DB using south


```
1.pip install south

```
```
2. settings.py  add 'south'
```
```
3. ./manage.py 
```
  you can see all the extra functionalites of south 


```
4../manage.py schemamigration Mymodel --initial
```
 to build your migration history


5. and now makes changes to your Models and run
``` 
./manage.py schemamigration --auto
```
   to auto detect changes in models

6. now you can apply migration with following commands
 
```
 ./manage.py migrate Mymodel
```
7. and rollback the back to changes you've made
``` 
./manage.py migrate Mymodel 002(migration number)
```

















