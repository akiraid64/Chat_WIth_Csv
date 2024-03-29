# Chat_WIth_Csv
This Streamlit application combines a chat interface with data visualization capabilities, allowing users to interact with their datasets and explore insights through intuitive visualizations.

# Chat and Visualize Data with Streamlit

This Streamlit application combines a chat interface with data visualization capabilities, allowing users to interact with their datasets and explore insights through intuitive visualizations.

## Features:

- **Chat Tab:** Upload a CSV file, engage in chat-based interactions, and view the conversation history. The system uses language models for conversational retrieval.

- **Visualize Data Tab:**

In the "Visualize Data" tab, users can explore different types of visualizations for the uploaded dataset.

**Instructions:**
1. After uploading the CSV file, select a visualization type from the sidebar.
2. Configure the visualization parameters (e.g., X-axis, Y-axis, filters) using the provided options.
3. View the generated visualization on the main panel.

**Available Visualizations:**
- Line Chart
- Clustered Bar Chart
- Heatmap
- Scatter Plot
- Histogram
- Box Plot
- Pie Chart


## Local Language Model Deployment:

In case anyone needs to run this application locally, the local language model is being deployed from the local machine. The model being used here is `llama-2-7b-chat.ggmlv3.q8_0.bin`, available on Hugging Face. To set it up:

1. Download the language model from [Hugging Face](https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main).
2. Save the downloaded model file in the same folder as `vis.py`.
3. Ensure to edit the model's filename in the code accordingly.

## How to Run:

1. Install dependencies:
   ```bash
   pip install streamlit
   pip install langchain-community
## How to Run:

```bash
streamlit run vis.py
```

# Install Dependencies

To set up the required dependencies for this project, follow the steps below:

1. **Navigate to the Project Folder:**
   Open the command prompt and change your current directory to the location where your project is stored. You can use the `cd` command to navigate to the project folder.

   ```bash
   cd path\to\your\project
   ```
   Once you are in the project folder, use the following command to install the dependencies listed in the requirements.txt file:
   ```bash
   pip install -r requirements.txt
   ```
## Contributing

Contributions are welcome! If you'd like to contribute to the development of this project, follow these steps:

1. **Fork the Repository:**
   Click the "Fork" button at the top right of the repository to create your copy.

2. **Clone your Fork:**
   Clone your forked repository to your local machine using the following command:
   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```


