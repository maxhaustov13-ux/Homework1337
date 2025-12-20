# LLM Usage Report (LLM.md)

## LLMs used during homework

### 1) ChatGPT (OpenAI)
- Interface: web chat
- Purpose of usage:
  - Understanding homework requirements (Git, branches, workflow, Pull Request).
  - Creating a minimal working Snakemake workflow (Snakefile and bash script).
  - Debugging issues in Debian/Docker environment (pip errors, virtual environments).
  - Writing a clear and reproducible README with step-by-step instructions.

## How I worked with the LLM
1. I described the task in simple words and provided full context:
   - homework description from the teacher;
   - terminal commands I executed;
   - full error messages from the console.
2. I followed the step-by-step instructions suggested by the LLM.
3. If something did not work, I sent the new error/output back to the LLM.
4. After the workflow worked correctly, I asked the LLM to help structure the final README.

## Example prompt to the LLM
**Prompt:**
> Please explain what I need to do like I am 5 years old.
> Give me a very clear step-by-step order with exact commands

## Example response from the LLM
**Short excerpt of the response:**
1. Open the terminal.
2. Go to the project folder.
3. Create a virtual environment.
4. Activate the virtual environment.
5. Install Snakemake.
6. Run the workflow.
7. Check the output file to see the result.

Each step was explained in simple words and in the correct order.


---

### Human - LLM interaction model

```md
```mermaid
graph TD
    A[Confusion] --> B[Ask LLM]
    B --> C[Simple explanation]
    C --> D[Run command]
    D --> E{Works?}
    E -- Yes --> F[Continue]
    E -- No --> B
