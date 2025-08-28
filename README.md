# AI Conversation Summarizer

A lightweight AI tool that summarizes chat or email logs into clear bullet points.  
The code includes comments in **English** for clarity and collaboration.

# Features
- Input: raw conversation logs (e.g. from chat, email).
- Output: JSON with concise key points + timestamp.
- Clean code with step-by-step comments in English.
- Designed to run with free resources.

# Usage
1. Clone the repository:
   git clone https://github.com/<your-username>/ai-conversation-summarizer.git

2. Open the notebook in Google Colab.

3. Run the cells step by step.


# Example Input:
[2025-08-27 09:15] Marco: Ragazzi, il cliente vuole la bozza entro venerdì.
[2025-08-27 09:17] Lucia: Ok, io preparo le slide.
[2025-08-27 09:20] Paolo: Io sistemo il codice.


# Example Output:
{
  "summary": [
    "Client needs draft by Friday",
    "Lucia will prepare slides",
    "Paolo will fix the code"
  ],
  "timestamp": "2025-08-28T12:00:00Z"
}


# License
MIT License
