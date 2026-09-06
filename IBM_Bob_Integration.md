# How we used IBM Bob in CyberShield

IBM watsonx.ai (Granite Model) is the brain of CyberShield.

1. Message Analysis: User ka message (SMS/WhatsApp) IBM Bob ko bheja jata hai.
2. Threat Detection: Bob check karta hai - Urgent language? KYC maang raha hai? Suspicious link hai?
3. Risk Score: HIGH / MEDIUM / LOW
4. Safe Action: User ko simple language me batata hai - "Click mat karo, official app se check karo"

Example: 
Input: "Your account will be blocked, update KYC now"
Output from Bob: Risk-HIGH, Reason-Urgent+KYC, Action-Do not click

This fulfills the requirement of using IBM Technology.
