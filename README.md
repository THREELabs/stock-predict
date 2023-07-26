# Web Application For Stock Price Prediction

## Table Of Content

+ [Demo](#demo)
+ [Overview](#overview)
+ [Motivation](#motivation)
+ [Technical Aspects](#technincal)
+ [Installation](#installation)
+ [Execution](#running)
+ [Deployment on Streamlit Cloud](#deploy)
+ [Technologies Used](#tech)
+ [Team](#team)
+ [LICENSE](LICENSE)
+ [Disclaimer](#disclaimer)


<a id="demo"></a><h2>Demo</h2>

### Interface
![Home](https://github.com/Sandy0002/Final-Year-Project/assets/110614803/12a437e5-15a9-436e-af87-e167c317369c)

**Stock exchange options**
![Stock Indexes](https://github.com/Sandy0002/Final-Year-Project/assets/110614803/9956cccc-afc4-4f2a-b504-da7a962dd26b)


**Forecast interval Options**
![Forecast Intervals](https://github.com/Sandy0002/Final-Year-Project/assets/110614803/8192c0ba-dd43-4d21-8ac0-a236163ca98e)

**While processing**
![Processing](https://github.com/Sandy0002/Final-Year-Project/assets/110614803/272edc78-5d17-4ac3-b377-b478c115d075)

**Post Processing**
![Output](https://github.com/Sandy0002/Final-Year-Project/assets/110614803/85e8f4a8-2655-4d52-b44d-7855ba79fb6a)



App [link](https://sandy0002-final-year-project-code-wxm7fn.streamlit.app/)


<a id="overview"></a><h2>Overview</h2>
This is a web application built using the concept of **Stock Price Prediction**. The web app is built using Streamlit framework along with the TensorFlow for deep learning purposes and have been deployed on the streamlit cloud

<a id="motivation"></a><h2>Motivation</h2>
Its been a while since I was building machine learning models and want to expand my knowledge by applying the concepts on the bigger problem. Such a manner would be applying the **stock price prediction concept upon stock exchanges** in which rather than simply have one dataset simply here we need to process data in real time and generate results.

<a id="technincal"></a><h2>Technical Aspects</h2>

Whole project is written using only python.

### Project Working
The working of the project is divided into 4 steps

+ **Fetching Data**
  + Program takes the user inputs such as the stock exchange, company name and forecast interval. **yFinance** library is used to fetch the data of the stock. By default we are taking only 5 years of data of  a stock for prediction
  
+ **Preprocessing Data**
  + Upon fetching data we need to preprocess it.We are using LSTM as they are suitable for time-series-analysis. So we need to convert the data into LSTM compatible format.

+ **Training Model**
  + After preprocessing the data is sent to the model for training it.

+ **Generating forecasts and displaying**
  + After training the past data is used to forecast the future values.
  

<a id="installation"></a><h2>Installation</h2>
The Code is written in Python 3.10. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:

``` pip install -r requirements.txt```


<a id="running"></a><h2>Execution</h2>

```streamlit run appName.py```

<a id="deploy"></a><h2>Deployment on Streamlit Cloud</h2>

+ Create an account on streamlit
+ Connect your github account with the streamlit account.
+ Create an app by selecting the respective settings such as repository, path of the code etc.

**Note**: For guidance check [here](#https://www.youtube.com/watch?time_continue=1&v=kXvmqg8hc70&embeds_referring_euri=https%3A%2F%2Fwww.bing.com%2F&embeds_referring_origin=https%3A%2F%2Fwww.bing.com&source_ve_path=Mjg2NjY&feature=emb_logo)


<a id="tech"></a><h2>Technologies Used</h2>

| Libraries        | Usage       
| ------------- |:-------------:|
**Numpy**  | Used for numerical computations in python
 **Pandas** | Used for file reading and other operations when working with large data.
 **Sklearn** | This is a machine learning library for python.
 **Plotly** | Interactive data visualization library
 **TensorFlow** | Deep Learning library from which model has been built
 **Streamlit** | Framework for providing interface of the web app
 **Datetime** | For datetime operations
 **yFinance** | For fetching stock data

<a id="team"></a><h2>Team</h2>
**P. Sandeep Murthy**


<a id="license"></a><h2>LICENSE</h2>
[MIT LICENSE](LICENSE)

## Disclaimer
This program is just for educational purpose and not for financial use purposes.
