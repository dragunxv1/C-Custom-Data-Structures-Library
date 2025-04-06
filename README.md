### ✅ **Project 1: C++ Custom Data Structures Library**
**Goal**: Implement `Vector`, `List`, `Stack`, and `Queue` from scratch in C++, without using STL containers.

#### 💡 Key Concepts:
- Dynamic memory management
- Templates
- RAII
- Pointers and references
- Object-oriented design

#### 🔧 Implementation Tasks:
- [ ] Create Visual Studio project. Empty project, configuration type has to be static library (.lib)
- [ ] Create a header and source file for each structure (`vector.hpp`, `list.hpp`, etc.)
- [ ] Implement basic operations:
  - **Vector**: `push_back`, `pop_back`, `resize`, `capacity`, `operator[]`
  - **List**: `push_front`, `push_back`, `remove`, `find`, `iterator`
  - **Stack**: `push`, `pop`, `top`, `empty`
  - **Queue**: `enqueue`, `dequeue`, `front`, `empty`
- [ ] Use dyanmic allocation to manage structure data, `new`, `delete`.
- [ ] Use constructor / destructor to manage the memory (RAII). Make sure to avoid leaks.
- [ ] Use templates so data structures are generic
- [ ] Implement copy constructor, move constructor, destructor (Rule of 3/5)
- [ ] Implement test project using the .lib to test your structures.
- [ ] Add test cases for each data structure
- [ ] (Optional) Add iterators for `Vector` and `List`

#### 🧪 Bonus Challenges:
- Add exception safety