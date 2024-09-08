
# Install the prerequisite applications

- https://github.com/computate-org/computate_potrace

# Install potrace

### Create a directory for the ansible role. 

```bash
install -d ~/.ansible/roles/computate.computate_potrace
```

### Clone the potrace ansible role. 

```bash
git clone git@github.com:computate-org/computate_potrace.git ~/.ansible/roles/computate.computate_potrace
```

## Run the potrace ansible playbook to install the application locally. 

```bash
cd ~/.ansible/roles/computate.computate_potrace
ansible-playbook install.yml
```

