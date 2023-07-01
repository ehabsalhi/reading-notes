# Access Control (ACL)

> # What is Role Based Access Control (RBAC) and why do we care?
> 
> Role-based access control (RBAC) is a security methodology based on managing user access to protect resources, including data, applications, and systems, from improper access, modification, addition, or deletion.
>
> ## Describe a Role/Permission heirarchy that you might implement using RBAC.
> 
> 1- Superadmin : Full access to all system functions and data.
> 
> 2- Admin : Administrative access to specific system functions and data.
>  
> 3- Manager : Access to specific functions and data relevant to their department or team.
>
> 4- Team Lead: Access to specific functions and data relevant to their team.
>
> 5- Employee: Access to essential functions and data required to perform their job.
>
> 6- Guest: Limited access to specific functions or data for temporary or external users.
>
> ## What approach might you take to implement RBAC?
> 
> RBAC implementation can vary depending on the technology stack and the specific requirements of the organization.
>
> # Three primary rules are defined for RBAC:
>
> 1- Role assignment: A subject can exercise a permission only if the subject has selected or been assigned a role.
>
> 2- Role authorization: A subject's active role must be authorized for the subject. With rule 1 above, this rule ensures that users can take on only roles for which they are authorized.
>
> 3- Permission authorization: A subject can exercise a permission only if the permission is authorized for the subject's active role. With rules 1 and 2, this rule ensures that users can exercise only permissions for which they are authorized.
>
> ## Describe RBAC to a non-technical friend? 
>
> Role-Based Access Control, is a way to control and manage who has access to what in a system or organization. It's like having different levels of permissions or rights for different people based on their roles or job functions , and it helps to ensure that people can only access what they need to do their work and nothing more.
>
> # If Authentication is “you are who you say you are,” what is Authorization?
>
> Authorization is the process of determining what a user is allowed to do or access within a system or organization after they have been authenticated.
>
> # What Are access rights Associated with? The User? or The Role? Explain.
>
>  In RBAC, permissions and access rights are assigned to roles based on the responsibilities and job functions associated with those roles ,also enabling simplified administration, scalability, consistency, flexibility, and the enforcement of separation of duties principles.
>
> ## Access Rights, or Authorization, is activated after a user successfully does what?
>
>  after a user successfully authenticates themselves
>
> ## Explain how RBAC might benefit a business
>
> 1- enhance security by ensuring that users only have access to the resources and data necessary for their roles and responsibilities.
>
> 2- By implementing RBAC, organizations can enforce access controls, track user activities, and generate audit reports
>
> 3- RBAC allows for assigning roles to users based on their job functions.
>
> # What are your learning goals after reading and reviewing [the class README?](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-08/)
>
> learning more about ACL and how can i use it inside the web app

