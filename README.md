#building_projects
This is a sandbox for now, including projects to be added to the MTC development project list

##the goal
in the bayarea_urbansim repository we track development projects in a csv with the following columns:

development_projects_id,
raw_id,
name,
site_name,
action,
scen0,
scen3,
scen1,
scen2,
address,
city,
zip,
county,
x,
y,
geom_id,
year_built,
duration,
building_type_id,
building_type,
building_sqft,
non_residential_sqft,
residential_units,
unit_ave_sqft,
tenure,
rent_type,
stories,
parking_spaces,
Average Weighted Rent,
rent_ave_sqft,
rent_ave_unit,
last_sale_year,
last_sale_price

@bobbylu has a list of development projects with the following columns:

jursidiction - list of city's-go to each city website, find projects
url(source)  
x,y - from latlong.net  
location - address from city  
units,  
commercial/office,status,  

the goal is to merge bobby's data into our csv in bayarea_urbansim. 

##to do 

we probably need to resolve some column differences. bobby's first commit here shows an example of a development project that we added without resolving many column differences. it would be interesting to see if we can add it to the bayarea_urbansim repository on a branch and have it run without error. 
