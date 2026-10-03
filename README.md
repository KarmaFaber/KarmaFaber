<!-- HEADER -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?color=0:1408d0,50:0860d0,100:08c4d0&height=220&section=header&text=Karma%20Faber&fontSize=32&type=waving&fontColor=ffffff&animation=fadeIn" alt="Karma Faber Header" width="100%"/>
  
  <h3>C / C++ Software Developer | Linux Systems, Networking & Concurrency</h3>

  <p>
    <a href="https://www.linkedin.com/in/mariaz-/">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/>
    </a>
    <img src="https://img.shields.io/badge/Focus-Systems%20%26%20Networking-000000?style=flat-square&logo=linux&logoColor=white" alt="Focus"/>
    <img src="https://img.shields.io/badge/Location-Madrid%2C%20Spain-lightgrey?style=flat-square&logo=googlemaps&logoColor=red" alt="Location"/>
  </p>
</div>

---

### 🛠️ Profile & Value Proposition

Software Developer specialized in **low-level systems programming (C/C++)**, POSIX APIs, and network protocol engineering. Trained through an intensive, project-driven curriculum at **42 Madrid** (+2,000 hours of practical engineering), implementing robust software from scratch without external high-level libraries under rigorous peer-review evaluations.

My technical approach combines low-level memory rigor (zero-leak tolerance verified with Valgrind) with over 8 years of prior professional background in regulatory compliance, technical auditing, and structured problem-solving.

* **Systems & Networking**: Raw sockets (`SOCK_RAW`), non-blocking I/O multiplexing (`epoll`/`poll`/`select`), and kernel signal management.
* **Concurrency & IPC**: Deterministic multi-threading with POSIX threads (`pthreads`), race-condition mitigation via mutexes, process trees (`fork`/`execve`), and anonymous pipelines.
* **Defensive Engineering & QA**: Development of custom test harnesses and automated scripts in Bash/C to stress parsers, detect memory corruption boundaries, and prevent edge-case regressions.

---

### 💻 Technical Stack

<table>
  <tr>
    <td><strong>Programming Languages</strong></td>
    <td>
      <img src="https://img.shields.io/badge/-C-007ACC?style=flat-square&logo=c&logoColor=white">&nbsp;
      <img src="https://img.shields.io/badge/-C++-007ACC?style=flat-square&logo=cplusplus&logoColor=white">&nbsp;
      <img src="https://img.shields.io/badge/-Bash-000000?style=flat-square&logo=gnu-bash&logoColor=white">&nbsp;
      <img src="https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white">
    </td>
  </tr>
  <tr>
    <td><strong>Systems & Networking</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black">&nbsp;
      <img src="https://img.shields.io/badge/Debian-A81D33?style=flat-square&logo=debian&logoColor=white">&nbsp;
      <img src="https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white">&nbsp;
      <img src="https://img.shields.io/badge/POSIX_API-3776AB?style=flat-square">&nbsp;
      <img src="https://img.shields.io/badge/Raw_Sockets-00599C?style=flat-square">&nbsp;
      <img src="https://img.shields.io/badge/I/O_Multiplexing-00599C?style=flat-square">&nbsp;
      <img src="https://img.shields.io/badge/pthreads-4A154B?style=flat-square">
    </td>
  </tr>
  <tr>
    <td><strong>QA, Testing & Scripting</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Bash_Scripting-000000?style=flat-square&logo=gnu-bash&logoColor=white">&nbsp;
      <img src="https://img.shields.io/badge/Custom_Test_Harnesses-24292e?style=flat-square">&nbsp;
      <img src="https://img.shields.io/badge/Valgrind-24292e?style=flat-square">&nbsp;
      <img src="https://img.shields.io/badge/GDB-3949AB?style=flat-square">&nbsp;
      <img src="https://img.shields.io/badge/AddressSanitizer-D32F2F?style=flat-square">
    </td>
  </tr>
  <tr>
    <td><strong>Toolchain & Infrastructure</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white">&nbsp;
      <img src="https://img.shields.io/badge/GNU_Make-000000?style=flat-square">&nbsp;
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">&nbsp;
      <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white">
    </td>
  </tr>
</table>

---

### 📊 Activity & Statistics

<div align="center">
  <table border="0">
    <tr>
      <td align="center" valign="middle">
        <img src="https://github-readme-stats.vercel.app/api?username=KarmaFaber&theme=tokyonight&show_icons=true&hide_border=true&count_private=true" alt="KarmaFaber Stats" />
      </td>
      <td align="center" valign="middle">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=KarmaFaber&theme=tokyonight&show_icons=true&hide_border=true&layout=compact" alt="Top Languages" />
      </td>
    </tr>
  </table>
  <br/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=KarmaFaber&theme=tokyonight&hide_border=true" alt="KarmaFaber Streak" />
