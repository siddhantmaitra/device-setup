

Ansible scripts to setup my EndeavourOS machines

## Usage

### Run playbook only
1. `git clone` the repository
2. `cd` into the project repository
3. run `ansible-galaxy install -r requirements.yml` in project root
4. run `ansible-playbook -v playbook.yml --ask-become-pass` in project root

### Full setup
- Uses `chezmoi` and `ansible` for complete setup
- Download and run this [script](https://github.com/siddhantmaitra/scripts/blob/main/working/setup.sh).


## Demo 
![demovid](assets/demo.mp4)


