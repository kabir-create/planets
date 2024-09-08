This Node.js project is designed to retrieve CSV data from a specific website, process it through a data pipeline and parser, and display the parsed data sequentially. The project handles the entire flow, from fetching the CSV data to parsing and displaying it in a user-friendly format.

**Features**
1.Fetch CSV data from a specified source (website).
2.Implement a data pipeline to handle streaming, parsing, and processing.
3.Parse CSV data efficiently and convert it into a structured format.
4.Display the processed data sequentially for easy viewing or further use.
5..Modular and scalable design for handling large datasets.
**Prerequisites**
Before you can run this project, make sure you have the following installed:

Node.js (v14.x or later)
npm (Node package manager)



**How It Works**
Data Fetching: The pipeline fetches CSV data from a provided URL or file. The data is streamed in chunks to handle large files without consuming too much memory.

CSV Parsing: The parser module processes the raw CSV data, converting it into structured JSON or object format for easy manipulation.

Data Display: The processed data is displayed sequentially, ensuring that each entry from the CSV is handled and shown in a meaningful order
