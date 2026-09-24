<!-- HEADER -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?color=0:1408d0,50:0860d0,100:08c4d0&height=220&section=header&text=Karma%20Faber&fontSize=32&type=waving&fontColor=ffffff&animation=fadeIn" alt="Karma Faber Header" width="100%"/>
  
  <h3>Junior Software Developer | 42 Madrid Student | C / C++ Systems & QA Automation</h3>
  
  <p>
    <a href="https://www.linkedin.com/in/mariaz-/">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/>
    </a>
    <img src="https://img.shields.io/badge/Status-42%20Madrid%20Student-000000?style=flat-square&logo=42&logoColor=white" alt="42 Madrid Student"/>
    <img src="https://img.shields.io/badge/Location-Madrid%2C%20Spain-lightgrey?style=flat-square&logo=googlemaps&logoColor=red" alt="Location"/>
  </p>
</div>

---

### 🛠️ Profile & Value Proposition
Junior Software Developer currently training at **42 Madrid**. Entering the tech sector (0 prior IT experience) with a strong, hands-on foundation in **low-level systems programming (C/C++)**, POSIX environments, and network protocols, backed by a previous professional background in administrative processes, technical auditing, and regulatory compliance.

- **Systems Foundations:** Low-level memory control (zero-leak tolerance), POSIX system calls, I/O multiplexing, concurrency (pthreads/mutexes), and network sockets.
- **QA & Testing Mindset:** Writing bespoke test harnesses in Bash to deliberately stress parsers, detect memory corruption, and cover edge cases before peer evaluations.
- **Monorepo:** All curriculum projects, modules, and exercises are centralized and documented in the [**42_School repository**](https://github.com/KarmaFaber/42_School).

---

### 💻 Technical Stack

| Category | Technologies & Tools |
| :--- | :--- |
| **Languages** | `C (C99/POSIX)` `C++ (OOP/STL)` `Bash Scripting` `TypeScript (backend)` `SQL` |
| **Systems & Networking** | `Linux (Debian/Ubuntu)` `POSIX API` `Sockets TCP/UDP` `Raw Sockets` `epoll / select` `pthreads` |
| **Testing & Debugging** | `Valgrind (Memcheck, Helgrind)` `GDB` `Custom Test Harnesses` `Postman / curl` `Defensive Coding` |
| **Tools & Environments** | `Git` `Docker` `Docker Compose` `Nginx` `Makefiles` |

---

### 🔬 Core 42 Madrid Projects

All individual modules and historical progress are cataloged in the [**42_School Monorepo**](https://github.com/KarmaFaber/42_School).

#### 🌐 Systems, Concurrency & Networking
- **[Webserv (C++)](https://github.com/KarmaFaber/42_School/tree/main/14_webserv)**
  - Non-blocking HTTP/1.1 server compliant with RFC 7230 using I/O multiplexing (`select`/`poll`/`epoll`).
  - Custom configuration parser, request routing (GET, POST, DELETE), CGI execution, and chunked transfer decoding.
- **[Minishell (C)](https://github.com/KarmaFaber/42_School/tree/main/9_minishell)**
  - POSIX-compliant command-line interpreter. Tokenizer, syntax parser, process lifecycle management (`fork`, `execve`), multi-pipes, redirections, and asynchronous signal handling.
- **[Philosophers (C)](https://github.com/KarmaFaber/42_School/tree/main/8_philosophers)**
  - Concurrent multi-threaded simulation solving the Dining Philosophers problem using `pthreads` and mutexes. Deadlock prevention and race condition elimination verified with Helgrind.
- **[ft_ping & ft_traceroute (C)](https://github.com/KarmaFaber/42_School/tree/main/oc_1_ft_ping)**
  - Low-level network utilities built with raw sockets (`SOCK_RAW`, `IPPROTO_ICMP`), custom packet construction, and manual RFC 1071 checksum implementation.

#### 🧪 Custom Test Suites & Validation (QA/Testing)
- **[test_parse_webserv (Bash)](https://github.com/KarmaFaber/test_parse_webserv)**
  - Automated stress test suite executing malformed configuration files and corrupted payloads against the HTTP server parser.
- **[ft_printf_test (Bash / C)](https://github.com/KarmaFaber/ft_printf_test)**
  - Automated differential test harness validating format specifiers, buffer boundaries, and return values against system `libc`.
- **[GetNextLine_test (Bash / C)](https://github.com/KarmaFaber/GetNextLine_test)**
  - Test framework testing arbitrary file descriptor reads, binary data, varying buffer sizes (`BUFFER_SIZE=1` to `10M`), and leak-free memory deallocation.

---

### 📊 Engineering Activity

<div align="center">
  <p align="center">
    <img src="https://github-readme-stats.vercel.app/api?username=KarmaFaber&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="KarmaFaber GitHub Stats" width="48%"/>
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=KarmaFaber&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" alt="KarmaFaber Top Languages" width="45%"/>
  </p>
</div>

<!-- FOOTER -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?color=0:1408d0,50:0860d0,100:08c4d0&height=80&section=footer&type=waving" alt="Footer" width="100%"/>
</div>