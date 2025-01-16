# Real-Time Voting System

## **Description**

Build a **real-time voting system** where users can create polls, vote, and view live results. Everything will run in the terminal, allowing multiple users to interact and update the poll dynamically.

---

## **Features**

1. **Poll Creation:**

   - Users can create polls with a title and multiple options.
   - Example: “What’s your favorite programming language?” with options: JavaScript, Python, Java, etc.

2. **Voting Mechanism:**

   - Users can vote by choosing an option by its index or name.
   - Prevent duplicate votes from the same user.

3. **Live Results:**

   - Display results dynamically as users vote.
   - Use text-based bar charts or percentages to show live updates.

4. **End Poll:**
   - Allow the poll creator to end the poll and display final results.

---

## **Challenges**

1. **Dynamic Updates:**

   - Update results in real-time without restarting the app.

2. **User Management:**

   - Track unique users to ensure each user votes only once.

3. **Error Handling:**
   - Handle invalid votes, duplicate votes, or empty polls gracefully.

---

## **Suggested Timeline**

### **Day 1: Poll Creation**

- Create a function to define a poll with a title and options.
- Store the poll data (e.g., title, options, votes) in an object.

### **Day 2: Voting System**

- Allow users to vote by choosing an option.
- Validate input to ensure the vote is valid.

### **Day 3: Live Results**

- Create a function to display live results.
- Update results dynamically as users vote.

### **Day 4: End Poll**

- Add the ability for the poll creator to end the poll.
- Display final results and a summary.

### **Day 5: Refinements**

- Handle edge cases, such as no votes, duplicate users, or invalid inputs.
- Make the results display visually appealing (e.g., ASCII bar chart).

---

## **Concepts to Use**

1. **Objects and Arrays:**

   - Use objects to store polls and their associated votes.
   - Use arrays to track users who have already voted.

2. **String Manipulation:**

   - Format results dynamically for live updates.

3. **Timers:**

   - Add optional time limits for voting.

4. **File Storage (Optional):**
   - Save poll data to a file so users can reload polls later.

---

## **Sample Gameplay Flow**

```
Welcome to the Real-Time Voting System!

1. Create Poll
2. Vote
3. View Results
4. End Poll
5. Exit

Choice: 1
Enter poll title: What’s your favorite programming language?
Enter options (comma-separated): JavaScript, Python, Java, C++

Poll created successfully!

---

Choice: 2
Vote on: What’s your favorite programming language?
Options:
1. JavaScript
2. Python
3. Java
4. C++
Enter your vote (1-4): 1
Vote recorded!

---

Choice: 3
Live Results:
JavaScript: ██████ 50%
Python: ██ 20%
Java: ██ 20%
C++: █ 10%
```

---

## **Advanced Features (Optional):**

- **Anonymous Polls:** Allow polls where the creator and voters remain anonymous.
- **Custom Rules:** Limit the number of votes per user or set time limits for polls.
- **Leaderboards:** Track the most popular poll topics.
