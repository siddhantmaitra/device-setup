

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

OR

```sh
curl https://www.smaitra.com/archbox | bash
```

## Demo 
Quick demo run of the `setup.sh` script when everything is installed.
https://github.com/siddhantmaitra/device-setup/assets/65553994/cd1cff30-7294-452b-9e1a-c6afffe10e45







