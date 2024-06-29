class Student:
    def __init__(self, name):
        self.name = name
        self.grades = {}

    def add_grade(self, subject, grade):
        self.grades[subject] = grade

    def calculate_average(self):
        return sum(self.grades.values()) / len(self.grades)

    def display_grades(self):
        print(f"Student: {self.name}")
        for subject, grade in self.grades.items():
            print(f"{subject}: {grade}")
        print(f"Average Grade: {self.calculate_average()}")

def main():
    student = Student(input("Enter student name: "))
    while True:
        subject = input("Enter subject (or 'q' to quit): ")
        if subject.lower() == 'q':
            break
        grade = float(input("Enter grade: "))
        student.add_grade(subject, grade)
    student.display_grades()
if __name__ == "__main__":
   main()
