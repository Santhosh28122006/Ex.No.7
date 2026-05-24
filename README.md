# Exno.7-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

# Name :Santhosh V
# Register no. 212224230251
# Aim: To develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced prompt designs and their corresponding outputs.

#AI Tools Required: 


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

# Procedure

## 1. Define Requirements
The assistant should:
- Manage tasks
- Schedule reminders
- Suggest wellness tips
- Respond to general queries

---

## 2. Create Prompts

### Basic Prompt
> "Create a simple task manager."

### Intermediate Prompt
> "Build a productivity assistant that can add tasks and schedule reminders."

### Advanced Prompt
> "Develop an AI productivity assistant that interacts naturally and adapts to user preferences."

---

## 3. Simulate User Interaction

```python
tasks = []

while True:
    user = input("You: ")

    if "add" in user:
        tasks.append(user)
        print("Assistant: Task added.")

    elif "show" in user:
        print(tasks)

    elif "wellness" in user:
        print("Assistant: Drink water and take breaks.")

    elif "exit" in user:
        break
```

---

# Expected Output

## Personal Productivity Assistant Features

### 1. Daily Task Manager
- Add and organize tasks
- Show pending tasks

### 2. Smart Scheduler
- Schedule reminders
- Detect overlapping events

### 3. Wellness Tips
- Suggest exercise and hydration reminders

### Example Interaction

```text
User: Add assignment submission tomorrow.
Assistant: Task added successfully.

User: Suggest a wellness tip.
Assistant: Take short breaks while working.
```

---


# Result: 
The lab exercise resulted in the creation of a prototype concept for a personal assistant powered by large language models. Students were able to:
 Understand how to tailor LLM prompts to real-life applications.
 Foster creativity by designing features suited to their personal or academic lives.
 Learn prompt engineering techniques for optimal interaction with AI tools.
 Experience the versatility and utility of generative AI in solving everyday problems.
