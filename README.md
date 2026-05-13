class Developer:
    def __init__(self):
        self.name = "Vinod Bavage"
        self.role = ["Data Scientist", "Python Developer", "Web Developer"]
        self.location = "Hyderabad, Telangana, IN"
        self.tech_stack = {
            "data_science": ["Machine Learning", "Deep Learning", "EDA"],
            "web_dev": ["React", "TypeScript", "Tailwind CSS"],
            "backend": ["Python", "SQL", "MongoDB"]
        }
        self.projects_built = "10+ websites"
        
    def current_focus(self):
        return ["Advanced ML", "Model Deployment", "Full-Stack Development"]

dev = Developer()
print(f"Building: {dev.projects_built} and counting...")
