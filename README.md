# Exno.7-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

# Date:24/05/2026
# Register no.212224230251
# Aim: To develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced prompt designs and their corresponding outputs.

#AI Tools Required: 
# AI Tools Required
- ChatGPT / OpenAI API
- Python
- VS Code or Jupyter Notebook


# Explanation: 
Prompt:
"Design a personal productivity assistant that can help manage daily tasks, schedule reminders, suggest wellness tips, and answer general queries. The assistant should interact using natural language and be adaptable to the user’s changing preferences over time."
Procedure:
1. Define the core requirements of a personal productivity assistant.
2. Identify and construct appropriate prompts for each task using an LLM (e.g., ChatGPT).
3. Simulate natural user interaction through a simple interface or command-line system.
4. Collect feedback or inputs from users and adapt responses accordingly.
5. (Optional) Integrate basic memory to simulate preference adaptation.
EXPECTED OUTPUT: - (attached the drive link)
Output (Example Response by LLM):
Personal Productivity Assistant Features:
1. Daily Task Manager:
o Accept tasks via natural language (e.g., "Remind me to call mom at 6 PM").
o Organize tasks by priority and deadline.
o Provide daily summaries and pending items.
2. Smart Scheduler:
o Schedule events and set reminders using contextual understanding.
o Notify user of overlapping appointments or free time slots.
3. Wellness Tips Generator:
o Suggest daily wellness advice (hydration, exercise, screen-time breaks).
o Adapt suggestions based on past user preferences and responses.

## Prompt
> "Design a personal productivity assistant that can help manage daily tasks, schedule reminders, suggest wellness tips, and answer general queries. The assistant should interact using natural language and adapt to user preferences over time."

---

# Procedure

1. Define the requirements of the productivity assistant.
2. Create prompts for task management, scheduling, and wellness suggestions.
3. Simulate user interaction using Python or a simple command-line interface.
4. Collect user feedback and improve responses.
5. Optionally store preferences for personalized suggestions.

---

# Example Python Code

```python
tasks = []

while True:
    user = input("You: ")

    if "add" in user.lower():
        tasks.append(user)
        print("Assistant: Task added successfully.")

    elif "show" in user.lower():
        print("Your Tasks:")
        for t in tasks:
            print("-", t)

    elif "wellness" in user.lower():
        print("Assistant: Drink water and take short breaks.")

    elif "exit" in user.lower():
        print("Assistant: Goodbye!")
        break
```

---

# Expected Output

## Personal Productivity Assistant Features

### 1. Daily Task Manager
- Add tasks using natural language
- Organize tasks by priority and deadline
- Show pending tasks

### 2. Smart Scheduler
- Schedule reminders and events
- Detect overlapping schedules

### 3. Wellness Tips Generator
- Suggest hydration and exercise reminders
- Provide screen-time break suggestions

---

# Example Interaction

```text
User: Remind me to call mom at 6 PM.
Assistant: Reminder added successfully.

User: Suggest a wellness tip.
Assistant: Take a 5-minute walk after long screen time.
```

---

# Conclusion
This project demonstrates how prompt engineering can be used to build an AI-powered productivity assistant capable of managing tasks, scheduling reminders, and providing personalized wellness suggestions.

# Result: 
The lab exercise resulted in the creation of a prototype concept for a personal assistant powered by large language models. Students were able to:
 Understand how to tailor LLM prompts to real-life applications.
 Foster creativity by designing features suited to their personal or academic lives.
 Learn prompt engineering techniques for optimal interaction with AI tools.
 Experience the versatility and utility of generative AI in solving everyday problems.
