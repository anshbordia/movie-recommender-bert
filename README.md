# movie-recommender-bert
Movie Recommendation Engine using BERT

Download and install the requirements using the command: pip install -r requirements.txt

Please refer to the Medium Article for a detailed description: https://medium.com/@ansh979/building-a-movie-recommendation-engine-in-python-53fb47547ace?sk=6657738924c8de4315e4b7d0c23f5f70


If you wish to run the recommender on Docker, do the following:
1) Setup Docker on your machine if you haven't already. Use this to get started: https://www.docker.com/get-started
2) Run the commands -> a) docker pull ansh979/recommender b) docker run -it ansh979/recommender

You can also host the model locally using FastApi:
1) Simply run server.ipynb
2) You can run the client in 2 ways: Run the client.ipynb or use FastApi's built-in client at http://localhost:8000/docs
3) To run client.ipynb simply make the 'useMyClient = True' in server.ipynb. You will still be able to use FastApi's built-in client but you will need to pass a json object instead of a string. 

