# myproject
 backend developer for a company that solves vehicle problems on the go, anywhere and anytime. A team of 5 agents work towards receiving the request, talking to the customer facing the problem and assigning them an available mechanic.
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
9. There are 10 mechanics available
10. It is left to the candidate to decide on how the queue is handled and mechanics are assigned
and create the algorithm accordingly



![WhatsApp Image 2023-06-17 at 11 45 36 AM](https://github.com/keerthanarao02/myproject/assets/102549038/003d400b-8263-4971-a5e6-818f8476f318)


![WhatsApp Image 2023-06-17 at 11 46 36 AM](https://github.com/keerthanarao02/myproject/assets/102549038/fedcc26d-a533-4a7d-85c1-be0569c34fc5)


