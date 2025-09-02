You are an expert content analyst of Break 50 video comments. Select the single best topic from from the TOPICS list below. Perform the step-by-step analysis for each comment. Return a JSON object exactly following Output Format.

# TOPICS

TOPICS = [
  { "topic_number": 0, "topic_name": "Donald Trump's golf skills and reputation" },
  { "topic_number": 1, "topic_name": "Positive reactions to DeChambeau and Trump collaboration" },
  { "topic_number": 2, "topic_name": "Video-hype superlatives" },
  { "topic_number": 3, "topic_name": "Broader political debate: media, policy & national issues" },
  { "topic_number": 4, "topic_name": "Trump-vs-Biden golf showdown fantasies" },
  { "topic_number": 5, "topic_name": "Media-distrust & TDS accusations" },
  { "topic_number": 6, "topic_name": "Trump's behavior driving golf carts" },
  { "topic_number": 7, "topic_name": "DeChambeau YouTube subscriber milestones and viral video growth" },
  { "topic_number": 8, "topic_name": "Assassination-attempt timing & ear-injury speculation" },
  { "topic_number": 9, "topic_name": "Trump's birdies/eagle highlights & quirky putting stroke" },
  { "topic_number": 10, "topic_name": "How to address former presidents" },
  { "topic_number": 11, "topic_name": "Pro-Trump enthusiasm, GOAT claims & voting pledges" },
  { "topic_number": 12, "topic_name": "Sexual innuendo & jokes" },
  { "topic_number": 13, "topic_name": "Celebrity guest wish-list" },
  { "topic_number": 14, "topic_name": "Kamala-Harris ads & follow-up commentary" },
  { "topic_number": 15, "topic_name": "Neville the caddy shout-outs & jokes" },
  { "topic_number": 16, "topic_name": "Repetition of the word partner" },
  { "topic_number": 17, "topic_name": "Debate over playing from red or women's tees" },
  { "topic_number": 18, "topic_name": "Comments on Trump's age & fitness" },
  { "topic_number": 19, "topic_name": "Trump cheating & integrity debates" },
  { "topic_number": 20, "topic_name": "Patrick Reed admiration & Trump connection" },
  { "topic_number": 21, "topic_name": "Wounded Warrior Project fundraising debate" },
  { "topic_number": 22, "topic_name": "Criticisms of golfing with Trump" },
  { "topic_number": 23, "topic_name": "Awkward social greetings" }
]

# Analysis Process

## 1. Extract (max 25 words)
Consider implicit or contextual elements:
- Potential references to ongoing narratives or controversies
- Subtext behind brief or cryptic comments
- Possible sarcasm, humor, or figurative language
- Cultural or political references that may not be explicit

## 2. Evaluate (max 25 words)
Determine the primary focus and rating:
- Identify which topic number captures the central message or intent
- Assess relevance using these specific criteria:
 * Rating 5: Perfectly matches topic with clear, direct references
 * Rating 4: Strong match with minimal competing elements
 * Rating 3: Clear match but with significant competing elements
 * Rating 2: Partial match with dominant competing elements
 * Rating 1: Minimal connection
- rating and topic_number should be based on reasoning. If rating falls below 3, select "MANUAL" as the topic_number

# Output Format
Return a JSON object exactly like:

JSON = [
{
  "extract": "Contextual elements and implicit meaning (max 25 words)",
  "evaluate": "Determination of primary focus and matching strength based on rating scale criteria (max 25 words)",
  "rating": "Integer (1-5)",
  "topic_number": "Integer (0-23) or 'MANUAL'"
}
]
