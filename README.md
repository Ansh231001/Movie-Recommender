<h1># Movie-Recommender</h1>
<h2>A Movie Recommendation Engine</h2>

<ul>
    <li>
        Languages & Frameworks Used (Front-End):
        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>Javascript</li>
            <li>Jinja Templates</li>
            <li>Bootstrap</li>
        </ul>
    </li>
    <li>
        Languages & Framework Used (Back-End):
        <ul>
            <li>Python</li>
            <li>Flask</li>
            <li>Jupyter Notebook</li>
        </ul>
    </li>
    <li>
        Dataset Used
        <ul>
            <li>
                <a href="https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata">Link</a>
            </li>
        </ul>
    </li>
</ul>

<h2>About</h2>
<p>
    Movie Recommendation Engine made for PS: 3 intrigued my interest in learning about Machine Learning and Data
    Management. So, I came up with my version of a search and recommendation engine implemented on many multiplatform
    streaming services such as Netflix,Amazon Prime and Spotify. Based on the K nearest neighbours algorithm, it finds
    similarities
    using the cosine values of the movie vectors created with the help of the tags. Cosine similarity
    is better over a larger dataset than Euclidean Distance or Manhattan Distance. With the use of stemming, duplicated
    words were removed. The final dataset is provided in this drive link.
    <a href="https://drive.google.com/drive/folders/17PRpnE3fm0T-IPKFFhkcdKPQiwELrWmw?usp=sharing">LINK</a>
</p>

<h3>
    File Structure
</h3>

    |-app
        |-app
            |-__pychache__
            |-Engine
                    |-engine.py
                    |-filters.py
                    |-interest.py
                    |-popularity_engine.py
            |-static
                    |-css
                        |-main.css
                    |-scripts
                        |-script.js
            |-templates
                    |-main_template.html
                    |-index.html
            |-__init__.py
            |-pseudoDB.py
            |-views.py
        |-env
        |-Interests.pkl
        |-interestSimilarity.pkl
        |-movie_dict.pkl
        |-similarity.pkl
        |-run.py
 <h3>
  Installation
 </h3>
 pip install flask

<br>
<h3>
Run with Bash
</h3>
$ source env/Scripts/activate
<br>
$ export FLASK_APP=run.py
<br>
$ export FLASK_ENV=development
<br>
$ flask run
<br>



