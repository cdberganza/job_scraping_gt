# Job Search Automation in Guatemala

This project automates the job search process by extracting job listings from popular job search websites in Guatemala. The system allows users to input specific job positions or categories and retrieve the most recent job offers in a CSV format, saving time and effort for job placement professionals.

## Key Features

- **Automated Job Search**: Automatically generates a search URL based on the user's input (job position or category).
- **Web Scraping**: Extracts key details such as job title, company, location, salary, and job URL using `BeautifulSoup`.
- **CSV Output**: Saves the extracted job offers in a structured CSV file, which is easy to review and share.
- **User Interaction in Spanish**: Since the system is designed for Spanish speakers in Guatemala, user prompts and CSV headers are presented in Spanish for ease of use.

## How It Works

1. **Generate a Search URL**: The system constructs a URL based on the user's input for the job position or category they want to search for.
2. **Data Extraction**: Using web scraping, relevant job offer information is extracted, such as job titles, companies, locations, salaries, and job links.
3. **Save as CSV**: The extracted data is saved to a CSV file with headers in Spanish, ready for further review or distribution.

## Technologies Used

- **Python**: The core language used to build the automation.
- **Libraries**:
  - `requests`: For making HTTP requests to retrieve webpage content.
  - `BeautifulSoup`: For parsing and extracting data from HTML pages.
  - `numpy`: Used for handling missing data (`NaN` values).
  - `csv`: For writing job offer data into a CSV file.

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/job-search-automation.git
´´´
2. Install the required Python libraries:
  ```bash
  pip install requests beautifulsoup4 numpy
```
3. Run the notebook to begin the job search automation:
   - Open the Jupyter Notebook and follow the instructions to input the job position or category.
   - The results will be saved as a CSV file with job offers.

## Example Usage

After running the notebook, you will be prompted to input a job position. The system will then:
1. Generate a search URL based on your input.
2. Scrape the website for job listings.
3. Save the job details to a CSV file.

For example:
- Input: `"Desarrollador"`
- Output: A CSV file named `Desarrollador.csv` containing the latest job offers.

## Contributions

Contributions are welcome! Feel free to open issues or submit pull requests if you want to improve or extend the functionality of the project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
