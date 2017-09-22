# Commands

- Create a user
'create role testuser with password 'testuser' login;'
- Create a database
'create database fubar'
- Revoke public access to database
'revoke all on database fubar from public;'
- Give access to new user
'grant all privileges on database fubar to testuser'




# References
http://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Appendix.PostgreSQL.CommonDBATasks.html#Appendix.PostgreSQL.CommonDBATasks.Roles
https://www.cyberciti.biz/faq/howto-add-postgresql-user-account/