# Instructions

You will need to find a partner and complete the following tasks together:

1. Answer the questions:
    - Nesting: How did you organize the additional details in the traveler field, and how does it improve the organization of the data overall?
    - Arrays: For the destinations and activities, what data structure did you use? What impact did this decision have?
    - Scalability: How could this JSON structure be expanded to include additional details, such as hotel information or transportation options?
    - Real-World Application: How would this data be useful in a travel app or API?
2. Add to your partner’s JSON object:
    - Create a pull request to add to your partner’s JSON object.
    - Add a new destination with activities.
    - Add a transportation field to each destination, containing nested objects for mode (string, e.g., "Flight") and cost (number, e.g., 150.00).
    - Discuss how their additions enhance the data model.
    - Note: Make sure your partner does not merge your code!

## Answers

- Nesting: How did you organize the additional details in the traveler field, and how does it improve the organization of the data overall?
    - **I chose to make the transportation detail an object that contains a mode and a cost. This improves the organization by detailing what kind of transportation will be used as well as how much the traveler will need to spend.**
- Arrays: For the destinations and activities, what data structure did you use? What impact did this decision have?
    - **For the destinations, I used a complex object. 3 strings for location, arrivalDate, and departureDate; 1 object for the transportation's information; and an array of objects listing the activities for each destination.**
    - **Each activity in the activities array contains a title and a time. Both are strings.**
    - **The impact is that each destination object is very orderly and its information is easily accessable.**
- Scalability: How could this JSON structure be expanded to include additional details, such as hotel information or transportation options?
    - **Adding a new object like we did with the transportation object. Hotel information would be a list of key-value pairs and transportation options would be a list of transportation objects.**
- Real-World Application: How would this data be useful in a travel app or API?
    - **It would be useful to look up information about the trip. Whether that be one thing at a time, or to organize all the information in a dashboard/visual design the traveler can easily read.**

- Discuss how the addition of the transportation field enhances the data model:
    - **It adds better planning to the model. A non-insignifiant piece of traveling is the traveling part. It makes sense to include the how-to-get there instead of just the what-to-do there.**
