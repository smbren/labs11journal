Week 1 Journal

Sprint Challenge - Labs I - Startup

Part 1 - Individual Accomplishments this Sprint
Provide a paragraph (5-8 sentences) summarizing the work you did over the course of this sprint, including the challenges you faced, the tools you used, and your accomplishments

This week I worked mostly on getting the basic backend set up. I started the week pair programming with Kevin; we worked on deploying the production servers. We ran into issues connecting to our database server, so we decided to move forward and test locally with sqlite3 until we could sort that out. Once the basic servers were set up, we split up so Kevin could work on connecting the servers and I worked on setting up the database schema. I wrote migrations in knex for the full schema, then started writing some basic endpoints so we could access the data.

--------------------------------

Detailed Analysis
Pick one of your tickets and provide a detailed analysis of the work you did. This should be approximately ¼ page of text, and include screenshots if appropriate

https://trello.com/c/4GR3P84D/14-create-tables-in-mysql

Setting up the database schema:
Before I started writing any code, I talked over the schema with the rest of the team to verify that it was correct and that I understood the user account models and what data we would actually need to store. I took some time to go back over my old back end projects and read about database design and using knex. I wrote the migrations and tested them locally in sqlite3. Once I was finished writing the migrations, I submitted a pull request and met back up with Kevin so we could test the migrations on the production database server. We ran into an issue caused by the order that the migrations were creating the database tables. I realized that some tables were being created before other tables that they depended on had been created. I was able to fix this by correcting the order that the migrations create the tables.


--------------------------------

Part 2 - Milestone Reflections
Write ¼ to ½ a page reflecting on your individual contributions to analyzing the project specification and writing the TDD. Describe the research you personally conducted to find out information on a competitor, investigate a technical solution to a specific problem, or define your customers.

I researched a competitor called classmax app. I analyzed their frontend layout and what data they were tracking for each student and how they displayed that data. I researched features that were similar to our features to see how they were implemented. I researched their payment options, target customers, and pricing.

Using the mockup and required features provided, I helped determine the flow of the site. I helped define what views would be required for each account type, what access they would have to data, and how they would navigate to different views. I helped determine the API endpoints we would need to access the required user data. I designed the database schema and the user account models. I researched which database we should use and suggested MYSQL for the production database. I determined what back end framework and middleware we would need to use.