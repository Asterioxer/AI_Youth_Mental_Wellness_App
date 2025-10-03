
  # AI Youth Mental Wellness App

  This is a code bundle for AI Youth Mental Wellness App. The original project is available at https://www.figma.com/design/RJX3QzEtUhMYVprqxbghNt/AI-Youth-Mental-Wellness-App.

  ## Running the code

  Run `npm i` to install the dependencies.

  Run `npm run dev` to start the development server.


  # Working Supabase Logs

  Supabase client initialized: {
  "url": "https://zzxeiiuseltxopybftvy.supabase.co",
  "keyLength": 208,
  "keyStart": "eyJhbGciOiJIUzI1NiIs..."
}
Testing database connection...
Database connection successful! Table accessible.
Database connection status: true
Loading entries for user: amitabhbachhuison@gmail.com
Loading journal entries for user: amitabhbachhuison@gmail.com
Load response: 200 {"entries":[]}
Loaded entries from server: {
  "entries": []
}
No entries found for user
No entries found in database, starting fresh
New entry submitted: {
  "content": "I feel like .........",
  "mood": "neutral",
  "confidence": 0.5
}
Current user info: {
  "name": "amitabhbachhuison",
  "email": "amitabhbachhuison@gmail.com"
}
Saved to localStorage, total entries: 1
Attempting to save to database for user: amitabhbachhuison@gmail.com
Saving journal entry via demo endpoint: {
  "content_text": "I feel like .........",
  "mood_score": 3,
  "user_email": "amitabhbachhuison@gmail.com"
}
Server response: 200 {"message":"Journal entry created successfully","entry":{"id":"13b22c2c-c24b-437b-a998-58c2a444753b","user_id":"724c72e5-724c-4724-8724-724c72e5724c","created_at":"2025-10-03T05:21:18.766328+00:00","content_text":"I feel like .........","content_audio_url":null,"mood_score":3,"ai_analysis_status":"pending"}}
Successfully saved to database via server: {
  "message": "Journal entry created successfully",
  "entry": {
    "id": "13b22c2c-c24b-437b-a998-58c2a444753b",
    "user_id": "724c72e5-724c-4724-8724-724c72e5724c",
    "created_at": "2025-10-03T05:21:18.766328+00:00",
    "content_text": "I feel like .........",
    "content_audio_url": null,
    "mood_score": 3,
    "ai_analysis_status": "pending"
  }
}
✅ Entry saved to database successfully
Loading journal entries for user: amitabhbachhuison@gmail.com
Load response: 200 {"entries":[{"id":"13b22c2c-c24b-437b-a998-58c2a444753b","user_id":"724c72e5-724c-4724-8724-724c72e5724c","created_at":"2025-10-03T05:21:18.766328+00:00","content_text":"I feel like .........","content_audio_url":null,"mood_score":3,"ai_analysis_status":"pending"}]}
Loaded entries from server: {
  "entries": [
    {
      "id": "13b22c2c-c24b-437b-a998-58c2a444753b",
      "user_id": "724c72e5-724c-4724-8724-724c72e5724c",
      "created_at": "2025-10-03T05:21:18.766328+00:00",
      "content_text": "I feel like .........",
      "content_audio_url": null,
      "mood_score": 3,
      "ai_analysis_status": "pending"
    }
  ]
}
Converted entries: 1
Refreshed entries from database: 1
