```cpp
#include <iostream>
#include <string>

class BlackByteOS {
public:
    std::string founder = "@voipcore";
    std::string coFounder = "@cz7qu";
    std::string discord = ".gg/cybr";

    void introduce() {
        std::cout << "Founder of " << founder << " with " << coFounder << std::endl;
        std::cout << "Join the dc: " << discord << std::endl;
    }
};

int main() {
    BlackByteOS bio;
    bio.introduce();
    return 0;
}
```
