### Hi there 👋

<!--
**akm6872/akm6872** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
#include <iostream>
#include <list> // Include the list header file

using namespace std;

int main() {
    // Create a list of integers
    list<int> mylist;

    // Add elements to the list
    mylist.push_back(10);
    mylist.push_back(20);
    mylist.push_back(30);

    // Iterate through the list and print its elements
    cout << "List elements: ";
    for (auto it = mylist.begin(); it != mylist.end(); ++it) {
        cout << *it << " ";
    }
    cout << endl;

    // Accessing elements by index is not supported in lists,
    // but you can iterate or use other methods to access elements.

    // Other operations such as pop_back(), push_front(), pop_front(),
    // insert(), erase(), clear(), etc., are also available for lists.

    return 0;
}
