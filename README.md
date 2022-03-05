# revisionHelper

It is an Application developed using ***HTML, CSS, javaScript, Node.js, Express.js, MongoDb and Python*** which is going to help in revising concepts. Whenever You are reading something online and you want to revise that after some time you can add the url, article name and data (when you want to revise) in the extension and it will send mail consisting topic name as subject and url attach.

#### Basically this Application has two parts: ####

1. After filling the form the data will submit in mongodb database.
2. There is a Python Script which will check the database in every 24 hours and when the date is matched it will send mail and also delete that data from database.

![revisionHelper form view](https://user-images.githubusercontent.com/89836012/156872296-96817ba7-ab70-4f56-9252-43ed69a0019b.jpeg)
