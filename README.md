# Mikkel Endresen



<style>
  .skills-table {
    width: 100%;
    border-collapse: collapse;
    border: 1px solid #ddd;
  }
  .skills-table th, .skills-table td {
    border: 1px solid #ddd;
    padding: 8px;
    text-align: left;
  }
  .skills-table th {
    background-color: #f2f2f2;
  }
  .skills-table ul {
    margin: 0;
    padding-left: 20px;
  }
  /* Add this rule for vertical lines */
  .skills-table td, .skills-table th {
    border-right: 1px solid #ddd;
  }
  /* Add this rule to remove the right border from the last column */
  .skills-table td:last-child, .skills-table th:last-child {
    border-right: none;
  }
</style>


<h2>Technical Skills</h2>
<table class="skills-table">
  <thead>
    <tr>
      <th>Skill</th>
      <th>Experience</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Vector Databases</td>
      <td>
        <ul>
          <li>Course, <a href="cypher-fundamentals">Cypher Fundamentals</a></li>
          <li>Course, <a href="introduction-to-neo4j-graph-data-science">Introduction to Neo4j Graph Data Science</a></li>
          <li>Course, <a href="databases:-from-embeddings-to-applications">Databases: From Embeddings to Applications</a></li>
          <li>Course, <a href="building-applications-with-vector-databases">Building Applications with Vector Databases</a></li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>FastAPI</td>
      <td>
        <ul>
          <li>Professional Experience, <a href="software-developer">GoodX</a></li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Numpy</td>
      <td>
        <ul>
          <li>University project, <a href="car-crash-severity-classification">Car crash severity classification</a></li>
          <li>University project, <a href="language-identification-using-convolutional-neural-networks">Language identification using convolutional neural networks</a></li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Pandas</td>
      <td>
        <ul>
          <li>University project, <a href="car-crash-severity-classification">Car crash severity classification</a></li>
          <li>Personal project, <a href="CSV-to-pandas-web-application">CSV to pandas web application</a></li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>AWS</td>
      <td>
        <ul>
          <li>Professional Experience, <a href="software-developer">GoodX</a></li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Azure</td>
      <td>
        <ul>
          <li>Course, <a href="fundamentals-of-azure-ai-services">Fundamentals of Azure AI services</a></li>
          <li>Course, <a href="fundamental-ai-concepts">Fundamental AI Concepts</a></li>
          <li>Course, <a href="fundamentals-of-machine-learning">Fundamentals of machine learning</a></li>
          <li>Course, <a href="microsoft-azure-ai-fundamentals:-ai-overview">Microsoft Azure AI Fundamentals: AI Overview</a></li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Pytorch</td>
      <td>
        <ul>
          <li>University Project, <a href="#language-identification-using-convolutional-neural-networks">Language Identification</a></li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>FastAPI</td>
      <td>
        <ul>
          <li>Professional experience, <a href="#Softwar-Developer-@-GoodX">GoodX</a></li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Django</td>
      <td>
        <ul>
          <li>Personal project, <a href="CSV-to-pandas-web-application">CSV to pandas web application</a></li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>ReactJS</td>
      <td>
        <ul>
          <li>Personal project, <a href="CSV-to-pandas-web-application">CSV to pandas web application</a></li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Shell</td>
      <td>
        <ul>
          <li>Course, <a href="introduction-to-shell">Introduction to Shell</a></li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>


## Projects

### Car crash severity classification (_2023_)  <a name="car-crash-severity-classification"></a>
- Used a dataset with traffic data from ACT and one with traffic camera locations to predict the car crash severity under certain conditions. Applied different statistical models as well as a neural networks to the problem in order to compare their performance. Performed extensive data preprocessing as the dataset was very skewed. SVM ended up being the best model with an accuracy of 93%.
- Recieved the Berrijam Innovative Applications of AI Award for the project.
- Key technologies used: Sklearn, Numpy, Pandas.
  
