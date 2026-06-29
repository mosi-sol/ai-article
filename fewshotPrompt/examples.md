- Sentiment Analysis
```
# ROLE
You are a Data Analyst specializing in customer feedback.

# TASK
Classify the sentiment of the review as "Positive", "Neutral", or "Negative".

# PATTERN (Few-Shot Examples)
---
Input:  "The product arrived late and was damaged."
Output: Negative

Input:  "It's okay, nothing special but it works."
Output: Neutral

Input:  "Absolutely love this! Best purchase ever."
Output: Positive
---

# EXECUTION
Apply the exact logic and format from the PATTERN to the following input:

Input:  "The features are great, but the battery life is disappointing."
Output:    
```

- Email Response Generator
```
# ROLE
You are a Customer Support Specialist.

# TASK
Draft a polite, solution-oriented email response based on the customer's issue.

# PATTERN (Few-Shot Examples)
---
Input:  "My order #12345 hasn't arrived yet. It's been 2 weeks."
Output: "Subject: Update on Order #12345\n\nDear Customer,\n\nThank you for reaching out. I've checked your order status and see it's currently in transit. We expect delivery within 3-5 business days. I've attached the tracking link for your convenience. Please let us know if you have further questions.\n\nBest regards,\nSupport Team"

Input:  "I received the wrong item. I ordered a blue shirt but got a red one."
Output: "Subject: Resolution for Incorrect Item\n\nDear Customer,\n\nI sincerely apologize for the mix-up with your order. We'd like to make this right immediately. Please keep the red shirt, and we'll ship the correct blue one at no cost today. You'll receive a new tracking number shortly.\n\nBest regards,\nSupport Team"

Input:  "The product stopped working after 3 days. Can I get a refund?"
Output: "Subject: Refund Request Approved\n\nDear Customer,\n\nI'm sorry to hear about the issue. We've approved your full refund, which will be processed within 5-7 business days. No need to return the item. We appreciate your feedback and hope to serve you better in the future.\n\nBest regards,\nSupport Team"
---

# EXECUTION
Apply the exact logic and format from the PATTERN to the following input:

Input:  "I was charged twice for the same order. Please fix this."
Output:    
```

- 
```
# ROLE
You are a Customer Support Specialist.

# TASK
Draft a polite, solution-oriented email response based on the customer's issue.

# PATTERN (Few-Shot Examples)
---
Input:  "My order #12345 hasn't arrived yet. It's been 2 weeks."
Output: "Subject: Update on Order #12345\n\nDear Customer,\n\nThank you for reaching out. I've checked your order status and see it's currently in transit. We expect delivery within 3-5 business days. I've attached the tracking link for your convenience. Please let us know if you have further questions.\n\nBest regards,\nSupport Team"

Input:  "I received the wrong item. I ordered a blue shirt but got a red one."
Output: "Subject: Resolution for Incorrect Item\n\nDear Customer,\n\nI sincerely apologize for the mix-up with your order. We'd like to make this right immediately. Please keep the red shirt, and we'll ship the correct blue one at no cost today. You'll receive a new tracking number shortly.\n\nBest regards,\nSupport Team"

Input:  "The product stopped working after 3 days. Can I get a refund?"
Output: "Subject: Refund Request Approved\n\nDear Customer,\n\nI'm sorry to hear about the issue. We've approved your full refund, which will be processed within 5-7 business days. No need to return the item. We appreciate your feedback and hope to serve you better in the future.\n\nBest regards,\nSupport Team"
---

# EXECUTION
Apply the exact logic and format from the PATTERN to the following input:

Input:  "I was charged twice for the same order. Please fix this."
Output:
```

- Data Extraction to JSON
```
# ROLE
You are a Data Processing Assistant.

# TASK
Extract key information from the text and format it as valid JSON.

# PATTERN (Few-Shot Examples)
---
Input:  "John Smith, age 34, works as a Software Engineer at TechCorp in New York. Email: john.smith@email.com"
Output: { "name": "John Smith", "age": 34, "occupation": "Software Engineer", "company": "TechCorp", "location": "New York", "email": "john.smith@email.com" }

Input:  "Maria Garcia is 28 years old. She's a Marketing Manager at GlobalBrand, based in Madrid. Contact: maria.g@brand.com"
Output: { "name": "Maria Garcia", "age": 28, "occupation": "Marketing Manager", "company": "GlobalBrand", "location": "Madrid", "email": "maria.g@brand.com" }

Input:  "Dr. Alan Lee, 45, is a Senior Researcher at BioLab in Singapore. Reach him at alan.lee@biolab.sg"
Output: { "name": "Dr. Alan Lee", "age": 45, "occupation": "Senior Researcher", "company": "BioLab", "location": "Singapore", "email": "alan.lee@biolab.sg" }
---

# EXECUTION
Apply the exact logic and format from the PATTERN to the following input:

Input:  "Sarah Johnson, 31, works as a Product Designer at CreativeStudio in Berlin. Her email is sarah.j@creative.de"
Output:    
```

- Social Media Post Creator
```
# ROLE
You are a Social Media Manager.

# TASK
Create an engaging social media post with a clear Call to Action (CTA).

# PATTERN (Few-Shot Examples)
---
Input:  "New coffee shop opening downtown, organic beans, cozy atmosphere"
Output: "☕ Something special is brewing downtown! Our new café features 100% organic beans and the coziest corner in the city. Come taste the difference today! 🌿\n\n📍 Visit us at 123 Main St.\n#OrganicCoffee #NewOpening #DowntownVibes"

Input:  "Gym offering 50% off first month, personal training included, modern equipment"
Output: "💪 New Year, New You! Get 50% OFF your first month + FREE personal training session. Our state-of-the-art equipment is waiting for you!\n\n🔥 Sign up before Friday!\n#FitnessGoals #GymLife #SpecialOffer"

Input:  "Bookstore hosting author meet-and-greet this Saturday, free entry, book signing included"
Output: "📚 Meet your favorite author THIS Saturday! Join us for an exclusive meet-and-greet with free entry and book signing. Don't miss this chance!\n\n⏰ 3 PM - 6 PM\n#AuthorEvent #BookLovers #MeetAndGreet"
---

# EXECUTION
Apply the exact logic and format from the PATTERN to the following input:

Input:  "Pet grooming salon offering summer special: bath, haircut, and nail trim for $49, all breeds welcome"
Output:    
```
