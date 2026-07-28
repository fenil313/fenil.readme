class Developer:

    def __init__(self):
        self.name = "Fenil"
        self.username = "fenil313"
        self.role = "Python Django Full Stack Developer"

        self.frontend = [
            "HTML5", "CSS3", "JavaScript", 
            "React", "Tailwind CSS", "Bootstrap"
        ]

        self.backend = [
            "Python", "Django", "Django REST Framework"
        ]

        self.database = [
            "PostgreSQL", "MySQL", "MongoDB", "SQLite"
        ]

        self.tools = [
            "Git", "GitHub", "Linux", "Docker", "VS Code", "Postman"
        ]

        self.learning = [
            "Redis", "Celery", "AWS", "CI/CD", "Microservices"
        ]

    def __str__(self):
        return "Building scalable web applications 🚀"