[Github Repo](https://github.com/MikkelEndresen/portfolio/tree/main/TheLastOfUs)

### Language identification using convolutional neural networks (_2023_) <a name="language-identification-using-convolutional-neural-networks"></a>
- Applied Convolutional Neural Networks to the Language Identification problem. Transformed audio samples to mel spectograms that was used as input for the model and subsequently trained it to identify five different languages. Performed hyperparameter tuning to identify optimal paramters for four different models. Best accuracy was 88.4% using a CNN-BiLSTM model.
- Key technologies used: Pytorch, Numpy.

[Github Repo](https://github.com/MikkelEndresen/portfolio/tree/main/LanguageIdentification)

### Data extraction from unstructured text (_2024_)  <a name="data-extraction-from-unstructured-text"></a>
- The task was to extract data into a structured format from unstructured OCR texts. Tried 3 different experiments with mixed results. Initally tried applying an LLM to identify the desired data. It seemed to identify most of the relevant information, but it struggled with formatting. Then I attempted to use a rule-based approach. However, due to the erros in the text from the OCR and the variability in the data the results were insufficient. Therefore, I returned to the LLM approach, but now using LangChains JsonOutputParser which was able to structure the data on the desired format.
- Key technologies used: Ollama, LangChain.

[Github Repo](https://github.com/MikkelEndresen/DataExtractionFromText)

### CSV to pandas web application (_2024_)  <a name="CSV-to-pandas-web-application"></a>
- A web application that processes and displays data. Input a .csv file and it returns the data as a df with the correct dtypes. You can also manually select other dtypes if needed. Uses React.js for the frontend and a Django for the backend API's.
- Key technologies used: Pandas, Django, React.

[Github Repo](https://github.com/MikkelEndresen/DataCleaning)

## Education

### University of New South Wales  (_Feb 2020 - Dec 2023_) <a name="unsw"></a>

  Bachelor of Science in Computer Science (Artificial Intelligence) with Distinction
  
  Bachelor of Commerce in Financial Technology with Distinction
  
  Special Achievements:
  - Leadership Foundations, Participant  (_2023_)
  - UNSW Professional Development Program - Workplace Experience, Participant  (_2023_)
  - UNSW Career Discovery Mentoring Program, Mentee  (_2023_)
  - Innovator Pro, Participant  (_2021_)

## Work Experience

**Software Developer @ GoodX (_Nov 2020 - Jan 2023_)**  <a name="software-developer"></a>
- Promted from intern to Software Developer
- Designed and implemented a microservices architecture using RESTful APIs with FastAPI, utilising AWS cloud solutions like S3 and lambda for deployment. 
- Contributed to the development of business valuation algorithms by improving data processes and legacy code, reducing valuation errors by 30%.
- Automated the business valuation report generation using a Python library called reportlab, producing individualised reports for over 500 companies.


**Consultant @ UNSW Finance (_Feb 2023 - May 2023_)**  <a name="consultant"></a>
- Collaborated in a team of eight on the first design of a Graduate program for the Finance department at UNSW. 


**Ice Hockey and Skating Coach @ Entrepreneur (_Dec 2021 - Dec 2023_)** <a name="entrepreneur"></a>
- Founded and managed my own business offering private lessons in Ice Hockey and Ice Skating, coaching for more than 500+ hours.



## Learning
- [Hackerrank Profile](https://www.hackerrank.com/profile/endresen_mikkel)  <a name="hackerrank"></a>
- Deeplearning.AI course: [Databases: From Embeddings to Applications](https://learn.deeplearning.ai/accomplishments/4b82e5ea-042f-408c-8ad2-6c81675f916c?usp=sharing) <a name="databases:-from-embeddings-to-applications"></a>
- Deeplearning.AI course: [Building Applications with Vector Databases](https://learn.deeplearning.ai/accomplishments/e6ffc5ae-e56e-4f19-b473-37a482089334)  <a name="building-applications-with-vector-databases"></a>
- DataCamp course: [Introduction to Shell](https://www.datacamp.com/completed/statement-of-accomplishment/course/095dfc1407b0f0a600a1185b54581dac52f06d4b)  <a name="introduction-to-shell"></a>
- Neo4j course: [Cypher Fundamentals](https://graphacademy.neo4j.com/c/59055e2b-b506-4297-986d-75186097348c/)  <a name="cypher-fundamentals"></a>
- Neo4j course: [Introduction to Neo4j Graph Data Science](https://graphacademy.neo4j.com/c/853a8c4f-0da6-4d73-8e96-0770751b3557/)  <a name="introduction-to-neo4j-graph-data-science"></a>
- Microsoft module: [Fundamental AI Concepts](https://learn.microsoft.com/en-us/users/mikkelendresen-2694/achievements/4s75de7k)  <a name="fundamental-ai-concepts"></a>
- Microsoft module: [Fundamentals of Azure AI Services](https://learn.microsoft.com/nb-no/users/mikkelendresen-2694/achievements/vkfhz7em?ref=https%3A%2F%2Fwww.linkedin.com%2F)  <a name="fundamentals-of-azure-ai-services"></a>
- Microsoft module: [Fundamentals of machine learning](https://learn.microsoft.com/en-us/users/mikkelendresen-2694/achievements/pta9r854)  <a name="fundamentals-of-machine-learning"></a>
- Microsoft module: [Microsoft Azure AI Fundamentals: AI Overview](https://learn.microsoft.com/nb-no/users/mikkelendresen-2694/achievements/wagth3fn?ref=https%3A%2F%2Fwww.linkedin.com%2F)  <a name="microsoft-azure-ai-fundamentals:-ai-overview"></a>





