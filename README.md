# 👋 Hi, I'm Alex  

```cpp
//  ==============================
//   ⌐■-■   Alex - Self-Taught Dev
//  ==============================
//   Location: Redruth
//   Language: C++
//   Specialty: Graphics | Systems | Embedded (exploring)
//  ==============================
//
//  // TODO: Become graphics wizard 🧙
//  // TODO: Contribute to open-source C++ projects
//  // TODO: Write my own rendering engine
//

#include <iostream>
#include <vector>
#include <string>

struct Developer {
    std::string name     = "Alex";
    std::string location = "Redruth";
    bool self_taught     = true;

    std::vector<std::string> passions {
        "C++",
        "Graphics Programming",
        "Systems Programming",
        "Embedded Systems (exploring)"
    };

    void aboutMe() {
        std::cout << "Hi, my name is " << name << "." << std::endl;
        std::cout << "I live in " << location << "." << std::endl;
        std::cout << "I'm a self-taught developer who loves:" << std::endl;
        for (const auto& passion : passions) {
            std::cout << " - " << passion << std::endl;
        }
    }

    void currentFocus() {
        std::cout << "\nCurrent Focus:" << std::endl;
        std::cout << " - Strengthening my C++ skills through projects" << std::endl;
        std::cout << " - Diving into rendering pipelines & performance optimization" << std::endl;
        std::cout << " - Learning how hardware and embedded systems tick" << std::endl;
    }

    void techInterests() {
        std::cout << "\nTech Interests:" << std::endl;
        std::cout << " - Operating systems & compilers" << std::endl;
        std::cout << " - Game engines & rendering" << std::endl;
        std::cout << " - Microcontrollers & low-level tinkering" << std::endl;
        std::cout << " - Problem-solving with code" << std::endl;
    }
};

int main() {
    Developer me;
    me.aboutMe();
    me.currentFocus();
    me.techInterests();
    return 0;
}
