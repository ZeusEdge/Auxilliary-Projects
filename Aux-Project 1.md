# ONBOARDING SHELL SCRIPT
Specifications:

Check the server if a user with that name already exists => ls /home

Create each user with the first name on the server as seen in the csv file => sudo useradd -m "username"

The "-m" flag ensures that the user being created has a default home folder.

