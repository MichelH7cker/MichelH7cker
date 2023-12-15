```C++
#include <iostream>
#include <vector>
#include <string>

class AboutMe {
public:
    void myLanguages() {
        std::cout << "# Here my languages: \n"; 
        std::cout << "C/C++, Python, Java, bash \n" << std::endl;
    }

    void myMarkupLanguages() {
        std::cout << "# Here my markup languages: \n"; 
        std::cout << "LaTeX, markdown, XML, HTML \n" << std::endl;
    }

    void myInterests() {
        std::cout << "# Here my Interests: \n"; 
        std::cout << "Linux, Electromagnetism, Cyber Security, "
                     "Software Development, Algorithms \n" << std::endl;
    }

    void myLinks() {
        std::cout << "# Here my links: \n"; 
        std::cout << " * Linkedin: https://www.linkedin.com/in/michelheckerfaria/ \n"
                     " * Gmail: michel.hecker@usp.br \n" << std::endl;
    }

    void showBio() {
        std::cout << "# Here is my short bio: \n"; 
        std::cout << 
            "I'm currently studying computer engineering at USP. "
            "I live in São Carlos and am available to work remotely. "
            "I'm currently doing research with the applied electromagnetism group of "
            "the department of electrical and computer engineering (SEL - EESC). "
            "Oh... I'm a huge coffee lover \u2615 \n"
        << std::endl;
    }

    void sayHello() {
        std::cout << "# Hi there, my name is Michel Hecker Faria\n" << std::endl;
    }
};

int main() {
    // Instantiate the AboutMe class
    AboutMe myProfile;

    // Display information
    myProfile.sayHello();
    myProfile.showBio();

    // Call functions to display relevant information
    myProfile.myLanguages();
    myProfile.myMarkupLanguages();
    myProfile.myInterests();
    myProfile.myLinks();

    return 0;
}
```

<!--
**MichelH7cker/MichelH7cker** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
