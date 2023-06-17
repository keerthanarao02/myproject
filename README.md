# myproject
 backend developer for a company that solves vehicle problems on the go, anywhere and anytime. A team of  agents work towards receiving the request, talking to the customer facing the problem and assigning them an available mechanic.
 1. Create a new Django project named "myproject".
2. Inside the project, create an app named "myapp".
3. Define a model named "Issue" in "myapp" with the following fields:
a. issueID
b. userID
c. location (location of request)
d. problem (Problem faced by the user)
e. time (time of request)
f. Status (INQUEUE, ASSIGNED, DISPATCHED)
4. Define another model named "Agents" in "myapp" with the following fields:
a. AgentID
b. Queue (no of requests pending in his queue)
5. Define another model named "Mechanic" in "myapp" with the following fields:
a. mechanicID
b. availability (initially true)
6. New Issue: for the user to send a request stating the problem, his location, time, and userID
7. Once the issue is created you have to randomly assign an agent with the least requests in his
queue.
9. There are  mechanics available
10. It is left to the candidate to decide on how the queue is handled and mechanics are assigned
and create the algorithm accordingly



![WhatsApp Image 2023-06-17 at 10 56 01 PM](https:/![WhatsApp Image 2023-06-17 at 10 57 11 PM](https://github.com/keerthanarao02/myproject/assets/102549038/8827420e-716d-42f8-b4df-dd573eb4c063)
/github.com/keerthanarao02/myproject/assets/102549038/fc35c60b-8937-49b8-b362-f5bbd29f93da)

