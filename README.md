# Multi-Agent Problem Solving with a Local LLM

This notebook demonstrates a simple multi-agent system for problem solving using a local Large Language Model (LLM). It utilizes Hugging Face's `transformers` library to load and interact with a pre-trained GPT-2 model.


## How it Works

1. **Define Agents:** The system consists of various agents, each with a specific role and instructions. Examples include a Coordinator, Math Expert, Fact Checker, and Creative Writer.

2. **Task Decomposition:** The Coordinator breaks down a complex task into smaller, manageable subtasks.

3. **Agent Selection:** For each subtask, the system identifies relevant agents based on the task's content.

4. **Debate (Optional):** If multiple relevant agents are identified, they engage in a debate to produce diverse perspectives on the subtask.

5. **Subtask Execution:** Each selected agent addresses the subtask using its unique expertise and instructions.

6. **Result Synthesis:** The Coordinator synthesizes the individual agent responses into a coherent and comprehensive solution.

7. **Process Logging and Explanation:** The system maintains a process log and generates a detailed explanation of how the task was solved.


## Example Usage

The notebook provides an example of how to use the system:
