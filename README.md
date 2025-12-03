This project demonstrates every single keyword in the C programming language across different standards (C89, C99, C11). Each keyword is shown with:
- Clear, practical code examples
- Explanation of usage and purpose
- Common pitfalls and best practices
- Standard-specific implementations

- C Keywords by Standard

C89/C90 (32 Keywords)
auto break case char const continue
default do double else enum extern
float for goto if int long
register return short signed sizeof static
struct switch typedef union unsigned void
volatile while

C99 Additions (5 Keywords)
_Bool _Complex _Imaginary inline restrict

C11 Additions (7 Keywords)
_Alignas _Alignof _Atomic _Generic _Noreturn
_Static_assert _Thread_local

Total: 44 Keywords**

## 🏗️ Project Structure
c-keyword-mastery/
├── src/ # Source code with comprehensive examples
├── examples/ # Individual keyword demonstration files
├── tests/ # Unit tests for all features
├── docs/ # Detailed documentation
├── include/ # Header files
├── scripts/ # Build and utility scripts
└── build/ # Build output directory

Build Instructions

### Prerequisites
- GCC or Clang compiler
- CMake (optional, for advanced builds)
- Make

### Simple Build
```bash
make

# Make sure you're in the right directory
pwd  # Should show: /home/sebastian/SSR/ALL_C_keywords

# Clean first
make clean

# Build
make

# Run
make run







