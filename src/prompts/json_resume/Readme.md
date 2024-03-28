# Create JSON Resume from a PDF

This guide provides steps for converting a PDF version of your CV into a JSON Resume format using ChatGPT. The process involves generating a standard JSON from your PDF CV and then converting that JSON into the [JSON Resume format](https://jsonresume.org/schema/), which can be used with tools like [Resoume](https://www.resoume.com/) to craft a professional resume quickly.

## Prerequisites

Before starting, ensure you have the following:

- Your CV in PDF format or any other format that can be easily read and converted.
- Access to [ChatGPT](https://openai.com/chatgpt) to assist with the conversion process.
- Familiarity with JSON formatting.

## Steps

1. **Convert PDF CV to JSON:**  
   - Use the `convert_cv_to_json.txt` prompt to ask ChatGPT to read your CV and convert it into a standard JSON format. This step requires you to describe the contents of your CV in detail to ChatGPT or use specific tools to extract the text from your PDF into a format that ChatGPT can process.

2. **Convert Standard JSON to JSON Resume Format:**  
   - With the standard JSON of your CV, use the `convert_from_json_to_json_resume.txt` prompt to instruct ChatGPT to convert this JSON into the JSON Resume format. This involves mapping the fields from your standard JSON to the fields defined in the JSON Resume schema.

3. **Use JSON Resume with Resoume:**  
   - With your CV in JSON Resume format, you can now use it on sites like Resoume to customize and generate a professional-looking resume. These platforms allow you to import your JSON Resume and apply various templates and designs to create a resume that stands out.

## Additional Resources

- [JSON Resume Schema](https://jsonresume.org/schema/): Detailed documentation of the JSON Resume format to help you understand the structure and fields required.
- [ChatGPT](https://openai.com/chatgpt): Interactive AI chatbot by OpenAI that can assist with various tasks, including converting CVs to JSON.
- [Resoume](https://www.resoume.com/): A platform that allows users to create professional resumes by importing their JSON Resume.

By following these steps and utilizing the provided resources, you can quickly transform your traditional CV into a modern, customizable JSON Resume. This method not only simplifies the process of resume creation but also opens up possibilities for integrating your resume data with various tools and platforms for job applications and professional networking.
