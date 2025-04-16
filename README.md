Kubernetes Aliases for Faster Workflow

Hi, I'm Shivam Vishwakarma ([@devshivops]([https://github.com/devshivops](https://github.com/DEV-SHIV-OPS))).

Here are some useful Kubernetes `kubectl` aliases I use to speed up daily DevOps tasks. Add them to your `~/.bashrc`, `~/.zshrc`, or shell config file.

Basic Aliases

alias k='kubectl'
alias kgp='kubectl get pods'
alias kgs='kubectl get svc'
alias kgn='kubectl get nodes'
alias kga='kubectl get all'
alias kctx='kubectl config use-context'
alias kns='kubectl config set-context --current --namespace'
Resource Operations
alias kgd='kubectl get deployments'
alias kdp='kubectl describe pod'
alias kdd='kubectl describe deployment'
alias kdsvc='kubectl describe service'

Apply and Delete YAMLs
alias kaf='kubectl apply -f'
alias kdf='kubectl delete -f'

Debugging and Logs
alias kex='kubectl exec -it'
alias kl='kubectl logs'
alias klf='kubectl logs -f'

Namespace Utilities
alias kgns='kubectl get namespaces'
alias kcn='kubectl config set-context --current --namespace'

YAML Output and Resource Metrics
alias kdpoyaml='kubectl get pod -o yaml'
alias kdeployyaml='kubectl get deploy -o yaml'
alias ktop='kubectl top pods'
alias ktopn='kubectl top nodes'

How to Use
Paste the above aliases into your shell config file (~/.bashrc or ~/.zshrc) and run:
source ~/.bashrc

# or
source ~/.zshrc
This helps speed up your Kubernetes tasks and keeps your workflow efficient.
