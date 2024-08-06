![](https://github.com/joewadk/BTT-FinalProject/gif/btt.gif)

# BTT Final Project
Hello! As part of the final lab assignment for Break Through Tech AI's Machine Learning Course, I analyzed a given dataset, the AirBnB Listings data set, in order to best approximate the best listing for a user based on the location, price, and number of total rooms the user asks for. This was done over Jupyter Notebook, so be sure to run each cell chronologically.
# Technologies I Used
This project utilized a mix of unsupervised and supervised learning to get the best listings for the user. I had filtered formatted my listings based on relevant features, then summed up all rooms as a total rooms feature. I would then use unsupervised supervised, in particular K means clusters, in order to filter listings based on location, room number, and pricing. I would then use One Hot Encoding as well as Random Forest Regression to then rank my listings based on the review score ratings and the review score value (user Sentiment). 
# Future Considerations
I do plan on working on this idea later on, and so I plan to add a user input box where they can add any other features they look for in their listing. I would then implement OpenAI to take all of this data and format it into a tuple that will become a target for my model to cluster to. I would later call OpenAi to format my output listings into a more human-readable format.
