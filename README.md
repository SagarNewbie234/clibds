# Data Structures Library in C
A comprehensive library implementing various data structures in C, including linked lists, stacks, queues, and trees.

## Table of Contents
- [Data Structures Library in C](#data-structures-library-in-c)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Features](#features)
  - [Contributing](#contributing)
  - [License](#license)

## Installation
Clone the repository:
```bash
git clone https://github.com/username/repo.git
cd repo
make
```

## Usage
To use the library, include `data_structures.h` in your project and link with `libdata_structures.a`.

Example of creating a stack:
```c
#include "data_structures.h"

int main() {
    Stack stack = create_stack();
    push(&stack, 10);
    int value = pop(&stack);
    free(&stack);
    return 0;
}
```

## Features
- Array-based and linked list-based stack implementation
- Support for infix, prefix, and postfix notation conversion
- Queue implementations with circular and priority queues

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your improvements.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

