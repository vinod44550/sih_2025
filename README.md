# sih_2025
This is a demo version of an AI-powered chatbot for public health awareness, created for the Smart India Hackathon (SIH).
The chatbot provides basic health information such as:<br>
.Preventive healthcare tips<br>
.Common disease symptoms<br>
.Vaccination reminders<br><br>

Currently, it is a prototype, showing the feasibility of a multilingual chatbot.<br>



User (WhatsApp/SMS)
        |
        v
   Twilio API
        |
        v
   Rasa NLU (IndicBERT) ---> Intent Classification
        |
        v
   Rasa Core (Dialogue Mgmt)
        |
        v
   Responses (Static Info)
        |
        v
User receives trusted info


