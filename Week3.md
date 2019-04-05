Part 1 - Individual Accomplishments this Sprint

Provide a paragraph (5-8 sentences) summarizing the work you did over the course of this sprint, including the challenges you faced, the tools you used, and your accomplishments

This week we focused mainly on the front end of the site and getting the user flow right. Early on in the week I realized that the way we chose to structure our database was going to cause problems with how we wanted to implement some features. As soon as I realized this, I brought it to the team and we decided that we should hold off on fixing it because it might break a lot of functionality on the front end and that we should focus on the front end of the site this week instead of fixing back end bugs. I moved forward with working on the front end components I built last week and making sure that they are mobile responsive. I also changed them to be pop up modals for a better user experience. During our UI meeting, our UI contact suggested that we add a feature for the user to be able to upload photos. I research possible solutions and worked on implementing one of them.


Detailed Analysis

Pick one of your tickets and provide a detailed analysis of the work you did. This should be approximately ¼ page of text, and include screenshots if appropriate

https://github.com/labs11-studentdata/labs11-studentData-BE/blob/master/config/imageUploads/uploadRoutes.js

This PR shows the backend part of implementing an image upload feature. I had never encountered this problem before, and it was more challenging than I first expected. While researching possible solutions, I found several options to choose from. I narrowed these options down to either storing images as binary data in our database or storing them in a public uploads folder on the server filesystem. After further research and weighing these options, I chose the latter option for our use case because it seems to be the common solution that is used for most real world projects. I found a backend middleware that works with formdata that we would be sending and spent some time learning how to work with it. Eventually I was able to successfully upload image files to our server filesystem. 



Part 2 - Weekly Reflection

As a part of your journal entry, write ¼ to ½ a page reflecting on your experiences working with a team to convert a disparate set of components into a single, cohesive, and complete product. Describe the challenges you faced and the steps you took to overcome them.

This week we spent most of our time trying to determine how to fit everyone's components into a final product that creates a logical user flow. This was really challenging because it seems like we were not all on the same page with what the final product should be. It turned out to be more like everyone had been working on individual projects instead of on the same code base and trying to fit all those separate individual projects into one product. There were also some instances where we had overlapping efforts and some team members working on features that were not part of the inital plan/spec so figuring out where to fit those new pieces in was very challenging. We made efforts to get everyone on the same page and created a standardized template for some front end features, but there is still a lot of work to do to fit everything together.

https://github.com/labs11-studentdata/labs11-studentData-BE/commit/2191c3c96b8d648bfe6161ecb352722a014dd1ad
https://github.com/labs11-studentdata/labs11-studentData-BE/commit/46e5abebcda730318f74b87dc9b58c7981c3cf42

https://github.com/labs11-studentdata/labs11-studentData-FE/commit/1e7bb87ab4c703934d3707cb7a736a3a989e7d94
https://github.com/labs11-studentdata/labs11-studentData-FE/commit/25baab322d651f3558360cfb84f5e314c841fb2a
https://github.com/labs11-studentdata/labs11-studentData-FE/commit/ddbe617c84c8e8e14e2d72a4c64be61dc4ab3a94
https://github.com/labs11-studentdata/labs11-studentData-FE/commit/5f2c90d0cff0b200789ebdcbf972816642960054
https://github.com/labs11-studentdata/labs11-studentData-FE/commit/e8fae8c68a25c24454f4a8a063235f9489a2d156
https://github.com/labs11-studentdata/labs11-studentData-FE/commit/7bbca609a74e1f1dcc50387f88ad47162ed77e25
https://github.com/labs11-studentdata/labs11-studentData-FE/commit/1979ed668959b0d7a7e3779667ae8f26dce0aced
https://github.com/labs11-studentdata/labs11-studentData-FE/commit/24793f0593857f518b13ebe987f2eedaf4fda661
https://github.com/labs11-studentdata/labs11-studentData-FE/commit/14229525d6a57277526e99bed08a229207fe4499
https://github.com/labs11-studentdata/labs11-studentData-FE/commit/56b3523be3dbf8fdb1f8c913979b38814416c282
https://github.com/labs11-studentdata/labs11-studentData-FE/commit/cf5e0bfe25094dafacc8188c683bbc36f7cc9f95