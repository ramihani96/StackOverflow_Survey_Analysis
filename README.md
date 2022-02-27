StackOverflow Survey Analysis
==============================

<h2> 1.Problem Statement </h2>
  <div>
    <ul>
      <li>
      The field of IT jobs and technologies keeps evolving quickly, such fast development confuses students and they do not know which skills they need to learn for which job.
      </li>
      <li>
      Some of these confusions can lead to questions like:
        <li>Do I need to learn C++ to be a data scientist ?</li>
        <li>Do DevOps and System Admins use the same technologies ?</li>
      </li>
      <li>
      The aim of this project is to <strong>develop a data-driven solution for students to answer such questions.</strong>
      </li>
      <li>
      We want to understand the relationships between the jobs and the technologies.
      </li>
    </ul>
  </div>

  <h2> 2.Business Case </h2>
    <div>
      <ul>
        <li>Our client is an IT Educational Institute.</li>
        <li>This project will help the institute to provide obvious career path solutions for their students.</li>
        <li>This project will help the graduates of the track to meet market requirements and this will lead to higher number of students coming to the institute and as an impact higher revenue for the institute.</li>
        <li>The main Key Performance Indicators <strong>(KPI's)</strong> of this projects are:<br>
            1. Higher Enrollment Rate. <br>
            2. Decrease in Drop-out Rate.<br>
            3. Saving time for Academic Advisors.<br>
        </li>
      </ul>
    </div>

  <h2> 3.Data Used for Analysis </h2>
  <div>
    <ul>
      <li>The Educational Institute doesn't have any internal data sources so we are going to use an external data source.</li>
      <li>We will be using <strong>StackOverflow Survey 2020</strong> in this project. (<a href="https://insights.stackoverflow.com/survey/2020"> StackOverflow Survey 2020 </a>)</li>
      <li>To download the dataset, click <a href="https://info.stackoverflowsolutions.com/rs/719-EMH-566/images/stack-overflow-developer-survey-2020.zip"Here</a>.
    </ul>
  </div>

<h2> 4.Project Organization</h2>
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
