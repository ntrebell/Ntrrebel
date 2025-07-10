# Ntrrebel
🔧 Mod Menu Developer | C++ &amp; Lua Hacker | Passionate Coder 🚀


<h1 align="center">Hey 👋, I'm NTRxRebel</h1>

```cpp
#include <iostream>
#include <vector>
#include <string>

class NTRxRebel {
public:
    std::string mood = "Silent but Deadly 🔥";
    std::vector<std::string> skills = {"C++", "Lua", "Memory Patch", "Bypass Creator", "ESP Designer"};
    std::string favWeapon = "M416 | KAR98 🔫";
    bool detected = false;

    void Inject() {
        std::cout << "[+] Injecting Cheat as NTRxRebel..." << std::endl;
        std::cout << "[*] Skills Loaded: ";
        for (auto &s : skills) std::cout << s << ", ";
        std::cout << std::endl;
        std::cout << "[*] Mood: " << mood << std::endl;
        std::cout << "[+] Status: Undetected ✅" << std::endl;
    }

    void SelfDestruct() {
        std::cout << "[!] Cheat Unloaded by NTRxRebel 🧠" << std::endl;
        detected = true;
    }
};

int main() {
    NTRxRebel rebel;
    rebel.Inject();
    // Code goes here...
    rebel.SelfDestruct();
    return 0;
}
