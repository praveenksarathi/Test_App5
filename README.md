# Test_App5
Python Test App for ALL REST

#Application Needs Input

#GET :

For Getting all the tasks currently listed
1 ) "curl -i http://localhost:5000/todo/api/v1.0/tasks"

To list the details of a particular task : Task_ID
2 ) "curl -i http://localhost:5000/todo/api/v1.0/tasks/Task_ID"

#POST :

curl -i -H "Content-Type: application/json" -X POST -d '{"FIELD1":"DATA","FIELD2":"DATA","FIELD3":"DATA",...}' http://localhost:5000/todo/api/v1.0/tasks

where FIELD is the representation of KEY in a JSON , and DATA represents VALUE in JSON.

#DELETE:

For Deleting Details on particular task :Task_ID with method : DELETE

curl -i http://localhost:5000/todo/api/v1.0/tasks/Task_ID

#PUT:

For Updating Details on particular task :TASK_ID

curl -i -H "Content-Type: application/json" -X PUT -d '{"FIELD":VALUE}' http://localhost:5000/todo/api/v1.0/tasks/TASK_ID

Where FIELD is the field in the collection whose value which you want to update where VALUE is the data that is to be updated in FIELD
