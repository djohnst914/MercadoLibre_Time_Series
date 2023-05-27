# Time Series: MercadoLibre 
For this challenge, I'm a growth analyst with MercadoLibre. With over 200 million users, MercadoLibre is the most popular e-commerce site in Latin America. I've been tasked with analyzing the company's financial and user data in clever ways to make the company grow. So, in the main application above, I have taken the necessary steps to find out if the ability to predict search traffic can translate into the ability to successfully trade the stock. The steps go as follows:

Step 1: Find unusual patterns in hourly Google search traffic

Step 2: Mine the search traffic data for seasonality

Step 3: Relate the search traffic to stock price patterns

Step 4: Create a time series model with Prophet

Step 5: Forecast revenue by using time series models

---

## *Technologies*

- **Programming Language:** Python
- **Libraries:** Pandas, hvPlot, pystan, prophet, holoviews, datetime, numpy, matplotlib, warnings
- **Framework:** JupyterLab
- **Operating Systems:** Mac OS, Microsoft Windows

---

## *Installation Guide*

**1. First things first:**
If you don't have Python, Jupyter Lab, or Anaconda installed on your operating system ..

-**[Install Python](https://www.python.org/downloads/)**

-**[Install JupyterLab](https://jupyter.org/install)**

-**[Install Anaconda](https://docs.anaconda.com/free/anaconda/install/index.html)**

**2.** Next, clone this repo to your computer if you haven't already done so, preferably somewhere with easy access like your desktop. Once cloned, proceed to step 3.


**3.** The Prophet library can be difficult to install on some machines, so for this application we use Google Colab - an IDE that allows you to run Jupyter Notebooks in the cloud. Once you have cloned this repo locally to your machine, follow these steps:

- Go to your preferred search engine (Chrome works best), in the URL type and enter https://colab.research.google.com/. 
- Once the page loads in the top left select 'File', then select 'Open Notebook'.
- You will be prompted to this little page. Select 'Upload', then 'Choose File'. 
![Screenshot 2023-05-27 at 12 44 19 PM](https://github.com/djohnst914/github_upload/assets/123714457/6ee34d98-784d-4aed-ab50-a4074f895072)
- Once prompted, navigate to where you cloned this repo on your machine, and select/open 'forecasting_net_prophet.ipynb'
![Screenshot 2023-05-27 at 12 44 37 PM](https://github.com/djohnst914/github_upload/assets/123714457/b94d64f0-b0b6-4602-9d1c-d8e8e1751cae)

### **IMPORTANT:** 
- Ensure conda 'dev' environment is activated in terminal before running the application if using Jupyter Lab:

                        Conda activate dev
- Make sure to run this application in Google Colab as it is intended. You may run this application in Jupyter Notebooks, but BEWARE: if you have a Mac with an M1 processing chip your machine will not be compatible with running Google Colab in the Jupyter Lab IDE. 

---

## *Usage*

- Once Google Colab is open, the setup is almost the same as Jupyter Lab. Every cell block will be autofilled from cloning the repo. To run a cell block, select the button in the top right corner of each block that looks like a play button: 
![Screenshot 2023-05-27 at 12 58 48 PM](https://github.com/djohnst914/github_upload/assets/123714457/c7be3175-7688-498b-855a-88242f741518)
- You will run into 3 total cell blocks throughout the application that will ask you to 'Choose Files' when uploading data into Colab:
![Screenshot 2023-05-27 at 12 59 03 PM](https://github.com/djohnst914/github_upload/assets/123714457/0b7669cf-c332-42a0-9048-2aba96067f64)
**NOTE:** You will select whatever file is listed in the read_csv function after selecting 'Choose Files', the first example is underlined above. Then, go to the resources folder that was cloned with the repo and select the listed csv file:
![Screenshot 2023-05-27 at 12 59 11 PM](https://github.com/djohnst914/github_upload/assets/123714457/1dfa381c-347a-4a3e-ad3e-04d429049099)
![Screenshot 2023-05-27 at 12 59 19 PM](https://github.com/djohnst914/github_upload/assets/123714457/5610e115-05c0-4c8d-9ea0-9772fdfdacc6)
- Repeat these steps throughout the main application.
- There are a few interactive graphs the user can manipulate to better understand a trend or explore a hypothesis they might have. The graphs are reltaively very user friendly, but if you find yourself having issues interacting with the them .. 

-**[Configuring hvPlot Tools](https://docs.bokeh.org/en/2.4.0/docs/user_guide/tools.html)**

---

## *Contributor*
For any questions, comments, concerns, feel free to contact below:
- Dylan Johnston
- Email: dylanhjjohnston@gmail.com
- [GitHub](https://github.com/djohnst914)

---

## *License*

This software is licensed under the MIT License. See [LICENSE](https://github.com/djohnst914/MercadoLibre_Time_Series/blob/main/LICENSE) file for details. 