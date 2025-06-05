class AboutMe:
    def __init__(self):
        self.name = "Venus Kareen"
        self.role = "DevOps Engineer | Cloud Enthusiast | IT Student"
        self.pronouns = ["She", "Her"]
        self.languages = ["Bash", "Python", "Go"]
        self.frameworks = ["Terraform", "Ansible"]
        self.tools = ["Git & GitHub", "Docker", "Kubernetes", "Jenkins", "MySQL"]
        self.cloud = ["AWS (Certified)", "Azure", "Google Cloud"]
        self.learning = ["CI/CD", "Monitoring & Logging", "Infrastructure as Code (IaC)", "DevSecOps"]

    def say_hello(self):
        print("Thanks for stopping by!")

me = AboutMe()
me.say_hello()


