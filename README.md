- Role Name

This Role will help to perform bulk registration across your infrastructure to do a bulk registration to the satellite server. This is role is in its development stage. This is very new code.

- Requirements

During the development, it will be considered that all the hosts will have "root" as common user and a comman password.


- How to Run the role on Red Hat Satellite or Foreman Server or any Server? 

- Command: 
(In the directory where the role is present.) 

 >  $ ansible-playbook -i inventory_file role-run.yml -b --ask-pass
 
 - Variables: 
  > There are a few inputs that you need to mention before you run the role. Based on the variables the roles will run. 

- Author Information

Name: Jaskaran Singh Narula narula.jaskaran@gamil.com

