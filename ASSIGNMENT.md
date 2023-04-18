# Evolution of the C++ Programming Language

## Introduction

<img align="right" src="images/stroustrup.jpg" alt="Bjarne Stroustrup Headshot"/> The C++ language begins with Bjarne Stroustrup. In 1979, he worked with the _Simula_ language for his Ph.D. thesis. The particular variant of _Simula_ that he worked with was _Simula 67_ which is known to be the first language to support the Object Oriented Programming paradigm. This paradigm inspired him to begin work on a language that took everything about the C language and then add classes to the language [1]. Creatively, it was called _C with Classes_ and had 3 goals: 

1. It should be organized with classes and inheritance.
2. It will have little to no performance hit relative to the _C_ language.
3. It could be used for any application that _C_ could be used for (yes, even the bad stuff) [2].

In 1983, the _C with Classes_ name was officially changed to _C++_, but it wasn't until 1985 that the first implementation and compiler were released [2]. The compiler, called CFront, was actually written in _C with Classes_ and additionally translated the compiled _C with Classes_ programs into standard _C_ code [1].

The language did not yet have a formal standardization, but two references were published to aid programmers in its use. _The C++ Programming Language_ in 1985, followed by the _The Annotated C++ Reference Manual_ in 1990. Both of these references influenced the first international standard for C++: ISO/IEC 14882:1998 that arrived in 1998 (informally C++98) [1].

This language took the imperative _C_ language and added classes to it to provide better organization and powerful OOP concepts that continued to evolve.

## Evolution and Continued Use

After C++98 standardization, the next milestone in the evolution of the language was, of course, to fix problems with the C++98 standardization itself. In 2003, the committee revised the C++98 standard to fix various problems and called the new language C++03. Updates to the language standard continued through 2011. These updates included more fixes for bugs and were often followed by a new release of the language. 

Between 2011 and 2019 new features were added such as lambda expressions, polymorphic lambdas, delegating constructors, uniform initialization syntax, hexadecimal floating point literals, type deduction, and decltype. The latest version of C++ was finalized in February 2020 and approved in September 2020. It is officially known as _ISO International Standard ISO/IEC 14882:2020(E) – Programming Language C++_. The latest version of C++ is expected to released sometime in 2023. 

C++ is still being used to this day and can be found in many different business sectors. C++ is fast and interfaces more closely with hardware which is an advantage when rendering graphics and processing data. The language also provides powerful features like multi-threading and concurrency which makes it a good candidate for distributed computing. Two examples of tools written in C++ are the mySQL database and the Mozilla Firefox web browser.

There are tradeoffs to be made when selecting the C++ language, but as shown in the next section C++ is still going strong and will continue to be used well into the future.          

## Language Trade-off's

The most important advantage of C++ is the inclusion of the object oriented programming paradigm, a programming model that helps organize the design and data of a program. The Standard Library portion of the language is portable, which allows a program to run on different computer platforms like Windows, MacOS, and Linux. However, not all libraries within the ecosystem are cross-platform. This can make selecting the right library difficult for the project. Luckily in 2011, the Boost Organization recognized this issue and "provides free peer-reviewed portable C++ source libraries" to the C++ community [6].

C++ provides Software Engineers control over how memory is managed and allocated. Although powerful, this feature can become a liability because bugs, like memory leaks, are easier to introduce into the code base.

Another powerful but tricky feature is pointers. Pointers provide efficiency and are integral to the language, but are a difficult concept to understand. Accidental misuse of pointers is detrimental to the program in that they may consume a lot of memory. This issue can be amplified if memory is allocated incorrectly. To top all of this off, C++ lacks a native garbage collector which means that an engineer must handle many memory management tasks themselves.

Speed is one of the top reasons that C++ is selected for certain projects. It is closer to the hardware than other languages due to several features including some we talked about above. Because of this, some portability, some convenience, and some simplicity is sacrificed to give engineers the control and flexibility required to produce speedy results.

## Conclusion

C++ shows strong signs of remaining a top choice language for the medium to long term future, especially for applications that prioritize quick execution and low latency code (such as games and server software) [3]. The ISO task force that publishes C++ language specifications recently approved a C++20 standard and is already working on the next version, C++23.  

Many valid criticisms of the language have been made by prominent figures in the computer science field (such as Linus Torvalds [4] and Donald Knuth [5]), mostly concerned with the lack of orthogonality and vast complexity of C++.  However, support for the use of C++ continues to remain strong because of the large body of existing code and the prevalence of skilled programmers throughout the software engineering workforce. C++ should continue to be a preferred choice for mainstream applications for years to come.  

## Timeline

![image](https://user-images.githubusercontent.com/53946628/232848877-38ef301b-d550-46c0-9ab6-79761b2e9a4f.png)


## Sources

[1] Albatross, "History of C++ - C++ Information," cplusplus.com. https://cplusplus.com/info/history/ (accessed Apr. 11, 2023).

[2] R. W. Sebesta, Concepts of Programming Languages. Addison-Wesley Longman, 2010.

‌[3] Educative.io, "Learn C++ for 2022," 2021. Accessed: Apr. 16, 2023 [Online]. Available: https://www.educative.io/blog/learn-cpp-for-2022.

[4] L. Torvalds, "Re: [RFC] Convert builin-mailinfo.c to use The Better String Library," lwn.net. Accessed: April 16, 2023 [Online]. Available: https://lwn.net/Articles/249460/.
‌

[5] J. L. Vossen, "An Interview with Donald Knuth," Dr. Dobb's Journal, Nov. 30, 1999. Accessed: Apr. 16, 2023 [Online]. Available: https://www.drdobbs.com/architecture-and-design/an-interview-with-donald-knuth/228700500.

[6] "Boost C++ Libraries," Boost.org, 2019. https://www.boost.org/ (accessed Apr. 16, 2023).
