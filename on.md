- See the section on 'Enabling remote debugging scenarios' on some advice on how to safely allow remote debugger clients to connect.

- This includes branching on secrets and, when the attacker could be co-located on the same infrastructure (e.g., same cloud machine), using a secret as an index into memory. 

- However, it is good practice to be as specific as possible with the types of exceptions that we intend to handle, and to allow any unexpected exceptions to propagate on.