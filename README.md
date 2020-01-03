# bootsy

__bootsy__, named after Bootsy Collins, is a tool for bootstrapping various operating systems into the state that I desire. I.e., it does all the necessary stuff that makes sense to offload rather than try to remember every time a new machine needs provisioning. 

Why? For fun and learning myself a thing or two.

### Warning

Right now this project is in its infancy and I am the sole contributor/maintainer. Therefore, I wouldn't recommend relyinig on this until it (hopefully) becomes more established and stable. I'll do my best to keep improving it, but can't make any promises.

## Installation

This project is intended to be as cross-platform as I can make it, a prerequisite of which is an easy installation story. Installing __bootsy__ should require as little yak shaving as possible and depend on the minimal amount of pre-existing toolchains and software on the target machine.

Bootsy has only two required dependencies:

  1) `git`: required to download the project

  2) `sh`: required to install the project
  
So, execute the folling from your terminal _to install_:

```
git clone https://github.com/slynnda/bootsy.git && cd bootsy && chmod +x install.sh && ./install

```

That's it!