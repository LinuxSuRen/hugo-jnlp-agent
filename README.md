# hugo-jnlp-agent

# Run

You can running a Jnlp-Agent use below cmd line:

`docker run --rm surenpi/hugo-jnlp-agent hugo help`

# Kubernets Plugin

You can add this agent to your kubernetes plugin, like:

```
Name=jnlp
Docker image=surenpi/hugo-jnlp-agent
Command to run=
Arguments to pass to the command=
Allocate pseudo-TTY=false
```
