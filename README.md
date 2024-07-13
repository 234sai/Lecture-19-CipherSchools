# Lecture-19-CipherSchools
In this lecture i have learned about the address of the elements in c++ and using arrays and pointers and how to intilize them and how to assign them Understanding the address of elements is fundamental in C++ programming, especially when dealing with arrays, pointers, and dynamic memory allocation. This knowledge is crucial for efficient data structures and algorithms

#include <iostream>

int main() {
  
    int num1, num2, sum;
    
    std::cout << "Enter the first number: ";
    std::cin >> num1;
    
    std::cout << "Enter the second number: ";
    std::cin >> num2;
    
    sum = num1 + num2;
    
    std::cout << "The sum of " << num1 << " and " << num2 << " is " << sum << "." << std::endl;
    
    return 0;
}
