1. This App is a multifunction Application
2. This App is targeted to includes all the fundamental concept of Android (Activity, Service, Content Provider, Intent, Broadcast Receiver, AIDL Service)
3. Activity serves as UI
4. Intent used to route between pages
5. Content Provider used to facilitate communication with database
6. Broadcast Receiver is used to handle broadcast notification
7. AIDL service is being used to handle communication between client App and server app
8. This Application has a Data Entry and a Calculator Function
9. In the Data Entry App, users can enter the data of Employees
10. In the Calculator App, users can perform basic operation (+, -, *, /) with the decimal numbers
11. All the operation performed by the user are stored in the database, and these past operation can be fetched by the History button
12. A background Service is also being implemented for the caculator App, which checks the usage time of the App
13. If usage time exceeds 1 minute it sends a broadcast to the client that One Minute is Over!
14. If usage time exceeds 2 minutues it opends an alert window (Time is Over!)