# Mikkel Endresen

#### Technical Skills: Python, C++, Numpy, Pytorch, Langchain, Pandas, Sklearn, FastAPI, Django


## Projects

### Car crash severity classification (_2023_)
- Used a dataset with traffic data from ACT and one with traffic camera locations to predict the car crash severity under certain conditions. Applied different statistical models as well as a neural networks to the problem in order to compare their performance. Performed extensive data preprocessing as the dataset was very skewed. SVM ended up being the best model with an accuracy of 93%.
- Recieved the Berrijam Innovative Applications of AI Award for the project.
- Key technologies used: Sklearn, Numpy, Pandas.
  
[Github Repo](https://github.com/MikkelEndresen/portfolio/tree/main/TheLastOfUs)

### Language identification using convolutional neural networks (_2023_)
- Applied Convolutional Neural Networks to the Language Identification problem. Transformed audio samples to mel spectograms that was used as input for the model and subsequently trained it to identify five different languages. Performed hyperparameter tuning to identify optimal paramters for four different models. Best accuracy was 88.4% using a CNN-BiLSTM model.
- Key technologies used: Pytorch, Numpy.

[Github Repo](https://github.com/MikkelEndresen/portfolio/tree/main/LanguageIdentification)

### Data extraction from unstructured text (_2024_)
- The task was to extract data into a structured format from unstructured OCR texts. Tried 3 different experiments with mixed results. Initally tried applying an LLM to identify the desired data. It seemed to identify most of the relevant information, but it struggled with formatting. Then I attempted to use a rule-based approach. However, due to the erros in the text from the OCR and the variability in the data the results were insufficient. Therefore, I returned to the LLM approach, but now using LangChains JsonOutputParser which was able to structure the data on the desired format.
- Key technologies used: Ollama, LangChain.

[Github Repo](https://github.com/MikkelEndresen/DataExtractionFromText)

### CSV -> pandas, web application (_2024_)
- A web application that processes and displays data. Input a .csv file and it returns the data as a df with the correct dtypes. You can also manually select other dtypes if needed. Uses React.js for the frontend and a Django for the backend API's.
- Key technologies used: Pandas, Django, React.

[Github Repo](https://github.com/MikkelEndresen/DataCleaning)

## Education

### University of New South Wales  (_Feb 2020 - Dec 2023_)

  Bachelor of Science in Computer Science (Artificial Intelligence) with Distinction
  
  Bachelor of Commerce in Financial Technology with Distinction
  
  Special Achievements:
  - Leadership Foundations, Participant  (_2023_)
  - UNSW Professional Development Program - Workplace Experience, Participant  (_2023_)
  - UNSW Career Discovery Mentoring Program, Mentee  (_2023_)
  - Innovator Pro, Participant  (_2021_)

## Work Experience

**Software Developer @ GoodX (_Nov 2020 - Jan 2023_)**
- Promted from intern to Software Developer
- Designed and implemented a microservices architecture using RESTful APIs with FastAPI, utilising AWS cloud solutions like S3 and lambda for deployment. 
- Contributed to the development of business valuation algorithms by improving data processes and legacy code, reducing valuation errors by 30%.
- Automated the business valuation report generation using a Python library called reportlab, producing individualised reports for over 500 companies.


**Consultant @ UNSW Finance (_Feb 2023 - May 2023_)**
- Collaborated in a team of eight on the first design of a Graduate program for the Finance department at UNSW. 


**Ice Hockey and Skating Coach @ Entrepreneur (_Dec 2021 - Dec 2023_)**
- Founded and managed my own business offering private lessons in Ice Hockey and Ice Skating, coaching for more than 500+ hours.


## Learning

- [Hackerrank Profile](https://www.hackerrank.com/profile/endresen_mikkel)
- Deeplearning.AI course: [Databases: From Embeddings to Applications](https://learn.deeplearning.ai/accomplishments/4b82e5ea-042f-408c-8ad2-6c81675f916c?usp=sharing)
- Deeplearning.AI course: [Building Applications with Vector Databases](https://learn.deeplearning.ai/accomplishments/e6ffc5ae-e56e-4f19-b473-37a482089334)





