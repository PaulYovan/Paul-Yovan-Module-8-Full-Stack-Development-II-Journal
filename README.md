# Paul-Yovan-Module-8-Full-Stack-Development-II-Journal

# Youtube Video Link
https://youtu.be/Ao3JuLKSRSk

# What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?
Some of the skills I've learned are how to move one database to another type of database, as well as move a static website over to a cloud-based environment using Amazon Web Services. Some of the skills I've developed with this course are my experience with MongoDB and now my newfound knowledge of how to use DynamoDB as well as S3 buckets. These skills make me a more marketable candidate as I now know how the cloud works for programming, which is essential at this time due to most things moving over to the cloud.

# How would you handle scale and error handling?
Regarding scale, it would depend on what I'm using. If it were a serverless program, then I shouldn't have to handle scale due to it being automated already; however, in a case where I do need to manage scale, then I would go off of the popularity of the program and how often it is used, and try to allocate resources to handle the demand. For error handling, I would make sure the HTTP Requests are working properly during testing and make sure that I have a couple of error exception handlers for timeout requests to prevent unnecessary resource costs. I would also set a function that prevents duplications of case-sensitive entities, such as usernames or possibly even SSNs.

# How would you predict the cost?
The way I would predict cost is first by figuring out how often the product is being used and which HTTP Requests are being used most often, then I would look at the average costs for these functions and then apply that formula to the current product to try and predict the overall costs, whether it be per day or per week.

# What is more cost predictable, containers or serverless?
In my opinion, containers are more cost predictable due to being a constant cost; however, serverless is more cost efficient as it only charges based on what is being used, rather than containers, which even when idle have costs.

# What roles do elasticity and pay-for-service play in decision making for planned future growth?
Pay-for-service is most likely the biggest factor when it comes to decision-making for future growth, as money would be what is most important for a company and obviously a company wouldn't want to waste money on resources that are not being used, which is where pay-for-service would come in, as you only pay for what is being used. Elasticity in this case would just be a bonus, as automatic scaling is obviously nice for a developer due to them being able to only focus on coding, but it doesn't mean that developers need elasticity to make a website properly.
