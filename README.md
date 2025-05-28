# SP_Trigger_Challenge_Team_AmaniMathlaRahma

### What is Stored Procedures?
 - A stored procedure is a precompiled collection of one or more SQL statements stored in the database. It can be executed multiple times with different parameters, allowing for efficient reuse of logic, reduced duplication, and better performance.
 - Stored procedures support input parameters, allow encapsulation of logic, and can perform a wide range of operations like data manipulation, validation, transactions, and reporting.

  ![Stored Procedures](./image/StoredProcedures.png)

   ### Benefits of Stored Procedures

 -  **Performance Optimization** 		
	- Stored procedures are compiled once and stored as executable plans.
On subsequent calls, the database reuses the compiled plan, speeding up execution.
 -  **Reduced Network Traffic**
	- Since stored procedures encapsulate multiple SQL statements, only the procedure call is sent over the network, not each individual SQL statement.
 -  **Improved Security**
		- Users can be granted permission to execute a stored procedure without having direct access to underlying tables.
Using EXECUTE AS can impersonate specific users and protect sensitive data.
 - **Code Reusability & Maintainability**
	- Avoids repeating code for repetitive tasks.
	- If changes are needed, only the stored procedure needs to be updated—not every application or client that uses it.
 - **Error Handling**
	- SQL Server supports error handling with TRY...CATCH blocks inside procedures.
 - **Modularity & Abstraction**
	- Procedures let you abstract complex SQL logic away from client applications.
	- Parameters can be used for dynamic input.