# VineforceTest

All files are uploaded along with Database script file and backup,

#Notes : 
  Connection string must be updated in WebAPI project appsetting.json before running the project.
  First start api project then start angular project using ng serve --open
  Scaffold the DbContext if needed,
  Scaffold-DbContext "Data Source=ServerName;Initial Catalog=DemoDatabase;Integrated Security=True;" Microsoft.EntityFrameworkCore.SqlServer -OutputDir Models -force
  Component
    Country : CRUD Implemented in Angular and Dot net core api, Country can't be deleted if a state entry is made because of forein key constraint,
    
    State : CRUD Implemented in Angular and Dot net core api, Country must be selected in order to add a state, 
    
    
 Single form is used for both Add and update form
 
 
 

