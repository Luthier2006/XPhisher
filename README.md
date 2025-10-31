[![Typing SVG](https://readme-typing-svg.herokuapp.com/?color=ff0000&size=35&center=true&vCenter=true&width=1000&lines=Attention!+⚠;We+are+not+responsible+for+misuse.)](https://git.io/typing-svg)

<h1 align='center'>XPhisher</h1>

<h1 align='center'>Responsible use and recommendations</h1>

Before using any material from this repository:

<p>Authorization: </p>

• obtain written authorization from the owner of the target environment (company, client, university). Document scope, duration, and success criteria.

<p>Test environment: </p>

• run examples only in isolated environments (virtual machines, laboratory networks) without connection to production systems.

<p>Do not collect real credentials: </p>

• set up educational landing pages that DO NOT request or store real passwords. To measure behavior, use test accounts created specifically for the exercise.

<p>Privacy and compliance: </p>

• follow local laws and internal policies (LGPD, GDPR or applicable legislation). Obtain approval from legal/compliance when appropriate.

<p>Responsible disclosure: </p>

• When publishing reports or samples, sanitize sensitive data and remove any identifiable information.

• Installation (analysis environment — for educational purposes only)

The steps below describe how to prepare a secure analysis environment. These commands do not activate or instruct you to execute attacks.

 → Create an isolated virtual machine (snapshot) with an operating system of your choice.

 → Install the necessary dependencies for analysis (interpreters, inspection tools, browsers in test mode).

 → Always review the content of the files before executing any script: read the code, check hashes and confirm the origin.

 → We strongly recommend using snapshots and initial restore after any lab run.

------------------------------------------------------------------------

<h1 align='center'>Good contribution practices</h1>

Contributions are welcome as long as they follow ethical and legal principles. Before opening PRs or issues, read and comply with these rules:

Only submit code and material that has defensive, educational, or research purposes. Avoid including artifacts that can be used operationally for attacks.

Provide clear description of the purpose and educational/research rationale for any sensitive material.

Include tests, documentation, and examples that demonstrate the safe use of the material.

For questions about acceptability, open an issue describing the case before submitting code.

-------------------------------------------------------------------------------------

<h1 align='center'>Security policy</h1>

If you find a vulnerability or sensitive content inadvertently posted, please contact the maintainer immediately and do not post details publicly until the issue is resolved. Use the contact channel below.

-------------------------------------------------------------------------------------

<h1 align='center'>License</h1>

This project is licensed under the GNU General Public License v3.0 (GPL‑3.0) — see the LICENSE file for the full text.
-------------------------------------------------------------------------------------

### Features

- Latest and updated login pages.
- Beginners friendly
- Multiple tunneling options
  - Localhost
  - Cloudflared
  - LocalXpose
- Mask URL support 
- Docker support

##

### Installation

- Just, Clone this repository -
  ```
  git clone --depth=1 https://github.com/htr-tech/zphisher.git
  ```

- Now go to cloned directory and run `zphisher.sh` -
  ```
  $ cd zphisher
  $ bash zphisher.sh
  ```

- On first launch, It'll install the dependencies and that's it. ***Zphisher*** is installed.

##

### Installation (Termux)
You can easily install zphisher in Termux by using tur-repo
```
$ pkg install tur-repo
$ pkg install zphisher
$ zphisher
```
### A Note : 
***Termux discourages hacking*** .. So never discuss anything related to *zphisher* in any of the termux discussion groups. For more check : [wiki](https://wiki.termux.com/wiki/Hacking)

##

### Installation via ".deb" file

- Download `.deb` files from the [**Latest Release**](https://github.com/htr-tech/zphisher/releases/latest)
- If you are using ***termux*** then download the `*_termux.deb`

- Install the `.deb` file by executing
  ```
  apt install <your path to deb file>
  ```
  Or
  ```
  $ dpkg -i <your path to deb file>
  $ apt install -f
  ```

##

### Run on Docker

- Docker Image Mirror:
  - **DockerHub** : 
    ```
    docker pull htrtech/zphisher
    ```
  - **GHCR** : 
    ```
    docker pull ghcr.io/htr-tech/zphisher:latest
    ```

- By using the wrapper script [**run-docker.sh**](https://raw.githubusercontent.com/htr-tech/zphisher/master/run-docker.sh)

  ```
  $ curl -LO https://raw.githubusercontent.com/htr-tech/zphisher/master/run-docker.sh
  $ bash run-docker.sh
  ```
- Temporary Container

  ```
  docker run --rm -ti htrtech/zphisher
  ```
  - Remember to mount the `auth` directory.

##

<details>
  <summary><h3>Dependencies</h3></summary>

<b>Zphisher</b> requires following programs to run properly - 
- `git`
- `curl`
- `php`

> All the dependencies will be installed automatically when you run **Zphisher** for the first time.
</details>

<details>
  <summary><h3>Tested on</h3></summary>

- **Ubuntu**
- **Debian**
- **Arch**
- **Manjaro**
- **Fedora**
- **Termux**
</details>

##

<h3 align="center"><i>:: Workflow ::</i></h3>
<p align="center">
<img src=".github/misc/workflow.gif"/>
</p>

------------------------------------------------------------------------------------

<h1 align='center'>Contact</h1>

<p align='center'>Maintainer: Luthier2006</p>
<p align='center'>E‑mail: luthier1611@gmail.com</p>
<p align='center'>GitHub: https://github.com/Luthier2006</p>

-------------------------------------------------------------------------------------

<h1 align='center'>Thanks</h1>

References and supporting materials: OWASP, academic literature on social engineering, awareness platforms (GoPhish) and documentation of safe practices.
