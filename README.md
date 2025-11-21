# 🧮 Go Arithmetic Operations

![Go](https://img.shields.io/badge/Go-1.20+-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)

A tiny Go example demonstrating basic arithmetic operations (addition, subtraction, multiplication, division, modulus). This project is intended as a simple learning resource for beginners.

---

## Table of Contents

- [Project Structure](#project-structure)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Example Code](#example-code)
- [Example Output](#example-output)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)

---

## 📂 Project Structure

go-arithmetic-operations/  
├── test2.go  # Main Go file with arithmetic operations  
└── README.md # Project documentation

---

## 🚀 Features

- Addition: add two integers
- Subtraction: subtract one integer from another
- Multiplication: multiply two integers
- Division: divide two integers (floating-point result)
- Modulus: remainder of integer division
- Simple, readable example for learning purposes

---

## ⚙️ Prerequisites

- Go 1.20+ installed: https://golang.org/dl/

---

## 🛠️ Usage

1. Clone the repository:

```bash
git clone https://github.com/Achintha-999/go-arithmetic-operations.git
cd go-arithmetic-operations
```

2. Run the program:

```bash
go run test2.go
```

(or build an executable)

```bash
go build -o arithmetic
./arithmetic
```

---

## 📄 Example Code

This is the main program (test2.go):

```go
package main

func main() {
    x := 10
    y := 4

    add := x + y
    sub := x - y
    mul := x * y
    div := float32(x) / float32(y)
    mod := x % y

    println("Addition:", add)
    println("Subtraction:", sub)
    println("Multiplication:", mul)
    println("Division:", div)
    println("Modulus:", mod)
}
```

---

## 📟 Example Output

When you run the program you should see something like:

```
Addition: 14
Subtraction: 6
Multiplication: 40
Division: 2.5
Modulus: 2
```

---

## 🤝 Contributing

Contributions, issues and feature requests are welcome. Feel free to:
- Open an issue for suggestions or bugs
- Submit a pull request with improvements

---

## 📜 License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## 🙏 Acknowledgements

Thanks to the Go community for great docs and resources that make learning easy.

---

## 📬 Contact

GitHub: https://github.com/Achintha-999

Happy coding! 🚀

