# StockSentry
StockSentry is a simple iOS/android app that helps you manage stocks and evaluate risk depending on both personal tolerance and the global risk factor.
Done as part of TAMUHack 2023, devpost: https://devpost.com/software/stocksentry.

# Inspiration
Interested in quantitative finance, our team was inspired to create this financial risk analysis app because we saw a need for a user-friendly and efficient tool for both individuals and businesses. Not only does StockSentry assess the investments of the user according to their own risk tolerance, but also with a range of other factors like inflation, unemployment, interest rate, and productivity, as well as through sentiment analysis of the present-day media.

# What it does
It allows anyone to trade and manage stocks while also being aware of the risks that come with it. After first learning about its user and their portfolio, StockSentry is able to use the state of the economy today to approximate the risk factor associated with the current investment. From there it compares the risk factor of the economy and the current portfolio of the user and assesses it against their desired risk tolerance. Depending on how the user's risk tolerance compares to the currently predicted risk, recommendations are made.

# How we built it
We built StockSentry with React Native for the front end and python for the backend which performs the risk analysis itself. It uses a statistical model to calculate the potential losses on the investment, along with a model which evaluates the state of the current economy using sentiment analysis with a natural language processing model and quantitative data, to predict the risk at the current state of affairs.

# Challenges we ran into
It was the team's first time using React Native, and 2 members' first time writing for front-end, but it was an enjoyable learning experience! Furthermore, we did not have extensive statistics or finance knowledge prior to starting the project, but grappling with the concepts and implementing them over the last 24 hours was a pleasant experience.

# Accomplishments that we're proud of
We're very proud to have a product that can actually help the user decide what are (somewhat) intelligent financial decisions, and can analyze their portfolio and goals through a variety of different lenses. It can approximate the risk of the user's investment and can potentially prevent them from making trades that they cannot handle, which they might have picked due to their inexperience.

# What we learned
We learned more about various technology stacks and techniques from sentiment analysis and natural language processing to front-end design and risk management knowledge. We enjoyed working as a team and are excited about what is to come!

# What's next for StockSentry
Our risk assessment model and financial suggestions could definitely be improved especially as we get a deeper understanding of risk management. We would also like to clean up the UI, fine-tune the risk-evaluation algorithm, and publish the app to both iOS and Android!
