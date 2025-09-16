# sih_2025
This is a demo version of an AI-powered chatbot for public health awareness, created for the Smart India Hackathon (SIH).
The chatbot provides basic health information such as:<br>
.Preventive healthcare tips<br>
.Common disease symptoms<br>
.Vaccination reminders<br><br>

Currently, it is a prototype, showing the feasibility of a multilingual chatbot.<br>



User (WhatsApp/SMS)<br>
        |<br>
        v<br>
   Twilio API<br>
        |<br>
        v<br>
   Rasa NLU (IndicBERT) ---> Intent Classification<br>
        |<br>
        v<br>
   Rasa Core (Dialogue Mgmt)<br>
        |<br>
        v<br>
   Responses (Static Info)<br>
        |<br>
        v<br>
User receives trusted info<br>


