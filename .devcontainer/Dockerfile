FROM mtnrbqcap/minideb-amaranth:0.3

# FROM mcr.microsoft.com/devcontainers/anaconda:0-3
# RUN conda install -n base conda-libmamba-solver \
#     && conda config --set solver libmamba \
#     && conda install -y python=3.8
#FROM condaforge/mambaforge

# Copy environment.yml (if found) to a temp location so we update the environment. Also
# copy "noop.txt" so the COPY instruction does not fail if no environment.yml exists.
#COPY exp-environment.txt .devcontainer/noop.txt /tmp/mm-tmp/
#COPY config/starship.toml .devcontainer/noop.txt /home/vscode/.config/
# RUN if [ -f "/tmp/mm-tmp/environment.yml" ]; then umask 0002 && /opt/conda/bin/conda env update -n base -f /tmp/conda-tmp/environment.yml; fi \
#     && rm -rf /tmp/conda-tmp
# [Optional] Uncomment this section to install additional OS packages.
# RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
#     && apt-get -y install --no-install-recommends <your-package-list-here>
