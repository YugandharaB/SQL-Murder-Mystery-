# SQL-Murder-Mystery-
SQL Assignments where I have solved the SQL Murder mystery 

SQL Murder Mystery 
1)	SELECT * 
FROM crime_scene_report 
WHERE city = 'SQL City'AND type = 'murder' AND DATE = 20180115
2)	SELECT * 
FROM person 
WHERE address_street_name = 'Franklin Ave' AND name LIKE 'Annabel%'
3)	SELECT * 
FROM get_fit_now_check_in WHERE check_in_date = 20180115;
4)	SELECT * 
FROM get_fit_now_member
WHERE name LIKE 'Annabel%' ;
5)	SELECT * 
FROM facebook_event_checkin
WHERE person_id = 16371
6)	SELECT * 
FROM interview
WHERE person_id = 16371
7)	SELECT * 
FROM interview
WHERE person_id = 14887
8)	SELECT * 
FROM get_fit_now_member
WHERE membership_status = 'gold' AND id LIKE '48Z%'
9)	SELECT * 
FROM person
WHERE license_id = 423327
10)	SELECT * 
FROM income 
WHERE ssn = '871539279'

11)	SELECT * 
FROM interview
WHERE person_id = 67318


12)	SELECT * 
FROM drivers_license
WHERE car_make LIKE 'Tesla%' AND car_model = 'Model S' AND gender = 'female' AND hair_color = 'red' AND height = 65;

13)	SELECT * 
FROM facebook_event_checkin
where event_name LIKE '%SQL Symphony Concert%' 

