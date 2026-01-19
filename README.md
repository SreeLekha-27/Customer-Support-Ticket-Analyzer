# Customer Support Ticket Analyzer

## Project Overview
The **Customer Support Ticket Analyzer** is a Python-based project developed as part of the **Data Analytics (DA) Module-End 4 assignment**. This project focuses on analyzing customer support tickets to extract insights that can help improve customer service, identify common issues, monitor ticket priority, and evaluate service quality.

Customer support teams handle numerous tickets daily, and analyzing these tickets helps identify recurring problems, understand customer sentiment, and improve response efficiency.

---

## Features

1. **Preloaded Ticket Data**  
   - The system starts with 10 preloaded tickets stored in a dictionary of lists.  
   - Each ticket contains:
     - Ticket Number
     - Customer Name
     - Issue Description
     - Priority (High / Medium / Low)

2. **Add New Tickets**  
   - Users can add new tickets with automatic ticket numbering starting from 11.  
   - Priority is validated to accept only High, Medium, or Low.  
   - New tickets are appended to the main ticket data.

3. **Issue Description Cleaning**  
   - Removes punctuation (.,!?-)  
   - Converts multiple spaces to single spaces  
   - Strips leading and trailing spaces  
   - Converts text to lowercase  
   - Replaces common shorthand/slang (e.g., “ok” → “okay”)  
   - Ensures consistent text for analysis.

4. **Keyword-Based Issue Insights**  
   - Counts tickets containing specific keywords like:
     - “poor”  
     - “good”  
     - “slow”  
     - “excellent”  
   - Case-insensitive search to capture all variations.

5. **Priority Analysis**  
   - Computes the number of tickets for each priority level (High, Medium, Low)  
   - Helps identify urgent issues vs. normal/low-priority requests.

6. **Longest Issue Description**  
   - Identifies the ticket with the longest issue description based on word count.  
   - Useful for highlighting complex customer issues.

7. **Unique Words Extraction**  
   - Extracts all unique words from issue descriptions.  
   - Provides a vocabulary set of customer terms for deeper insights.

---
