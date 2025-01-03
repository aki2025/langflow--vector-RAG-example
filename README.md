# langflow--vector-RAG-example
langflow- vector RAG example creation.

Load your data into a vector database with the 📚 **Load Data** flow, and then use your data as chat context with the 🐕 **Retriever** flow.

**🚨 Add your OpenAI API key as a global variable to easily add it to all of the OpenAI components in this flow.** 

**Quick start**
1. Run the 📚 **Load Data** flow.
## 📚 1. Load Data Flow

Run this first! Load data from a local file and embed it into the vector database.

Select a Database and a Collection, or create new ones. 

Click ▶️ **Run component** on the **Astra DB** component to load your data.

* If you're using OSS Langflow, add your Astra DB Application Token to the Astra DB component.

#### Next steps:
 Experiment by changing the prompt and the contextual data to see how the retrieval flow's responses change.

<img width="595" alt="image" src="https://github.com/user-attachments/assets/20469052-12cc-40e0-806a-657e478bcb10" />

   
3. Run the 🐕 **Retriever** flow.

   ## 🐕 2. Retriever Flow

This flow answers your questions with contextual data retrieved from your vector database.

Open the **Playground** and ask, 

```
What is this document about?
```
<img width="676" alt="image" src="https://github.com/user-attachments/assets/e6a587d7-0909-401c-96b1-83888d6e3c26" />


**Next steps** 

- Experiment by changing the prompt and the loaded data to see how the bot's responses change. 

For more info, see the [Langflow docs](https://docs.langflow.org/starter-projects-vector-store-rag).
