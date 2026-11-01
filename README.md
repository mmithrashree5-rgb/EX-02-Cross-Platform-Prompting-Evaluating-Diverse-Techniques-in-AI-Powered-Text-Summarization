# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization


## AIM

To analyze and compare the effectiveness of different prompt structures (**Basic Prompting, Role Prompting, Context Prompting, Constraint Prompting, and Output Format Prompting**) across different AI platforms (**ChatGPT, Gemini, Claude AI, and Microsoft Copilot**) for the purpose of **text summarization**.

## SCENARIO

You are a member of a technical content development team for an online learning platform that provides simplified summaries of technical articles to undergraduate engineering students.

The objective is to summarize a 500-word technical article on **"AI-Based Smart Waste Management System"** using different prompting techniques across multiple AI platforms.

The generated summaries are evaluated based on the following factors:

- Accuracy
- Coherence
- Simplicity
- Relevance
- Readability
- Response Quality

## APPLICATION SELECTED

**Text Summarization – AI-Based Smart Waste Management System**

## PROMPTING TECHNIQUES USED

### 1. Basic Prompt

**Prompt Used:**

```text
Summarize the following article on "AI-Based Smart Waste
Management System" in approximately 150 words.

The summary should:
- Include the key ideas.
- Be understandable for undergraduate students.
- Preserve the original meaning.

Article:
[Paste the article here]
```

### 2. Role Prompt

**Prompt Used:**

```text
Assume you are an environmental technology expert teaching
AI-Based Smart Waste Management to first-year engineering students.

Read the article below and prepare a summary of approximately
150 words.

Requirements:
- Explain the important concepts.
- Use simple and understandable language.
- Highlight the role of AI in waste management.

Article:
[Paste the article here]
```

### 3. Context Prompt

**Prompt Used:**

```text
You are creating educational content for an online learning
platform designed for undergraduate engineering students.

Read the following article on AI-Based Smart Waste Management
and produce a summary of approximately 150 words.

The summary should:
- Explain how AI helps in waste management.
- Cover the essential technologies and applications.
- Help students understand the topic easily.

Article:
[Paste the article here]
```

### 4. Constraint Prompt

**Prompt Used:**

```text
Summarize the following article on AI-Based Smart Waste
Management while following these conditions:

- Limit the summary to 150 words.
- Use clear and simple English.
- Avoid unnecessary technical terminology.
- Include only essential concepts.
- Preserve the original meaning.
- Make it suitable for undergraduate students.

Article:
[Paste the article here]
```

### 5. Output Format Prompt

**Prompt Used:**

```text
Summarize the following article on AI-Based Smart Waste
Management using the following format:

Title:
Introduction:
Working Principle:
Key Technologies:
1. Artificial Intelligence
2. Internet of Things (IoT)
3. Smart Sensors

Applications:
Advantages:
Limitations:
Conclusion:

Requirements:
- Approximately 150 words.
- Use simple language.
- Maintain a logical structure.
- Include relevant information from the article.

Article:
[Paste the article here]
```

## AI PLATFORM EVALUATION

### 1. ChatGPT + Basic Prompting

**Prompt Used:**

Summarize the AI-Based Smart Waste Management article in approximately 150 words using simple language.

**Summary Generated:**

AI-Based Smart Waste Management uses artificial intelligence and smart technologies to improve waste collection and disposal. Sensors installed in waste bins monitor waste levels and send information to a central system. AI analyzes this data to identify full bins and plan efficient collection routes. IoT technology connects devices and enables real-time monitoring. This system helps reduce unnecessary vehicle trips, save time, and improve waste collection. It also supports waste segregation and recycling. However, implementation costs, maintenance, and technical challenges can limit its use.

**Evaluation:**

| Criterion | Result |
|---|---|
| Accuracy | High |
| Coherence | Good |
| Simplicity | Excellent |
| Relevance | High |
| Readability | Excellent |

### 2. Gemini + Role Prompting

**Prompt Used:**

Act as an environmental technology expert and summarize the article on AI-Based Smart Waste Management for engineering students.

**Summary Generated:**

AI-Based Smart Waste Management is a modern approach that uses artificial intelligence to improve the collection, sorting, and disposal of waste. Smart sensors detect the amount of waste in bins, while IoT devices transfer this information to monitoring systems. AI processes the collected data and helps authorities plan better collection schedules and routes. This technology reduces manual monitoring, improves recycling, and supports cleaner cities. Although it provides several benefits, installation costs and maintenance requirements remain important challenges.

**Evaluation:**

| Criterion | Result |
|---|---|
| Accuracy | Very High |
| Coherence | Excellent |
| Simplicity | Good |
| Relevance | Excellent |
| Readability | Very Good |

