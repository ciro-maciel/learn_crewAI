# Learn: CrewAI

Welcome to the repository for learning how to use CrewAI, a powerful framework for AI-driven task automation. This repository serves as a resource for developers looking to integrate CrewAI into their workflows for building complex, scalable AI systems.

## What is CrewAI?

CrewAI is a framework designed for creating and managing AI-powered tools that work collaboratively. It enables the development of AI "crews" composed of specialized agents and tasks, allowing for sophisticated automation and coordination in various domains, and more, much more...

## About the Project

This project aims to provide a comprehensive introduction to CrewAI, covering the basics of setting up, configuring, and using the framework. It includes practical examples, step-by-step tutorials, and detailed explanations to help you get started.

### Requirements

- Python 3.8 or higher, see my Fast Course for [Learn: Python](https://github.com/ciro-maciel/learn_python)
- Poetry (Python package manager), see my Fast Course for [Learn: Poetry](https://github.com/ciro-maciel/learn_poetry)


#### OpenAI
[OpenAI](https://openai.com/) is an AI research organization focused on benefiting humanity.

**Generate an OpenAI API Key**

1. **Sign Up:** Create an account at [OpenAI](https://platform.openai.com/signup).
2. **Dashboard:** Go to the **Dashboard** and click **"API Keys"**.
3. **Create Key:** Click **"Create new secret key"**.
4. **Copy & Save:** Store the key securely.
5. **Optional: Store in `.env`**
    - Add to a `.env` file:

```env
OPENAI_API_KEY=your_api_key_here
```

**References**

- [OpenAI API Documentation](https://beta.openai.com/docs/api-reference/)
- [GPT-4o mining](https://openai.com/index/gpt-4o-mini-advancing-cost-efficient-intelligence/)
- [Pricing](https://openai.com/api/pricing/)


### Serper
[Serper](https://serper.dev) provides search engine data and SERP insights through an API, allowing developers to programmatically retrieve search results.

**Generate a Serper API Key**

1. **Sign Up:** Go to [serper.dev](https://serper.dev) and create an account.
2. **Access the Dashboard:** After logging in, head to your **Dashboard**.
3. **Generate API Key:** Find the **"API Keys"** section and click **"Generate new API key"**.
4. **Copy and Save:** Copy the key and store it securely.
5. **Optional - Store in `.env`:**
   - Add the key to a `.env` file in your project:

```env
SERPER_API_KEY=your_api_key_here
```

## Getting Started

To install CrewAI, first clone the repository and install the necessary dependencies:

```bash
$ git clone https://github.com/ciro-maciel/learn_crewAI.git
$ poetry install
$ poetry shell
```

### Running the Lessons

####  L2: Create Agents to Research and Write an Article

In this lesson, you will be introduced to the foundational concepts of multi-agent systems and get an overview of the crewAI framework.

```bash
$ python src/L2_research_write_article.py
```

#### L3: Multi-agent Customer Support Automation

In this lesson, you will learn about the six key elements which help make Agents perform even better:
- Role Playing
- Focus
- Tools
- Cooperation
- Guardrails
- Memory

```bash
$ python src/L3_customer_support.py
```

#### L4: Tools for a Customer Outreach Campaign

In this lesson, you will learn more about Tools. You'll focus on three key elements of Tools:
- Versatility
- Fault Tolerance
- Caching

```bash
$ python src/L4_tools_customer_outreach.py
```

#### L5: Automate Event Planning

In this lesson, you will learn more about Tasks.

```bash
$ python src/L5_tasks_event_planning.py
```

#### L6: Multi-agent Collaboration for Financial Analysis

In this lesson, you will learn ways for making agents collaborate with each other.

```bash
$ python src/L6_collaboration_financial_analysis.py
```

#### L7: Build a Crew to Tailor Job Applications

In this lesson, you will built your first multi-agent system.

```bash
$ python src/L7_job_application_crew.py
```


## References

- [Multi AI Agent Systems with crewAI](https://www.deeplearning.ai/short-courses/multi-ai-agent-systems-with-crewai/)
- [crewAI](https://www.crewai.com/)
- [crewAI Documentation](https://docs.crewai.com/)

## About the Author

This repository was created and is maintained by **Ciro Cesar Maciel**. I am a Software Engineer passionate about creating efficient and well-documented solutions. I am always looking for new tools and practices that can simplify and improve the development workflow.

In addition to this project, I have been working on other interesting projects related to automation, Artificial Intelligence (AI), browser extensions, and more. I am also beginning to teach what is necessary to learn Artificial Intelligence (AI), helping others to get started on their AI journey.

If you are interested in Software Development, Data Science, AI, or other tech topics, feel free to explore my GitHub profile and connect with me.

### How to Find Me:

- GitHub: [ciro-maciel](https://github.com/ciro-maciel)
- LinkedIn: [Ciro Cesar Maciel](https://www.linkedin.com/in/ciro-maciel/)
- Website: [ciro-maciel](https://www.ciro-maciel.click)

I am always open to new collaborations and projects. If you have an interesting idea or just want to exchange thoughts about development, don't hesitate to reach out!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
