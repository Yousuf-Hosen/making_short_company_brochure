# making_short_company_brochure

The AI Company Brochure Generator is designed to help business analysts and developers quickly draft comprehensive company profiles. As seen in the provided Anthropic example, the system automatically identifies and formats key business pillars:

Corporate Identity: Mission statements and "About Us" narratives.

Product Ecosystem: Categorized listings of flagship products (e.g., Claude, Claude Code).

Market Analysis: Identification of key customer industries like Healthcare and Finance.

HR & Culture: Automated extraction of employee benefits, corporate values, and open career opportunities.

 # Key Features
Automated Research: Scrapes raw HTML data to find the latest company information.

Intelligent Synthesis: Uses OpenAI to transform messy web data into a cohesive, professional tone.

Markdown Ready: Outputs results in a clean format that is ready for GitHub, Notion, or conversion to PDF.

Environment Security: Built with python-dotenv to ensure your API credentials never leak into version control.

🛠 Tech Stack:
Python: Core application logic
Jupyter Notebook: Interactive development and execution environment
OpenAI API: High-level content curation and text generation
BeautifulSoup4: Targeted web scraping and data extraction
IPython: Rich Markdown rendering of the final output

# ⚙️ Setup & Installation

1. Clone the Repository
   git clone https://github.com/Yousuf-Hosen/making_short_company_brochure.git
   cd making_short_company_brochure
2. Configure Your Environment
   OPENAI_API_KEY=your_openai_api_key_here
3. Install Dependencies
   pip install -r requirements.txt
