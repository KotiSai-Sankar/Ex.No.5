

# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

### Date: 
### Register No: 212222240111

# Aim: To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios.  Analyze the quality, accuracy, and depth of the generated responses 



### AI Tools Required: 
Copilot


## **Objective**  
- Understand how the same task can be refined into multiple prompting techniques: Zero-shot, Few-shot, Chain-of-Thought.  
- Compare naïve vs. basic prompts across different healthcare-related scenarios.  
- Evaluate outputs in terms of **quality, accuracy, and depth**.  


## **Selected Text Scenarios**  
1. Generating a creative story.  
2. Answering a factual question.    
3. Providing advice/recommendations.  


## **Scenario 1: Generating a Creative Story**  
**Naïve Prompt (Basic):**  
"Write a story about smart transportation in a city."

**Output**:  
"🚦 Smart City, Smooth Ride 🚦
In the futuristic city of Metrovia, transportation was powered by AI. Roads had sensors, traffic lights adjusted in real time, and self-driving electric buses called Autowaves moved like a swarm—changing routes based on demand, weather, and even social media buzz.
Citizens used the Pulse App to suggest improvements, track buses, and earn rewards for walking or biking. The system was so smart, it even rerouted traffic during emergencies and healed cracked roads with smart asphalt.
Metrovia wasn’t just fast—it was kind, green, and built around its people.
"

**Zero-Shot Prompt:**  
"Without any examples, write a short story about how a city improves traffic flow and commuter experience using smart transportation systems."  

**Output**:  
"The city of Liora faced daily traffic chaos. To fix it, leaders installed smart sensors, adaptive signals, and AI-driven routing. Vehicles, buses, and trains synced with real-time data. Commuters used a single app to plan trips, switch modes, and avoid delays. Roads adjusted lanes during peak hours. Public transport became faster, cleaner, and more reliable. Within months, traffic eased, pollution dropped, and people moved with ease."

**Few-Shot Prompt (2 Examples):**  
"Example 1: Real-time traffic sensors adjust signal timings to reduce congestion.  
Example 2: A mobile app helps commuters choose the fastest route based on live data.  
Now, write a new story about how smart transportation systems improve life in a city."    

**Output**:  
"In the city of Novara, traffic once drained time and energy. Then came smart upgrades: sensors tracked flow, signals adapted instantly, and commuters used an app to plan faster routes. Public transport synced with real-time data, reducing wait times. Roads became smoother, air cleaner, and people reached destinations calmly. Life moved better—because the city learned to move smart."

**Chain-of-Thought Prompt:**  
Step 1: A city faces daily traffic jams and long commute times.  
Step 2: Smart sensors and GPS data are used to monitor traffic flow.  
Step 3: Signal timings and public transport routes are adjusted dynamically.  
Step 4: Commuters receive live updates and route suggestions.  
Step 5: Write a story combining these steps.   

**Output:**
"The city of Elora struggled with traffic jams and long commutes. To fix this, smart sensors and GPS data began tracking vehicle flow. Signals adjusted in real time, and buses changed routes based on demand. Commuters got live updates and smarter route suggestions. Soon, travel became faster, smoother, and stress-free."

---

## **Scenario 2: Answering a Factual Question**  
**Naïve Prompt:**  
"How does online education help students?"

**Output:**
"Online education helps students by making learning more flexible and accessible. They can study from anywhere and choose their own schedule, which is great for balancing other responsibilities. It also offers a wide variety of courses from different institutions, often at lower costs than traditional education. Students gain digital skills and learn to manage their time better, while those in remote areas or with special needs benefit from easier access to quality education. Overall, it supports independent learning and opens up new opportunities for personal and academic growth."

**Zero-Shot Prompt:**  
"Without any examples, explain how online learning supports students in their studies."

**Output:**
"Online learning supports students by offering flexible access to lessons and materials, allowing them to study at their own pace and convenience. It helps them stay organized, track progress, and focus on individual academic goals. The digital format encourages independent learning and builds time management skills. With interactive tools and varied content formats, students can better understand concepts and reinforce their knowledge. Overall, online learning creates a supportive environment that promotes self-growth, academic success, and adaptability in a changing world."

**Few-Shot Prompt (2 Examples):**  
"Example 1: Online classes allow students to learn from home.  
Example 2: Recorded lectures help students review lessons anytime.  
Now, explain another way online education benefits students."  

