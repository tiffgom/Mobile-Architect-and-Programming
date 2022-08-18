# Mobile-Architect-and-Programming
### Briefly summarize the requirements and goals of the app you developed. 
#### What user needs was this app designed to address?
The application I developed is an Event Tracking App. The overarching purpose of the application is to create an easy-to-use app with an interactive UI where new or existing users may employ CRUD functionality to create, read, update, and delete events to and from an event SQLite database. To garner a customized user experience, login functionailty is provided through the use of a user SQLite database to store credentials for easy retrieval at login and in case of forgotton passwords. Users may also enable a feature to receive SMS notifications for upcoming events.
### What screens and features were necessary to support user needs and produce a user-centered UI for the app? 
*LOGIN - REGISTRATION - PASSWORD RETRIEVAL*

![Login](https://user-images.githubusercontent.com/88759442/185329824-fef776a0-4b7b-4fab-9e63-40b9be7ac785.jpg)
![Register](https://user-images.githubusercontent.com/88759442/185330011-43a9a482-9ada-4a33-b058-c984b1399d4c.jpg)
![password](https://user-images.githubusercontent.com/88759442/185330044-548e6a08-88a8-4278-ba39-dd8068552193.jpg)

*EVENT DASHBOARD - NEW EVENT - MODIFY EVENT*

![Dashboard](https://user-images.githubusercontent.com/88759442/185330219-e3227810-9616-4080-9cae-9b642adc2af7.jpg)
![ADD](https://user-images.githubusercontent.com/88759442/185330269-2e8b4d90-f352-4efd-bbcb-1767cf905603.jpg)
![modify](https://user-images.githubusercontent.com/88759442/185330675-a8048697-55cb-4354-8786-5ad0a96c9ae0.jpg)

*DELETE ALL ALERT - SMS NOTIFICATION ALERT - MENU*

![DeleteALL](https://user-images.githubusercontent.com/88759442/185330815-c173917b-4d82-4f53-81f0-c3f1d5431dfb.jpg)
![SMS](https://user-images.githubusercontent.com/88759442/185330843-3f6e19d3-2fa0-4d84-9429-2ccc6fcc9c6c.jpg)
![MENU](https://user-images.githubusercontent.com/88759442/185330885-615bc75c-e628-4fd2-a4d7-b0013b8a84dc.jpg)


#### How did your UI designs keep users in mind? 
Early on throughout the design process, extensive research was conducted to identify the types of users that would be attracted to a simple interface with likewise simple functionality. I kept my users in mind with the simply designed dashboard, the easy-to-navigate interface that allows them to employ basic functionality quickly (add, delete, update, and set reminders), and the fact it keeps user data confined to just the app. They will appreciate the  minimalistic interface that does not distract from the app’s core features.  
#### Why were your designs successful?
I designed mockups for each screen. This was crucial to my design since it pushes you to consider how the user will navigate the application. It also allowed me to visualize layouts and choose, for instance, to create a dialogue box instead of a screen based on the amount of required text input fields to retrieve a user's forgotten password. Additionally, I began to experiment with themes and logo/icon positioning. When I was satisfied with my design, I began to label my buttons and other components with the calls required to activate them. All the design decisions were deliberately chosen to ensure seamless interaction between the device, user, and application while keeping user satisfaction, functionality, and requirements at the forefront. As a result I designed a successful interface with elements such as a consistent theme, distinct labels, distinguishable iconography, and identifiable navigation buttons.
### How did you approach the process of coding your app? 
#### What techniques or strategies did you use? 
My labeled mockup acted as a blueprint that helped to guide be throughout the process of coding my app. Throughout the design of the mockup I had to determine the app's requirements which helped me identify the app's architecture- a MVC design. I heavily modularized the application through the use of multiple classes to separate activity screens and functionality. I used coding best practices, simplified code structure to keep it legible and clean, used logical naming conventions, and commenting to explain portions of code.
#### How could those be applied in the future?
The modularity and best coding practices I employed will allow me to incremently improve upon my app. Myself or another developer should have no problem accessing the code for whatever feature they wish do enhance or add additional feature. I do plan incorporating an event list search bar that will require my use of existing code.
### How did you test to ensure your code was functional?
A phone emulator was used for testing and real-time adjustments, particularly regarding the UI design and structure. Using this strategy, I was able to mimic the navigation on an Android phone in a manner similar to a user and make minor UI and code modifications in order to improve the user experience and the aesthetic appeal of the application. Furthermore, I tested the functionailty of each feature as if I were an existing or new user. 
#### Why is this process important and what did it reveal?
### Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?
In creating the app's user interface (UI), I had to make several modifications in order to create a design that would attract my chosen user demographic. My initial design improved as I better grasped the material to include additional CRUD functionality like a delete all function. Viewing the final product from the user's perspective inspired me to create an overflow menu option with logout and switch user options instead of a simple logout icon button. 
### In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
I was particulary successful in creating two SQLite databases to store user and event data and developing as well as the subsequent CRUD operations for each. Multiple users may create accounts with unique credentials that are stored and checked against the database at login as well as retrieve stored forgotten passwords. Existing, at each login, can view their current event lists, create new events, and modify or delete existing events. Their current list is always stored at log out and retrieved at log in.
