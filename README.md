## working with MeTTa
### Overview
This script facilitates processing and analyzing biological data using the MeTTa library. It focuses on loading datasets, extracting relationships between genes, transcripts, and proteins, and serializing the results into a structured JSON-compatible format.

### Features
- **Dataset Loader**: Recursively loads .metta files from a specified directory into a working space.
- **Gene-Transcript Mapping**: Fetches transcripts associated with a specified gene.
- **Transcript-Protein Mapping**: Determines the proteins derived from specific transcripts.
- **Serializer**: Converts raw MeTTa results into a JSON-serializable format for further analysis.



**Set Up:**

Method 1:

**Set Up the Virtual Environment**:

    ```sh
    python -m venv venv
    source venv/bin/activate
    ```
   ```sh
   pip install -r requirements.txt
   ```

Method 2:

**Set up Docker**:
```sh
docker build -t metta-app .
docker run -it --rm -v ${PWD}:/app metta-app
```




