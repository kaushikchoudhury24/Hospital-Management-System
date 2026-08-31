class Patient:
    def __init__(self, name, age, disease):
        
        self.name = name
        self.age = age
        self.disease = disease

    def display_info(self):
        
        print(f"Patient: {self.name}, Age: {self.age}, Disease: {self.disease}")
        
         



patient1 = Patient("John Doe", 45, "Diabetes")
patient2 = Patient("Jane Smith", 30, "Hypertension")
patient3 = Patient("Emily Clark", 25, "Asthma")


patient1.display_info()
patient2.display_info()
patient3.display_info()
