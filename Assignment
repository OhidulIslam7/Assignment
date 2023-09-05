class Person {
  String firstName;
  String lastName;

  Person(this.firstName, this.lastName);

  void display() {
    print("First Name = $firstName");
    print("Last Name = $lastName");
  }
}

class Teacher extends Person {
  int numberOfPublication;

  Teacher(String firstName, String lastName, this.numberOfPublication)
      : super(firstName, lastName);

  @override
  void display() {
    super.display();
    print("Number Of Publication = $numberOfPublication");
  }
}

class Student extends Person {
  double cgpa;

  Student(String firstName, String lastName, this.cgpa) : super(firstName, lastName);

  @override
  void display() {
    super.display();
    print("CGPA = $cgpa");
  }
}

void main() {
  List<Person> people = [
    Teacher("Babul", "Mridha", 5),
    Teacher("Isteak", "Ahmed", 10),
    Student("Sapon", "Ahmed", 3.14),
    Teacher("Amran", "Hasan", 7),
    Student("Jannat", "Akter", 4.19),
  ];

  for (var person in people) {
    person.display();
    print(""); // Add a blank line to separate each person's information
  }
}
