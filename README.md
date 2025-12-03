# R Sandbox
## Quickstart
### Install

| Step                                                   | Incantation                                                                                   |
|--------------------------------------------------------|-----------------------------------------------------------------------------------------------|
| install R (arch)                                  | `yay -S r`                                                                               |
| install rv (arch)                                     | `curl -sSL https://raw.githubusercontent.com/A2-ai/rv/refs/heads/main/scripts/install.sh \| bash`                                                                           |
| install jupyterlab (arch)                                  | `yay -S jupyterlab`                                                                               |
| install pandoc (arch)                                  | `yay -S pandoc`                                                                               |
| Sync R packages                                  | From sandbox/: `rv sync`                                                                               |
| Register the kernel with Jupyter                                  | From sandbox/: `R -e 'IRkernel::installspec()'`                                                                               |

### Usage
Launch commands from sandbox/.
| Target             | Incantation                  |
|--------------------|------------------------------|
| repl               | `R`             |
| Launch JupyterLab               | `jupyter lab`             |
| Launch JupyterLab in background               | `jupyter lab --no-browser`             |
| Export RMarkdown to HTML               | `R -e "rmarkdown::render(input = 'hello_world.Rmd', output_dir = '../docs/')"`             |

## Swirl
"swirl teaches you R programming and data science interactively, at your own pace, and right in the R console!"

[https://swirlstats.com](https://swirlstats.com)
```
[don@nessie sandbox]$ R -q
rv repositories active!
repositories: 
  PPM: https://packagemanager.posit.co/cran/latest

rv libpaths active!
library paths: 
  /home/don/repos/r-sandbox/sandbox/rv/library/4.5/x86_64
  /usr/lib/R/library
> library("swirl")

| Hi! Type swirl() when you are ready to begin.

> swirl()

| Welcome to swirl! Please sign in. If you've been here before, use the same
| name as you did then. If you are new, call yourself something unique.

What shall I call you? 
```

## Useful Links
- R Project: [https://www.r-project.org](https://www.r-project.org)
- R Manuals: [https://cran.r-project.org/manuals.html](https://cran.r-project.org/manuals.html)
- Swirl (R Tutorial): [https://swirlstats.com/students.html](https://swirlstats.com/students.html)