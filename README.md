# lookalike_model
lookalike model for finding audience similar to seed audience

Link to Streamlit UI: [Similance Demos](https://similance-demos.streamlit.app/similance_insurance)

When asked to upload test data, you can find data here:
[src/resources/data/](src/resources/data/)

Each demo has 3 data files, for each demo name <demo>
  <demo>.csv is the main file.
  <demo>_master.csv is processed file that contains test data (data used for creating vector store)
  <demo>_test.csv is the data we use for uploading in UI and generation output.
  <demo>_output.csv is the output generated by uploading <demo>_test.csv

To un streamlit app locally:
1. Populate streamlet's secrets.toml with OPENAI_API_KEY.
2. Install requirements from requirements.txt
3. Run the following from project dir:
   ```
   streamlit run landing_page.py
   ```
4. The other pages used are in [pages/](pages/) directory.
