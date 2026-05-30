EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

AIM:

To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

SCENARIO:

You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

1.Accuracy

2.Coherence

3.Simplicity

4.Speed

5.User experience

OUTPUT:

Scenario 1: Zero-shot Prompting<br>
prompt 1: Explain gravity in one simple line<br>
Ans: Gravity is the force that pulls objects toward each other, especially toward the Earth. (ChatGPT)
Ans: Gravity is the invisible force of attraction that pulls all objects with mass toward one another. (Gemini)
Ans: Gravity is the force that pulls objects with mass toward each other, which is why things fall to the ground and planets orbit stars. (Claude)
Ans: Gravity is the invisible force that pulls objects toward each other, keeping planets, stars, and us grounded. (Copilot)

Scenario 2: Few-shot Prompting
prompt 2: Example: Car – used for travel
Example: Phone – used for communication
Task: Laptop – used for what?
Ans: Laptop – used for computing and work tasks such as studying, coding, and creating documents. (ChatGPT)
Ans: Laptop – used for productivity and information. (Gemini)
Ans: Laptop – used for computing and work. (Claude)
Ans: Laptop – used for work, study, and entertainment. (Copilot)

Scenario 3: Chain-of-thought prompting
prompt 3: Explain step-by-step to find the LCM of 12 and 18
Ans: 1.Write the prime factors of each number
* 12 = 2 × 2 × 3 = 2² × 3
* 18 = 2 × 3 × 3 = 2 × 3²
2. Take the highest power of each prime factor
* Highest power of 2 → 2²
* Highest power of 3 → 3²
3. Multiply them together
* LCM = 2² × 3² = 4 × 9 = 36
LCM of 12 and 18 is 36 (ChatGPT)
Ans: To find the LCM (Least Common Multiple) of 12 and 18 concisely, use the Listing Multiples method:
List multiples of 12: 12, 24, 36, 48
List multiples of 18: 18, 36, 54
Identify the smallest match: The first number to appear in both lists is 36.
LCM = 36 (Gemini)
Ans: Step 1: Find the prime factorization of each number.
12 = 2 × 2 × 3 = 2² × 3
18 = 2 × 3 × 3 = 2 × 3²
Step 2: Identify all prime factors that appear in either number.
The prime factors are: 2 and 3
Step 3: For each prime factor, take the highest power that appears in either factorization.
Highest power of 2: 2² (from 12)
Highest power of 3: 3² (from 18)
Step 4: Multiply these highest powers together.
LCM = 2² × 3² = 4 × 9 = 36
Answer: The LCM of 12 and 18 is 36. (Claude)
Ans: Multiples of 12: 12, 24, 36, 48
Multiples of 18: 18, 36, 54
First common multiple: 36
Answer: The LCM of 12 and 18 is 36. (Copilot)

Scenario 4: Role-Based Prompting
prompt 4: I'm 10th standard school boy. Explain Quantum optics
Ans: Quantum optics is the study of light at a very small (atomic) level.
It explains that light is made of tiny energy packets called photons and can behave as both a wave and a particle.
This concept helps us understand technologies like lasers, optical fibers, and quantum communication. (ChatGPT)
Ans: 1. Light as "Packets"
In quantum optics, we don't just see light as a continuous beam. We treat it as being made of tiny, individual packets of energy called photons.
2. The Core Idea
It explores how these photons interact with atoms and subatomic particles. Think of it this way:
Classical Optics: Light is like a flowing river of water.
Quantum Optics: Light is like a stream of individual water droplets.
3. Key Concepts to Know
Quantization: Energy isn't continuous; it comes in specific "chunks."
Wave-Particle Duality: Light has a "split personality"—it acts as both a wave and a particle depending on how you measure it.
Photon Interference: Individual photons can interfere with themselves, leading to strange results that classical physics can't explain.
4. Real-World Uses
You already use the results of quantum optics every day!
Lasers: Precise beams of light used in surgery and barcode scanners.
Fiber Optics: High-speed internet sent via light pulses.
Quantum Computers: The future of super-fast computing. (Gemini)
Ans: What is Quantum Optics?
Quantum optics is the study of light at the smallest possible level - understanding light as tiny packets of energy called photons rather than just waves.
Key Idea:
You've learned that light behaves as a wave (like ripples in water). But quantum optics shows that light also behaves as particles (photons) - like tiny balls of energy. This is
called wave-particle duality.
Simple Example:
Think of a dim light bulb. Classical physics says light flows continuously like water from a tap. But quantum optics reveals that the light is actually made of billions of
individual photons shooting out one by one - so fast you can't see the gaps! (Claude)
Ans: Quantum optics is the study of light at the quantum level, where light is treated as tiny particles called photons and we explore how they interact with matter.
Quick Teacher-Style Breakdown 👨‍🏫
Light as photons: Instead of just waves, light is made of energy packets called photons.
Photon–matter interaction: Quantum optics looks at how these photons interact with atoms and molecules.
Applications: Used in lasers, quantum computers, secure communication, and even experiments on entanglement and teleportation.
Key idea: It connects quantum mechanics with optics, showing how the smallest units of light behave in surprising ways.

RESULT:

Above are the outputs which is given AI tools according to the following prompts such as zero-shot, few-shot, chain-of-thought and role-based.
