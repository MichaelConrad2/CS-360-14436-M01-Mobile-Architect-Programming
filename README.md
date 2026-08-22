# CS 360 Mobile Architecture and Programming

## Inventory Manager App

### Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The goal of my Inventory Manager app was to create a simple Android application that allows warehouse and stockroom users to manage inventory efficiently from a mobile device. The application was designed to reduce the need for paper records or delayed inventory updates by giving users a way to view and modify inventory information directly in the app. The final application includes user login and account creation, an inventory grid, the ability to add and remove inventory items, controls for changing quantities, and optional SMS notifications when an item's quantity reaches zero. The application stores its data locally so that its primary inventory features can continue working without an internet connection.

The main user need I wanted to address was speed and simplicity. Warehouse employees may need to update inventory repeatedly throughout the day, so completing common actions should not require unnecessary steps. Managers and supervisors also need accurate inventory information so they can identify shortages and determine when products need to be replenished. These needs influenced both the features I implemented and the way I organized the application's interface.

### What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

The application required screens and features that supported the main inventory workflow. This included authentication for logging in or creating an account, an inventory screen for viewing current items and quantities, controls for adding and removing items, quantity adjustment controls, and notification functionality. The design focused on keeping important actions visible and reducing the amount of effort required to complete routine inventory tasks.

I kept users in mind by emphasizing simple navigation, readable information, consistent design elements, and controls that clearly communicate their purpose. One-tap quantity controls are especially useful because changing inventory counts is an action users may perform frequently. I also designed the notification feature so that users choose whether they want to enable SMS alerts instead of requiring the permission automatically. I believe the design was successful because it focused on the tasks users need to perform most often instead of adding unnecessary complexity.

### How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

My approach to coding the application was to develop it incrementally instead of trying to complete every feature at the same time. I separated the application into smaller pieces, such as authentication, database operations, inventory display, quantity updates, and notifications. I would implement a feature, test its behavior, correct problems, and then continue to another part of the application.

Breaking development into smaller components made troubleshooting easier because I could focus on a specific area when something did not work as expected. I also tried to keep the user interface and application logic organized so changes in one area were easier to understand and maintain. I can apply this strategy to future projects by continuing to divide larger applications into manageable features and testing each feature throughout development rather than waiting until the entire application is complete.

### How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

I tested the application throughout development by running it and checking individual features as they were implemented. This included testing login and account creation, loading inventory data, adding and removing inventory records, adjusting quantities, and verifying notification behavior. I also considered situations where the user might deny SMS permission to make sure the rest of the application would continue working normally.

Testing throughout development is important because an application can compile successfully while still containing functional or usability problems. Testing individual workflows helped reveal issues earlier, when they were easier to isolate and correct. It also reinforced the importance of testing different user actions and conditions rather than only testing the expected path through the application. For future applications, I would continue this approach and expand testing across additional Android versions and physical devices whenever possible.

### Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

One challenge was connecting the original design ideas to a functional application while keeping the interface straightforward. During the planning stage, I identified several features that would support inventory management, but implementing those ideas required determining how the screens, database operations, and user actions would work together.

The notification feature was another area that required additional problem solving. SMS permission has to be handled carefully on Android, so I designed the application to request permission only when the user chooses to enable SMS notifications. If permission is denied, the inventory management features continue functioning instead of making the notification feature a requirement for using the application. Working through challenges like this taught me to adapt my original design when technical requirements affect the implementation.

### In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

I was particularly successful with the inventory management workflow because it brings together several of the skills developed throughout the course. The user can authenticate, view stored inventory, add or remove items, and adjust quantities while the application maintains the data locally. The optional SMS alert functionality adds another layer by responding when inventory reaches zero.

I think this portion of the application demonstrates my ability to connect user interface design, persistent data, application logic, Android permissions, and user-centered design into one functional mobile application. More importantly, the completed application reflects how my development approach changed throughout CS 360. I now think beyond whether an application simply works and consider why it is being developed, who will use it, how easily users can complete their tasks, and how the application can be tested and improved.
