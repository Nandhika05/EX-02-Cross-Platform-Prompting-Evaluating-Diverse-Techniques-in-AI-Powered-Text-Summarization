# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

# register Number : 212223040125

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## Algorithm

# 1.Define Use Case
Identify a realistic personalization scenario (e.g., product recommendations based on user behavior).

# 2.Select Prompt Types
Choose three distinct prompting strategies:

Straightforward Prompt Tabular Format Prompt Missing Word Prompt

# 4.Design Prompts
Write specific prompt examples aligned with the use case for each strategy.

# 5.Submit to Platforms
Run each prompt through two different AI platforms (ChatGPT and Claude).

# 6.Collect Outputs
Record the responses generated by each platform.

# 7.Evaluate Criteria
Assess each output based on:
Relevance Coherence Customization Depth Responsiveness Tone

# 8.Compare and Recommend
Identify the best-performing combinations and suggest practical applications.

# Use Case:
AI-Driven Personalization for Travel Recommendations
# Scenario: 
The system tailors vacation packages based on user preferences, including past trips, browsing history, and travel-related interests. For instance, it offers personalized recommendations for destinations, accommodation types, activities, and experiences.

# 1. Straightforward Prompt
# Prompt:
```
"The user recently browsed tropical destinations, booked a beach resort, and added a diving course to their wishlist. Suggest personalized vacation packages."
```
# Outputs:
# ChatGPT:
Based on your interest in tropical destinations, I recommend a trip to Bali with options for scuba diving and a stay at a luxury beachfront resort. You may also like a snorkeling adventure in the Maldives or a yoga retreat in Costa Rica.

# Claude:
Since you’ve been exploring tropical escapes and diving activities, I suggest considering destinations like the Maldives with exclusive diving tours and resorts, or perhaps a wellness retreat in the Bahamas with guided underwater explorations.

# Evaluation:

| Criteria                | ChatGPT    | Claude     |
| ----------------------- | ---------- | ---------- |
| **Relevance**           | ✅ High     | ✅ High     |
| **Coherence**           | ✅ Natural  | ✅ Natural  |
| **Customization Depth** | ✅ Detailed | ✅ Moderate |
| **Responsiveness**      | ✅ Fast     | ✅ Fast     |
| **Tone**                | ✅ Friendly | ✅ Friendly |

Winner: ChatGPT – Slightly more specific and product-rich recommendations.

# 2. Tabular Format Prompting
# Prompt:
```
Based on the table below, generate personalized vacation packages.

Recently Viewed	Booked	Wishlist
Bali	Beach Resort	Diving Course
Maldives	-	Snorkeling Adventure
```
# Outputs:
# ChatGPT:
Recommended Vacation Packages:
• Beachfront resort in Bali with a diving certification course.
• Maldives all-inclusive resort with snorkeling and private tours.
• Costa Rica eco-lodge with underwater excursions and yoga.

# Claude:
Personalized Travel Suggestions:
• Diving package in the Bahamas, complete with resort and activity booking.
• Private Maldives villa with a guided snorkeling tour and beach access.
• Bali wellness package that includes diving and local cultural experiences.

# Evaluation:

| Criteria                | ChatGPT        | Claude         |
| ----------------------- | -------------- | -------------- |
| **Relevance**           | ✅ High         | ✅ High         |
| **Coherence**           | ✅ Structured   | ✅ Structured   |
| **Customization Depth** | ✅ Strong       | ✅ Strong       |
| **Responsiveness**      | ✅ Fast         | ✅ Fast         |
| **Tone**                | ✅ Professional | ✅ Professional |


Winner: Tie – Both platforms interpreted the tabular input effectively.

# 3. Missing Word Prompting
# Prompt:
```
"User is interested in [tropical destinations] and [beach resorts]. Suggest vacation packages like _______."
```
# Outputs:
# ChatGPT:
You might enjoy an all-inclusive stay in the Maldives, complete with guided snorkeling tours, or a luxury resort in Hawaii with surfing lessons and oceanfront villas.

# Claude:
Explore trips to the Caribbean with private beach villas and optional water sport packages, or perhaps a retreat in the Seychelles featuring beach activities and local cultural experiences.

#Evaluation:

| Criteria                | ChatGPT    | Claude     |
| ----------------------- | ---------- | ---------- |
| **Relevance**           | ✅ Strong   | ✅ Strong   |
| **Coherence**           | ✅ Good     | ✅ Good     |
| **Customization Depth** | ✅ Moderate | ✅ High     |
| **Responsiveness**      | ✅ Fast     | ✅ Fast     |
| **Tone**                | ✅ Friendly | ✅ Friendly |

Winner: Claude – Slightly more creative with diverse vacation options.

## Result:
Thus, the summarized Result section based on the experiment using the three prompt types (Straightforward, Tabular Format, Missing Word) and two AI platforms (ChatGPT and Claude).



