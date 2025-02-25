# ansible-kt
Content for Ansible KT

```sh
# create and activate Python virtual env
python3 -m venv .pyenv
source ./pyenv/bin/activate

# install Ansible
pip install ansible

# install required Ansible roles
ansible-galaxy role install -r requirements.yaml

# exit Python virtual env
deactivate
```