**Output:**
"Online education helps students develop self-discipline and time management skills. By organizing their own study schedules and meeting deadlines independently, students build habits that support long-term academic and personal success."

**Chain-of-Thought Prompt:**  
Step 1: Students need flexible access to learning materials.  
Step 2: Online platforms provide lessons, assignments, and discussions.  
Step 3: Students can learn at their own pace and schedule.  
Step 4: This flexibility improves accessibility and understanding.  
Step 5: Explain this process in detail.  

**Output:** 
"Online education supports students by creating a flexible and accessible learning environment. It begins with the need for students to access study materials without time or location constraints. Online platforms meet this need by offering digital lessons, assignments, and discussion forums that are available anytime. This setup allows students to engage with content at their own pace, choosing when and how to study based on their personal schedules and learning preferences. As a result, students can revisit complex topics, pause and reflect, or accelerate through familiar material. This level of flexibility not only makes education more accessible to a wider range of learners but also enhances their understanding by allowing them to learn in ways that suit them best."

---


## **Scenario 3: Providing Advice/Recommendations**  
**Naïve Prompt:**  
"Give advice on improving productivity in the workplace."

**Output:**
"Improving workplace productivity starts with setting clear goals and organizing tasks by priority. When employees know what to focus on, they work more efficiently. Time management and short breaks help maintain energy and concentration. Good communication and the right tools make collaboration smoother and reduce delays. Supporting employee well-being and encouraging skill development also boost motivation and performance. Together, these practices create a more productive and positive work environment."

**Zero-Shot Prompt:**  
"Without examples, suggest how companies can boost employee productivity."

**Output:**
"Companies can boost employee productivity by creating a clear and supportive work environment. This includes setting well-defined goals, aligning tasks with employee strengths, and providing regular feedback. Encouraging open communication and collaboration helps reduce misunderstandings and fosters teamwork. Offering opportunities for skill development and recognizing achievements can increase motivation and engagement. Additionally, ensuring a healthy work-life balance and providing the right tools and resources enable employees to perform efficiently and stay focused."

**Few-Shot Prompt (2 Examples):**  
"Example 1: Introduce flexible working hours to reduce stress.  
Example 2: Use project management tools to track progress.  
Now give three more ways companies can enhance workplace productivity."  

**Output:**
"Example 3: Encourage regular feedback and communication to keep teams aligned and motivated.  
Example 4: Provide training and development opportunities to improve skills and efficiency.  
Example 5: Create a positive work environment that supports employee well-being and focus.  
"

**Chain-of-Thought Prompt:**  
"Step 1: Identify common workplace challenges.  
Step 2: Think of practical solutions for each issue.  
Step 3: Suggest specific methods to apply those solutions.  
Step 4: Explain the potential benefits of each method.  
Step 5: Provide actionable recommendations."  

**Output:**  
"To boost workplace productivity, companies should identify common challenges like poor communication or low engagement, develop practical solutions such as improving workflows or offering training, apply these through clear methods like using collaboration tools or flexible schedules, explain how each method enhances focus and efficiency, and finally, implement actionable steps like setting clear goals, recognizing achievements, and supporting employee well-being."  

---

## **Evaluation Table (Quality, Accuracy, Depth: 1–5 scale)**  

| Scenario                       | Prompt Type       | Quality | Accuracy | Depth |  
|--------------------------------|-----------------|---------|---------|-------|  
| Creative Story                  | Naïve            | 4       | 3       | 2     |  
|                                | Basic/Refined    | 5       | 5       | 5     |  
| Answering Factual Question      | Naïve            | 3       | 3       | 4     |  
|                                | Basic/Refined    | 5       | 5       | 5     |  
| Providing Advice/Recommendations| Naïve            | 4       | 3       | 2     |  
|                                | Basic/Refined    | 5       | 5       | 5     |  

---

## **Analysis:**  
- **Basic/Refined prompts consistently generate higher quality, more accurate, and deeper responses** compared to naïve prompts.  
- Naïve prompts work but often produce vague or incomplete answers.  
- Chain-of-Thought prompting provides structured reasoning, improving clarity and depth.  
- Few-shot prompts improve performance when examples are provided, especially for complex tasks like summarization or advice.  
- Zero-shot prompts work moderately but can miss context or detail if the instruction is too broad.  



## RESULT:

The prompts for all scenarios were executed successfully using different prompting patterns.  
Copilot generated meaningful responses, and refined prompts provided clearer and more complete outputs than naive prompts.

