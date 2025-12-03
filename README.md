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