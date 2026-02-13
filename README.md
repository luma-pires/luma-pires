```python
@dataclass
class Me:
    name: str = 'Luma Pires'
    location: str = 'São Paulo - SP'
    role: str = 'Backend Engineer (AI/LLM)'
    linkedin: str = 'https://www.linkedin.com/in/lumapires/'

    tools: List[str] = (
        'Python', 'SQL', 'FastAPI', 'Docker', 'Kafka',
        'LangChain', 'LangGraph', 'CrewAI', 'Web Scraping'
    )

    languages: List[str] = ('Portuguese', 'English')

    education: List[str] = (
        'MSc in Computer Engineering (in progress) - POLI/USP (2024–present)',
        'BSc in Economics and Controllership - FEARP/USP (2019–2023)'
    )
```
