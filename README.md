### Hello there 👋

```cpp
#include <iostream>
#include <vector>
#include <string>

class SoftwareEngineer {
public:
    SoftwareEngineer() {
        name = "Nghia (Matt) Nguyen";
        description = "Software Engineer/Student by day, sleeping by night";
        school = "Drexel University";
        most_used = {".js", ".cs", ".py", ".cpp"}
    }

    void say_hi() {
        std::cout << "Welcome, hope you find something interesting in here." << std::endl;
    }

private:
    std::string name;
    std::string role;
    std::string school;
    std::vector<std::string> language_spoken;
    std::vector<std::string> most_used_languages
};

int main() {
    SoftwareEngineer me;
    me.say_hi();

    return 0;
}
```
