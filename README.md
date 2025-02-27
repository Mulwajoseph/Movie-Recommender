# MOVIE-RECOMMENDER SYSTEM  

<!-- ![Movies Wallpaper](Photos/images.jpg) -->
<div align="center">
  <img src="Photos\camera-shots.jpg" alt="Wallpaper" width="800"/>
</div>

## Objective  

Our objective is to build a production-quality movie recommendation pipeline which provides a personalizied  5 top list of movies specific to each users. The goal of this new pipeline is to increase user retention for the platform and provide a better experience.

## Data Source   

We will be using a[dataset](https://grouplens.org/datasets/movielens/latest/) from the GroupLens research lab at the University of Minnesota 

The dataset is compressed into `ml-latest.tar.gz`. 
To extract the data set, run:
<pre><code>
tar -xvzf ml-latest.tar.gz</code></pre>

## Installations  

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/your-repo.git
 
2.Navigate to the project Directory  
  <pre><code>cd your-repo</code></pre>
  

3.Install the required dependencies  
   <pre><code>pip install -r requirements.txt</code></pre>
   
## Usage  

1.Preprocess the data  
   <pre><code>python src/data_processing.py</code></pre>
   

2.Train the reccommendation Model  
   <pre><code>python src/model_training.py</code></pre>


3.Generate Movie Recommendation for user   
   <pre><code>python src/recommender.py --user_id <USER_ID></code></pre>
   
## Dependencies 

Install the python packages enlisted in the requirements.txt  
   To install them run:
      <pre><code>pip install -r requirements.txt</code></pre>
      


## Contributing  

If you`d like to contribute please follow the following steps:  
   1. Fork the repository    
   2. Create a new branch  
   3. Commit your changes  
   4. Submit a pull request  


## Contacts   

For questions or feedback.kindly reach out:  

   - <b>Email:</b>mulwajose.jm@gmail.com  
   - <b>Github:</b><a href="/https://github.com/Mulwajoseph">Github</a>  