### 3. Claude AI + Context Prompting

**Prompt Used:**

Prepare a student-friendly summary of the AI-Based Smart Waste Management article for an educational platform, highlighting its technologies, applications, and benefits.

**Summary Generated:**

AI-Based Smart Waste Management combines Artificial Intelligence, IoT, and smart sensors to make waste collection more efficient. Sensors monitor waste levels in bins and transmit real-time information through connected devices. AI analyzes the information to predict waste collection needs and optimize vehicle routes. The system is useful in smart cities, public waste collection, and recycling facilities. It helps reduce fuel consumption, manual effort, and environmental pollution. However, data management, infrastructure costs, and system maintenance are some of the challenges involved.

**Evaluation:**

| Criterion | Result |
|---|---|
| Accuracy | Excellent |
| Coherence | Excellent |
| Simplicity | Good |
| Relevance | Very High |
| Readability | Very Good |

### 4. Microsoft Copilot + Constraint Prompting

**Prompt Used:**

Summarize the article on AI-Based Smart Waste Management in approximately 150 words using simple English, including only the essential concepts, benefits, and limitations.

**Summary Generated:**

AI-Based Smart Waste Management uses AI, IoT, and sensors to improve waste collection. Sensors identify waste levels in bins and send information to a central system. AI analyzes the data and helps plan collection routes and schedules. This reduces unnecessary trips, saves fuel, and improves waste management. The technology also supports recycling and cleaner surroundings. However, high installation costs and maintenance requirements are some of its limitations.

**Evaluation:**

| Criterion | Result |
|---|---|
| Accuracy | High |
| Coherence | Good |
| Simplicity | Excellent |
| Relevance | High |
| Readability | Excellent |

### 5. ChatGPT + Output Format Prompting

**Prompt Used:**

Summarize the article using headings such as Introduction, Working Principle, Key Technologies, Applications, Advantages, Limitations, and Conclusion.

**Summary Generated:**

**Title: AI-Based Smart Waste Management**

**Introduction:** AI-Based Smart Waste Management uses modern technology to improve waste collection and disposal.

**Working Principle:** Sensors monitor waste levels and send information to a central system. AI analyzes the data and helps plan collection routes.

**Key Technologies:** Artificial Intelligence, IoT, and smart sensors.

**Applications:** Smart cities, waste collection, and recycling centres.

**Advantages:** Saves time, reduces fuel usage, and improves waste segregation.

**Limitations:** High installation costs and maintenance requirements.

**Conclusion:** AI-based waste management provides an efficient solution for developing cleaner and smarter cities.

**Evaluation:**

| Criterion | Result |
|---|---|
| Accuracy | High |
| Coherence | Excellent |
| Simplicity | Excellent |
| Relevance | Excellent |
| Readability | Excellent |

## COMPARISON TABLE

| AI Platform | Prompting Technique | Accuracy | Coherence | Simplicity | Readability |
|---|---|---|---|---|---|
| ChatGPT | Basic | High | Good | Excellent | Excellent |
| Gemini | Role | Very High | Excellent | Good | Very Good |
| Claude AI | Context | Excellent | Excellent | Good | Very Good |
| Microsoft Copilot | Constraint | High | Good | Excellent | Excellent |
| ChatGPT | Output Format | High | Excellent | Excellent | Excellent |

## OVERALL FINDINGS

| Prompt Structure | Key Strength | Limitation |
|---|---|---|
| Basic Prompt | Generates a quick general summary | May miss specific details |
| Role Prompt | Adapts the explanation to the target audience | May focus more on the assigned role |
| Context Prompt | Produces relevant and meaningful content | Requires sufficient context |
| Constraint Prompt | Controls length and language | Too many restrictions may omit details |
| Output Format Prompt | Produces organized and structured summaries | Depends on the specified format |

## FINAL RESULT

Different prompt structures were designed and evaluated across ChatGPT, Gemini, Claude AI, and Microsoft Copilot for summarizing a technical article on AI-Based Smart Waste Management System.

The experiment led to the following conclusions:

1. Basic Prompting generated a simple and general summary.
2. Role Prompting made the explanation more suitable for engineering students.
3. Context Prompting improved the relevance of the summary.
4. Constraint Prompting produced short and focused summaries.
5. Output Format Prompting generated well-organized and readable summaries.

**Conclusion:** Selecting appropriate prompt structures improves the clarity, accuracy, and organization of AI-generated summaries. Combining role, context, constraints, and output formatting can help generate more effective educational content.

---

**Note:** The generated summaries and evaluation ratings are illustrative examples. Actual outputs and evaluation results should be updated after testing the same source article on all four AI platforms.