</div>

---

### 📂 Engineering Portfolios & Repositories

#### 🏛️ [42_CommonCore (Systems & Software Monorepo)](https://github.com/KarmaFaber/42_CommonCore)
*Central monorepo containing systems programming, networking architectures, and modern C++ implementations:*
* **[webserv](https://github.com/KarmaFaber/42_CommonCore/tree/main/14_webserv)**: Non-blocking HTTP/1.1 server compliant with RFC 7230 using I/O multiplexing (`select`/`poll`/`epoll`), dynamic CGI execution, and custom config parsing. Written in C and C++. 
* **[minishell](https://github.com/KarmaFaber/42_CommonCore/tree/main/9_minishell)**: POSIX command interpreter with AST parsing, pipeline architecture (`pipe`/`dup2`), process trees (`fork`/`execve`), and asynchronous signal handlers.
* **[philosophers](https://github.com/KarmaFaber/42_CommonCore/tree/main/8_philosophers)**: Concurrency engine solving the Dining Philosophers problem with POSIX threads, fine-grained mutex isolation, and real-time microsecond clocks.
* **[C++ Modules (00–09)](https://github.com/KarmaFaber/42_CommonCore/tree/main/12_CPPs)**: Deep dive into OOP rigor, Orthodox Canonical Form (RAII), exception hierarchies, template metaprogramming, and STL time-complexity optimization ($O(N \log N)$).
* **[cub3D](https://github.com/KarmaFaber/42_CommonCore/tree/main/11_cub3D)**: 3D raycasting engine written in C applying DDA linear traversal, real-time matrix rendering, and boundary collision bounding.
* **[Inception](https://github.com/KarmaFaber/42_CommonCore/tree/main/13_inception)** & **Born2beRoot**: Multi-container infrastructure orchestration and Linux server security hardening (LVM with LUKS encryption, UFW, AppArmor).

#### 🌐 [42_OutCore (Low-Level Networking Suite)](https://github.com/KarmaFaber/42_OutCore)
*Advanced systems and network protocol utilities interfacing directly with Layer 3/4 network boundaries:*
* **[ft_ping](https://github.com/KarmaFaber/42_OutCore/tree/main/01_ft_ping)**: Custom network diagnosis utility using raw sockets (`SOCK_RAW`, `IPPROTO_ICMP`), manual RFC 1071 checksum calculation, and microsecond RTT statistics.
* **[ft_traceroute](https://github.com/KarmaFaber/42_OutCore/tree/main/02_ft_traceroute)**: Network path discovery tool manipulating Time-to-Live (`IP_TTL`) fields to trace intermediate gateways and process ICMP Time Exceeded packets.

#### 🧪 Dedicated Test Suites & QA Frameworks
* **[test_parse_webserv](https://github.com/KarmaFaber/test_parse_webserv)**: Automated stress-testing framework fuzzing configuration parsers with malformed tokens and broken scope boundaries via Bash.
* **[ft_printf_test](https://github.com/KarmaFaber/ft_printf_test)**: Differential test harness benchmarking formatting flags, pointer addresses, and integer overflows against system `glibc`.
* **[GetNextLine_test](https://github.com/KarmaFaber/GetNextLine_test)**: Boundary test suite stressing buffer memory allocations (`1B` to `10MB`) and file descriptor handling under continuous Valgrind auditing.

---

<!-- SNAKE GAME -->
<div align="center" style="margin-top: 20px;">
  <img src="https://github.com/7oSkaaa/7oSkaaa/blob/output/github-contribution-grid-snake.svg?" alt="Snake Game" width="100%"/>
</div>

<!-- FOOTER -->
<hr>
<div align="center" width="100" style="margin-bottom:20px">
  <img src="https://capsule-render.vercel.app/api?color=0:1408d0,50:0860d0,100:08c4d0&height=100&section=footer&fontSize=30&type=waving&fontColor=fefefe" alt="footer" />
</div>


<!--
USED:
1. Markdown:  https://github.github.com/gfm/
2. Icons: https://coolsymbol.com/
3. Header/Footer: https://github.com/kyechan99/capsule-render
4. GitHub streak: https://github-readme-streak-stats.herokuapp.com/demo/
5. Templates: https://github.com/durgeshsamariya/awesome-github-profile-readme-templates/blob/master/templates/Dum6o.md
6. Badges: https://shields.io
7. Stats: https://github.com/anuraghazra/github-readme-stats
9.Snake game: https://github.com/7oSkaaa/7oSkaaa/blob/output/github-contribution-grid-snake.svg
10. 42 badge:  https://github.com/oakoudad/badge42
-->
