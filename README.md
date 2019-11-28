# Hack-the-North-2018
Intelligent web application that utilizes machine learning to identify products through images and outputs the price per share of the company's stock. Completed in 33 hours for Hack the North 2018 Hackathon at the University of Waterloo.

# Inspiration
One of our favorite books is One Up on Wall Street by famed investor Peter Lynch. In his book, Lynch reveals an inspirational and intimate story from his past. The story goes as follows. One day many decades ago, Lynch noticed that his wife spoke highly of a certain brand of pants. Failing to see the potential behind an unknown clothing company, Lynch did not even consider it as an investment opportunity. Five years later, his wife and all of her friends wear the same pants. They are on sale in stores across America. At this point, the stock had increased by many thousand percentage points. The moral of this story is that our first-hand experiences with products and services can be just as, if not more, valuable than traditional tools such as technical analysis. We were inspired by this story to create a tool that allows individuals to quickly discover investment opportunities as they appear.

# What it does
The web application takes an image as an input, and uses the Clarifai API to identify key objects within the image, and then determines the companies responsible for said objects. Next, the application retrieves real-time data about the stock via the Alpha Vantage API, and computes the historical and real-time datapoints to predict future movement in the stock price. This information is clearly conveyed to the user - all in under a second.

# How we built it
The front-end of the web application was built using HTML, CSS, and JavaScript, while much of the machine learning and prediction was done with Python. APIs such as Clarifai and Alpha Vantage enabled us to quickly perform tasks such as image recognition and data retrieval.

# Challenges we ran into
As this was our first time working on a project of this magnitude, we found two things in particular to be quite challenging. First, it was at times difficult to delegate different tasks for each group member, as we did not do much planning beforehand. Secondly, keeping the code clean and organized became increasingly more challenging as the code increased in length.

# Accomplishments that we're proud of
This is by far our largest coding project. We are immensely proud that we were able to quickly learn and integrate so many new technologies, such as machine learning and API usage, into a functional project.

# What we learned
One of the most valuable lessons we learned from this hackathon was the importance of preparation. As we found out, a lack of planning at the early stages of the project ended up stymieing our ability to work efficiently later on. Lke making a meal, the preparation is just as important as the cooking itself.

# What's next for InVisualize.io
We plan on expanding InVisualize.io into a mobile app to allow individuals to discover inspirational investment ideas on the go. Furthermore, we plan on implementing a search engine to give users a wider array of information and functionality.
