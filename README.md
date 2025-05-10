## Project Summary

In this project, you will build a custom chatbot using OpenAI's API and a dataset of your choice, **without relying on frameworks** like LangChain. This manual approach helps you understand the underlying mechanics of chatbot systems and prompt engineering.

You will:
- Choose and justify a dataset
- Prepare the data for custom querying
- Build and test a chatbot using OpenAI and pandas
- Demonstrate the impact of your dataset on chatbot responses

## What Will You Build?

By the end of this project, you will have a chatbot tailored to a custom scenario. You are responsible for selecting and processing the dataset, implementing a custom querying system, and showing the chatbot’s enhanced performance through specific example questions.

## Recommended Data Sources

Choose from the following data options or upload your own:

### Provided CSV Datasets (in `/data` folder)
- **2023_fashion_trends.csv**: Fashion quotes and insights for 2023
- **character_descriptions.csv**: Fictional characters with attributes
- **nyc_food_scrap_drop_off_sites.csv**: Info on NYC compost drop-offs

### External Options
- **Wikipedia API**: Pull structured article content (except “2022” and “2023 Syria–Turkey earthquake” articles)
- **Your Own Source**: Web scraped data or text-heavy datasets (20+ rows)

> ⚠️ Avoid numeric-heavy datasets like budgets or inventory; OpenAI LLMs are not optimized for such data.

## Project Instructions

Work primarily in `project.ipynb`. The notebook includes `TODO` markers guiding you through each step:

### 1. Choose a Dataset and Explain the Scenario
- Pick a dataset
- Write a paragraph (Markdown cell) describing:
  - Why the data is relevant
  - The context where this chatbot would be used

### 2. Prepare the Dataset
- Ensure the dataset is structured as a DataFrame with a `text` column
- You can clean the data using any tool (Excel, Sheets, or Python)

### 3. Perform Custom Query Integration
- Use provided query code with your dataset
- Replace all references to demo datasets

### 4. Test and Demonstrate Chatbot Behavior
- Write **two questions** showing chatbot answers with and without custom data
- Highlight how your data improves specificity or relevance

## Example Scenarios

- **Fashion Assistant**: Uses `2023_fashion_trends.csv` to answer current style questions
- **Theater Character Bot**: Helps users find similar characters across stories
- **NYC Compost Helper**: Finds nearby drop-off sites and explains hours or requirements

## Final Deliverables

- Complete `project.ipynb` with all four TODOs addressed
- Functional chatbot integrated with your dataset
- Clear demonstration of how custom data improves the chatbot

---

Happy coding! 🎯
